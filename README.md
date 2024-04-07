[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [your name]
### Student number: [your student number] 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
1. Problem-solving skills The game presents players with obstacles, puzzles, and enemies that require quick thinking and strategic planning to overcome. Players learn to analyze situations and develop effective solutions to progress through levels.
2. Hand-eye coordination  The game requires precise control and timing. Players improve their hand-eye coordination as they navigate obstacles, jump on platforms, and avoid enemies.
3. Persistence and resilience The game can be challenging, with difficult levels and tricky obstacles. Players learn the value of persistence and resilience as they repeatedly attempt to overcome challenges and progress further in the game.
4.Risk assessment. Players must assess risks and rewards when deciding how to approach obstacles and enemies. Learning when to take risks and when to proceed cautiously is a valuable skill that can be applied in various contexts.
In the game, players will discover health potions, but they need to take risks to get them.

### 1.2. Drama
My game intensity curve goes from low to high and then slowly decreases.
The first part of the game involves the player doing some simple jumps and dodging a handful of monsters. In the second part of the game, the player has to avoid more monsters. Before entering the third part (the cave), the player can recover 3 health points by defeating the monster, which will feel relaxed, while entering the cave requires the player to quickly break obstacles and avoid the attack of the monster, which will be very tense.

### 1.3. Challenge

1. Platforming challenges. Players must master precise jumps and timing to progress.
2. Enemy encounters: Throughout the game, players encounter various enemies, each with its own behavior and attack patterns. Players must learn how to effectively defeat or avoid these enemies to continue their journey.
3. Precision and timing: This game demands precise control and timing from players, particularly when executing jumps, dodging obstacles, or navigating tight spaces. Small errors in timing or execution can result in failure.
In this game, the player encounters few monsters in part1 but will deal with more and more monsters with the progression of the game.

### 1.4. Exploration

1. Movement. Movement is essential for exploring different areas of the level, jumping over obstacles, and reaching higher platforms.
2. Observation: Players observe the environment for clues.
3. Trial and error: Exploration often involves experimentation and trial and error. Players may try different paths, jumps, or actions to uncover secrets or progress through the level.
In the game, players will find movable boxes and they will try to move the box to reach higher platforms. When the player explores the cave, there will be many monsters and acid. Players will be impressed by the tension and difficulty of exploring the cave. With the progress of the game, players will pick up powerful weapons and they will explore how to use those weapons.


## 2. Core Gameplay (~400 words)


2.1 spitters. Spitter is a powerful monster in the game. At the beginning of the game, if the player stands still on the ground, they will be attacked by underground spitters, forcing them to start the game and giving them a sense of urgency.
2.2 Spike spike does not actively attack players, so I placed a spike at the beginning of the game to familiarize players with enemies in the game. At the same time, I found that spikes cannot be killed by weapons and can block bullets, so I placed bullet-blocking spikes in part three.
2.3 Moving Platforms Moving platforms are elements in the game that test players' jumping skills. I placed moving platforms at the beginning of the game to test players' jumping skills while also taking them to where they want to go.
2.4 passthrough platforms Fixed platforms are where players move most often, and I added various monsters and props on top of them to enrich their content.
2.5 chompers Chompers are close-range monsters that players need to kill or avoid. I placed them on platforms to increase the difficulty of the game.
2.6 keys Players obtain victory in games by accumulating keys to open doors; I placed each key in a location that requires effort from players through jumping and avoiding monsters.
2.7 checkpoints When encountering strong acid, players will return to checkpoints; placing checkpoints at the beginning of games would undermine player confidence, so I placed them midway through games instead.
2.8 health pickups Some health potions require players to defeat large numbers of monsters before obtaining them, giving players more choices.
2.9 weapon pickup (staff) I put staffs in mid-game for players to kill monsters. If I put it in the early game, it will make the game much easier, which will make the player feel bored.
2.10 weapon pickup (gun) I put guns before entering part three so that players could use guns to kill monsters outside caves and get healing before entering caves. A gun is also useful for killing cave monsters.
2.11 acid Before entering part three, the player will encounter acid, The Player needs to be careful and quickly break obstacles to enter the cave.


## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.
Iterative design has greatly helped my game design. Firstly, at the beginning, the difficulty levels of the three parts of the game were not evenly balanced, with the first part being too difficult and causing players to frequently die in that section. Through iterative design, I was able to better balance the difficulty levels of all three parts of the game. Secondly, initially there was no design for moving boxes in the game. However, in order to attract more player interest, I added two movable boxes in the game which required players to use their brains to push them and reach places they couldn't access before. Additionally, there were frequent bugs in the early stages of the game such as boxes falling underground etc., but through iterative design I was able to fix most of these bugs. Finally, I continuously adjusted the difficulty level of the third part of the game so that most players could not win on their first attempt; however by learning from mistakes and gaining experience they could quickly find a way to victory. In summary: after obtaining key from cave entrance,the difficulty level decreased significantly.In future designs,it may be appropriate to increase some difficulties.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


