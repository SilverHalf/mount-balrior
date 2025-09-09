---
layout: page
title: Mechanics
nav_order: 1
parent: Godscream Ura
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn } [Strategy Guide](./strategy.html){: .btn }

# Ura Mechanical Reference
{: .no_toc}

This section contains a detailed reference of the various attacks and mechanics present in the encounter. 

The rest of this page is structured into the following sections:
1. [**Overview**](#overview) - basic description of the fight and its main points.
2. [**Phases**](#phases) - a description of the structure of the fight, with transitions and differences between phases.
3. [**Mechanics**](#list-of-mechanics) - a reference of every attack in the encounter.
4. [**Effects**](#list-of-effects) - a reference of all effects unique to the encounter.

<img class=divider>

## Overview

The fight against Ura is split into 4 different phases, each characterized by a different set of mechanics. The phase transitions are based on Ura's health pool, occurring at 70%, 40%, and 1% of her maximum health. At the beginning of the final phase, Ura heals back to 16% HP (31% in Legendary Mode).

Managing Ura's mechanics requires lots of breakbar damage, cleave damage, mobility and support in the form of <img class="inline condition"> [Condition] cleanse and <img class="inline stability"> [Stability].

---

### Bloodstone Juggling
{: .no_toc}
One of the defining characteristics of Ura CM are the mechanics revolving around Bloodstone shards. These are interactable objects that can be picked up by players, and are of fundamental importance for clearing the encounter, as they allow players to negate mechanics and damage enemies that they normally wouldn't be able to.

Two shards spawn at the beginning of the encounter, and a player using a shard generally cannot pick up a new one for a certain amount of time. This means that, in order to cover all mechanics, it is necessary to rotate the shards throughout the entire squad: getting the hang of this "juggling" and performing it smoothly is the key to clearing the encounter, and is also the main reason why voice communications are so highly recommended.

More information on this mechanic can be found [here](#bloodstone-shard).

---

### Geysers and Arena Management
{: .no_toc}
An important facet of the Ura encounter is area denial. Throughout the fight, the boss will summon Geysers, stationary structures that affect an area, buffing the boss and harming the squad in some manner.
Learning to kill or otherwise handle these quickly and efficiently is of fundamental importance, as the eventual lack of space and additional damage pressure they inflict can quickly escalate.

More information on geysers can be found [here](#geysers).

---

### Defiance Management
{: .no_toc}
Throughout the fight, Ura will periodically gain stacks of <img class="inline risingpressure"> [Rising Pressure]. These increase her outgoing damage while reducing all incoming damage, and are thus not desirable.

Breaking Ura's <img class='inline defiance'> [Defiance Bar] resets the number of stacks to zero. However, this has the downside of granting Ura <img class="inline titanicresistance"> [Titanic Resistance], a permanent stacking buff which reduces incoming defiance damage and makes breaking successive bars more difficult. Managing outgoing crowd control therefore is very important and requires decent coordination to only break the bar at specific intervals.

In Legendary Mode, Ura regenerates 150 defiance every second, so the pressure becomes even greater.

---

### Table of Mechanics
{: .no_toc}
A brief description of the primary attacks performed by Ura during the encounter. Click on a mechanic to view additional information.

| **Attack**      | **Common Name** | **Target**        | **Cooldown [s]** | **Brief Description** |
| [Scalding Aura] | -               | Hitbox | -                | Pulses damage and <img class="inline burning"> [Burning]. |
| [Autoattack Chain] | - | Tank | - | A series of 3 attacks, dealing damage and applying <img class="inline vuln"> [Vulnerability]. The third and final attack also inflicts <img class="inline knockdown"> [Knockdown]. |
| [Acid Spray]    | -               | Enemies in front of Ura | 1.5 | Used when the target is not in melee range. Applies <img class="inline sulfuricacid"> [Sulfuric Acid]. |
| [Pressure Blast] | Bubbles, Friends  | Two random players  | ?                 | Traps two random players inside bubbles. These must be freed using <img class="inline dispel"> [Dispel]. |
| [Propel]        | Charge, Jump, Leap | Furthest player within 1500 range | 12 | Ura jumps a fixed distance, dealing heavy damage when she lands. |
| [Return]       | Toilet, Whirlpool | - | - | Swirls players around Ura and then teleports everyone and herself to a fixed location. |
| [Steam Prison]  | Arena, Cage | Random | ~20 | Spawns a cage around a player that reflects projectiles. |
| [Create Titanspawn Geyser]  |  Titanspawn | - | ~30 | <img class="inline knockdown"> [Knockdown] in an AoE, then spawns a [Titanspawn Geyser]. |

<img class=divider>

## Phases
Ura's encounter can be divided into four distinct parts, which are described below.

### 100% - 70%

The fight starts when both [Bloodstone Shards] are picked up by the players. Ura will spawn in the center of the arena and will start using the following skills (generally in this order):
- [Pressure Blast]
- [Propel]
- [Autoattack Chain]
- [Acid Spray] (only if her target isn't in melee range)

Additionally, [Toxic Geysers] will start spawning every 12 seconds.

Once Ura hits 70% health, she will interrupt whatever skill she is casting, lock her breakbar and use [Return]. Note that if she interrupts herself while at the very beginning of a [Propel] cast, then she may not cast [Return]. Depending on her position, this can be catastrophic, as she will not move in the next phase.

---

### 70% - 40%

Assuming a successful [Return], the second phase starts after everyone has been transported to Ura's new starting location. The [Toxic Geyser] timer continues from the previous phase, however, the next spawn point changes to 8 (see the image [here](#toxic-geysers)) and will continue from there (9, 10, ...) in phase 2. The time interval between [Toxic Geyser] spawns changes to 24s in Challenge Mode, but stays at 12s in Legendary Mode.

Ura herself is stationary in phase 2 and will not not cast [Propel] or [Pressure Blast]. Instead, she will gain the following abilities:
- [Create Titanspawn Geyser]
- [Sulfuric Geyser]
- [Steam Prison]

This phase continues until Ura reaches 40% of her maximum HP. 

---

### 40% - 1%

The third phase always starts with Ura self-interrupting and casting [Pressure Blast]. In this phase, Ura will be able to cast all of the skills she obtained in the previous two phases. Furthermore, the [Toxic Geyser] timing immediately resets and a [Toxic Geyser] spawns at 7 and continues from there.

This phase continues until Ura hits 1% of her maximum HP.

---

### Post-Heal - 0%

When Ura reaches 1% health, she becomes <img class='inline invuln'> [Invulnerable], clears all <img class="inline condition"> [Conditions] from herself, and heals by 15% of her maximum HP (30% in Legendary Mode).

Ura's skill-set remains the same as in phase 3. The [Toxic Geyser] pattern continues from phase 3 without any timer or location resets. The only change in Ura's attacks is that [Sulfuric Geyser] now targets two players at once, instead of only one.

> Note: Ura will self-interrupt herself at 40% in phase 4 again due to the self-interrupt that happens from the transition of phase 2 into phase 3. This is an unfortunate bug that can lead to animations being cancelled and Ura incorrectly using Propel.

At the start of this phase, a [Titanspawn Geyser] will always spawn. Furthermore, in Legendary Mode all [Titanspawn Geysers] will start spawning [Legendary Ventshots] instead of [Champion Fumarollers] during this phase.

<img class=divider>

## List of Mechanics

This section contains a full, in-depth explanation of all mechanics in the encounter.

Ura has a priority rotation, and the skills she has available depend on the phase, but they'll always follow a certain priority:

|**Priority**|**Skill**                 |**100% - 70%**     |**70% - 40%**      |**40% - 1%**       |**Heal - 0%**      |
|1           |[Pressure Blast]          |<img class="check">|                   |<img class="check">|<img class="check">|
|2           |[Create Titanspawn Geyser]|                   |<img class="check">|<img class="check">|<img class="check">|
|3           |[Sulfuric Geyser]         |                   |<img class="check">|<img class="check">|<img class="check">|
|4           |[Steam Prison]            |                   |<img class="check">|<img class="check">|<img class="check">|
|5           |[Propel]                  |<img class="check">|                   |<img class="check">|<img class="check">|
|6           |[Autoattack Chain]        |<img class="check">|                   |<img class="check">|<img class="check">|
|7           |[Acid Spray]              |<img class="check">|<img class="check">|<img class="check">|<img class="check">|

Ura cannot target <img class='inline stealth'> [Stealthed] players with skills.

---

### Bloodstone Shard
{: .no_toc}
Bloodstone Shards are red crystalline items that appear on the floor of Ura's arena. Players can interact with one to pick it up, with the following effects as long as they are holding it:
- They gain a red icon above their head.
- They gain <img class='inline deterrence'> [Deterrence], making them immune to some of Ura's mechanics.
- They can use the special skill <img class='inline dispel'> [Dispel].
- If they are affected by <img class='inline saturation'> [Bloodstone Saturation], they will start taking damage equal to 20% of their maximum health every second for each stack of the effect.

Two shards spawn in the center of the arena; picking up both starts the encounter.

![Bloodstone Shard](https://wiki.guildwars2.com/images/thumb/0/0f/Bloodstone_Shard_%28Mount_Balrior%29.jpg/360px-Bloodstone_Shard_%28Mount_Balrior%29.jpg)
{: .center}

#### Bloodstone Radiation
{: .no_toc}
If a bloodstone is left on the floor without any players interacting with it for 4-5 seconds, it will start pulsing with radiation, which damages all allies for 10% of their maximum health every 3 seconds until the shard is picked up. Every time this occurs, the shard will pulse with a red AoE indicator; this is not indicative of the actual range of the attack, which is arena-wide.

#### <img class="inline dispel"> Dispel
{: .no_toc}
This is a [Special Action Skill](https://wiki.guildwars2.com/wiki/Special_action_skill) that allows the player to interact with several of Ura's abilities. The skill has a range of 80 centered on the caster, and can:
- Free players trapped by [Pressure Blast] or [Return].
- Make [Toxic Geysers] vulnerable or kill them.
- Make [Titanspawn Geysers] vulnerable.

Using <img class="inline dispel"> [Dispel] drops the shard where the player is standing and applies 45s of <img class='inline saturation'> [Bloodstone Saturation].

---

### Geysers
{: .no_toc}
Geysers are enemy structures that are spawned by Ura periodically throughout the encounter. They give the boss some sort of advantage while progressively debilitating the squad, and thus must be dealt with rapidly and efficiently.

| **Type**                  | **Health**   | **Hitbox** | **Defiance Bar** |
| [Toxic Geyser]            | 448,200      | 416        | 800 (1000 in LM) |
| [Sulfuric Geyser]         | Untargetable | 440 - 580  | -                |
| [Titanspawn Geyser]       | 448,200      | 210 - 416  | 2000             |

#### Toxic Geysers
{: .no_toc}

Toxic Geysers spawn at specific time intervals in defined positions, shown in the image below. Spawning always starts at the first position and continues sequentially until the last.

In Challenge Mode, toxic geysers spawn every 12 seconds during the first phase, and every 24 seconds in the following phases. In Legendary Mode, they instead spawn every 12 seconds in all phases.

<img class="center" width="80%" src="../images/ura/ura_toxic_geyser_spawns.webp" />

Toxic Geysers spawn with a 580 radius AoE around them that applies 5 <img class="inline poison"> [Poison] every second, additionally inflicting <img class="inline sulfuricacid"> [Sulfuric Acid] when over 10 <img class="inline poison"> [Poison] stacks. Furthermore, this AoE also increases in radius every second by 10 units. As long as Ura is in contact with this AoE, she will periodically gain <img class='inline protection'> [Protection], <img class='inline resolution'> [Resolution] and 25 <img class='inline might'> [Might].

Breaking a Toxic Geyser's <img class='inline defiance'> [Defiance Bar] disables its AoE field and resets its radius. Toxic Geysers are immune to damage when spawning, but can be made vulnerable by using <img class="inline dispel"> [Dispel]. A geyser that is vulnerable and has had either its defiance or health depleted will be destroyed.

Because Toxic Geysers are constructs, they have lower armor and thus <img class='inline power'> [Power] damage is more effective against them.

In Legendary Mode, Toxic Geysers regenerate 150 Defiance every second.

#### Sulfuric Geysers
{: .no_toc}
Ura will periodically perform an animation and target a player with a Sulfuric Geyser. The player will get an audio cue, a timer above their head, and waves will start emanating around their position to show that they have been targeted.

After 5 seconds, the timer will run out and a sulfuric geyser will spawn on the player's position. Sulfurics spawn with an AoE around them that applies 5 <img class="inline poison"> [Poison] every second, additionally inflicting <img class="inline sulfuricacid"> [Sulfuric Acid] when over 10 <img class="inline poison"> [Poison] stacks. As long as Ura is in contact with this AoE, she will periodically gain <img class='inline protection'> [Protection], <img class='inline resolution'> [Resolution] and 25 <img class='inline might'> [Might].

When the geyser spawns, it will release a circular shockwave that will expand and cover the entire arena. This wave can be dodged, blocked or jumped, and it deals damage and inflicts <img class='inline sulfuricacid'> [Sulfuric Acid] on hit. 

Sulfuric Geysers cannot be destroyed, but despawn 5 minutes after they appear. They must be positioned accordingly at the edges of the arena so that they don't impede the squad and buff the boss for this duration.

Players targeted by a geyser will gain 5 seconds of <img class='inline superspeed'> [Superspeed].

Over the course of the fight, some sulfuric geysers will spawn naturally in predetermined positions independently from the players' actions.

#### Titanspawn Geysers
{: .no_toc}

When spawning a Titanspawn Geyser, Ura jumps into the air and crashes down, damaging everyone in an AoE centered around her. This attacks deals moderate damage and inflicts <img class='inline knockdown'> [Knockdown].

After this, a Titanspawn Geyser will spawn in one of five locations, chosen at random. This structure immediately spawns a [Champion Fumaroller], or a [Legendary Ventshot] in Legendary Mode during the final phase. Another add will spawn every 15 seconds until the geyser is destroyed.

Titanspawners are invulnerable when created, but can be made vulnerable using <img class="inline dispel"> [Dispel]. They also have a <img class='inline defiance'> [Defiance Bar] that can be broken to apply <img class='inline exposed'> [Exposed].

Because Titanspawn Geysers are constructs, they have lower armor and thus <img class='inline power'> [Power] damage is more effective on them.

Ura has a hard limit of 10 "minions" beyond which she will not spawn any more. This number includes Titanspawn Geysers, Fumarollers and Ventshots, and is reduced to 6 in phase 4.

| **Enemy**                 | **Health**   | **Hitbox** | **Defiance Bar** |
| [Champion Fumaroller]     | 1,789,242    | 300        | 1000             |
| [Legendary Ventshot] (LM) | 23,594,400   | 300        | 2000             |

#### Champion Fumaroller
{: .no_toc}

These dangerous enemies generally target players close to them and can be baited close to the boss in order to CC, cleave and kill them. They have three notable attacks:
- <u>Full Stream</u> - a headbutt attack in a line that inflicts <img class="inline knockback"> [Knockback]. Targets the player with the highest toughness in the Fumaroller's cone of view.
- <u>Breaking Ground</u> - a dangerous attack consisting in a snowflake pattern of lines centered on the Fumaroller which deals heavy damage to all players standing on it. Vertices deal extra damage.
- <u>Mantle Grinder</u> - the Fumaroller rolls in place, pulsing damage and <img class="inline knockback"> [Knockback]. 

#### Legendary Ventshot
{: .no_toc}
These enemies only spawn in Legendary Mode during the final phase instead of [Champion Fumarollers]. They have over 20 million health and are therefore not meant to be killed, but remain extremely dangerous due to their capabilities:
- <u>Tethers</u> -Ventshots periodically tether to up to five nearby titans, geysers, or other ventshots. If less than five allies are present, they will tether multiple times to the same ally until they form five tethers. Each tether applies <img class='inline risingpressure'> [Rising Pressure] to the corresponding ally. This buff has a shorter duration than usual, only lasting for ~12 seconds.
- <u>Please let me play the game</u> - most of the Ventshot's other attacks deal heavy damage, inflict <img class='inline knockdown'> [Knockdown] and <img class='inline burning'> [Burning], and are generally very undesirable. For this reason the general approach to these is to maintain permanent <img class='inline stability'> [Stability] and projectile denial throughout the final phase.

---

### Scalding Aura
{: .no_toc}
An AoE aura that is always active inside the boss's hitbox. Deals damage and applies <img class="inline burning"> [Burning].

---

### Acid Spray
{: .no_toc}

This attack is used when Ura's target is not in melee range and she has no other attack to cast that doesn't require a melee target. It consists in many small projectiles that deal damage and apply <img class="inline sulfuricacid"> [Sulfuric Acid] on hit.

---

### Pressure Blast
{: .no_toc}

This mechanic targets two random players with small white tracking AoEs. Targeted players will hear an audio cue, and after a short time interval, all allies inside the AoEs will be captured in bubbles and start floating upwards. 

Captured players cannot use any movement or abilities, and cannot be <img class='inline stunbreak'> [Stunbroken] out of this effect. They can only be freed using <img class='inline dispel'> [Dispel], otherwise continuing to float up until the bubbles pop, at which point they will drop down and die to fall damage.

It is standard practice for both players targeted by this skill to stack together a small distance away from the main group. This allows both to be freed with a single cast of <img class='inline dispel'> [Dispel], without the skill affecting the rest of the squad. For this reason, this mechanic is often called "friends".

The cooldown of [Pressure Blast] starts counting once all captured players are freed and hence it's of highest importance to free the captured players always as fast as possible (to mitigate the chance of Ura casting [Propel] during Phase 3 and 4).

Players affected by <img class='inline deterrence'> [Deterrence] cannot be targeted or affected by this skill.

It can happen that players suspended by bubbles are hit by <img class='inline knockback'> [Knockback], such as from [Champion Fumarollers]. In this case their actual position will be misaligned from the white indicator: <img class='inline dispel'> [Dispel] should always be used directly underneath the affected players.

---

### Propel
{: .no_toc}

Ura targets the furthest player within 1500 range and jumps a fixed distance, dealing heavy damage when she lands. This can be mitigated with any traditional method.

This and [Return] are the only ways the boss can move, as it cannot walk. Therefore, groups often try to bait this skill to position the boss in an advantageous location (for example, out of the range of [Toxic Geysers] or [Sulfuric Geysers]).

---

### Return
{: .no_toc}

This attack happens during the transition into the second phase, when Ura hits 70%, but also if Ura hits the edge of the arena due to [Propel].

Ura will start swirling all players around her in a vortex, capturing them after a moment and then teleporting herself and them to her spawn point. Captured players are affected identically as with [Pressure Blast]: they will be unable to move or use skills until <img class='inline dispel'> [Dispel] is used to free them or they die due to the bubbles popping.

Players can dodge this mechanic with the right timing, but this is often not useful they will be separated from the rest of the squad and will have to run back to Ura.

---

### Steam Prison
{: .no_toc}
Targets a random player with a large AoE. They will hear an audio cue, and after a short time interval, an arena/cage formation will spawn centered on them.

All projectiles originating inside the arena will be reflected back to their caster, which can quickly down an unprepared individual. The walls also inflict <img class='inline knockback'> [Knockback] to players attempting to exit the cage, preventing these movements unless the players are provided with <img class="inline stability"> [Stability]. Blinks, shadowsteps and portals also let players exit.

When placing the arena, medium range dashes can be used with the correct timing to not get caught inside. <img class='inline superspeed'> [Superspeed] also allows placing the arena and getting safely out by just running quickly enough before the arena spawns.

---

### Autoattack Chain
{: .no_toc}

This attack consists in two smashes followed by a final cone attack. Each attack deals damage and applies <img class="inline vuln"> [Vulnerability] on hit. The third and final cone also inflicts <img class="inline knockdown"> [Knockdown].

<img class=divider>

## List of Effects
Ura's encounter has various effects applied to players or enemies, which are listed below for reference purposes.

---

### <img class="inline titanicresistance"> Titanic Resistance
{: .no_toc}

Every time Ura's <img class='inline defiance'> [Defiance Bar] is broken, she gains one stack of <img class="inline titanicresistance"> [Titanic Resistance]. This effect reduces any incoming defiance damage by 5% and is additive. For example, once Ura has 10 stacks of <img class="inline titanicresistance"> [Titanic Resistance], defiance damage is reduced by 50%, which effectively doubles her breakbar.

This mechanic essentially limits the number of times the breakbar can be broken to roughly 13 to 15 times per encounter, depending on the squad composition.  This dictates the timing of when to break the bar, which comes out to be roughly every 40 to 50 seconds.

| Stacks | CC Multiplier |  Effective regen (LM) [1/s] | Effective CC bar |
| 0  | 1    | 150  | 3000  |
| 1  | 0,95 | 158  | 3158  |
| 2  | 0,9  | 167  | 3333  |
| 3  | 0,85 | 176  | 3529  |
| 4  | 0,8  | 188  | 3750  |
| 5  | 0,75 | 200  | 4000  |
| 6  | 0,7  | 214  | 4286  |
| 7  | 0,65 | 231  | 4615  |
| 8  | 0,6  | 250  | 5000  |
| 9  | 0,55 | 273  | 5455  |
| 10 | 0,5  | 300  | 6000  |
| 11 | 0,45 | 333  | 6667  |
| 12 | 0,4  | 375  | 7500  |
| 13 | 0,35 | 429  | 8571  |
| 14 | 0,3  | 500  | 10000 |
| 15 | 0,25 | 600  | 12000 |
| 16 | 0,2  | 750  | 15000 |
| 17 | 0,15 | 1000 | 20000 |
| 18 | 0,1  | 1500 | 30000 |
| 19 | 0,05 | 3000 | 60000 |
| 20 | 0,0  | Infinite|Infinite|

---

### <img class="inline risingpressure"> Rising Pressure
{: .no_toc}

Ura, [Champion Fumarollers] and [Legendary Ventshots] gain one stack of [Rising Pressure] every 8 seconds in LM and every 12 seconds in CM. This effect increases damage dealt and reduces incoming damage by 5% per stack (additively). Breaking the enemy's <img class="inline defiance"> [Defiance Bar] removes all [Rising Pressure] stacks and grants a stack of <img class='inline titanicresistance'> [Titanic Resistance].

---

### <img class="inline saturation"> Bloodstone Saturation
{: .no_toc}

A debuff applied to players when they use <img class='inline dispel'> [Dispel]. Lasts for 45 seconds and can stack, dealing damage to the afflicted player equal to 20% of their maximum health per stack per second as long as they are holding a [Bloodstone Shard].

---

### <img class="inline deterrence"> Deterrence
{: .no_toc}

A buff a player gets when holding a [Bloodstone Shard]. Players affected by this buff cannot be targeted or affected by [Pressure Blast].

---

### <img class="inline sulfuricacid"> Sulfuric Acid
{: .no_toc}

A dangerous stacking debuff applied by various mechanics that deals damage every second and applies one stack of [Exposed] every 5 seconds.

It can be removed with normal condition cleanse, but only ever one stack at a time, even if the skill would remove multiple conditions. It has very low priority, meaning that generally it will be the last condition removed in case of multiple conditions on the same player. Furthermore, it cannot be transferred to enemies, though this will cleanse as usual.

<img class=divider>

[Return to Home](../index.html){: .btn } [Return to Overview](overview.html){: .btn } [Return to Top](#ura-mechanical-reference){: .btn .fixed}
{: .center}

[Acid Spray]: #acid-spray
[Titanic Resistance]: #-titanic-resistance
[Deterrence]: #-deterrence
[Dispel]: #bloodstone-shard
[Bloodstone Shard]: #bloodstone-shard
[Bloodstone Shards]: #bloodstone-shard
[Bloodstone Saturation]: #-bloodstone-saturation
[Champion Fumaroller]: #champion-fumaroller
[Champion Fumarollers]:  #champion-fumaroller
[Legendary Ventshot]: #legendary-ventshot
[Legendary Ventshots]: #legendary-ventshot
[Toxic Geyser]: #toxic-geysers
[Toxic Geysers]: #toxic-geysers
[Sulfuric Geyser]: #sulfuric-geysers
[Sulfuric Geysers]: #sulfuric-geysers
[Create Titanspawn Geyser]: #titanspawn-geysers
[Titanspawn Geyser]: #titanspawn-geysers
[Titanspawn Geysers]: #titanspawn-geysers
[Autoattack Chain]: #autoattack-chain
[Pressure Blast]: #pressure-blast
[Propel]: #propel
[Scalding Aura]: #scalding-aura
[Steam Prison]: #steam-prison
[Bloodstone Radiation]: #bloodstone-radiation
[Rising Pressure]: #-rising-pressure
[Return]: #return
[Sulfuric Acid]: #-sulfuric-acid

[Invulnerable]: https://wiki.guildwars2.com/wiki/Invulnerable
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar
[Aegis]: https://wiki.guildwars2.com/wiki/Aegis
[Protection]: https://wiki.guildwars2.com/wiki/Protection
[Resolution]: https://wiki.guildwars2.com/wiki/Resolution
[Might]: https://wiki.guildwars2.com/wiki/Might
[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Power]: https://wiki.guildwars2.com/wiki/Power
[Condition]: https://wiki.guildwars2.com/wiki/Condition
[Conditions]: https://wiki.guildwars2.com/wiki/Condition
[Poison]: https://wiki.guildwars2.com/wiki/Poisoned
[Burning]: https://wiki.guildwars2.com/wiki/Burning
[Vulnerability]: https://wiki.guildwars2.com/wiki/Vulnerability
[Knockdown]: https://wiki.guildwars2.com/wiki/Knockdown
[Knockback]: https://wiki.guildwars2.com/wiki/Knockback
[Exposed]: https://wiki.guildwars2.com/wiki/Exposed
[Stunbroken]: https://wiki.guildwars2.com/wiki/Stun_break
[Superspeed]: https://wiki.guildwars2.com/wiki/Superspeed
[Stealthed]: https://wiki.guildwars2.com/wiki/Stealth