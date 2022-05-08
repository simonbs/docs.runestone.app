# docs.runestone.app
Documentation for Runestone. The documentation is hosted at docs.runestone.app

## Deploying the Documentation

The documentation is deployed by running the [Update documentation](https://github.com/simonbs/docs.runestone.app/actions) action. This aciton performs the following steps:

1. Clone the [Runestone repository](https://github.com/simonbs/runestone).
2. Builds the DocC documentation using xcodebuild.
3. Commits the changes to the main branch of this repository.

[Netlify](https://www.netlify.com) monitors changes to this repository and will clone the repository and host the documentation.
