---
layout: page
title: Decima Mechanics
nav_order: 1
parent: Godsquall Decima
---

# Decima Mechanical Reference
{: .no_toc}

This page contains detailed information on all attacks, phases, mechanics and effects in the Godsquall Decima encounter.

Decima is an articulated fight with many phases and interactions, and several mechanics lead naturally into each other, so knowing the nature of these interactions is fundamental towards learning the encounter.

### Table of Contents
{: .no_toc}

1. TOC
{:toc}

---

## Attacks

These are mechanics originating from Decima herself. Decima's behaviour is to perform an attack loop: a series of skills that are cast continuously one after the other, looping continuously until the boss's health is below the threshold to begin its next phase. Most of Decima's attacks are part of this loop.

---

### Thrumming Presence

A 750-radius area-of-effect centered around Decima, outlined with a faint red circle. Constantly inflicts a small amount of damage to all players inside the area (increasing with the number of <img class="inline charge"> [Charge] on the boss) and applies <img class="inline harmonic-sensitivity"> [Harmonic Sensitivity].

<img class="center" width="80%" src="../images/decima/mechanics/thrumming.webp" />

Decima gains her Thrumming Presence at the beginning of the encounter, and only loses it while moving, while casting [Flux Nova], while <img class="inline stun"> [Stunned], and while under 10% health.

---

### Fluxlances

Also known as "Arrows" due to their indicator. Laser attacks originating from the boss. Once their indicator appears, after a brief delay, fluxlances will fire, applying an effect in a line according to their type. Fluxlances have infinite range, but can be blocked by [Conduits]. Any conduit hit by a lance will increase its charge level, but will prevent the lance from extending beyond the conduit itself. All fluxlances cannot be <img class="inline aegis"> [Blocked] or <img class="inline evade"> [Evaded], and ignore <img class="inline invuln"> [Invulnerability].

#### Standard Fluxlance
Also known as orange arrow. Targets the furthest player that is not targeted by another Fluxlance, dealing heavy damage to all allies in a line, increased for players affected by <img class="inline harmonic-sensitivity"> [Harmonic Sensitivity]. Applies 30 seconds of <img class="inline galvanic-sensitivity"> [Galvanic Sensitivity], and <img class="inline exposed"> [Exposed] to all allies, hit except its target.

#### Red Fluxlance
Also known as red arrow. Always targets the furthest player, and **instantly defeats** all allies it hits. Must be aimed away from the squad a blocked using a [Conduit].

#### Focused Fluxlance
Also known as green arrow. Targets the furthest conduit from the furthest player from the boss. Requires five people to be inside the arrow's line of fire to block the attack and prevent it from charging the conduit. Deals heavy damage, reduced based on the number of people in the arrow, and unaffected by <img class="inline harmonic-sensitivity"> [Harmonic Sensitivity]. Focused Fluxlances are summoned as part of Decima's attack rotation from 40% to 10% hp.

<img class="center" width="80%" src="../images/decima/mechanics/fluxlances.webp" />

Standard or red fluxlances are summoned whenever Decima casts one of the following skills as part of her attack loop:

#### Fluxlance Fusillade
Targets the five furthest players with standard fluxlances. Targeted players will have a number above their head from one to five. After a brief delay, the lances will be fired in sequence based on their number.

#### Fluxlance Salvo
Targets the five furthest players with fluxlances. After a brief delay, all lances are fired simultaneously. Every other time that Decima uses this skill, one of the fluxlances will be a red Fluxlance.



---

### Chorus of Thunder

Decima consumes all her stacks of <img class="inline harmony"> [Peal of Harmony] and  <img class="inline discord"> [Peal of Discord], with the following effects:

- For each stack of <img class="inline discord"> [Peal of Discord] consumed, Decima will target the closest untargeted player to the boss with a Thunder.
- For each stack of <img class="inline harmony"> [Peal of Harmony] consumed, Decima will target the closest uncharged [Conduit] to the furthest player with a Thunder.

Thunders are tracking circular AoEs that fill and explode after a brief delay, dealing damage and charging all [Conduits] they hit. Damage increases with the number of overlapping AoEs, but can be <img class="inline evade"> [Evaded], <img class="inline invuln"> [Invulned] or <img class="inline aegis"> [Blocked]. Single blocks will prevent one Thunder from hitting, but channeled blocks are necessary in case of multiple overlaps.

Players hit by any Thunder except their own will be <img class="inline exposed"> [Exposed].

Chorus of Thunder is used regularly by Decima as part of her attack loop.

---

### Conduits
Conduits, or pylons, are structures that are manipulated by Decima and play a critical part in the encounter as a whole. Eighteen of them are summoned at the beginning of the fight, and they persist throughout all phases. Conduits are arrayed in shifting patterns around Decima, which vary based on the phase and the state of Decima's attack loop.

#### Conduit Charge
Whenever a conduit is hit by by [Fluxlances] or [Thunder], it gains a level of Charge. When charged, a conduit gains *Fulgent Aura*: a red damaging AoE centered around the conduit that grows larger with each level of charge.

#### Fulminate
Conduits cannot be charged more than three times: every time a level three conduit would gain a charge, it instead *Fulminates*, dealing massive damage and applying <img class="inline exposed"> [Exposed] in a large area, and granting Decima five stacks each of <img class="inline harmony"> [Peal of Harmony] and <img class="inline discord"> [Peal of Discord].

#### Fulgent Fences
Lasers that link two conduits together. Whenever any player passes through them, they are affected by *Reverberating Impact*, which deals moderate damage and pushes the player out of the laser, preventing them from crossing it. This is also applied for movement skills such as dashes, but excludes player teleportation such as blinks or portals, and is not affected by <img class="inline stability"> [Stability]. Players that are knocked into a fence by Decima's attacks are ejected at high speeds, possibly into other fences.

#### Dancing Sparks

Also known as greens. Small AoEs that spawn from charged [Conduits] and start moving towards Decima. If they are allowed to reach the boss, they are consumed and grant her a stack of <img class="inline charge"> [Charge].

Sparks deal damage to all players standing in their area, which is greatly increased towards players affected by <img class="inline galvanic-sensitivity"> [Galvanic Sensitivity]. When enough players stand inside a spark, it will stop moving towards Decima and start draining health, disappearing once fully drained. The number of players required to achieve this effect is displayed above each spark, and is equal to the charge level of its originating conduit.

All charged conduits spawn sparks simultaneously as part of Decima's attack loop.

---

### Foreshock & Mainshock

<img class="center" width="100%" src="../images/decima/mechanics/mainshock.webp" />

#### Foreshock
Decima stomps three times, dealing moderate damage in 3 large AoEs.

#### Mainshock
Always cast after Foreshock:  a "pizza" attack centered on Decima. Deals significant damage and additionally inflicts 25 <img class="inline vuln"> [Vulnerability](https://wiki.guildwars2.com/wiki/Vulnerability). Players hit by multiple "slices" will recieve multiple instances of this damage.

Foreshock and Mainshock are used regularly by Decima as part of her attack loop.

---


### Seismic Crash

Decima leaps up, then crashes down in a circular AoE centered on herself. This AoE has two components:
- The inner circle, with the same dimensions as Decima's hitbox, **instantly defeats** all players inside of it. This effect cannot be <img class="inline evade"> [Evaded], <img class="inline invuln"> [Invulned] or <img class="inline aegis"> [Blocked].
- A larger area around Decima deals damage (decreasing the further the player is from the boss) and inflicts <img class="inline knockback"> [Knockback]. This part can be mitigated using all standard methods.

Seismic Crash is a critical ability, not due to its instant kill potential, but mainly because the <img class="inline knockback"> [Knockback] is especially dangerous when combined with [Chorus of Thunder], [Fluxlances] and [Fulgent Fences].

Decima casts this skill regularly as part of her attack loop. Furthermore, she also casts this skill as part of her Seismic Reposition, which is essentially identical but also has a movement component.

---


## Effects

### <img class="inline galvanic-sensitivity"> Galvanic Sensitivity

An effect that is applied to players hit by [Fluxlances], lasting for 30 seconds. Greatly increases damage taken from [Dancing Sparks]. <img class="inline galvanic-sensitivity"> [Galvanic Sensitivity] is incompatible with <img class="inline harmonic-sensitivity"> [Harmonic Sensitivity], which it overwrites.

---

### <img class="inline harmonic-sensitivity"> Harmonic Sensitivity

An effect that is applied to players standing inside Decima's <img class="inline thrumming"> [Thrumming Presence], lasting for 30 seconds. Greatly increases damage taken by [Fluxlances]. <img class="inline harmonic-sensitivity"> [Harmonic Sensitivity] is incompatible with <img class="inline galvanic-sensitivity"> [Galvanic Sensitivity], and cannot be applied to players affected by <img class="inline galvanic-sensitivity"> [Galvanic Sensitivity].

---

### <img class="inline charge"> Charge

A stacking effect that is gained by Decima every time she consumes [Dancing Sparks]. Increases all outgoing damage from all of Decima's attacks. If Decima gains 10 stacks of <img class="inline charge"> [Charge], she becomes <img class="inline enrage"> [Unstoppable](https://wiki.guildwars2.com/wiki/Unstoppable_(Decima)) and <img class="inline invuln"> [Invulnerable], after which she then **instantly defeats** all players.

Decima loses all stacks of <img class="inline charge"> [Charge] when she performs her [Flux Nova].

---

### <img class="inline harmony"> Peal of Harmony

A stacking effect that determines the number of [Conduits] that Decima targets during her [Chorus of Thunder]. Decima starts the fight with 5 stacks of <img class="inline harmony"> [Peal of Harmony], and gains a stack every 5% of her HP.

---

### <img class="inline discord"> Peal of Discord

A stacking effect that determines the number of players that Decima targets during her [Chorus of Thunder]. Decima gains 5 stacks of <img class="inline harmony"> [Peal of Harmony] every 10% of her HP.

---

[Harmonic Sensitivity]: #-harmonic-sensitivity
[Galvanic Sensitivity]: #-galvanic-sensitivity
[Charge]: #-charge
[Fluxlances]: #fluxlances
[Thrumming Presence]: #thrumming-presence
[Dancing Sparks]: #dancing-sparks
[Peal of Harmony]: #-peal-of-harmony
[Peal of Discord]: #-peal-of-discord
[Conduit]: #conduits
[Conduits]: #conduits
[Flux Nova]: #flux-nova
[Chorus of Thunder]: #chorus-of-thunder
[Thunder]: #chorus-of-thunder
[Seismic Crash]: #seismic-crash
[Seismic Reposition]: #seismic-crash
[Fulgent Fences]: #fulgent-fences

[Unblockable]: https://wiki.guildwars2.com/wiki/Unblockable
[Blocked]: https://wiki.guildwars2.com/wiki/Block
[Evaded]: https://wiki.guildwars2.com/wiki/Evade
[Exposed]: https://wiki.guildwars2.com/wiki/Exposed
[Invulnerable]: https://wiki.guildwars2.com/wiki/Invulnerability
[Invulnerability]: https://wiki.guildwars2.com/wiki/Invulnerability
[Invulned]: https://wiki.guildwars2.com/wiki/Invulnerability
[Stunned]: https://wiki.guildwars2.com/wiki/Stun
[Knockback]: https://wiki.guildwars2.com/wiki/Knockback
[Stability]: https://wiki.guildwars2.com/wiki/Stability


