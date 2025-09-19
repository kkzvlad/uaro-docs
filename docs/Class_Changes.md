# Class Changes
uaRO uses the pre-renewal class system, with selected adjustments to skills and mechanics for balance and smoother gameplay. These changes preserve the classic feel while improving the overall experience.

For full reference on unmodified pre-renewal skills, you can [visit the iRO Classic Wiki](https://irowiki.org/classic/Main_Page).

<!-- Dev Note: Alt text is excluded from images because it would announce duplicate skill names to screen readers. Instead, use blank alt="" for the decorative image to be skipped by assistive technology. -->

## General / Shared
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Reflected Damage: Amount</td>
                <td>When a reflection skill or behavior activates, it reflects the amount of damage listed, ie 50%.</td>
                <td>The amount of damage reflected cannot be greater than the amount of HP the user of the skill has.</td>
            </tr>
            <tr>
                <td>Reflected Damage: Safety Wall</td>
                <td>Players inside can reflect damage via skill or behavior.</td>
                <td>Players inside <strong>can not</strong> any reflect damage.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/al_teleport.gif" alt="">Teleport</td>
                <td>You can teleport to a random spot on the same map. </td>
                <td>Adjusted to prevent players from landing on a map portal.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

## Swordsman

### Knight / Lord Knight
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/kn_bowlingbash.gif" alt="">Bowling Bash</td>
                <td>
                    <!-- Splash damage of.<br> -->
                    Knockback distance of 1 cell.<br>
                    Skill range of 1 cell.<br>
                </td>
                <td>
                    <!-- Splash damage increased to 3.<br> -->
                    Knockback distance removed.<br>
                    Skill range increased to 2 cells.<br>
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/kn_brandishspear.gif" alt="">Brandish Spear</td>
                <td>Knockback distance of 2 cells.<br>
                <td>Knockback decreased to 1 cell.</td>
            </tr>
        </tbody>
    </table>
</div>


### Crusader / Paladin
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Shield Swapping</td>
                <td>Swapping a shield while a skill is active cancels the skill.</td>
                <td>Swapping sheilds will no longer interrupt the skill. Removing shield will stll cancel the skill.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/cr_reflectshield.gif" alt="">Shield Reflect</td>
                <td>Returns some damage dealt to you back to the enemy. Reflected damage a percentage of received damage.</td>
                <td>The amount of damage reflected cannot be greater than the amount of HP the wearer of the skill has. Reflect is not transmitted if the character is within a Safety Wall.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/cr_devotion.gif" alt="">Devotion</td>
                <td>Skill is usable on party members, including non-guild members.</td>
                <td>
                    Cannot be placed on non-guild members outside of Battlegrounds.<br><br>
                    Added a buff icon when skill is active for both caster and receiver.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/cr_grandcross.gif" alt="">Grand Cross</td>
                <td>Grand Cross hits 1-5 times, depending highly on position and movement of enemy/enemies. When one or more monsters are on a single cell of GC, the number of hits are reduced by 1 per monster (to a minimum of one hit to one monster).</td>
                <td>Due to increased mob stack size, mobs on the same cell take 100% of the damage from every hit.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/pa_gospel.gif" alt="">Gospel</td>
                <td>Buff persists through log out.</td>
                <td>Buffs reset upon relog.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

## Mage

### Wizard / High Wizard
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/wz_icewall.gif" alt="">Ice Wall</td>
                <td>Cannot be used in Cannot be used in GvG, Battlegrounds, Endless Tower, or Nidhoggur's Nest.</td>
                <td>Additionally cannot be used on MVP maps. </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/wz_sightrasher.gif" alt="">Sightrasher</td>
                <td>
                    Range of 15x15 cells.<br>
                    Moves through obstacles including walls.
                </td>
                <td>
                    Range reduced to 7x7 cells.<br> 
                    Cannot go through obstacles or walls.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/hw_gravitation.gif" alt="">Gravitation Field</td>
                <td>The great difficulty of this skill prevents you from doing anything else while casting, including using items. When is active, the caster becomes immobile and cannot attack or use skills.</td>
                <!-- TODO: What does this mean??? --->
                <td>Adjusted to behave as expected for optimized gameplay.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/hw_magicpower.gif" alt="">Amplify Magic Power</td>
                <td>Increases MATK for the next instance of magical damage dealt. Does not include multiple ticks.</td>
                <td>Modified to increase MATK for each tick AoE spells Meteor Storm, Storm Gust, and Lord of Vermillion.</td>
            </tr>
        </tbody>
    </table>
</div>



### Sage / Professor
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/sa_abracadabra.gif" alt="">Abracadabra</td>
                <td>Can be used anywhere excluding WoE: SE.</td>
                <td>Can no longer can be used in towns.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/sa_autospell.gif" alt="">Auto Spell</td>
                <td>Maximum level of skill varies from 1-3 based on skill level. Skill cast chance varies by level used.</td>
                <td>Skills cast will always be level 5, assuming the player has learned at least level 5 of the spell used.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/pf_mindbreaker.gif" alt="">Mind Breaker</td>
                <td>Attack the mind of the enemy to cause mental breakdown. This decreases enemy's INT MDEF, but it ups their MATK. This is basically Provoke for Magicians.</td>
                <td>Adds a debuff icon for the receiver. Updates stats to show impact.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

## Merchant

<!-- mammo 500z when possessing a certain item? 7/4/25, pending info -->

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/mc_cartrevolution.gif" alt="">Cart Revolution</td>
                <td>Putting items in your cart increases the damage by up to 100% more (1% per 80 weight as it has 8000 weight max).</td>
                <td>Cart weight requirement is removed.</td>
            </tr>
        </tbody>
    </table>
</div>

### Blacksmith / Whitesmith
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Fame System</td>
                <td>Fame points earned are kept permanently. A weapon created by ranked blacksmith will deal an extra +10 seeking damage, which pierces defense and never misses. Ranking can be checked in-game with <code>/blacksmith</code>.</td>
                <td>Fame points decay by 10% per month, to support better game balance.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/bs_overthrust.gif" alt="">Power Thrust</td>
                <td>There is a 0.1% chance to break your weapon with each hit.</td>
                <td>No longer breaks weapons.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/bs_adrenaline.gif" alt="">Adrenaline Rush</td>
                <td>Increase your attack speed with Mace and Axe type weapons by 30%. Increases attack speed of nearby party member with Mace and Axe type weapons by 20%. Changing from a Mace or Axe to any other type of weapons (including bare fists) will cancel the effect.</td>
                <td>You can use One-Handed Swords with this skill. </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/ws_carttermination.gif" alt="">Cart Termination</td>
                <td>Uses the power of Zeny to strike a single enemy with your cart. Damage is dependent on the cart's weight.</td>
                <td>
                    Cost is reduced to 0z.<br>
                    Skill is now selectable by level.<br>
                    Cart weight requirement is removed.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/ws_overthrustmax.gif" alt="">Maximum Power Thrust</td>
                <td>There is a 0.1% chance to break your weapon with each hit.</td>
                <td>No longer breaks weapons.</td>
            </tr>
        </tbody>
    </table>
</div>



### Alchemist / Creator
Medicine Bowls can be found at our [Inn Tool Dealers](Dealers.md#enhanced-tool-dealer) in addition to typical locations.

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Fame System</td>
                <td>Fame points earned are kept permanently. Potions made by the 10 top ranked alchemists will receive a 50% bonus to their potency. Rankings can be checked with <code>/alchemist</code> in game.</td>
                <td>Fame points decay by 10% per month, to support better game balance.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/am_twilight3.gif" alt="">Twilight Alchemy III</td>
                <td>Creates 100 Alcohol, 50 Acid Bottle and 50 Bottle Grenade.</td>
                <td>Increases Acid Bottle from 50 → 100, and Bottle Grenade from 50 → 100. Increases Medicine Bowl requirement from 200 → 300.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/am_twilight3.gif" alt="">Twilight Alchemy IV</td>
                <td>N/A</td>
                <td>New skill Alchemist Link skill that allows brewing of 200 Blue Potions at once.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

## Acolyte
Blue Gems are sold at our [Inn Tool Dealers](Dealers.md#enhanced-tool-dealer) in additional to typical locations.


<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/al_warp.gif" alt="">Warp Portal</td>
                <td>Cannot be used in GvG maps or Battleground maps.</td>
                <td>Additionally cannot be used on MVP maps. </td>
            </tr>
        </tbody>
    </table>
</div>

### Priest / High Priest
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/pr_magnus.gif" alt="">Magnus Exorcismus</td>
                <td>
                    Any Demon family and Undead property monsters entering the area of the effect suffer Holy property damage per wave.<br><br>
                    Skill damage is interrupted if player is Stunned, Petrified, or Frozen.
                </td>
                <td>   
                    Increases mob pool damaged by the skill. Races effected are Undead and Demon. Elements effected are Shadow, Ghost, and Undead.<br><br>
                    Damage ticks continue even if player is Stunned, Petrified, or Frozen.
                </td>
            </tr>
        </tbody>
    </table>
</div>

### Monk / Champion
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/mo_extremityfist.gif" alt="">Asura Strike</td>
                <td>HP/SP will not regenerate naturally for 5 minutes after Asura Strike is used.</td>
                <td>SP regenerates normally upon relogging.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

## Thief
A selection of arrows can are our [Inn Tool Dealers](Dealers.md#enhanced-tool-dealer). Additional speciality arrows must be crafted.

### Assassin / Assassin Cross
Venom Knife can be found at our [Inn Tool Dealers](Dealers.md#enhanced-tool-dealer) in addition to typical locations.

No other changes to Assassin skills.

### Rogue / Stalker
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/rg_backstab.gif" alt="">Backstab</td>
                <td>Powerful attack that can only be used from behind the enemy. Cannot miss and will turn the target to face the caster, thus preventing repeated use.</td>
                <td>Can be performed from any angle.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/rg_plagiarism.gif" alt="">Plagiarism</td>
                <td>Skills must be copied from another player.</td>
                <td><a href="Custom_NPC.md">Plagiarism NPC</a> allows Rogues/Stalkers to copy skills for a fee.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/st_preserve.gif" alt="">Preserve</td>
                <td>
                    Duration of 10 minutes.
                </td>
                <td>
                    Infinite duration. Becomes a toggle on / off skill.<br>
                    Persists through log out.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/st_rejectsword.gif" alt="">Reject Sword</td>
                <td>Parry 3 attacks from an enemy and receive only half of the damage.</td>
                <td>The amount of damage reflected cannot be greater than the amount of HP the wearer of the skill has. Reflect is not transmitted if the character is within a Safety Wall.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

## Archer
A selection of arrows can are our [Inn Tool Dealers](Dealers.md#enhanced-tool-dealer). Additional speciality arrows must be crafted.

### Hunter / Sniper
Traps are sold at our [Inn Tool Dealers](Dealers.md#enhanced-tool-dealer) in additional to typical locations.

No other changes to Hunter skills.

### Dancer / Gypsy & Bard / Clown (Minstrel) 
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Buff Icons</td>
                <td>N/A</td>
                <td>Song buff icons are added and with other player buffs.</td>
            </tr>
            <tr>
                <td>Buff Duration</td>
                <td>Song buffs end as soon a player exits the song area.</td>
                <td>Song buff will continue for 20 seconds after leaving the song area.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/bd_rokisweil.gif" alt="">Loki's Veil</td>
                <td>Blocks all skill use for everything (including players) within area of effect.</td>
                <td>Cannot be used on MVP maps. </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/cg_hermode.gif" alt="">Wand of Hermode</td>
                <td>Skill is an ensamble and requires both a Clown and Gypsy to perform.</td>
                <td>Skill can be performed solo.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->
## Super Novice
<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Death Count</td>
                <td>If a Super Novice can manage to avoid even a single death until job 70 and onwards, you will get +10 for all stats. If you die anytime afterwards, you will lose that bonus.</td>
                <td>Super Novice death count can be reset at a <a href="../Custom_NPC/#other">special NPC south of Prontera</a>.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/nv_breakthrough.png" alt="">Breakthrough</td>
                <td>Breakthrough is an Expanded Super Novice skill that has been adjusted for Pre-Renewal.</td>
                <td>
                    Increases your ATK, Max HP, Max SP, and incoming healing amounts.<br><br>
                    <strong>Level 1</strong>: ATK + 10, Max HP + 200, Max SP + 20, Healing Amount +2%<br>
                    <strong>Level 2</strong>: ATK + 20, Max HP + 400, Max SP + 40, Healing Amount +4%<br>
                    <strong>Level 3</strong>: ATK + 30, Max HP + 600, Max SP + 40, Healing Amount +6%<br>
                    <strong>Level 4</strong>: ATK + 40, Max HP + 800, Max SP + 80, Healing Amount +8%<br>
                    <strong>Level 5</strong>: ATK + 60, Max HP + 1,000, Max SP + 100, Healing Amount +10%
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/nv_transcendence.png" alt="">Transcendence</td>
                <td>Transcendence is an Expanded Super Novice skill that has been adjusted for Pre-Renewal.</td>
                <td>
                    Increases your MATK, Max HP, Max SP, and incoming healing amounts.<br><br>
                    <strong>Level 1</strong>: MATK + 10, Max HP + 200, Max SP + 20, Healing Amount +2%<br>
                    <strong>Level 2</strong>: MATK + 20, Max HP + 400, Max SP + 40, Healing Amount +4%<br>
                    <strong>Level 3</strong>: MATK + 30, Max HP + 600, Max SP + 40, Healing Amount +6%<br>
                    <strong>Level 4</strong>: MATK + 40, Max HP + 800, Max SP + 80, Healing Amount +8%<br>
                    <strong>Level 5</strong>: MATK + 60, Max HP + 1,000, Max SP + 100, Healing Amount +10%
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/nv_helpangel.png" alt="">Angel, Help me!</td>
                <td>Angel, Help me! is an Expanded Super Novice skill that has been adjusted for Pre-Renewal.</td>
                <td>
                    Restores HP and SP for you and your party members in a 15x15 cells around you.<br><br>
                    HP per second 500, SP per second 100. Duration of 20 seconds. Cooldown of 300 seconds.
                </td>
            </tr>
        </tbody>
    </table>
</div>



---

## Extended Classes
Many previously unequippable items are now accessible to Extended Classes: [see the full list](Item_Changes.md#extended-classes).


<!---------------------------------------------------------------------------->
### Taekwon

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Fame System</td>
                <td>Fame points earned are kept permanently. The top 10 ranked taekwon players are able to perform infinite combos and receive tripled Maximum HP and SP at level 90. Fame points are ignored if player changes job to Star Gladiator. Rankings can be checked with <code>/taekwon</code> in game.</td>
                <td>Fame points decay by 10% per month, to support better game balance.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

#### Star Gladiator

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/sg_feel.gif" alt="">Feeling of the Sun, Moon, and Stars</td>
                <td>Permanently memorize a map for bonuses for "Place of the Sun", "Place of the Moon", and/or "Place of the Stars".</td>
                <td>An <a href="../Custom_NPC/#skills">NPC named Salvia</a> is available in the <a href="../Inns.md/#locations">Prontera West inn</a> to reset Feeling for a fee.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/sg_hate.gif" alt="">Hatred of the Sun, Moon, and Stars</td>
                <td>Permanently memorize a monster for bonuses for "Target of the Sun", "Target of the Moon", or "Target of the Stars".</td>
                <td>An <a href="../Custom_NPC/#skills">NPC named Salvia</a> is available in the <a href="../Inns.md/#locations">Prontera West inn</a> to reset Hatred for a fee.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/sj_document.gif" alt="">Miracle of the Sun, Moon, and Stars</td>
                <td>Miracle has a low rate to grant the ability to use all Solar, Lunar, and Stellar-aligned skills on any map on any day of the week. This means offensive and supporting skills are stacked as well. The effect lasts for one hour and disappears if the player logs off or switches maps.</td>
                <td>Success rate increased from 0.02% to 0.1%.</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

#### Soul Linker

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Max Job Level</td>
                <td>50</td>
                <td>Increased to 70: HP/SP pool is unchanged.</td>
            </tr>
            <tr>
                <td>Soul Link Duration (Level 5)</td>
                <td>5 minutes</td>
                <td>10 minutes</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/sl_sma.gif" alt="">Esma</td>
                <td>SP Cost for Level 1–10: 8–80</td>
                <td>Decreased SP Cost for Level 1–10: 4–40</td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

### Ninja 
Ninja's skill materials and ammo can are sold by our [Enhanced NPC Dealers](Dealers.md#ninja-materials) in addition to their typical locations. Weapons and other gear are not sold at this NPC.

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/nj_zenynage.gif" alt="">Throw Zeny</td>
                <td>
                    After cast delay of 5 seconds.<br>
                    SP cost of 50.
                </td>
                <td>
                    Reduced after cast delay to 2 sec.<br>
                    Reduced SP cost to 25.<br>
                    Halves the amount of zeny used during WoE.<br>
                    Disabled cost during BG.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/nj_kunai.gif" alt="">Throw Kunai</td>
                <td>After cast delay of 1 second.</td>
                <td>Reduced after cast delay to 0.5 seconds.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/nj_issen.gif" alt="">Final Strike</td>
                <td>SP cost for level 1-10 is 55-100.</td>
                <td>Reduced SP cost to 30-50. </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/nj_huuma.gif" alt="">Throw Huuma Shuriken</td>
                 <td>
                    After cast delay of 2 seconds.<br>
                    SP cost for level 1-5 is 20, 25, 30, 35, 40.
                </td>
                <td>
                    Reduced after cast delay to 1.5 seconds.<br>
                    Reduced SP cost to 5, 10, 15, 20, 25. 
                </td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

### Gunslinger
Gunslinger's skill materials and ammo can are sold by our [Enhanced NPC Dealers](Dealers.md#gunslinger-materials) in addition to their typical locations. Weapons and other gear are not sold at this NPC.

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="../img/Class_Changes/gs_glittering.gif" alt="">Flip the Coin</td>
                <td>
                    Success chance for level 1-5 of 10-30%.<br>
                    SP cost of 2.
                </td>
                <td>
                    Increased success chance to 100%.<br>
                    Decreased SP cost to 1.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/gs_tripleaction.gif" alt="">Triple Action</td>
                <td>SP cost of 20.</td>
                <td>Decreased SP cost to 12.</td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/gs_adjustment.gif" alt="">Adjustment</td>
                <td>
                    Cost of 2 coins.<br>
                    SP cost of 15.<br>
                    Duration of 20 seconds.
                </td>
                <td>
                    Decrease cost to 1 coin.<br>
                    Decreased SP cost to 10.<br>
                    Increased duration to 60 seconds.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/gs_rapidshower.gif" alt="">Rapid Shower</td>
                <td>
                    After cast delay of 1 second.<br>
                    SP cost level 1-10 of 22-40.<br>
                    Consumes 5 bullets.
                </td>
                <td>
                    Decreased after cast delay to 0.75 seconds.<br>
                    Decreased SP cost of level 1-10 to 12-20.<br>
                    Modified bullet consumpion: 1 ammo at level 1/2, 2 ammo at 3/4, 3 ammo at 5/6, 4 ammo at 7/8, and 5 ammo at 9/10.
                </td>
            </tr>
            <tr>
                <td><img src="../img/Class_Changes/gs_fullbuster.gif" alt="">Full Buster</td>
                <td>
                    After cast delay for level 1-10 of 1.2-3 seconds.<br>
                    SP cost level 5-10 of 40-65.
                </td>
                <td>
                    Decreased maximum after cast delay to 2 seconds.<br>
                    Decreased SP cost of level 5-10 to 35.
                </td>
            </tr>
        </tbody>
    </table>
</div>



<!---------------------------------------------------------------------------->

## Adoptee

<div class="class-changes-table">
    <table>
        <thead>
            <tr>
                <th>Topic</th>
                <th>iRO Offical Behavior</th>
                <th>uaRO Changed Behavior</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Maximum Stats</td>
                <td>Adopted characters cannot increase a stat past 80 base.</td>
                <td>Increase stat maximum to 99.</td>
            </tr>
        </tbody>
    </table>
</div>