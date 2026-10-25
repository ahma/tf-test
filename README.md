# GH1 GitHub validation lab

Disposable test content for validating the customer-owned GitHub content-source adapter while retaining the platform Gitea executor.

## Current state

This repository is a lab target only. The implementation passed local synthetic checks; live GitHub validation and independent review are still pending. Original P9 acceptance remains incomplete.

The `gh1/lab-base` branch provides an initial commit and a branch name containing a slash for bounded API checks. No application code, workflow, infrastructure configuration or credentials are included.

## Execution boundaries

Record exact test actions and evidence before claiming a check passes. App installation, permissions, token production and protection changes require a separately specified setup. No infrastructure deployment or automatic workflow is configured.

Never commit credentials, private keys, token files, authorization headers or private runtime evidence.
