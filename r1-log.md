# #100DaysOfCode Log - Round 1 - Alexander Anich

The log of my #100DaysOfCode challenge. Started on March 31st, Sunday, 2019.

## Log

### R1D0 - 3/31/2019
**Today's Progress**: 
Day 0 of #100DaysOfCode Challenge! I worked on exploring the new UIElements API that will be available for Editor UI in Unity 2019.x. I got my project setup and a repo established on Github (linked below) and created a bare-bones "Hello, World!" using the new VisualElement C# class.

**Thoughts**:
Project initialization always takes more time than I expect, especially on an OS I'm not familiar with (Windows). Although, from just initializing the "Hello, World!", I get a giddy feeling that I'll find this a lot more comfortable for creating Editor UI coming from a web-developer background! I'm excited to play around with the UXML and USS next! :) 

**Link to work**:
[repo](https://github.com/warlokkz/UIElementsExperiment)

### R1D1 - 4/1/2019
**Today's Progress**: 
Day 1 of #100DaysOfCode Challenge! Continuing exploration of the UIElements API. Created a layout of visual elements using the FlexBox implementation available as a part of UIElements.

**Thoughts**:
I'm glad that the FlexBox API is mostly what I expected it to be. One thing that I found lacking was that there was not a "justifySelf" option, which made it difficult to add justification to a specific element among a list of others.

**Link to work**:
[repo](https://github.com/warlokkz/UIElementsExperiment)

### R1D2 - 4/2/2019
**Today's Progress**: 
Moved all of the inline-styles into a schnazy new USS file. Experimented with extending the VisualElement class into new Components, as opposed to building them inline. Also used the Manipulator class to turn the boxes red on click.

**Thoughts**:
I think there is a lot of potential in this new system, given that Unity is providing good primitive components to work with I suspect that porting a web Frontend framework will not be so hard (if it deserves to be here.)

**Link to work**:
[repo](https://github.com/warlokkz/UIElementsExperiment)

### R1D3 - 4/3/2019
**Today's Progress**: 
Following the example provided by Unity, played around with the Toolbar UIElement primitives to build part of a todo-list.

**Thoughts**:
The Toolbar primitives are quick to setup and using flexbox to position them is a breeze. Building custom tools might seem like less of a chore in Unity now. 

**Link to work**:
[repo](https://github.com/warlokkz/UIElementsExperiment)

### R1D4 - 4/4/2019
**Today's Progress**: 
Broke out of following Unity's example and tried implementing a leader-board with UIElements in the Editor. Got the basic structure down.

**Thoughts**:
FlexBox is glorious. I'm kind of upset that they didn't implement `justify-self` for items in a flexbox container - I was used to using that.

**Link to work**:
[repo](https://github.com/warlokkz/UIElementsExperiment)

### R1D5 - 4/5/2019
**Today's Progress**: 
Added a manipulator class for adding mouse events and styling to the individual scores on the leaderboard.

**Thoughts**:
I'm trying to break things into components, because I'm so used to coding in React. But I don't know what best practice for creating UI in C# will be like.

**Link to work**:
[repo](https://github.com/warlokkz/UIElementsExperiment)

### R1D6 - 4/6/2019
**Today's Progress**: 
Started a new prototype Unity project to play with their new ECS system. Got familiar with some of the constructs, but didn't get my axis movement system working yet.

**Thoughts**:
It seems like the ECS API is still in heavy development, many of the examples I've seen from 2018 are either deprecated or the API has changed drastically.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D7 - 4/7/2019
**Today's Progress**: 
After some headache of patching compile errors, got the ECS working and rendering a component (cube). Then got it moving using a component system which was exciting!

**Thoughts**:
An important package to have installed in Unity is the Hybrid.Renderer to render the components. For a while I was expecting the cube to be there automatically from conversion.... 

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D8 - 4/8/2019
**Today's Progress**: 
Spent a little more time reading and understanding the purpose + usage of ECS - and the "DOTS" stack in Unity. Got my little cube moving by mapping Input -> InputSystem -> MovementSystem. Hype!

**Thoughts**:
I really appreciate the separation of concerns that you get from a ECS style structure. Data is separated from functionality and it reminds me of a functional style of development.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D9 - 4/9/2019
**Today's Progress**: 
Changed the motion of the movement to an xz-axis, added a small quad to represent the ocean that the ship will move on. Tried to get click-to-move working with a ClickSystem.

**Thoughts**:
It seems that the click-to-move isn't working because Raycasts are not registering as hit inside of the pure ECS systems. Going to need to rethink how this is going to work.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D10 - 4/10/2019
**Today's Progress**: 
Added the Physics Preview package, following along samples of integrating the Physics library with a component system. Got a raycast to register off a click!

**Thoughts**:
The preview packages are in very early release and it sometimes makes it difficult to work with.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D11 - 4/11/2019
**Today's Progress**: 
Upgraded dependencies for unity.physics (up to date with current ECS, hurray!). Fleshed out the rest of the ClickSystem based on examples put out by the Unity team to transfer a Raycast to the MoveSystem to translate the object.

**Thoughts**:
There is quite a bit of the Job/ECS interaction that I do not fully understand, but I'm trying my best to analyze it while I create a working concept.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D12 - 4/12/2019
**Today's Progress**: 
Not much progress today. Explored different ways of moving the character using the move system.

**Thoughts**:
I thought a NavMesh would be interesting to bring in, but I think I wanted to just use the physics to move the ship.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D13 - 4/13/2019
**Today's Progress**: 
Tried to refactor the movement system to orient the cube in the direction of the mouse-click, then move forward, but I just got a randomly spinning cube.

**Thoughts**:
I like this new approach as it is more straightforward in what to accomplish.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D14 - 4/14/2019
**Today's Progress**: 
Taking a break from the "ship" project to go through and learn some of the fundamentals of Unity without ECS.

**Thoughts**:
I have a general grasp over the process of how physics and scripting works in Unity, but combining my inexperience with movement control and a new system like ECS is hard to juggle at the same time.

**Link to work**:
n/a

### R1D15 - 4/15/2019
**Today's Progress**: 
Studied physics fundamentals in Unity, like physics materials, joints and purposeful constraints in the editor.

**Thoughts**:
There is a lot of power given to the game developer through the Editor to play with Physics, but I'm curious on how to elegantly incorporate these components into a complex code base.

**Link to work**:
n/a

### R1D16 - 4/16/2019
**Today's Progress**: 
Studying more physics constructs in Unity: this time ragdolls and wheel colliders. Went down the rabbit-hole of looking at other ECS creations on the Unity Forums.

**Thoughts**:
DOTS seems to be a large movement within the Unity organization. Definitely need to spend more time in it.

**Link to work**:
n/a

### R1D17 - 4/17/2019
**Today's Progress**: 
Used a navmesh in a example project to move a character with a navmesh agent.

**Thoughts**:
NavMeshes and NavMesh agents make the character movement so easy to do in Unity. I want to try and use this in ECS.

**Link to work**:
n/a

### R1D18 - 4/18/2019
**Today's Progress**: 
Beginning work on incorporating a NavMeshAgent system into the existing ECS code.

**Thoughts**:
I haven't a clue what I'm doing. but I'm trying to find examples of navmesh + ecs.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D19 - 4/19/2019
**Today's Progress**: 
More work (lots of reading) on trying to incorporate NavMeshAgents for the character movement system.

**Thoughts**:
Actually beginning to understand the decisions behind the example I'm following, which is nice so I think I have a direction to head in next time.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D20 - 4/20/2019
**Today's Progress**: 
Worked on getting the data from ClickSystem into the NavigationSystem (being reworked from MovementSystem).

**Thoughts**:
I'm so grateful for examples on the internet.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D21 - 4/25/2019
**Today's Progress**: 
Lost a few days because of the flu. Back on the horse with great success! Got my click to move working :*). Its so beautiful.

**Thoughts**:
You cannot box in a value type (components) inside of a job that is BurstCompiled, it doesn't support it. This includes the Debug.Log call which attempts to box the value into an object. This caused frustration. If you desperately need to log inside of the job execute, then remove the BurstCompile attribute while logging. 

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D22 - 4/26/2019
**Today's Progress**: 
Added in a little low-poly ship for flair in the project. Tried to combat the rotational fighting that happens when the ship reaches the destination, but I could not find a way yet. 

**Thoughts**:
Need to study more quaternions.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D23 - 4/27/2019
**Today's Progress**: 
Got the twitchy rotations from happening when the ship reached it's destination. Trying to refactor the click system so that it can produce a singleton value for other systems to use.

**Thoughts**:
I'm starting to wrap my head around when to use what construct where now.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D24 - 4/28/2019
**Today's Progress**: 
refactored the clickSystem's singleton implementation to be more aligned with the values of ECS, removing state from the ClickSystem.

**Thoughts**:
This part was a bit of a breakthrough for me! Its hardening my concepts of how systems should interact with one another, not by referencing eachother, but by reading eachother's components that they modify.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D25 - 4/29/2019
**Today's Progress**: 
Added the rough implementation of a cursor spawning system that spawns a cube wherever the user clicks (as visual feedback to know they clicked there).

**Thoughts**:
I can see the benefit of extracting your behavior into systems and state into components, it makes the contracts between systems very easy to reason about!

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D26 - 4/30/2019
**Today's Progress**: 
Refactored a bit today, particularly file structure, organizing components and systems into folders. I fixed an issue where the CursorSpawnSystem was spawning hundreds of cursors because of the ClickData. Now it spawns one per click

**Thoughts**:
There are times where I want to write things imperatively, or to let a system maintain state - similar to an OOP approach - but I am trying my best to stay close to the virtues of a ECS architecture.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D27 - 5/1/2019
**Today's Progress**: 
Implemented a small despawning system for cursors, that makes a spawned cursor destroy it's entity after a specified lifetime.

**Thoughts**:
ECS is awesome.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D28 - 5/2/2019
**Today's Progress**: 
Played around with particle systems and integrating it into the hybrid renderer... but didn't get very far.

**Thoughts**:
There is a lot of work to be done to get existing systems to play nicely with ECS.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D29 - 5/5/2019
**Today's Progress**: 
Refactored the click system to re-use the ray-casting logic for a new firing system upcoming.

**Thoughts**:
I've stumbled into an issue with ordering of systems, which seems to be an issue once I've created a singleton entity (which means there is now an order
dependency). I may need to create a small system manager, where I can dictate the exact order in which the systems are initialized.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D30 - 5/6/2019
**Today's Progress**: 
Created a ProjectileSpawner component, system and proxy for converting a prefab into a future projectile. Got it spawning on left-click for now.

**Thoughts**:
I took a different approach for handling the player input, instead of querying for the click singleton I'm looping over the input data, and querying for the spawner entity. I don't know if there is a greater benefit, but I feel like it makes more sense compared to iterating over the spawner components.

**Link to work**:
[repo](https://github.com/warlokkz/ship)


### R1D31 - 5/7/2019
**Today's Progress**: 
Created a ProjectileMovementSystem that will move the projectiles along their direction path and decay their velocity over time.

**Thoughts**:
I had a lot of fun tweaking the values for the projectiles this time around! :)

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D32 - 5/8/2019
**Today's Progress**: 
Created a despawning system for projectiles.

**Thoughts**:


**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D33 - 5/9/2019
**Today's Progress**: 
begun refactoring projectileMovementSystem to use the physics preview (with ties into DOTS).

**Thoughts**:


**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D34 - 5/10/2019
**Today's Progress**: 
Projectiles now use physics to determine trajectory. Added CollisionFilters for Raycast hits.

**Thoughts**:
DOTS Physics is attempting to replace as much as it can - the PhysicsShape is a replacement for Colliders.

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D35 - 5/13/2019
**Today's Progress**: 
Lot's of reading about ECS. Read mainly about strategies to combat garbage by batching command buffer requests. Not much closer to implementing it, however.

**Thoughts**:

**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D36 - 5/14/2019
**Today's Progress**: 
Created a TrackSystem to move tagged Entities backwards against a flow of a current.

**Thoughts**:


**Link to work**:
[repo](https://github.com/warlokkz/ship)

### R1D37 - 5/15/2019
**Today's Progress**: 
Refactored the TrackSystem heavily, trying to use the notion of "ticks" instead of updating individual systems by Time.delta time. Hopefully this will allow more control over how/when things are updated.

**Thoughts**:
I'm starting to pierce through to the next level of my understanding of ECS, which is really nice. The pattern is beginning to reveal itself more to me.

**Link to work**:
[repo](https://github.com/warlokkz/ship)