# docs.runestone.app
Documentation for Runestone. The documentation is hosted at docs.runestone.app

## Deploying the Documentation

The documentation is deployed by running the [Update documentation](https://github.com/simonbs/docs.runestone.app/actions) action. Then running the action it will ask which branch to build the documentation from.

The action then performs the following steps:

1. Clone the [Runestone repository](https://github.com/simonbs/runestone) and checkout the specified branch.
2. Builds the DocC documentation using xcodebuild.
3. Commits the changes to the main branch of this repository.

[Netlify](https://www.netlify.com) monitors changes to this repository and will clone the repository and host the documentation.
