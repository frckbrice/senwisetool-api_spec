# senwisetool-project

__table of content__

- [local setup](#setup-repo-locally)
- [how to render the](#how-to-render-the-documentation)
- [API tags](#api-tags)

## setup repo locally

- Clone repo with
  
  ```bash
    git clone git@github.com:kraulain/rbclean-infra.git
  ```

- Navigate to project with from your terminal

  ```bash
    cd rbclean-infra
  ```

## How to render the documentation

<!-- - Install Redoc CLI with the command `npm i redoc-cli g` -->

- Start local server for the spec in watch mode

    ```bash
      npm run dev
    ```

- Create a deployable zero-dependency HTML file

- Generate the html with

    ```bash
      npm run build:html
    ```

## Contributing

- Branches should be name with `feature/<task>` format

- Writing commits
  - Commit messages should follow the for mat `#<issue_number> | <author_name> | <work_description>`

  - @example is `#1 | Kraulain | create empty repo`

  - The numbering is with respect to the issue number your are working on

- When creating a `PR`;

  - If that pr is for an existing `issue`, be sure to tag the issue in the PR description, to auto-close the issue if it's approved, you can use any of these commands

    - `Resolves #<issue_number>`

    - `Fixes #<issue_number>` or

    - `Closes #<issue_number>`
  
  - Always assign the PR to yourself and your team-mate

- ### API tags

  - Auth
  - Users
  - Orders
  - Notifications
  - Reports

|

___

__Happy Coding 🚀__
