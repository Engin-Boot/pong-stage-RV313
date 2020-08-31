# PONG_SCORING

## Specification

This Module tells about the Scoring Method of the game.

### Scenario : Ball hits the paddle

Given : The game is ON and in progress in the system.

When : The ball hits the Paddle in the Middle.

Then : Ball moves in the opposite x direction, but continues in the same y direction.

### Scenario : Ball hits top or bottom of screen

Given : The game is ON and in progress in the system.

When : The ball hits top or bottom of screen.

Then : Ball reverses its y direction, but continues in the same x direction

### Scenario : Ball hits left or right of screen

Given : The game is ON and in progress in the system.

When : The ball hits left or right of screen.

Then : Ball crosses the paddle and the opposite player gets coin.
