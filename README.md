# GitHub Actions workflow for deploying app to www.evennode.com
This repository serves as a guide to configuring your GitHub Actions workflow 
to automatically deploy your app to www.evennode.com on every commit to the master branch.

## Configuration
1. Copy the file [.github/workflows/deploy-to-evennode.yml](.github/workflows/deploy-to-evennode.yml) to your local repository
2. Configure the following secrets for your repository's settings
    1. `SSH_KEY` - Your private key used to deploy to EvenNode
    2. `EVENNODE_REPO_URL` - Your application's git repository from EvenNode such as `git@git.evennode.com:myapplication.git`
    3. `GIT_EMAIL` - Email under which git shall deploy your application
    4. `GIT_NAME` - Name under which git shall deploy your application

After the configuration push changes to your git repository on GitHub and watch it deploy
your app to www.evennode.com
