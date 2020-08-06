# Workout-Tracker
Week-17 HW

![License Badge](https://img.shields.io/badge/license-MIT-blue)

## Description

This application is a workout tracker. It uses a Mongo database with a Mongoose schema to handle adding exercises and retrieving workout information. The application also uses Express to handle server-side routes and APIs.

## Table of Contents

  * [User-Story](#user-story)
  * [Acceptance-Criteria](#acceptance-criteria)
  * [Deployed Application](#deployed-application)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)

## User Story

```
AS A user, I want to be able to view create and track daily workouts. 
I want to be able to log multiple exercises in a workout on a given day.
I should also be able to track the name, type, weight, sets, reps, and duration of exercise. 
IF the exercise is a cardio exercise,
I should be able to track my distance traveled.
```

## Acceptance Criteria

```
When the user loads the page, they should be given the option to create a new workout, or continue with their last workout.

The user should be able to:

  * Add exercises to a previous workout plan.

  * Add new exercises to a new workout plan.

  * View multiple the combined weight of multiple exercises on the `stats` page.
```

## Deployed Application

Here is the URL for the deployed [Workout Tracker Application](https://polar-shelf-16735.herokuapp.com/) on Heroku.


## Installation

```
1. Go to https://github.com/alek2535/Workout-Tracker

2. Fork the branch and then click on clone or download

3. Paste copied link after `git clone` into your bash console in your desired directory

4. You should now have access to the repository
```

Since there is a `package.json`, you will need to run `npm install`.

Once you have the dependancies installed run the command:

```
`npm start` or `npm run watch`
```

Make sure you have MongoDB running in the background.

## Usage

A consumer will reach their fitness goals quicker when they track their workout progress.

Technologies Used:

* JavaScript
* Node.js
* Express
* Morgan
* MongoDB
* Mongoose

## Contributing

Use the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/code_of_conduct.md) when contributing and making pull requests.

For major changes, please create an issue before any changes to discuss them.


## License

[MIT License](./LICENSE)

Copyright (c) 2020 Alek Valencia

## Project Status

This project meets most of the requirements in the Acceptance Criteria. There seems to be some issues with the stats page and the graphs. This needs to be fixed to be fully functional.

## Tests

There are currently no tests for this project.

## Questions

GitHub profile: [alek2535](https://github.com/alek2535)

Email: alekvalencia2535@gmail.com

If you have any questions about the project you can reach me at the above email.
