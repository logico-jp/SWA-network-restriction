# SWA-network-restriction

- This repository is a sample one to verify `networking.allowedIpRange` in `staticwebapp.config.json`.

## Prerequisites

- Azure Static Web Apps
    - Standard plan is mandatory (Free plan is out of support).

## Configuration

### (1) GitHub

- Create branch ("main", "dev" and "staging").

### (2) Azure

- Create Static Web Apps (Standard plan)
- Configure Static Web Apps to use the repository as a source.

### (3) GitHub Actions

- Following the [document](https://learn.microsoft.com/en-us/azure/static-web-apps/branch-environments?tabs=github-actions), modify the original workflow.

### (4) Create `staticwebapp.config.json`

- Following the [document](https://learn.microsoft.com/en-us/azure/static-web-apps/configuration#networking), create and edit `staticweapp.config.json`
- Publish web app with main branch.

### Pull request preview

- Modify 