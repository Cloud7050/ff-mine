---
title: Cloud's Leviathan Guide
layout: page
permalink: /leviathan
---

## What

**Phase 1**\
The boss has two parts which share a healthpool. The head reflects physical ranged damage; the tail reflects magic damage.

- Body Slam: Invisible horizontal line AoE. Does ~80% HP to squishies. Knocks everyone towards that side
- Spinning Dive: Line AoE with knockback. Inflicts a 2min vuln stack (water resistance down)
- Waterspout: 2 untelegraphed circular AoEs. Does ~25% HP to each squishy. Targets healers first
- Grand Fall: A set of multiple big, dodgeable circular AoEs. Inflicts 30s heavy
- Tidal Roar: Raidwide
- Tidal Wave: Special raidwide. Must be mitigated with the Elemental Converter (see below) to survive. Does true damage; tank LB does not help

Head:

- Dread Tide: 3 circular AoEs in a line. Starts on the MT, then sequentially away from the head
- Aqua Breath: ~7y circular cleave. Does little damage

Tail:

- Tail Whip: ~9y circular cleave. Does ~20% HP to squishies
- Briny Mirror: 1min debuff that inflicts a 45s Briny Veil stack on others who directly heal the target. Targets tail's top enmity. Gets reapplied on expiry or if the target dies
  - Briny Veil: Linearly reduces action range. Target cannot act at 16 stacks

Wavespine Sahagin:\
Cannot be stunned, but can be slowed.

- Stun Shot: Inflicts 30s paralysis on a target. Used once in a while
- Hydro Shot: Leaves a light blue circle on the ground that inflicts unstackable 9s DoT (Dropsy). Will start to spam this if not killed in time

Wavetooth Sahagin:

- Deadwash: Inflicts 5s hysteria on everyone. Can be stunned during the castbar. Used once in a while
- Dreadstorm: Leaves a dark blue circle on the ground that inflicts 10s hysteria. Immune to stuns during the castbar. Will start to spam this if not killed in time, or once <70% HP

Gyre Spume (yellow orb):\
Cannot move. Steals charge (elemental conversion) while alive

- Splash: Raidwide. Happens when killed

Elemental Converter:\
Gains charge over time. Becomes operable once all Gyres are dead.\
Spends charge when interacted with to create a short-lived barrier, which mitigates Tidal Wave. Higher charge improves the mitigation; at least ~24 charge is needed for the party to survive.

**Phase 2**\
Wave Spume (blue orb):\
Starts tethered to the centre and steals Converter charge.\
Once aggroed, stops stealing charge and tethers to its target instead, inflicting unstackable bleeding.

- Aqua Burst: Detonates itself in a proximity raidwide. Happens 32s after first tethering (10s after you stop sliding from Slam)

## Water Jets

Both Slam and Dive are telegraphed by a water jet.

Slam has 4 possible jet locations (NE/NW/SE/SW), which is where the head will appear from. Effectively, Slam will either knock everyone to the N or to the S.

Dives have 10 possible jet locations:

- The boss may dive from the N or S vertically, covering half the ship (2 N, 2 S)
- The boss may dive from the E or W horizontally, covering a third of the ship (E/W, NE/NW/SE/SW)

We can put these possibilities into 2 groups:

- The N group includes 2 dives from N, 2 dives from NE/NW, and E/W central dives
- The S group includes 2 dives from S, 2 dives from SE/SW, and again E/W central dives

The boss usually does 2 dives. The first dive will be from the group corresponding to the side he disappeared from. The second dive will be from the opposite group.\
There are exceptions where the boss will only do the first dive:

- When the boss means to end his combo with Tidal Wave, he will only do 1 vertical dive - he will not pick any horizontal dives from the corresponding group. I call this the "converter dive"
- For the combo right after Wave Spumes spawn, he will only do 1 dive

e.g if he disappears from the N and wants to dive twice, the first dive will be from the N group and the second from the S group.\
e.g. if he disappears from the S and wants to do his converter dive, it will be 1 of the 2 vertical dives from the S.

## When

**Phase 1** <90%\
Slam\
2 N Wavespines\
*At <80% HP:*\
Briny Mirror, 1 E Wavetooth\
~~3 Grand Falls, 2 dives~~

~~Slam~~\
*At <70% HP skip here:*\
4 Gyres\
Tidal Roar, 3 Grand Falls, 2 dives

Slam\
*When Gyres dead skip here:*\
Grand Fall, [Converter] 1 vertical dive, Tidal Wave

**Phase 2**\
Slam breaks railings\
2 Tidal Roars\
2 S Wavespines\
2 Tidal Roars, Grand Fall, 2 dives

Slam\
*At <35% HP skip here:*\
4 Gyres\
2 Tidal Roars, 4 Wave Spumes\
3 Grand Falls, 1 dive

Slam\
3 Grand Falls, [Converter] 1 vertical dive, Tidal Wave

**Phase 3**\
Slam\
1 W Wavetooth\
2 Tidal Roars\
2 Tidal Roars\
3 Grand Falls, 2 dives

Slam\
2 Tidal Roars\
2 Tidal Roars\
~~2 Tidal Roars, 2 N Wavespines~~\
~~2 Tidal Roars~~\
~~3 Grand Falls, 2 dives~~

## How

**Phase 0**

- The boss doesn't do any mechanics (he disappears at <90% HP). Save your buffs and burst for the Wavetooth later

**Phase 1**

- MT grabs the head. MT should stay in the corner beside the head, to point Dread Tide off the ship
- OT grabs the tail. OT is free to move around and grab adds
- Melees should attack head instead of tail, as tail has the stronger circular cleave
  - This also makes it easier for healers to AoE heal the party while avoiding OT
- Healers should stay apart due to Waterspout. Others should avoid them. You may want to mark the healers
- Healers need to manage their Briny Veil stacks and let them expire when the stacks get too high
  - Actions that don't heal the OT directly will not give stacks (e.g. WHM Regen, AST Synastry, SCH Embrace/Whispering Dawn)
  - Regens that also directly heal alongside applying their regen buff will give stacks (e.g. WHM Medica II, AST Aspected Benefic)
  - It's a good idea to stack a lot of regens on the OT, and save big heals for the OT, to reduce the number of actions used on them
- Gyres should be focused one by one. e.g. Gyre at head → Gyre at tail → Gyre opposite tail → last Gyre. If you instead spread out your damage, it's bad because:
  - Too many Gyres are alive for too long. Each Gyre steals charge while alive; you may not have enough for the Converter
  - Since Gyres do a raidwide on death, killing one too soon after the previous creates burst damage that is harder to heal
- I recommend keeping 1 Gyre alive until the boss disappears, to prevent ambiguity. The moment the boss leaves to start 2 dives, you are free to finish it off. As long as you were killing the other Gyres at a decent pace, you will have sufficient charge
  - As you prog, you will reach a point where you sometimes skip to the converter dive (by killing all Gyres early). When the boss leaves, it becomes hard to tell whether he's going to do 2 dives, or has skipped to 1 dive + Tidal Wave. Skip checks also stop a little while before he leaves, so it may look like you killed all Gyres before he left, but you can't say for sure whether you actually skipped. Guessing wrong leads to an early/late Converter press, which is a wipe, so this strat makes the fight consistent by not skipping

**Phase 2**

- Slam breaks the railings. Dives and Slams can now knock you off
- OT grabs Wave Spumes. After Slam, kite them to the corner furthest from the party and pop invuln
  - Wave Spumes have too much health. Don't bother trying to kill them, just let them detonate

**Phase 3**

- Remember to chain stun and burn the last Wavetooth asap. If too many are dead to kill it quickly, dps LB if you really must. It can easily hysteria everyone off the ship

## Other Tips

- You can DoT both the head and tail at the same time
  - Actions that also directly damage alongside applying their DoT may have that direct damage reflected, so beware
- Tanks'/melees' physical ranged attacks will get reflected by the head, so beware
- DRK's magic attacks will get reflected by the tail, so they should MT
- If you get a rez during dives, you should wait till after Slam to accept it, to avoid instantly falling off/dying
- Arm's Length/Surecast negates the knockback from Slam. You can save it as a panic button if you lose track of jets and think you're about to get knocked off
  - Tanks may instead use it as extra mit for the Wavespines
- The Sahagin all spawn at fixed locations which makes them predictable to watch for. Switching to them the moment they spawn is important
- When using healer LB3, first make sure the bodies have actually respawned on the ship, since they are likely to get knocked off after each Slam
- Healers can use Rescue to save people from falling off
- As Briny Mirror makes it costly to heal the OT, you may want to let MT grab 1 or both Wavespines instead of OT
- If healers are struggling with stacks, you may want OT to stay in the other corner similar to MT, so it's easier for healers to AoE heal the party while avoiding OT
- There is an edge case for the first dive combo of phase 2 (Grand Fall, 2 dives). If the boss is already leaving to start dives, but at the same time hits the <35% HP breakpoint, then his combo is instead a *duplicate* of the subsequent combo (3 Grand Falls, 1 dive)
  - This should rarely happen, but if it does, you may get caught off guard by him doing just 1 dive. As per the infographics below, it is safer to dodge to the other side instead of staying in the middle, even if what you think is a dive (and not a Slam) wouldn't hit you
  - As per the breakpoint skip, 4 Gyres will still spawn immediately, just that such timing feels unexpected
  - After the combo, he resumes his rotation as usual (from 4 Wave Spumes, then that 1 dive combo again etc.)

<img class="border" src="images/infographics/leviathan-2-dives.png" width="700" />

<img class="border" src="images/infographics/leviathan-converter-dive.png" width="700" />
