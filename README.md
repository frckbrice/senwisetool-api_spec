# Senwisetool REST API Specifications

![dislay image](docs/swt-project-image.png)

__This repository contains the specification files for  senwisetool REST APIs.__

__table of content__

- [local setup](#setup-repo-locally)
- [how to render the](#how-to-render-the-documentation)
- [API tags](#api-tags)

## setup repo locally

- Clone repo with
  
  ```bash
    git clone git@github.com:frckbrice/senwisetool-api_spec.git
  ```

- Navigate to project : the target is to access the senwisetool.yaml file for build.

  ```bash
    cd senwisetool-api_spec/swt_api_spec
  ```

## How to render the documentation

<!-- - Install Redoc CLI with the command `npm i redoc-cli -g` -->

- Start local server for the spec in watch mode (you could just enter cd swt_api_apec && redocly build-docs senwisetool.yaml)

    ```bash
      - npm install -g @redocly/cli@latest
      - redocly build-docs senwisetool.yaml
      - redocly preview-docs senwisetool.yaml
    ```
- after the preview on client finished build, you can follow the displayed link to browser and Voila.
- ### API tags

  - Users
  - Projects
  - Subscriptions
  - Farms
  - Training
  - Companies
  - Markets
  - Transactions
  - project_audits
  - Market_audits
  - Collector_agents
  - Farm_coordinates
  - Requirements
  - Price_plan
  - Campaigns
  - Stock_campaigns


### WIP (Work in Progress)
__Thanks 🚀__
