Class Select:

When entering your first combat you will be presented with a prompt to select your class. Press the in game stats button(z) for Rogue, the strafe button(alt) for Knight, the attack button(left-click or control) for warrior, and the voice chat button(/) for mage.

Combat:

Fights are started by you or allies shooting an enemy or being shot by an enemy. When combat starts use the button for class selection to use you skills, each class has 3 unique skills and the same basic attack. Winning a fight grants you 50 exp and cash. Leveling up fully heals health and mana while also increasing your stats based on class. Use right click to close the damage window and continue combat.

Shop:

Press tab to open the shop menu. All items cost 200 cash.use voice chat to buy an item, strafe to close the menu, attack then right click to move through the menu, and in game stats to equip an item.

Skills:

Basic attack: deals hero->pow * 10 / villain->def damage and restores 10 mana.

Rogue: 

•  Multi-Attack: deals (hero->pow * 10 / villain->def) + 9 damage, costs 10 mana

•  Speed strike: deals hero->spd * 30 / villain->def damage, costs 20 mana

•  Blitz: deals hero->spd * hero->pow * 30 / villain->def damage, costs 50 mana

Knight:

•  Guard Stance:Halves damage of 1 enemy attack, costs 10 mana

•  Shield Bash: deals hero->def * 25 / villain->def damage, costs 20 mana

•  Power Swing: deals hero->def * hero->pow * 30 / villain->def damage, costs 50 mana

Warrior:

•  Rage: next player attack deals double damage, costs 10 mana

•  Sacrificial Hit: deals hero->pow * 50 / villain->def damage, costs 20 mana and 10 hp

•  Health Potion: Heals player 50 hp, costs 50 mana

Mage:

•  Fire ball: deals hero->pow * 40 / villain->def damage, costs 10 mana and 1 additional turn

•  Life Drain: deals hero->pow * 10 / villain->def damage, costs 20 mana and heals the player based on damage dealt

•  Meteor:hero->pow * hero->pow * 60 / villain->def damage, costs 50 mana and 2 additional turns

Stats:

Rogue base stats:

•  Pow: 2

•  Spd: 4

•  Def: 1

Rogue growths:

•  Pow: +1 per level

•  Spd: +2 per level

•  Def: +1 every other level

Knight base stats:

•  Pow: 2

•  Spd: 1

•  Def: 4

Knight growths:

•  Pow: +1 per level

•  Spd: +1 every other level

•  Def: +2 per level

Warrior base stats:

•  Pow: 4

•  Spd: 1

•  Def: 2

Warrior growths:

•  Pow: +2 per level

•  Spd: +1 every other level

•  Def: +1 per level

Mage base stats:

•  Pow: 4

•  Spd: 2

•  Def: 1

Mage growths:

•  Pow: +2 per level

•  Spd: +1 per level

•  Def: +1 every other level

Weapon Stats:

Dagger:

•  Pow: 1

•  Spd: 3

•  Def: 2

Long Sword:

•  Pow: 3

•  Spd: 1

•  Def: 2

Short Sword:

•  Pow: 3

•  Spd: 2

•  Def: 1

Shield:

•  Pow: 2

•  Spd: 1

•  Def: 3

All cost 200 cash

Enemy Stats:

•  All enemy only do 1 attack:

•  Damage formula: ((villain->pow * 10) / (hero->def)) + 1

•  Pow stat: (enemy->spawnArgs.GetInt("health")) / 15) + 1

•  Def stat: (enemy->spawnArgs.GetInt("health")) / 15) + 1
