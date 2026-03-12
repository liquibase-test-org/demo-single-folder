# liquibase-test-org/demo-single-folder

[![pipeline status](https://github-deployer.liquibase.com/api/badge/repo_66af3989)](https://github-deployer.liquibase.com/projects/repo_66af3989/pipeline)

> **This repository is managed by [Liquibase Secure for GitHub](https://github-deployer.liquibase.com).**

## Table of Contents

- [Overview](#overview)
- [What the workflows do](#what-the-workflows-do)
- [Important](#important)
- [Documentation](#documentation)

## Overview

This repository contains database changelogs and automated workflows managed by Liquibase Secure. Changes are authored, validated, and deployed through the Liquibase Secure UI.

## What the workflows do

| Workflow | Purpose |
|----------|---------|
| `liquibase-check.yml` | Runs policy checks on pull requests |
| `liquibase-deploy.yml` | Deploys changes to the target environment on merge |
| `liquibase-promote.yml` | Promotes a deployment artifact to the next environment |
| `liquibase-rollback.yml` | Rolls back deployed changesets |
| `liquibase-test-connection.yml` | Tests database connectivity |

## Important

**Do not manually edit files under `.github/workflows/liquibase-*`.** These workflows are generated and maintained by Liquibase Secure. Manual changes will be overwritten.

To manage your database changes, use the Liquibase Secure app:

[Open Liquibase Secure for GitHub](https://github-deployer.liquibase.com)

## Documentation

- [Liquibase Documentation](https://docs.liquibase.com)
