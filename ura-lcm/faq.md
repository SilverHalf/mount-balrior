---
layout: page
title: FAQ
nav_order: 2
parent: Legendary Ura
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn } [Strategy Guide](./strategy.html){: .btn }

# Legendary Ura Frequently Asked Questions

This page contains a set of frequently asked questions regarding the Legendary Ura encounter. These are grouped into four sections:

1. [Ura's Attacks and How to Deal with Them](#uras-attacks-and-how-to-deal-with-them)
2. [Ranged Group and Toxic Geysers](#ranged-group-and-toxic-geysers)
3. [Phasing and Related Issues](#phasing-and-related-issues)
4. [Titanspawners, Fumarollers, Ventshots](#titanspawner-fumarollers-ventshots)
5. [Builds, Composition and More](#builds-squad-compositions-and-more)
6. [Glossary](#glossary)

<img class=divider>

## 1. Ura's Attacks and how to deal with them

<details class=faq>
<summary>1.1 - How, who, where to kite Ura jumps in p1?</summary>
<div markdown='block'>

Ura targets the furthest player within 1500 range, so in order to kite, you just need to be the furthest away. It’s best if all healers (<img class='inline chrono'> [Chronomancer], <img class='inline scourge'> [Scourge], <img class='inline deadeye'> [Deadeye]) are aware of how and where to kite, so they can provide some redundancy and know how to react if they are out of place.

Ura's jumps should roughly follow the [Toxic Geysers], as shown below (The numbers with the white background next to the black arrows are the order of the jumps; 1, 2, 3, …; you can see that you essentially kite Ura back and forth). Importantly though, you want to kite so that Ura does not jump into Toxic Geysers, as that will give her boons. You want her to be close to the geysers, but outside of the boon range.

<img class='center' src='../images/ura/ura_propel_p1.webp' width='70%'>

{: .note}
Boons from Toxic Geysers are only given in the initial radius and not in the extended radius when they grow.

If you are in a situation where you are doing a Toxic Geyser in a bad position and you know Ura will jump soon, you can try to quickly move closer to Ura so the other healers can bait her properly, or move out of her 1500 range so you aren’t targeted.

Depending on your damage and whether Ura gets CC'd, you might want to bait slightly differently and not exactly like shown. You can just follow the general principles of: 
1) Follow Toxics.
2) Make sure to not make her jump into Toxics.
3) After the last jump, stand southwest of Ura to make her face that way (more info on that below).

</div>
</details>

<details class=faq>
<summary>1.2 - How, when and why to CC Ura correctly?</summary>
<div markdown='block'>

Ura builds up <img class='inline risingpressure'> [Rising Pressure], which gets removed when you CC her. This also gives her a stack of <img class='inline titanicresistance'> [Titanic Resistance], which reduces incoming CC damage. This means that you want to CC Ura whenever she gets to roughly 5-6 stack , in order to keep the damage reduction low on average, while also not getting overwhelmed by high <img class='inline titanicresistance'> [Titanic Resistance] stacks.

Whenever Ura is CCd, her attack will be interrupted and she will immediately start casting the next attack. Ura’s attacks are on a priority list, with cast times, aftercasts and cooldowns. She will go down her priority list and cast the next skill that is available (if a target is in range). If you CC at the wrong time, you can remove cast and aftercast from a skill, which will cause Ura to run out of attacks and then use [Propel]. That’s why we want to CC at the end of aftercasts, in order to minimize the chances of Ura jumping away. For more information see [when to CC Ura](../ura/mechanics.html#when-to-cc-ura).

The best CC timings are (gifs from Elise):

[Steam Prison] - After her hands are down. Roughly 3 seconds time window after hands are down.

<img class='center' src='../images/ura/ura-cc-donutmove.gif' width='70%'>

[Create Titanspawn Geyser] - after she is in the air. Roughly 4-5 seconds time window after she is in the air.

<img class='center' src='../images/ura/ura-cc-jumpslam.gif' width='70%'>

[Sulfuric Geyser] - Once the indicators start, which is roughly when she has stretched her arm out front fully. About 2-3 seconds of a window.

<img class='center' src='../images/ura/ura-cc-sulfanim.gif' width='70%'>

</div>
</details>

<details class=faq>
<summary>1.3 - How, when and who tanks Ura?</summary>
<div markdown='block'>

Ura needs a tank from Phase 3 (40%) onward. The reason for this is that in Phase 2 she cannot use [Propel], but she can use it again in Phase 3 and 4. You need a tank for Ura such that Ura is able to cast attacks other than Propel. If no one is in front of her, she casts [Propel], because all other attacks require a target in front of her (i.e. she goes down her priority list and if no target is available, goes to the next attack etc.. which brings her to the only attack that doesn’t require a target in front of her, which is Propel).

The tank can be any dps, or any player in general. There is no real “tanking mechanic” per se, like nothing to do with Toughness or anything, it’s just that Ura needs any player in front of her to cast abilities other than Propel.

The Line of Sight from Ura is roughly a 140° cone: see the shaded area below. The cone is decently wide and the tank just needs to stay within that cone. See [tanking Ura](../ura/mechanics.html#tanking-ura) for more information.

<img class='center' src='../images/ura/ura-cone.webp' width='70%'>

</div>
</details>

<details class=faq>
<summary>1.4 - How to turn Ura to the correct side?</summary>
<div markdown='block'>

Turning Ura is a bit finnicky. She only turns when she casts [Steam Prison] or [Sulfuric Geyser]. For both casts she will turn toward a random target and follow them for the duration of the cast. This means that she actually can spin 180° to one of the [Toxic Geyser] group: in these situations it’s crucial for the tank to notice this and quickly run back into her cone of vision.

You can use this to turn Ura by having everyone except the tank go to the side where you want Ura to turn, which gives you a high probability that she will turn once Arena/Sulfuric is used.

Other than that, the tank can try to slowly rotate Ura by standing on one side at the end of Ura’s cone of vision and rotate her in small steps.

</div>
</details>

<details class=faq>
<summary>1.5 - How come I'm getting <img class='inline exposed'> Exposed?</summary>
<div markdown='block'>

When <img class='inline sulfuricacid'> [Sulfuric Acid] ticks for 5 seconds, it will turn into <img class='inline exposed'> [Exposed]. You can get <img class='inline sulfuricacid'> [Sulfuric Acid] from many different attacks: standing in [Toxic Geysers] and [Sulfuric Geysers] if you have too many <img class='inline poison'> [Poison] stacks, from Ura’s [Acid Spray] (used when she has no melee target), and from the waves that get released from [Sulfuric Geysers].

In order to prevent getting exposed, you need to cleanse <img class='inline sulfuricacid'> [Sulfuric Acid], which can only be done one stack at a time. That’s why bringing extra cleanse on DPS is so important, so that you have many different skills that cleanse the group in order to minimize <img class='inline exposed'> [Exposed].

</div>
</details>

<details class=faq>
<summary>1.6 - Where do I drop Sulfurics?</summary>
<div markdown='block'>

Looking at the image below, good places are the purple areas, so basically outside of the part of the area that is covered with [Toxic Geysers] and additionally specifically not behind 1 and 2 (except for the ranged group if they are close there). The reason for this is that the purple areas below area reachable from the boss, but behind 1 and 2 is not reachable.

<img class='center' src='../images/ura/ura_sulfurics.webp' width='70%'>

Additionally, within those areas, it’s better to drop Sulfurics between Geysers where NO double drops are happening. Example: #13 and #14 are always double dropped, so ideally don’t go between them, but #12 and #14, or #10 and #13 are not, so it’s better to drop between those. The absolute best area to drop them is behind #9, which, as can be seen from the image, is the shortest path from Ura.

</div>
</details>

<details class=faq>
<summary>1.7 - Is it worth stacking Sulfuric Geysers?</summary>
<div markdown='block'>

Yes, but they can very quickly kill you if you are not careful. Rule of thumb is that on a non-healer you can stack a maximum of two [Sulfuric Geysers] (i.e. you run into only one existing and drop yours on top) and on a healer it depends if you have many cleanses or defensive skills available. <img class='inline chrono'> [Chronomancer] has it the easiest, because you can press <img class='inline distortion'> [Distort] and ignore all incoming damage and conditions.

</div>
</details>

<details class=faq>
<summary>1.8 - What attacks should I dodge?</summary>
<div markdown='block'>

Generally, dodge [Create Titanspawn Geyser] (the stomp/jump in the air from Ura) and [Propel] (jump) when she lands. Try to sidestep or dodge the final cone of her [Autoattack Chain]. Other than that you can jump, block or dodge the waves from [Sulfuric Geysers]. You can also double dodge out of the [Steam Prison] with the right timing (or with <img class='inline superspeed'> [Superspeed]), if you don’t have a mobility skill and no <img class='inline stability'> [Stability]. You can dodge [Sulfuric Geyser]/[Toxic Geyser] AoEs to prevent the damage ticks, but this is not as important.

</div>
</details>

<details class=faq>
<summary>1.9 - Can you give <img class='inline stability'> Stability to people in bubbles?</summary>
<div markdown='block'>

No, the people targeted by the mechanic get <img class='inline stability'> [Stability] removed if they have it beforehand, and cannot receive it again during bubbles, until they're <img class='inline dispel'> [Dispelled]. This means that players in bubbles can get knocked by [Champion Fumarollers], which can lead to displaced bubbles.

The white indicator on the floor is misleading in these situations, because it only shows the initial bubble position, and does not get updated when knocked, but <img class='inline dispel'> [Dispel] only works if the shard is dropped underneath the bubble. In such cases immediately call out in voice that the shard needs to be dropped again.

</div>
</details>

<details class=faq>
<summary>1.10 - How do I deal with bubbles in this situation?</summary>
<div markdown='block'>

#### I have bubble at the same time as the Titanspawner

The [Bloodstone Shard] always MUST to go to the [Titanspawner], this means that the bubbles also MUST go to the Titanspawner. General rule of thumb is to always do bubbles next to the Titanspawn when both are up.

#### I have bubble at the same time as the Titanspawner and the second bubble is tank

In this case they should call for a backup tank immediately and run to the Titanspawn. Usually there is always someone who can backup tank for a bit, like a DPS from the ranged team, or one of the healers.

#### I have bubble but I am far running back from [Sulfuric Geyser]

Just like the case above with the ranged being far away, call it out immediately with the direction and meet in the middle.

There is one specific possible scenario where you get Sulfuric > phase 40% to p3 > Sulfuric person gets the bubble. This is very unlucky timing and it’s a difficult situation to solve. The second bubble has to run out to the Sulfuric person together with the melee who has the bloodstone shard (and the one who is supposed to pick up) in order to save them. Otherwise they will likely die and it’s a wipe.

</div>
</details>

<img class=divider>

## Ranged group and Toxic Geysers

<details class=faq>
<summary>2.1 - Who should be double dropping?</summary>
<div markdown='block'>

All healers: <img class='inline chrono'> [Chronomancer], <img class='inline deadeye'> [Deadeye] and <img class='inline scourge'> [Scourge] generally. There is an edge case where the DPS that helps the ranged team also has to double drop, which can happen in the p2 to p3 transition if Toxic Geyser #5 or #6 spawns. In that case the dps has to double drop #8 and #9, but otherwise only the healers double drop.

</div>
</details>

<details class=faq>
<summary>2.2 - Which Toxic Geysers are double dropped?</summary>
<div markdown='block'>

Essentially almost all of them. Please check a [ranged rotation](strategy.html#ranged-rotation) for more information.

</div>
</details>

<details class=faq>
<summary>2.3 - What Toxic Geysers should be done in the final phase?</summary>
<div markdown='block'>

All should be done up to #14. After that, everything else can be safely ignored, except for #8 and #11 if you get them. Please check a [ranged rotation](strategy.html#ranged-rotation) for more information.

</div>
</details>

<details class=faq>
<summary>2.4 - Are there differences in doing Toxics in p3 and p4?</summary>
<div markdown='block'>

Not mechanically speaking, but exceptions apply for the last few [Toxic Geysers] of Phase 4. Toward the end when you only have geysers #12, #13 and #14 left, you don’t need to do them immediately since at that point you aren’t doing the rest. So you can take your time and do those whenever it is convenient, which is generally when your squad is healthy and there are no important mechanics happening (such as CCing the boss).

After #14, the next Toxic Geysers that become relevant are #8 and then #11. If you have high enough damage, those won’t matter, but if they do, have your <img class='inline chrono'> [Chronomancer] (and someone else if needed) prepared to immediately CC #8 when it spawns (you can estimate the timing by looking at when 6 and then 7 spawn). Depending on Ura’s HP, either she will die very soon and you can ignore #8 after CCing, or you want to drop a shard there (e.g. by using Scourge Sandswell to quickly get there and back again). If damage is low enough to where you get #11, just immediately drop the shard (and pick it up again) and kill it with DPS, since the squad is usually stacking on that spot. Otherwise, the <img class='inline chrono'> [Chronomancer] should immediately CC it.

</div>
</details>

<details class=faq>
<summary>2.5 - What is the advantage/disadvantage of having a DPS help the ranged group?</summary>
<div markdown='block'>

Having a DPS help makes the ranged rotation easier to deal with. The limiting factor is the duration of the <img class='inline saturation'> [Bloodstone Saturation] debuff from using <img class='inline dispel'> [Dispel]. The disadvantage is that it is better to have a DPS with blink skill, which limits the playable classes. More information on this strategy can be found here: [NA Pug Rotation](mechanics.html#na-pug-rotation).

Playing with 3-heal ranged is harder to execute, as the duration of <img class='inline saturation'> [Bloodstone Saturation] makes it tighter. The advantage is slightly higher DPS on the boss and that you can have 2 tanks instead of 1. More information on this strategy can be found here: [3-Heal Rotation](mechanics.html#na-pug-rotation).

</div>
</details>

<details class=faq>
<summary>2.6 - How to deal with bubbles, sulfuric and cage when double dropping?</summary>
<div markdown='block'>

- [Pressure Blast] - Quick reactions, depending on the situation you might want to call out for the next person in the rotation to free you on the next Geyser, or that you'll run back to the group.
- [Sulfuric Geyser] - Always has high priority and needs to be placed correctly. If you are supposed to do a double drop, and you just used <img class='inline dispel'> [Dispel] and then got targeted by the sulfuric, just leave the shard on the ground, place the geyser, and tell the group that the shard will tick two or three times so they can play safe and heal accordingly.
- [Steam Prison] - Place it so that it does not overlap any [Toxics Geysers] that you want to do, while also moving away from melee range such that the squad can still move around the boss. The arena reflects projectiles, which means the <img class='inline deadeye'> [Deadeye] cannot CC, because Spear 4 (the CC skill) is a projectile. There are situations where e.g. the <img class='inline deadeye'> [Deadeye] has already CCd one Toxic and you are supposed to double drop when you get the arena. In those cases you can just go to the Toxic, <img class='inline dispel'> [Dispel], place the arena there, pick up and move to the second Toxic. This is fine if and only if the first Toxic has been CCd already, cause then the projectile reflects don’t matter (and you can simply outheal a few ticks on yourself from being inside the arena).

</div>
</details>

<details class=faq>
<summary>2.7 - I have a shard that I am supposed to drop, but I just got bubble!</summary>
<div markdown='block'>

First of all, while holding the [Bloodstone Shard], you are immune to [Pressure Blast] and you also can't get targeted by it. If you just <img class='inline dispel'> [Dispelled], then get a bubble, and you are supposed to double drop, then you can just wait 2 seconds and then pick up the shard again to ignore the bubble and just outheal the tick from it. <img class='inline dispel'> [Dispel] again the bubble is over and you are on the next Toxic.

If you are Supposed to pick it up, but your buddy has not dropped it yet, you can call that they should free you on top of the geyser they need to <img class='inline dispel'> [Dispel].

</div>
</details>

<details class=faq>
<summary>2.8 - I have a shard that I just dropped but I just got bubble and group is far!</summary>
<div markdown='block'>

Immediately call out that bubble is far away (and the direction if possible) and then use your movement skills if you have any available. In principle, the 2 bubbles should meet in the middle if both are far from each other.

</div>
</details>

<details class=faq>
<summary>2.1 - I have to <img class='inline dispel'> Dispel but another ranged player near me has a bubble!</summary>
<div markdown='block'>

If you are holding the [Bloodstone Shard] and a range buddy next to you has the bubble, then just free them when you <img class='inline dispel'> [Dispel]. Depending on the situation, you may have to just wait a couple of seconds until they are bubbled, and only then should you drop. Remember to spam your healing skills on top of yourself to negate the incoming damage from <img class='inline saturation'> [Bloodstone Saturation] in case you already have a stack.

</div>
</details>

<img class=divider>

## Phasing and related issues

### What is the issue with CCing around 40%? 

On 40%, Ura transitions from Phase 2 to Phase 3. This causes her to interrupt herself. Similar to bad CC timing, this can lead to an unlucky self-interrupt timing that can cause a jump. There is not really a whole lot that you can do about that, because controlling dps to phase at a good time is very hard. However, what is good to do is to not CC her shortly before, or after, because if you do, that’s two CCs in a short time (once from the squad, once from her self-interrupt), which can increase the chance of her running out of attacks to use and then consequently use Propel (the jump).

---

### What are the biggest issues while phasing?

- P2: nothing specifically, except if you have low dps, then Toxic Geyser 12, 13, 14 can be an issue (see next question below).
- P3: Ura will self-interrupt and the Toxic Geyser timer instantly resets to 0 and Toxic 7 will spawn (this means it’s a bit more hectic for the ranged team). Additionally, Ura will immediately cast Bubbles/friends as the first skill in P3. This is usually the most difficult transition, because it starts from being very chill in p2 to suddenly being very hectic with lots of mechanics.
- P4: self-interrupt, but otherwise nothing in particular. The self-interrupt is less of an issue, because Ura will also spend a few seconds in a phasing animation.

---

### 1st phasing 70% - How to deal with 10. and 11. (12.) And 8. Toxic spawn? 

Depends on strategy, please refer to a ranged rotation spreadsheet, or ask for a specific strat.

But generally if you have low dps and you get 13 + 14, you might even just want to /gg and practice p1, since your whole rotation will be thrown off. If just 12 and 13 spawn extra, the CC DE can CC those to reset the aoe until they are done normally during p2. Realistically this should only happen very early into 0 exp prog. Even after a couple of pulls you should phase fast enough to get max 12. If not, you might have a dps issue in general and won’t be able to kill Ura within the enrage timer (i.e. this is also a nice self-squad check to see if the overall dps is good enough – just remember specifically for this that depending on the dps, you might have some extra modifiers at high/low hp percentages; but it works as rule of thumb).

---

### 2nd phasing 40% - How to deal with 7. And 8. Toxic spawn?

Depends on strategy; please refer to a ranged rotation spreadsheet, or ask for a specific strat.

---

### Is there any issue while phasing p4?

Phase 4 transition also self-interrupts Ura, so it can happen to also cause a jump if she self-interrupts at a very bad timing. However, due to the phase 4 transition also causing an animation for Ura, it’s a little bit less likely than for the p2>p3 transition.

<img class=divider>

## Titanspawner, Fumarollers, Ventshots

### How does Titanspawner and Ventshot work?

Titanspawner Geysers are created every time Ura uses her Create Titanspawn ability (Orange Circle around her and jump/stomp in the air). The Titanspawners in p2/p3 are the same as in p4, but while p2/p3 is active, they will spawn Champion Fumarollers, while in p4 they will spawn Legendary Ventshots. Additionally, when Ura hits 1% and heals, she will always spawn an additional Titanspawn Geyser independent of her Create Titanspawn Geyser skill.

More details here: https://silverhalf.github.io/mount-balrior/ura/mechanics.html#titanspawn-geysers

---

### When is a good time to stop killing Titanspawners?
It depends on the squad. Stopping to kill Titanspawn Geysers during p3 can be very dicey, because multiple Fumarollers alive can very quickly down and wipe you. If you play with 2x Heal Chronos, you can outheal/stab that and stop killing Titanspawners roughly after 15%. This will reduce the number of Ventshots you get down to ~2 during p4, which means you will likely not wipe if projectile block fails.
However, if you play with only one Chrono and one hybrid Scourge, then it’s not recommended to stop killing Titanspawn Geysers in p3. In that case just stop doing them in p4, except if the first Titanspawn Geyser in p4 is directly next to the squad. In that case you can quickly kill it. Ignore all other Titanspawners after the first in p4.

---

### What is the biggest issue when letting Fumarollers run around and how to deal with it?

The dangerous part is that Fuma attacks hit quite hard and that combined with Stars/Snowflakes can quickly down and kill you. The longer they live, the higher the chance that they spawn another star under the boss. That’s why you generally want to kill them as quickly as possible, like so: 1) Fuma spawns on titanspawner, 2) bait the Fuma to the boss (standing 90°/tangential at the boss), and 3) after Fuma has charged, move on top of it and cleave it down asap.

The only exception to killing them immediately is for some specific strategies in which you want to keep Fumas alive for as long as possible at the start of p4, in order to get less Ventshots (this works because Ventshots, Titanspawners and Fumarollers have an entity cap, such that when too many are on the field, no new entities will spawn). But this is quite dangerous, because multiple Fumas alive can kill you quickly. The cap is currently believed to be at ~6 for Ventshots, which means that if you have 6 entities from Titanspawners + Fumarollers alive, that no Ventshot will spawn.

For kiting, you can watch the Fumas and bait them into the stack before running out for Toxic Geysers; the baiting part works, because Fumas target the highest Toughness player with their charge attack that is in their cone of vision. This makes it relatively easy to bait them as healers to the squad; in that way they also won’t bother you at range. Sometimes there is no time to wait for this, in that case just avoid as much damage as possible, by e.g. using Dodge/Distort and healing yourself in case you take damage.

Generally, you want the Fumarollers to charge as quickly and as close as possible to Ura and then you want to immediately cleave them down, before they cast a star/snowflake on the boss. If they do cast one, just move out of it as quickly as possible. If someone downs, everyone needs to immediately ress, because downing on top of a star/snowflake can very quickly kill you.

Fumarollers don’t need to be CCd. They can be CCd just from passive AoE CC, but there is no specific need to pay special attention to it.

The melee team who kills the Titanspawner should always have some stability (e.g. from the qfb) when they go kill the Titanspawner, such that they don’t immediately get knocked. Once the Fumaroller is on the group, also make sure to use Stability. The star attack knocks back three times, while charge, roll and headbut knocks once each.

---

### How to deal with Venshots?

After having 2+ Ventshots, keep projectile block up on the group permanently and try to keep up Stab as well. Ventshots can kill you either with ranged attacks when projectile block is down, or with melee attacks (that also knock you) when they are close to the squad. 

As Chrono with Stab Mantra and Precog, you can this rotation for permanent Stability from Schwifty: https://www.youtube.com/watch?v=ZNt3AbNwiuw

---

### There are multiple strategies for Titanspawners: What is an advantage and disadvantage of power/all dps taking care of titan spawn?

The reason why Power dps on Titanspawner has an added advantage is because Titanspawners have low armor and hence take extra Power damage and combined with no ramp-up which is typical for most power builds, they can pretty quickly, which mitigates the possibility of having a second Fumaroller spawning. Burn-based condition builds are also pretty strong due to their relatively short ramp-up. Note that Conditions can be stacked on the Titanspawner Geyser while it’s still invulnerable.

All dps (and QFBs) on the Titanspawner has the advantage that the group stays together (except for the los tank), but it has the disadvantage that when the los tank gets bubble, there is a chance that no backup tank is available which means the tank cannot move to the Titanspawner quickly. One way to circumvent this is by having only the melee group who do the Bloodstone Shard rotation be on the Titanspawner, which means you will always have multiple people los tanking and there is no need to call for a backup tank if someone gets a mechanic. The downside for this is that the squad is split into two, so if someone starts downing for whatever reason, ressing takes longer.

Generally either way works good enough and you can pick on personal preference and/or if you have Power dps available or not.

---

### In case of power dps taking care of Titan - How many people and what class should be sent there?

For simplicity it’s best to send the full melee shard rotation group there, because then you will always have the players who need to drop and pick the Bloodstone Shard on the group. This should be a QFB and 3x dps. 1x Power dps and 2x Condi dps, or having at least 2x Burn-based Condi dps (Weaver, Willbender, Firebrand) is usually enough to make sure the 4 players from the melee group can kill the Titanspawner comfortably in time.

<img class=divider>

## Builds, Squad compositions and more

### What are available builds?

#### CC Deadeye

For the most part there is only one specific build, but some small variations are possible. Depending if you are tunneling or not, you can play with/without weapon swap.

NOTE: Depending on if you need to provide Fury/Might, or not, you can choose between Relic of the Midnight King (for Fury/Might), or Relic of Speed (permanent Superspeed if boons aren’t needed).

- Default build with weapon swap (Quick Pockets): https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oivMapCCLFc82gK0HUB-e
- Tunnel variation without weapon swap (Sleight of Hand; Note that you can also run a different stacking Sigil, like Perception for more Precision if critting is an issue for Init regen): https://gw2skills.net/editor/?PagEQjWWADkJx2Ym4xad92A-DyIY1oi/QaRJEmEomRgjuKoC9BVA-e

---

#### Heal Chronomancer

The last util skill is flexible and can be taken based on personal preference, or to fill the gap where your squad is likely needing it the most:
- Blink is nice for early prog to cover up mistakes and when being late with mechanics, which can help your group to prog faster early on. It is also useful to blink and bait Ura into a specific direction when CCing at the wrong time (but that requires fast anticipatory reactions).
- Feedback and the trait Medic’s Feedback give you some ranged ress power and allow you to backup projectile blocks in p4.
- A CC skill (Technobabble, Signet of Domination, Well of Senility) can be useful to quickly solo CC Toxic Geysers from range (otherwise solo CC with Moa + Spear 5; or with Rifle4 + Moa, but the latter requires very good timing). This can be useful when the CC DE is not that experienced yet, and in general to support CC more (both Toxics and Boss).
- Well of Precognition is in the default build (below), but if you are paired with a Quick Firebrand who has Stab and is comfortable with it, then you could also drop Well of Precognition and use two of the utilities mentioned above.

Note that there have been plenty of kills with all different kind of utility variations and the different utility skills can fill different needs. Hence, there is not a clear go to that is the best for all situations.

Build (if tunneling, just swap Concentration to Sigil of Life on the Spear): https://gw2skills.net/editor/?PigEQiWmBzCrhNiH9karD-DSRYjR1VPSIFlRLpQ6VluvGCSo83S7bWQFA-e

---

#### Celestial Hybrid Scourge

There are a few different build options to run as Scourge. This mostly depends what your group needs, or is comfortable with, in terms of balancing offensive vs defensive.

- Offensive: Curses + Soul Reaping; advantage is you have low cd on CPC, which means 1x scg + 1x qfb can take care of reflect and the rest is additional backup and higher dps. sword offhand for extra movement; downsides is less healing and no Stability, so when running this you want lots of Stability from your Quick Firebrand: https://gw2skills.net/editor/?PSAFo8FbYZGsPGILiNiF711rH-DyIY1on/M6SKkrKQh/KGSQsHeNB4BDUB-e
- Middle ground: play the offensive one with Trail of Anguish instead of Blood is Power, if you want to have a Stability skill available.
- Defensive: Blood Magic instead of Curses; has more healing and more Stability/boons; downside is that not running Curses means longer CPC cd, which means you need to account for either a more difficult projectile block rotation that involves more people, or better you need at least 2 Firebrands that can do the projectile block rotation and Scourge is just a backup with CPC – Note that one qfb with Wall of Reflect + F3-3 and then a second Firebrand with just F3-3 is enough for the basic projectile block rotation: https://gw2skills.net/editor/?PSwAo+ZlZwiYfsH2ImqXXveA-DyIY1oj/U6SCkqIIXFQ6CBD/rYIBxe41AiHMQFA-e

---

####  Condition Quickness Firebrand

There are a few variations possible that mostly depends on what your squad needs (the first 3 builds are around ~2.7k to 3.7k lower lower than the SC bench; the last build is around ~6.3k lower; see screenshot below):
- Wall of Reflection (Trapper runes; ~3.7k dps loss); is needed once per squad and should call the Projectile block rotation with Wall + F3-3 + fill – where the fill is either Scourge CPC, or another Firebrand F3-3: https://gw2skills.net/editor/?PWyAo+rlRExe6ZQBttkGZkW0WbPTA-DSJYyRL/hkjkKBFQHCBF+r4IBxW41AiPNQFA-e
- Some Stability FB; Elite Mantra is recommended due to higher dps:
    - Elite Stab Mantra (Firebrand runes, but still purging flames; ~2.7k dps loss); trades the SYG from the build above for Elite Mantra; loses the Superspeed from FMW, but gains the condi cleanse from PF and a group stunbreak on Elite Mantra: https://gw2skills.net/editor/?PWyAo+rlRExe6ZQBtukmZkW0WbPTA-DSJYyRL/hkjkKBFQHCBx+r4IBxW41AiPNQFA-e
    - FMW + Stand Your Ground (Trapper runes; ~3.7k dps loss); has the advantage of still having FMW for Superspeed to quickly run to the Titanspawners; use SYG for Titanspawn and F3-5 for Arena: https://gw2skills.net/editor/?PWyAo+rlRExe6ZQBNskGZkW0WbPTA-DSJYyRL/hkjkKBFQHCBF+r4IBxW41AiPNQFA-e
- Stab bot: Elite Stab Mantra + Stand Your Ground (Firebrand runes; ~6.3k dps loss); trades even more dps for more Stability, which can be done if people in your sub get knocked around a lot (e.g. in the offensive Scourge subgroup when the Scourge has no Stability): https://gw2skills.net/editor/?PWyAo+rlRExe6ZQBNskmZkW0WbPTA-DSJYyRL/hkjkKBFQHCBx+r4IBxW41AiPNQFA-e

![qfb-numbers](../images/ura/qfb-numbers.webp)

---

#### DPS builds

DPS builds always depend on the current Meta, so it’s best to just look at the build section on the Void Lounge discord, but a current snapshot (August 2026) is: Condi Weaver, Willbender, Daredevil, Mechanist, Firebrand & Power Scrapper, Berserker, Vindicator: https://discord.com/channels/1121166847266537562/1332712612877570089/1360699762143137963

---

#### What are important skills DPS should take?

Depends on the spec, but general condition cleanse, stability and movement skills are nice if they don’t cost that much dps and if you are not struggling with dps. Examples are:
- Willbender: Virtues traitline, middle column, take the middle trait => lots of additional condi cleanse with F2 at a very minor dps loss
- Mechanist: Healing Turret for aoe condi cleanse
- Weaver: lightning flash for mobility instead of fire elemental (generally it’s always worth to have good sulfuric placements over some dps)
- Scrapper: can take the Stab on Function trait in the first column of the Scrapper traitline, but note that you have less party Superspeed then

---

### What are the best ways to CC on the support classes?

- For CC DE, check out this amazing guide from Chupa: https://docs.google.com/presentation/d/19xXTt8iPkvoDVG_I_TEQOd_Xyw4R6ZdB90SOWWzzh4M/edit?slide=id.p#slide=id.p
- Chrono: Moa (+ any other skill from weapon or util you might have) and depending on the situation also don’t be afraid to use those within CS if you anticipate needing CC again soon after.
- Scourge: Golem
- QFB: Pistol 5 (but generally don’t hold it) and F1-3 (is relatively little CC though).


---

### Who is the main provider of stability?

It depends on the squad composition, how much Stability you are running and on the situation; so generally there is not one main Stability provider. But the Chrono has Stab Mantra and should always pay attention to mechanics and use a charge whenever there is a mechanic (Titanspawner, Arena, Fumaroller) and when running Precognition can also drop those onto the group at the Titanspawner, or on the squad when a Fumaroller is alive. Scourge and Qfb have varying amounts depending on the build, but should similarly use them whenever needed and they are in range (e.g. Stand Your Ground when the group runs to the Titanspawner and F3-5/Elite Mantra for Arena and Fumaroller attacks. So summarizing, whoever has Stability should always use it for mechanics if they are at the squad, or wherever the mechanic is happening (e.g. while the Chrono has obviously the most amount of Stability if they run Precog, this doesn’t help when they are on ranged shard duty away from the squad, at which point the Qfb needs to provide the Stability).

---

### What are possible compositions?

The two main compositions are relatively similar and only come down to Scourge, or Chrono as second healer and what specific build the QFB runs.

Scourge comp: higher dps, but less healing/stability

| CC DE       | Hybrid Scourge* | QFB (Stab**) | dps (los tank) | dps (ranged bu) |
| -- | -- | -- | -- | -- |
| Heal Chrono | QFB (Wall, marker) | dps | dps | dps |

*If defensive, then the two QFBs should do the basic projectile block rotation, while having the CPC from Scourge as backup whenever needed.
**If confident, can also drop the SYG and still run PF, especially if the Hybrid Scourge plays the defensive version with Trail + Staff for Stability.

Double Chrono comp: higher dps, but less healing/stability

| CC DE       | Heal Chrono | QFB (Wall, marker) | dps (los tank) | dps (ranged bu) |
| -- | -- | -- | -- | -- |
| Heal Chrono | QFB*     | dps | dps | dps |

*The PF QFB can either still run Elite Mantra with Purging Flames to have some more Stability, or fully offensive with the default SC build (only F3-5 then for Stability).

The dps can in principle be any dps of the builds mentioned above in the dps build section. One notable distinction is that if you run a full Condi comp, everyone in Sub2 (QFB + 3 dps) should go kill the Titanspawner Geyser, while with Power dps, only 2x Power dps are required to go there to kill it in time

---

### How to assign dps for melee rotations and Titanspawners?

Titanspawner and melee rotation: The melee shard rotation consists of 4 people (e.g. everyone except the Healer in Sub2 => QFB + 3 dps) and hence all of them can go to the Titanspawn Geyser, such that you always have the melee Bloodstone Shard person there and the Stability from the QFB for the Fumaroller (F3-5/SYG/Stab Mantra, depending on the build you run). Having at least one Power dps in this group helps with killing the Titanspawn Geyser more quickly. If you run a full Condi composition and have problems killing it in time, then you can have the QFB from Sub1 and the dps (ranged bu) also go and dps the Titanspawner (which leaves only the los tank at the boss).

### Is it possible to have a different quick dps?

Other quickness builds are technically possible to run if there is no need for specific skills (e.g. projectile block, Stability, ..), but QFB is generally the best choice due to high dps combined with the massive amount of utility it brings. If in doubt, just check your squad composition and make sure everything is covered.

<img class=divider>

## Glossary

Arena: Donut/Cage/Prison refers to Ura’s Steam Prison attack that shows up as a donut-shaped orange indicator around a player and spawns a circular boundary. After spawning, it can only be escped by having Stability, or via blinking over it. Inside, it ticks damage, applies Sulfuric Acid and reflects all projectiles.

Bubbles: Bubbles, or the “Friends” mechanic refers to Ura’s Pressure Blast attack that applies 2 small circle indicators to random players (who don’t hold a Bloodstone Shard at the time of casting), which will trap those players and anyone else caught in the explosion radius in floating bubbles that slowly rise.

Titanspawner: Refers to the Titanspawn Geyser that appears when Ura casts “Create Titanspawn Geyser”. Spawns Fumarollers, or Ventshots depending on the phase.

Fumas/Fumarollers: Refer to the Champion Fumaroller adds that spawn from Titanspawn Geysers during phase 2 and phase 3.

Ventshots: Refer to the Legendary Ventshot enemies that spawn from Titanspawn Geysers during phase 4.


<img class=divider>

[Return to Home](../index.html){: .btn } [Return to Overview](overview.html){: .btn } [Return to Top](#ura-faq){: .btn .fixed}
{: .center}

[Chronomancer]: strategy.html#builds-and-povs
[Deadeye]: strategy.html#builds-and-povs
[Scourge]: strategy.html#builds-and-povs

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
[Titanspawner]: ../ura/mechanics.html#titanspawn-geysers
[Create Titanspawn Geyser]: ../ura/mechanics.html#titanspawn-geysers
[Pressure Blast]: ../ura/mechanics.html#pressure-blast
[Pressure Blasts]: ../ura/mechanics.html#pressure-blast
[Titanic Resistance]: ../ura/mechanics.html#-titanic-resistance
[Champion Fumaroller]: ../ura/mechanics.html#champion-fumaroller
[Champion Fumarollers]: ../ura/mechanics.html#champion-fumaroller
[Bloodstone Saturation]: ../ura/mechanics.html#-bloodstone-saturation
[Propel]: ../ura/mechanics.html#propel
[Autoattack Chain]: ../ura/mechanics.html#autoattack-chain
[Rising Pressure]: ../ura/mechanics.html#-rising-pressure
[Steam Prison]: ../ura/mechanics.html#steam-prison
[Return]: ../ura/mechanics.html#return
[Sulfuric Acid]: ../ura/mechanics.html#-sulfuric-acid
[Acid Spray]: ../ura/mechanics.html#acid-spray

[Exposed]: https://wiki.guildwars2.com/wiki/Exposed
[Poison]: https://wiki.guildwars2.com/wiki/Poison
[Distort]: https://wiki.guildwars2.com/wiki/Distortion
[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Superspeed]: https://wiki.guildwars2.com/wiki/Superspeed