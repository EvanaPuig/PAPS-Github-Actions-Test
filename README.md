# Github Actions Test
## Name of repo: paps-github-actions-test
Description: This is a repo for testing how Github actions works in an Android project and compare it to other services like Bitrise

## Step 1: Documentation
Go read the docs at: https://docs.github.com/en/actions

### Read the About Github actions
[About GitHub Actions - GitHub Docs](https://docs.github.com/en/actions/getting-started-with-github-actions/about-github-actions)
*Key points*: 
1. GitHub Actions enables you to create custom software development life cycle (*SDLC*) workflows directly in your GitHub repository.
2. You can write individual tasks, called actions, and combine them to create a custom workflow.
3. Workflows are custom automated processes that you can set up in your repository to build, test, package, release, or deploy any code project on GitHub.
4. What’s the difference between release and deploy?
5. There are some limitations depending on the GitHub plan: [About GitHub Actions - GitHub Docs](https://docs.github.com/en/actions/getting-started-with-github-actions/about-github-actions#usage-limits)

### Read about the terminology of GitHub actions
Go read the docs at: [Core concepts for GitHub Actions - GitHub Docs](https://docs.github.com/en/actions/getting-started-with-github-actions/core-concepts-for-github-actions)

No need to copy each concept, but they are good to reference often.

*Key points*:
1. A group of steps to perform a certain thing constitute an *action*.
2. *Artifacts* are not just apks, but also things that come out of testing like logs or screenshots, any by-product.
3. GitHub performs all upgrades and maintenance of GitHub-hosted runners (so if you want to run your tests in an older version of Android you may be tied up to the latest and greatest?)
4. Steps > Actions > Jobs > Workflow
5. *Runner* is the app that runs ‘GitHub Action Workflows’
