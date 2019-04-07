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
