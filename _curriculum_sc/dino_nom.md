---
title: "Dino nom"
description: "Simple Scratch project intended to teach students clones, variables, and broadcasting"
date: 2024-02-19
l_number: 1
layout: default
---


This is a simple game intended to teach elementary school students who have already learned the basics of Scratch the use of clones (basic instantiations of classes), variables, and a bit of animation. It's somewhat open-ended in the sense that kids can draw their own backgrounds and implement cool player animations.

Final result:
<iframe src="https://scratch.mit.edu/projects/986600657/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>

### Step 1: Player movement
Have the player's character move to the center of the screen at the bottom on start, then implement simple left and right movement, like so.

![Implementation of basic movement](/assets/images/curriculum/scratch/dino_nom/03-22-24-155936.png)

### Step 2: player bounds
Note: this step isn't really necessary, but I think this looks nicer.
Next step is to create arbitrary bounds that the player's character can't cross. Although it is possible to use "if on edge, bounce", that creates a weird looking effect when the player holds down a key. I implemented this using simple if statements.

![Implementation of simple bounds](/assets/images/curriculum/scratch/dino_nom/03-22-24-160349.png)


### Step 3: Making the food appear and move
Have students implement moving to a random position on the top of the screen. Make sure to teach students how "pick random" works. Then use a forever loop to have the food move downwards. For testing, have the students click the "when I start as a clone" block. This will create a clone and have it follow the directions.

![Having food move](/assets/images/curriculum/scratch/dino_nom/03-22-24-162704.png)


### Step 4: Making clones of the food
Create a new sprite with a picture of some food, and set it to be invisible. Then, have the students go to the stage and add blocks to create a new clone of that food every few seconds. Ensure that students understand what clones are.

![Implementation of food clones](/assets/images/curriculum/scratch/dino_nom/03-22-24-161846.png)

### Step 5: Making the clones get eaten and disappear
Teach students the concept of broadcasting a message and how it'll be useful here. Then explain deleting clones and why it's important (specifically why it's better than simply hiding it). Use if statement to implement these when the food touches the player, or the food touches the floor (note: the y<0 ensures the food is not touching the top edge).

![Implementation of deleting clones and broadcasting messages](/assets/images/curriculum/scratch/dino_nom/03-22-24-163214.png)

### Step 6: Implementing score variable
Teach students how to create a variable, how they work, and why they're useful. Then use "when I receive" block to update the score variable whenever food is eaten. Also make sure the score variable is displayed. Also add block to update score when go is pressed in the stage. 

![Implementation of updating score when something gets eaten](/assets/images/curriculum/scratch/dino_nom/03-22-24-163705.png)

From here, students should have a basic understanding of how the code works.

### Step 7: Lives
- Create variable for lives
- Create broadcast when food is missed
- Add handler when a life is lost
- replace forever loops with ones that repeat until lives run out
- add block to switch background when lives run out
- reset lives on start (in stage)

### Step 8: Random food type
Add [n] number of costumes of different foods, then use "pick random" to pick between 1 and [n], like so.

![Implementation of random food](/assets/images/curriculum/scratch/dino_nom/03-22-24-165043.png)

### Step 9: Animation on event
Add second costume to player, the add blocks to switch between those costumes momentarily when the player eats food.

![Implementation of simple eating animation](/assets/images/curriculum/scratch/dino_nom/03-22-24-165224.png)


### Step 10: Increase difficulty
Use variables to adjust food drop speed and spawn rate as score increases. Ensure these variables are reset when the game is started.

![Implementation of increasing difficulty](/assets/images/curriculum/scratch/dino_nom/03-22-24-165414.png)

### From here:
- Have students draw their own backgrounds to personalize
- Have students create additional animations