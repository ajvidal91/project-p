# Project Phaser

## WIP: going thru the Phaser 3 documentation and deciding on content and concept as I go along.
## Enter `npm install`
### To run server enter `http-server`  

#Notes:

The `platforms` variable creates a new Static Physics Group
In depth explaination of the different types of statics groups found in this
link ![phaser link](https://phaser.io/tutorials/making-your-first-phaser-3-game/part4)
a Group As their name implies are ways for you to group together similar
objects and control them all as one single unit. You can also check for collision
between Groups and other game objects. Groups are capable of creating their own Game
Objects via handy helper functions like create. A Physics Group will automatically
create physics enabled children, saving you some leg-work in the process.
With our platform Group made we can now use it to create the platforms:
