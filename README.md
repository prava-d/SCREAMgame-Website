
#**UNDER CONSTRUCTION**

## What is it?

This interactive, voice-controlled, screaming game allows two players to compete against each other: one player controls the character in order to avoid the death traps, while the other player voice-activates the death traps.

## Who are we?

**Camille Xue**
Camille is a first year engineering student at Franklin W. Olin College of Engineering, studying Engineering with Computing. Her project goals for this project included working with new libraries and integrating voice input with the game environment. For this project, Camille worked on the voice integration and the environment set-up.

**Minju Kang**
Minju is a first year engineering student at Franklin W. Olin College of Engineering, studying Electrical Engineering. Her project goals for this project were to learn how to use pygame and to be able to work in a group on a semi-large scale project. Minju's contributions for this projects were the general game structure design, environment set-up, and player set-up.

**Nathaniel Tan**
Nathaniel is a first year engineering student at Franklin W. Olin College of Engineering, also studying Electrical Engineering. Project goals for this project included: learning how to integrate physics concepts into game design and learning more about game design. Nathaniel worked on the physics and collision detection engine and the level editor.

**Prava Dhulipalla**
Prava, like all of her project partners, is a first year engineering student at Franklin W. Olin College of Engineering, studying Electrical and Computer Engineering. Her project goals were to learn more about machine learning and voice integration with a project. As a result, she worked on the neural network and the voice integration aspects of the code.

## How do you play?

Please reference the [README.md](https://github.com/nathanieltan/ScreamGame/blob/master/README.md) on our original repository in order to play our SCREAM game! Have fun!

## What went into this project?

All four project students are part of the ENGR2510 Software Design, Fall 2017 class. As part of a final project project, we elected to create a voice-controlled 'scream' game, while also pursuing personal project goals.

```markdown
Overview of the main parts of the code

_Level Editor_
All individual levels are implemented in seperate files, all in one folder. The code specifies which level, which then finds the correct file in the level folder.

_Physics and Collision Detection Engine_
The physics work off of real life kinematic equations, with the except of the use of trial and error to determine friction and gravity coefficients. The collision detection was fairly basic, as it was two-dimensional and the detection focused on rectangular boxes.

_Environment Set-up_
The environment set-up included generating the sky, the ground, the boxes, and the death-traps.

_Player Set-up_
The player set-up included generating the character, and integrating keyboard commands with character movement.

_Voice Integration_
The game records the character for a small amount of time, and then processes that information to determine whether it was loud enough to make the death traps fall.

_Neural Network_
This trains on the 'a', 'e', and 'o' vowel sounds to differentiate using machine learning methods, specifically a neural network algorithm.
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/prava-d/SCREAMgame-Website/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
