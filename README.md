# TerraGo
Wait for it.
The way I'll do is this:
1)create all the object that can be added into the scene first
2)In the main scene,use 1d simplex noise to calculate the height along the x-axis
3)if it's under the height for generation,I'll create another simplex noise to determine what block to place at that point.
4)create more noise to add more details.U can use your creativity to partition the world and add some rules to determine how u want to design the world,u can take various other factors into account also.
5)for the floating part and some random out of place stuff,I think u can create algorithms to generate them,such as generate_dungeon()orgenerate_floatingLand()

Btw,in Godot,there's a built in noise called open simplex noise,I'm sure there's many tutorial and documentations online,just go search about it..

Some helpful links:
1)https://godot-es-docs.readthedocs.io/en/latest/classes/class_opensimplexnoise.html
2)https://www.redblobgames.com/maps/terrain-from-noise/

Hope it helps...I'm not really good at answering,but this is more or less how I generate my world.
