# Plan

## Tool: Phaser
## Product: (An dungeon alike game)

---

## Timeline

  <h3>Basic Game Information/Overview</h3>
  <ul>
    <li>Should also include somewhat of an color for the background; black, white, blue, etc (not determined yet)
    <li>Textures should also be included, some blocks contains textures of concrete, stone, bricks and etc</li>
    <li>Maybe also start thinking about how will the mood/the game will shift towards, like the targetted audience; if the game is light-hearted and is meant for knowledge testing + fun then maybe something bright and perhaps colorful</li>
    <li>Fire Boy and Water Girl game as reference: Instead of matching doors, we can make it fun and learnable</li>
    <li>Each level(Mininmum 3-4 levels) consists of different math pieces of general knowledge of stuff, can includes history, math, etcs</li>
    <ul>
      <li>General knowledge for math can include: Algebra related, Geometry related, and others etc (mostly for highschools 9-12)</li>
      <li>General knowledge for history can include: about the U.S history, history about the world, famous people, and etc (ideas related to history basically)
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



#### MVP

- [ ] Task (deadline: X)
  - [ ] Subtask (deadline: X)

#### Beyond MVP

- [ ] Task
  - [ ] Subtask


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
