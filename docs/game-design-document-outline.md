# Game Design Document
## Retro KICK – 3D Soccer Game
**Course:** IT265  
**Game Engine:** Unity  
**Programming Language:** C#  
**Genre:** Sports / Soccer  
**Document Status:** Initial Design – Pre-Development

---

# 1. Overview

## Game Concept
Retro KICK is a 3D soccer game inspired by classic arcade soccer games. The player controls a soccer character on a field and attempts to score goals against an opposing team.

The game will focus on simple, enjoyable soccer gameplay, including movement, ball control, passing, shooting, and defending. The ultimate vision is to create a complete soccer game with multiple teams, different stadiums, tournaments, and going against other players.

## Genre
- Sports
- Soccer
- Arcade

## Target Audience
The game is intended for casual players and soccer fans who enjoy simple sports games. It will be designed to be easy to learn and accessible to players with different levels of gaming experience.

## Game Flow Summary
The player starts at the main menu and selects a game mode. After selecting a match, the player enters a 3D soccer field and controls their character during the game.

The player attempts to score goals while preventing the opponent from scoring. When the match ends, the game displays the final score and allows the player to restart or return to the main menu.

---

# 2. Look and Feel

The game will use a 3D environment created in Unity.

The visual style will be inspired by retro soccer games while using modern 3D objects and environments. The soccer field will include grass, goals, boundary lines, and soccer players.

The game will aim for a colorful and simple visual design rather than realistic graphics.

---

# 3. Gameplay and Mechanics

## Gameplay
The main gameplay involves controlling a soccer player and attempting to score goals.

The player will be able to:
- Move around the soccer field.
- Control and approach the soccer ball.
- Pass the ball.
- Shoot toward the opponent's goal.
- Defend against the opponent.
- Score goals.

## Game Progression
The initial game will focus on a single playable soccer match.

The ultimate version may include multiple matches, tournaments, different teams, and increasing difficulty.

## Mission and Challenge Structure
The main challenge is to score more goals than the opposing team before the match timer reaches zero.

Additional challenges may include winning matches against stronger opponents and completing tournament objectives.

## Puzzle Structure
The game does not contain traditional puzzles. The main challenges involve soccer strategy, positioning, timing, and controlling the ball.

## Objectives
The primary objective is to score more goals than the opponent.

Secondary objectives include:
- Maintaining possession of the ball.
- Preventing the opponent from scoring.
- Successfully passing and shooting.
- Winning the match.

---

# 4. Play Flow

The player will follow this general flow:

1. Launch the game.
2. View the main menu.
3. Select Play.
4. Enter the soccer match.
5. Move the player and control the ball.
6. Pass and shoot to score goals.
7. Complete the match.
8. View the final score.
9. Restart or return to the main menu.

---

# 5. Mechanics

## Rules
- The player must score goals by getting the ball into the opponent's goal.
- The ball moves according to Unity's physics system.
- Players cannot move through solid objects.
- The match ends when the timer reaches zero.
- The team with the highest score wins.
- If the score is tied, the match may end in a draw or use a future overtime system.

## Physics
Unity's physics system will be used to simulate the soccer ball.

The ball will have:
- Rigidbody physics.
- Collision detection.
- Friction and bouncing.
- Movement caused by passing and shooting.

The soccer field and goals will use colliders to prevent objects from passing through them.

## Movement
The player will control a soccer character using keyboard input.

The character will be able to move forward, backward, left, and right across the field.

The ultimate version may include sprinting, turning animations, and different movement speeds.

## Objects
The main objects in the game will include:
- Soccer ball.
- Soccer players.
- Soccer field.
- Goals.
- Goalposts.
- Scoreboard.
- Match timer.

The soccer ball will be controlled through movement and physics rather than being picked up.

## Actions
The player will be able to perform actions such as:
- Move.
- Pass.
- Shoot.
- Sprint.
- Defend.

Actions will be triggered through keyboard or controller input.

## Combat
There is no traditional combat in the game.

The main conflict is between the two soccer teams competing to score goals. Players may attempt to intercept the ball or block shots.

## Economy
The initial game will not include an economy or currency system.

The ultimate version may include unlockable teams, stadiums, or cosmetic items.

---

# 6. Screen Flow

The planned screen flow is:

Main Menu → Game Mode Selection → Soccer Match → Match Results

## Main Menu
The main menu will include:
- Play
- Settings
- Exit

## Game Mode Selection
The player will choose a game mode before entering the match.

## Soccer Match
The main gameplay screen will display the soccer field, players, scoreboard, and timer.

## Match Results
The results screen will display the final score and whether the player won, lost, or drew.

---

# 7. Game Options

The initial game may include basic options such as:
- Sound volume.
- Music volume.
- Keyboard controls.
- Restart match.

Future options may include difficulty settings, camera settings, and controller configuration.

---

# 8. Replay and Saving

The initial version will allow the player to restart a match.

The game will not require a save system because matches will be short and self-contained.

The ultimate version may include saving tournament progress and unlocked content.

## Cheats and Easter Eggs
No cheats or Easter eggs are planned for the initial version.



---

# 9. Story, Setting, and Characters

## Story and Narrative
The game does not have a major story.

The player participates in soccer matches against an opposing team. The main focus is gameplay rather than narrative.

## Game World
The game takes place on a 3D soccer field.

The environment will include:
- Grass field.
- Soccer goals.
- Field markings.
- Stadium surroundings.

Future versions may include different stadiums and environments.

## Characters
The main characters are the soccer players.

The player-controlled character will be able to move around the field and interact with the ball.

The opposing team will attempt to defend its goal and score against the player.

Characters may include basic running, kicking, shooting, and idle animations.

---

# 10. Levels

## Playing Levels
The initial game will contain one soccer field.

The field will include two goals and enough space for players to move and compete.

The main objective is to score goals against the opposing team.

Future versions may include additional stadiums and different field designs.

## Training Level
A training mode may be added in the future.

The training level would allow the player to practice movement, passing, shooting, and ball control without an opponent.

---

# 11. Interface

## Visual System
The game will use a simple and readable interface.

The HUD will display:
- Player score.
- Opponent score.
- Match timer.

The main menu and results screen will use simple buttons and text.

## Camera
The game will use a third-person or elevated camera that allows the player to see the soccer field and follow the action.

The camera may follow the player or focus on the active gameplay area.

## Control System
The planned keyboard controls are:

- W – Move forward.
- S – Move backward.
- A – Move left.
- D – Move right.
- Space – Shoot.
- E – Pass.
- Shift – Sprint.

The controls may be adjusted during development.

---

# 12. Audio, Music, and Sound Effects

The game may include background music inspired by retro sports games.

Sound effects may include:
- Ball kicking.
- Ball bouncing.
- Goal scoring.
- Crowd cheering.
- Match start and end sounds.

The initial version may use basic sound effects before adding more detailed audio.

---

# 13. Help System

The initial game will include basic instructions explaining how to move, pass, shoot, and score.

A simple control guide may be displayed on the main menu or during the first match.

---

# 14. Artificial Intelligence

## Opponent and Enemy AI
The opposing team will eventually use AI to compete against the player.

The AI may:
- Move toward the ball.
- Attempt to intercept passes.
- Defend its goal.
- Shoot when near the player's goal.

The initial version may use simple movement or a basic opponent before implementing advanced AI.

## Non-Combat and Friendly Characters
Friendly teammates may assist the player by moving into position and receiving passes.

In the initial version, teammates may be stationary or use basic movement.

## Support AI
Future AI systems may control teammates and opposing players.

## Player and Collision Detection
Unity's physics and collision systems will be used to detect interactions between players, the ball, and the environment.

## Pathfinding
The ultimate version may use pathfinding or simple AI steering to help players navigate the soccer field.

---

# 15. Technical

## Target Hardware
The game will initially target Windows PC.

## Development Hardware and Software
- Unity Game Engine.
- C# programming language.
- Visual Studio or Visual Studio Code.
- Windows computer.
- GitHub for project version control.

## Network Requirements
The initial version will be a single-player offline game.

Online multiplayer may be considered as a future feature but is not required for the initial project.

## Game Art
The game will use 3D models for the soccer field, players, ball, and goals.

The visual style will be retro-inspired and relatively simple to keep the project manageable.

Game art may include:
- Soccer player models.
- Soccer ball model.
- Grass and field textures.
- Goal models.
- Basic player animations.

---

# 16. Development Scope

## Ultimate Game Vision
The ultimate version of Retro KICK may include:
- Multiple soccer teams.
- Multiple stadiums.
- Tournament mode.
- Player animations.
- Sound effects and music.

## Initial Development Plan
The initial version will focus on creating a playable 3D soccer game in Unity.

The main development goals are:
- Create a soccer field.
- Add a controllable player.
- Add a soccer ball with physics.
- Implement movement.
- Implement passing and shooting.
- Add goals and scoring.
- Create a basic match timer and scoreboard.

Additional features will be added if time allows.

The goal is to develop a simple but playable soccer game while learning Unity's 3D development tools and C# programming.
