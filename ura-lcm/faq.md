---
layout: page
title: FAQ
nav_order: 2
parent: Legendary Ura
---

[Return to Home](../index.html){: .btn } [Return to Overview](./overview.html){: .btn } [Strategy Guide](./strategy.html){: .btn }

# Legendary Ura - FAQ

This page contains a set of frequently asked questions regarding the Legendary Ura encounter. These are grouped into the following sections:

1. [Ura's Attacks and How to Deal with Them](#uras-attacks-and-how-to-deal-with-them)
2. [Ranged Group and Toxic Geysers](#ranged-group-and-toxic-geysers)
3. [Phasing and Related Issues](#phasing-and-related-issues)
4. [Titanspawners, Fumarollers, Ventshots](#titanspawners-fumarollers-ventshots)
5. [Builds, Composition and More](#builds-squad-compositions-and-more)
6. [Glossary](#glossary)

<img class=divider>

## 1. Ura's Attacks and how to deal with them

---

<details class=faq>
<summary>1.1 - How does kiting Ura work in phase 1?</summary>
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
<summary>1.4 - How do I turn Ura to the correct side?</summary>
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

Generally, dodge [Create Titanspawn Geyser] (the stomp/jump in the air from Ura) and [Propel] (jump) when she lands. Try to sidestep or dodge the final cone of her [Autoattack Chain]. Other than these, you can jump, block or dodge the waves from [Sulfuric Geysers]. You can also double dodge out of the [Steam Prison] with the right timing (or with <img class='inline superspeed'> [Superspeed]), if you don’t have a mobility skill and no <img class='inline stability'> [Stability]. You can dodge [Sulfuric Geyser]/[Toxic Geyser] AoEs to prevent the damage ticks, but this is not as important.

</div>
</details>

<details class=faq>
<summary>1.9 - Can you give <img class='inline stability'> Stability to people in bubbles?</summary>
<div markdown='block'>

No, the people targeted by the mechanic stripped of <img class='inline stability'> [Stability] if they have it beforehand, and cannot receive it again during bubbles, until they're <img class='inline dispel'> [Dispelled]. This means that players in bubbles can get knocked by [Champion Fumarollers], which can lead to displaced bubbles.

The white indicator on the floor is misleading in these situations, because it only shows the initial bubble position, and does not get updated when knocked, while <img class='inline dispel'> [Dispel] only works if casted underneath the bubble. In such cases immediately call out in voice that the shard needs to be dropped again.

</div>
</details>

<details class=faq>
<summary>1.10 - How do I deal with bubbles in this situation?</summary>
<div markdown='block'>

#### I have bubble at the same time as the Titanspawner!

The [Bloodstone Shard] always MUST to go to the [Titanspawner], this means that the bubbles also MUST go to the Titanspawner. General rule of thumb is to always do bubbles next to the Titanspawn when both are up.

#### I have bubble at the same time as the Titanspawner and the second bubble is tank!

In this case they should call for a backup tank immediately and run to the Titanspawn. Usually there is always someone who can backup tank for a bit, like a DPS from the ranged team, or one of the healers.

#### I have bubble but I am running back from [Sulfuric Geyser]!

Just like the case above with the ranged being far away, call it out immediately with the direction and meet in the middle.

There is one specific possible scenario where you get Sulfuric > phase 40% to p3 > Sulfuric person gets the bubble. This is very unlucky timing and it’s a difficult situation to solve. The second bubble has to run out to the Sulfuric person together with the melee who has the bloodstone shard (and the one who is supposed to pick up) in order to save them. Otherwise they will likely die and it’s a wipe.

</div>
</details>

<img class=divider>

## 2. Ranged group and Toxic Geysers

---

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

## 3. Phasing and related issues

---

<details class=faq>
<summary>3.1 - What is the issue with CCing around 40%?</summary>
<div markdown='block'>

At 40% of her HP, Ura transitions from Phase 2 to Phase 3. This interrupts her current skill cast, which similarly to bad CC timing, can lead to her using [Propel]. There isn't much you can do to prevent this, as controlling DPS to phase at a good time is very difficult. However, try not to CC her shortly before or after the transition, as two interrupts in a short interval can increase the chance of her running out of attacks to use and then consequently using [Propel]. See [preventing Propel](mechanics.html#preventing-propel) for more information.

</div>
</details>

<details class=faq>
<summary>3.2 - What are the biggest issues while phasing?</summary>
<div markdown='block'>

- **Phase 2** - nothing specifically, but if you have low dps, then [Toxic Geysers] #12, #13, #14 can be an issue.
- **Phase 3** - Ura will self-interrupt and the [Toxic Geyser] timer instantly resets, spawning #7 instantly and making things a bit more difficult for the ranged team. Additionally, Ura will immediately cast [Pressure Blast]. This is usually the most difficult transition, because it starts from being very chill in p2 to suddenly being very hectic with lots of mechanics.
- **Phase 4** - self-interrupt, but otherwise nothing in particular. The self-interrupt is less of an issue, because Ura will also spend a few seconds in a phasing animation.

</div>
</details>

<details class=faq>
<summary>3.3 - How do I deal with #10, #11 (#12) and #8 geysers at 70%?</summary>
<div markdown='block'>

Depends on strategy; please refer to a [ranged rotation](strategy.html#ranged-rotation) or ask your commander.

But generally if you have low dps and you get #13 and #14, you might even want to /gg and practice phase 1, since your whole rotation will be thrown off. If just #12 and #13 spawn extra, the <img class='inline deadeye'> [Deadeye] can reset them until they are done normally at some point in phase 2.

Realistically this should only happen very early into prog: even after a couple of pulls you should phase fast enough to not get #13. If not, you have a DPS issue which will prevent you from killing Ura within the enrage timer; as rule of thumb, this is also a nice check to see if the overall squad dps is enough.


</div>
</details>

<details class=faq>
<summary>3.4 - How do I deal with #7 and #8 geysers at 40%?</summary>
<div markdown='block'>

Depends on strategy; please refer to a [ranged rotation](strategy.html#ranged-rotation) or ask your commander.

</div>
</details>

<details class=faq>
<summary>3.5 - Is there any issue while phasing into phase 4?</summary>
<div markdown='block'>

The Phase 4 transition also interrupts Ura's current cast, so it can also cause a jump if it happens with very bad timing. However, due to the transition also including an animation for Ura, it’s less likely than for the phase 3 transition. Check [preventing Propel](mechanics.html#preventing-propel) for more information.

</div>
</details>

<img class=divider>

## 4. Titanspawners, Fumarollers, Ventshots

---

<details class=faq>
<summary>4.1 - How do Titanspawners and Ventshots work?</summary>
<div markdown='block'>

[Titanspawn Geysers] are created every time Ura uses her [Create Titanspawn Geyser] ability . The Titanspawners in phase 2 and 3 are the same as in phase 4, but while they will spawn [Champion Fumarollers] in p2, in p4 they will instead spawn [Legendary Ventshots]. Additionally, when Ura hits 1% and heals, she will always spawn an additional Titanspawn Geyser independent of her Create Titanspawn Geyser skill.

</div>
</details>

<details class=faq>
<summary>4.2 - When is a good time to stop killing Titanspawners?</summary>
<div markdown='block'>

It depends on the squad. Not killing [Titanspawn Geysers] during phase 3 can be very dicey, because multiple [Champion Fumarollers] can quickly CC, down then wipe you. If you play with two <img class='inline chrono'> [Chronomancers], this can be managed with relative ease by outhealing the damage and providing <img class='inline stability'> [Stability], so you can stop killing Titanspawners roughly after 15% pre-heal. This will reduce the number of [Legendary Ventshots] you get down to ~2 during the final phase, which means you will likely not wipe if projectile block fails.

However, if you play with only one <img class='inline chrono'> [Chronomancer] and one <img class='inline scourge'> [Scourge], then it’s recommended to continue killing all Titanspawners throughout phase 3. Then, if the first [Titanspawn Geyser] in p4 is directly next to the squad, you can quickly kill it. Ignore all other Titanspawners after the first.

</div>
</details>

<details class=faq>
<summary>4.3 - Why are Fumarollers dangerous and how do I deal with them?</summary>
<div markdown='block'>

[Champion Fumarollers] hit hard: their attacks often inflict <img class='inline knockback'> [Knockback], which when combined with the heavy damage from Stars/Snowflakes, can quickly down and kill you. The longer they live, the higher the chance that they spawn another star under the boss, so you generally want to kill them as quickly as possible. This usually involves:

1. Baiting the Fumaroller to the boss (standing 90°/tangential at the boss)
2. After the Fumaroller charges, moving on top of it and cleaving it down.

The only exception to killing them immediately is for some specific strategies in which you want to keep them alive for as long as possible at the start of phase 4, in order to get less [Legendary Ventshots]. This works because Ventshots, [Titanspawn Geysers] and Fumarollers have an entity cap (6 in phase 4), so when too many are on the field, no new entities will spawn. However, this is quite dangerous, and requires specialized compositions.

Players in the ranged group should watch the Fumarollers and bait them into the stack before running out for [Toxic Geysers] if possible, since their charge targets the highest toughness player in their cone of vision. Baiting them in this manner also makes it so that they cannot bother you at range while dealing with other mechanics.

Generally, you want to kill the Fumarollers before they cast a star/snowflake on the boss. If they do cast one, move out of it as quickly as possible. If someone downs, everyone needs to immediately ress, as the high incoming damage makes it difficult to do with few players.

Fumarollers don’t need to be CCd. They can be CCd just from passive AoE CC, but there is no specific need to pay special attention to it.

The melee team who kills the Titanspawner should always have some <img class='inline stability'> [Stability] (e.g. from the <img class='inline firebrand'> [Firebrand]), so that they don’t immediately get knocked. Once the Fumaroller is on the group, also make sure to also provide <img class='inline stability'> [Stability]. The star attack inflicts <img class='inline knockback'> [Knockback] three times, while the charge, roll and headbutt only once each.

</div>
</details>

<details class=faq>
<summary>4.4 - How do I deal with Ventshots?</summary>
<div markdown='block'>

[Legendary Ventshots] have over 20 million HP, so they are not meant to be killed. After 2 or more spawn, keep projectile block up on the group permanently and try to keep up permanent <img class='inline stability'> [Stability] as well. Ventshots can kill you either with ranged attacks when projectile block is down, or with melee attacks (that also inflict <img class='inline knockback'> [Knockback]) when they are close to the squad. 

As a <img class='inline chrono'> [Chronomancer], if you are running <img class='inline precog'> [Well of Precognition] you can use this [rotation](https://www.youtube.com/watch?v=ZNt3AbNwiuw) from Schwifty for permanent <img class='inline stability'> [Stability].

</div>
</details>

<details class=faq>
<summary>4.5 - What are the advantages and disadvantages of only <img class='inline power'> Power DPS killing Titanspawners?</summary>
<div markdown='block'>

[Titanspawn Geysers] have low armor and therefore take extra <img class='inline power'> [Power] damage. This, combined with the absence of ramp-up and the strong burst typical to most power DPS, can kill them pretty quickly, which mitigates the possibility of having a second [Champion Fumaroller] spawn. <img class='inline burning'> [Burning]-based condition builds are also viable due to their relatively short ramp-up. Note that conditions can be stacked on the Titanspawner Geyser while it’s still invulnerable.

Instead, sending all the DPS and boonDPS to the Titanspawner has the advantage that the group stays together (except for the [tank](../ura/mechanics.html#tanking-ura)), but the disadvantage that if the tank is targeted by [Pressure Blast], there may not be a backup tank available. One way to circumvent this is by having only the players doing the melee [Bloodstone Shard] rotation on the Titanspawner, which means you will always have multiple people tanking. The downside in this case is that once more the squad will be split into two.

Generally either way works good enough: pick based on personal preference and whether you have <img class='inline power'> [Power] DPS available.

</div>
</details>

<details class=faq>
<summary>4.6 - How many <img class='inline power'> Power DPS and what classes should be sent to Titanspawners?</summary>
<div markdown='block'>

For simplicity it’s best to send the full melee shard rotation group, as this way you will always include the players who must <img class='inline dispel'> [Dispel] and successively pick up the [Bloodstone Shard]. This should be a <img class='inline firebrand'> [Firebrand] and three DPS at least. Including a single <img class='inline power'> [Power] DPS, or having at least two <img class='inline burning'> [Burning]-based <img class='inline condition'> [Condition] DPS (such as <img class='inline weaver'> [Weaver], <img class='inline willbender'> [Willbender] and <img class='inline firebrand'> [Firebrand]) is usually enough to make sure that they can kill the Titanspawner comfortably in time.

</div>
</details>

<img class=divider>

## Builds, Squad Compositions and More

---

<details class=faq>
<summary>5.1 - What supports should I play?</summary>
<div markdown='block'>

You can find a list of builds in the [builds & PoV section](strategy.html#builds-and-povs) of the strategy guide, but here follows a short description of the most popular builds:

---

#### <img class='inline deadeye'> CC Deadeye

This is the only build that can keep up with the encounter's extreme Crowd Control requirements with little assistance.

For the most part there is only one specific build, but some small variations are possible. Depending if you are [tunneling](strategy.html#tunneling) or not, you can play with/without weapon swap.

If you are learning to play this build, check out Chupathingy's excellent <img class='inline deadeye'> [CC Deadeye Guide](https://docs.google.com/presentation/d/19xXTt8iPkvoDVG_I_TEQOd_Xyw4R6ZdB90SOWWzzh4M) for more information.

{: .note}
If you need to provide <img class='inline might'> [Might] and <img class='inline fury'> [Fury], you should take <img class='inline midnight'> [Relic of the Midnight King]. Otherwise, take <img class='inline speed'> [Relic of Speed] for permanent <img class='inline superspeed'> [Superspeed].

---

#### <img class='inline chrono'> Heal Chronomancer

A standard, yet extremely strong build that does everything well.

By default takes <img class='inline precog'> [Well of Precognition] but if you are paired with a Quick <img class='inline firebrand'> [Firebrand] who is comfortable with providing <img class='inline stability'> [Stability], then you could also drop the well, replacing it with:
- <img class='inline blink'> [Blink] for early prog, to cover up mistakes and manage mechanics. It is also useful to bait Ura into casting [Propel] in a specific direction.
- <img class='inline feedback'> [Feedback] allows you to backup projectile blocks in p4, and if taken along with the <img class='inline medic-feedback'> [Medic Feedback] trait also gives you extra ress ability.
- An additional CC skill (such as <img class='inline technobabble'> [Technobabble], <img class='inline domination'> [Signet of Domination], <img class='inline senility'> [Well of Senility]) can be useful to quickly solo CC [Toxic Geysers] from range (otherwise you can solo CC with <img class='inline moa'> [Signet of Humility] and <img class='inline collapse'> [Mental Collapse] with <img class='inline clarity'> [Clarity]; or with <img class='inline moa'> [Signet of Humility] and <img class='inline sharpshooter'> [Phantasmal Sharpshooter] , but the latter requires very good timing). This can be useful when the <img class='inline deadeye'> [Deadeye] is inexperienced, and when they cannot otherwise CC.

There have been plenty of kills with all different kind of utility variations, and all the utility skills can fill different needs. Hence, there is not a clear go-to that is the best for all situations.

---

#### <img class='inline scourge'> Celestial Hybrid Scourge

A flexible support that provides a bit of extra damage and utility, depending on your group's needs in terms of offensive vs defensive support.

- **Offensive**: runs the <img class='inline curses'> [Curses] and <img class='inline reaping'> [Soul Reaping] traitlines for some additional damage. Has a lower cooldown on <img class='inline cpc'> [Corrosive Poison Cloud], which means that they can cover reflect with only a single <img class='inline firebrand'> [Firebrand]. Also runs sword offhand for extra movement. The downsides are less healing and no <img class='inline stability'> [Stability], so the <img class='inline firebrand'> [Firebrand] in the same subgroup should bring extra.
- **Defensive**: runs <img class='inline blood-magic'> [Blood Magic] instead of <img class='inline curses'> [Curses] for more healing, <img class='inline stability'> [Stability] and boons. The downside is less damage and a longer cooldown on <img class='inline cpc'> [Corrosive Poison Cloud], which means you need to account for either a more difficult projectile block rotation that involves additional people, or (better) you need at least two <img class='inline firebrand'> [Firebrands] with the <img class='inline scourge'> [Scourge] just backing up.
- **Middle ground**: play the offensive build with <img class='inline anguish'> [Trail of Anguish] instead of <img class='inline blood-power'> [Blood is Power], so you have a <img class='inline stability'> [Stability] skill available.

---

####  Condition Quickness Firebrand

A high damage boonDPS with exceptional utility.

There are a few variations in your loadout depending on your squad's needs:

- <img class='inline wall-reflect'> [Wall of Reflection] is needed once per squad. This player should call the projectile block rotation, which is <img class='inline wall-reflect'> [Wall of Reflection] -> <img class='inline bulwark'> [Chapter 3: Valiant Bulwark] -> fill – where the fill is either <img class='inline cpc'> [Corrosive Poison Cloud], or another <img class='inline firebrand'> [Firebrand]'s <img class='inline bulwark'> [Chapter 3: Valiant Bulwark]. Loses ~3.7k DPS from the bench.
- Running <img class='inline liberation'> [Mantra of Liberation] and <img class='inline purging'> [Purging Flames] (recommended) gains additional cleanses and <img class='inline stability'> [Stability]  with a group <img class='inline stunbreak'> [Stunbreak] on the elite, losing ~2.7k DPS from the bench and the <img class='inline superspeed'> [Superspeed] from <img class='inline feel-my-wrath'> [Feel My Wrath!].
- Running <img class='inline feel-my-wrath'> [Feel My Wrath!] and <img class='inline stand-ground'> [Stand Your Ground!] has the advantage of still providing <img class='inline superspeed'> [Superspeed] to quickly run to the [Titanspawn Geysers]. Use <img class='inline stand-ground'> [Stand Your Ground!] for the Titanspawn and <img class='inline epilogue'> [Epilogue: Unbroken Lines] for [Steam Prison]. This loses ~3.7k DPS from the bench.
- Running <img class='inline liberation'> [Mantra of Liberation] and <img class='inline stand-ground'> [Stand Your Ground!] trades even more DPS (~6.3k) for more <img class='inline stability'> [Stability], which can be done if people in your sub get knocked around a lot, such as when running an offensive <img class='inline scourge'> [Scourge].

<div style="color: grey">Numbers from Iskarel and SC.</div>

</div>
</details>

<details class=faq>
<summary>5.2 - What DPS should I play?</summary>
<div markdown='block'>

DPS builds always depend on the current meta, so it’s best to just look at the [builds & PoV section](strategy.html#builds-and-povs) to see what is up-to-date. Alternatively, servers such as <img class='inline vl-icon'> [Void Lounge](https://discord.com/invite/voidlounge) keep a dedicated build section that you can check.

</div>
</details>

<details class=faq>
<summary>5.3 - What utility should I bring on DPS?</summary>
<div markdown='block'>

Condition cleanse, <img class='inline stability'> [Stability] and movement skills are nice if they don’t cost you much and if your group doesn't require more damage. Examples are:

- <img class='inline willbender'> [Willbender] - in the <img class='inline virtues'> [Virtues] traitline, taking <img class='inline absolute-resolve'> [Absolute Resolve] brings lots of cleanse at a very minor DPS loss.
- <img class='inline mechanist'> [Mechanist] - <img class='inline healing-turret'> [Healing Turret] is good AoE cleanse.
- <img class='inline weaver'> [Weaver] - can bring <img class='inline lightning'> [Lightning Flash] for mobility instead of <img class='inline ele-glyph'> [Glyph of Lesser Elementals]. Generally it’s always worth to have good [Sulfuric Geyser] placements over some additional damage.
- <img class='inline scrapper'> [Scrapper] - can take <img class='inline mass-momentum'> [Mass Momentum] for additional <img class='inline stability'> [Stability] at the cost of <img class='inline superspeed'> [Superspeed].
</div>
</details>

<details class=faq>
<summary>5.4 - What are the best ways to CC on a support class?</summary>
<div markdown='block'>

- <img class='inline deadeye'> [Deadeye] - check out the [detailed guide](https://docs.google.com/presentation/d/19xXTt8iPkvoDVG_I_TEQOd_Xyw4R6ZdB90SOWWzzh4M) from Chupathingy.
- <img class='inline chrono'> [Chronomancer] - <img class='inline moa'> [Signet of Humility] combined with any other skill from weapons or utilities you might have. Depending on the situation, don’t be afraid to use these within <img class='inline cs'> [Continuum Split] if you anticipate needing CC again soon after.
- <img class='inline scourge'> [Scourge] - <img class='inline golem'> [Summon Flesh Golem] into <img class='inline golem-charge'> [Charge].
- <img class='inline firebrand'> [Firebrand] - <img class='inline jurisdiction'> [Jurisdiction] (but generally don’t hold it) and <img class='inline rebuke'> [Chapter 3: Heated Rebuke].

</div>
</details>

<details class=faq>
<summary>5.5 - How much damage should I be dealing?</summary>
<div markdown='block'>

#### todo

</div>
</details>

<details class=faq>
<summary>5.6 - Who should provide <img class='inline stability'> Stability?</summary>
<div markdown='block'>

Highly dependant on the squad composition, how much <img class='inline stability'> [Stability] you are running and on the situation. Generally there is not one main <img class='inline stability'> [Stability] provider. The <img class='inline chrono'> [Chronomancer] is running <img class='inline stab-mantra'> [Mantra of Concentration] and should always pay attention to mechanics and use a charge whenever there is a mechanic that requires it. If running <img class='inline precog'> [Well of Precognition], they can also drop it onto the group at [Titanspawn Geysers], or on the squad if a [Champion Fumaroller] is on stack.

<img class='inline scourge'> [Scourge] and <img class='inline firebrand'> [Firebrand] have varying amounts depending on the build, but should similarly use them whenever needed and they are in range (e.g. <img class='inline stand-ground'> [Stand Your Ground!] for Titanspawners and <img class='inline epilogue'> [Epilogue: Unbroken Lines] for [Steam Prison]).

So summarizing, whoever has <img class='inline stability'> [Stability] should always use it for mechanics if they are on stack, or wherever the mechanic is happening. For example while the Chrono has obviously the greatest amount of <img class='inline stability'> [Stability] if they are running <img class='inline precog'> [Well of Precognition], this doesn’t help when they are on ranged shard duty away from the squad: at this point the <img class='inline firebrand'> [Firebrand] needs to provide <img class='inline stability'> [Stability].

</div>
</details>

<details class=faq>
<summary>5.7 - What are compositions are commonly run?</summary>
<div markdown='block'>

The two main compositions are relatively similar and only come down to <img class='inline scourge'> [Scourge] or <img class='inline chrono'> [Chronomancer] as second healer and what specific build the <img class='inline firebrand'> [Firebrand] runs.

The DPS builds can in principle be any dps of the builds in the [builds & PoV section](strategy.html#builds-and-povs). One notable distinction is that if you run a full <img class='inline condition'> [Condition] comp, everyone in the second subgroup (<img class='inline firebrand'> [Firebrand] + 3 DPS) should go kill the [Titanspawn Geyser], while with <img class='inline power'> [Power] DPS, only two are required to go there to kill it in time. In this case, these two should be placed with their <img class='inline firebrand'> [Firebrand] in the <img class='inline deadeye'> [Deadeye]'s subgroup.

---

#### Scourge Composition
Trades higher DPS for less healing and <img class='inline stability'> [Stability].

|<img class='inline deadeye'> [Deadeye] | <img class='inline scourge'> [Scourge]* | <img class='inline firebrand'> [Firebrand] (Stab**) | DPS ([tank](../ura/mechanics.html#tanking-ura)) | DPS (Ranged Backup) |
|<img class='inline chrono'> [Chronomancer] | <img class='inline firebrand'> [Firebrand] (Wall, marker) | DPS | DPS | DPS |

\* If defensive, then the two <img class='inline firebrand'> [Firebrands] should do the basic projectile block rotation, while keeping the <img class='inline cpc'> [Corrosive Poison Cloud] from the <img class='inline scourge'> [Scourge] as backup whenever needed.

** If confident, can also drop <img class='inline stand-ground'> [Stand Your Ground!] and still run <img class='inline purging'> [Purging Flames], especially if the <img class='inline scourge'> [Scourge] plays the defensive version with <img class='inline anguish'> [Trail of Anguish] and Staff for <img class='inline stability'> [Stability].

---

#### Double Chrono Composition
Trades lower DPS for more healing and <img class='inline stability'> [Stability].

|<img class='inline deadeye'> [Deadeye] | <img class='inline chrono'> [Chronomancer] | <img class='inline firebrand'> [Firebrand] (Wall, marker) | DPS ([tank](../ura/mechanics.html#tanking-ura)) | DPS (Ranged Backup) |
|<img class='inline chrono'> [Chronomancer] | <img class='inline firebrand'> [Firebrand]* | DPS | DPS | DPS |


\* The <img class='inline firebrand'> [Firebrand] can either run <img class='inline liberation'> [Mantra of Liberation] and <img class='inline purging'> [Purging Flames] to have some extra <img class='inline stability'> [Stability], or fully offensive with the default SnowCrows build, bringing only <img class='inline epilogue'> [Epilogue: Unbroken Lines] for <img class='inline stability'> [Stability].

</div>
</details>

<details class=faq>
<summary>5.8 - How do I assign DPS for melee rotations and Titanspawners?</summary>
<div markdown='block'>

The melee shard rotation consists of 4 people (e.g. everyone except the Healer in Sub2) and thus all of them can go to the [Titanspawn Geyser], such that you always have the melee [Bloodstone Shard] and the <img class='inline stability'> [Stability] from the <img class='inline firebrand'> [Firebrand] for the [Champion Fumaroller].

Having at least one <img class='inline power'> [Power] DPS in this group helps with killing the Titanspawner quickly. If you run a full <img class='inline condition'> [Condition] composition and have problems killing it in time, then you can have the <img class='inline firebrand'> [Firebrand] from Sub1 and the DPS (ranged backup) also go and cleave the Titanspawner (which leaves only the [tank](../ura/mechanics.html#tanking-ura) at the boss).

</div>
</details>

<details class=faq>
<summary>5.9 -Can I play a different QuickDPS?</summary>
<div markdown='block'>

Other support builds can technically be run if there is no need for specific skills (e.g. projectile block, <img class='inline stability'> [Stability], ..), but <img class='inline firebrand'> [Firebrand] is generally the best choice due to high DPS combined with the massive amount of utility it brings. If in doubt, just check your squad composition and make sure everything is covered.

</div>
</details>

<img class=divider>

## Glossary

---

**Arena:** Donut/Cage/Prison refers to Ura’s [Steam Prison] attack that shows up as a donut-shaped orange indicator around a player.

**Bubbles:** aka “Friends”, refers to Ura’s [Pressure Blast] attack that applies 2 small circle indicators to random players which will trap those players and anyone else caught in the explosion radius in floating bubbles.

**Titanspawner:** Refers to the [Titanspawn Geyser] that appears when Ura casts [Create Titanspawn Geyser].

**Fumas/Fumarollers:** Refer to the [Champion Fumaroller] adds that spawn from [Titanspawn Geysers].

**Ventshots:** Refer to the [Legendary Ventshot] adds that spawn from [Titanspawn Geysers] during phase 4.


<img class=divider>

[Return to Home](../index.html){: .btn } [Return to Overview](overview.html){: .btn } [Return to Top](#ura-faq){: .btn .fixed}
{: .center}

[Chronomancer]: strategy.html#builds-and-povs
[Chronomancers]: strategy.html#builds-and-povs
[Deadeye]: strategy.html#builds-and-povs
[Scourge]: strategy.html#builds-and-povs
[Firebrand]: strategy.html#builds-and-povs
[Firebrands]: strategy.html#builds-and-povs
[Willbender]: strategy.html#builds-and-povs
[Weaver]: strategy.html#builds-and-povs
[Mechanist]: strategy.html#builds-and-povs
[Scrapper]: strategy.html#builds-and-povs

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
[Legendary Ventshot]: ../ura/mechanics.html#legendary-ventshot
[Legendary Ventshots]: ../ura/mechanics.html#legendary-ventshot
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
[Burning]: https://wiki.guildwars2.com/wiki/Burning
[Distort]: https://wiki.guildwars2.com/wiki/Distortion
[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Superspeed]: https://wiki.guildwars2.com/wiki/Superspeed
[Knockback]: https://wiki.guildwars2.com/wiki/Knockback
[Power]: https://wiki.guildwars2.com/wiki/Power
[Condition]: https://wiki.guildwars2.com/wiki/Contition_damage
[Might]: https://wiki.guildwars2.com/wiki/Might
[Fury]: https://wiki.guildwars2.com/wiki/Fury
[Relic of the Midnight King]: https://wiki.guildwars2.com/wiki/Relic_of_the_Midnight_King
[Relic of Speed]: https://wiki.guildwars2.com/wiki/Relic_of_Speed
[Well of Precognition]: https://wiki.guildwars2.com/wiki/Well_of_Precognition
[Blink]: https://wiki.guildwars2.com/wiki/Blink
[Feedback]: https://wiki.guildwars2.com/wiki/Feedback
[Medic Feedback]: https://wiki.guildwars2.com/wiki/Medic%27s_Feedback
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