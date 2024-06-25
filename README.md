<p align="center">
  <a href="http://nuom.co.uk/" target="blank"><img src="https://assets-global.website-files.com/60893c95d5c9871201e719d5/60894c461d15a242648ac3ab_logo-black.svg" width="320" alt="Nuom 
Logo" /></a>
</p>

# Nuom's Senior Fullstack Test

If you are reading this, it's probably because you are thinking of joining our engineering team at [nuom](https://nuom.co.uk). With this test, we will assess:

* Your capacity to write Backend code
* Your capacity to write Frontend code
* Your capacity to create an API using best practices
* Your capacity to write clean code
* Your capacity to communicate your decisions

For this test you are free to use the language and framework which is the most comfortable to you for both the
Frontend and Backend.

You are free to use the database of your choice.


## Context

You will be building a system to rate and recommend dogs based on the [Dog CEO API](https://dog.ceo/dog-api/documentation/).

Each dog is characterised by they *Breed*, *Size*, *Color*, *Description* and *Tags*. 
The *Tags* are a list of words that describe the dog personality.

The dogs are rated by the users on a scale of 1 to 5.

## Requirements
- When the backend load, it should initialise the database with the data found in the `data` folder.
- A user should be able to rate a dog on a scale of 1 to 5 that is already in the database.
- The application should recommend dogs to users. It should take into account previous ratings in order to recommend a dog. This is the main task of this project and most of your time should be spent on this.
- Authentication is not required for this project.



## How to submit:
* Create a Github repository. It is recommended to keep it private.
* Once you are done, send a link to your repository by email to Loic
* Add *loicNuom* as a collaborator so the code can be reviewed
* Book a time slot with Loic for the technical interview


## Final note

There is absolutely no constraint on the technological stack that you might choose to achieve this,
either in the backend or frontend. Choose whichever you think is best suited for the task.

You can use any algorithm you want to implement the recommendation system. However, the recommendation should take into account the user's previous ratings. 

You are free to modify the data structure as you see fit.

There is no time limit so that you can organise yourself how you prefer, but we don't expect candidates to spend more than 5 to 8 hours working on it.

The code is reviewed with the same level of scrutiny we review code internally, and then we grade it among 4 main axes:
- Correctness wrt to the given specification: is it doing what we want?
- User experience: would our clients understand and like the software?
- Ease of deploying and operate: would our on-the-field teams be able to deploy the software and support clients in their daily usage?
- Code quality: would your future colleagues be able to work on the code?

It's ok to only convincingly describe something you'd do in an actual production app that you don't want to spend time actually doing for an interview exercise.
Historically, the #1 reason for us not going forward following this exercise is correctness, that is code is sent either with major bugs, or without following the specification. 

If something is not clear, feel free to send us an email! Asking questions is not frowned upon :-)

We are looking for high quality code: typically something that you would put into production and be proud of.

Have fun!
