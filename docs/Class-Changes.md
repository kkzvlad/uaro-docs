🧙‍♂️ Class Changes¶
🔧 Smith¶
Over-Thrust / Max Over-Thrust no longer break weapons
1H swords now compatible with Adrenaline Rush
“Repair Weapon” skill description updated to include armor repair with steel
🥷 Ninja¶
Fixed animation issue causing stuck sitting / stuck movement while hit
Cold Heart / Black Cat accessories now complete combos with Rogue Treasure


🏹 3. Skill & Mechanic Tweaks¶
Magnus Exorcismus¶
Now inflicts damage on monsters of Undead, Demon races or Shadow, Ghost, Undead elements.
Improved Portal Mechanics¶
Fly Wing and Teleport will no longer randomly land you within portals, ensuring more control.
Skill Adjustments¶
Backstab: Now correctly registers damage at 0 cell range.
Asura Strike: SP regenerates correctly upon relogging.
Gravitation Field (High Wizard): Adjusted to behave as expected for optimized gameplay.

Soul Linker max job level extended to 70.
HP/SP pools remain the same as Job 50.
All Soul Links (Level 5) now last 10 minutes (previously 5 minutes).


Bowling Bash's range increased to 2 cells to reduce the range-mob bug.
Fixed an issue where Sage's Free Cast increased ASPD instead of decreasing it at skill levels lower than 10.
Soul Breaker's range increased to 9 cells.
The Grand Cross skill can now be plagiarized.

6 December 2024<br>
## 🎯 **Extended Class Skill Reworks**

### **Gunslinger**
| Skill Name         | Change                                |
|--------------------|---------------------------------------|
| Rapid Shot         | SP cost per level 1–10: `12–20`.     |
|                    | AfterCastDelay: `1 sec → 0.75 sec`.  |
| Full Buster        | AfterCastDelay: `2 sec`.             |
|                    | SP cost level 5–10: `35`.            |
| Triple Action      | SP cost: `20 → 12`.                  |
| Flip the Coin      | SP cost: `2 → 1`. Success Rate: `100%`.

### **Ninja**
| Skill Name              | Change                                |
|-------------------------|---------------------------------------|
| Throw Zeny              | AfterCastDelay: `5 sec → 2 sec`.     |
|                         | SP cost: `50 → 25`.                  |
| Throw Kunai             | AfterCastDelay: `1 sec → 0.5 sec`.   |
| Final Strike            | SP cost per level 1–10: `30–50`.     |
| Throw Huuma Shuriken    | AfterCastDelay: `2 sec → 1.5 sec`.   |
|                         | SP cost level 1–5: `5,10,15,20`.     |

### **Star Gladiator**
- **Miracle Success Rate:** `0.02% → 0.1%`.

### **Soul Linker**
- **Esma SP Cost:** Level 1–10: `4–40`.



24 July 2024<br>
Lif Homunculus has been reverted to the classic version where Mental Change resets upon respawning the homunculus.
Ninja can now equip Magic Bible Vol. 1.
Soul Linker can now equip Staff of Darkness.

04 July 2024<br>
Dragon Fire Formation no longer works under Land Protector.


15 June 2024<br>
Taekwon can now equip Swordman Medal of Honor.
Redemptio cooldown reduced from 10 minutes to 3 minutes.

16 May 2024<br>
Soul Linkers can again perform their skills.
Skills for few classes no longer show up under the "Etc" Tab.
High Jump and Running Soul Linker skills now work within Battlegrounds.
Aspersio can now be used on members outside of your party

11 May 2024<br>
The new skill, Screenshot 2024-05-11 at 00.24.21.png Twilight Alchemy 4, is now available under Alchemist Link. This skill allows you to brew 200 Blue Potions simultaneously.
Made tweaks to the timings and positioning for certain skills, which theoretically should positively impact the effectiveness of Ninja's Crimson Fire Formation skill.

19 February 2024<br>
Changed the animation delay to match official behavior. skill_amotion_leniency now defaults to 0 which offers a more accurate official behavior.
Changed Poisoning Weapon to show the type of poison used when applied
Added the missing EXP rewards for the Amatsu Dungeon quest.
Fixed some interactions of Ki Translation
It should fail with a skill failure message and not consume requirements when:
being cast on Gunslinger class
being cast on a player that already has 5 spheres
being cast on friendly non-player units (e.g. Mercenary)
Fixed some interactions of Absorb Spirit Sphere
It should fail and not consume SP when:
the target player doesn't have spheres
the target player is of Gunslinger class (due to teh game implementation not allowing them to have spheres)
the target player is friendly
It should fail and consume SP when:
used on a BOSS monster
used on a non-boss monster, but failing the 20% check
used on non-player units (like mercenaries)
moved the target check to condition cast end
Fixed the error message when a gunslinger is attempting to use a skill that requires coins without having the necessary amount.
Fixed the stacking of Poem of The Netherworld to match the behavior described in the 2012.08.22 official patch notes.
it cannot be placed over another instance of the skill
when trying to do so, it should show a position error to client
Fixed Sage's free case increasing ASPD instead of decreasing it when the skill level is lower than 10.
Fixed Triple Attack not applying the same motion delay as the client in the case the next combo is not possible, causing visual glitches.
Fixed the Triple Attack delay formula increasing delay with dex instead of decreasing it.
Fixed the Triple Attack animation not workingn when there's no possible chainable combo skill.
Fixed Triple Attack overwriting attackabletime.
Fixed combo delays applying to all combos-based skills and not sending the proper time to the client.
Fixed one cell movement not ignoring hidden objects (such as GMs) in its stack limit calculation.
Fixed an issue causing characters to be stuck in a walk loop while trying to pick up an unreachable item on the ground.
Fixed range and cast time for Soul Destroyer.
Fixed Dispel not working in duels.
Fixed songs not triggering their onleft or onout events when overlapping and turning into dissonance.
Fixed the range checks of Blade Stop:
Fixed the target's (as in triggering attack target, and Blade Stop caster) equipped weapon wrongly affecting the skill's working range.
Success range is changed to 2, to match the official behavior.
In pre-re, changed it to always succeed against player attackers regardless of range.
Changed it to always succeed for non-player casters regardless of range (custom Hercules behavior, officially only players may cast Blade Stop).
Fixed CELL_NOSTACK making mob AI not being able to reach target under certain conditions.
Fixed the critical bonus calculation from status effects getting truncated to 0.3 CRIT per point of LUK instead of 1/3.
Fixed some SC counters (including Storm Gust) not getting reset to 0 when a unit dies.
Fixed costumes blocking itemskill execution, even when items are being consumed.
Removed an incorrect afterCastActDelay from Sacrifice
Removed the fixed target from some combo skills. Monk skills act on the current target even if the last skill was used on a different enemy.


04 January 2024<br>
Bowling Bash Gutterlines Removed
The Gutterlines in Bowling Bash have been successfully removed.


30 November 2023<br>
Fixes in some items, they can now be equipped by some extended classes such as Taekwon, Gunslinger, Ninja, Soul Linker, and Star Gladiator:
Sprint Mail
Sprint Ring
Sprint Shoes
Armor of Naga
Ring Of Flame Lord
Ring Of Resonance
Shield of Naga
Vesper Cores


17 November 2023<br>
Bowling Bash's range increased to 2 cells to reduce the range-mob bug.
Fixed an issue where Sage's Free Cast increased ASPD instead of decreasing it at skill levels lower than 10.
Soul Breaker's range increased to 9 cells.
The Grand Cross skill can now be plagiarized


15 September 2023<br>
Brandish Spear

KnockBackTiles: 1.
Bowling Bash

SplashRange: 3.
KnockBackTiles: 0.
Adjustments made to the Gutter Line.
Charge Attack

The range has been fixed to 14 cells

The following equipment, previously restricted to transcended classes, is now available to Gunslingers, Ninjas, Soul Linkers, Taekwonds, and Star Gladiators:

Armor of Naga [1] [Body]
Bison Horn [1] [Accessory]
Black Leather Boots [0] [Footgear]
Divine Cloth [1] [Body]
Dragon Breath [1] [Garment]
Expert Ring [1] [Accessory]
Nydhorgg's Shadow Garb [1]
Orleans's Glove [1]
Orleans's Gown [1]
Orleans's Server [1]
Platinum Shield [0]
Ring Of Flame Lord [0]
Ring Of Resonance [0]
Shadow Walk [0]
Shield of Naga [1]
Sprint Mail [1]
Sprint Ring [0]
Sprint Shoes [1]
Thorny Buckler [1]
Tidal Shoes [1]
Valkyrian Armor [1]
Valkyrian Manteau [1]
Valkyrian Helm [1]
Valkyrian Shoes [1]
Vesper Core 01 [0]
Vesper Core 02 [0]
Vesper Core 03 [0]
Vesper Core 04 [0]
Vital Tree Shoes [0]
Wool Scarf [1]
Magic Bible Vol



21 July 2023<br>
Grand Cross

With the new changes, when mobs are gathered in the same cell, each one will feel the full force of every hit.

Gc-all-mob AdobeExpress.gif


Bowling Bash skill modification

Splash Range increased to 2.
Knock Back distance dicreased to 0.
Bb-no-demi-gutter-bug 0-knockback AdobeExpress.gif


Monster Stack and Grimtooth

Monster stack limit increased from 1 to 7 monsters.
These changes will pave the way for a more efficient use of the Grimtooth skill.
Bb.gif


Songs additional effect

There's an additional effect that lasts for 20 seconds after player leave song zone.


03 July 2023<br>
Missing Icons for some skills has been added.
Longing for Freedom skill now appears in a right tab.
Wand of Hermode skill no longer ensemble skill type and can be used in solo during WoE time.

30.04.2023<br>
Skill Fixes
Screenshot 2023-04-30 at 21.02.29.png The Back Stab skill has been adjusted and can now be executed from any direction.
The behaviour of various types of Reflect Skills types has been fixed:
The amount of damage cannot be greater than the amount of HP the wearer of the skill has.
Reflect is not transmitted if the character is in the Safety Wall.
Monster Valkyrie Randgris is back on map.