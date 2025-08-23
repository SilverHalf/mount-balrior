---
layout: page
title: Strategy
nav_order: 2
parent: Godscream Ura
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn } [Mechanical Reference](./mechanics.html){: .btn }

# Recommended Ura Strategy

This strategy focuses on smoothing out communications regarding everything that has to do with [Bloodstone Shards] and <img class='inline dispel'> [Dispel], since this is often the hardest part of the encounter: making sure a shard is available, used, and then picked up as fast as possible every time it becomes necessary for a new mechanic.

This is achieved through a proper division of roles, where different parts of the squad circulate different shards to take care of specific threats, while also trying to provide good damage, boon uptime, and defensive utility.

## Composition

Ura CM is generally played with three healers, who must bring high amounts of crowd control to deal with [Toxic Geysers] and <img class='inline titanicresistance'> [Titanic Resistance]. Furthermore, they benefit from high survivability and mobility to facilitate mechanics, and <img class='inline stability'> [Stability] for their subgroups. For these reasons, the most commonly played specialization in this role is <img class='inline chrono'> [Chronomancer], followed by <img class='inline druid'> [Druid], <img class='inline scourge'> [Scourge] (often with a Celestial build), and <img class='inline specter'> [Specter].

[<img class='inline chrono'> Chronomancer Build](https://gw2skills.net/editor/?PigEQiWmBDhZxuYj4RPp26A-DSRYjR1VPSIFlRLpQ6VluvGCSo83S7bWQFA-e){: .btn} [<img class='inline scourge'> Scourge Build](https://en.gw2skills.net/editor/?PSAFw8laYZGMJ2DLiNip6V2rH-DSRYjRPV1HSI1ALkWigqLg0TBdvNEkQZP8aQwmFoC-e){: .btn} [<img class='inline druid'> Druid Build](https://gw2skills.net/editor/?POwEYKNssBmC7gxwKxxXSvpVi37B-DSRYjRwHCSUjuLjqrq0TBfvOEkQ5vl23sgKA-e){: .btn}
{: .center}

BoonDPS can bring additional utility to the fight, such as extra CC and <img class='inline stability'> [Stability], but this is not usually a limiting factor. Damage players can bring both <img class='inline power'> [Power] and <img class='inline condition'> [Condition] builds, though it is beneficial to bring a couple of <img class='inline power'> [Power] builds to handle [Titanspawn Geysers], since they have lower overall toughness. The fight also benefits builds with high cleave damage for both Titanspawners and [Champion Fumarollers], and extra mobility for easily placing [Sulfuric Geysers].

A typical combination might look like this:

|       | Heal              | DPS/Hybrid Support | DPS       | DPS       | DPS       |
| Sub 1 | <img class="inline chrono"> [Chrono] | DPS Support        | <img class='inline power'> [Power] | <img class='inline power'> [Power] | Any DPS  |
| Sub 2 | <img class="inline chrono"> [Chrono] | Hybrid/Full Heal   | Any DPS   | Any DPS   | Any DPS   |

## Shard Division

The most important concept underpinning this strategy is the way it manages [Bloodstone Shards]. Since there are two shards available, we call on the _ranged shard_ and the other _melee shard_. These are managed by two separate groups:
- A _ranged group_ containing the three healers. These three will share the _ranged shard_, using it to <img class='inline dispel'> [Dispel] all [Toxic Geysers] throughout the fight.
- A _melee group_ containing everyone else. This group will use the _melee shard_ to <img class='inline dispel'> [Dispel] the other mechanics in the fight: [Pressure Blast] (aka Friends, Bubbles) and [Titanspawn Geysers].

Establishing a rotation for the shard is extremely important. Whenever a player drops a shard, they should call out the next person in the rotation and the location where it is dropped, e.g. "Titanspawn", "Bubbles" or "\[Toxic\] number 5".

#### Marker Packs

Especially for the healers, it is extremely beneficial to install [HasKha's Markers](https://github.com/HasKha/gw2-markers) for [Blish HUD](https://blishhud.com/)'s [Pathing Module](https://blishhud.com/modules/?module=bh.community.pathing). This pack will show an overlay for geysers, allowing players to easily use numbered spawn positions as shown [here](/mechanics.html#toxic-geysers) for callouts. The pack can be installed directly from the Pathing Module's marker repository.

Alternatively, groups can use in-game markers. This is an inferior option compared to the overlay, since there are 14 spawn locations for [Toxic Geysers] and only 8 different markers available. The following marker pack (requires Blish HUD's [Commander Markers](https://blishhud.com/modules/?module=Manlaan.CommanderMarkers) module) makes the certain optimizations to manage this issue:

- Markers on geysers number 5, 8, 9, and 12.
- Markers between toxic geysers that are usually double dropped: 1 & 2, 3 & 4, 7 & 10, 13 & 14.
- No marker on 11 because it's in the boss anyways, so it's an easy one to remember, especially when you have the marker on 8 as reference point.

<details>
<summary>Click to view markers</summary>
<contents>
<div>Paste the following code into Commander Markers to use this marker pack:</div>
<code class="wrap">
eyJlbmFibGVkIjp0cnVlLCJuYW1lIjoiVXJhIENNL0xNIiwiZGVzY3JpcHRpb24iOiJUaGVzZSBtYXJrZXJzIHNob3cgdGhlIG1vc3QgaW1wb3J0YW50IFRveGljIEdleXNlcnMgYW5kIGFyZSBhbHNvIHVzZWZ1bCBmb3IgZ2VuZXJhbCBkaXJlY3Rpb24uIiwibWFwSWQiOjE1NjQsInRyaWdnZXIiOnsieCI6MTU3LjI0Njc1LCJ5IjoyMzkuOTE4MTgyLCJ6IjoyNjkuOTI4OTI1fSwibWFya2VycyI6W3siaSI6MSwiZCI6IlRveGljIEdleXNlciAxLzIiLCJ4IjoxODguOTI1NzIsInkiOjI2MS42MDE2ODUsInoiOjI2OS45MjkxNjl9LHsiaSI6MiwiZCI6IlRveGljIEdleXNlciAzLzQiLCJ4IjoxODguMDQ5OTQyLCJ5IjoyMjYuMTQwMDMsInoiOjI2OS45Mjg5MjV9LHsiaSI6MywiZCI6IlRveGljIEdleXNlciA4IiwieCI6MTYyLjA0NjYzMSwieSI6MjI4LjI3MTc0NCwieiI6MjY5Ljk5MDg3NX0seyJpIjo0LCJkIjoiVG94aWMgR2V5c2VyIDEzLzE0IiwieCI6MTI0LjM0Njc5NCwieSI6MjA5Ljg0OTY0LCJ6IjoyNjkuOTg2NDJ9LHsiaSI6NiwiZCI6IlRveGljIEdleXNlciA5IiwieCI6MTQ1LjgzMTc3MiwieSI6MjU4LjQ0MDgyNiwieiI6MjY5LjkzNDc4NH0seyJpIjo1LCJkIjoiVG94aWMgR2V5c2VyIDcvMTAiLCJ4IjoxNzAuOTA3MzY0LCJ5IjoyMDIuNDc5NTUzLCJ6IjoyNzAuMDYyOTU4fSx7ImkiOjcsImQiOiJUb3hpYyBHZXlzZXIgNSIsIngiOjE2NS43MjUyMzUsInkiOjI1Mi41NTQ5NjIsInoiOjI2OS45MzQ3ODR9LHsiaSI6OCwiZCI6IlRveGljIEdleXNlciAxMiIsIngiOjEyMi40NDU4MTYsInkiOjI0OS43ODIxMiwieiI6MjY5LjkyODkyNX1dfQ==
</code>
</contents>
</details>

<img class=divider>

## 100% - 70%

The fight starts when both [Bloodstone Shards] are picked up. Usually a player from the melee group picks up the first one, then a player from the ranged group pick up the second one when everyone is in position to start the fight.

Throughout this phase <img class='inline dispel'> [Dispel] must be used to manage [Pressure Blast] (aka Bubbles) and [Toxic Geysers].

The two players targeted by [Pressure Blast] should stack together separate from the rest of the group (possibly in melee range of the boss so as to upkeep DPS), so that the melee shard holder can save both of them with a single <img class='inline dispel'> [Dispel]. The shard holder will not be affected by [Pressure Blast], so they can stack on top of their affected teammates. They should also always call out the next person in the rotation after using their shard, which should quickly be picked up. Since there is little other pressure for the melee players in this phase, groups progressing the fight should use it to practice their rotation and get it perfect for the following phases.

The ranged group will have a harder time of it, they will have to manage double the rate of [Toxic Geysers] in this phase compared to the rest of the fight. This requires "Double Sharding", a technique that involves using <img class='inline dispel'> [Dispel] on a geyser, then quickly picking up the [Bloodstone Shard], moving to a second geyser, and using <img class='inline dispel'> [Dispel] again. This requires surviving the ticking damage from <img class='inline saturation'> [Bloodstone Saturation], which deals 20% max HP damage per second.

To simplify double sharding, it is best to wait for both [Toxic Geysers] to spawn before using <img class='inline dispel'> [Dispel] on the first, so as to not have to wait between casts. Mobility skills are also extremely useful for quickly moving from one shard to the other.

Alternatively, groups can still "single shard", but that requires assigning one or more additional players to the ranged group rotation for this phase, increasing overall complexity.

### Example Ranged Shard Rotation

|Player|Pick Up #|First Dispel|Second Dispel|
|Heal 1| - | 1 | 2 |
|Heal 2| 2 | 3 | 4 |
|Heal 3| 4 | 5 | 6 |
|Heal 1| 6 | 7 | 8 |
|...   |...|...|...|

<img class="center" width="100%" src="../images/ura/ura_toxic_geyser_spawns.webp" />

Healers will also have to break the geyser's <img class='inline defiance'> [Defiance Bar] to destroy them completely. 

Throughout this phase, Ura will use [Propel] after every [Pressure Blast]. This will often target the members of the ranged group while they are doing their mechanics: as such they should try to bait this skill away from geysers into potentially advantageous positions. An example movement pattern is shown in the image below:

<img class="center" width="100%" src="../images/ura/ura_propel_p1.webp" />

After using [Propel], Ura will generally use her [Autoattack Chain], which requires <img class='inline aegis'> [Aegis] or <img class='inline stability'> [Stability] for the last hit. 

Ura should be CCd roughly whenever she gains 5 stacks of <img class='inline risingpressure'> [Rising Pressure]. This will help to keep the pace, while also not getting overwhelmed by the required CC amount in the later phases.

<img class=divider>

## 70% - 40%

Ura will begin this phase by casting [Return] and trapping everyone in bubbles. This must be <img class='inline dispel'> [Dispelled] by the player holding the melee shard. If Ura casted [Pressure Blast] just before this transition, this player should keep their shard and use it to save both the targeted players and the rest of the group.

Immediately after, Ura will cast [Create Titanspawn Geyser]. Whoever is next in the melee rotation should have picked up the shard, and the squad should move to the geyser's location to quickly <img class='inline dispel'> [Dispel] it (calling out the next player in the rotation to pick up!) and burst it down. After the geyser is dead, immediately return to stack at the boss, and try to kill the [Champion Fumaroller] on top of it. Since the add targets player and allies, it is beneficial to stack opposite Ura compared to it and recall pets so that it quickly moves on top of the boss to be cleaved. Future casts of [Create Titanspawn Geyser] should be handled in the same manner.

Ideally the titanspawner should be killed within 15 seconds, so that it doesn't spawn a second [Champion Fumaroller]. Since these adds inflict large amounts of crowd control and damage, having multiple can quickly snowball the fight out of control.

New in phase 2 are also [Sulfuric Geyser] casts, which will target a random player. Depending on where the player is standing, they will want to run out and drop them at different locations. Below is a map that shows shaded purple areas, which are good locations to drop Sulfurics at. The 5 circles near the boss and the associated arrows indicate the direction you should run out when standing on those sides of the boss. Alternatively, [HasKha's Marker Pack](#marker-packs) also has indicators for safe sulfuric drop zones which are extremely useful.

<img class="center" width="100%" src="../images/ura/ura_sulfurics.webp" />

Players should try to avoid running out in the North-East direction as the Toxic Geysers 1 and 2 are so far out, that you cannot make the distance without movement skills. This can cause Sulfurics Geysers to drop at Toxic Geysers 1 or 2, making the ranged group's unnecessarily harder.

If you have movement skills, always use them to get away from the boss and don't save them to get back quickly, because getting further away and placing the geysers in safe spots is more important. <img class='inline chrono'> [Chronomancers] should try to provide returning players with a <img class='inline rifle-portal'> [Dimensional Aperture] (Rifle 5) to quickly bring them back to the stack.

It can happen that [Pressure Blast] overlaps with [Create Titanspawn Geyser] or [Sulfuric Geyser] cast and you have a bubble on the geyser and one on the boss: in this case try and meet in the middle. Each player who gets targeted should always look for the second one immediately and move to a convenient position.

The [Toxic Geyser] rotation in this phase will restart from #8. The ranged group will overall have an easier time managing geysers in this phase, since their cooldown will increase from 12 to 24 seconds, no longer requiring double sharding. Players should keep up calling where they use their shard so as to maintain the rotation.

Ura's [Steam Prison] should be placed far enough from the boss so that players can navigate around her without danger of going inside the arena. Furthermore, try and pay attention to not overlap it with any other mechanics, such as [Toxic Geysers]. For the most part, players can always turn around 180° degrees and run away from the boss immediately. Before arena becomes active, the position of it is already fixed. You can use this brief period to use a movement skill or <img class='inline superspeed'> [Superspeed] in order to get out of its area before becoming trapped. This removes the need for <img class='inline stability'> [Stability], but requires precise timing. Try to practice this, as being stuck inside the arena in phase 3 and onwards can quickly become fatal.

<img class=divider>

## 40% - 1%

Once Ura hits 40%, she self-interrupts and will immediately cast [Pressure Blast]. This transition can be very hectic, especially if it occurs in proximity to [Create Titanspawn Geyser], as melee shard management becomes difficult. Calling it out in voice helps players prepare for the bubbles and not be caught off-guard. The transition also resets [Toxic Geyser] spawn patterns: #7 will spawn immediately and the timer will be reset. This means the ranged group may have to handle two geysers in rapid succession.

Starting from this phase, Ura has access to all mechanics from the two previous phases. This means that while the ranged group will continue using their <img class='inline dispel'> [Dispel] only on [Toxic Geysers], the melee group will have to handle both [Pressure Blast] and [Create Titanspawn Geyser] for the rest of the fight. In particular, managing the bubbles as soon as possible is important to make the skill to go on cooldown, which in turn is relevant to minimize the chances of Ura using [Propel] in this phase and the following.

<img class=divider>

## Healed - 0%

On reaching 1% health, Ura will become <img class='inline invuln'> [Invulnerable], clear all <img class="inline condition"> [Conditions] from herself, and heal by 15% of her maximum HP.

Immediately after the transition, there will always be an additional [Titanspawn Geyser] independent of the [Create Titanspawn Geyser] skill. Groups in this phase may decide to kill only this titanspawner and additionally 1-2 others, while ignoring the rest, based on their distance from the boss. In case multiple [Champion Fumarollers] come to the stack, it's important to provide additional <img class='inline stability'> [Stability] and move off of any damaging AoEs so that they do not destabilize the squad.

Additionally, Ura will start targeting two players with [Sulfuric Geysers] instead of only one per cast. It's best to drop the Sulfuric Geysers next to each other instead of in two different spots in order to use the space efficiently and depending on how close the squad is to killing.

The [Toxic Geyser] patterns simply continues from the previous phase without interruptions. The ranged group can continue doing the first few as usual, with the added option of ignoring geysers far from the boss as the group gets closer to a kill and they become less relevant.

<img class=divider>

[Return to Home](../index.html){: .btn } [Return to Overview](overview.html){: .btn } [Return to Top](#recommended-ura-strategy){: .btn .fixed}
{: .center}

[Bloodstone Shard]: mechanics.html#bloodstone-shards
[Bloodstone Shards]: mechanics.html#bloodstone-shards
[Toxic Geyser]: mechanics.html#toxic-geysers
[Toxic Geysers]: mechanics.html#toxic-geysers
[Sulfuric Geyser]: mechanics.html#sulfuric-geysers
[Sulfuric Geysers]: mechanics.html#sulfuric-geysers
[Dispel]: mechanics.html#-dispel
[Dispelled]: mechanics.html#-dispel
[Titanspawn Geyser]: mechanics.html#titanspawn-geysers
[Titanspawn Geysers]: mechanics.html#titanspawn-geysers
[Create Titanspawn Geyser]: mechanics.html#titanspawn-geysers
[Pressure Blast]: mechanics.html#pressure-blast
[Pressure Blasts]: mechanics.html#pressure-blast
[Titanic Resistance]: mechanics.html#-titanic-resistance
[Champion Fumaroller]: mechanics.html#champion-fumaroller
[Champion Fumarollers]: mechanics.html#champion-fumaroller
[Bloodstone Saturation]: mechanics.html#-bloodstone-saturation
[Propel]: mechanics.html#propel
[Autoattack Chain]: mechanics.html#autoattack-chain
[Rising Pressure]: mechanics.html#-rising-pressure
[Steam Prison]: mechanics.html#steam-prison
[Return]: mechanics.html#return

[Chrono]: https://wiki.guildwars2.com/wiki/Chronomancer
[Chronomancer]: https://wiki.guildwars2.com/wiki/Chronomancer
[Chronomancers]: https://wiki.guildwars2.com/wiki/Chronomancer
[Druid]: https://wiki.guildwars2.com/wiki/Druid
[Specter]: https://wiki.guildwars2.com/wiki/Specter
[Scourge]: https://wiki.guildwars2.com/wiki/Scourge
[Power]: https://wiki.guildwars2.com/wiki/Power
[Condition]: https://wiki.guildwars2.com/wiki/Condition_damage
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar
[Aegis]: https://wiki.guildwars2.com/wiki/Aegis
[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Dimensional Aperture]: https://wiki.guildwars2.com/wiki/Dimensional_Aperture
[Superspeed]: https://wiki.guildwars2.com/wiki/Superspeed