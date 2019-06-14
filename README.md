# explosion-impact-angle-tutorial
Godot 3.1 Tutorial: How to rotate bullet hit impact object in relation to surface normal's when colliding, ex. such as bullet explosions hits etc.

This video is right but =

obj.rotation_degrees = rad2deg(atan2(collision_normal.y,collision_normal.x)) 

is what you want to write for the explosion impact object. you don't want to use the 360/(2 * PI) as in tutorial, although that works, this is better. :) Thank you Deoxy Ribo for pointing that out :)

the explosion and Godot mascot animations are my own, please feel free to use them as you wish

best wishes
Max Robert
