# Day 1 - Doodle Dash

A platformer game with Flutter and Flame! In the Doodle Dash game, inspired by Doodle Jump, you play as either Dash (the Flutter mascot), or her best friend Sparky (the Firebase mascot), and try to reach as high as possible by jumping on platforms.

Codelab: [Lab:Building a game with Flutter and Flame](https://codelabs.developers.google.com/codelabs/flutter-flame-game)

## Game's Features

- A sprite that can move horizontally and vertically
- Randomly generated platforms
- A gravity effect that pulls down your sprite
- Game menus
- In-game controls like pause and replay
- The ability to keep score

## Game Play

Doodle Dash is played by moving Dash left and right, jumping on platforms, and using power ups to increase her ability throughout the game. You start the game by choosing the initial difficulty level (1 through 5), and clicking `Start`.

###  Levels

There are 5 levels in the game. Each level (after level 1) unlocks new features.

- Level 1 (default): This level spawns `NormalPlatform` and SpringBoard platforms. When created, any platform has a 20% chance of being a moving platform.
- Level 2 (score >= 20): Adds `BrokenPlatform` that can only be jumped on once.
- Level 3 (score >= 40): Unlocks the `NooglerHat` power up. This special platform lasts for 5 seconds and increases Dash's jumping ability by 2.5x her normal velocity. She also wears a cool noogler hat for those 5 seconds.
- Level 4 (score >=80): Unlocks the `Rocket` power up. This special platform, represented by a rocket ship, makes Dash invincible. It also increases Dash's jumping ability by 3.5x her normal velocity.
- Level 5 (score >= 100): Unlocks `Enemy` platforms. If Dash collides with an enemy, it's an automatic game over.

## Getting Started

- Clone this Repo
- Run `flutter pub get`
- and voila!!