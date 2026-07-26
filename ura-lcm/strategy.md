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
- Most LCM strategies ignore [Titanspawn Geysers], drastically simplifying melee group mechanics.
- Two compositions are popular: [Solo CC] and [4-man].
- The fight is an extremely tight DPS check, requiring every player to pull their weight.
- An inordinate amount of CC is required throughout the fight to manage [Rising Pressure] and [Toxic Geysers].
- The ranged group will have to [double drop](../ura/strategy.html/#double-sharding-toxic-geysers) for the entire fight.
- [Tanking Ura](../ura/mechanics.html#tanking-ura), facing her in the right direction and timing CC correctly is essential to avoid her casting [Propel] and upkeep high DPS uptime.
- The final phase spawns multiple [Legendary Ventshots] that introduce extreme damage and CC pressure.

<img class=divider>

## Overview

Ura's overall mechanics and flow remain similar from CM to LCM. It is played pretty much [in the same way]((../ura/strategy.html#bloodstone-juggling-and-groups)), by dividing the squad into two groups, *melee* and *ranged*, with each group managing a single [Bloodstone Shard]. The main differences strategy-wise are:
- The *melee* group does not move to kill [Titanspawn Geysers].
- The *ranged* group will [double drop](../ura/strategy.html/#double-sharding-toxic-geysers) for the entire fight, with a rotation that depends on their composition.

---

#### Why not kill Titanspawners?

The primary reason is to take advantage of the cap on [Legendary Ventshots]. These are extremely dangerous enemies that start spawning from [Titanspawn Geysers] instead of [Champion Fumarollers] in the final phase. However, they can only spawn if there are less than 6 entities alive, including both [Champion Fumarollers] and [Titanspawn Geysers].

The aim is to have as many entities as possible when going into the final phase. By not killing any Titanspawners, you can have up to five of them up simultaneously, which when combined with the [Champion Fumarollers] surviving from the previous phase, will prevent any Ventshots from spawning at the start of the phase.

Towards the end of the fight, once all [Champion Fumarollers] are dead, you can still have one or two Ventshots spawning, but since these are few and appear late into the phase, they can simply be ignored with healing and <img class='inline stability'> [Stability]. This is much easier compared to the alternative, where you have to upkeep permanent projectile block throughout the phase.

This strategy has the added advantage of always keeping the melee group in a single stack. Management of the [Bloodstone Shard] is simplified due to not having to <img class='inline dispel'> [Dispel] Titanspawners, the group has higher DPS uptime on the boss and more DPS overall, and it is easier to provide support. Furthermore, a [tank](../ura/strategy.html#tanking-ura) is not strictly necessary as the entire group will stay within line-of-sight at all times.

The disadvantage of this strategy is the presence of multiple [Champion Fumarollers] on the group for most of the fight, which requires consistently high healing and <img class='inline stability'> [Stability] uptime and limits composition options.

---

#### Meeting the DPS check

Legendary Ura has an effective health of 123'451'556 HP and a maximum encounter duration of 11 minutes. This means that effectively, a group will need to average overall 187k average DPS to clear the encounter before enrage.

This number is greatly influenced by <img class='inline risingpressure'> [Rising Pressure]. Correct management of the damage reduction applied by this status will make or break a pull. Always keep an eye on the number of stacks on the boss: try to CC whenever she reaches 5 stacks. Ideally try to do so immediately after she gains a stack: this alone can increase your DPS by 3-4% easily, which is equivalent to 20-25 seconds on the enrage timer.

Players should have an up-to-date build (check the [builds section](#builds-and-povs) above and [Snowcrows](https://snowcrows.com/)), and should be competent with their class and rotation, practicing it if necessary on the [DPS golem](https://snowcrows.com/guides/arcdps/special-forces-area). Players should aim to do as much damage as possible while not failing mechanics.

To have an indicative understanding of how much DPS is necessary to clear the encounter, check the spreadsheet [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQRWHzmW9qli-mQ_MBS_uq65Bd64jy-djaDM7-Lt5sAcTqeuaOER3an1XNsS054DZeKg06ehE_Cf4_g/pubhtml).


<img class=divider>

## Composition

Legendary Ura is played primarily with two different composition types, differing based on how they manage CC:
- [Solo CC] compress most of the encounter's CC requirements onto one specialized build.
- [4-man] spreads out CC between the four supports.

The composition choice will greatly impact the strategy for the ranged group.

---

### Solo CC Compositions

These compositions use a single specialized role to CC all of the [Toxic Geysers] over the course of the fight. This frees up the rest of the squad to run anything in theory, as long as the basic requirements of healing, <img class='inline stability'> [Stability] and cleanse are met.

The most common solo-CC class is <img class='inline deadeye'> [Deadeye], due to its extreme mobility with <img class='inline shadowstep'> [Shadowstep] and <img class='inline deadeye-mark'> [Deadeye's Mark](https://wiki.guildwars2.com/wiki/Deadeye%27s_Mark), and its ability to constantly inflict <img class='inline daze'> [Daze] with <img class='inline distracting-throw'> [Distracting Throw] and regenerate initiative with <img class='inline m7'> [Maleficent Seven](https://wiki.guildwars2.com/wiki/Maleficent_Seven), <img class='inline' src='https://wiki.guildwars2.com/images/thumb/8/80/Malicious_Ashen_Assault.png/50px-Malicious_Ashen_Assault.png'> [Malicious Ashen Assault](https://wiki.guildwars2.com/wiki/Malicious_Ashen_Assault)  and <img class='inline' src='https://wiki.guildwars2.com/images/thumb/4/4d/Mercy.png/50px-Mercy.png'> [Mercy](https://wiki.guildwars2.com/wiki/Mercy). Other viable classes include <img class='inline' src='https://wiki.guildwars2.com/images/d/d1/Antiquary_icon_small.png'> [Antiquary](https://wiki.guildwars2.com/wiki/Antiquary), <img class='inline specter'> [Specter] and <img class='inline bladesworn'> [Bladesworn](https://wiki.guildwars2.com/wiki/Bladesworn): the only strict requirement is being able to burst out over 1000 CC every 12 seconds.

For defensive supports, <img class='inline troubadour'> [Troubadour] is the most common pick due to its great healing, <img class='inline stability'> [Stability] access and CC. Similarly for BoonDPS, <img class='inline evoker'> [Evoker](https://wiki.guildwars2.com/wiki/Evoker) (specifically played with the Toad familiar) is a common pick due to its great damage and <img class='inline stability'> [Stability] access.

Try to run DPS that can provide good amounts of <img class='inline stability'> [Stability]. <img class='inline willbender'> [Willbender] with <img class='inline stand-ground'> [Stand Your Ground!] is a common pick due to its high mobility, abundant cleanse, and its increased damage when cleaving thanks to <img class='inline perm-wrath'> [Permeating Wrath] and <img class='inline restore-virtues'> [Restorative Virtues]. Additionally:
- One DPS will have to participate in the ranged rotation and therefore benefits from additional mobility: this is often played by a <img class='inline mechanist'> [Mechanist] or <img class='inline scourge'> [Scourge].
- One or more DPS will play a high-toughness build, aiming to be highest in the group. This will make [Champion Fumarollers] target them and get cleaved down on top of the boss. 

#### Example Composition
{: .no_toc}
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
            <td><a href="#builds-and-povs"><img class='inline troubadour'>Heal Troubadour</a></td>
            <td>Ranged</td>
            <td></td>
            <td>3</td>
        </tr>
        <tr>
            <td class='phase1'>1</td>
            <td><a href="#builds-and-povs"><img class='inline evoker'></a>Toad Evoker</td>
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
            <td><a href="#builds-and-povs"><img class='inline chrono'> Heal Troubadour</a></td>
            <td>Ranged</td>
            <td></td>
            <td>1</td>
        </tr>
        <tr>
            <td class='phase2'>2</td>
            <td><a href="#builds-and-povs"><img class='inline evoker'></a>Toad Evoker</td>
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

---

### 4-man Compositions

These compositions tend to spread out CC requirements between all four support players, who together form the ranged group. This forces a stricter composition, as each support needs to be able to CC [Toxic Geysers], leading to the ubiquitous roster of heal <img class='inline troubadour'> [Troubadours] and celestial <img class='inline specter'> [Specters].

<img class='inline troubadour'> [Troubadour] provides incredible boon access, <img class='inline stability'> [Stability] uptime, CC, healing and general utility. 

Celestial <img class='inline specter'> [Specters] provide decent <img class='inline stability'> [Stability] and boons, excellent CC and mobility, and can also upkeep <img class='inline vuln'> [Vulnerability] and <img class='inline poison'> [Poison] (required for <img class='inline thorns-relic'> [Relic of Thorns]). They have two main loadouts, with one taking <img class='inline silence-well'> [Well of Silence](https://wiki.guildwars2.com/wiki/Well_of_Silence) and <img class=inline src='https://wiki.guildwars2.com/images/thumb/3/35/Superior_Rune_of_the_Trapper.png/60px-Superior_Rune_of_the_Trapper.png'> [Rune of the Trapper](https://wiki.guildwars2.com/wiki/Superior_Rune_of_the_Trapper) for more damage, and the other running <img class='inline bounty-well'> [Well of Bounty](https://wiki.guildwars2.com/wiki/Well_of_Bounty) and <img class=inline src='https://wiki.guildwars2.com/images/thumb/2/24/Superior_Rune_of_the_Mesmer.png/60px-Superior_Rune_of_the_Mesmer.png'> [Rune of the Mesmer](https://wiki.guildwars2.com/wiki/Superior_Rune_of_the_Mesmer) for more group support.


Try to run DPS that can provide good amounts of <img class='inline stability'> [Stability]. <img class='inline willbender'> [Willbender] with <img class='inline stand-ground'> [Stand Your Ground!] is a common pick due to its high mobility, abundant cleanse, and its increased damage when cleaving thanks to <img class='inline perm-wrath'> [Permeating Wrath] and <img class='inline restore-virtues'> [Restorative Virtues]. <img class='inline willbender'> [Willbender] players should run a mix of Trailblazer and Dire for additional survivability. This brings around 2.5k DPS loss in a golem situation, which can be made up with through the more aggressive gameplay this gear enables. Healers must ensure that they have less toughness than the DPS so that they are not targeted by [Champion Fumarollers] while doing mechanics.

Up to one DPS per subgroup can bring a different build that is not <img class='inline willbender'> [Willbender]; any more and <img class='inline stability'> [Stability] uptime may start to become an issue. These players will often bring whatever flavour of greedy DPS has the highest benchmark at the time.

#### Example Composition
{: .no_toc}

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
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline troubadour'> Heal Troubadour</a></td>
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
            <td>Greedy DPS</td>
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
            <td><a href="#willbender-strategy-builds-and-povs"><img class='inline troubadour'> Heal Troubadour</a></td>
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
            <td>Greedy DPS</td>
            <td>Melee</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

---

### Builds and PoVs

This is a small selection of builds and PoVs and is not regularly updated. You can find up-to-date information on <img class='inline vl-icon'> [Void Lounge](https://discord.com/invite/voidlounge).

#### Solo CC
{: .no_toc}

|Build|Role|PoV|Last updated|
| <img class='inline deadeye'> [CC Deadeye](https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oi/MaRF0zUwRfMUh+gKA-e) | Ranged Solo Toxics | TBA | July 2026 |
| <img class='inline bladesworn'> [CC Bladesworn](https://gw2skills.net/editor/?PKRAYlJwUZtsEGJeaX/xXA-DSRYKBhPGFcHnRLKgemAO6EBL0vZBVA-e) | Ranged Solo Toxics | [PoV](https://youtu.be/3aj-JoV9GJI) | July 2026 |
| <img class='inline troubadour'> [Heal Troubadour](https://gw2skills.net/editor/?PihEQiW2L7iNzsYj4RPlO1B-DSZYjRFoGGSwlRLJQ6FgvvGCSAsBwS7bWQFA-e) | Ranged, Heal | [PoV](https://www.youtube.com/watch?v=j9cDoQ8IcZY) | July 2026 |
| <img class='inline evoker'> [Toad Evoker](https://gw2skills.net/editor/?PGgEoEWWAjmdx0Y14o8YNVVKHAA-DSRYkRDWOszoDFQISAF+rIIhwG41ogPNQFA-e) | Melee, BoonDPS | [PoV](https://youtu.be/OuoCipdW4GQ) | July 2026 |

#### 4-man
{: .no_toc}

|Build|Role|PoV|Last updated|
|<img class='inline troubadour'> [Heal Troubadour](https://gw2skills.net/editor/?PigEQiW2LzidxkZj4RPlOVB-DSZYjRwKTN0GkoiIzsQaJESvqKJBc8ERQCl/WafzCqA-e) (<img class='inline call-response'> [Call and Response])|Healer & Toxics|[PoV](https://youtu.be/U-_TFEcLBb4)|April 2026|
|<img class='inline troubadour'> [Heal Troubadour](https://gw2skills.net/editor/?PihEQiWmB7iJzsYj4RPpOzB-DSZYjBlpGaDSUdkZWGtkCpXBOeiIIBwe4t0+mFUB-e) (<img class='inline altered-chord'> [Altered Chord])|Healer & Toxics|[PoV](https://youtu.be/X_BUGk2vzhw)|April 2026|
|<img class='inline specter'> [Celestial Specter (<img class=inline src='https://wiki.guildwars2.com/images/thumb/2/24/Superior_Rune_of_the_Mesmer.png/60px-Superior_Rune_of_the_Mesmer.png'> Mesmer)](https://gw2skills.net/editor/?PagEQjWGKjlly2Yn4Yb9H9B-DyIY1oivQapCiMBqMEc89QQCg9wbh+vKoC-e)|Toxics|[PoV](https://youtu.be/rUM8EZMYLrU)|April 2026|
|<img class='inline specter'> [Celestial Specter (<img class=inline src='https://wiki.guildwars2.com/images/thumb/3/35/Superior_Rune_of_the_Trapper.png/60px-Superior_Rune_of_the_Trapper.png'> Trapper)](https://gw2skills.net/editor/?PagEQjWGKjlty2Yn4Yb9H9B-DyIY1oi/QaRFEpEoShgCfPEkAYP8Wo/rCqA-e)|Toxics| |April 2026|
|<img class='inline willbender'> [DPS Willbender (PP/PT)](https://gw2skills.net/editor/?PWABoqp/lVw6YqMMWLW0WbxSA-DSRYcB1TG9cCFSlhQuJQHVgD/KCSQsHeNg4TDUB-e)| DPS |[PoV](https://www.youtube.com/watch?v=WJKHwUIudkA)|September 2025|

For more information on <img class='inline willbender'> [Willbender] gameplay in particular, check out Mastro's [P/P/T cWB Manifesto](https://discord.com/channels/380901000200060929/380903704808652801/1467802730658664500).

<img class='divider'>

## Strategy

### Shard Rotations

For the _melee rotation_, since the strategy ignores [Titanspawn Geysers], the only thing the melee group needs to <img class='inline dispel'> [Dispel] is [Pressure Blast]. For this reason, there are generally only 4 to 5 people assigned to the melee rotation, which otherwise works as normal. Groups can choose to forgo a rotation if they are confident.

The _ranged rotation_ depends on the composition used:

---

#### Solo CC

---

#### 4-man

The strategy uses a 4-man rotation involving all the support players double-dropping.

[<img class='inline sheets'> 4-man Rotation for Willbender Strat by Asterius](https://docs.google.com/spreadsheets/d/1gOhbFgtSnaW_8T1m12PgZe8lG7VH-P3IckXoPUPqNdA/edit?gid=969431177#gid=969431177){: .btn}

Responsibility for CCing [Toxic Geysers] is spread out between all of the ranged group members. Each support will CC two geysers every rotation:
- The geyser they pick up the [Bloodstone Shard] from.
- The first geyser they <img class='inline dispel'> [Dispel] when double dropping.

<img class='inline troubadour'> [Troubadours] running <img class='inline call-response'> [Call and Response] can CC toxics by doing the combination:
1. <img class='inline scarlet-tale'> [Tale of the Tortured Mastermind].
2. <img class='inline sharpshooter'> [Phantasmal Sharpshooter] or <img class='inline collapse'> [Mental Collapse] with <img class='inline clarity'> [Clarity].
3. <img class='inline moa'> [Signet of Humility] or <img class='inline deafening-drum'> [Deafening Drum] with three notes to trigger <img class='inline call-response'> [Call and Response].

Alternatively, if they are running <img class='inline altered-chord'> [Altered Chord] they can either:
- Use <img class='inline deafening-drum'> [Deafening Drum] in medium range to trigger the 2-second <img class='inline daze'> [Daze], and wait for 1-2 autos before casting it for the optimal timing (overlapping with the final pulse of <img class='inline scarlet-tale'> [Tale of the Tortured Mastermind]).
- Use <img class=inline src='https://wiki.guildwars2.com/images/thumb/d/dc/Flustering_Flute.png/50px-Flustering_Flute.png'> [Flustering Flute](https://wiki.guildwars2.com/wiki/Flustering_Flute) before <img class='inline deafening-drum'> [Deafening Drum] (at the cost of <img class='inline protection'> [Protection] uptime).
- Use an additional weapon skill after the normal sequence.

<img class='inline specter'> [Specters] can CC with <img class='inline distracting-throw'> [Distracting Throw], making sure to have enough initiative to do so. There is generally enough time between the two geysers for it to regenerate, but players who find themselves constantly short can run two spears and take advantage of <img class='inline quickpockets'> [Quick Pockets]. Crowd control from <img class='inline distracting-throw'> [Distracting Throw] requires that the target be movement-impaired. This can be done by casting <img class='inline siphon'> [Siphon](https://wiki.guildwars2.com/wiki/Siphon) or <img class='inline gloom-well'> [Well of Gloom](https://wiki.guildwars2.com/wiki/Well_of_Gloom) on the target.

If players cannot CC, they should call for backups. Since all four ranged players are double dropping, there is quite a bit of flexibility overall.

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
[Solo CC]: #solo-cc-compositions
[4-man]: #4-man-compositions

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
[Troubadour]: #willbender-strategy-builds-and-povs
[Troubadours]: #willbender-strategy-builds-and-povs

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
[Quick Pockets]: https://wiki.guildwars2.com/wiki/Quick_Pockets
[Altered Chord]: https://wiki.guildwars2.com/wiki/Altered_Chord
[Call and Response]: https://wiki.guildwars2.com/wiki/Call_and_Response
[Protection]: https://wiki.guildwars2.com/wiki/Protection
[Tale of the Tortured Mastermind]: https://wiki.guildwars2.com/wiki/Tale_of_the_Tortured_Mastermind
[Deafening Drum]: https://wiki.guildwars2.com/wiki/Deafening_Drum
[Daze]: https://wiki.guildwars2.com/wiki/Daze

[CC Deadeye]: https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oivMapCCLFc82gK0HUB-e