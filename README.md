# RPG Battle Game

A small web-based game implementing a step-by-step battle mechanics.

[Game published](https://rpg-battle.netlify.app)

## Game Process Description

A Battle Mage is figthting a Monster.

Combat proceeds by turns. Each turn the computer (Monster) randomly chooses one of the available actions and tells the player what it is going to do. In response the player (Battle Mage) must choose his action.

This is followed by the mutual infliction of damage. Magic armor blocks magic damage, physical armor blocks physical damage.

Once an action is taken, it cannot be chosen again until the cooldown finishes.

Combat is fought until one of the opponents wins.

The player chooses the difficulty (initial health of the Battle Mage) before starting the battle.

## Features

- MVC pattern implemented
- Replay possibility added
- No adaptive design

## Technologies used:

- HTML5
- CSS3
- JavaScript
