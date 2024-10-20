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



### Very Basic example:
### Workflows
Imagine a workflow like a list of chores you need to do every day. But instead of you doing them, a robot does it for you! It’s like telling the robot, "First, clean your room, then wash the dishes, and finally, do your homework." A **workflow** is like this list of chores for a computer, and it runs automatically when something happens, like when you finish breakfast or when you come home from school.

### Events
An **event** is the thing that tells the robot when to start doing its chores. For example, you might tell the robot, "Start cleaning when the clock strikes 4 PM," or "Start when you come home from school." In the same way, when certain things happen on your computer, like someone adding a new picture to a folder, the workflow gets triggered.

### Jobs
A **job** is like one big chore that the robot needs to complete. Inside the job, there are smaller steps the robot follows, just like "cleaning the room" could involve picking up toys, making the bed, and sweeping the floor. Each job is done in order, step by step.

### Actions
An **action** is like a special tool the robot uses to do a specific task. If you ask the robot to clean your room every day, it can use a broom. But if you ask it to wash the car, it needs a sponge. Actions are tools that help the robot complete its jobs more easily without you telling it every little detail.

### Runners
A **runner** is the robot itself! It's like a little helper that runs around doing your tasks. But remember, it can only do one job at a time, just like you can only be in one place at a time.
