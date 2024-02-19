# CS415 MP2

## Map and Player
- Build an open-world map (an island)
  - Reference: https://www.youtube.com/watch?v=RCENB-s5POA
- Player characters can run, jump, and fly
- Remove player control for a short time after damage

## Collectible Items
- Gems
- First aid kits
- Items are scattered around the map

## Health System
- Health
  - Debug hotkey `H`: Decreases health
  - Picking up a first aid kit: Increases health
  - Collisions with enemies: Decrease health
- Credit points
  - Debug hotkey `P`: Increases credits
  - Picking up a gem: Increases credits
- Game Over screen
  - Appears when health reaches `0`
  - Allows level restart

## Pursuer Enemies
### Roam and Chase
- Randomly roam
- Run towards the player when perceived
- Resume roaming when the player:
  - Flies, or
  - Hides, or
  - Leaves the perceived distance
### Collision with Player
- Exploding visual and sound effects
- Causes damage to the player
- Explodes when the player collides with the enemy's head

## Cannon Enemies
- Launch projectiles randomly
- Damage the player with projectiles
- Cause damage near the player when a projectile lands
- Explode when the player collides with the top
- Cause damage to the player upon body contact
