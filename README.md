# Codeuino Website

Offical site for Codeuino landing page. Please visit [http://www.codeuino.org/](http://www.codeuino.org/)

### Table of contents

 - Requirements
 - Installation
 - File Structure
 - How to contribute
 - Credits
 
 ## Requirements
 Following applications are required to run the application locally.
 
 - Git
 - Npm
 - Node

## Installation
To run the application on your local system follow these steps

 1. <code>git clone https://github.com/codeuino/website-www.codeuino.org.git</code>
 2. Move to the project directory.
 3. <code>git checkout development</code>
 4. <code>npm install</code>
 5. Open <code>localhost:3000</code> to view the website on your local browser.

## File Structure

This section describes about the file structure of the project.
All the source code is located in <code>src</code> directory.
There are two main directories in the src folder, <code>components</code> and <code>pages</code>.
The pages directory contains all the source code of routes in separate folders.
The components directory contains all reusable component file in separate folders.

## Dockerizing the application

### To use the application in docker for both production and development use, follow:

- Build and tag docker image <code> docker image build -f  Dockerfile-dev  -t {name-of-docker-file-of-your-choice}  . </code>

- Running docker image <code> lakshyadocker run -it -v ${PWD}:/app -v /app/node_modules -p {Port-you-want-your-app-on}:3000 --rm {docker-image} </code>

## How to contribute

### Opening an issue

[![GitHub issues](https://img.shields.io/github/issues/codeuino/website-www.codeuino.org?logo=github)](https://github.com/codeuino/website-www.codeuino.org/issues) ![GitHub closed issues](https://img.shields.io/github/issues-closed/codeuino/website-www.codeuino.org?logo=github)

You should usually [open an issue](https://github.com/codeuino/website-www.codeuino.org/issues/new) in the following situations:

* Report an error you can’t solve yourself
* Discuss a high-level topic or idea (for example, community, vision or policies)
* Propose a new feature or other project idea

**Tips for communicating on issues:**

If you see an open issue that you want to tackle, comment on the issue to let people know you’re on it. That way, people are less likely to duplicate your work.
If an issue was opened a while ago, it’s possible that it’s being addressed somewhere else, or has already been resolved, so comment to ask for confirmation before starting work.
If you opened an issue, but figured out the answer later on your own, comment on the issue to let people know, then close the issue. Even documenting that outcome is a contribution to the project.

### Opening a pull request

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?logo=github)](http://makeapullrequest.com) ![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/codeuino/website-www.codeuino.org?logo=git&logoColor=white) ![GitHub contributors](https://img.shields.io/github/contributors/codeuino/website-www.codeuino.org?logo=github)

You should usually open a pull request in the following situations:

* Submit trivial fixes (for example, a typo, a broken link or an obvious error)
* Start work on a contribution that was already asked for, or that you’ve already discussed, in an issue
A pull request doesn’t have to represent finished work. It’s usually better to open a pull request early on, so others can watch or give feedback on your progress. Just mark it as a “WIP” (Work in Progress) in the subject line. You can always add more commits later.

## Credits

This project is currently maintained by [Jaskirat Singh](https://github.com/jaskirat2000) .
