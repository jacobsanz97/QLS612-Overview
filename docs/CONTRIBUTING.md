# Contributing to the Cayman theme

## How to report a bug

Here are a few tips for writing *great* bug reports:

* Describe the specific problem (e.g., "widget doesn't turn clockwise" versus "getting an error")
* Include the steps to reproduce the bug, what you expected to happen, and what happened instead
* Check that you are using the latest version of the project and its dependencies
* Include what version of the project your using, as well as any relevant dependencies
* Only include one bug per issue. If you have discovered two bugs, please file two issues
* Even if you don't know how to fix the bug, including a failing test may help others track it down

**If you find a security vulnerability, do not open an issue. Please email security@github.com instead.**

## How to propose changes

Here's a few general guidelines for proposing changes:

* If you are making visual changes, include a screenshot of what the affected element looks like, both before and after.
* Follow the [Jekyll style guide](https://ben.balter.com/jekyll-style-guide).
* If you are changing any user-facing functionality, please be sure to update the documentation
* Each pull request should implement **one** feature or bug fix. If you want to add or fix more than one thing, submit more than one pull request
* Do not commit changes to files that are irrelevant to your feature or bug fix
* Don't bump the version number in your pull request (it will be bumped prior to release)
* Write [a good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)

At a high level, [the process for proposing changes](https://guides.github.com/introduction/flow/) is:

1. [Fork](https://github.com/pages-themes/cayman/fork) and clone the project
2. Configure and install the dependencies: `script/bootstrap`
3. Make sure the tests pass on your machine: `script/cibuild`
4. Create a new branch: `git checkout -b my-branch-name`
5. Make your change, add tests, and make sure the tests still pass
6. Push to your fork and [submit a pull request](https://github.com/pages-themes/cayman/compare)
7. Pat your self on the back and wait for your pull request to be reviewed and merged

**Interesting in submitting your first Pull Request?** It's easy! You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

## Bootstrapping your local development environment

`script/bootstrap`

## Running tests

`script/cibuild`

## Code of conduct

This project is governed by [the Contributor Covenant Code of Conduct](../coc.md).
By participating, you are expected to uphold this code.

## Additional Resources

* [Contributing to Open Source on GitHub](https://guides.github.com/activities/contributing-to-open-source/)
* [Using Pull Requests](https://help.github.com/articles/using-pull-requests/)
* [GitHub Help](https://help.github.com)
