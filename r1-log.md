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
