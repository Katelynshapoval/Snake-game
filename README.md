# Snake Game

This repository contains a simple Snake game implemented in JavaScript. The game features a classic Snake character that the player controls, collecting food items to grow and avoiding collisions with the game's boundaries and its own tail.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Snake Movement](#snake-movement)
- [Food Collection](#food-collection)
- [Game Over](#game-over)
- [Restart](#restart)
## Introduction

The Snake Game is a classic video game where players control a snake that moves around the game board, eating food to grow longer. The game provides a simple yet engaging experience and challenges players to avoid collisions with walls and the snake's own tail.

## Features

### Snake Movement

- The snake can be controlled using arrow keys (up, down, left, right).
- The snake moves at a constant speed (`SNAKE_SPEED`).

### Food Collection

- Food items are randomly placed on the game board.
- When the snake collides with a food item, it grows in length.

### Game Over

- The game ends if the snake collides with the game board's boundaries.
- The game ends if the snake collides with its own tail.

### Restart

- If the player loses, a confirmation dialog appears.
- By clicking "OK," the player can restart the game.

## Gameplay

- The goal is to collect as much food as possible while avoiding collisions.
- Use the arrow keys to control the snake's movement.
- The game ends if the snake collides with the game board boundaries or its own tail.
- After losing, click "OK" in the confirmation dialog to restart the game.
