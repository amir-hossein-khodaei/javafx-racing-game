# Contributing to javafx-racing-game

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them.

## Table of Contents

- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Your First Code Contribution](#your-first-code-contribution)

## Development Setup

This project uses **Java 21** and **Maven**.

### Prerequisites
1. OpenJDK 21 or higher
2. Git

### Build Instructions

1. **Fork and Clone** the repository.
2. **Build** using the Maven Wrapper:
   `ash
   ./mvnw clean install
   `
3. **Run** the application:
   `ash
   ./mvnw javafx:run
   `

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
3. You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Styleguides

### Commit Messages
We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.
- \eat: allow provided config object to extend other configs\
- \ix: array parsing issue when multiple spaces were contained in string\
- \docs: correct spelling of CHANGELOG\

### Java Style
Please follow standard Java naming conventions (PascalCase for classes, camelCase for methods/variables).
