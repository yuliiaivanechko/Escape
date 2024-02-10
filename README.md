# 06-Zombie-Runner
In this section we create a First Person Shooter with a zombie theme. We cover raycasting for shooting and the core mechanics you'd expect in an FPS. This repo is part of our Complete Unity C# Developer 3D course (http://gdev.tv/cu2github). (Ref: ZR_CU2)

# Complete Unity Developer 3D - Zombie Runner

This is the [Complete Unity Developer 3D](http://gdev.tv/cu2github) - one of the most successful e-learning courses on the internet! Completely re-worked from scratch with brand-new projects and our latest teaching techniques. You will benefit from the fact we have already taught half a million students game development, many shipping commercial games as a result.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Complete Unity Developer 3D](http://gdev.tv/cu2github)

## In This Section

In this section we create a First Person Shooter with a zombie theme. We cover raycasting for shooting and the core mechanics you'd expect in an FPS. This repo is part of our Complete Unity C# Developer 3D course (http://gdev.tv/cu2github). (Ref: ZR_CU2)

## How To Build / Compile

## Lecture List

Here are the lectures of the course for this section.


### 1 Welcome To Zombie Runner ###

**In this video (objectives)...**

1. Overview of this section.
2. Demo of the game prototype.

**After watching (learning outcomes)...**

Ready and raring to start this section.


### 2 Zombie Runner Game Design ###

**In this video (objectives)...**

1. Discussion of the game overview screen and core features.
2. Reminder that we're using Unity 2019.1.

**After watching (learning outcomes)...**

Super clear on the game we are making and the feature priorities.

### 3 Adding First Person Controller ###

**In this video (objectives)...**

1. Download Unity Standard Assets.
2. Implement the First Person Controller with RigidBody.

**After watching (learning outcomes)...**

Get and add the First Person Controller to our scene.

### 4 Make A Prototyping Sandbox ###

**In this video (objectives)...**

1. Use Unity's simple prototyping geometry to make a simple level.
2. Make sure there are different obstacles to test the expected functionality in the game.

**After watching (learning outcomes)...**

Create a simple sandbox level for prototyping.

### 5 Using NavMeshAgent For AI ###

**In this video (objectives)...**

1. Add a placeholder enemy with NavMeshAgent component.
2. Bake our NavMesh.
3. Create EnemyAI.cs and add logic to move the enemy towards the player.

**After watching (learning outcomes)...**

Use the NavMeshAgent component to drive the enemy towards the player.


### 6 Getting Stuck & Jittering ###

**In this video (objectives)...**

1. Fix jitter by removing head bob.
2. Stop player getting stuck on walls by adding a physics material.

**After watching (learning outcomes)...**

Fix some issues with our first person controller.


### 7 Enemy AI - Chase Range ###

**In this video (objectives)...**

1. Make the enemy and player more obvious in their positions.
2. Create logic that tells the enemy to move to the target if the target is within the chase range.

**After watching (learning outcomes)...**

Move the enemy to the target if the target is within range.


### 8 Using OnDrawGizmosSelected() ###

**In this video (objectives)...**

1. Use the Unity docs to figure out how to draw a gizmo which shows the chase range of our enemies.

**After watching (learning outcomes)...**

Use gizmos to visualise chase range.


### 9 Enemy AI - Attack If Provoked ###

**In this video (objectives)...**

1. Structure our EnemyAI class so we have logic for the enemy being provoked.
2. Use the nav mesh stopping distance as part of our conditions for attacking or not.

**After watching (learning outcomes)...**

Add to our enemy AI, causing it to attack if provoked.


### 10 Give That Player A Gun ###

**In this video (objectives)...**

1. Import a weapon and attach it to the player.
2. Add a reticle the the UI canvas.

**After watching (learning outcomes)...**

Give the player a weapon asset.


### 11 Introduction To Raycasting ###

**In this video (objectives)...**

1. Overview of how Raycasting works.
2. Add a ray that is cast when the player clicks their shoots (clicks their mouse button).
3. Print to the console the thing that we hit.

**After watching (learning outcomes)...**

Implement raycasting so we can shoot an invisible laser beam.


### 12 Enemy Health & Damage ###

**In this video (objectives)...**

1. Create a public method that reduces enemy's health.
2. Call that method from our weapon and pass in the weapon's specific damage amount.

**After watching (learning outcomes)...**

Lay some smack down on an enemy (well, decrease its hit points).


### 13 Implement A Muzzle Flash ###

**In this video (objectives)...**

1. Create simple code to play our muzzle flash.
2. Create a particle system that looks somewhat like a muzzle flash.

**After watching (learning outcomes)...**

Create a muzzle flash particle effect and play it when the player shoots.


### 14 Creating Shooting Hit Effect ###

**In this video (objectives)...**

1. Twiddle with one of the standard assets particle effects to get something we like.
2. Instantiate the hit impact at the point the raycast hits.

**After watching (learning outcomes)...**

Instantiate a hit effect when we shoot something.


### 15 Introducing Animator Controller ###

**In this video (objectives)...**

1. Discuss animation states.
2. Set up a simple flow from Idle to Move to Attack.

**After watching (learning outcomes)...**

Understand the basics of how Animator Controllers work.


### 16 Creating A Simple Animation ###

**In this video (objectives)...**

1. Create a new animation that we add to idle state.
2. Understand that we can animate properties such as the transform of an object.

**After watching (learning outcomes)...**

Understand how to add simple animations to our animator controller states.


### 17 Animator Transition Conditions ###

**In this video (objectives)...**

1. Set up a trigger and a bool parameter.
2. Cycle through our states by trigging our transition conditions.

**After watching (learning outcomes)...**

Understand how to trigger different states based upon parameter conditions being met.


### 18 Trigger Animation In Code ###

**In this video (objectives)...**

1. Add code to trigger move state.
2. Implement attack state bool to set to true or false depending upon enemy AI logic.

**After watching (learning outcomes)...**

Understand how to use code to trigger animation state changes.


### 19 Use Animation Events ###

**In this video (objectives)...**

1. Create EnemyAttack.cs and create a public method that can be called as an animation event.
2. Create simple animation for attack and add an animation event which calls our attack code.

**After watching (learning outcomes)...**

Use animation events to create precise attack moments.


### 20 Create Player Health Class ###

**In this video (objectives)...**

1. Nifty challenge where you get to chose your difficulty level.
2. Have the enemy damage the player.

**After watching (learning outcomes)...**

Complete our loop where the enemy can hit and damage the player.


### 21 Rotate To Face Target ###

**In this video (objectives)...**

1. Discuss briefly how Vectors work.
2. Rotate the enemy to face the player by using Quaternion.Slerp().

**After watching (learning outcomes)...**

Be clear on how to rotate an object so that it is facing another moving object.


### 22 Game Over User Interface ###

**In this video (objectives)...**

1. Create a Game Over canvas with buttons to reload game and quit.
2. Create a class which contains the methods with the functionality for our buttons.

**After watching (learning outcomes)...**

Create a simple game over menu to ensure we can restart the game when the player dies.


### 23 Create A Death Handler ###

**In this video (objectives)...**

1. Disable and enable our game over menu screen.
2. Give the cursor back to the player.
3. Stop the game so that we aren't seeing weird cursor fighting issues.

**After watching (learning outcomes)...**

Elegantly handle displaying and using the Game Over menu when the player dies.


### 24 Using BroadcastMessage ###

**In this video (objectives)...**

1. Our goal is to have the enemy provoked when shot.
2. We look at a couple of ways to do this, one of which being BroadcastMessage().

**After watching (learning outcomes)...**

Use BroadcastMessage() to call any methods of a particular name on our Game Object.


### 25 Early Gameplay Loop ###

**In this video (objectives)...**

1. Tidy up our sandbox and make a bit of level flow.
2. Tune our Player and enemies so that the game feels the way we want.

**After watching (learning outcomes)...**

Make the game feel like a game with the limited feature set we have at the moment.


### 26 Weapon System Overview ###

**In this video (objectives)...**

1. Examine Rick's prototype to look at how the weapon switching, ammo system and ammo pickups relate to one another.

**After watching (learning outcomes)...**

Be clear on what we are about to undertake with our weapon system.


### 27 Weapon Zoom - Field Of View ###

**In this video (objectives)...**

1. Figure out what would give us a zoomed in effect.
2. Create a connection to our camera and variables for zoomed in and out FOV.
3. Create logic that toggles between zoomed in and zoomed out.

**After watching (learning outcomes)...**

Clear on how to use a camera's field of view to zoom in and out.


### 29 Basic Ammo Functionality ###

**In this video (objectives)...**

1. Create Ammo.cs and add 2 public methods to allow our weapon to communicate with our ammo.
2. Create logic so we can only shoot if we have more than 0 ammo and to decrease ammo each time we shoot.

**After watching (learning outcomes)...**

Add basic ammo functionality where we decrease our ammo when shooting and can only shoot if we have enough ammo.


### 31 Weapon Differentiation ###

**In this video (objectives)...**

1. Create a delay between shots for our weapon.
2. Tune the damage, range, scope and shot delay for our three weapons.

**After watching (learning outcomes)...**

Understand how to create a shooting delay and how to differentiate our 3 weapons.


### 32 Set Active Weapon ###

**In this video (objectives)...**

1. Create a foreach loop which loops through our weapons and sets them active or inactive.
2. Create the framework for the player to be able to select their weapon.

**After watching (learning outcomes)...**

Create the framework for setting weapons active or inactive.


### 33 Player Input To Select Weapon ###

**In this video (objectives)...**

1. Create a way for the player to change weapons by pushing the keyboard numbers.
2. Create a way for players to change weapons by using the scroll wheel.

**After watching (learning outcomes)...**

Give the player multiple ways to change weapons.


### 34 Public Enum & Private Class ###

**In this video (objectives)...**

1. Tidy up a couple of bugs.
2. Create AmmoType public enum.
3. Create AmmoSlot private class.

**After watching (learning outcomes)...**

Have experimented with a public enum and private class.


### 35 Different Weapon Different Ammo ###

**In this video (objectives)...**

1. Assign our weapon to be a particular ammo type.
2. Hook everything up so our weapons decrease ammo from a specific ammo slot.

**After watching (learning outcomes)...**

Have specific weapons use specific types of ammo.


### 36 Quick Bug Fix Challenge ###

**In this video (objectives)...**

1. Identify why our weapon is staying zoomed.
2. Challenge to fix the issue.

**After watching (learning outcomes)...**

Practice finding and fixing bugs.


### 37 Ammo Pickup - Part 1 ###

**In this video (objectives)...**

1. Create a game object which is triggered when the player runs through it and destroyed, printing a witty message to the console in the process.

**After watching (learning outcomes)...**

Create a simple pickup framework that can only be triggered by the player.


### 38 Ammo Pickup - Part 2 ###

**In this video (objectives)...**

1. Set the value and type of the pickup.
2. Create a public method to increase ammo amount.
3. Create prefab variants for each pickup type.


**After watching (learning outcomes)...**

Increase specific types of ammo when we collect that an ammo pickup of that type.


### 39 Let's Add A Zombie ###

**In this video (objectives)...**

1. Import enemy character asset.
2. Hook up new animations to our animator.
3. Add code to trigger enemy death and stop weird death-related behaviours.


**After watching (learning outcomes)...**

Make your game 5 times more awesome by having an enemy who actually looks like an enemy.


### 40 Quick Zombie Attack Challenge ###

**In this video (objectives)...**

1. Figure out why our zombie is not hurting us.
2. Implement a fix to this problem.


**After watching (learning outcomes)...**

Practice hunting down an issue and implementing a solution.


### 41 Flex Your Level Design Muscles ###

**In this video (objectives)...**

1. Create a new scene that will be a more organised level.
2. Sketch out a level design and import that into the scene to use as a reference diagram.


**After watching (learning outcomes)...**

Create a level design diagram to use as a reference for the level creation.


### 42 Add Terrain & Trees ###

**In this video (objectives)...**

1. Add terrain and sculpt it, being sure to add elevation changes.
2. Add trees.
3. Add grass texture and mesh.


**After watching (learning outcomes)...**

Make our forest look interesting by adding terrain and trees.


### 43 ProBuilder For Making Props ###

**In this video (objectives)...**

1. Instal ProBuilder.
2. Use ProBuilder to make shotgun shells.
3. Use ProBuilder to make bullets.


**After watching (learning outcomes)...**

Get comfortable with ProBuilder by making props.


### 44 ProBuilder To Make Rooms ###

**In this video (objectives)...**

1. Install ProGrids.
2. Create the shell for our first room.
3. Create a separate game object that is the roof.

**After watching (learning outcomes)...**

Comfortable using ProBuilder to make rooms.


### 45 ProBuilder To Make Levels ###

**In this video (objectives)...**

1. Use ProBuilder's Poly Shape Tool to trace around our entire level sketch.
2. Flip the normals of our level so we can see the walls on the inside.
3. Add elevation and link everything up.

**After watching (learning outcomes)...**

Comfortable using ProBuilder to make levels.


### 46 Adding Textures With ProBuilder ###

**In this video (objectives)...**

1. Import some textures.
2. Use ProBuilder's Material Editor to add textures.
3. Use ProBuilder's UV Editor to tweak the look of the textures.

**After watching (learning outcomes)...**

Comfortable using ProBuilder to add textures and materials.


### 47 We Need Some Lights ###

**In this video (objectives)...**

1. Create a light with an emissive material.
2. Place lights in our scene.

**After watching (learning outcomes)...**

Able to place emissive lights in your scene.


### 48 Create A FlashLight ###

**In this video (objectives)...**

1. Create a flashlight that is attached to the player.
2. Decay the flashlight angle and intensity over time.

**After watching (learning outcomes)...**

Create a decaying flashlight.


### 49 Create A Battery Pickup ###

**In this video (objectives)...**

1. Create 2 public methods on our flashlight which increase angle and intensity.
2. Create a battery pickup which calls the 2 public methods.

**After watching (learning outcomes)...**

Create a battery pickup which restores the functionality of our flashlight.


### 50 Display Current Ammo UI ###

**In this video (objectives)...**

1. Tidy up, add enemies, rebake navmesh.
2. Add code and UI to display the player's ammo for each weapon cycled through.

**After watching (learning outcomes)...**

Display the ammo for the currently wielded weapon.


### 51 Damage Received UI ###

**In this video (objectives)...**

1. Add some cool effect for when the player takes damage.
2. Trigger the UI effect by turning on and off the canvas.

**After watching (learning outcomes)...**

Provide the player visual feedback for when they receive damage.


### 52 Props & Polish ###

**In this video (objectives)...**

1. Download and add props to your game, being sure to use them to make a story.
2. A challenge for you to make a 5 minute experience that is wow.

**After watching (learning outcomes)...**

Add props and polish your game to make a 5 minute wow.