# Contributing to React CDK

We welcome you help to make React CDK better. This document will help to streamline the contributing process and save everyone's precious time.

## Issues

No software is bug free. So, if you got an issue, follow these steps:

* Search the [issue list](https://github.com/kadirahq/react-storybook/issues?utf8=%E2%9C%93&q=) for current and old issues.
* If non of that is helping, create an issue with with following information:
  * Clear title (make is shorter if possible).
  * Describe the issue in clear language.
  * Share error logs, screenshots and etc.
  * To speed up the issue fixing process, send us a sample repo with the issue you faced.

## Pull Requests (PRs)

We welcome your contributions. There are many ways you can help us. This is few of those ways:

* Fix typos and add more documentation.
* Try to fix some [bugs](https://github.com/kadirahq/react-cdk/labels/bug).
* Add new features (try to discuss with what are building by creating an issue).

Before you submit a new PR, make you to run `npm test`. Do not submit a PR if tests are failing. If you need any help, create an issue and ask.

## Development Guide

This is Yeoman generator. There are two generators, which are:

* app - main generator creates the project
* update - which update an existing project

Before you start developing, you need to get familiar with yeoman first. Refer following links:

* [Yeoman getting started guide](http://yeoman.io/learning/)
* [Creating a yeoman generator](http://yeoman.io/authoring/)

Then link this project with `npm link`. Then you can try `yo react-cdk` and it'll use your development repo.
