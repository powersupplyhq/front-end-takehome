# Front End Takehome Project
A take home project for Front End developers interviewing for a role at Territory Foods.

## Your mission
Hey Front End developer. Welcome. Your mission, should you choose to accept it, is to carve out 3 hours (TOPS) and create a single page app (SPA) using the API endpoint, and the front-end mockups defined below.

Maybe you don't totally finish everything. _That is ok!_ We care more about seeing what you do get done than what you don't, which gives us an opportunity to discuss your approach to time management & prioritization.

To this end, please initialize a Git repo for this project and commit your work just like you would normally.

## What we are asking you to build:
A very simplified version of our menu view: https://www.territoryfoods.com/menus/2020-08-03

#### Here's where you'll get the meals:
https://territory-meals-api.herokuapp.com/meals
(it's a hobby tier dyno, so if it fails to load right away, it's because it needs to spin up. Try again, and once it's up it'll stay awake for a while)

#### Here's what our designer would like it to look like
You do not need to match these perfectly, but, this role will be working closely with our design team, so being able to replicate a mockup from scratch will be important.

_This should save you time!_

[Here are some mockups](https://www.figma.com/file/xGLKFAHDKoEODwpYPWQPoj/Code-Challenge?node-id=2%3A904)

#### Here are some user stories we would like the app to accomplish:
 - As a user, I want to see all of the meals available on one page.
 - As a user, I want to be able to filter meals by `tag` and `type`
   - The collection of available tags should be based on what exists in the collection of meals. Hint: this should be dynamic, not hardcoded.
 - As a user, I want to be able to search meals by `title`

#### If you've got time...(stretch goal)
 - As a user, I want to be able to add/remove the meals I select to a cart.
 - As a user, I want to be able to see what is in my cart.
   - Hint: this should be a modal or component on the page. Not a separate view.
   
## How to build it (what to use):
 - We use React, though you may choose use the language and framework of your choice.

## When You're Done
Zip up your git repo and send it as an email attachment to `bolak@territoryfoods.com`
