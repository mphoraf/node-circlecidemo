# CircleCI Demo React Native App

[![CircleCI](https://circleci.com/gh/mphoraf/node-circlecidemo/tree/development.svg?style=svg)](https://circleci.com/gh/mphoraf/node-circlecidemo/tree/development)

## Building and running locally on a node image

1. Run `yarn` to install the JS dependencies.
2. Run `yarn test` to run the JS tests (via `jest`).
3. Run `yarn start` to run the app in development mode. You can open it
   in the [Expo app](https://expo.io) on your phone. It will reload as
   you save edits to your files. You will see error messages and logs in
   your terminal window.



### Running tests using the CircleCI CLI

You can run individual jobs from the [configuration
file](https://github.com/mphoraf/node-circlecidemo/blob/master/.circleci/config.yml)
using the CircleCI CLI.

Please see [this doc](https://circleci.com/docs/2.0/local-jobs/#nav-button)
for details on how to install the CLI. Once it is installed, you can run
the `build` job by running the following in the root of this repo:

```bash
circleci build
```

To run the node job, you can run the following:

```bash
circleci build --job node
```


## Building on CircleCI

This example is ready to be built on CircleCI. Once you have copied or
forked the repository, navigate to the CircleCI web interface, choose
**Projects** and then **Add project**. Select a project and click
**Start building**.

Try pushing some changes to your repo to see how a JS job runs.
