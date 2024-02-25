# Overview

This game is an open-world-like adventure where players are tasked to explore an island, collect gems, and combat enemies. The ultimate objective of the game is to collect a specified number of gems while preserving the player's health status.

# Map and Character

The game features an open-world-like map, representing an island amid the ocean, encompassing diverse terrains such as grasslands, forests, hills, and mountains. The intricacy of this map provides players with a 5 to 10 minutes exploration experience.

The player's character has the ability to run, jump, and fly, which offers players to explore the map.

# Health System

The game has a health system, where the player's health status is exhibited in the form of a progress bar at the top corner of the screen.

- Players may lose health points due to enemy attacks.
- The game ends and can be restarted when the player's health points reach 0 or if the player falls into the sea.
- Players can gain health points by destroy enemies.
- Additionally, first aid kits scattered across the map can be collected to augment the player's health points.

# Collectibles

Four types of gems have been dispersed across the map for players to collect and increase their score, which is displayed as a progress bar in the top corner of the screen. To amplify the game's challenge, some gems are located on mountains, while others are hidden within forests. The game ends with a victory when the player collects a certain quantity of gems.

# Enemies

Three types of enemies have been designed for this game:

1. Pursuer Enemy: Typically roams around randomly and charges towards the player upon sensing their presence. If the player is not detected (due to flying, hiding, or moving beyond sensing distance), it resumes its random roaming.
2. Mortar Enemy: Continuously launches projectiles at random angles and distances, targeting areas with a high concentration of gems to escalate the game's difficulty. Explosions are accompanied by visual and sound effects upon the projectiles' impact.
3. Flying Dragon Enemy: It shoots fireballs. Soars mid-air with minimal terrain restrictions, thereby escalating the player's evasion and hiding difficulty. Its other behaviors are akin to the Pursuer.

The enemies can inflict damage on players in the following ways:

- Physical collision with the player
- Player's contact with the mortar body
- Projectile explosion in the vicinity of the player
- Direct hit on the player by a projectile (inflicts higher damage)

When the player takes damage, it is pushed back a few steps, lose control for a second, and visual and sound effects are triggered. Players can destroy enemies by jumping on their heads or tops, which in turn increases the player's health points.

Player must kill (destroy) a certain number of enemies to win. This means that player cannot win by avoiding enemies.

# Design Decisions

- Opting for an open-world-like map design to enhance the player's exploration enjoyment and game complexity.
- Increasing the game's challenge and player's game experience by designing a variety of enemies and damage methods.
- Enhancing the game's strategy and complexity by designing a health system and collectibles, requiring players to balance between gem collection and maintaining health.
- Guiding players to explore different areas of the map by designing various types of gems and their placement, thereby enhancing the game's exploration and challenge aspects.
