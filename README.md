# Godot Minigame 5

## Devlog

The cone count UI works by every time the player hits a cone, it goes up by one. In the

cone script, the \_on\_body\_shape\_entered function detects whether the body hitting the cone is a vehicle; the vehicle being the player. If it is the player, then it calls on the increaseConesHit function that is in the time\_ui script. The increaseConesHit function adds one to the count every time a cone is hit. The conesText label is then updated every time, through a string function. Which allows the player to see how many cones they have hit.



## Open-Source Assets

* [Car movement scripts \& car/racetrack models](https://github.com/DAShoe1/Godot-Easy-Vehicle-Physics/tree/main)
* [Racing props](https://atomicrealm.itch.io/modular-roads)
* [Finish line 3D model](https://sketchfab.com/3d-models/finish-line-7ec1d8194ddf46e6b398d336df0b5d7a)

