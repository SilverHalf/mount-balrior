---
layout: page
title: Mechanics
nav_order: 1
parent: Godspoil Greer
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn } [Strategy Guide](./strategy.html){: .btn }

# Greer Mechanical Reference
{: .no_toc}

This section contains a detailed reference of the various attacks and mechanics present in the Godspoil [Greer encounter]. 

The rest of this page is structured into the following sections:
1. **Overview** - basic description of the fight and its main points.
2. **Phases** - a description of the structure of the fight, with transitions and differences between phases.
3. **Mechanics** - a reference of every attack in the encounter.
4. **Effects** - a reference of all effects unique to the encounter.

### Table of Contents
{: .no_toc}

1. TOC
{:toc}

---

## Overview

Greer's basic attack pattern centers around a handful of skills that have individual cooldowns, priorities and line of sight/range conditions. This means that while there is some randomness in the encounter, repeatable patterns often occur as high priority skills come off cooldown ar roughly the same instants over multiple pulls. The fight is separated into various main and split phases, with transitions triggered by hitting specific health thresholds.

### Enemy entities
{: .no_toc}

During the [Greer encounter], you will have to deal with multiple different enemies on top of [Greer]: the three lesser Titans ([Ereg], [Gree] and [Reeg]), three Champion Proto-Greerlings and some weaker [Elite Empowering Beast]s.

| **Enemy** | **Health** | **Hitbox** | **Defiance Bar** |
| Godspoil Greer | 47,188,800 | 800 | 6000 |
| Gree, the Bringer | 23,594,400 | 600 | |
| Reeg, the Blighter | 23,594,400 | 600 | |
| Ereg, the Enabler | 23,594,400 | 600 | |
| Champion Proto-Greerling | 5,112,120 | 600 | |
| Elite Empowering Beast | 236,003 | 240 | 500 |


### Boons on the titans
{: .no_toc}

The fight starts with [Greer], [Gree], [Reeg], and [Ereg] all being alive and vulnerable at their specific spawn location. While [Gree], [Reeg], or [Ereg] are alive (called, the lesser titans, hereafter), they will give boons that are shared between each other and [Greer]. Gree gives <img class="inline protection"> [Protection], Reeg <img class="inline resolution"> [Resolution] and Ereg <img class="inline might"> [Might].

Bringing the lesser titans below certain health thresholds makes them despawn for the current phase and consequently prevents their respective boon from being applied. These thresholds are 75% for the first main phase and 25% for the second main phase. For this reason, <img class='inline power'> [Power]-based squad compositions should start on [Gree], while <img class='inline condition'> [Condition]-based squads should focus on [Reeg].

### Table of Mechanics
{: .no_toc}
A brief description of the primary mechanics in the fight. Click on a mechanic to view additional information.

| **Attack** | **Common Name** | **Target** | **Used by (Cooldown [s])** | **Brief Description** |
| [Blob of Blight] | Death orbs | Three furthest players | Greer (120), Reeg (75), Ereg (75) | Large homing orbs that <img class="inline knockback"> [Knockback] and spawn projectiles. |
| [Cage of Decay] | Arrows | Tank | Greer (120), Gree (30) | 5 Arrows that spawn projectiles starting with the two outer Arrows going inward. The projectiles spawn [Noxious Blight] pools once they reach the end of their track, or when they hit the edge of the arena. |
| [Empowering Blast] | Empowered orbs/Small orbs | Greer and other lesser Titans | lesser titans (10) | Small purple orbs that give <img class='inline empowered'> [Empowered] stacks to their target. |
| [Enfeebling Miasma] | Cones, Poison cones | Tank | Greer (120), Reeg (75), Ereg, (75) | An attack spawning three cones with an outgoing poisonous gas that applies <img class="inline poison"> [Poison] and leaves behind [Noxious Blight] pools. |
| [Eruption of Rot] | Greens | Random | Greer (120), lesser titans (75) | Large Green AoEs centered around players that need either 2, or 3 players inside them to be solved. |
| [Rain of Spores] | Artillery barrage | Furthest players | Greer (120), Reeg (120), Ereg (120) | A barrage of projectiles indicated by small AoEs that explode on impact, dealing damage and applying <img class="inline poison"> [Poison] and <img class="inline confusion"> [Confusion]. |
| [Ripples of Rot] | Jump | Closest player, but only if no player is in their extended melee range | Greer (120), Gree (30) | A jump attack with a large AoE that deals damage and inflicts <img class="inline knockback"> [Knockback], <img class="inline poison"> [Bleeding]  and <img class="inline plague-rot"> [Plague Rot]. |
| [Scattering Sporeblast] | Barrage | Tank | Greer (12), Reeg (8), Ereg (8) | A barrage of damaging projectiles that targets enemies in front of the caster. |
| [Stomp the Growth] | Slam, Stomp, Wave | Tank | Greer (2), Gree (2), Reeg (2) | A three-part attack chain. The first two attacks are damaging AoE slams and the third and final part releases a wave that deals damage, corrupts boons, and applies <img class="inline vuln"> [Vulnerability] and <img class="inline knockdown"> [Knockdown]. |
| [Sweep the Mold] | Autoattack, Cone | Tank | Greer (2), Gree (2) | Two subsequent cone attacks that deal damage and apply <img class="inline knockback"> [Knockback], <img class="inline poison"> [Bleeding] and <img class="inline poison"> [Poison] for the first one and <img class="inline knockback"> [Knockback], <img class="inline cripple"> [Cripple] and <img class="inline poison"> [Poison] for the second. |
| <img class="inline plague-rot"> [Plague Rot] | Covid, Reds | - | - | A dangerous debuff applied by some of Greer's abilities that deals damage and corrupts boons in an AoE around the affected player, and can rapidly spread to other players. |

---

## Phases

There are essentially 3 different types of phases:
- Burn phases, in which Greer and the lesser titans are attackable.
- Split phases, in which Greer is <img class='inline invuln'> [Invulnerable] and the lesser Titans are attackable (at new, different locations) - The 10% phase, in which Greer is <img class='inline invuln'> [Invulnerable], but 3 Champion Proto-Greerlings are active (and Ereg, if kept alive).

The fight overall consists of:
1. A main phase from 100% to 65% health.
2. A split phase.
3. A second main phase from 65% to 35% health.
4. A second split phase.
5. A third main phase from 35% to 10% health.
6. The proto-greerling phase.
7. A final phase from 10% to 0% health.

### Main Phases

The main phase starts at the beginning of the fight with the following spawnpoints for Greer and the lesser titans:

<img class="center" width="70%" src="../images/greer/mechanics/mainphase_spawnpoints.webp" />

During the first two main phases, all lesser titans will not move from these locations. During the third main phase, [Ereg] will be free to move if he is still alive.

Depending on whether your group is playing with a <img class='inline power'> [Power] or <img class='inline condition'> [Condition] based composition, you will start at a different location:

- <img class='inline power'> [Power] compositions will start on [Gree]
- <img class='inline condition'> [Condition] compositions will start on [Reeg]

At the start of phases, high priority skills are usually used, which means [Blob of Blight] (Death Orbs) and [Eruption of Rot] (Greens). The first goal is to bring either Gree, or Reeg to 75%, such that they despawn and with them their respective boon is removed (<img class="inline protection"> [Protection] for [Gree], <img class="inline resolution"> [Resolution] for [Reeg]).

The main phase then revolves around damaging Greer while dealing with his cooldown and priority based attacks all while simultaneously blocking all relevant projectiles, especially [Empowering Blast] from the active lesser titans.

At 80%, 50%, and 20% of his health, Greer will become <img class='inline invuln'> [Invulnerable], unlocking a <img class='inline defiance'> [Defiance Bar], which needs to be broken quickly. While the defiance bar is active, Greer will continuously spawn AoEs on the group, which deal moderate to high damage. Breaking the bar will spawn several [Elite Empowering Beast]s, respectively, that will start targeting Greer with [Empowering Blast], requiring additional projectile block.
- Two [Elite Empowering Beast]s will be spawned at 80% HP.
- Three will be spawned at 40% HP.
- Four will be spawned at 20% HP.

The first main phase ends at 65%, the second at 35% and the third at 10%. The first two main phases are pretty similar in the amount of mechanics and small orbs from [Empowering Blast] that have to be dealt with. The third main phase is different since both Gree and Reeg will have been killed already, removing the need to block their projectiles.

---

### Split Phases

The split phases start once Greer hits 65% and 35% HP. All lesser titans currently alive will move to a new position, as shown by the following image. 

<img class="center" width="70%" src="../images/greer/mechanics/splitphase_spawnpoints.webp" />

During these phases Greer is <img class='inline invuln'> [Invulnerable] and does not perform any attacks or mechanics, instead remaining at the position he occupied at the end of the previous main phase.

Split phases end when both [Reeg] and [Gree] have reached a defined health threshold, that being 50% HP for the first split phase, or 0% for the second. [Ereg] does not count towards the end of the split phase. He will despawn when reaching 50% HP during the first split, or otherwise when the phase ends. If he is alive at the end of the second split phase, he will remain active and mobile throughout the rest of the fight or until killed. 

Usually <img class='inline power'> [Power] compositions will try to focus down [Gree] first, while <img class='inline condition'> [Condition] groups will instead go for [Reeg]. Both will then transition to the remaining lesser titans once the one applying their main antagonistic boon is removed.

---

### Proto-Greerling Phase

Once Greer hits 10% of his HP, he will become <img class='inline invuln'> [Invulnerable]. At the same time, three Champion Proto-Greerlings will appear. They have 12 possible spawn points, out of which three are chosen at random.

<img class="center" width="70%" src="../images/greer/mechanics/protolings_spawnpoints.webp" />

These Champions will continously perform the basic attack chains: [Sweep the Mold], [Stomp the Growth] and [Scattering Sporeblast]. This means this phase has a very high level of incoming damage and requires constant projectile block.

Greer will remain fully active throughout this phase. The squad should pay attention to his highly disruptive mechanics, in particular [Blob of Blight], [Eruption of Rot] and [Ripples of Rot].

--- 

### Sub 10% Phase

Once the last champiton has been defeated, Greer becomes vulnerable for 30 seconds. After this time passes, the champtions respawn and he becomes <img class='inline invuln'> [Invulnerable] once more untill they are dead. This ususally leads to a wipe due to the tight enrage timer.

While this phase is functionally identical to a main phase, the time limit means that it must be approached in a fundamentally different manner. Always try to prepare approriately by having major cooldowns ready or by prestacking conditions on Greer while finishing the last Champion. It can be beneficial to kill the final champion close to Greer for this reason.

During this phase you only have to deal with Greer's attacks (and [Ereg]'s if he's alive), but because Greer often has a lot of <img class="inline empowered"> [Empowered] stacks at this point, every attack is deadly, especially [Stomp the Growth].


---

## List of Mechanics

This section contains a full, in-depth explanation of all mechanics in the encounter.

Generally, there is a skill priority that titans follow, however, this skill priority is often interrupted with the Auto-attack chain [Sweep the Mold]. The full logic behind how Greer selects what attacks to use is not yet fully understood. The general priority of skills is roughly as follows:
1. [Blob of Blight]
2. [Eruption of Rot]
3. [Ripples of Rot] (only when no target is in range)
4. [Rain of Spores]  (when Greer's target is not in melee range)
5. [Scattering Sporeblast] (when Greer's target is not in melee range)
6. [Enfeebling Miasma]
7. [Cage of Decay]
8. [Rain of Spores]  (when Greer's target is not in melee range)
9. [Stomp the Growth]

---

### [Blob of Blight]
{: .no_toc}

An attack used by Greer (cooldown 120s), Reeg (cooldown 75s) and Ereg (cooldown 75s) targeting the three furthest players. These players get notified by a <img class="inline target"> [Target] effect in their boon bar and a pulsing audio cue. Spawns three homing orbs in sequence in front of the caster. These orbs start tracking the targeted players while constantly spawning projectiles.

If they hit a player, they will become stationary for 12 seconds before despawning. The projectiles they summon during this period can quickly become deadly if not avoided.

Moving orbs can also be despawned by evading through then them, or by moving into them with active <img class='inline invuln'> [Invulnerability] effects, such as <img class='inline distortion'> [Distortion]. This does not work for stationary orbs.

---

### [Cage of Decay]
{: .no_toc}

An attack used by Greer (cooldown 120s) and Gree (cooldown 30s). This attacks produces five projectiles, marked with arrow indicators. It starts with 2 arrows directed towards opposite sides of the caster, with the following directed inwards by 45° steps. These projectiles inflict <img class="inline knockback"> [Knockback] multiple times while travelling along their path. Once they reach their maximum travel or hit the edge of the arena, they spawn a pool of [Noxious Blight] which persists for a brief period, stripping boons and applying <img class="inline plague-rot"> [Plague Rot].

---


### [Empowering Blast]
{: .no_toc}

An attack used by the three lesser titans and by [Elite Empowering Beasts]. It shoots out small orbs towards other lesser titans and towards Greer. If they hit their target, the target receives two stacks of <img class="inline empowered"> [Empowered]. These small orbs can be destroyed by using projectile destruction/reflection skills. During the first and second main phase, lesser titans will constantly use this ability as long as they are active, which requires frequent projectile block. It's crucial to block those as much as possible, because otherwise Greer will gain too many <img class="inline empowered"> [Empowered] stacks and overwhelm you.

---

### [Enfeebling Miasma]
{: .no_toc}

An attack used by Greer (cooldown 120s), [Reeg] (cooldown 75s) and [Ereg] (cooldown 75s). It spawns three cone indicators that release an outgoing wave of miasma, leaving behind clouds of poisonous gas. The waves corrupt boons and applies <img class="inline poison"> [Poison], and should be avoided by either immediately dodging through the casting add, or by standing between the cones. Note that the actual area of effect is larger than the indicator. The poisonous gas clouds are pools of [Noxious Blight], which corrupt boons and apply <img class="inline plague-rot"> [Plague Rot]. Avoid them at all costs.

---

### [Eruption of Rot]
{: .no_toc}

Used by Greer (cooldown 120s) and all three lesser titans (cooldown 75s). Targets one or mora players with a green AoE requires a certain amount of players inside: 3 if the caster is Greer, 2 if the caster is another titan. Failing to solve any Green summons a [Noxious Blight] pool under the targeted player that knocks up, corrupts boons and inflicts <img class="inline plague-rot"> [Plague Rot]. Failing a Green furthermore gives two stacks of <img class="inline empowered"> [Empowered] to the caster: for this reason it's always important to have the minimum number of players for each green.

Players that stand in multiple greens within a short time interval will be <img class='inline invuln'> [Downed]. This effect can be evaded with the right timing, or can be avoided with <img class='inline invuln'> [Invulnerability] skills. Similarly, the pool summoned by failed greens can be avoided in the same manner.

The number of Greens spawned by Greer increases in later phases up to a maximum number of three simultaneous three-person Greens.

---

### [Rain of Spores]
{: .no_toc}

Used by Greer (cooldown 120s), [Reeg] (cooldown 120s) and [Ereg] (cooldown 120s). Targets the furthest player, shooting out a barrage of projectiles indicated by small AoEs. These deal damage and apply <img class="inline poison"> [Poison] and <img class="inline confusion"> [Confusion]. It's best to have projectile block up for these to mitigate as much damage as possible.

Greer uses this attack only when his target is not in melee range

---

### [Ripples of Rot]
{: .no_toc}

An attack used by Greer (cooldown 120s) and [Gree] (cooldown 30s) that can happen whenever they don't have a melee target available. When this attack is used, the caster jumps up toward their target, falling down in a deadly AoE that spreads outwards from their point of contact with the ground. The attack deals damage and inflicts <img class="inline knockback"> [Knockback], <img class="inline poison"> [Bleeding] and <img class='inline plague-rot'> [Plague Rot]. 

The exact trigger for this attack is not precisely understood, but it's tied to being in a specific range window from the caster, somewhere between 600 and 1000. If you are closer than this, this attack will not be used.

---

### [Scattering Sporeblast]
{: .no_toc}

Used by Greer (cooldown 12s), [Reeg] (cooldown 8s), [Ereg] (cooldown 8s) and Champion Proto-Greerlings. Shoots damaging spores that can be projectile blocked, targeting enemies in front of the caster and dealing moderate to high damage. Since Reeg and Ereg don't have [Sweep the Mold] and [Stomp the Growth] in their skillsets, they will use this attack very frequently. Greer uses this attack only when his target is not in melee range.

---

### [Stomp the Growth]
{: .no_toc}

A three-part attack chain used by Greer, [Gree] and Champion Proto-Greerlings regularly. The first two attacks are high damage melee AoE slams. The third and final attack has different effects based on the caster: when cast by Greer it releases a wave that deals damage, corrupts boons, and inflicts <img class="inline vuln"> [Vulnerability] and <img class="inline knockback"> [Knockback]; when cast by [Gree] or the Champion Proto-Greerlings, it does not unleash a wave, instead dealing heavy damage and a inflicting <img class="inline knockdown"> [Knockdown].

This attack can be mitigated with <img class="inline aegis"> [Aegis], blocks, or evasion. The wave it generates when cast by Greer can also be jumped.

This attack becomes especially deadly in the later phases of the fight, when Greer often has several stacks of <img class='inline empowered'> [Empowered], due to its high damage and large area of effect.



---

### [Sweep the Mold]
{: .no_toc}

This attack is used by Greer, [Gree] and Champion Proto-Greerlings regularly. It consists of two subsequent 60° cones that <img class="inline knockback"> [Knockback], deal damage and inflict <img class="inline bleeding"> [Bleeding] and <img class="inline poison"> [Poison] for the first swipe and <img class="inline cripple"> [Cripple] and <img class="inline poison"> [Poison] for the second swipe. The damage component of this attack is not high, so it can be ignored using <img class="inline stability"> [Stability] or otherwise mitigated with <img class="inline aegis"> [Aegis] or by sidestepping.

---

## List of Effects
Greer's encounter has some additional unique effects, which are listed below for reference purposes.

---

### <img class='inline empowered'> Empowered
{: .no_toc}
An effect that is gained by all three titans when players fail mechanics. Increases outgoing damage by 5% per stack, up to 99 stacks, at which point all attacks become unblockable. Titans can gain <img class='inline empowered'> [Empowered] through the following:

- [Empowering Blast] will grant one stack every time it hits a titan.
- [Eruption of Rot] will grant two stacks to the casting titan on failure.

---

### <img class="inline plague-rot"> Plague Rot
{: .no_toc}
An debuff that is applied to players hit by a [Cage of Decay], [Enfeebling Miasma], or [Ripples of Rot]. Affected players are surrounded by a red AoE that regularly corrupts boons and applies <img class="inline poison"> [Poison]. This effect spreads to other players the AoE, and if uncontrolled can quickly spread to the entire squad.

The effect is removed is the affected player is <img class='inline invuln'> [Downed], or after a brief time interval.

Reaching 10 stacks of <img class="inline plague-rot"> [Plague Rot] will instantly kill the player.

---

### <img class="inline target"> Target
{: .no_toc}
An effect that gets applied from being targeted by [Blob of Blight], which targets the furthest players away from the caster.

---

### [Noxious Blight]
{: .no_toc}
Describes various stationary AoE pools left behind by some abilities that corrupt boons and apply <img class="inline plague-rot"> [Plague Rot] to any player touching them.

---


[Return to Home](../index.html){: .btn } [Return to Overview](overview.html){: .btn } [Return to Top](#greer-mechanical-reference){: .btn .fixed}

[Greer]: https://wiki.guildwars2.com/wiki/Greer,_the_Blightbringer
[Greer encounter]: https://wiki.guildwars2.com/wiki/Mount_Balrior#Challenge_mode_2
[Gree]: https://wiki.guildwars2.com/wiki/Gree,_the_Bringer
[Reeg]: https://wiki.guildwars2.com/wiki/Reeg,_the_Blighter
[Ereg]: https://wiki.guildwars2.com/wiki/Ereg,_the_Enabler
[Elite Empowering Beast]: https://wiki.guildwars2.com/wiki/Elite_Empowering_Beast
[Elite Empowering Beasts]: https://wiki.guildwars2.com/wiki/Elite_Empowering_Beast
[Empowering Blast]: #empowering-blast
[Cage of Decay]: #cage-of-decay
[Blob of Blight]: #blob-of-blight
[Empowered]: https://wiki.guildwars2.com/wiki/Empowered_(Greer,_the_Blightbringer)
[Enfeebling Miasma]: #enfeebling-miasma
[Eruption of Rot]: #eruption-of-rot
[Rain of Spores]: #rain-of-spores
[Ripples of Rot]: #ripples-of-rot
[Scattering Sporeblast]: #scattering-sporeblast
[Stomp the Growth]: #stomp-the-growth
[Sweep the Mold]: #sweep-the-mold
[Plague Rot]: #-plague-rot
[Target]: #-target
[Noxious Blight]: #noxious-blight

[Aegis]: https://wiki.guildwars2.com/wiki/Aegis
[Protection]: https://wiki.guildwars2.com/wiki/Protection
[Resolution]: https://wiki.guildwars2.com/wiki/Resolution
[Might]: https://wiki.guildwars2.com/wiki/Might
[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Poison]: https://wiki.guildwars2.com/wiki/Poisoned
[Confusion]: https://wiki.guildwars2.com/wiki/Confusion
[Bleeding]: https://wiki.guildwars2.com/wiki/Bleeding
[Vulnerability]: https://wiki.guildwars2.com/wiki/Vulnerability
[Cripple]: https://wiki.guildwars2.com/wiki/Crippled
[Knockback]: https://wiki.guildwars2.com/wiki/Knockback
[Knockdown]: https://wiki.guildwars2.com/wiki/Knockdown
[Distortion]: https://wiki.guildwars2.com/wiki/Distortion
[Spare the Ereg]: https://wiki.guildwars2.com/wiki/Mount_Balrior_(achievements)#achievement8548
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar
[Invulnerable]: https://wiki.guildwars2.com/wiki/Invulnerability
[Invulnerability]: https://wiki.guildwars2.com/wiki/Invulnerability
[Power]: https://wiki.guildwars2.com/wiki/Power
[Condition]: https://wiki.guildwars2.com/wiki/Condition_Damage
[Downed]: https://wiki.guildwars2.com/wiki/Downed