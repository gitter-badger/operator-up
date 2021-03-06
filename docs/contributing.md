# Contributing

Interested in contributing to Operator Up? Want to report a issue? Before you do, please read the following guidelines.

## Submission context
### Got a question or problem?
For quick questions there's no need to open an issue as you can reach us on gitter.im.

### Need to make a correction to the content?
If you found a bug within the docs, you can help us by submitting an issue to the issue tracker in our GitHub repository. Even better, you can submit a Pull Request with a fix. However, before doing so, please read the submission guidelines.

### Missing a TTP, Section, Tool Cheat sheet?
You can request a new feature by submitting an issue to our GitHub Repository. If you would like to implement a new section, please submit an issue with a proposal for your work first, to be sure that it is of use for everyone. Please consider what kind of change it is:

* For a major section, first open an issue and outline your proposal so that it can be discussed. This will also allow us to better coordinate our efforts, prevent duplication of work, and help you to craft the change so that it is successfully accepted into the project.
* Small tool additions, cheet sheets and TTPs can be crafted and directly submitted as a Pull Request. However, there is no guarantee that your PR will make it into the master, as it's always a matter of opinion whether if benefits the overall project.

## Submission guidelines
### Submitting an issue
Before you submit an issue, please search the issue tracker, maybe an issue for your problem already exists and the discussion might inform you of workarounds readily available.

We want to fix all the issues as soon as possible, but before fixing a bug we need to reproduce and confirm it. In order to reproduce bugs we will systematically ask you to provide a minimal reproduction scenario using the custom issue template. Please stick to the issue template.

### Submitting a Pull Request (PR)
Search GitHub for an open or closed PR that relates to your submission. You don't want to duplicate effort. If you do not find a related issue or PR, go ahead.

1. **Development**: Fork the project, set up the development environment, make your changes in a separate git branch and add descriptive messages to your commits.

2. **Build**: Before submitting a pull requests, build the docs using `mkdocs`. This is a mandatory requirement for your PR to get accepted, as all docs must be compiled and pass our CI before we accept it.

3. **Pull Request**: After building the docs, commit the compiled output, push your branch to GitHub and send a PR to the `master` branch. If we suggest changes, make the required updates, rebase your branch and push the changes to your GitHub repository, which will automatically update your PR.

After your PR is merged, you can safely delete your branch and pull the changes from the main (upstream) repository.

## Acknowledgments
This page is based off: https://squidfunk.github.io/mkdocs-material/contributing/ as they have a great submission criteria setup.