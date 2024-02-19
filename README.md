# CS415 MP2

## Map and Player
- Build an open-world map (an island)
  - Reference: https://www.youtube.com/watch?v=RCENB-s5POA
- Player characters can run, jump and fly

## Collectible Items
- Gem
- First aid kit
- Scattered around the map

## Health System
- Health
  - Debug hotkey `H`: Decrease health
  - Pick up first aid kit: increase health
  - Collisions with enemies: decrease health
- Credit point
  - Debug hotkey `P`: increase credit
  - Pick up gem: increase credit
- Game Over screen
  - When health reaches `0`
  - Restart level

## Pursuer enemies
### Roam and Chase
- Random roaming
- Run to the player when perceive
- Resume roaming when
  - Player flies, or
  - hides, or
  - leaves the perceived distance
### Collision player
- Exploding visual and sound effect
- Damage to player
