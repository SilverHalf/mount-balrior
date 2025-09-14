---
layout: page
title: LCM Strategy
nav_order: 1
parent: Legendary Ura
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn } [Frequently Asked Questions](./faq.html){: .btn }

# Legendary Ura Strategy Guide

Legendary Ura is an extreme challenge that requires near-perfect execution to be cleared.
Many concepts generally carry over from the [Normal Challenge Mode Strategy](../ura/strategy.html), so it is highly recommended to be familiar with Challenge Mode and with your chosen class before attempting to progress the Legendary Mode.

---

#### General Points
- The fight is an extremely tight DPS check, requiring every player to pull their weight.
- An inordinate amount of CC is required throughout the fight, requiring special builds and consideration.
- Usually groups will have a melee rotation to leave nothing to chance.
- The ranged group will have to [double drop](../ura/strategy.html/#double-sharding-toxic-geysers) for the entire fight. There are several ways of doing this depending on strategy and composition.
- [Tanking Ura](../ura/mechanics.html#tanking-ura), facing her in the right direction and timing CC correctly is essential to avoid her casting [Propel] and upkeep high DPS uptime.
- The final phase spawns multiple [Legendary Ventshots]. These are extremely dangerous, and must be dealt with.

---

#### Main Variations

There are two primary ways to approach Ura LCM:

- [Standard Strategy](#standard-strategy) - an extension of the normal CM strategy to LCM. Its main differences involve some composition changes, and the introduction of more elaborate ranged rotations to manage the fight's increased cadence.
- [Willbender Strategy](#willbender-strategy) - a mostly LCM-only strategy that takes advantage of some mechanical interactions to simplify the fight.

<img class=divider>

## Standard Strategy

This strategy plays out in a similar manner to normal Ura Challenge mode for the first three phases. Every point in the [Normal Challenge Mode Strategy Guide](../ura/strategy.html) is applicable here.

- For the _ranged group_ the main difference lies in [double sharding](../ura/strategy.html/#double-sharding-toxic-geysers), and everything that goes along with learning and executing a [ranged rotation](#ranged-rotation) properly.
- For the _melee group_, the differences lie in the fight's overall requirements: with such a tight DPS check, there is little to no room for mistakes.
- The _tank_ will have a fundamental role, as beyond [preventing propel](../ura/strategy.html#preventing-propel), they must often call CC for the rest of the group. Proper CC timings to minimize the uptime of <img class='inline risingpressure'> [Rising Pressure] can improve overall DPS by 5-10%, which is often the difference between killing or wiping to enrage.

---

#### Composition

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
            <td><a href="https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oivMapCCLFc82gK0HUB-e"><img class='inline deadeye'> CC Deadeye</a></td>
            <td>CC + Ranged</td>
            <td></td>
            <td>1</td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="https://gw2skills.net/editor/?PigEQiWmBzCrhNiH9karD-DSRYjR1VPSIFlRLpQ6VluvGCSo83S7bWQFA-e"><img class='inline chrono'> Heal Chronomancer</a></td>
            <td>Ranged</td>
            <td></td>
            <td>2</td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="https://gw2skills.net/editor/?PWyAo+rlRExe6ZQBttkGZkW0WbPTA-DSJYyRL/hkjkKBFQHCBF+r4IBxW41AiPNQFA-e"><img class='inline firebrand'> Quick Firebrand</a></td>
            <td>Melee + Titanspawner</td>
            <td>A</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="https://wiki.guildwars2.com/wiki/Power"><img class='inline power'> Power</a> DPS</td>
            <td>Melee + Titanspawner</td>
            <td>B</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="https://wiki.guildwars2.com/wiki/Power"><img class='inline power'> Power</a> DPS</td>
            <td>Melee + Titanspawner</td>
            <td>C</td>
            <td></td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td>Full/Hybrid Heal</td>
            <td>Ranged</td>
            <td></td>
            <td>3</td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="https://gw2skills.net/editor/?PWyAo+rlRExe6ZQBttkGZkW0WbPTA-DSJYyRL/hkjkKBFQHCBF+r4IBxW41AiPNQFA-e"><img class='inline firebrand'> Quick Firebrand</a></td>
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
            <td>Tank</td>
            <td></td>
            <td>Backup</td>
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

Standard LCM compositions keep the division between a _ranged group_ and a _melee group_ introduced in CM.

The ranged group is usually composed of:
- A heal <img class='inline chrono'> [Chronomancer] bringing extra CC.
- Either a second full healer (usually another <img class='inline chrono'> [Chronomancer]) or a hybrid celestial heal <img class='inline scourge'> [Scourge].
- A specialized <img class='inline deadeye'> [Deadeye] build that can upkeep constant CC.
- Occasionally, a DPS <img class='inline mechanist'> [Mechanist] running <img class='inline shift'> [Shift Signet].

<img class='inline deadeye'> [Deadeye] is almost ubiquitous due to its unique ability to constantly dish out massive CC, by spamming <img class='inline distracting-throw'> [Distracting Throw] and resetting their initiative with <img class='inline m7'> [Maleficent Seven](https://wiki.guildwars2.com/wiki/Maleficent_Seven). <img class='inline chrono'> [Chronomancer] is similarly almost always present due to its incredible boon access, <img class='inline stability'> [Stability] uptime, CC output, healing and general utility.

For boonDPS, the most common choice is <img class='inline firebrand'> [Firebrand], as beyond doing excellent damage they can provide abundant condition cleanse, <img class='inline stability'> [Stability] with <img class='inline stand-ground'> [Stand Your Ground!], and projectile reflection with <img class='inline wall-reflect'> [Wall of Reflection] and <img class='inline bulwark'> [Chapter 3: Valiant Bulwark]. Two <img class='inline firebrand'> [Firebrands] can upkeep 100% projectile reflection uptime if one of them is running <img class='inline wall-reflect'> [Wall of Reflection], though this is a little tight so often the healers will help out with either <img class='inline feedback'> [Feedback] on a <img class='inline chrono'> [Chronomancer], <img class='inline smoke-screen'> [Smoke Screen] on the <img class='inline deadeye'> [Deadeye], or <img class='inline cpc'> [Corrosive Poison Cloud] on a <img class='inline scourge'> [Scourge].

Usually running a couple of <img class='inline power'> [Power] damage dealers is extremely beneficial, as [Titanspawn Geysers] have less armor. These two players accompanied by a boonDPS can usually solo it within the 15 second respawn interval. Common choices here are classes with good burst damage and cleave, such as <img class='inline scrapper'> [Scrapper] or <img class='inline vindicator'> [Vindicator].

The tank players usually do not participate in the melee rotation, but all other DPS and boonDPS do.

#### Builds and PoVs

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

If anything is outdated, you can find up-to-date builds and PoVS on <img class='inline vl-icon'> [Void Lounge](https://discord.com/invite/voidlounge).

---

#### Melee Rotation

The melee group consists of five people, which should order themselves into a sequence before the fight starts. Following the rotation as closely as possible is the key to smooth reproducible runs and progression. _Always_ call out the next person in the rotation and mention where you are dropping your shard. For example:

> A: "B, dropping on Titanspawn"

The rotation cannot always be perfectly smooth due to overlapping mechanics. If a player cannot pick up because they are elsewhere, they should call out the next person. For example:

> A: "B, dropping on Titanspawn"

> B: "I'm doing sulfuric, C pickup"

A situation that often arises is when a player was not freed from [Pressure Blast] by <img class='inline dispel'> [Dispel] (for example they got clipped accidentally by a bubble). In this case the player who used the shard can quickly pick it up and use it again, or if the following player in the rotation picked up, they should immediately use and call out the next player.

In general, with five people following the rotation there is enough leeway to skip one player. Issues arise when players make multiple mistakes in succession, in which case it may be necessary to have a tank temporarily pick up a shard.

---

#### Ranged Rotation

Ranged players will generally be [double sharding](../ura/strategy.html/#double-sharding-toxic-geysers) for the entirety of the fight. Most groups will ask you to use an [overlay](../ura/strategy.html#marker-packs): callouts are usually done exclusively with geyser numbers.

Pain points often occur in the transitions at 70% and 40% of Ura's HP, where the rotation restarts from #8 and #7 respectively. There are several commonly used rotations, that all introduce some optimizations to alleviate these and reduce overall strain on the ranged players. Several of these are displayed below.

---

<img class='inline sheets'> [Heal-Only Rotation by Minas](https://docs.google.com/spreadsheets/d/18a4OXN5U8gqNg8eI7LLdyj6YZwHlVMm8bcH1rhdfXps)
{: .btn}

This rotation has only the healers and the <img class='inline deadeye'> [CC Deadeye] doing ranged shards. The advantage of this is that overall there will always be more damage players on the boss, leading to higher damage uptime.

This rotation also optimizes the order in which the geysers are <img class='inline dispel'> [Dispelled] to make double dropping a bit easier, and has other small optimizations to reduce strain on the healers.

The disadvantage of this rotation is that it requires overall higher DPS to be executed cleanly. This makes it common in experienced groups, but less accessible for progression purposes.

---

<img class='inline sheets'> [EU Pug Rotation by Luna](https://docs.google.com/spreadsheets/d/1IGCWOLWRkC8AlaJvVupbUTj5jzGbdBhzeBF7cd9MFV0)
{: .btn}

This is an adaptation of the [Healer Only](#healer-only-rotation) rotation that changes the order slightly and introduces a DPS player to aid with the 40% transition. For this reason, this strategy is slightly more forgiving overall while still offering optimized damage.

---

<img class='inline sheets'> [NA Pug Rotation by Narra](https://docs.google.com/spreadsheets/d/1slMSuj0KzgsFcr7aw0GdmeLDfnRK7tOdepiWoKbMSR4)
{: .btn}

This strategy includes a DPS player alongside the healers as part of the rotation. This is usually a <img class='inline mechanist'> [Mechanist] with <img class='inline shift'> [Shift Signet], or another specialization with similar mobility and damage.

The advantage of this rotation is that there is overall more leeway since there is one more person helping out. The disadvantage is slightly less outgoing damage overall since this DPS player will have to cover some mechanics, and less role compression, making LFG slightly more difficult.

---

#### Pain Points
In progression, most groups will struggle around the 70% and 40% transitions, and in the final phase.

- **70% transition:** here is where the first [Titanspawn Geyser] arrives. Ranged rotations also restart from #8, which takes some getting used to. This is also the first place to check your DPS: If #13 spawns, you do not have enough to kill within the enrage timer.
- **40% transition:**  [Toxic Geyser] #7 will spawn instantly, which requires extra management by the ranged group. Ura casts [Pressure Blast], which can overlap uncomfortably with any [Titanspawn Geysers] from the previous or following phase. Furthermore, since the transition interrupts Ura's current attack, she may use [Propel], which is often difficult to recover from, making for an overall hectic transition.
- **Final Phase:** the clock is ticking down, and you will have to manage immense incoming pressure from [Legendary Ventshots].

---

#### Preparing for the final phase
In the final phase, you want to minimize the number of [Legendary Ventshots] on the field at any time. Given that the total number of [Legendary Ventshots], [Champion Fumarollers] and [Titanspawn Geysers] in phase 4 cannot exceed six, it's often common to stop killing [Titanspawn Geysers] _before_ transitioning, so that they can fill up this cap. In general:

- If you are running a "safer" composition with two full healers, such as two heal <img class='inline chrono'> [Chronomancers], you can stop killing Titanspawners as soon as 15% HP in the main phase. Be warned though: this will spawn more [Champion Fumarollers], which in turn requires extra healing and <img class='inline stability'> [Stability].
- If you are running a more aggressive composition, typically with a single heal <img class='inline chrono'> [Chronomancer] and a hybrid <img class='inline scourge'> [Scourge], then it is more difficult to manage multiple Fumarollers on stack. For this reason, it is best to stop killing Titanspawners only on entering the final phase (optionally killing the first if it spawns in an extremely convenient position).

---

#### Surviving the final phase
You will want to be [facing Ura](../ura/strategy.html#tanking-ura) towards the North-West, in order to position the squad at the shortest possible difference from the safe drop zone for [Sulfuric Geysers], behind #9.

You will need to upkeep permanent projectile reflection to safeguard the group from the [Legendary Ventshots]' ranged attacks. One of the <img class='inline firebrand'> [Firebrands] will be running <img class='inline wall-reflect'> [Wall of Reflection], and should be calling out the skill rotation. This generally repeats:
1. The first <img class='inline firebrand'> [Firebrand] casting <img class='inline wall-reflect'> [Wall of Reflection].
2. The first <img class='inline firebrand'> [Firebrand] casting <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] when 10-11s are remaining on their cooldown for <img class='inline wall-reflect'> [Wall of Reflection].
3. A filler skill provided by another player, usually either a second <img class='inline firebrand'> [Firebrand]'s' <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] or a <img class='inline scourge'> [Scourge]'s <img class='inline cpc'> [Corrosive Poison Cloud]. When this ends, <img class='inline wall-reflect'> [Wall of Reflection] should be ready again.

Try to count down the time remaining on your reflect, and call for backup if your skills are not available. Remember that:
- <img class='inline wall-reflect'> [Wall of Reflection] lasts for 10 seconds (with <img class='inline master-consecrations'> [Master of Consecrations]).
- <img class='inline cpc'> [Corrosive Poison Cloud] lasts for 8 seconds.
- <img class='inline smoke-screen'> [Smoke Screen] lasts for 7 seconds.
- <img class='inline feedback'> [Feedback] lasts for 6 seconds.
- <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] lasts for 5 seconds.

It is also important to upkeep <img class='inline stability'> [Stability] on the group, to manage both Ura and the Ventshots' melee attacks. <img class='inline chrono'> [Chronomancers] running <img class='inline stab-mantra'> [Mantra of Concentration] and <img class='inline precog'> [Well of Precognition] can achieve this solo by using [this rotation](https://www.youtube.com/watch?v=ZNt3AbNwiuw) from Schwifty. Otherwise, they will have to coordinate with their <img class='inline firebrand'> [Firebrand].

---

#### How to meet the DPS check

Legendary Ura has an effective health of 137,161,289 HP and a maximum encounter duration of 11 minutes. This means that effectively, a group will need to average overall 208k total DPS to clear the encounter before enrage.

This number is greatly influenced by <img class='inline risingpressure'> [Rising Pressure]. Correct management of the damage reduction will make or break a pull. Always keep an eye on the number of stacks on the boss: try to CC when she reaches 5 stacks. In earlier phases, when she does not have much <img class='inline titanicresistance'> [Titanic Resistance], it can be hard to reach 5 before breaking: try then to CC at 3 or 4.

Always try to CC as soon as she gains a stack of <img class='inline risingpressure'> [Rising Pressure]. This can increase your DPS by 3-4% easily, which is equivalent to 20-25 seconds on the enrage timer.

Players should have an up-to-date build (check the [builds section](#builds-and-povs) above and [Snowcrows](https://snowcrows.com/)), and should be competent with their class and rotation, practicing it if necessary on the [DPS golem](https://snowcrows.com/guides/arcdps/special-forces-area). Players should aim to do as much damage as possible while not failing mechanics.

By averaging out a sample of kill logs in a time period (June to September 2025), we can find the average DPS numbers for squads that cleared.

|Role|Phase 1|Phase 2|Phase 3|Phase 4|
|:--|:--|:--|:--|:--|
|DPS|37.5k|32k|29.5k|28k|
|BoonDPS|29k|23.5k|22k|22k|
|Squad|260k|215k|198k|194K|

{: .note}
Individual damage should be higher for tank players, and can be lower for those assigned to mechanics, such as [Titanspawn Geysers] or ranged backup.

While this is just an average, and it is definitely possible to clear with less DPS than this, higher damage will result in an overall easier fight for everyone, as the group will overall have to play less mechanics and there is more leeway for mistakes. Players should generally try to aim for or surpass these numbers.

<img class=divider>

## Willbender Strategy

Developed by Asterius (see his original spreadsheet <img class='inline sheets'> [here](https://docs.google.com/spreadsheets/d/1gOhbFgtSnaW_8T1m12PgZe8lG7VH-P3IckXoPUPqNdA)), this is a variation on the standard that has significant differences in composition and strategy. These mainly come down to two major changes:

- The melee group does not kill [Titanspawn Geysers].
- Every DPS will play <img class='inline condition'> [Condition] <img class='inline willbender'> [Willbender].

---

#### Why not kill Titanspawners?

The primary reason is to take advantage of the cap on [Legendary Ventshots] in phase 4. [Legendary Ventshots] can only spawn if there are less than 6 entities alive, including [Champion Fumarollers] and [Titanspawn Geysers]. By not killing any Titanspawners, the aim is to have as many entities as possible when going into the final phase. This, combined with a couple of [Champion Fumarollers] surviving from the previous phase, will prevent Ventshots from spawning at the start of phase 4.

Once all [Champion Fumarollers] are dead, depending on where the Titanspawners generated, you can still have up to 1-2 [Legendary Ventshots], but since these are few and spawn late into phase 4, you don't need permanent projectile block. This makes the final phase much easier compared to the standard strategy, as a major difficulty factor is removed.

Furthermore, this has the added advantage of always keeping the melee group in a single stack. Management of the [Bloodstone Shard] is simplified due to not having to <img class='inline dispel'> [Dispel] Titanspawners, the group has higher DPS uptime on the boss and hence higher squad dps overall, and it is easier to rez people that go downstate. The only reason for DPS to leave the stack is to place [Sulfuric Geysers] and [Steam Prison].

---

#### Why Willbenders?

With many [Titanspawn Geysers] surviving throughout the fight, you will also get many [Champion Fumarollers] (up to 10 Titanspawners & Fumarollers combined). <img class='inline willbender'> [Willbender] shines in these circumstances, as beyond already being a strong build with high damage, mobility and cleanse, it also:

- Gains excellent access to <img class='inline stability'> [Stability] by running <img class='inline stand-ground'> [Stand Your Ground!] for a minimal DPS loss.
- Gains increased damage and cooldown reduction due to <img class='inline perm-wrath'> [Permeating Wrath] and <img class='inline restore-virtues'> [Restorative Virtues] striking multiple enemies for most of the fight, which in turn increases DPS on Ura as well.

At the same time though, you want to kill [Champion Fumarollers] as fast as possible in order to not get overwhelmed by them. They generally spawn fast enough to supply a constant stream of multi-target cleave.

---

#### Composition

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
            <td>CC + Ranged</td>
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
            <td>Melee</td>
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

This composition is much more rigid compared to the [standard strategy](#standard-strategy). <img class='inline chrono'> [Chronomancer] is almost always present due to its incredible boon access, <img class='inline stability'> [Stability] uptime, CC output, healing and general utility. Similarly, celestial <img class='inline specter'> [Specters] provide decent <img class='inline stability'> [Stability] and boons, excellent CC and mobility, and can also upkeep <img class='inline vulnerability'> [Vulnerability] (which would otherwise be lacking) and <img class='inline poison'> [Poison] (required for <img class='inline thorns'> [Relic of Thorns]).

All four supports are part of the ranged group. The abundance of [Champion Fumarollers] makes it harder for them to move around and do mechanics, so the <img class='inline chrono'> [Chronomancers] will usually run <img class='inline blink'> [Blink], and the <img class='inline specter'> [Specters] <img class='inline shadowstep'> [Shadowstep].

DPS players should run a mix of Trailblazer and Dire for additional survivability. This brings around 2.5k damage loss in a golem situation, which can be made up with through the more aggressive gameplay this gear enables. <img class='inline chrono'> [Chronomancers] should ensure they have less toughness than the DPS so that they are not targeted by [Champion Fumarollers] while doing mechanics. Generally a [tank](../ura/strategy.html#tanking-ura) is not strictly necessary as the entire group will stay within line-of-sight at all times.

---

#### Builds and PoVs

|Build|Role|PoV|Last updated|
|<img class='inline chrono'> [Heal Chronomancer](https://en.gw2skills.net/editor/?PigEQiWmBzidxQYj4RPp2+A-DSRYjR1DJ4CplUIoIo6CQ3XDBI09wbp9NLoC-e)|Healer & Toxics|[PoV](https://www.youtube.com/watch?v=LM7uye3SYWI)|September 2025|
|<img class='inline specter'> [Celestial Specter](https://en.gw2skills.net/editor/?PawEQbNqMUGLLltxOxx26O2D-DyIY1om/QaRB0lMIShgCfPEkAYP8Wo/SDqA-e)|Toxics|[PoV](https://www.youtube.com/watch?v=5LZMDgfcpg0)|September 2025|
|<img class='inline willbender'> [DPS Willbender (PP/PT)](https://gw2skills.net/editor/?PWABoqp/lVw6YqMMWLW0WXxSA-DSRYfB1bG9cCFSbhQuJQHVgD/KCSQsHeNg4sCUB-e)| DPS |[PoV](https://www.youtube.com/watch?v=rPfD2MvHZ2c)|September 2025|
|<img class='inline willbender'> [DPS Willbender (PP/ST)](https://gw2skills.net/editor/?PWABoqp/lVw6YqMMWLW0WXxSA-DSRYfB1bG9cCFSbhQuJQHVgD/KCSQsHeNg4sCUB-e)| DPS |[PoV](https://www.youtube.com/watch?v=gi8RSToi7hg)|September 2025|
|<img class='inline willbender'> [DPS Willbender (PP/PT, Toughness)](https://gw2skills.net/editor/?PWABoqp/lVw6YqMMWLW0WXxSA-DSRYcB1TG9cCFSlhQuJQHVgD/KCSQsHeNg4TDUB-e)| DPS ||September 2025|
|<img class='inline willbender'> [DPS Willbender (PP/ST, Toughness)](https://gw2skills.net/editor/?PWABoqt/lVw6YqMMWLW0WXxSA-DSRYcB1TG9cCFSlhQuJQHVgD/KCSQsHeNg4TDUB-e)| DPS ||September 2025|

If anything is outdated, you can find up-to-date builds and PoVS on <img class='inline vl-icon'> [Void Lounge](https://discord.com/invite/voidlounge).

---

#### Bloodstone Shard Rotations

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

If players cannot CC, they should call for backups. Since there is one more person in the rotation compared to a normal standard strategy, there is some flexibility.

#### How to meet the DPS check

Everything already said for the [standard strategy](#how-to-meet-the-dps-check) is still valid.

Willbender compositions will generally have a different damage profile, with less DPS overall in phase 1 and 4, but more in phase 2 and 3. By averaging out a sample of kill logs in a time period (June to September 2025, currently small sample size due to the strategy being relatively recent), we can find the average DPS numbers for squads that cleared.

|Role|Phase 1|Phase 2|Phase 3|Phase 4|
|:--|:--|:--|:--|:--|
|<img class='inline willbender'> DPS|32k|34.5k|33.5.5k|26.5k|
|<img class='inline specter'> BoonDPS|14k|11.5k|9k|9k|
|Squad|224k|235k|221k|180k|

While this is just an average, and it is definitely possible to clear with less DPS than this, higher DPS will result in an overall easier fight for everyone, as the group will overall have to play less mechanics and there is more leeway for mistakes. Players should generally try to aim for or surpass these numbers.


<img class=divider>

[Return to Home](../index.html){: .btn } [Return to Overview](overview.html){: .btn } [Return to Top](#recommended-legendary-ura-strategy){: .btn .fixed}
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

[CC Deadeye]: https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oivMapCCLFc82gK0HUB-e