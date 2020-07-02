# Fitness Tracker

This fitness app was made to test my knowledge of MongoDB/Mongoose and making routes.
Using a pre-built front end I came up with the models and routes to allow the user to post, push, and get data.

https://fitness-tracker-dmw.herokuapp.com/

![Fitness Tracker Demo](/public/assets/demoImages/fitnessTracker.gif)

## Table of Contents

* [Description](#description)
* [Technologies Used](#technologies)
* [Usage](#usage)
* [Future Development](#future)
* [Acknowledgements](#acknowledgements)

## Description

This full-stack web application prompts the user to input exercises as part of a workout.
The user can then view their stats for their most recent workout or for the past week.

The app was created with the following user story in mind:

*As a user, I want to be able to view create and track daily workouts. 
I want to be able to log multiple exercises in a workout on a given day. 
I should also be able to track the name, type, weight, sets, reps, and duration of exercise. 
If the exercise is a cardio exercise, I should be able to track my distance traveled.*

## Technologies Used

* Bootstrap: CSS framework
* Express: web framework
* MongoDB: database
* Mongoose: database ORM

## Usage

To begin, the user will click on the New Workout button. This will lead them to the workout input page.
They will then select either a Resistance or Cardio exercise from the dropdown menu.
For Resistance exercises, fill out the exercise name, weight, sets, reps, and duration.
For Cardio exercise, fill out the exercise name, distance, and duration.
Then the user will click the Add Exercise button to add another exercise to the workout or the Complete button to finish the workout.
Once the workout is complete the user will be navigated back to the home screen where the total numbers from the last workout are displayed.
If the user clicks on the Dashboard link in the top left corner they will be taken to a page that has their stats from the past week sorted by duration and pounds lifted.

## Future Development

While developing this app was a great *exercise* in Mongoose and routes, I don't find it particularly useful.
I would like to allow to the user to view all of their previous workouts or exercies by date.
This would allow the user to check their progress in their fitness journey.

## Acknowledgements

I would like to thank UW Coding bootcamp, tutor Namita Shenai, instructor John Young, and TA's Abdul Aziz and Ben Vaagen.
