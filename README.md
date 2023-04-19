# Build and Deploy to Visual Studio App Center using GitHub Actions

This repository contains an Android app and a pipeline.yml file that automates the build and deployment of the app to Visual Studio App Center using GitHub Actions.

## Prerequisites

Before getting started, you will need to:

- Have a GitHub repository with an Android app that you want to build and deploy to Visual Studio App Center.
- Create an account on Visual Studio App Center and create an app.
- Obtain an API token from Visual Studio App Center. You will need this later to configure the pipeline.

## Creating the pipeline.yml file

1. Navigate to the root directory of your GitHub repository.

2. Create a `.github/workflows` directory if it doesn't already exist.

3. Create a new file in the `.github/workflows` directory called `pipeline.yml`.

4. Open the `pipeline.yml` file and paste
