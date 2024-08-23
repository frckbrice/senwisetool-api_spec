# senwisetool-project

__table of content__

- [local setup](#setup-repo-locally)
- [how to render the](#how-to-render-the-documentation)
- [API tags](#api-tags)

## setup repo locally

- Clone repo with
  
  ```bash
    git clone git@github.com:frckbrice/senwisetool-api_spec.git
  ```

- Navigate to project with from your terminal

  ```bash
    cd senwisetool-api_spec
  ```

## How to render the documentation

<!-- - Install Redoc CLI with the command `npm i redoc-cli -g` -->

- Start local server for the spec in watch mode (you could just enter cd swt_api_apec && redocly build-docs senwisetool-api_spec.yaml)

    ```bash
      - npm install -g @redocly/cli@latest
      - redocly build-docs ./swt_api_spec/senwisetool-api_spec.yaml
      - redocly preview-docs ./swt_api_spec/senwisetool-api_spec.yaml
    ```

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
  - Collector_agent
  - ...
__


### WIP (Work in Progress)
__Thanks 🚀__
