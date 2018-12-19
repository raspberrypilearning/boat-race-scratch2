## Crashing!

At the moment, the boat sprite can simply sail through the wooden barriers! You're going to fix that now.

--- task ---

You need two costumes for your boat sprite: one normal costume, and one for when the boat crashes. Duplicate your boat sprite's costume, and name one costume 'normal' and the other 'hit'.

--- /task ---

--- task ---

Click on your 'hit' costume, and use the **Select** tool to grab pieces of the costume and move and rotate them to make the boat look like it has crashed to pieces.

 ![screenshot](images/boat-hit-costume.png)

--- /task ---

--- task ---

Now add code to your boat so that it crashes and breaks up when it touches any brown wooden barriers.

--- hints ---
--- hint ---
You need to add code blocks inside your `forever`{:class="blockcontrol"} loop so that your code keeps checking if the boat sprite has crashed, and if it has crashed, the code needs to reset the boat sprite's position.

`if`{:class="blockcontrol"} the boat is `touching`{:class="blocksensing"} the brown colour of the wood, you need to `switch to the hit costume`{:class="blocklooks"}, `say Noooo! for 2 seconds`{:class="blocklooks"}, and then `switch back to the normal costume`{:class="blocklooks"}. Finally, you'll need to `point up`{:class="blockmotion"} and `go to the start position`{:class="blockmotion"}.

--- /hint ---
--- hint ---
Here are the code blocks you need:
![boat-sprite](images/boat_resize.png)
![blocks_1545215393_9806917](images/blocks_1545215393_9806917.png)
--- /hint ---
--- hint ---
Here's what your code should look like:
![boat-sprite](images/boat_resize.png)
![blocks_1545215395_1026468](images/blocks_1545215395_1026468.png)
--- /hint ---
--- /hints ---

--- /task ---

--- task ---

You should also add code to make sure that your boat sprite always starts out looking 'normal'.

Test your code again. If you try to sail the boat through a wooden barrier now, the boat should crash and then move back to its starting position.

 ![screenshot](images/boat-crash.png)

--- /task ---

