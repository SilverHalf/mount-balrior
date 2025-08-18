---
layout: page
title: CM Strategy
nav_order: 2
parent: Godscream Ura
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn } [Mechanical Reference](./mechanics.html){: .btn } [LCM Strategy Guide](./strategy-lcm.html){: .btn }

# Recommended Ura Strategy

Managing Ura requires high level coordination and often on-the-fly improvisation. At least in Challenge Mode, the fight is not a damage check (in fact it is quite forgiving from that point of view), but a mechanics check. Stay on top of things as they happen while keeping your squad alive, and you will cruise along until you kill. Fall behind on mechanics, and the pace will wear you down and make things much harder until you stabilize or wipe.

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

The most important concept underpinning this strategy is the way it manages [Bloodstone Shards]. Since there are two shards available, we divide them into a _ranged shard_ and a _melee shard_. These are assigned to two separate groups:
- A _ranged group_ containing the three healers. These three will share the _ranged shard_, using it to <img class='inline dispel'> [Dispel] all [Toxic Geysers] throughout the fight.
- A _melee group_ containing everyone else. This group will use the _melee shard_ to <img class='inline dispel'> [Dispel] the other mechanics in the fight: [Pressure Blast] (aka Friends, Bubbles) and [Titanspawn Geysers].

Establishing a rotation for the shard is extremely important. Whenever a player drops a shard, they should call out the next person in the rotation and the location where it is dropped, e.g. "Titanspawn", "Bubbles" or "\[Toxic\] number 5".

#### Marker Packs

Especially for the healers, it is extremely beneficial to install [HasKha's Markers](https://github.com/HasKha/gw2-markers) for [Blish HUD](https://blishhud.com/)'s [Pathing Module](https://blishhud.com/modules/?module=bh.community.pathing). This pack will show an overlay with numbered spawn positions for geysers, allowing players to easily keep track of mechanics and use numbers for callouts. The pack can be installed directly from the Pathing Module's marker repository.

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

The fight starts when both [Bloodstone Shards] are picked up. Usually one player from the melee group picks one up, then a player from the ranged group pick up the second one when everyone is in position to start the fight.

Throughout this phase the important mechanics are [Pressure Blast] and [Toxic Geysers].

The melee group can easily handle bubbles as long as no mistakes are made. Groups progressing this fight should use this phase to practice their rotation: melee players should always call out the next player in their rotation whenever they use a shard, and no shard should remain on the floor for more than a couple of seconds.

The ranged group will have a harder time of it, they will have to manage double the rate of [Toxic Geysers] in this phase compared to the rest of the fight. This requires "Double Sharding", a technique that involves using <img class='inline dispel'> [Dispel] on a geyser, then quickly picking up the [Bloodstone Shard], moving to a second geyser, and using <img class='inline dispel'> [Dispel] again. This requires surviving the ticking damage from <img class='inline saturation'> [Bloodstone Saturation], which deals 20% max HP damage per second.

To simplify double sharding, it is best to wait for both [Toxic Geysers] to spawn before using <img class='inline dispel'> [Dispel] on the first, so as to not have to wait between casts. Mobility skills are also extremely useful for quickly moving from one shard to the other.

Alternatively, groups can still "single shard", but that requires assigning one or more additional DPS or BoonDPS to the ranged group rotation for this phase, increasing overall complexity.

### Example Ranged Shard Rotation

|Player|Pick Up #|First Dispel|Second Dispel|
|Heal 1| - | 1 | 2 |
|Heal 2| 2 | 3 | 4 |
|Heal 3| 4 | 5 | 6 |
|Heal 1| 6 | 7 | 8 |
|...| | | |

<img class="center" width="100%" src="../images/ura/ura_toxic_geyser_spawns.webp" />

Healers will also have to break the geyser's <img class='inline defiance'> [Defiance Bar] to destroy them completely.

Throughout this phase, Ura will use [Propel] after every [Pressure Blast]. This will often target the members of the ranged group while they are doing their mechanics: as such they should try to bait this skill away from geysers into potentially advantageous positions. An example movement pattern is shown in the image below:

<img class="center" width="100%" src="../images/ura/ura_propel_p1.webp" />

After using [Propel], Ura will generally use her [Autoattack Chain], which requires <img class='inline aegis'> [Aegis] or <img class='inline stability'> [Stability] for the last hit. 

Ura should be CCd roughly whenever she gains 5 stacks of <img class='inline risingpressure'> [Rising Pressure]. This will help to keep the pace, while also not getting overwhelmed by the required CC amount in the later phases.

<img class=divider>

## 70% - 40%

Ura will begin this phase by casting [Return] and trapping everyone in bubbles. This must be <img class='inline dispel'> [Dispelled] by the player holding the melee shard. If Ura casted [Pressure Blast] just before this transition, this player should keep their shard and use it to save both the targeted players and the rest of the group.

Immediately after, Ura will cast [Create Titanspawn Geyser]. Whoever is next in the melee rotation should have picked up the shard, and the squad should move to the geyser's location to quickly <img class='inline dispel'> [Dispel] it (calling out the next player in the rotation to pick up!) and burst it down. After the geyser is dead, immediately return to stack at the boss, and try to cleave down the [Champion Fumaroller] on top of it. It can be beneficial to stack opposite Ura compared to the fumaroller, and to recall mechs and other pets so that it moves quickly to the squad. Future casts of [Create Titanspawn Geyser] should be handled in the same manner.

New in phase 2 are also [Sulfuric Geyser] casts, which will target a random player. Depending on where the player is standing, they will want to run out and drop them at different locations. Below is a map that shows shaded purple areas, which are good locations to drop Sulfurics at. The 5 circles near the boss and the associated arrows indicate the direction you should run out when standing on those sides of the boss.

<img class="center" width="100%" src="../images/ura/ura_sulfurics.webp" />

Players should try to avoid running out in the North-East direction as the Toxic Geysers 1 and 2 are so far out, that you cannot make the distance without movement skills. This can cause Sulfurics Geysers to drop at Toxic Geysers 1 or 2, making the ranged group's unnecessarily harder.

If you have movement skills, always use them to get away from the boss and don't save them to get back quickly, because getting further away and placing the geysers in safe spots is more important. <img class='inline chrono'> [Chronomancers] should try to provide returning players with a <img class='inline rifle-portal'> [Dimensional Aperture] (Rifle 5) to quickly bring them back to the stack.

The [Toxic Geyser] rotation in this phase will restart from #8. The ranged group will overall have an easier time managing geysers in this phase, since their cooldown will increase from 12 to 24 seconds, no longer requiring double sharding. Players should keep up calling where they use their shard so as to maintain the rotation.

Ura's [Steam Prison] should be placed far enough from the boss so that players can navigate around her without danger of going inside the arena. Furthermore, try and pay attention to not overlap it with any other mechanics, such as [Toxic Geysers]. For the most part, players can always turn around 180° degrees and run away from the boss immediately. Before arena becomes active, the position of it is already fixed. You can use this brief period to use a movement skill or <img class='inline superspeed'> [Superspeed] in order to get out of its area before it becomes active. This removes the need for <img class='inline stability'> [Stability], but requires precise timing. Try to practice this timing, as being stuck inside the arena in phase 3 and onwards can quickly become fatal.

<img class=divider>

## 40% - 1%

Once Ura hits 40%, she self-interrupts and will immediately cast [Pressure Blast]. This transition can be very hectic, especially if it occurs in proximity to [Create Titanspawn Geyser], as melee shard management becomes difficult. Calling it out in voice helps players prepare for the bubbles and not be caught off-guard.

For Bubbles, generally you want to place them right next to the stacking group. However, if it overlaps with a Titanspawn Geyser and you have a Bubble on the Titanspawn Geyser and one on the melee group on the boss, then try and meet in the middle if both Bubbles are far apart. Same when someone who is away doing Sulfuric Geyser, or Toxic Geysers. Both players who get the bubble should always look for the second one immediately, because breaking the Bubbles as soon as possible is important for the skill to go on cooldown, which in turn is relevant to minimize the chances of Ura using Propel in this phase (and phase 4). Another exception is when Champion Fumaroller are alive and close to the stack. In that case stack on the opposite side. For example if everyone is stacked on the boss and a Fumaroller is to the left-hand side of the stack, Bubbles should go to the right-hand side of the stack instead. This is because players caught in Bubbles can be knocked (by the Fumaroller) which will displace them and desync the player with the white indicator on the ground. If that happens, ignore the white indicator and drop the Bloodstone Shard under the displaced player.

The 40% transition also resets Toxic Geyser spawn patterns. Toxic Geyser 7 spawns immediately at 40% and the 12 seconds (LM), or 24 seconds (CM) timer resets. This means it can be hectic for the Heal Chronos and Toxic Geyser Shard droppers as well, so be prepared for the transition. The first few Toxic Geysers depend on the dps in phase 2 and if Toxic Geyser 3, 4, or 5, was the last to spawn. The following table shows the Toxic Geysers in phase 3:

| Toxic Geyser | Drop | Pickup |
| 7            | S1   | HC2    |
| 8            | HC2  | HC1 (late depending on phasing) |
| 9            | HC1  | S2 (late depending on phasing) |
| 10           | S2   | S2     |
| 11           | S2   | S1     |
| 12           | S1   | HC2    |
| 13           | HC2  | HC2    |
| 14           | HC2  | HC1    |
| 1            | HC1  | HC1    |
| 2            | HC1  | S2     |
| 3            | S2   | S2     |
| 4            | S2   | S1     |
| 5            | S1   | S1     |
| 6            | S1   | HC2    |
| 7            | HC2  | HC1    |

The small adaption you have to do comes when you phase before Toxic Geyser 4 spawns in phase 2. In this case S1 will already pick up from Toxic Geyser 3 and not 4, and will asap drop it on Toxic Geyser 7. Depending on how fast you phase, the Heal Chrono in sub 1 will still have 2x Bloodstone Saturation stacks and hence, cannot immediately pick up on Toxic Geyser 8. Hence, what you should do in this case is to immediately CC Toxic Geyser 8 (because it gives boons to the boss) and let HC2 drop the shard just before Toxic Geyser 8 regenerates its defiance bar. Then, HC1 pick it up as soon as the existing stacks run out. Note that this may still be a few seconds away, so be prepared to have the Bloodstone Shard tick once, or twice and heal your squad. Next, HC1 drops the shard on Toxic Geyser 9 and S2 needs to pick it up. Here it will be the same situation, where S2 will still have one Bloodstone Saturation stack. Do it the same way as before: CC Toxic Geyser 9, drop it toward the end of the regenerating defiance bar and S2 pick it up then as soon as the stacks drop. Be prepared to heal against one, or two Bloodstone Shard ticks.

Once Ura hits 1%, Ura will heal and become invulnerable for a short period of time.

<img class=divider>

## Healed - 0% (16% in CM, 41% in LM)

Immediately after the transition, there will always be an additional Titanspawn Geyser independent of the Create Titanspawn Geyser skill from Ura. Typically you focus this first Titanspawn Geyser and depending on the position also the second Titanspawn Geyser in both CM and LM and then ignore all other ones. If you do, or ignore the second one depends on the position of the stack and the Titanspawn Geyser. If it's a close one next to the boss, you can do it, but if it is one of the further away ones, you can ignore it.

Additionally in the last phase, Ura will inflict two players with Sulfuric Geysers per cast instead of only one. In order to use the space efficiently, it's best that both players drop the Sulfuric Geysers next to each other instead of in two different spots. But in particular for CM, since the fight will be over soon, this does not matter too much. It's more important for LM, where space is more limited.

The Toxic Geyser patterns simply continues from phase 3 into phase 4, so continue doing the first few Toxic Geysers as usual. In CM, because the fight will be over soon, only clear any Toxic Geysers that are close to the boss, but ignore the ones further away. For LM, you want to continue clearing all Toxic Geyser up until Toxic Geyser 14, but ignore the Toxic Geyser spawns from 1 onward. The following table shows those Toxic Geysers:

| Toxic Geyser | Drop | Pickup |
| 8            | HC1  | HC1    |
| 9            | HC1  | S2     |
| 10           | S2   | S2     |
| 11           | S2   | S1     |
| 12           | S1   | HC2    |
| 13           | HC2  | HC2    |
| 14           | HC2  | HC1    |

After Toxic Geyser 14, HC1 can use the Toxic Geyser for the Bubbles.

The following contains some further information for Legendary Mode for the last phase.

Projectile block for LM: Particularly important in the last phase for LM is that the Legendary Ventshots are dealing heavy damage from both melee and ranged attacks. Melee attacks can be baited away from the stack by having some pets standing between the stack and the Ventshots. So any Mechanist, or Ranger player in the squad, try and reposition your Pet such that it takes aggro from the Ventshots and tanks the melee hits. If multiple Ventshots melee attack the squad at the same time, it can wipe the entire squad in a second. That's why tanking them away with pets is crucial! Furthermore, the Ventshots continuously use ranged projectile attacks. These cannot be tanked which requires permanent projectile block around the squad, particularly once multiple Ventshots are alive. This needs to be reflected in the squad composition by having multiple sources of projectile reflect (for example, have a Vindicator with Ventari and Firebrand using F3-3/Sanctuary and a Scourge using Corrosive Poison Cloud). This also requires clear communication, so focus on keeping comms clear for correct projectile block callouts. One way to handle projectile blocks is e.g. to have the Ventari Vindicator dictate the timing. That is use Ventari bubble for ~10 seconds (and legend swap at the end), then have the Firebrand use F3-3, followed by the Scourge using CPC. The Ventari Vindicator swaps legend back to Ventari off cooldown and will have bubble up again after 10 seconds (legend swap cooldown). This means the Firebrand and Scourge (or any other projectile block you decide to have) needs to cover these periods of 10 seconds (or a little bit more to have some leeway; the combo written here provides 13 seconds) and have a cooldown of less than, or equal to 20 seconds (i.e. a full loop is ~10 seconds of Ventari and 10 seconds of the other projectile blocks). Ventari could in principle be kept up for longer, but we limit it to 10 seconds to line it up with CC timing (read the note below on CC timing).

CC timing and extra Rising Pressure stacks in LM: Ventshots have an ability that gives extra Rising Pressure stacks for 20 seconds to nearby Titans and Geysers. This cannot really be controlled in a good way, which means it just causes more stacks on Ura and thereby making Ura have higher damage reduction in this phase on average. But because there is not really a workaround to prevent this, it doesn't have an influence on the gameplay. You should plan out a specific CC timing and just follow that, while ignoring the extra Rising Pressure stacks. For example, in the PoV linked above, we CCd ever other time the Ventari Bubble ran out. The logic behind this is the following: Ventari bubble runs out => Ventari Vindicator swaps legend and uses Staff 5 for large CC. At the same time everyone else CCs as well. Because we want to CC every ~40 seconds roughly to keep the Rising Pressure stacks low enough on average, this therefore dictates the projectile block timing as well. With the composition used in the PoV, the CC was reliant on getting Staff 5 hits from the Ventari Vindicator (and Shiro Elite) and hence this needed to be timed with Legend swaps to have enough energy for the CC.

Positioning in LM: In LM the last phase will usually last 3 minutes or more and therefore the space toward the end will be limited because of expanding Toxic Geysers. Since we clear Toxic Geysers until 14, you want to position the squad in that South to South-West direction roughly. Note that the position needs to be dynamically adjusted based on Titanspawn Geyser spawnpoints, because you don't want to stand directly next to a Ventshot to mitigate melee attacks. Therefore, if you have a Titanspawn Geyser next to you, rotate the squad a little bit away and place a pet in between to tank melee aggro. If you anticipate Ura using Propel, you can bait the charge between Toxic Geyser 12 and 14, as long as there are no Sulfuric Geyser (drops from players, or from the naturally spawning ones) there and then rotate to stand toward the edge of the arena.

Further notes for LM:
- Melee attacks from Ventshots can CC players, therefore you want to upkeep Stability as much as possible. For the Heal Chronos this means using all charges of your Stab Mantra off cooldown and immediately start recharging it again once it's ready. The time between Stability running out and Mantra being recharged can be covered by Distort and by the other support using some Stability.
- Bubbles need to be placed next to the group, but because everyone also needs to stand inside the projectile block area, the space is quite limited. So be extra careful to not overlap any other players with Bubbles.
- Toward the very end of the fight, Toxic Geyser 8 might spawn and give boons to the boss. This should be CCd immediately via ranged CC and ideally also dropped. One way to do this is like so: a Scourge has the Bloodstone Shard and uses Sandswell Portal to Toxic Geyser 8, drops the shard and immediately takes the Portal back to the stack. One Heal Chrono can take the portal and immediately pick-up the shard. If available, you can use Distort to survive and bridge the gap until portal can be taken back. This sequence can be seen [here](https://youtu.be/HEz9N3Ivb_o?si=kpWERESLl0zuCUQn&t=810).

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
[Titanspawn Geyser]: mechanics.html#titanspawn-geyser
[Titanspawn Geysers]: mechanics.html#titanspawn-geyser
[Create Titanspawn Geyser]: mechanics.html#titanspawn-geyser
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