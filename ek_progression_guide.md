# Elite Knight hunting guide by comfort (Tibia, Nov 2026)

This guide is for anyone playing an Elite Knight alone, including players who are brand new to Tibia. It answers one question at every level: **where can I hunt without stress, and still make good experience and gold?**

Everything here describes Tibia as it is in November 2026, after the big vocation changes of June 2026. Older guides and videos may give different advice, because spells, damage and potions changed a lot.

## How to use this guide
The game has many systems that make a knight stronger: imbuements, charms, the Wheel of Destiny and more. Each one helps, but each one is also something new to learn, buy or keep track of. This guide adds them **one at a time**, in sections:

- **Section 1, Basic mechanics:** just your weapon, one attack spell, one healing spell and potions. Full hunting ground lists.
- **Section 1a, Stealth Ring:** a ring that hides you from many monsters. Hunting ground lists.
- **Section 1b, More spells:** the other knight spells (outline).
- **Section 2, Imbuements:** life and mana leech on your gear. Full hunting ground lists.
- **Sections 3 to 6:** charms and prey, the Wheel of Destiny, weapon proficiency, and the full late-game setup (outlines for now).

Start in Section 1. Find your level in the hunting ground tables and pick a hunting ground near the top of the list: those are the most comfortable ones. When hunting there feels easy, move on to the next section and see which new hunting grounds open up.

If you test a hunting ground, write down how it went in `spot_tests.md`. Tested hunting grounds are marked with ✓ and use real numbers instead of estimates.

## Words you'll see
- **HP and mana:** your health and the energy you spend on spells. A knight has about 185 + 15 × (level − 8) HP: 815 at level 50, 2,075 at level 134.
- **Spawn:** the monsters that live in a hunting ground and come back after you kill them.
- **Box, boxing:** letting several monsters surround you and hitting them all at once with an area spell. Bigger boxes kill faster but hurt more.
- **`exori`:** the knight's basic area attack (level 35). It hits every monster standing next to you.
- **`exura ico`:** the knight's basic healing spell.
- **XP/h, loot/h:** experience and gold (the value of what monsters drop) per hour of hunting.
- **Depot:** your storage in each city. It's also where the Market is.
- **Market:** where players buy and sell items. Many monster drops sell there for far more than shops pay.
- **Band:** a level range in the hunting ground tables, such as 40–50.

## Comfort: the idea behind this guide
Some hunting grounds ask almost nothing of you: you walk in, attack, and never need to heal. Others ask a lot: you have to watch your health all the time, carry many potions, avoid certain rooms, or bring special gear. This guide calls that difference **comfort**.

Comfort depends on your level. A hunting ground that is dangerous at level 50 can be relaxing at level 130, because you have more HP and hit harder.

Every hunting ground gets two grades from **0 (most comfortable) to 3 (least comfortable)**:
- **Hunt:** how much attention the hunt itself needs.
- **Prep:** how much you need to bring or buy before you go.

| Grade | Hunt (during the hunt) | Prep (before the hunt) |
|---|---|---|
| **0** | You just attack. No healing needed. | Nothing special. |
| **1** | You heal or drink a potion now and then. | A few cheap potions. |
| **2** | You box monsters with `exori` and drink potions steadily. | Many potions, or a specific piece of gear. |
| **3** | You need special tactics: invisible monsters, monsters that call helpers, rooms to avoid. | Something from a later section of this guide. |

The best hunting grounds are **Prep 0, Hunt 0** ("P0 H0" in short). That's the dream: no potions, no worries, just hunting.

There's a third kind of comfort, **knowledge**: how much of the game you need to understand. That's what the sections are for. Each section has a **kit**, the things everyone in that section uses. In Section 2, for example, everyone has the two leech imbuements, so they don't count against a hunting ground's Prep grade.

### How a hunting ground is graded
For hunting grounds that were tested, the grades come from what actually happened: how much healing was needed and how much was spent on potions.

For all other hunting grounds, the grade comes from the monsters, using data from TibiaWiki. The main question is: **how hard can the hunting ground's strongest common monster hit you in a single turn, compared with your total HP?** "Common" means at least 1 in 10 of the monsters there. The check is done at the lowest level of each band.

For example, at level 50 you have about 815 HP. A monster that can hit 250 in one turn takes about 30% of your health, which makes the hunting ground Hunt 2.

| A common monster can hit you for… | Hunt | Prep |
|---|---|---|
| less than 15% of your HP | 0 | 0 |
| 15% to 30% | 1 | 1 |
| 30% to 50% | 2 | 2 |
| half your HP or more | 3 | 3 |

A few other things make a hunting ground less comfortable:
- **Elemental damage.** Fire, ice, energy, earth and death damage go straight through normal armor. If most of a hunting ground's damage is elemental, its Hunt grade goes up one step, and you'll usually want special armor (Prep 2).
- **Invisible monsters.** You can't see them to attack them, so the hunting ground is Hunt 3.
- **Monsters that call helpers** ("summoners"), or a rare monster that can take half your HP in one turn, make the hunting ground at least Hunt 2.
- **Special gear.** If the hunting ground needs a specific item, like an elemental armor or a Dwarven Ring, Prep is 2.

Some hunting grounds are left out entirely: those full of summoners, or with many monsters that hurt you but give no experience.

### Which hunting grounds are listed
A hunting ground appears in every band from its recommended level upwards, so the same hunting ground shows up in several bands. Its grades and numbers get better as your level goes up.

Each band shows only its **5 best hunting grounds**. Hunting grounds that aren't worth your time are dropped first: a hunting ground's experience **or** its loot must be at least three quarters of the third-best hunting ground in that band, and its loot must cover the potions it costs. The rest are sorted by comfort (Prep first, then Hunt), then by loot, and the top 5 are listed.

Each hunting ground is tagged as an **XP** hunting ground (good for levelling), a **money** hunting ground (good for gold), or **XP + money**.

### The character the numbers assume
The XP and loot numbers are estimates for a typical knight: someone whose skill is a little below the usual for their level (30 at level 8, 63 at 30, 96 at 90, 114 at 200), wearing the best gear they could buy with about 3 hours of hunting income. A new character only reaches those skills by training offline from the start (see Section 1). Each band lists that gear. If your skill or gear is better, you'll do better than the tables.

## Section 1: Basic mechanics
In this section you use only the basics: your weapon, the `exori` attack spell, the `exura ico` healing spell, potions, normal gear, and an amulet and ring that never run out. Everything else comes later.

### How to fight
**Before level 35**, a knight has no area attack, so fight one or two monsters at a time with your normal attacks. Heal with `exura ico` when you need it.

**From level 35** you learn `exori`. It costs 125 mana and hits every monster standing next to you, so it pays off when three or more monsters surround you. This is called **boxing**:
1. Walk into the spawn and let a few monsters follow you.
2. Stop and let them surround you.
3. Cast `exori` whenever it's ready, and keep attacking normally in between.
4. Start with two or three monsters. Add one more at a time as long as your HP stays above about 60%.

Against just one or two monsters, normal attacks are enough. Save your mana for groups.

**Potions:** all potions share one short cooldown (about 1 second), so you can't drink a health and a mana potion at the same moment. Use mana potions to keep casting `exori`, and switch to a health potion when your HP drops fast. Mana Potions are the cheapest per point of mana. Stronger potions unlock at higher levels: Strong (level 50), Great (80), and for health also Ultimate (130) and Supreme (200).

**Stay safe:** always know your way out, and leave when your HP falls to about half. Don't wait until it's almost empty.

### Gear
In Section 1 you wear only items that never run out, so there are no charges or timers to watch.
- **Amulet:** a Platinum Amulet early on, then a Foxtail Amulet from level 100 (it reduces physical damage by 5%).
- **Ring:** a Butterfly Ring from level 50.
- **Elemental hunting grounds:** some hunting grounds hit mostly with one element. For those, an elemental armor (Lavos, Crystalline, Swamplair or Voltage, level 60) helps; the hunting ground's notes tell you when.

### Before you hunt: stamina and blessings
**Stamina** is how long your character can hunt at full strength. It goes up to 42 hours. With a premium account, the first 3 hours from full stamina give **50% more experience**, so start your best hunts right after a long rest. Below 14 hours you only get half the experience and no loot, so stop and rest. Stamina comes back while you are logged out: about 1 minute for every 3 minutes offline, and half as fast for the 3 bonus hours.

**Blessings** are bought from NPCs in the cities and protect you when you die. With the 5 regular blessings you lose about 70% less experience and skill, and you keep all your items. Together they cost about (level − 20) × 1,000 gold up to level 120, so about 70k at level 90, and about 105k at level 134. They're worth it.

### Selling your loot
Many things monsters drop sell on the Market for much more than any shop pays. A Stone Wing, for example, sells for about 2.4k on the Market but only 120 at a shop. The notes for each hunting ground name its most valuable drop.

The in-game Hunt Analyser often shows less loot than you really made, because it values items at shop prices. In one tested hour it showed 10.6k of loot; selling everything on the Market brought in 106k.

Prices also differ between game worlds, sometimes by three times, so check your own Market before choosing a hunting ground for its loot.

### Train your skills while you're offline
Your sword (or club, or axe) skill decides how hard you hit, and at low levels it matters more than your level. You can train it for free while you're logged out:

1. Go to a **Training Statue**. Every big city has them in its training school, and Targuna has one too. Later, a bed in a house works the same way.
2. Use it, pick **Sword Fighting + Shielding** (or club or axe), and log out. Training starts after 10 minutes offline.
3. You can train up to **12 hours in a row**. The time comes back one second for every second you spend online, or offline without training.

It's worth doing **right away, from level 8**. A new knight with sword 16 and shielding 12 reaches about sword 41 and shielding 35 after 12 hours. That more than doubles the damage you deal, and you block many more hits. It costs nothing, and training early helps every hunt that comes after, so make it a habit: whenever you log out, use a training statue.

A few more things:
- Hunting trains your skill too, about twice as fast as offline training, as long as you keep attacking.
- The daily reward sometimes gives free training weapons. Use them on the Exercise Dummy in any training school for a little extra skill.
- Free accounts train more slowly offline and stop at skill 50.

### Easy quests before level 20
At low levels, a few safe quests give as much experience as hours of hunting. Quest experience is fixed, so it helps most while your skills are still low. Together, the Targuna Quest and the first three mainland quests below give about 28,000 experience, close to a third of what it takes to go from level 8 to 20.

**On Newhaven**, the starting island. Do these before you leave, because you can't go back:
- **[Newhaven Quest](https://tibia.fandom.com/wiki/Newhaven_Quest):** 1,600 experience, a Guardian Ring and a Scarf (about 15 minutes).
- **[Newhaven Legion Helmet Quest](https://tibia.fandom.com/wiki/Newhaven_Legion_Helmet_Quest):** a Legion Helmet (about 5 minutes).

**On Targuna**, the island for levels 8 to 20, the [Targuna Quest](https://tibia.fandom.com/wiki/Targuna_Quest) has three missions:

| Mission | Who starts it | Level | What you do | Reward |
|---|---|---|---|---|
| [An ancient enemy](https://tibia.fandom.com/wiki/Targuna_Quest/Spoiler#An_ancient_enemy) | Lizzie | any | Kill the Lizard Commander two floors down in the Hidden Lizard Temple | 1,500 experience, 2 platinum coins |
| [A long lost treasure](https://tibia.fandom.com/wiki/Targuna_Quest/Spoiler#A_long_lost_treasure) | Sterling | 10 | On Aragonia, kill 20 pirates and use 10 tortoise eggs; bring Morla's map back to Sterling, then dig at the marked place (bring a rope and a shovel) | 3,000 experience and an Adventurer Backpack |
| [Burning Heat](https://tibia.fandom.com/wiki/Targuna_Quest/Spoiler#Burning_Heat) | Emiliana | 12 | Go down through the Crimson Court and beat the Herald of Fire | 5,000 experience and the Reliable Ram mount (give the turnips to the ram) |

**On the mainland:**

| Quest | Where | Account | Reward |
|---|---|---|---|
| [The Scatterbrained Sorcerer Quest](https://tibia.fandom.com/wiki/The_Scatterbrained_Sorcerer_Quest) | Starts in Thais, with errands in Venore, Kazordoon, Ab'Dendriel and Carlin | Free | 10,650 experience and 5,350 gold |
| [Jack to the Future Quest](https://tibia.fandom.com/wiki/Jack_to_the_Future_Quest) | Edron | Premium | 6,000 experience |
| [Rottin Wood and the Married Men Quest](https://tibia.fandom.com/wiki/Rottin_Wood_and_the_Married_Men_Quest) | Outlaw Camp (best near level 20) | Free | 1,600 experience and 2,500 gold |
| [Venore Daily Tasks](https://tibia.fandom.com/wiki/Venore_Daily_Tasks_Quest) (from level 15) | Venore | Free | 1,000 experience and 1,000 gold every day |
| [Loose Ends Quest](https://tibia.fandom.com/wiki/Loose_Ends_Quest) | Thais, Venore, Edron, Ankrahmun, Outlaw Camp | Premium | 500 experience just for talking to the NPCs, more for their quests |

Each name links to its TibiaWiki page, which has a step-by-step spoiler.

### Reading the hunting ground tables
- **Hunting ground:** the name links to the entrance on the tibiamaps.io map. ✓ means the hunting ground was tested at that level.
- **Prep and Hunt:** the comfort grades, 0 to 3.
- **XP/h and Loot/h:** estimated experience and gold per hour for the typical knight at the lowest level of the band, without bonuses and before paying for potions. Tested hunting grounds show real results.
- **Depot:** the nearest depot, how many squares you walk from it to the entrance, and about how long that takes. For islands and hidden areas it lists each step: the walk to the boat (or teleport), the trip, and the walk from where you arrive.
- **Notes:** the tag (XP, money or both), test results, how to get access, **Watch** (what makes the hunting ground less comfortable) and **Sells** (its most valuable drop).

Each band's title also shows roughly how long it takes to reach the next band: the experience between the two levels, divided by the average XP/h of the hunting grounds listed. It counts raw experience only, so the stamina bonus, XP boosts and prey make it faster.

#### Level 8–20 (~8.1 hours to the next band)
**Typical knight in this band:** skill 30, weapon attack 25. Good-value gear, each piece under ~33k: Serpent Sword, Morning Star or Orcish Axe (sword, club or axe), with Golden Armor, Knight Legs, Royal Helmet, Carapace Shield, Boots of Haste.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Thais Wasp Dungeon](https://tibiamaps.io/map#32428,32315,7:2) | 0 | 0 | ~8k | ~65k | Thais 188 / ~47 s | **money**. Sells: Honeycomb |
| [Swamp Troll Cave](https://tibiamaps.io/map#32938,32219,7:2) | 0 | 2 | ~7k | ~30k | Venore 262 / ~1.1 min | **money**. Watch: skip Ghoul (hits half your HP). Sells: Medicine Pouch |
| [Meriana](https://tibiamaps.io/map#32335,32580,7:2) | 1 | 1 | ~7k | ~40k | Liberty Bay 9 / ~2 s, Peg Leg's boat to Meriana | **money**. Needs the Access to Meriana part of [The Shattered Isles Quest](https://tibia.fandom.com/wiki/The_Shattered_Isles_Quest). Watch: Centipede hits 25% of HP. Sells: Centipede Leg |
| [Hidden Lizard Temple (Targuna)](https://tibiamaps.io/map#31936,31863,7:2) | 1 | 1 | ~18k | ~25k | Targuna depot, on the island | **XP**. Lizards; the Lizard Statues inside cure their poison. Watch: Lizard Executioner hits 27% of HP. Sells: Lizard Tail |
| [Aragonia (Targuna)](https://tibiamaps.io/map#33513,32720,7:2) | 1 | 1 | ~19k | ~20k | Targuna, then Sterling's sea turtle (free) | **XP**. Pirates; part of the [Targuna Quest](https://tibia.fandom.com/wiki/Targuna_Quest). Watch: Pirate Quartermaster hits 27% of HP. Sells: Gold Tooth |

#### Level 20–30 (~14 hours to the next band)
**Typical knight in this band:** skill 50, weapon attack 31. Good-value gear, each piece under ~71k: Crimson Sword, Furry Club or Dwarven Axe (sword, club or axe), with Dragon Scale Mail, Golden Legs, Royal Helmet, Rift Shield, Boots of Haste.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Nibelor](https://tibiamaps.io/map#32353,31053,7:2) | 0 | 0 | ~8k | ~115k | Svargrond 182 / ~46 s | **money**. Ask Iskan in Svargrond for a "passage" (he may ask for a task first). Sells: Winter Wolf Fur |
| [Thais Wasp Dungeon](https://tibiamaps.io/map#32428,32315,7:2) | 0 | 0 | ~13k | ~100k | Thais 188 / ~47 s | **money**. Sells: Honeycomb |
| [Meriana](https://tibiamaps.io/map#32335,32580,7:2) | 0 | 0 | ~11k | ~65k | Liberty Bay 9 / ~2 s, Peg Leg's boat to Meriana | **money**. Needs the Access to Meriana part of [The Shattered Isles Quest](https://tibia.fandom.com/wiki/The_Shattered_Isles_Quest). Sells: Centipede Leg |
| [Hidden Lizard Temple (Targuna)](https://tibiamaps.io/map#31936,31863,7:2) | 0 | 0 | ~30k | ~45k | Targuna depot, on the island | **XP**. Lizards; the Lizard Statues inside cure their poison. Sells: Lizard Tail |
| [Aragonia (Targuna)](https://tibiamaps.io/map#33513,32720,7:2) | 0 | 0 | ~35k | ~40k | Targuna, then Sterling's sea turtle (free) | **XP**. Pirates; part of the [Targuna Quest](https://tibia.fandom.com/wiki/Targuna_Quest). Sells: Gold Tooth |

#### Level 30–40 (~21 hours to the next band)
**Typical knight in this band:** skill 63, weapon attack 37. Good-value gear, each piece under ~133k: Epee, Sapphire Hammer or Beastslayer Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Boots of Haste.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Nibelor](https://tibiamaps.io/map#32353,31053,7:2) | 0 | 0 | ~9k | ~130k | Svargrond 182 / ~46 s | **money**. Ask Iskan in Svargrond for a "passage" (he may ask for a task first). Sells: Winter Wolf Fur |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~18k | ~125k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Thais Wasp Dungeon](https://tibiamaps.io/map#32428,32315,7:2) | 0 | 0 | ~13k | ~105k | Thais 188 / ~47 s | **money**. Sells: Honeycomb |
| [Hidden Lizard Temple (Targuna)](https://tibiamaps.io/map#31936,31863,7:2) | 0 | 0 | ~45k | ~55k | Targuna depot, on the island | **XP**. Lizards; the Lizard Statues inside cure their poison. Sells: Lizard Tail |
| [Aragonia (Targuna)](https://tibiamaps.io/map#33513,32720,7:2) | 0 | 0 | ~45k | ~50k | Targuna, then Sterling's sea turtle (free) | **XP**. Pirates; part of the [Targuna Quest](https://tibia.fandom.com/wiki/Targuna_Quest). Sells: Gold Tooth |

#### Level 40–50 (~22 hours to the next band)
**Typical knight in this band:** skill 68, weapon attack 40. Good-value gear, each piece under ~263k: Assassin Dagger, Shadow Sceptre or Warrior's Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Boots of Haste.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~20k | ~150k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Nibelor](https://tibiamaps.io/map#32353,31053,7:2) | 0 | 0 | ~9k | ~130k | Svargrond 182 / ~46 s | **money**. Ask Iskan in Svargrond for a "passage" (he may ask for a task first). Sells: Winter Wolf Fur |
| [Crimson Court (Targuna)](https://tibiamaps.io/map#31962,31898,5:2) | 0 | 0 | ~60k | ~45k | Targuna, portal in Emiliana's house | **XP**. Infernoids; cross the fire fields or switch them off with the floor slabs; Needs the Burning Heat mission of the [Targuna Quest](https://tibia.fandom.com/wiki/Targuna_Quest) (level 12). Sells: Infernoid Ember |
| [Horestis Tomb (Ankrahmun)](https://tibiamaps.io/map#33062,32731,6:2) | 0 | 2 | ~55k | ~65k | Ankrahmun 170 / ~40 s | **XP**. Tomb servants, clay guardians and sacred spiders; upstairs at the dragon spawn nearest Ankrahmun. Watch: skip Death Priest (hits half your HP). Sells: Fist on a Stick |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 1 | 1 | ~60k | ~150k | Edron 129 / ~30 s | **XP + money**. Watch: Wyvern hits 22% of HP. Sells: Wyvern Talisman |

#### Level 50–60 (~31 hours to the next band)
**Typical knight in this band:** skill 74, weapon attack 42. Good-value gear, each piece under ~226k: Relic Sword, Deepling Squelcher or Warrior's Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Boots of Haste.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~25k | ~170k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Nibelor](https://tibiamaps.io/map#32353,31053,7:2) | 0 | 0 | ~9k | ~130k | Svargrond 182 / ~46 s | **money**. Ask Iskan in Svargrond for a "passage" (he may ask for a task first). Sells: Winter Wolf Fur |
| [Horestis Tomb (Ankrahmun)](https://tibiamaps.io/map#33062,32731,6:2) | 0 | 0 | ~65k | ~75k | Ankrahmun 170 / ~40 s | **XP**. Tomb servants, clay guardians and sacred spiders; upstairs at the dragon spawn nearest Ankrahmun. Sells: Fist on a Stick |
| [Crimson Court (Targuna)](https://tibiamaps.io/map#31962,31898,5:2) | 0 | 0 | ~60k | ~45k | Targuna, portal in Emiliana's house | **XP**. Infernoids; cross the fire fields or switch them off with the floor slabs; Needs the Burning Heat mission of the [Targuna Quest](https://tibia.fandom.com/wiki/Targuna_Quest) (level 12). Sells: Infernoid Ember |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 1 | 1 | ~70k | ~170k | Edron 129 / ~30 s | **XP + money**. Watch: Wyvern hits 18% of HP. Sells: Wyvern Talisman |

#### Level 60–70 (~32 hours to the next band)
**Typical knight in this band:** skill 80, weapon attack 44. Good-value gear, each piece under ~233k: Mystic Blade, Metal Bat or Vile Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Badger Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~80k | ~195k | Edron 129 / ~30 s | **XP + money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~30k | ~190k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~80k | ~190k | Kazordoon 137 / ~34 s | **XP + money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Horestis Tomb (Ankrahmun)](https://tibiamaps.io/map#33062,32731,6:2) | 0 | 0 | ~70k | ~90k | Ankrahmun 170 / ~40 s | **XP**. Tomb servants, clay guardians and sacred spiders; upstairs at the dragon spawn nearest Ankrahmun. Sells: Fist on a Stick |
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 3 | ~50k | ~385k | Kazordoon 137 / ~35 s | **money**. **Gloom wolves only some days.** Mini World Change with 3 versions (gloom wolves, poachers, or game animals), picked at server save; peek at the entrance before planning. Tainted Caves always has them, but it's left out (no-XP tainted souls). Watch: invisible monsters. Sells: Gloom Wolf Fur |

#### Level 70–80 (~36 hours to the next band)
**Typical knight in this band:** skill 85, weapon attack 46. Good-value gear, each piece under ~195k: Crystalline Sword, Onyx Flail or Hive Scythe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Badger Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~90k | ~215k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~30k | ~215k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~90k | ~210k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 3 | ~60k | ~435k | Kazordoon 137 / ~35 s | **money**. **Gloom wolves only some days.** Mini World Change with 3 versions (gloom wolves, poachers, or game animals), picked at server save; peek at the entrance before planning. Tainted Caves always has them, but it's left out (no-XP tainted souls). Watch: invisible monsters. Sells: Gloom Wolf Fur |
| [Arena and Zoo Quarter](https://tibiamaps.io/map#32677,31231,7:2) | 0 | 3 | ~95k | ~40k | Yalahar 193 / ~48 s | **XP**. Watch: invisible monsters, summoners. Sells: Mutated Rat Tail |

#### Level 80–90 (~43 hours to the next band)
**Typical knight in this band:** skill 90, weapon attack 47. Good-value gear, each piece under ~181k: Crystalline Sword, Onyx Flail or Deepling Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~235k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~100k | ~230k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 0 | 0 | ~50k | ~190k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Swamplings and Forest Fury Camp's leaf golems. Watch: slows or summons. Sells: Piece of Swampling Wood |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 | 2 | ~125k | ~40k | Venore 527 / ~2.2 min | **XP**. Watch: summoners, skip Dragon Lord (hits half your HP). Sells: Wyvern Talisman |

#### Level 90–100 (~58 hours to the next band)
**Typical knight in this band:** skill 96, weapon attack 48. Good-value gear, each piece under ~196k: Blade of Corruption, Onyx Flail or Deepling Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~105k | ~250k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 0 | 0 | ~50k | ~190k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Swamplings and Forest Fury Camp's leaf golems. Watch: slows or summons. Sells: Piece of Swampling Wood |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) ✓ | 0 | 1 | 90k | 215k | Carlin 173 / ~45 s | **money**. **Tested** (level ~90, club 107): 1.8k healing/h; high-price world. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

#### Level 100–110 (~68 hours to the next band)
**Typical knight in this band:** skill 98, weapon attack 49. Good-value gear, each piece under ~205k: Blade of Corruption, Obsidian Truncheon or Deepling Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~110k | ~260k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~100k | ~195k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 0 | 0 | ~50k | ~190k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Swamplings and Forest Fury Camp's leaf golems. Watch: slows or summons. Sells: Piece of Swampling Wood |

#### Level 110–120 (~81 hours to the next band)
**Typical knight in this band:** skill 100, weapon attack 49. Good-value gear, each piece under ~208k: Blade of Corruption, Obsidian Truncheon or Deepling Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~115k | ~265k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~100k | ~200k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 0 | 0 | ~50k | ~190k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Swamplings and Forest Fury Camp's leaf golems. Watch: slows or summons. Sells: Piece of Swampling Wood |

#### Level 120–130 (~93 hours to the next band)
**Typical knight in this band:** skill 101, weapon attack 50. Good-value gear, each piece under ~217k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~120k | ~275k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~105k | ~210k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 0 | 0 | ~50k | ~190k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Swamplings and Forest Fury Camp's leaf golems. Watch: slows or summons. Sells: Piece of Swampling Wood |

#### Level 130–140 (~105 hours to the next band)
**Typical knight in this band:** skill 103, weapon attack 50. Good-value gear, each piece under ~223k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~120k | ~280k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 0 | 0 | ~50k | ~190k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Swamplings and Forest Fury Camp's leaf golems. Watch: slows or summons. Sells: Piece of Swampling Wood |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) ✓ | 0 | 0 | 120k | 185k | Carlin 173 / ~45 s | **Tested** (level 134, sword 115): no healing, 70 gold of supplies. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

#### Level 140–150 (~97 hours to the next band)
**Typical knight in this band:** skill 105, weapon attack 50. Good-value gear, each piece under ~226k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Rift Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~125k | ~285k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~110k | ~215k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 | 2 | ~160k | ~55k | Venore 527 / ~2.2 min | **XP**. Watch: summoners. Sells: Wyvern Talisman |

#### Level 150–160 (~117 hours to the next band)
**Typical knight in this band:** skill 106, weapon attack 50. Good-value gear, each piece under ~229k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Prismatic Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~125k | ~295k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 0 | 0 | ~135k | ~235k | Darashia 99 / ~25 s, then Gnomegate teleport | **money**. Wyverns and earth elementals; needs [Bigfoot's Burden Quest](https://tibia.fandom.com/wiki/Bigfoot%27s_Burden_Quest) (Gnomegate access). Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~110k | ~215k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

#### Level 160–170 (~132 hours to the next band)
**Typical knight in this band:** skill 108, weapon attack 50. Good-value gear, each piece under ~233k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Prismatic Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~130k | ~300k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 0 | 0 | ~135k | ~240k | Darashia 99 / ~25 s, then Gnomegate teleport | **money**. Wyverns and earth elementals; needs [Bigfoot's Burden Quest](https://tibia.fandom.com/wiki/Bigfoot%27s_Burden_Quest) (Gnomegate access). Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~110k | ~215k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

#### Level 170–180 (~147 hours to the next band)
**Typical knight in this band:** skill 109, weapon attack 50. Good-value gear, each piece under ~237k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Prismatic Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~130k | ~305k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 0 | 0 | ~140k | ~245k | Darashia 99 / ~25 s, then Gnomegate teleport | **money**. Wyverns and earth elementals; needs [Bigfoot's Burden Quest](https://tibia.fandom.com/wiki/Bigfoot%27s_Burden_Quest) (Gnomegate access). Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~110k | ~215k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

#### Level 180–190 (~163 hours to the next band)
**Typical knight in this band:** skill 111, weapon attack 50. Good-value gear, each piece under ~236k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Prismatic Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~130k | ~310k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 0 | 0 | ~140k | ~250k | Darashia 99 / ~25 s, then Gnomegate teleport | **money**. Wyverns and earth elementals; needs [Bigfoot's Burden Quest](https://tibia.fandom.com/wiki/Bigfoot%27s_Burden_Quest) (Gnomegate access). Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~110k | ~215k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

#### Level 190–200 (~180 hours to the next band)
**Typical knight in this band:** skill 112, weapon attack 50. Good-value gear, each piece under ~233k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Prismatic Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~135k | ~315k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 0 | 0 | ~145k | ~250k | Darashia 99 / ~25 s, then Gnomegate teleport | **money**. Wyverns and earth elementals; needs [Bigfoot's Burden Quest](https://tibia.fandom.com/wiki/Bigfoot%27s_Burden_Quest) (Gnomegate access). Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~110k | ~215k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

#### Level 200+
**Typical knight in this band:** skill 114, weapon attack 50. Good-value gear, each piece under ~225k: Shiny Blade, Obsidian Truncheon or Crystalline Axe (sword, club or axe), with Magic Plate Armor, Golden Legs, Demon Helmet, Prismatic Shield, Draken Boots.

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 0 | 0 | ~135k | ~320k | Kazordoon 137 / ~34 s | **money**. Only on poacher days: Poacher Caves is a Mini World Change with 3 versions (gloom wolves, poachers or game animals), picked at server save. Sells: Wyvern Talisman |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 0 | 0 | ~145k | ~255k | Darashia 99 / ~25 s, then Gnomegate teleport | **money**. Wyverns and earth elementals; needs [Bigfoot's Burden Quest](https://tibia.fandom.com/wiki/Bigfoot%27s_Burden_Quest) (Gnomegate access). Sells: Wyvern Talisman |
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 0 | 0 | ~100k | ~240k | Edron 129 / ~30 s | **money**. Sells: Wyvern Talisman |
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 0 | 0 | ~35k | ~225k | Farmine 98 / ~24 s | **money**. Sells: Shaggy Tail |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 | 0 | ~110k | ~215k | Carlin 173 / ~45 s | **money**. Elven Hoofs; easy monsters: nothing flees, heals, summons or keeps its distance. Sells: Elven Hoof |

## Section 1a: Stealth Ring
A **Stealth Ring** makes you invisible for 10 minutes. Many monsters can't see invisible players, so they simply ignore you. Players report that these monsters don't attack you or call helpers even while you're hitting them. You can kill them without taking any damage. Cyclops, forest furies, gloom wolves, amazons and barbarians are some of them. Stronger monsters, like dragons and dwarf guards, can see invisible players and attack you as usual.

The ring has its own section because it asks for more preparation: you have to buy rings and swap them every 10 minutes. In return, several better-paying hunting grounds become comfortable much earlier, especially between levels 20 and 90. You can use it on top of any later section.

### Using it
1. **Buy rings on the Market.** They cost about 800–1,500 gold each, depending on the world (around 1,000 is typical). You use 6 per hour, so about 6k gold per hour. The NPC Haroun in Ankrahmun sells them for 5,000 each, which is much more expensive.
2. **Put one on before you walk into the spawn**, and keep the next one ready on a hotkey. Swap when the current ring is almost used up. If it runs out in the middle of a group, they all attack you at once.
3. **Walk to the monsters.** Monsters that can't see you won't follow you, so you can't gather a group. Walk up to them and attack. `exori` still hits all the monsters next to you.
4. **Try one monster first** the first time, to be sure it really ignores you.
5. You can't log out right away while these monsters are on your screen, even with the ring on.

### What it changes
- **Levels 8 to 40:** about twice as many hunting grounds become Prep 0, Hunt 0. Forest Fury Camp becomes comfortable from level 30 instead of around 100, with about 44k XP and 87k loot per hour at 30.
- **Levels 40 to 90:** the Lair of the Treeling Witch becomes comfortable from level 50 instead of 80, and the Ragnir barbarians from 40.
- **Gloom wolves at Poacher Caves** become Prep 0, Hunt 0 from around level 60, with an estimated 385–560k loot per hour (before 60, the wyverns living nearby can see you and still hit a little). Two warnings: the gloom wolves are only there on some days (Poacher Caves changes every day), and their fur, which is most of the money, sells only about 35–50 per day on each world, so hunting them for hours can crash its price.
- **Above level 100** little else changes: most monsters worth hunting there can see invisible players.

### Reading the Section 1a tables
Like Section 2, these tables list only the hunting grounds the ring makes more comfortable, the 5 best per band. The grades show the change, for example "2 → **0**". A dash ("– → 0") means the hunting ground isn't in Section 1 at all, because without the ring it's too annoying. "Can't see you" names the main monsters that will ignore you; "Still" names the strongest one that can still hit you.

The XP and loot numbers use the same killing speed as Section 1. Real results may be different: you can't gather groups, but you also never stop to heal. Loot is shown before paying for the rings.

#### Level 8–20 with a Stealth Ring (~6.6 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Edron Goblin Cave](https://tibiamaps.io/map#33108,31850,7:2) | 2 → **0** | 3 → **0** | ~8k | ~40k | Edron 135 / ~34 s | **money**. Can't see you: Bug, Goblin, Goblin Assassin, Goblin Scavenger. Sells: Bone Club |
| [Meriana](https://tibiamaps.io/map#32335,32580,7:2) | 1 → **0** | 1 → **0** | ~7k | ~40k | Liberty Bay 9 / ~2 s, Peg Leg's boat to Meriana | **money**. Can't see you: Centipede, Wasp, Crab, Crimson Frog. Sells: Centipede Leg |
| [Hidden Lizard Temple (Targuna)](https://tibiamaps.io/map#31936,31863,7:2) | 1 → **0** | 1 → **0** | ~18k | ~25k | Targuna depot, on the island | **XP**. Can't see you: Lizard Henchman, Lizard Executioner, Lizard Magician, Lizard Swordmaster. Sells: Lizard Tail |
| [Aragonia (Targuna)](https://tibiamaps.io/map#33513,32720,7:2) | 1 → **0** | 1 → **0** | ~19k | ~20k | Targuna, then Sterling's sea turtle (free) | **XP**. Can't see you: Pirate Navigator, Pirate Gunner, Pirate Cook, Pirate Quartermaster. Sells: Gold Tooth |
| [Crimson Court (Targuna)](https://tibiamaps.io/map#31962,31898,5:2) | 1 → **0** | 1 → **0** | ~20k | ~15k | Targuna, portal in Emiliana's house | **XP**. Can't see you: Infernoid Blob, Infernoid Hound, Infernoid Soul, Infernoid Spiritual. Sells: Infernoid Ember |

#### Level 20–30 with a Stealth Ring (~13 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 1 → **0** | 1 → **0** | ~12k | ~85k | Farmine 98 / ~24 s | **money**. Can't see you: Gnarlhound. Sells: Shaggy Tail |
| [Edron Goblin Cave](https://tibiamaps.io/map#33108,31850,7:2) | 1 → **0** | 3 → **0** | ~14k | ~70k | Edron 135 / ~34 s | **money**. Can't see you: Bug, Goblin, Goblin Assassin, Goblin Scavenger. Sells: Bone Club |
| [Hrodmir Stone Golem Caves](https://tibiamaps.io/map#32065,31194,7:2) | 2 → **0** | 2 → **0** | ~25k | ~25k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 163 / ~41 s | **XP**. Can't see you: Gargoyle, Stone Golem. Sells: Stone Wing |
| [Forsaken Mine, Cyclopes (Ab'Dendriel)](https://tibiamaps.io/map#32648,31732,7:2) | 3 → **0** | 3 → **0** | ~25k | ~7k | Ab'Dendriel 84 / ~20 s | **XP**. Can't see you: Cyclops, Cyclops Drone. Sells: Cyclops Toe |
| [Ghoul Hill](https://tibiamaps.io/map#33203,31680,7:2) | 3 → **1** | 3 → **1** | ~30k | ~45k | Edron 306 / ~1.3 min | **XP**. Can't see you: Demon Skeleton. Still: Ghoul hits 27% of HP. Sells: Rotten Piece of Cloth |

#### Level 30–40 with a Stealth Ring (~16 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 1 → **0** | 3 → **0** | ~20k | ~315k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Bittermor barbarians](https://tibiamaps.io/map#32003,31228,7:2) | 1 → **0** | 1 → **0** | ~30k | ~95k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 157 / ~39 s | **money**. Can't see you: Badger, Barbarian Headsplitter, Barbarian Skullhunter, Frost Troll, Mammoth, Winter Wolf. Sells: Winter Wolf Fur |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 2 → **0** | 2 → **0** | ~45k | ~85k | Carlin 173 / ~45 s | **XP**. Can't see you: Leaf Golem, Forest Fury, Wilting Leaf Golem. Sells: Elven Hoof |
| [Meriana Gargoyle Cave](https://tibiamaps.io/map#32389,32604,7:2) | 1 → **0** | 1 → **0** | ~40k | ~70k | Liberty Bay 9 / ~2 s, Peg Leg's boat to Meriana, then 48 / ~12 s | **XP**. Can't see you: Gargoyle, Stone Golem, Tarantula, Thornback Tortoise. Sells: Stone Wing |
| [Hrodmir Stone Golem Caves](https://tibiamaps.io/map#32065,31194,7:2) | 1 → **0** | 1 → **0** | ~40k | ~40k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 163 / ~41 s | **XP**. Can't see you: Gargoyle, Stone Golem. Sells: Stone Wing |

#### Level 40–50 with a Stealth Ring (~20 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 2 → **0** | 2 → **0** | ~40k | ~115k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 223 / ~56 s | **money**. Can't see you: Barbarian Bloodwalker, Barbarian Headsplitter, Barbarian Skullhunter, Mammoth, Winter Wolf. Sells: Winter Wolf Fur |
| [Bittermor barbarians](https://tibiamaps.io/map#32003,31228,7:2) | 1 → **0** | 1 → **0** | ~30k | ~110k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 157 / ~39 s | **money**. Can't see you: Badger, Barbarian Headsplitter, Barbarian Skullhunter, Frost Troll, Mammoth, Winter Wolf. Sells: Winter Wolf Fur |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 1 → **0** | 1 → **0** | ~55k | ~105k | Carlin 173 / ~45 s | **XP**. Can't see you: Leaf Golem, Forest Fury, Wilting Leaf Golem. Sells: Elven Hoof |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 1 → **0** | 2 → **2** | ~40k | ~145k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Can't see you: Bug, Wilting Leaf Golem, Leaf Golem. Sells: Piece of Swampling Wood |
| [Drefia](https://tibiamaps.io/map#33018,32443,7:2) | 2 → **0** | 2 → **2** | ~65k | ~90k | Darashia 274 / ~1.1 min | **XP**. Can't see you: Demon Skeleton. Sells: Horoscope |

#### Level 50–60 with a Stealth Ring (~26 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 1 → **0** | 1 → **0** | ~45k | ~165k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Can't see you: Bug, Wilting Leaf Golem, Leaf Golem. Sells: Piece of Swampling Wood |
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 1 → **0** | 1 → **0** | ~45k | ~130k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 223 / ~56 s | **money**. Can't see you: Barbarian Bloodwalker, Barbarian Headsplitter, Barbarian Skullhunter, Mammoth, Winter Wolf. Sells: Winter Wolf Fur |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 1 → **0** | 1 → **0** | ~60k | ~120k | Carlin 173 / ~45 s | **XP**. Can't see you: Leaf Golem, Forest Fury, Wilting Leaf Golem. Sells: Elven Hoof |
| [Drefia](https://tibiamaps.io/map#33018,32443,7:2) | 1 → **0** | 2 → **2** | ~75k | ~105k | Darashia 274 / ~1.1 min | **XP**. Can't see you: Demon Skeleton. Sells: Horoscope |
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 1 → **1** | 3 → **1** | ~45k | ~340k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Still: Wyvern hits 18% of HP. Sells: Gloom Wolf Fur |

#### Level 60–70 with a Stealth Ring (~32 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~50k | ~385k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 1 → **0** | 1 → **0** | ~50k | ~185k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Can't see you: Bug, Wilting Leaf Golem, Leaf Golem. Sells: Piece of Swampling Wood |
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 1 → **0** | 1 → **0** | ~50k | ~145k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 223 / ~56 s | **money**. Can't see you: Barbarian Bloodwalker, Barbarian Headsplitter, Barbarian Skullhunter, Mammoth, Winter Wolf. Sells: Winter Wolf Fur |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 1 → **0** | 1 → **0** | ~70k | ~140k | Carlin 173 / ~45 s | **XP**. Can't see you: Leaf Golem, Forest Fury, Wilting Leaf Golem. Sells: Elven Hoof |
| [Drefia](https://tibiamaps.io/map#33018,32443,7:2) | 1 → **0** | 2 → **2** | ~90k | ~115k | Darashia 274 / ~1.1 min | **XP**. Can't see you: Demon Skeleton. Sells: Stone Skin Amulet |

#### Level 70–80 with a Stealth Ring (~41 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~60k | ~435k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 1 → **0** | 1 → **0** | ~50k | ~190k | Edron 36 / ~9 s, Captain Seahorse's boat to Cormaya, then 137 / ~34 s | **money**. Can't see you: Bug, Wilting Leaf Golem, Leaf Golem. Sells: Piece of Swampling Wood |
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 1 → **0** | 1 → **0** | ~55k | ~160k | Svargrond 63 / ~16 s, Buddel's boat to the Barbarian Settlements, then 223 / ~56 s | **money**. Can't see you: Barbarian Bloodwalker, Barbarian Headsplitter, Barbarian Skullhunter, Mammoth, Winter Wolf. Sells: Winter Wolf Fur |
| [Drefia](https://tibiamaps.io/map#33018,32443,7:2) | 1 → **0** | 2 → **2** | ~100k | ~130k | Darashia 274 / ~1.1 min | **XP**. Can't see you: Demon Skeleton. Sells: Stone Skin Amulet |

#### Level 80–90 with a Stealth Ring (~37 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~65k | ~475k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Drefia](https://tibiamaps.io/map#33018,32443,7:2) | 1 → **0** | 2 → **2** | ~120k | ~115k | Darashia 274 / ~1.1 min | **XP**. Can't see you: Demon Skeleton. Sells: Stone Skin Amulet |

#### Level 90–100 with a Stealth Ring (~44 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~70k | ~520k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 → **0** | 1 → **0** | 90k | 215k | Carlin 173 / ~45 s | **money**. Can't see you: Leaf Golem, Forest Fury, Wilting Leaf Golem. Sells: Elven Hoof |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~135k | ~45k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 100–110 with a Stealth Ring (~49 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~545k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~145k | ~45k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 110–120 with a Stealth Ring (~57 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~150k | ~50k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 120–130 with a Stealth Ring (~66 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~155k | ~50k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 130–140 with a Stealth Ring (~79 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Cult Cave (Liberty Bay)](https://tibiamaps.io/map#32359,32721,7:2) | 1 → **0** | 1 → **1** | 105k | 195k | Liberty Bay 143 / ~35 s | **money**. Can't see you: Novice of the Cult. Sells: Rope Belt |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~160k | ~50k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 140–150 with a Stealth Ring (~86 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~160k | ~55k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 150–160 with a Stealth Ring (~97 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~165k | ~55k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 160–170 with a Stealth Ring (~109 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~170k | ~55k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 170–180 with a Stealth Ring (~121 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~170k | ~55k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 180–190 with a Stealth Ring (~134 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~175k | ~55k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 190–200 with a Stealth Ring (~147 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~180k | ~60k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

#### Level 200+ with a Stealth Ring

| Hunting ground | Prep | Hunt | XP/h | Loot/h | Depot | Notes |
|---|---|---|---|---|---|---|
| [Poacher Caves, Gloomy (Ferngrim's Gate)](https://tibiamaps.io/map#32754,31928,7:2) | 0 → **0** | 3 → **0** | ~75k | ~560k | Kazordoon 137 / ~35 s | **money**. Can't see you: Ghost Wolf, Gloom Wolf. Sells: Gloom Wolf Fur |
| [Plains of Havoc](https://tibiamaps.io/map#32735,32297,7:2) | 0 → **0** | 2 → **1** | ~180k | ~60k | Venore 527 / ~2.2 min | **XP**. Can't see you: Skeleton. Sells: Wyvern Talisman |

## Section 1b: More spells (outline)
Knights have many more spells, but each one is something extra to keep track of while you hunt, so Section 1 leaves them out on purpose. A later version of this guide will show which hunting grounds they help with. They include:
- **Stronger area attacks:** `exori gran` (level 90), `exori min` (70, hits in front of you), `exori mas` (33, wide area) and `exori scu` (30, damage based on your shield).
- **Stronger heals:** `exura gran ico` (level 80, but it can only be used every 2 minutes) and `exura med ico`.
- **Stances:** Protector (`utamo tempo`) makes you take 15% less damage but also deal 15% less. Blood Rage (`utito tempo`) does the opposite.
- **Speed and regeneration:** `utani hur` (haste), `utani tempo hur` (a short sprint), and `utura` / `utura gran` (slow healing over time).

Single-target and ranged attack spells are left out completely: they're weak for the attention they need.

## Section 2: Imbuements
An **imbuement** is a temporary enchantment you add to a piece of gear. It lasts for 20 hours of fighting, then wears off and you add a new one.

For a comfortable knight, two imbuements matter far more than any other:
- **Vampirism (life leech):** part of the damage you deal comes back to you as health.
- **Void (mana leech):** part of the damage you deal comes back as mana.

Together they mean the monsters you hit pay for your healing and your spells. You drink fewer potions, worry less about your health, and can safely fight bigger groups. That's why this section's kit is **Basic Vampirism on your armor and Basic Void on your helmet**. The other imbuements help too, but they give much less for the gold.

### When to start
Imbuements have no level requirement, and even cheap gear has slots for them: Golden Armor and Royal Helmet, the usual gear from level 8, have 2 slots each.

But leech gives back a share of the damage you deal, and low-level characters don't deal much. A typical level 8 knight deals about 19k damage per hour, so Basic leech gives back only about 1k health and 0.6k mana per hour. Meanwhile the kit costs about 3.7k gold per hour, roughly a third of what you loot at those levels.

It starts paying for itself **around level 30 to 50**. By then you deal 60–80k damage per hour, `exori` costs real mana, and potions become a real expense. The Section 2 tables still start at level 8, so you can see which hunting grounds it would help.

### Setting it up
1. **Unlock imbuing** with the first part of the [Forgotten Knowledge Quest](https://tibia.fandom.com/wiki/Forgotten_Knowledge_Quest/Spoiler). It's easy and safe at any level: walk to the Halls of Hope, just north of Thais, and give 5 Heavy Old Tomes to the NPC Albinius (say "temple", then "yes"). Tomes cost about 250 gold each on the Market, and they also drop from orcs, trolls, skeletons, ghouls and cyclops. This unlocks the Basic level for everyone and the Intricate level for premium accounts.
2. **Armor:** go to an Imbuing Shrine in any big city and add Basic Vampirism. You need 25 Vampire Teeth (cheap on the Market) and pay a 7,500 gold fee.
3. **Helmet:** buy a Basic Void scroll on the Market and use it on your helmet. Scrolls work anywhere, without a shrine. For Basic Void the scroll is cheaper than the shrine.
4. **Try it** at a hunting ground you already know, pulling one or two more monsters than usual. Write down how it went.

If you'd rather skip the quest, Imbuement Scrolls work for any player, without the quest and without a shrine. A Basic Vampirism scroll costs about 33k on the Market, a bit more than the ~19k the shrine route costs.

The whole kit costs about 74k gold for 20 hours of fighting, around 3.7k gold per hour. That's a small part of what a decent hunt makes.

Costs, using Market prices from November 2026:

| Imbuement | Cheapest way, per 20 h | Per hour |
|---|---|---|
| Basic Vampirism | shrine ~19k | ~0.9k |
| Basic Void | scroll ~55k | ~2.8k |
| Basic Strike | scroll ~35k | ~1.7k |
| Basic Slash | shrine ~10k | ~0.5k |
| Intricate Vampirism | shrine ~284k | ~14.2k |
| Intricate Void | shrine ~265k | ~13.2k |

### What changes when you have leech
In the level 134 tests, a knight dealt about 145–190k damage per hour. With the kit, that would give back about 7–10k health and 2–6k mana every hour. Area attacks give back less mana for each extra monster hit.

At hunting grounds where you never needed to heal, not much changes. At hunting grounds where you were drinking potions, you'll drink fewer and hunt more calmly. The biggest gain should come from fighting bigger groups safely, but how much that adds hasn't been tested yet.

### Good to know
- The 20 hours only count down while you're fighting.
- An item can hold one imbuement of each kind, and each item has 0 to 3 slots for them. Legs can't be imbued. Magic Plate Armor and Demon Helmet, the typical gear from level 30, have 2 slots each.
- Removing an imbuement costs 15,000 gold, so usually you just let it run out.

### Other imbuements (later, less value for the gold)
- **Strike** (weapon) adds critical hits: about +1% damage at Basic, +2% at Intricate and +4.5% at Powerful.
- **Slash, Bash or Chop** (helmet or weapon) add sword, club or axe skill: +1, +2 or +4, which is roughly +0.7% damage per point.
- **Elemental protection** (armor or shield) reduces one element's damage by 3%, 8% or 15%. It's useful at hunting grounds that hit mostly with one element.

### Farm your own materials
Some Section 1 hunting grounds drop imbuement materials, so you can imbue with your own loot:
- **Vampire Teeth** come from vampires, for example in the Edron Vampire Crypt.
- **Rope Belts** (for Void) come from cultists and dark monks, for example in the Cult Cave near Liberty Bay.
- **Bloody Pincers** (for Intricate Vampirism) come from blood crabs at Laguna Islands and Meriana.

### Reading the Section 2 tables
These tables list only the hunting grounds that get more comfortable with the kit, the 5 best per band; every Section 1 hunting ground still works. The grades show the change, for example "2 → **0**". The XP and loot numbers are the Section 1 estimates, so treat them as a minimum: with leech you should do better, but by how much isn't tested yet.

Leech helps most against steady damage. It doesn't help against a monster that can take half your health in one hit, against monsters that call helpers or turn invisible, or against elemental damage, so those hunting grounds keep their grades.

#### Level 8–20 with leech (~6.0 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Meriana](https://tibiamaps.io/map#32335,32580,7:2) | 1 → **0** | 1 → **0** | ~7k | ~40k | **money** |
| [Hidden Lizard Temple (Targuna)](https://tibiamaps.io/map#31936,31863,7:2) | 1 → **0** | 1 → **0** | ~18k | ~25k | **XP** |
| [Aragonia (Targuna)](https://tibiamaps.io/map#33513,32720,7:2) | 1 → **0** | 1 → **0** | ~19k | ~20k | **XP** |
| [Crimson Court (Targuna)](https://tibiamaps.io/map#31962,31898,5:2) | 1 → **0** | 1 → **0** | ~20k | ~15k | **XP** |
| [Thais Wolf Den](https://tibiamaps.io/map#32505,32283,7:2) | 1 → **0** | 1 → **0** | ~16k | ~4k | **XP** |

#### Level 20–30 with leech (~14 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Gnarlhound Caves](https://tibiamaps.io/map#33193,31473,7:2) | 1 → **0** | 1 → **0** | ~12k | ~85k | **money** |
| [Hrodmir Stone Golem Caves](https://tibiamaps.io/map#32065,31194,7:2) | 2 → **0** | 2 → **1** | ~25k | ~25k | **XP** |
| [Undead Cave (Mount Sternum)](https://tibiamaps.io/map#32418,32017,7:2) | 2 → **0** | 2 → **2** | ~25k | ~20k | **XP**. Still: summoners, skip Enslaved Dwarf (hits half your HP) |
| [Edron Goblin Cave](https://tibiamaps.io/map#33108,31850,7:2) | 1 → **0** | 3 → **3** | ~14k | ~70k | **money**. Still: invisible monsters |

#### Level 30–40 with leech (~15 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Bittermor barbarians](https://tibiamaps.io/map#32003,31228,7:2) | 1 → **0** | 1 → **0** | ~30k | ~95k | **money** |
| [Meriana Gargoyle Cave](https://tibiamaps.io/map#32389,32604,7:2) | 1 → **0** | 1 → **0** | ~40k | ~70k | **XP** |
| [Hrodmir Stone Golem Caves](https://tibiamaps.io/map#32065,31194,7:2) | 1 → **0** | 1 → **0** | ~40k | ~40k | **XP** |
| [Elves (Foreigner Quarter)](https://tibiamaps.io/map#32753,31289,7:2) | 2 → **0** | 2 → **1** | ~35k | ~100k | **XP + money** |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 2 → **0** | 2 → **1** | ~45k | ~85k | **XP** |

#### Level 40–50 with leech (~19 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 1 → **0** | 1 → **0** | ~60k | ~150k | **XP + money** |
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 1 → **0** | 1 → **0** | ~60k | ~140k | **XP + money** |
| [Bittermor barbarians](https://tibiamaps.io/map#32003,31228,7:2) | 1 → **0** | 1 → **0** | ~30k | ~110k | **money** |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 1 → **0** | 1 → **0** | ~55k | ~105k | **XP** |
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 2 → **0** | 2 → **1** | ~40k | ~115k | **money** |

#### Level 50–60 with leech (~24 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Edron Wyvern Hill](https://tibiamaps.io/map#33221,31769,7:2) | 1 → **0** | 1 → **0** | ~70k | ~170k | **XP + money** |
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 1 → **0** | 1 → **0** | ~45k | ~165k | **money** |
| [Poachers (Poacher Caves)](https://tibiamaps.io/map#32754,31928,7:2) | 1 → **0** | 1 → **0** | ~70k | ~160k | **XP + money** |
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 1 → **0** | 1 → **0** | ~45k | ~130k | **money** |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 1 → **0** | 1 → **0** | ~60k | ~120k | **XP** |

#### Level 60–70 with leech (~31 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 1 → **0** | 1 → **0** | ~50k | ~185k | **money** |
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 1 → **0** | 1 → **0** | ~50k | ~145k | **money** |
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 1 → **0** | 1 → **0** | ~70k | ~140k | **XP** |
| [Killer Caiman Cave (Farmine)](https://tibiamaps.io/map#33137,31448,7:2) | 1 → **0** | 1 → **0** | ~75k | ~19k | **XP** |
| [Elves (Foreigner Quarter)](https://tibiamaps.io/map#32753,31289,7:2) | 2 → **0** | 2 → **1** | ~80k | ~90k | **XP** |

#### Level 70–80 with leech (~34 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Lair of the Treeling Witch (Cormaya)](https://tibiamaps.io/map#33338,31972,7:2) | 1 → **0** | 1 → **0** | ~50k | ~190k | **money** |
| [Ragnir barbarians](https://tibiamaps.io/map#32135,31332,7:2) | 1 → **0** | 1 → **0** | ~55k | ~160k | **money** |
| [Edron Dragon Lair](https://tibiamaps.io/map#33098,31701,7:2) | 2 → **0** | 2 → **1** | ~95k | ~95k | **XP** |
| [Formorgar Glacier Crystal Spiders](https://tibiamaps.io/map#32112,31153,1:2) | 2 → **0** | 2 → **1** | ~100k | ~50k | **XP** |
| [Venore Dragon Lair](https://tibiamaps.io/map#32804,32148,7:2) | 2 → **0** | 2 → **1** | ~95k | ~40k | **XP** |

#### Level 80–90 with leech (~28 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 1 → **0** | 1 → **0** | ~105k | ~185k | **money** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 2 → **0** | 2 → **1** | ~145k | ~55k | **XP** |
| [Drefia](https://tibiamaps.io/map#33018,32443,7:2) | 1 → **0** | 2 → **2** | ~120k | ~115k | **XP**. Still: summoners, skip Grim Reaper (hits half your HP) |
| [Edron Orc Cave](https://tibiamaps.io/map#33173,31901,7:2) | 2 → **0** | 2 → **2** | ~115k | ~90k | **XP**. Still: summoners |
| [Old Fortress, Bonebeasts (Edron)](https://tibiamaps.io/map#33224,31652,7:2) | 2 → **0** | 2 → **2** | ~135k | ~60k | **XP**. Still: summoners, skip Lich (hits half your HP) |

#### Level 90–100 with leech (~34 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Forest Fury Camp (Carlin)](https://tibiamaps.io/map#32444,31718,7:2) | 0 → **0** | 1 → **0** | ~90k | ~215k | **money** |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 1 → **0** | 1 → **0** | ~115k | ~200k | **money** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 2 → **0** | 2 → **1** | ~155k | ~60k | **XP** |
| [Venore Dragon Lair](https://tibiamaps.io/map#32804,32148,7:2) | 2 → **0** | 2 → **1** | ~135k | ~40k | **XP** |
| [Forbidden Temple (Carlin)](https://tibiamaps.io/map#32404,31790,7:2) | 2 → **0** | 2 → **1** | ~135k | ~30k | **XP** |

#### Level 100–110 with leech (~35 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 1 → **0** | 1 → **0** | ~120k | ~210k | **money** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 2 → **0** | 2 → **1** | ~165k | ~65k | **XP** |
| [Old Fortress, Bonebeasts (Edron)](https://tibiamaps.io/map#33224,31652,7:2) | 2 → **0** | 2 → **2** | ~150k | ~70k | **XP**. Still: summoners, skip Lich (hits half your HP) |
| [Lich Hell (Liberty Bay)](https://tibiamaps.io/map#31936,32594,8:2) | 2 → **0** | 2 → **2** | ~150k | ~65k | **XP**. Still: summoners, skip Lich (hits half your HP) |
| [Edron Lycanthropes Cave](https://tibiamaps.io/map#33179,31922,7:2) | 2 → **0** | 3 → **3** | ~165k | ~75k | **XP**. Still: invisible monsters |

#### Level 110–120 with leech (~43 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 1 → **0** | 1 → **0** | ~120k | ~215k | **money** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 2 → **0** | 2 → **1** | ~170k | ~65k | **XP** |
| [Drefia Wyrm Lair](https://tibiamaps.io/map#33070,32396,13:2) | 2 → **0** | 2 → **1** | ~150k | ~55k | **XP** |
| [Old Fortress, Bonebeasts (Edron)](https://tibiamaps.io/map#33224,31652,7:2) | 2 → **0** | 2 → **2** | ~155k | ~70k | **XP**. Still: summoners, skip Lich (hits half your HP) |
| [Lich Hell (Liberty Bay)](https://tibiamaps.io/map#31936,32594,8:2) | 1 → **0** | 2 → **2** | ~155k | ~70k | **XP**. Still: summoners, skip Lich (hits half your HP) |

#### Level 120–130 with leech (~49 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 1 → **0** | 1 → **0** | ~125k | ~220k | **money** |
| [Old Masonry](https://tibiamaps.io/map#32805,31657,8:2) | 1 → **0** | 1 → **0** | ~155k | ~80k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~175k | ~70k | **XP** |
| [Drefia Wyrm Lair](https://tibiamaps.io/map#33070,32396,13:2) | 2 → **0** | 2 → **1** | ~155k | ~60k | **XP** |
| [Old Fortress, Bonebeasts (Edron)](https://tibiamaps.io/map#33224,31652,7:2) | 1 → **0** | 2 → **2** | ~160k | ~75k | **XP**. Still: summoners, skip Lich (hits half your HP) |

#### Level 130–140 with leech (~50 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~205k | ~250k | **XP + money** |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 1 → **0** | 1 → **0** | ~130k | ~225k | **money** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~210k | ~100k | **XP** |
| [Old Masonry](https://tibiamaps.io/map#32805,31657,8:2) | 1 → **0** | 1 → **0** | ~160k | ~80k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~180k | ~70k | **XP** |

#### Level 140–150 with leech (~54 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~210k | ~255k | **XP + money** |
| [Crystal Grounds (Gnomegate)](https://tibiamaps.io/map#33002,31868,13:2) | 1 → **0** | 1 → **0** | ~130k | ~230k | **money** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~215k | ~100k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~180k | ~70k | **XP** |
| [Deeplings Library (Fiehonja)](https://tibiamaps.io/map#33457,31196,13:2) | 2 → **0** | 2 → **1** | ~200k | ~135k | **XP** |

#### Level 150–160 with leech (~60 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~210k | ~255k | **XP + money** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~220k | ~105k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~185k | ~75k | **XP** |
| [Darashia Dragon Lair](https://tibiamaps.io/map#33264,32277,7:2) | 2 → **0** | 2 → **0** | ~195k | ~45k | **XP** |
| [Carlin Dragon Lair](https://tibiamaps.io/map#32349,31836,8:2) | 2 → **0** | 2 → **0** | ~175k | ~45k | **XP** |

#### Level 160–170 with leech (~66 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~215k | ~260k | **XP + money** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~220k | ~105k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~190k | ~75k | **XP** |
| [Darashia Dragon Lair](https://tibiamaps.io/map#33264,32277,7:2) | 2 → **0** | 2 → **0** | ~195k | ~45k | **XP** |
| [Carlin Dragon Lair](https://tibiamaps.io/map#32349,31836,8:2) | 2 → **0** | 2 → **0** | ~180k | ~45k | **XP** |

#### Level 170–180 with leech (~71 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~220k | ~265k | **XP + money** |
| [Deeplings Library (Fiehonja)](https://tibiamaps.io/map#33457,31196,13:2) | 1 → **0** | 1 → **0** | ~215k | ~140k | **XP** |
| [Fiehonja deeplings](https://tibiamaps.io/map#33514,31324,7:2) | 1 → **0** | 1 → **0** | ~200k | ~120k | **XP** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~225k | ~110k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~190k | ~75k | **XP** |

#### Level 180–190 with leech (~79 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~225k | ~270k | **XP + money** |
| [Deeplings Library (Fiehonja)](https://tibiamaps.io/map#33457,31196,13:2) | 1 → **0** | 1 → **0** | ~215k | ~150k | **XP** |
| [Fiehonja deeplings](https://tibiamaps.io/map#33514,31324,7:2) | 1 → **0** | 1 → **0** | ~205k | ~130k | **XP** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~230k | ~110k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~195k | ~75k | **XP** |

#### Level 190–200 with leech (~86 hours to the next band)

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~225k | ~275k | **XP + money** |
| [Deeplings Library (Fiehonja)](https://tibiamaps.io/map#33457,31196,13:2) | 1 → **0** | 1 → **0** | ~220k | ~155k | **XP** |
| [Fiehonja deeplings](https://tibiamaps.io/map#33514,31324,7:2) | 1 → **0** | 1 → **0** | ~205k | ~130k | **XP** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~235k | ~110k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~200k | ~80k | **XP** |

#### Level 200+ with leech

| Hunting ground | Prep | Hunt | XP/h (at least) | Loot/h (at least) | Notes |
|---|---|---|---|---|---|
| [Energy Elemental Lair](https://tibiamaps.io/map#33176,32548,7:2) | 2 → **0** | 2 → **0** | ~230k | ~280k | **XP + money** |
| [Deeplings Library (Fiehonja)](https://tibiamaps.io/map#33457,31196,13:2) | 1 → **0** | 1 → **0** | ~220k | ~155k | **XP** |
| [Fiehonja deeplings](https://tibiamaps.io/map#33514,31324,7:2) | 1 → **0** | 1 → **0** | ~210k | ~135k | **XP** |
| [Water Elemental Dungeon (Port Hope)](https://tibiamaps.io/map#32679,32964,7:2) | 2 → **0** | 2 → **0** | ~235k | ~115k | **XP** |
| [Vengoth Werewolf Cave](https://tibiamaps.io/map#32980,31497,7:2) | 1 → **0** | 1 → **0** | ~200k | ~80k | **XP** |

## Section 3: Charms and prey (outline)
**Prey** lets you pick a creature and get a bonus while hunting it: more experience (13–40%), more damage (7–25%), less damage taken (12–30%) or more loot (13–40%). The bonus is random, and premium accounts have 2 prey slots. Open it with Ctrl+Y.

**Charms** are perks you attach to one creature each. You unlock them with points earned by completing that creature's Bestiary entry, which mostly means killing enough of them. Two are great for comfort:
- **Dodge:** put it on the monster that hurts you most. It gives a 5–11% chance to take no damage from it.
- **Wound:** put it on the monster you kill most. It adds about 1–4% damage.

Still to write: which hunting grounds get more comfortable with charms and prey.

## Section 4: Wheel of Destiny and gems (outline)
From level 51 (after promotion, with a premium account) you get **1 point per level** to spend on the Wheel of Destiny, a board of permanent perks. A level 134 knight has 84 points.

A good start for comfort: first the slices that give extra HP, then **Battle Healing**, which makes your healing 30% stronger while you use a shield. TibiaPal has a planner and ready-made knight builds (tibiapal.com/wheels). Gems, which add more perks, come later.

Still to write: a build for each level band and the hunting grounds it helps with.

## Section 5: Weapon proficiency (outline)
Every kill with a weapon equipped builds up that weapon's **proficiency**, which unlocks perks for it, such as more damage or more critical hits. Progress belongs to each weapon, so switching weapons often wastes it: keep one main weapon per level band. Reaching proficiency level 3 takes about 800 kills of mid-level monsters.

Still to write: which perks to pick for each weapon.

## Section 6: The Forge and the full Elite Knight (outline)
The last step is the **Exaltation Forge**, which upgrades items to higher tiers with small chance-based effects, on top of everything from the earlier sections. Together that's what experienced players call a "full setup".

Still to write: what the Forge does for a knight, and which hunting grounds become comfortable with a full setup.

## Appendix: how the numbers are made
Nobody publishes hunting numbers for knights without a full setup, so the XP and loot numbers in Sections 1 and 2 are calculated. Here is how, in plain terms.

1. **Monsters and loot.** For each hunting ground, TibiaWiki lists which monsters live there, how much experience and HP each one has, and what it drops and how often. Each drop is valued at whichever is higher: the shop price or the Market price (the middle price on three big worlds, November 2026). Very rare drops (less than 1 in 1,000 kills) count at shop price, so lucky jackpots don't inflate the numbers.
2. **Which monsters you meet.** The mix of monsters comes from where they appear near the hunting ground's entrance on a fan-made copy of the game map.
3. **How fast you kill.** The speed comes from real level 134 hunts, which dealt 144–191k damage per hour. For other levels it's scaled by how hard the typical knight hits at that level, and adjusted for monster HP: big monsters waste less time per kill. It's capped at 550 kills per hour, and at what the hunting ground can respawn.
4. **Putting it together.** Damage per hour, times the experience and loot each point of damage brings at that hunting ground, gives XP/h and loot/h.

**How far to trust them:**
- In the tests, experience and loot per point of damage came out within about 10% of these estimates.
- Nothing is tested above level 134 yet.
- The estimates don't know about walking between scattered monsters, other players in the same hunting ground, or areas that change every day (Poacher Caves, Forsaken Mine).
- The tests used `exori gran` on big groups. Section 1 uses only `exori`, so real numbers there may be a little lower.
- If a hunting ground's money comes from one single item (like Gloom Wolf Fur), hunting it a lot can push that item's Market price down.

Use the numbers to compare hunting grounds with each other, not as promises.

## Sources
- **TibiaWiki** (tibia.fandom.com): hunting places, creatures, items, spells, potions, imbuements, charms, prey, Wheel of Destiny, weapon proficiency, stamina, blessings, Vocation Adjustments 2026.
- **Market prices:** tibiamarket.top (Antica, Quidera, Yovera), Nov 2026.
- **Spawns:** canary OT map (otservbr-monster.xml).
- **Depot distances:** tibiamaps.io walkability map and TibiaWiki coordinates.
- **Full-setup numbers:** TibiaPal (https://tibiapal.com/hunting), TibiaRoute, tibiastats.pl.
- **Planners:** https://tibiapal.com/wheels, https://tibiapal.com/weapon-proficiency, https://tibiapal.com/imbue
- **Tests:** `spot_tests.md`.
