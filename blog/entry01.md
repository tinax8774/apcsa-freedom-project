# Entry 1
##### 11/09/2026


### Content
During the past few weeks we have chosen a tool and a project idea that we want to do. My project idea is to make a study tool more specifically for AP classes but instead of making it just a boring website that people would not be interested in I'm gonna make it have two options one would be notes and quizzes and the other one would change it into a platformer game so it gives the user a more fun option when it comes to studying. The tool I chose for this project is Godot as it is a game engine which would perfectly make the platformer game that is going to be a part of the website.


Below is how I have tinkered with my tool:
* Learned how to add in a sprite
        * Go to other node
        * Go to node2D
        * Go to collisionObject2D and then physicsBody2D then characterBody2D
        * Allows for you to add in your own sprites
* Used to make all sorts of games
    * Game engine to make video games
    * Learned how to input a character avatar into the screen


``` java
@export var speed = 400


func get_input():
    var input_direction = Input.get_vector("left", "right", "up", "down")
    velocity = input_direction * speed


func _physics_process(delta):
    get_input()
    move_and_slide()
```
* Used to control the movement of a sprite on the screen

Basically my thought process of how I'm gonna use godot is using the sprite and making a platformer game where the user can choose what subject they are trying to study and they are able to collect points but also study at the same time. If they don't want to do that then there will be an option where it gives a summary of whatever unit or topic they want.


### Sources
The sources I used was the following
* [Tool website](https://docs.godotengine.org/en/stable/)
* [Youtube Video](https://www.youtube.com/watch?v=oED12Mo2018)


### EDP(Engineering Design Process)
We are currently on step one which is choosing a tool and project idea. The next step is to continue to learn our tool.


### Skills
One skill I got out of this is time management trying to balance assignments and also this major project and college stuff is rough. Trying to find the time to focus just on tinkering or just this blog entry has been a challenge and something that will slowly get easier once college stuff dies down.


Another skill is How to Google because trying to learn this tool without the help of google and youtube is difficult as the coding language is slightly different compared to java and really tests your research skills in order to fully learn your tool. I've been getting better at this skill after doing it for three years but there are moments where trying to find a recent source feels impossible.
[Next](entry02.md)


[Home](../README.md)

