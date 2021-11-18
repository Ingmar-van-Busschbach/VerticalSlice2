# World of Warcraft Vertical Slice

Vertical slice project of World of Warcraft, recreating the combat system, as well as upgrading the graphics to suit 2020 graphics.

## Summary
- World of Warcraft
- Combat system
- Animation triggered effects
- AI
- Graphics improvements

#### World of Warcraft:
WoW is a MMORPG game where you control a character that has attacks and abilities they can use to defeat enemy characters, that also have attacks and abilities.
WASD is used for walking around, the mouse is used to look around, as well as used to target enemies.

#### Combat system
WoW uses a combo based attack system, where you get more powerful attacks if you attack continuously, up to a limit. There are also special attacks called abilities. Abilities have cooldowns, while attacks do not.

![attack system](https://www.ingmarmatthis.nl/images/VS2AttackSystem.png)

#### Animation triggered effects
All sound effects and particle effects for the attacks were triggered through the animation montages, which allows us to trigger an event on the exact frame we want that event to happen.

![animation trigger](https://www.ingmarmatthis.nl/images/VS2AnimationTrigger.png)

#### AI
There is simple AI in the game that will respond to attacks and return fire. They will also attack automatically if the player gets too close.

![AI combat](https://www.ingmarmatthis.nl/images/VS2AIAttack.png)

#### Graphics improvements
We improved the graphics quality of the game by adding ORM maps, normal maps and emissive textures to the characters. We also used AI upscaling for the player texture, giving it a higher quality. We also made shader improvements and redid the lighting.

![graphics improvements](https://www.ingmarmatthis.nl/images/VS2Graphics.png)
