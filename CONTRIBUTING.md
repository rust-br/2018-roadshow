EM CONSTRUÇÃO
# Guia de Contribuidores

:+1::tada: Primeiro de tudo, obrigado por contribuir com nosso projeto! :tada::+1:

Neste guia há conjunto de diretrizes para contribuir com as iniciativas deste experimento. Estas são as diretrizes, e não regras absolutas. Sinta-se à vontade para propor mudanças neste documento em um [pull request](https://help.github.com/articles/about-pull-requests/).

#### Índice

[Código de Conduta](#code-of-conduct)

[I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [Atom and Packages](#atom-and-packages)
  * [Atom Design Decisions](#design-decisions)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [JavaScript Styleguide](#javascript-styleguide)
  * [CoffeeScript Styleguide](#coffeescript-styleguide)
  * [Specs Styleguide](#specs-styleguide)
  * [Documentation Styleguide](#documentation-styleguide)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Código de Conduta

This project and everyone participating in it is governed by the [Atom Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [atom@github.com](mailto:atom@github.com).

## I don't want to read this whole thing I just have a question!!!

> **Note:** [Please don't file an issue to ask a question.](https://blog.atom.io/2016/04/19/managing-the-deluge-of-atom-issues.html) You'll get faster results by using the resources below.

We have an official message board with a detailed FAQ and where the community chimes in with helpful advice if you have questions.

* [Discuss, the official Atom and Electron message board](https://discuss.atom.io)
* [Atom FAQ](https://discuss.atom.io/c/faq)

If chat is more your speed, you can join the Atom and Electron Slack team:

* [Join the Atom and Electron Slack Team](https://atom-slack.herokuapp.com/)
    * Even though Slack is a chat service, sometimes it takes several hours for community members to respond &mdash; please be patient!
    * Use the `#atom` channel for general questions or discussion about Atom
    * Use the `#electron` channel for questions about Electron
    * Use the `#packages` channel for questions or discussion about writing or contributing to Atom packages (both core and community)
    * Use the `#ui` channel for questions and discussion about Atom UI and themes
    * There are many other channels available, check the channel list

## What should I know before I get started?

### Atom and Packages

Atom is a large open source project &mdash; it's made up of over [200 repositories](https://github.com/atom). When you initially consider contributing to Atom, you might be unsure about which of those 200 repositories implements the functionality you want to change or report a bug for. This section should help you with that.

Atom is intentionally very modular. Nearly every non-editor UI element you interact with comes from a package, even fundamental things like tabs and the status-bar. These packages are packages in the same way that packages in the [Atom package repository](https://atom.io/packages) are packages, with one difference: they are bundled into the [default distribution](https://github.com/atom/atom/blob/10b8de6fc499a7def9b072739486e68530d67ab4/package.json#L58).

<a id="atom-packages-image"/>

![atom-packages](https://cloud.githubusercontent.com/assets/69169/10472281/84fc9792-71d3-11e5-9fd1-19da717df079.png)

To get a sense for the packages that are bundled with Atom, you can go to Settings > Packages within Atom and take a look at the Core Packages section.

Here's a list of the big ones:
