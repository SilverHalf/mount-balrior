---
layout: page
title: LCM Strategy
nav_order: 1
parent: Legendary Ura
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn .uralm} [Frequently Asked Questions](./faq.html){: .btn .uralm}

# Legendary Ura Strategy Guide
{: .no_toc}

<details>
<summary><b>Table of Contents</b></summary>
<div markdown=block>
1. TOC
{:toc}

---
</div>
</details>

Legendary Godscream Ura is an extreme challenge that requires near-perfect execution to be cleared.
Many concepts generally carry over from the [Challenge Mode Strategy](../ura/strategy.html), so it is highly recommended to be familiar with Challenge Mode and with your chosen class before attempting to progress the Legendary Mode.

---

#### Main Points
{: .no_toc}
- Two very different strategies are popular: [Spawner](#spawner-strategy) and [Willbender](#willbender-strategy).
- The fight is an extremely tight DPS check, requiring every player to pull their weight.
- An inordinate amount of CC is required throughout the fight.
- The ranged group will have to [double drop](../ura/strategy.html/#double-sharding-toxic-geysers) for the entire fight. There are several ways of doing this depending on strategy and composition.
- [Tanking Ura](../ura/mechanics.html#tanking-ura), facing her in the right direction and timing CC correctly is essential to avoid her casting [Propel] and upkeep high DPS uptime.
- The final phase spawns multiple [Legendary Ventshots] that introduce extreme damage and CC pressure.

<img class=divider>

## Overview

Ura's overall mechanics and flow remain similar from CM to LCM. There are two primary ways to approach the encounter, outlined below. The choice of which strategy to play depends on your squad's overall experience, preferences and region. 

<div class="index-container">
<div class="strategy bordered" markdown=block>
#### [Spawner](#spawner-strategy)
{: .no_toc .center}
An extension of the CM strategy to LCM with some composition changes. Popular on the NA server.

<img class=pro> Build and class diversity similar to CM.<br>
<img class=con> More difficult execution.<br>
<img class=con> [More difficult DPS check](https://docs.google.com/spreadsheets/d/1PgCP4ilNxd5QcbvztkzXe7WB2LtZ2A-qpIPy_2y7Ssw/edit?usp=sharing). 
</div>
<div class="strategy bordered" markdown=block>
#### [Willbender](#willbender-strategy)
{: .no_toc .center}
A mostly LCM-only strategy that takes advantage of some mechanical interactions to simplify the fight. Popular on the EU server.

<img class=pro> Easier execution.<br>
<img class=pro> [Easier DPS check](https://docs.google.com/spreadsheets/d/1PgCP4ilNxd5QcbvztkzXe7WB2LtZ2A-qpIPy_2y7Ssw/edit?usp=sharing).<br>
<img class=con> Strict composition with little to no variation.<br>
<img class=con> Depends on <img class='inline willbender'> [Willbender] for DPS.
</div>
</div>

<img class=divider>

## Spawner Strategy

This strategy plays out in a similar manner to Ura Challenge mode for the first three phases. Every point in the [Challenge Mode Strategy Guide](../ura/strategy.html) is applicable here.

- For the _ranged group_ the main difference lies in [double sharding](../ura/strategy.html/#double-sharding-toxic-geysers), and everything that goes along with learning and executing a [ranged rotation](#ranged-rotation) properly.
- For the _melee group_, the differences lie in the fight's overall requirements: with such a tight DPS check, there is little to no room for mistakes.
- The _tank_ will have a fundamental role, as beyond [preventing propel](../ura/strategy.html#preventing-propel), they must often call CC for the rest of the group. Proper CC timings to minimize the uptime of <img class='inline risingpressure'> [Rising Pressure] can improve overall DPS by up to 5-10%, which is often the difference between killing or wiping to enrage.
- The final phase, from 30% post-heal to kill, has extreme CC and damage pressure. The usual approach is to upkeep permanent <img class='inline stability'> [Stability] and projectile reflection for the entirety of the phase's duration.

---

### Composition

The composition remains based on the division between a _ranged group_ and a _melee group_ introduced in CM. The ranged group is usually composed of:
- A heal <img class='inline chrono'> [Chronomancer] bringing extra CC.
- A hybrid celestial healer, usually a <img class='inline scourge'> [Scourge].
- A specialized <img class='inline deadeye'> [Deadeye] build that can satisfy the encounter's excessive CC requirements.
- One DPS, usually a <img class='inline mechanist'> [Mechanist] running <img class='inline shift'> [Shift Signet].

The melee group contains everyone else, except for one DPS that covers the role of *tank*. 

Spawner strategy compositions can be relatively flexible, depending on the extra utility brought by the boonDPS and DPS. An example could be as follows:
<div>
<table class="fl-table padded">
    <thead>
        <tr>
            <th>Sub</th>
            <th>Build</th>
            <th>Role</th>
            <th>Melee</th>
            <th>Ranged</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#builds-and-povs"><img class='inline deadeye'> CC Deadeye</a></td>
            <td>CC + Ranged</td>
            <td></td>
            <td>2</td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#builds-and-povs"><img class='inline scourge'> Celestial Scourge</a></td>
            <td>Ranged</td>
            <td></td>
            <td>3</td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#builds-and-povs"><img class='inline firebrand'> Quick Firebrand</a></td>
            <td>Melee</td>
            <td>A</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td>DPS</td>
            <td>Melee</td>
            <td>B</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td>DPS</td>
            <td>Melee</td>
            <td>C</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="#builds-and-povs"><img class='inline chrono'> Heal Chronomancer</a></td>
            <td>Ranged</td>
            <td></td>
            <td>1</td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td>BoonDPS</td>
            <td>Melee</td>
            <td>D</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td>DPS</td>
            <td>Melee</td>
            <td>E</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td>DPS</td>
            <td>Ranged</td>
            <td></td>
            <td>4</td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td>DPS</td>
            <td>Tank</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>
</div>

<img class='inline deadeye'> [Deadeye] is almost ubiquitous due to its unique ability to constantly dish out massive CC by spamming <img class='inline distracting-throw'> [Distracting Throw] and resetting their initiative with <img class='inline m7'> [Maleficent Seven](https://wiki.guildwars2.com/wiki/Maleficent_Seven). <img class='inline chrono'> [Chronomancer] is similarly almost always present due to its incredible boon access, <img class='inline stability'> [Stability] uptime, CC output, healing and general utility. <img class='inline scourge'> [Scourge] is usually played with a celestial build, since it brings additional damage without sacrificing much in the way of healing and utility, and is sometimes replaced by another celestial healer such as <img class='inline specter'> [Specter].

For boonDPS, the most common choice is <img class='inline firebrand'> [Firebrand], as beyond doing excellent damage they can provide abundant condition cleanse, <img class='inline stability'> [Stability] with <img class='inline stand-ground'> [Stand Your Ground!], and projectile reflection with <img class='inline wall-reflect'> [Wall of Reflection] and <img class='inline bulwark'> [Chapter 3: Valiant Bulwark]. Two <img class='inline firebrand'> [Firebrands] can upkeep 100% projectile reflection uptime if one of them is running <img class='inline wall-reflect'> [Wall of Reflection], though this is a little tight so often the healers will help out with either <img class='inline feedback'> [Feedback] on a <img class='inline chrono'> [Chronomancer], <img class='inline smoke-screen'> [Smoke Screen] on the <img class='inline deadeye'> [Deadeye], or <img class='inline cpc'> [Corrosive Poison Cloud] on a <img class='inline scourge'> [Scourge].

The tank players usually do not participate in the melee rotation, but all other DPS and boonDPS do. While not strictly necessary, running one or more <img class='inline power'> [Power] damage dealers can be beneficial, as [Titanspawn Geysers] have less armor.

---

#### Builds and PoVs

This is a non-exhaustive list of playable builds on the encounter. If anything is outdated, you can find up-to-date information on <img class='inline vl-icon'> [Void Lounge](https://discord.com/invite/voidlounge).

|Build|Role|PoV|Last updated|
|<img class='inline chrono'> [Heal Chronomancer](https://gw2skills.net/editor/?PigEQiWmBzCrhNiH9karD-DSRYjR1VPSIFlRLpQ6VluvGCSo83S7bWQFA-e)|Healer & Toxics||August 2025|
|<img class='inline deadeye'> [CC Deadeye](https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oivMapCCLFc82gK0HUB-e)|CC Bot & Toxics|[PoV](https://youtu.be/hxm8MSuFuyo), [Golem](https://youtu.be/vH_CbAcGEjo), [Guide](https://docs.google.com/presentation/d/19xXTt8iPkvoDVG_I_TEQOd_Xyw4R6ZdB90SOWWzzh4M)|September 2025|
|<img class='inline scourge'> [Offensive Hybrid Scourge](https://gw2skills.net/editor/?PSAFo8FbYZGsPGILiNiF711rH-DyIY1on/M6SKkrKQh/KGSQsHeNB4BDUB-e)|Hybrid Heal & Toxics|[PoV](https://youtu.be/0skBqF5KlFA)|September 2025|
|<img class='inline scourge'> [Defensive Hybrid Scourge](https://gw2skills.net/editor/?PSwAo+ZlZwiYfsH2ImqXXveA-DyIY1oj/U6SCkqIIXFQ6CBD/rYIBxe41AiHMQFA-e)|Hybrid Heal & Toxics||September 2025|
|<img class='inline firebrand'> [Quick Firebrand (Reflect)](https://en.gw2skills.net/editor/?PWyAo+rlRExe6ZQBttkGZkW0WbPTA-DSJYyRL/hkjkKBFQHCBF+r4IBxW41AiPNQFA-e)| BoonDPS & Reflect |[PoV](https://youtu.be/J5zNxbxZInI)|September 2025|
|<img class='inline firebrand'> [Quick Firebrand (Elite Mantra)](https://en.gw2skills.net/editor/?PWyAo+rlRExe6ZQBtukmZkW0WbPTA-DSJYyRL/hkjkKBFQHCBx+r4IBxW41sjPNQFA-e)| BoonDPS & Reflect ||September 2025|
|<img class='inline firebrand'> [Quick Firebrand (SYG)](https://en.gw2skills.net/editor/?PWyAo+rlRExe6ZQBNskGZkW0WbPTA-DSJYyRL/hkjkKBFQHCBF+r4IBxW41AiPNQFA-e)| BoonDPS & Reflect ||September 2025|
|<img class='inline mechanist'> [2-kit Mechanist](https://snowcrows.com/builds/raids/engineer/condition-mechanist-two-kits)|DPS (& Toxics) |[PoV](https://youtu.be/YZA5kr7REVg)|September 2025|
|<img class='inline daredevil'> [Condi Daredevil](https://gw2skills.net/editor/?PagAgilRwOYfMKWJO2W1NNA-DSJYmRD/ZUgCoDJgC/VEgA1AvmZ8gBA-e)|DPS|[PoV](https://www.youtube.com/watch?v=YQ4ZJvkXoEA)|September 2025|
|<img class='inline vindicator'> [Power Vindicator](https://gw2skills.net/editor/?PmyAExzlxQmMP6k1RpMOClRSqMCqkJ7lasC-DSRYBRN33cQgHSmSggFCVoCk5dijEG7h3i+LYQFA-e)|DPS & Titanspawners|[PoV](https://youtu.be/sgiPQ1FeqLI)|September 2025|
|<img class='inline scrapper'> [Power Scrapper](https://gw2skills.net/editor/?PeQAIlJw0YcsNWKO2LvteA-DSRYBRBH2cQnnRtSgKUAy8bRQCjNwrhCnRgKA-e)|DPS & Titanspawners |[PoV](https://www.youtube.com/watch?v=d82vtsmHL38)|September 2025|

---

#### Extra Build Information

Here you will find additional tips on how to tweak certain common builds to your squad's requirements.

<details class='faq'>
<summary><img class='inline chrono'> Heal Chronomancer</summary>
<div markdown=block>
By default takes <img class='inline precog'> [Well of Precognition] but if you are paired with a Quick <img class='inline firebrand'> [Firebrand] who is comfortable with providing <img class='inline stability'> [Stability], then you could also drop the well, replacing it with:
- <img class='inline blink'> [Blink] for early prog, to cover up mistakes and manage mechanics. It is also useful to bait Ura into casting [Propel] in a specific direction.
- <img class='inline feedback'> [Feedback] allows you to backup projectile blocks in p4, and if taken along with the <img class='inline medic-feedback'> [Medic Feedback] trait also gives you extra ress ability.
- An additional CC skill (such as <img class='inline technobabble'> [Technobabble], <img class='inline domination'> [Signet of Domination], <img class='inline senility'> [Well of Senility]) can be useful to quickly solo CC [Toxic Geysers] from range (otherwise you can solo CC with <img class='inline moa'> [Signet of Humility] and <img class='inline collapse'> [Mental Collapse] with <img class='inline clarity'> [Clarity]; or with <img class='inline moa'> [Signet of Humility] and <img class='inline sharpshooter'> [Phantasmal Sharpshooter] , but the latter requires very good timing). This can be useful when the <img class='inline deadeye'> [Deadeye] is inexperienced, and when they cannot otherwise CC.
</div>
</details>

<details class='faq'>
<summary><img class='inline scourge'> Celestial Hybrid Scourge</summary>
<div markdown=block>
You can tweak your build based on how aggressive you want to be.

- **Offensive**: runs the <img class='inline curses'> [Curses] and <img class='inline reaping'> [Soul Reaping] traitlines for some additional damage. Has a lower cooldown on <img class='inline cpc'> [Corrosive Poison Cloud], which means that they can cover reflect with only a single <img class='inline firebrand'> [Firebrand]. Also runs sword offhand for extra movement. The downsides are less healing and no <img class='inline stability'> [Stability], so the <img class='inline firebrand'> [Firebrand] in the same subgroup should bring extra.
- **Defensive**: runs <img class='inline blood-magic'> [Blood Magic] instead of <img class='inline curses'> [Curses] for more healing, <img class='inline stability'> [Stability] and boons. The downside is less damage and a longer cooldown on <img class='inline cpc'> [Corrosive Poison Cloud], which means you need to account for either a more difficult projectile block rotation that involves additional people, or (better) you need at least two <img class='inline firebrand'> [Firebrands] with the <img class='inline scourge'> [Scourge] just backing up.
- **Middle ground**: play the offensive build with <img class='inline anguish'> [Trail of Anguish] instead of <img class='inline blood-power'> [Blood is Power], so you have a <img class='inline stability'> [Stability] skill available.
</div>
</details>

<details class='faq'>
<summary><img class='inline deadeye'> CC Deadeye</summary>
<div markdown=block>
For the most part there is only one specific build, but some small variations are possible. Depending if you are [tunneling](strategy.html#tunneling) or not, you can play with/without weapon swap.

If you are learning to play this build, check out Chupathingy's excellent <img class='inline deadeye'> [CC Deadeye Guide](https://docs.google.com/presentation/d/19xXTt8iPkvoDVG_I_TEQOd_Xyw4R6ZdB90SOWWzzh4M) for more information.

{: .note}
If you need to provide <img class='inline might'> [Might] and <img class='inline fury'> [Fury], you should take <img class='inline midnight'> [Relic of the Midnight King]. Otherwise, take <img class='inline speed'> [Relic of Speed] for permanent <img class='inline superspeed'> [Superspeed].
</div>
</details>

<details class='faq'>
<summary><img class='inline firebrand'> Condition Quickness Firebrand</summary>
<div markdown=block>
There are a few variations in your loadout depending on your squad's needs:

- <img class='inline wall-reflect'> [Wall of Reflection] is needed once per squad. This player should call the projectile block rotation, which is <img class='inline wall-reflect'> [Wall of Reflection] -> <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] -> fill – where the fill is either <img class='inline cpc'> [Corrosive Poison Cloud], or another <img class='inline firebrand'> [Firebrand]'s <img class='inline bulwark'> [Chapter 3: Valiant Bulwark]. Loses ~3.7k DPS from the bench.
- Running <img class='inline liberation'> [Mantra of Liberation] and <img class='inline purging'> [Purging Flames] (recommended) gains additional cleanses and <img class='inline stability'> [Stability]  with a group <img class='inline stunbreak'> [Stunbreak] on the elite, losing ~2.7k DPS from the bench and the <img class='inline superspeed'> [Superspeed] from <img class='inline feel-my-wrath'> [Feel My Wrath!].
- Running <img class='inline feel-my-wrath'> [Feel My Wrath!] and <img class='inline stand-ground'> [Stand Your Ground!] has the advantage of still providing <img class='inline superspeed'> [Superspeed] to quickly run to the [Titanspawn Geysers]. Use <img class='inline stand-ground'> [Stand Your Ground!] for the Titanspawn and <img class='inline epilogue'> [Epilogue: Unbroken Lines] for [Steam Prison]. This loses ~3.7k DPS from the bench.
- Running <img class='inline liberation'> [Mantra of Liberation] and <img class='inline stand-ground'> [Stand Your Ground!] trades even more DPS (~6.3k) for more <img class='inline stability'> [Stability], which can be done if people in your sub get knocked around a lot, such as when running an offensive <img class='inline scourge'> [Scourge].

<div style="color: grey">Numbers from Iskarel and SC.</div>
</div>
</details>

---

### Rotations

The melee group consists of five people, and the melee rotation works in pretty much the same way as in CM. Following it as closely as possible is the key to smooth reproducible runs and progression. _Always_ call out the next person in the rotation and mention where you are dropping your shard. It is possible also to run without a fixed melee rotation if all players are participating without any issues.

In general, with five people following the rotation there is enough leeway to skip one player. Issues arise when players make multiple mistakes in succession, in which case it may be necessary to have a tank temporarily pick up a shard.

Ranged players will be [double sharding](../ura/strategy.html/#double-sharding-toxic-geysers) for the entirety of the fight. Using an [overlay](../ura/strategy.html#marker-packs) is basically mandatory, since callouts are usually done exclusively with geyser numbers or symbols.

<img class='inline sheets'> [NA Pug Rotation by Narra](https://docs.google.com/spreadsheets/d/e/2PACX-1vTRRf8AogRxhW1trZYtEtOPlQzA5WaZjZD64s90_IuGrxyWGjgwLCo3yBQRCAytN8VGu6gALfMAw9V8/pubhtml?gid=591640946&single=true)
{: .btn}

This rotation includes a DPS player alongside the healers as a fourth member. This is usually a <img class='inline mechanist'> [Mechanist] with <img class='inline shift'> [Shift Signet], or another specialization with similar mobility and damage. This gives the ranged group overall more leeway in exchange for a slight loss in DPS for the ranged damage player.

<img class='inline sheets'> [EU Pug Rotation by Luna](https://docs.google.com/spreadsheets/d/e/2PACX-1vQttaDhjhxuvL_VH61ieYoJSYwn2odinF7puAqlxfgMd397TE4ifA3-htNj8iXWBRF15qFkR9vDSxA9/pubhtml?gid=1491958775&single=true)
{: .btn}

This rotation optimizes the order in which the geysers are <img class='inline dispel'> [Dispelled] to make double dropping a bit easier. It also has other small tweaks to reduce strain on the healers, including the introduction of a DPS aiding the 40% transition. This results in slightly higher DPS in exchange for slightly more stress on the ranged group.

---

### Managing the Final Phase
In the final phase, you will have immense incoming pressure from [Legendary Ventshots] on the field. This requires special attention to be survived. 


#### Preparation
{: .no_toc}
Given that the total number of [Legendary Ventshots], [Champion Fumarollers] and [Titanspawn Geysers] in phase 4 cannot exceed six, it's often common to stop killing [Titanspawn Geysers] _before_ transitioning, so that they can fill up this cap. In general:

- If you are running a "safer" composition with two full healers, such as two heal <img class='inline chrono'> [Chronomancers], you can stop killing Titanspawners as soon as 15% HP in the main phase. Be warned though: this will spawn more [Champion Fumarollers], which in turn requires extra healing and <img class='inline stability'> [Stability].
- If you are running a more aggressive composition, typically with a single heal <img class='inline chrono'> [Chronomancer] and a hybrid <img class='inline scourge'> [Scourge], then it is more difficult to manage multiple Fumarollers on stack. For this reason, it is best to stop killing Titanspawners only on entering the final phase (optionally killing the first if it spawns in an extremely convenient position).

#### Survival
{: .no_toc}
You will want to be [facing Ura](../ura/strategy.html#tanking-ura) towards the North-West, in order to position the squad at the shortest possible difference from the safe drop zone for [Sulfuric Geysers], behind #9.

You will need to upkeep permanent projectile reflection to safeguard the group from the [Legendary Ventshots]' ranged attacks. One of the <img class='inline firebrand'> [Firebrands] will be running <img class='inline wall-reflect'> [Wall of Reflection], and should be calling out the skill rotation. This generally repeats:
1. The first <img class='inline firebrand'> [Firebrand] casting <img class='inline wall-reflect'> [Wall of Reflection].
2. The first <img class='inline firebrand'> [Firebrand] casting <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] when 10-11s are remaining on their cooldown for <img class='inline wall-reflect'> [Wall of Reflection].
3. A filler skill provided by another player, usually either a second <img class='inline firebrand'> [Firebrand]'s' <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] or a <img class='inline scourge'> [Scourge]'s <img class='inline cpc'> [Corrosive Poison Cloud]. When this ends, <img class='inline wall-reflect'> [Wall of Reflection] should be ready again.

If you are running only a single <img class='inline firebrand'> [Firebrand], replace the second step with a <img class='inline feedback'> [Feedback].

Try to count down the time remaining on your reflect, and call for backup if your skills are not available. Remember that:
- <img class='inline wall-reflect'> [Wall of Reflection] lasts for 10 seconds (with <img class='inline master-consecrations'> [Master of Consecrations]).
- <img class='inline cpc'> [Corrosive Poison Cloud] lasts for 8 seconds.
- <img class='inline smoke-screen'> [Smoke Screen] lasts for 7 seconds.
- <img class='inline feedback'> [Feedback] lasts for 6 seconds.
- <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] lasts for 5 seconds.

It is also important to upkeep <img class='inline stability'> [Stability] on the group, to manage both Ura and the Ventshots' melee attacks. <img class='inline chrono'> [Chronomancers] running <img class='inline stab-mantra'> [Mantra of Concentration] and <img class='inline precog'> [Well of Precognition] can achieve this solo by using [this rotation](https://www.youtube.com/watch?v=ZNt3AbNwiuw) from Schwifty. Otherwise, they will have to coordinate with their <img class='inline firebrand'> [Firebrand].

---

### Meeting the DPS check

Legendary Ura has an effective health of 137,161,289 HP and a maximum encounter duration of 11 minutes. This means that effectively, a group will need to average overall 208k total DPS to clear the encounter before enrage.

This number is greatly influenced by <img class='inline risingpressure'> [Rising Pressure]. Correct management of the damage reduction will make or break a pull. Always keep an eye on the number of stacks on the boss: try to CC when she reaches 5 stacks. In earlier phases, when she does not have much <img class='inline titanicresistance'> [Titanic Resistance], it can be hard to reach 5 before breaking: try then to CC at 3 or 4.

Always try to CC as soon as she gains a stack of <img class='inline risingpressure'> [Rising Pressure]. This can increase your DPS by 3-4% easily, which is equivalent to 20-25 seconds on the enrage timer.

Players should have an up-to-date build (check the [builds section](#builds-and-povs) above and [Snowcrows](https://snowcrows.com/)), and should be competent with their class and rotation, practicing it if necessary on the [DPS golem](https://snowcrows.com/guides/arcdps/special-forces-area). Players should aim to do as much damage as possible while not failing mechanics.

To have an indicative understanding of how much DPS is necessary to clear the encounter, check the spreadsheet [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQRWHzmW9qli-mQ_MBS_uq65Bd64jy-djaDM7-Lt5sAcTqeuaOER3an1XNsS054DZeKg06ehE_Cf4_g/pubhtml).

<img class=divider>

## Willbender Strategy

Developed by Asterius (see his original spreadsheet <img class='inline sheets'> [here](https://docs.google.com/spreadsheets/d/1gOhbFgtSnaW_8T1m12PgZe8lG7VH-P3IckXoPUPqNdA)), this is a variation on the standard that has significant differences in composition and strategy. These mainly come down to two major changes:

- The melee group does not kill [Titanspawn Geysers].
- Every DPS will play <img class='inline condition'> [Condition] <img class='inline willbender'> [Willbender].

---

#### Why not kill Titanspawners?
{: .no_toc}
The primary reason is to take advantage of the cap on [Legendary Ventshots] in phase 4. [Legendary Ventshots] can only spawn if there are less than 6 entities alive, including [Champion Fumarollers] and [Titanspawn Geysers]. By not killing any Titanspawners, the aim is to have as many entities as possible when going into the final phase. This, combined with a couple of [Champion Fumarollers] surviving from the previous phase, will prevent Ventshots from spawning at the start of phase 4.

Once all [Champion Fumarollers] are dead, depending on where the Titanspawners generated, you can still have up to 1-2 [Legendary Ventshots], but since these are few and spawn late into phase 4, you don't need permanent projectile block. This makes the final phase much easier compared to the standard strategy, as a major difficulty factor is removed.

Furthermore, this has the added advantage of always keeping the melee group in a single stack. Management of the [Bloodstone Shard] is simplified due to not having to <img class='inline dispel'> [Dispel] Titanspawners, the group has higher DPS uptime on the boss and hence higher squad dps overall, and it is easier to rez people that go downstate. The only reason for DPS to leave the stack is to place [Sulfuric Geysers] and [Steam Prison].

---

#### Why Willbenders?
{: .no_toc}
With many [Titanspawn Geysers] surviving throughout the fight, you will also get many [Champion Fumarollers] (up to 10 Titanspawners & Fumarollers combined). <img class='inline willbender'> [Willbender] shines in these circumstances, as beyond already being a strong build with high damage, mobility and cleanse, it also:

- Gains excellent access to <img class='inline stability'> [Stability] by running <img class='inline stand-ground'> [Stand Your Ground!] for a minimal DPS loss.
- Gains increased damage and cooldown reduction due to <img class='inline perm-wrath'> [Permeating Wrath] and <img class='inline restore-virtues'> [Restorative Virtues] striking multiple enemies for most of the fight, which in turn increases DPS on Ura as well.

At the same time though, you want to kill [Champion Fumarollers] as fast as possible in order to not get overwhelmed by them. They generally spawn fast enough to supply a constant stream of multi-target cleave.

---

### Composition

This composition is much more rigid compared to the [standard strategy](#standard-strategy). <img class='inline chrono'> [Chronomancer] is almost always present due to its incredible boon access, <img class='inline stability'> [Stability] uptime, CC output, healing and general utility. Similarly, celestial <img class='inline specter'> [Specters] provide decent <img class='inline stability'> [Stability] and boons, excellent CC and mobility, and can also upkeep <img class='inline vuln'> [Vulnerability] (which would otherwise be lacking) and <img class='inline poison'> [Poison] (required for <img class='inline thorns-relic'> [Relic of Thorns]).

<table class="fl-table padded">
    <thead>
        <tr>
            <th>Sub</th>
            <th>Build</th>
            <th>Role</th>
            <th>Melee</th>
            <th>Ranged</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline specter'> Cele Specter</a></td>
            <td>Ranged</td>
            <td></td>
            <td>1</td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline chrono'> Heal Chronomancer</a></td>
            <td>Ranged</td>
            <td></td>
            <td>2</td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline willbender'> DPS</a></td>
            <td>Melee</td>
            <td>A</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline willbender'> DPS</a></td>
            <td>Melee</td>
            <td>B</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline willbender'> DPS</a></td>
            <td>Melee</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline specter'> Cele Specter</a></td>
            <td>Ranged</td>
            <td></td>
            <td>3</td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline chrono'> Heal Chronomancer</a></td>
            <td>Ranged</td>
            <td></td>
            <td>4</td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline willbender'> DPS</a></td>
            <td>Melee</td>
            <td>C</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline willbender'> DPS</a></td>
            <td>Melee</td>
            <td>D</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline willbender'> DPS</a></td>
            <td>Melee</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

All four supports are part of the ranged group. The abundance of [Champion Fumarollers] makes it harder for them to move around and do mechanics, so the <img class='inline chrono'> [Chronomancers] will usually run <img class='inline blink'> [Blink], and the <img class='inline specter'> [Specters] <img class='inline shadowstep'> [Shadowstep].

DPS players should run a mix of Trailblazer and Dire for additional survivability. This brings around 2.5k damage loss in a golem situation, which can be made up with through the more aggressive gameplay this gear enables. <img class='inline chrono'> [Chronomancers] should ensure they have less toughness than the DPS so that they are not targeted by [Champion Fumarollers] while doing mechanics. Generally a [tank](../ura/strategy.html#tanking-ura) is not strictly necessary as the entire group will stay within line-of-sight at all times.

All DPS should bring <img class='inline stand-ground'> [Stand Your Ground!] and use it off-cooldown.

---

#### Builds and PoVs

|Build|Role|PoV|Last updated|
|<img class='inline chrono'> [Heal Chronomancer](https://en.gw2skills.net/editor/?PigEQiWmBzidxQYj4RPp2+A-DSRYjR1DJ4CplUIoIo6CQ3XDBI09wbp9NLoC-e)|Healer & Toxics|[PoV](https://www.youtube.com/watch?v=LM7uye3SYWI)|September 2025|
|<img class='inline specter'> [Celestial Specter](https://en.gw2skills.net/editor/?PawEQbNqMUGLLltxOxx26O2D-DyIY1om/QaRB0lMIShgCfPEkAYP8Wo/SDqA-e)|Toxics|[PoV](https://www.youtube.com/watch?v=5LZMDgfcpg0)|September 2025|
|<img class='inline willbender'> [DPS Willbender (PP/PT)](https://gw2skills.net/editor/?PWABoqp/lVw6YqMMWLW0WXxSA-DSRYcB1TG9cCFSlhQuJQHVgD/KCSQsHeNg4TDUB-e)| DPS |[PoV](https://www.youtube.com/watch?v=VOuZDJKsRJg)|September 2025|
|<img class='inline willbender'> [DPS Willbender (PP/ST)](https://gw2skills.net/editor/?PWABoqt/lVw6YqMMWLW0WXxSA-DSRYcB1TG9cCFSlhQuJQHVgD/KCSQsHeNg4TDUB-e)| DPS ||September 2025|

If anything is outdated, you can find up-to-date builds and PoVS on <img class='inline vl-icon'> [Void Lounge](https://discord.com/invite/voidlounge).

---

### Rotations

For the _melee rotation_, since the strategy ignores [Titanspawn Geysers], the only thing the melee group needs to <img class='inline dispel'> [Dispel] is [Pressure Blast]. For this reason, there are generally only 4 people assigned to the melee rotation, which otherwise works as normal.

For the _ranged rotation_ the strategy uses a 4-man rotation involving all the support players double-dropping.

[<img class='inline sheets'> 4-man Rotation for Willbender Strat by Asterius](https://docs.google.com/spreadsheets/d/1gOhbFgtSnaW_8T1m12PgZe8lG7VH-P3IckXoPUPqNdA/edit?gid=969431177#gid=969431177){: .btn}

Since there is not a dedicated CC <img class='inline deadeye'> [Deadeye], responsibility for CCing [Toxic Geysers] is spread out between all of the ranged group members. Every one of these supports will CC two geysers every rotation:
- The geyser they pick up the [Bloodstone Shard] from.
- The first geyser they <img class='inline dispel'> [Dispel] when double dropping.

<img class='inline specter'> [Specters] can CC with <img class='inline distracting-throw'> [Distracting Throw], and should make sure to have enough initiative to do so. There is generally enough time between the two geysers to have it regenerate.

<img class='inline chrono'> [Chronomancers] will need to save their <img class='inline cs'> [Continuum Split] to ensure that they can get both geysers in series:
1. <img class='inline cs'> [Continuum Split], then <img class='inline moa'> [Signet of Humility] & <img class='inline domination'> [Signet of Domination]/<img class='inline senility'> [Well of Senility]/<img class='inline technobabble'> [Technobabble].
2. <img class='inline moa'> [Signet of Humility] & <img class='inline domination'> [Signet of Domination]/<img class='inline senility'> [Well of Senility]/<img class='inline technobabble'> [Technobabble].

If players cannot CC, they should call for backups. Since all four ranged players are double dropping, there is more flexibility overall compared to a standard strategy.

<img class=divider>

[Return to Home](../index.html){: .btn } [Return to Overview](overview.html){: .btn } [Return to Top](#legendary-ura-strategy-guide){: .btn .fixed}
{: .center}

[Bloodstone Shard]: ../ura/mechanics.html#bloodstone-shards
[Bloodstone Shards]: ../ura/mechanics.html#bloodstone-shards
[Toxic Geyser]: ../ura/mechanics.html#toxic-geysers
[Toxic Geysers]: ../ura/mechanics.html#toxic-geysers
[Sulfuric Geyser]: ../ura/mechanics.html#sulfuric-geysers
[Sulfuric Geysers]: ../ura/mechanics.html#sulfuric-geysers
[Dispel]: ../ura/mechanics.html#-dispel
[Dispelled]: ../ura/mechanics.html#-dispel
[Titanspawn Geyser]: ../ura/mechanics.html#titanspawn-geysers
[Titanspawn Geysers]: ../ura/mechanics.html#titanspawn-geysers
[Create Titanspawn Geyser]: ../ura/mechanics.html#titanspawn-geysers
[Pressure Blast]: ../ura/mechanics.html#pressure-blast
[Pressure Blasts]: ../ura/mechanics.html#pressure-blast
[Titanic Resistance]: ../ura/mechanics.html#-titanic-resistance
[Champion Fumaroller]: ../ura/mechanics.html#champion-fumaroller
[Champion Fumarollers]: ../ura/mechanics.html#champion-fumaroller
[Legendary Ventshots]: ../ura/mechanics.html#legendary-ventshot
[Bloodstone Saturation]: ../ura/mechanics.html#-bloodstone-saturation
[Propel]: ../ura/mechanics.html#propel
[Autoattack Chain]: ../ura/mechanics.html#autoattack-chain
[Rising Pressure]: ../ura/mechanics.html#-rising-pressure
[Steam Prison]: ../ura/mechanics.html#steam-prison
[Return]: ../ura/mechanics.html#return

[Chrono]: https://wiki.guildwars2.com/wiki/Chronomancer
[Chronomancer]: https://wiki.guildwars2.com/wiki/Chronomancer
[Chronomancers]: https://wiki.guildwars2.com/wiki/Chronomancer
[Deadeye]: https://wiki.guildwars2.com/wiki/Deadeye
[Firebrand]: https://wiki.guildwars2.com/wiki/Firebrand
[Firebrands]: https://wiki.guildwars2.com/wiki/Firebrand
[Scourge]: https://wiki.guildwars2.com/wiki/Scourge
[Scrapper]: https://wiki.guildwars2.com/wiki/Scrapper
[Vindicator]: https://wiki.guildwars2.com/wiki/Vindicator
[Mechanist]: https://wiki.guildwars2.com/wiki/Mechanist
[Willbender]: #willbender-strategy-builds-and-povs
[Willbenders]: #willbender-strategy-builds-and-povs
[Specter]: #willbender-strategy-builds-and-povs
[Specters]: #willbender-strategy-builds-and-povs

[Power]: https://wiki.guildwars2.com/wiki/Power
[Condition]: https://wiki.guildwars2.com/wiki/Condition_damage
[Conditions]: https://wiki.guildwars2.com/wiki/Condition_damage
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar
[Aegis]: https://wiki.guildwars2.com/wiki/Aegis
[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Dimensional Aperture]: https://wiki.guildwars2.com/wiki/Dimensional_Aperture
[Superspeed]: https://wiki.guildwars2.com/wiki/Superspeed
[Invulnerable]: https://wiki.guildwars2.com/wiki/Invulnerability
[Wall of Reflection]: https://wiki.guildwars2.com/wiki/Wall_of_Reflection
[Stand Your Ground!]: https://wiki.guildwars2.com/wiki/%22Stand_Your_Ground!%22
[Chapter 3: Valiant Bulwark]: https://wiki.guildwars2.com/wiki/Chapter_3:_Valiant_Bulwark
[Smoke Screen]: https://wiki.guildwars2.com/wiki/Smoke_Screen
[Corrosive Poison Cloud]: https://wiki.guildwars2.com/wiki/Corrosive_Poison_Cloud
[Feedback]: https://wiki.guildwars2.com/wiki/Feedback
[Shift Signet]: https://wiki.guildwars2.com/wiki/Shift_Signet
[Mantra of Concentration]: https://wiki.guildwars2.com/wiki/Mantra_of_Concentration
[Well of Precognition]: https://wiki.guildwars2.com/wiki/Well_of_Precognition
[Master of Consecrations]: https://wiki.guildwars2.com/wiki/Master_of_Consecrations
[Restorative Virtues]: https://wiki.guildwars2.com/wiki/Restorative_Virtues
[Permeating Wrath]: https://wiki.guildwars2.com/wiki/Permeating_Wrath
[Blink]: https://wiki.guildwars2.com/wiki/Blink
[Haste]: https://wiki.guildwars2.com/wiki/Haste
[Stunbreak]: https://wiki.guildwars2.com/wiki/Stun_break
[Quickness]: https://wiki.guildwars2.com/wiki/Quickness
[Vulnerability]: https://wiki.guildwars2.com/wiki/Vulnerability
[Poison]: https://wiki.guildwars2.com/wiki/Poison
[Relic of Thorns]: https://wiki.guildwars2.com/wiki/Relic_of_Thorns
[Shadowstep]: https://wiki.guildwars2.com/wiki/Shadowstep
[Distracting Throw]: https://wiki.guildwars2.com/wiki/Distracting_Throw
[Continuum Split]: https://wiki.guildwars2.com/wiki/Continuum_Split
[Technobabble]: https://wiki.guildwars2.com/wiki/Technobabble
[Signet of Domination]: https://wiki.guildwars2.com/wiki/Signet_of_Domination
[Well of Senility]: https://wiki.guildwars2.com/wiki/Well_of_Senility
[Signet of Humility]: https://wiki.guildwars2.com/wiki/Signet_of_Humility
[Phantasmal Sharpshooter]: https://wiki.guildwars2.com/wiki/Phantasmal_Sharpshooter
[Mental Collapse]: https://wiki.guildwars2.com/wiki/Mental_Collapse
[Clarity]: https://wiki.guildwars2.com/wiki/Clarity
[Corrosive Poison Cloud]: https://wiki.guildwars2.com/wiki/Corrosive_poison_cloud
[Stand Your Ground!]: https://wiki.guildwars2.com/wiki/%22Stand_Your_Ground!%22
[Trail of Anguish]: https://wiki.guildwars2.com/wiki/Trail_of_Anguish
[Blood is Power]: https://wiki.guildwars2.com/wiki/Blood_is_power
[Curses]: https://wiki.guildwars2.com/wiki/Curses
[Soul Reaping]: https://wiki.guildwars2.com/wiki/Soul_Reaping
[Blood Magic]: https://wiki.guildwars2.com/wiki/Blood_Magic
[Wall of Reflection]: https://wiki.guildwars2.com/wiki/Wall_of_Reflection
[Chapter 3: Valiant Bulwark]: https://wiki.guildwars2.com/wiki/Chapter_3:_Valiant_Bulwark
[Mantra of Liberation]: https://wiki.guildwars2.com/wiki/Mantra_of_Liberation
[Purging Flames]: https://wiki.guildwars2.com/wiki/Purging_Flames
[Stunbreak]: https://wiki.guildwars2.com/wiki/Stun_break
[Feel My Wrath!]: https://wiki.guildwars2.com/wiki/%22Feel_My_Wrath!%22
[Epilogue: Unbroken Lines]: https://wiki.guildwars2.com/wiki/Epilogue:_Unbroken_Lines
[Chapter 3: Heated Rebuke]: https://wiki.guildwars2.com/wiki/Chapter_3:_Heated_Rebuke
[Virtues]: https://wiki.guildwars2.com/wiki/Virtues
[Absolute Resolve]: https://wiki.guildwars2.com/wiki/Absolute_Resolve
[Healing Turret]: https://wiki.guildwars2.com/wiki/Healing_Turret
[Lightning Flash]: https://wiki.guildwars2.com/wiki/Lightning_Flash
[Glyph of Lesser Elementals]: https://wiki.guildwars2.com/wiki/Glyph_of_Lesser_Elementals
[Mass Momentum]: https://wiki.guildwars2.com/wiki/Mass_Momentum
[Continuum Split]: https://wiki.guildwars2.com/wiki/Continuum_Split
[Summon Flesh Golem]: https://wiki.guildwars2.com/wiki/Summon_Flesh_Golem
[Charge]: https://wiki.guildwars2.com/wiki/Charge_(necromancer_skill)
[Jurisdiction]: https://wiki.guildwars2.com/wiki/Jurisdiction
[Mantra of Concentration]: https://wiki.guildwars2.com/wiki/Mantra_of_Concentration
[Distracting Throw]: https://wiki.guildwars2.com/wiki/Distracting_Throw
[Might]: https://wiki.guildwars2.com/wiki/Might
[Fury]: https://wiki.guildwars2.com/wiki/Fury
[Relic of the Midnight King]: https://wiki.guildwars2.com/wiki/Relic_of_the_Midnight_King
[Relic of Speed]: https://wiki.guildwars2.com/wiki/Relic_of_Speed

[CC Deadeye]: https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oivMapCCLFc82gK0HUB-e