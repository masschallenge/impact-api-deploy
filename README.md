# impact-api-deploy
Contains the build and deploy components of the api server

In its current state, this project is setup with travis-ci (travis-ci.org) to run the builds. A build is initiated upon creating a pull request or making a merge into a branch.

Travis is pre-configured to deploy to the impact api production instance anytime something is merged into master. All thje settings and secret keys are configured in travis via environment variables.