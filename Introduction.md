# Workflows in GitHub Actions

A **workflow** is a configurable automated process that runs one or more jobs. Workflows are defined by a YAML file that is checked into your repository. They can be triggered by various events in your repository, manually, or at a scheduled time.

Workflows are defined in the `.github/workflows` directory within a repository. A single repository can have multiple workflows, each performing different sets of tasks.

## Events

An **event** is a specific activity in a repository that triggers a workflow run. For example, events can originate from GitHub activities like creating a pull request, opening an issue, or pushing a commit to a repository.

## Jobs

A **job** is a set of steps in a workflow that is executed on the same runner. Each step is either:
- A shell script to be executed.
- An action that will be run.

Steps within a job are executed in order and are dependent on one another.

## Actions

An **action** is a custom application built for the GitHub Actions platform. It performs complex, frequently repeated tasks and helps reduce the amount of repetitive code in workflow files.

## Runners

A **runner** is a server that executes workflows when triggered. Each runner can run one job at a time.
