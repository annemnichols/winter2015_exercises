# 12 Days of Coding

Please present the project that you wish to be peer reviewed in this folder. Replace where appropriate.

## [ Anne's List ]

## Description of Project

This is a classified's ad site that I chose to build off of the 12 Days list. I chose it because I think it shows all the major Rails skills and gems we've learned so far. I used Devise to create user accounts and Paperclip to allow users to upload photos with their ad posts. 

## Challenges

- What challenges did you encounter? How did you overcome them? Be candid.

	I struggled a bit with getting Paperclip to work. The issue ended up coming down to a permissions issue in the model. I also had a difficult time with figuring out how to display all of the user posts on the index page because displaying posts required a user ID. I fixed this issue by putting in an exception for the index method to the before_action set_user in the posts controller.

- Based on this project, what do you want to learn more of?

	I'd like to learn more about how to put validations in the controller for user accounts. 
