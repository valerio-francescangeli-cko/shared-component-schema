# Shared Component Schema

This project is a boilerplate that allow teams to create shared components.

It incorporates CKO's Own UI Toolkit to facilitate creation of React components that respect our design style.

## Configuration
At the moment the is no CLI in place.
- Download the project as a zip file
- Customise `package.json` details like name, version and author
- Run `git init`

Your component is inside the src folder.

## Local testing
Run `yarn dev` to spin up a local website on `localhost:1234`.

## Peer Dependencies
Rollup can exclude any package from the final bundle. As an example the project excludes react.
The list of exclusion is inside `rollup.config.js` under the voice `external`.

## Local Deployments
To create a local package run `yarn create-local-package`.
