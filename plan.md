# Plan

## Tool: Phaser
## Product: (An dungeon puzzle like game)

---

## Timeline

N/A

---
<h3>Basic Game Information/Overview</h3>

**FYI**: *INFORMATION PROVIDED BELOW MIGHT CHANGE OVER THE COURSE OF DEVELOPING THE GAME*

  <ul>
    <li>Should also include somewhat of an color for the background; black, white, blue, etc (not determined yet)</li>
    <li>Textures should also be included, some blocks contains textures of concrete, stone, bricks and etc</li>
    <li>Maybe also start thinking about how will the mood/the game will shift towards, like the targetted audience; if the game is light-hearted and is meant for knowledge testing + fun then maybe something bright and perhaps colorful</li>
    <li>Fire Boy and Water Girl game as reference: Instead of matching doors, we can make it fun and learnable</li>
    <li>Each level(Mininmum 3-4 levels) consists of different math pieces of general knowledge of stuff, can includes history, math, etcs</li>
    <ul>
      <li>General knowledge for math can include: Algebra related, Geometry related, and others etc (mostly for highschools 9-12)</li>
      <li>General knowledge for history can include: about the U.S history, history about the world, famous people, and etc (ideas related to history basically)</li>
    </ul>
    <li>Lives system can be introduced: The player is granted 4-5 lives(Not determined for the exact amount) and if they step on the trap they lose 1 live, if they lose all of their lives, then they have to retry, restarting the whole thing over again</li>
    <li>Also could include elements of traps concept and things that can trigger death for the player (ingame)
      <ul>
        <li>Could include spike  traps, where some are glued in the floor, some on the celling top, some can have hidden mechanic where if the player moves to an certain area that           spike trap triggers</li>
        <li>Can also include, lava; the player has to jump over the lava otherwise they will died and be respawn to the beginning of the spawn-point</li>
      </ul>
    <li>One player only; the player model (not determined yet)</li>
    <ul>
      <li>Must includes the key usage of movements; right/left key for movements left and right, up and down key for jumping up and down</li>
      <li>Can incorporates elements of DOM; functions like keypress</li>
    </ul>
  </ul>

<h3>Code Usage</h3>
  <ul>
    <li>As earlier mentioned, we need keypress for the movements of the player</li>
    <li>Maybe the usage of arrays?<li>
      <ul>
        <li>Why arrays? Because it can help store array of numbers and stuff in that list. For example: if the user recieved answer is "Who is the first president of the U.S", and inside the array variabled called "President" would be ["George Washington, Abraham Lincoln"], and the if function would make it so if the user didn't choose 0 of the array it would return false</li>
      </ul>
    <li>Creating multiple variables:</li>
    <ul>
      <li>Needs many variable for the usage of storing data and what the input value of the user types and keeping track of stuff.</li>
      <li>For example var userLives = 5; we store the 5 lives in userLives, so that we can incorporate that into the code whenever the user loses an live</li>
    </ul>
    <li>Usage of basic javascript included?</li>
    <ul>
      <li>For example: If conditions; if the user recieves an math problem and asks them 50 + 50, if the user inputs the value of 100 (which is true), then it would return "you just gain an fragment that is needed in order to unlock the next stage!" and if the user input is NOT 100 then it would return "You got the answer wrong, try again!"</li>
      <ul>
        <li>In regards to the function, an addEventListener is also required, so that the key is waiting for the event to happen so the function can start to do its own thing</li>
      </ul>
      <li>Previously mentioned we would also have functions, for keypress; DOM and JS so that when an user presses the left key their sprite would move towards the left by x amount of distances, and the smae for right, up and down key</li>
    </ul>
  </ul>

### Roles
*Common patterns of role control in the making of the game*
- **Xin Yu** = The Architect and Builder; involved in some part of JS managment
- **Rain** = The Assister and JS management; involved slighty in the Styling of the game

#### MVP
<!--REMEMBER WHEN DONE WITH A TASK, X IT OUT VIA THE BRACKET AND AT THE END OF THE TASK TEXT, ADD THE DATE YOU FINISHED IT AT-->
- ### 1) Setting things up & The Basics (Feb 17th)
  - [] Create the necessary folders, files, textures (**Xin Yu**)
  - [] Set up phaser completely and a game canvas with a decided width and height; includes basic/simple CSS styling to center the canvas (**Xin Yu**)
  - [] Preload all (if there is any) textures in the preload function (**Xin Yu**)
  - [] Create platforms with physics, collision, and texture (**Rain**)
  - [] Add 2 sprite characters with physics, collision, and texture (**Rain**)
  - [] Add a collectable with physics, collision, and texture (**Rain**)

- ### 2) User Interactability (Mar 2nd - Mar 8th)
BELOW UNTIL NEXT TEXT, ALL SHOULD BE DONE IN `function update`
  - [] Implement Arrows Key + WASD Movement controls for the sprites (**Rain**)
  - [] Make it that sprites can collect collectables (**Xin Yu**)
  - [] Add a concept of death of the sprites when interacting with something (i.e., traps) (**Rain**)
    - [] Add some entity/thing that can kill the sprite + physics/collision/texture (**Xin Yu**)
    - **NOTE THAT THIS CONCEPT OF DEATH WILL BE REFINED FURTHER DOWN THE MVP**

- ### 3) Levels + Functionality (Mar 9th - Mar 15th)
  - [] Create different levels (**Xin Yu**)
  - [] Create a "key" system that unlocks new levels; sprites can pick it up like collectables (**Xin Yu**)
  - [] Make it that the key the sprite is holding disables a level barrier near the end of each level (unlocks something) (**Rain**)
  - [] Consider transferring the user onto the next level when the sprite interacts with the "winning line" (**Rain**)
  - [] Users have to answer correctly to the prompt(s) in order to obtain the key (**Xin Yu**)

- ### 4) Restarting + Concept of Death (Mar 16th - Mar 22nd)
  - [] Make it that a kill-item (static) instantly kills the sprite when colliding (**Rain**)
  - [] Develop a restart system when the sprite is killed by a kill-item; restart back to the same level (**Rain**)

- ### 5) Map Development + Design (Mar 23rd - Apr 1st)
  - [] Create obstacle courses with kill-items to make it harder; as levels progress, maps get more difficult (**Xin Yu; Rain will assist**)
  - [] Find places on the level to put the "winning line", spawn area, key location + the riddle to solve to get to it (**Xin Yu; Rain will assist**)

#### Beyond MVP

- []
  - []


<!-- EXAMPLE

## Tool: APIs
## Product: Green Glass Door riddle app

## Timeline

### MVP

- [ ] Front-end
  - [x] Webpage to collect input from user (deadline: 4/15)
  - [ ] Webpage to display "yes, but a ___ can't" or "no, but a ___ can" (deadline: 5/1)
- [x] Back-end
  - [x] Use regex to test whether or not the word can go through the GGD (deadline: 3/1)
  - [x] Use the Twinword API to find related words (deadline: 3/15)
    - [ ] Iterate through the words until an opposite example can be found (deadline: 4/1)

#### Beyond MVP

- [ ] Use another API to make sure the opposite example is a noun
- [ ] Automate notification of API limit to make sure I don’t exceed free quota
- [ ] A multiple choice quizzer that will test the user’s knowledge of the solution

-->





<!-- DO NOT USE THIS YET

#### Peer Feedback

| Name | Glows | Grows |
| -------- | ------- | ------- |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

-->
