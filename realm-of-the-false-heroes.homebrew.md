<style>
/* ============================================================
   THE REALM OF THE FALSE HEROES — Homebrewery V3 (A4)  v2.0
   ============================================================ */

/* ---- A4 PAGE SIZE (210 × 296.8 mm) ----
   You can also just pick "A4" in the brew's page-size dropdown. */
.page { width: 210mm; height: 296.8mm; }

/* Heading tiers: #  = chapter / new page;  ### = sub-section.
   Generic hook: swap "the Villain" for your campaign's Big Bad. */

/* ---- FULL-BLEED ART (exemplar — tune offsets to your theme) ----
   Add one of these as a bare class on an <img> to run it off the page
   edge with a feathered interior edge. Offsets assume PHB A4 padding
   (~1.4 / 1.9 / 1.6 cm); nudge the margins if a seam or gap shows. */
.page img.bannerBleed {   /* section-top banner: sides bleed, fade at bottom */
  width: calc(100% + 3.8cm); max-width: none;
  margin: 0 -1.9cm 0.3cm -1.9cm;
  -webkit-mask-image: linear-gradient(#000 76%, transparent);
          mask-image: linear-gradient(#000 76%, transparent);
}
.page img.bleedBottom {   /* page-bottom fill: sides + bottom bleed, fade at top */
  width: calc(100% + 3.8cm); max-width: none;
  margin: 0.3cm -1.9cm -1.6cm -1.9cm;
  -webkit-mask-image: linear-gradient(transparent, #000 26%);
          mask-image: linear-gradient(transparent, #000 26%);
}
.page img.bleedRight {    /* right-column portrait: right bleed, fade at left */
  width: calc(100% + 2.4cm); max-width: none;
  margin: 0 -1.9cm 0 0;
  -webkit-mask-image: linear-gradient(to right, transparent, #000 44%);
          mask-image: linear-gradient(to right, transparent, #000 44%);
}
.page img.handoutPortrait {  /* full-height portrait handout (e.g. the rotated battle map) */
  display: block; margin: 0 auto;
  height: 252mm; width: auto; max-width: 100%;
}
</style>


{{frontCover}}

{{banner HOMEBREW}}

{{margin-top:90px}}
::::::

## A Comedic Level 9 Interlude for Any Campaign

{{footnote
A party yanked out of their campaign and into a comic convention—who must win their way home. · Artwork generated with Nano Banana (Gemini) for this module.
}}

![The Departure](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/08-floor-lore-expert-2.png){position:absolute,bottom:0,right:0,height:100%}

\page

# Synopsis
::
Weary and weakened, cornered by a party far too powerful for him, **the Villain** plays a desperate card. With a forbidden artefact gifted to him in a fever dream, he banishes the party to a dimension where magic and martial prowess mean nothing: **a comic convention**.

In this bizarre realm of synthetic heroes and cardboard gods, the party is stripped of lethal force. To escape, they must navigate the strange customs of "fandom," survive the judgment of the locals, and win a cosplay tournament against their arch-rivals, **Team Rules Lawyer**. Only by claiming the Grand Prize—the **Amulet of Restoration**—can they shatter the illusion and go home.

:::::
{{note
##### Running This Interlude
Drop this anywhere you need a fun, low-stakes diversion: have your campaign's **Big Bad** invoke the artefact mid-confrontation. It runs well as a one-shot or a palate-cleanser between heavy arcs. Throughout, swap **"the Villain"** for whoever your party is currently chasing, and their lair for your own.
}}


\column

{{text-align:center
![The convention awaits](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/03-arrival-excel.png){width:96%}
}}
:::
{{note
##### At a Glance
* **Level:** ~9 (scales easily; see the DM's Toolkit).
* **Length:** one evening, ~3 hours.
* **Tone:** comedic, non-lethal, improv-friendly.
* **Hook:** the Villain's artefact. **Goal:** win the tournament, claim the Amulet, return.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Part 1: The Departure

{{wide
![A sinister hydra-carved throne](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/01-departure-throne.png){bannerBleed}
}}

{{note
**Location:** The Villain's throne room (use your campaign's lair).
}}
::
**The Villain** looks down on the party from a sinister throne carved like a many-headed hydra. Whatever he once was, he is diminished now—gaunt, his power guttering like a dying candle. He has no interest in a straight fight against foes who blaze with such divine and arcane power.

{{descriptive
"You come to me seeking blood? I have little left to spill. You seek to play the hero? Then go... go to the realm where *everyone* plays the hero, where greatness is nothing but a costume and a painted mask!"
}}

With a trembling hand, the Villain produces the **Amulet of False Realities**. The artefact hums with a chaotic, glitching energy, its surface shifting between gold and cheap plastic. He crushes it in his fist.

![The amulet shatters](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/02-departure-amulet.png){width:100%}

::
The sound is not a magical explosion, but a digital screech—like a corrupted audio file. The air goes cold and dry in an instant. The room dissolves, not into darkness, but into a swirl of green mist that smells of ozone, spilled energy drink, and rotting vegetation.

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Part 2: Arrival at the Convention

:::::::::::::::::::::::::::::::::::::::::::
{{descriptive
**Read Aloud:**
:
"The familiar weight of your own world vanishes in a heartbeat. The air hits your skin—shockingly cold, dry, and smelling of conditioned air and processed sugar. Silence is shattered by a deafening, continuous roar: thousands of voices talking at once, punctuated by electronic beeping and thumping bass music.
:
The mist clears, revealing a cavernous space unlike any dungeon you have ever seen. You stand on a grey carpet in a hall the size of a city. Above, massive metal rafters hold blinding artificial suns that buzz with electricity. Around you, legions of mortals—wizards, soldiers, aliens, and creatures you cannot name—walk in herds, their faces lit by glowing rectangular scrying stones.
:
You look down at your gear. Your *Holy Avenger* looks... painted? The metal lacks its lustre. Your heavy plate armour feels impossibly light, like hardened foam. You have not travelled to the Hells or the Abyss. You have travelled to a **comic convention**."
}}

::
{{note
**Location:** The main hall of an enormous modern convention centre.
}}
{{wide
![Arrival on the convention floor](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/03-arrival-excel.png){bleedBottom}
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# The "Convention Curse" (Global Rules)
In this dimension, the physics of your world are rewritten by the mundane laws of Earth, filtered through the lens of a convention. The following rules apply.

:::
:::
{{note
##### 1. Foam Physics
All weapon damage is reduced to **0**. A greataxe hit does not cleave flesh; it bounces harmlessly off the target. However, the force is real enough to knock someone back. A successful hit pushes the target 5 feet and earns **Style Points** (flavor only).
:
##### 2. Magic as SFX
Spells are transmuted into "Special Effects."

* *Fireball* becomes a burst of harmless glitter and dry ice fog.
* *Thunderwave* is a localized bass drop from hidden speakers.
* *Eldritch Blast* looks like a laser pointer or a smoke ring.

These effects deal **no damage**, but they are visually spectacular.
}}

\column
:::::::::::
{{note
##### 3. Class Fantasy Rule (Agency Fix)
The loss of damage does not mean a loss of agency. While spells don't hurt, **they still impose conditions or distractions.**

* A well-timed *Fog Cloud* still blinds enemies.
* *Thaumaturgy* can rattle the environment to intimidate a rival.
* *Hold Person* might manifest as the target getting their costume snagged on scenery.

***DM Ruling:*** If a player uses a spell creatively to distract, blind, or impede a rival, grant **Advantage** to an ally or impose **Disadvantage** on the Rival.
:
##### 4. The Tether
The artefact keeps one cruel thread tied to home. Healing magic (*Cure Wounds*, *Lay on Hands*, potions) fizzles instantly into stage smoke—the characters **cannot heal** here. It is a constant, nagging reminder that however safe this world feels, whatever doom drove them out is still waiting when they get back.
}}
:::
{{note
##### Style Points & Hype
Foam hits and clever flourishes earn **Style Points**—pure flavour on the floor, but once the Tournament begins they become **Hype**, the only "damage" that matters. Reward Style for in-character commitment, crowd-pleasing description, and creative "powers"; booing, breaking character, or arguing the rules (Chad's whole gimmick) loses it.
}}

{{note
##### What Your Gear Becomes
Magic items don't *work* here—but they still look incredible. When a player asks what their kit does on the floor:
| Magic Item | On the Convention Floor |
|:-----------|:------------------------|
| *+1 Sword* | A flawless foam replica |
| *Wand of Magic Missiles* | A light-up toy that goes "pew pew" |
| *Bag of Holding* | A bottomless tote of merch |
| *Cloak of Elvenkind* | A very good hoodie (Advantage to slip through crowds) |
| *Immovable Rod* | A selfie stick that will not collapse |
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

## Working the Crowd
:
Before the structured encounters, let the party simply *gawk*. Drop these in whenever they wander, stall, or you want to fill time. Roll or pick freely.
:
:::
{{note
##### d20 Random Convention Encounter
| d20 | Encounter |
|:--:|:----------|
| 1 | A child in a full astronaut helmet salutes the Paladin and will not break character. |
| 2 | Two people inside one inflatable T-rex suit are having a very real breakup. |
| 3 | A booth offers to "enhance your aura" (airbrush tattoos—card only). |
| 4 | A staffer mistakes the Druid for an official mascot and hustles them to a photo line. |
| 5 | Free hugs. Aggressively free. |
| 6 | A queue with no visible front or purpose. People keep joining it. |
| 7 | An artist will draw "your OC" for 10 gp (cannot accept gold). |
| 8 | A man speedruns a children's game for a small, intense crowd. |
| 9 | Someone sells bottled "Genuine Dragon Breath" (it's mint). |
| 10 | A panel lets out; a stampede of lanyards. |
| 11 | A vendor swears the prop sword is "battle-ready" (it is foam). |
| 12 | A lost phone glows on the ground, ringing endlessly. |
| 13 | A cosplay-repair station: hot glue, safety pins, a saintly volunteer. |
| 14 | A "psychic" reads the Warlock's patron and gets it *unsettlingly* right. |
| 15 | A flash mob breaks into a dance the party doesn't know. |
| 16 | A fan recognizes the Tiefling as a character and quotes lines at them. |
| 17 | A vending machine eats a coin and dispenses a glowstick. |
| 18 | A heated debate about a show no one present has finished. |
| 19 | A mascot down—someone in a giant suit needs help standing up. |
| 20 | Team Rules Lawyer, posing for photos, "graciously" ignore the party. |
}}

\column
:::::::::::
{{note
##### d12 Overheard at the Con
| d12 | "..." |
|:--:|:------|
| 1 | "I'm not saying it's canon, I'm saying it *should* be." |
| 2 | "Has anyone seen my sword? Foam, about yea big—" |
| 3 | "The panel queue is three hours." |
| 4 | "That's not lore-accurate and it's ruining my day." |
| 5 | "Is the wifi down or is it just me?" |
| 6 | "He paid HOW much for that figure?" |
| 7 | "Meet me by the giant inflatable thing." |
| 8 | "Did you charge your phone? Did you?" |
| 9 | "Security's after someone with a *real* sword." |
| 10 | "I'm in my flop era, cosplay-wise." |
| 11 | "Last call for tournament entry—FINAL call!" |
| 12 | "Don't make eye contact with the timeshare booth." |
}}
::
{{note
##### d6 Artist Alley (a prop to grab)
| d6 | Prop (mundane, but fun) |
|:--:|:------------------------|
| 1 | Foam "+1" longsword (a great photo) |
| 2 | A "legally distinct" plushie |
| 3 | Lanyard of (carrying lots of) Holding |
| 4 | Enamel pin of a god no one recognizes |
| 5 | Bootleg tee with a typo'd catchphrase |
| 6 | A single, very large novelty coin |
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Part 3: The Convention Floor
With the crowd taken in, the party must navigate the "locals" and the strange bureaucracy of the convention.
::::::
### Encounter A: The Prophecy of the Tri-Fandom (The Flyer)
A frantic, exhausted teenager in a neon "EVENT STAFF" t-shirt runs past, aggressively shoving a glossy, brightly colored pamphlet into the Paladin's chest before sprinting away. *(Full-size, printable copies of both sides are in the **Player Handouts** at the back.)*
:::::
{{text-align:center
![The flyer, front](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/04-floor-flyer-1.png){width:74%}
}}
:::::

{{descriptive
##### The Pamphlet Reads:
**"TRI-FANDOM TOURNAMENT! Main Stage! Level 0, Capital Hall!"** *Compete in the Sci-Fi, Retro, and Fantasy Zones!* **GRAND PRIZE:** The Amulet of Restoration! *(Sponsored by Raid: Shadow Legends)*
}}

\column
::::::::::
The party must use their high-level fantasy skills to decipher the strange dialect, bizarre imagery (anime girls, spacemen), and the confusing labyrinth map on the back. Have each player choose how to interpret the "missive" and roll one of the following.

**Intelligence (Investigation or History) DC 15** — reading the strange Common dialect and the meaning of "Sponsored by Raid: Shadow Legends."

* ***Success:*** They deduce that "Tri-Fandom" means three trials, the "Amulet" is their ticket home, and "Shadow Legends" is merely a wealthy merchant guild backing the event.
* ***Fail Forward:*** They read it as a desperate plea for help—"Shadow Legends" are demons raiding the tournament—and tackle the nearest demon cosplayer (0 damage, huge scene), triggering **Encounter B**.

**Wisdom (Survival) DC 15** — reading the labyrinthine convention map.

* ***Success:*** They map the grid and find the quickest route to the stage.
* ***Fail Forward:*** They hold the map upside down, march through a "STAFF ONLY" door into a catering closet, and get Febrezed by a janitor—reeking of "Summer Meadow," they take **Disadvantage on Intimidation** for an hour.

**Intelligence (Religion) DC 14** — interpreting the bizarre white "gods" on the flyer (a squad of white-armoured space-troopers).

* ***Success:*** They realize these are fictional avatars, not deities—no divine retribution to fear.
* ***Fail Forward:*** They take the figures for the local supreme deity and the tournament a holy rite. To avoid wrath they loudly praise **"Hail the Overlord"** as they walk—earning strange looks, and a passing raver who nods and hands them a **Glowstick** (a *Torch* casting neon-blue light).

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### Encounter B: Peace-Bonding
{{wide
![A security guard peace-bonds the party's weapons](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/06-floor-peace-bonding.png){bannerBleed}
}}

:

As the party moves through the crowd, a security guard (human, tired eyes, yellow high-vis vest) steps into their path, holding up a hand.

* **The Guard:** "Oi, mate. Hold up. You can't walk around with those props unsecured. Health and safety regulations. Let's see 'em."
* **Interaction:** Without waiting for permission, he secures their swords into their scabbards with bright orange zip-ties, or ties ribbons around wands and holy symbols.
* **Mechanic:** Drawing a weapon now requires a **DC 10 Strength check** to snap the tie.
* **Failure (Fail Forward):** They snap it by brute force, but it looks incredibly aggressive. The Guard sighs and slaps a neon **"PROP VIOLATION"** wristband on them before waving them through.
  * ***Effect:*** Later, during the Tournament, a Rival can point out the wristband to a judge ("Disqualification! He's unsafe!"), imposing **Disadvantage** on one crucial check.

### Encounter C: The Lore Expert
A teenager in a "Dungeon Master" t-shirt and cat ears approaches the most exotic-looking party member.

* **The Fan:** "Whoa. That is insane. Is that spirit gum or liquid latex? The texture on the horns is flawless. Did you 3D print the core?" He reaches out to poke a horn, tail, or scale without asking.
* **Mechanic:** A **DC 14 Dexterity save** to dodge the poke, or a **Charisma (Intimidation)** check to growl, "Do. Not. Touch."
* **Success:** His eyes go wide. "Whoa... so in character. Awesome." He snaps a selfie and runs off, instantly posting it.

{{text-align:center
![The lore expert](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/07-floor-lore-expert.png){width:60%}
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### Encounter D: The Alchemist
{{wide
![The Potions & Elixirs stall](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/09-floor-alchemist.png){bannerBleed}
}}

{{descriptive
A hand-painted banner reads "POTIONS & ELIXIRS." Behind a counter wreathed in dry-ice fog, a profoundly bored vendor slings glowing slushies and cans of "Thunder-Bull," tapping each sale against a little card reader.
}}

The stall sells two "potions"—and won't take a single gold piece for either.

* **The Vendor:** "Is this a prop coin? *Plastic?* I can't take props, mate. Card or Apple Pay only. Or you got a trade pass?"
* **Getting Paid (pick one):**
  * ***Sleight of Hand (DC 13):*** the Rogue lifts a drink clean off the counter.
  * ***Deception / Persuasion (DC 14):*** pass a 'prop' dagger or ring off as a "limited-edition collectible" worth a trade.
  * ***Performance (DC 12):*** pose for paid selfies with passing fans until you've earned enough "card."

\column

{{descriptive
##### Mana Potion *(blue-raspberry slushie)*
A waxed cup of radioactive-blue ice. *Effect:* the brain-freeze clears your head—on your **next turn only**, add **+1d4** to one check, attack, or save. A second within the hour leaves you **Poisoned** (the sugar shakes) for 10 minutes.
}}

{{descriptive
##### Stamina Potion *(energy drink)*
![Stamina Potion](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/10-item-stamina-potion.png){width:100%}
*Effect:* the sugar-and-caffeine rush grants *Haste* for 1 minute. Immediately after, you suffer 1 level of **Exhaustion** (the crash).
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### Encounter E: The Inciting Rivalry
A group of six cosplayers parts the crowd like a phalanx, shoving bystanders aside with practiced coordination. It is **Team Rules Lawyer**. Chad the Paladin stops in front of the party, sneering at their actual, battle-worn armor.

{{descriptive
"Cute," Chad says, tapping the Fighter's breastplate. "Going for the 'battle-damaged' look? A bit derivative, isn't it? Amateur hour."
:
Behind him, Sneaky Pete giggles, shaking a pouch of glitter. "Bet they didn't even read the rulebook, Chad."
}}

**Meet the Rivals.** As they posture, each tosses a jab—give the players six faces to want to beat:

* ***Chad:*** "Rules are rules. I've read all of them. Twice."
* ***Sneaky Pete*** *(already behind you):* "Boo. ...Kidding. Or am I?"
* ***Legolad:*** "Stand where the light's good—you'll want this clip later."
* ***Bathrobe Wizard*** *(yawning):* "Wake me for the final."
* ***Pizza Guy*** *(mouth full):* "You gonna finish that... dignity?"
* ***Goth Barbarian:*** "...whatever."

* **The Conflict:** "This is *our* con. We've won three years running. Go enter the beginner's bracket."
* **Mechanic:** A **DC 15 Intimidation or Performance check** wipes the smirk off Chad's face. *Success:* the crowd "Ooooohs!" and the party banks **10 Temporary Hype**. *Failure:* Chad shoves past—"See you at the bottom of the leaderboards."

\column

![Team Rules Lawyer parts the crowd](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/11-floor-team-rivalry.png){bleedRight}

{{note
##### Sizing Them Up
A character may make a **Wisdom (Insight) DC 13** as the rivals strut. On a success, reveal one rival's obvious weakness—their *Tactics* line from Appendix A (e.g., Pete bails the round before he'd take a hit; the Wizard does nothing until provoked). Forewarned, the party can plan how to humiliate them later.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Part 4: The Side Quests
*Objective: win items to cheat in the main tournament.*

:::
::::::::::::::
{{note
##### The Clock
The PA system booms overhead: *"Attention cosplayers! The Tri-Fandom Qualifiers begin in 30 minutes! Please report to the staging area!"* — The party has time to attempt only **TWO** of the three side quests. Choose the rewards that serve best.
}}
::
### 1. The VR Horror Booth
{{wide
![The VR horror booth](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/12-sq1-vr-booth.png){bannerBleed}
}}

{{descriptive
On the monitor, a player in a headset claws at the air, mouth open in a silent scream as a glitchy red ghost lunges. A small crowd films it, delighted. A cardboard sign promises: "SURVIVE = PRIZE."
}}

**Setting.** A sleek black kiosk; the headset drops you into a terrifyingly realistic digital dungeon.

**Game.** "Survive the Glitch"—don't scream at the jump-scares.

**Check.** **DC 13 Wisdom saving throw** to realize the ghosts aren't real.

\column

{{note
##### Rival Play — Sneaky Pete
Blind in the headset, the hero never sees **Sneaky Pete** slip behind them to *add his own* scares—a cold breath on the neck, a whispered "*behind you*," a rubber spider down the collar.
* **Impact:** roll the **Wisdom save with Disadvantage.** Pass anyway and Pete shrugs ("worth a shot") and lifts a single harmless prop for later—pure flavour.
}}

{{descriptive
##### Reward: The Tactical Visor
![The Tactical Visor](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/13-item-tactical-visor.png){width:100%}
*(Cheap red plastic sunglasses.)* They filter visual noise—ignore visual penalties (smoke, strobes, fog) in **Zone 1**.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### 2. The Impossible Claw Machine
{{wide
![The impossible claw machine](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/14-sq2-claw-machine.png){bannerBleed}
}}

{{descriptive
Behind the glass, a pile of impossibly cute plushies. The claw hangs limp and loose—obviously rigged. A small child sniffles nearby, pockets turned out, staring at the one that got away.
}}

**Setting.** "Beat the Rig"—a machine engineered to fail.

**Check.** **DC 15 Sleight of Hand** (thieves' tools on the service lock) **OR DC 16 Athletics** (shake a prize into the chute).

\column

{{note
##### Rival Play — Chad
The instant a hero reaches in, **Chad** materialises with a lanyard and a clipboard. "*Excuse me.* Tampering with arcade equipment is a **Section 12** violation." (There is no Section 12.)
* **Impact:** before finishing the check, win a **DC 13 Charisma (Deception or Intimidation)** to wave him off. Fail and a *real* staffer drifts over—the machine "resets," giving **Disadvantage** on the attempt.
}}

{{descriptive
##### Reward: Gamer Grip Gel
![Gamer Grip Gel](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/15-item-grip-gel.png){width:100%}
*(A tube of neon green sticky slime.)* On hands or feet: **Advantage** on physical checks (climbing, gripping, dancing) in **Zone 2**.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### 3. The Debate Club
{{wide
![The debate club](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/16-sq3-debate-club.png){bannerBleed}
}}

{{descriptive
A ring of folding tables, a fortress of energy-drink cans, and a knot of red-faced nerds mid-argument over whether something is "canon." They turn, as one, and fix the party with the stare of people who have *opinions.*
}}

**Setting.** "Fan Theory Debate"—the nerds slam a topic on the table and the party must argue the convoluted "correct" answer (full rulings in **Appendix B**):

* ***The Titan Clash*** — Darkseid's Omega Beams vs. Thanos's Legendary Resistances.
* ***Speed vs. Prep*** — Batman (with Lair Actions) vs. Gear 5 Luffy.
* ***Shield Semantics*** — Captain America's shield vs. Zoro's Haki.
* ***Elemental Standoff*** — Aang vs. Superman.
* ***The Willpower War*** — Cap's Aura vs. Luffy's Conqueror's Haki.

**Check.** **DC 14 Charisma (Persuasion or Deception)**—use D&D logic to build a nonsensical but convincing argument and win the crowd.

\column

{{note
##### Rival Play — Bathrobe Wizard
Roused from a nap by the shouting, the **Bathrobe Wizard** shuffles over and—*appallingly*—knows his stuff. He takes the opposing podium, sighing the entire time.
* **Impact:** the debate becomes a **contested Charisma check vs. the Wizard (+6).** Beat him and the crowd turns; lose and he wins the point, mutters "*obviously,*" and shuffles off to nap (**Disadvantage** if you try again this hour).
}}

{{descriptive
##### Reward: The Spoilers Cheat Sheet
![The Spoilers Cheat Sheet](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/17-item-cheat-sheet.png){width:100%}
*(A crumpled napkin of scribbled notes.)* It holds the trivia answers—an **Auto-Success** on one round in **Zone 3**.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Part 5: The Tri-Fandom Tournament
{{wide
{{note
**Goal:** Collect 3 Tokens to qualify for the Finale.
:
**Opponents:** *Team Rules Lawyer*—Chad, Sneaky Pete, Legolad, Bathrobe Wizard, Pizza Guy, and the Goth Barbarian (full stat blocks in Appendix A).
:
**Rival Interference:** In *each* zone, the team has **1 Interference Token** to impose **Disadvantage** on a check or force a re-roll—bumping elbows, flashing lights, heckling, or spilling soda.
}}
}}
::::::

### Zone 1: A Distant Galaxy
{{wide
![The sci-fi shooting gallery](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/18-zone1-scifi.png){bannerBleed}
}}

:

{{descriptive
A bored staffer in a white space-trooper helmet waves you to the firing line. "Blasters up—no real powers, no exceptions. Targets light up, you shoot 'em. Try not to cry when the turrets shoot back." A klaxon wails; fog rolls across the deck.
}}

**Challenge.** A shooting gallery built like a spaceship corridor. Players hit light-up targets with plastic blasters while dodging "return fire" (foam darts) from automated turrets and the Rivals.

***Mechanics***
* **Attack:** **Ranged Weapon Attack (Dex)** vs. AC 12 targets.
* **Defense:** At the start of the round, a **DC 14 Dexterity save** to dodge the foam hail; failure means you're distracted and lose an action.

***Class Hooks***
* *Monk — Deflect Missiles:* catch a foam dart and fling it back, hitting a target automatically.
* *Caster:* *Fog Cloud*, *Darkness*, or *Minor Illusion* obscures the Rivals' vision (**Disadvantage** on their attacks this round).

***Win Condition.*** Hit 5 targets before the Rivals do.

\column

{{note
##### Rival Play — Legolad
This is **Legolad's** house. He calls every shot ("*...and the crowd goes wild*") and steals the heroes' targets out from under them.
* **Impact:** at the start of each round he tags **one lit target first** (it doesn't count for the heroes). Once this zone he spends the **Interference Token** for **Disadvantage** on a hero's attack—"bad form, mate." Hit 5 anyway and he sulks: **Disadvantage** on his interference in the *next* zone.
}}

{{text-align:center
![Legolad lines up a shot](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/19-rival-legolad.png){width:58%}
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### Zone 2: The Retro Arcade
::::
{{wide
![The retro arcade](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/20-zone2-arcade.png){bannerBleed}
}}

:

{{descriptive
The bass is a physical thing. A neon sign flickers **DANCE OR DIE** (the "DIE" is a sticker over "DEMO"). Beside the dance pad, the High Striker towers, its bell impossibly high, a smug carny leaning on the lever.
}}

**Challenge.** A neon-lit corner with two games: "Dance Dance Revolution" (rhythm) and the "High Striker" (strength hammer). The air smells of ozone and sweat.

***Mechanics***
* **Dance:** **Performance** or **Acrobatics** to keep up with the arrows. The beat accelerates (DC 10 → DC 15 → DC 20).
* **Hammer:** **Strength (Athletics)** vs. DC 18 to ring the bell.

***Class Hooks***
* *Barbarian/Fighter:* spending *Rage* or *Action Surge* smashes the hammer with divine force (**Advantage** or an auto-success).
* *Bard — Bardic Inspiration:* add the die to the Dance score, shouting out the rhythm.

***Win Condition.*** 3 successful checks total.

\column

![Dance Dance Revolution](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/21-zone2-dance.png){width:100%}


{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### Zone 3: The Live Stage (Lore)
{{wide
![The live lore stage](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/23-zone3-stage.png){bannerBleed}
}}

:

{{descriptive
Stage lights blind you; a microphone whines. The Host—a sweating man in a screen-printed tee—shuffles cue cards. "Welcome to LORE QUIZ! Remember, contestants: the *audience* decides what's true, not the rulebook. Begin!"
}}

**Challenge.** The party sits at a panel table under bright lights as the Host fires impossible trivia questions (see Appendix B). The audience watches expectantly.

***Mechanics.*** **Contested Checks** vs. the Rivals. Players may use **Persuasion** (charm the crowd), **Deception** (a convincing lie), **Intimidation** (scare the Host into accepting an answer), or **Performance**.

***Class Hooks***
* *Cleric/Paladin — Zone of Truth (subtly):* forces a Rival to stutter and admit they don't know—an Auto-Win for that round.
* *Warlock/Sorcerer — Minor Illusion:* a visual hologram of the answer dazzles the audience (**Advantage**).

***Win Condition.*** Win 3 rounds of applause.

{{wide
![The panel table under the lights](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/24-zone3-panel.png){bleedBottom}
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Part 6: The Grand Finale
::
{{note
**Location:** The Main Stage—a massive platform with pyrotechnics, a giant screen displaying the party's faces, and a throne for the Head Judge.
:
**The Judge:** **the Dark Lord** (a cosplayer in a high-quality black-armoured villain costume).
:
**The Opponent:** **Team Rules Lawyer** (the full group assembled).
}}

{{note
##### The Judges
***The Dark Lord*** rewards spectacle and punishes hesitation. A committed villain monologue earns bonus Hype—but flinch, and he'll Dread-Grip you for the crowd.
:
***The Host (Zone 3)*** loves a confident *wrong* answer more than a meek right one. Deception and Performance beat raw Knowledge.
}}

\column
::
{{note
##### The Arena (Terrain)
The stage isn't an empty box—break up the fight with:
* **Prop crates** (the marked squares): half cover; climb one for high ground.
* **Speaker stacks** at the corners: total cover, and a *Thunderwave* if toppled (DC 13 Dex or **Prone**).
* **The Judge's desk & throne**: raised ground the Dark Lord rules from.
* **Pyro jets** along the front lip: a 5-ft. line that erupts on a botched flourish (2d10 Hype).
* **Trailing cables & a foam-pit "moat"** off the back: difficult terrain, perfect for a dramatic shove.
}}

{{wide
![The Dark Lord, Head Judge](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/27-finale-darklord.png){bleedBottom}
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

{{text-align:center
![The main-stage battle map — a player handout](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/26-finale-stage-2.png){handoutPortrait}
}}

{{footnote Player Handout — The Main Stage}}
{{pageNumber,auto}}

\page

### Encounter: The Battle for Hype
Instead of health, each team shares a single **"Hype Meter."** **Team Rules Lawyer (the Rivals) start with 150 Hype**—the bigger team, the bigger meter—while **the Heroes start with 120 Hype** (a 4–5-PC party), **plus the +10 Temp Hype** if they beat Chad back in Encounter E (and anything still banked from the zones). Whoever empties the other team's meter first wins the crowd. Adjust either pool by ±30 Hype per PC beyond a 4–5 party (see the DM's Toolkit). Roll initiative as normal.

***Attacks***
* **Standard Hit:** a successful attack deals **1d10 Hype damage**—the crowd cheering a solid hit.
* **Style Bonus:** describe a cool move ("I backflip off the speaker!") to add **+5 Hype damage**.
* **Magic:** damage spells instead force a **Charisma save**. On a fail, the Rivals are "Stunned by the Special Effects" and lose their next turn.

{{text-align:center
![Hype Meter](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/25-finale-stage-1.png){width:100%}
}}

\column

{{note
##### The Dark Lord's Lair Actions
On initiative count 20 (losing ties), the Dark Lord intervenes:
:
1. ***Dread Grip.*** He points at a player. DC 13 Wisdom save or be Restrained by stagehands.
2. ***High Ground.*** He raises a platform. Attacks from the high ground have Advantage.
3. ***Heavy Metal Music.*** He changes the track. All Hype damage is doubled for 1 round.
4. ***Rigging Drop.*** A massive prop block crashes from the roof onto a 10-ft. square (a marked crate, or under a random player). Each creature there makes a **DC 15 Dexterity save**—on a fail, 3d10 Hype and knocked **Prone**; half and no prone on a success. The block remains as a 5-ft. **raised platform** (high ground; Advantage to attack from atop it).
}}

{{note
##### Chad's Home Turf Actions (Champion's Privilege)
As reigning champion, Chad knows the stage crew. On initiative count 10 (losing ties), he triggers one "Accident":
:
1. **"Cut the Mic!"** One spellcasting player is **Deafened** by feedback until the end of their next turn.
2. **"Pyrotechnic Glitch."** A spark fountain erupts under a player. DC 14 Dex save or fall **Prone** (−1d10 Hype).
3. **"Sponsor Break."** Chad downs a "Refreshing Healing Elixir." Team Rules Lawyer regains **2d10 Hype**.
}}

**Victory.** When the Rivals' Hype hits 0, they "die" dramatically—falling over, clutching their chests, overacting. The Dark Lord stands, slow-claps, and awards the party the **Amulet**.

{{wide
{{note
##### d8 Rival Taunt
Roll or pick when a Rival lands a hit or spends Interference (in the zones or here).
| d8 | "..." | d8 | "..." |
|:--:|:------|:--:|:------|
| 1 | "Is that... store-bought?" | 5 | "You're holding the sword wrong." |
| 2 | "My cosplay has *lore*." | 6 | "Smile for the 'gram, loser." |
| 3 | "Source? I need a source." | 7 | "That's not canon and you know it." |
| 4 | "We did this bit two years ago." | 8 | "Cute. Watch a professional." |
}}
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

### The Dark Lord's Gifts
"Impressive," the Dark Lord breathes. "Most impressive. Take these—from my private collection." He tosses three plastic items that keep a spark of magic.

{{descriptive
##### Youngling Slayer 9000
![Youngling Slayer 9000](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/28-item-lightsaber.png){width:100%}
A plastic extendable laser sword. In your world, a **+1 shortsword** that sheds dim red light.
}}

{{descriptive
##### Vocal Processor
![Vocal Processor](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/29-item-vocal-processor.png){width:100%}
A black voice-modulator box. In your world, it grants **Advantage on Intimidation** (the user sounds like a cyborg).
}}

\column
::::::::
{{descriptive
##### Dread Lord Cookies
![Dread Lord Cookies](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/30-item-cookies.png){width:100%}
A tin of black-frosted, helmet-shaped cookies. Acts as a ***Potion of Greater Healing***, but the user must end their next sentence with "...as I foretold."
}}
::
{{note
##### Crossing Back
These three relics keep their spark back home; everything else (the Visor, the Gel, the Stamina cans) is mundane junk the moment the party returns. Hand the players the relic cards as the convention dissolves around them.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Part 7: Epilogue (The Return)
::
{{wide
![The return home](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/31-epilogue.png){bannerBleed}
}}

:

The party gathers around the Amulet and connects the shards together.

{{descriptive
"The world fractures. The roar of the convention hall is silenced instantly, replaced by a heavy, oppressive quiet. The cool, dry air is slammed away by the weight and smell of the place you left.
:
You look down. The foam sword in your hand suddenly drags your arm down with the weight of cold, heavy steel. Your plastic armour bites into your shoulders, solid and real. The magic returns to your blood—hot, dangerous, and lethal.
:
You stand once again where you began. The 'fun' is over."
}}

\column

**The Villain** sits exactly as you left him, perhaps even more diminished. He is shocked to see you return—but, true to his word, he yields.

* He surrenders **whatever you came for**.
* He gives up the next thread of your quest, and your campaign resumes from precisely where it paused.

{{note
##### Back to the Campaign
The interlude leaves no lasting mechanical marks beyond the three relics and whatever bruised egos Team Rules Lawyer inflicted. Resume your campaign exactly where the artefact interrupted it.
}}
::
{{note
##### Callbacks & Consequences
A few threads worth pulling later:
:
* **Chad returns.** Team Rules Lawyer make a perfect recurring rival—a vanity-cursed adventuring party who "did it first."
* **Brief fame.** Someone filmed the finale; an NPC may recognize the party from "that video."
* **Souvenirs.** Each PC keeps one harmless prop. Let them describe it.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Appendix A: The Rivals
Designed to challenge a Level 9 party: high ACs (costume quality) and disruptiveness in place of lethal damage. The whole team shares a single **150-point Hype pool** (their "Ego")—every hit chips the same shared meter. Each block opens with a one-line ***Tactics*** cue for how to play them.

{{monster,frame
![Chad the Paladin](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/32-rival-chad.png){width:80%}
## Chad the Paladin
*Medium humanoid (team leader), lawful evil*
___
**Armor Class** :: 20 (plastic plate + shield)
**Hit Points**  :: Shares Team Pool (Ego)
**Speed**       :: 30 ft.
___
***Tactics.*** Front-runs and lawyers; targets whoever's having the most fun and tries to invalidate it.
:
***Catchphrase.*** *"By the rulebook—page 47, subsection C—I've already won."*
:
***Aura of Smugness.*** Allies within 10 ft. have advantage on saving throws.
:
***Roleplay Police.*** Advantage on saves vs. illusion spells (he points out the wires).
### Actions
***Foam Smite.*** *Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 1d10 + 5 Hype, and the target makes a **DC 16 Constitution save** or is **Blinded** until the end of its next turn.
### Reactions
***"Actually..."*** When a creature he sees casts a spell or uses a feature, Chad argues the rules. The creature makes a **DC 16 Charisma save** or the spell/feature fails and the action is wasted.
}}

\column
:::::::::::::
{{monster,frame
![Sneaky Pete](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/33-rival-sneaky-pete.png){width:100%}
## Sneaky Pete
*Medium humanoid (the rogue), chaotic neutral*
___
**Armor Class** :: 17 (black morph suit + Dex)
**Hit Points**  :: Shares Team Pool (Ego)
**Speed**       :: 40 ft.
___
***Tactics.*** Never fights fair—glitter, flash, sabotage—and vanishes the round before he'd take a hit.
:
***Catchphrase.*** *"You didn't see that. Nobody saw that."*
:
***Evasion.*** On a Dex save for 0 Hype damage, he takes none on a success and half on a failure.
:
***Sneak Attack.*** +4d6 Hype damage if an ally is within 5 ft. of the target.
### Actions
***Foam Dagger.*** *Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 1d8 + 6 Hype.
:
***Glitter Bomb (Recharge 5–6).*** Glitter bursts in a 10-ft. radius within 20 ft.; each creature makes a **DC 16 Dexterity save** or is **Blinded** and glittered (**Disadvantage on Stealth** until a long rest).
### Bonus Actions
***Cunning Action.*** Dash, Disengage, or Hide.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

{{monster,frame
{{text-align:center
![Legolad](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/19-rival-legolad.png){width:44%}
}}
## Legolad
*Medium humanoid (the ranger), neutral competitive*
___
**Armor Class** :: 16 (elven tunic)
**Hit Points**  :: Shares Team Pool (Ego)
**Speed**       :: 35 ft.
___
***Tactics.*** Kites and snipes from range, narrating his own highlight reel.
:
***Catchphrase.*** *"...and the crowd goes WILD as Legolad nails it again!"*
:
***Sharpshooter.*** His ranged attacks ignore half and three-quarters cover.
### Actions
***Multiattack.*** Two Nerf Bow attacks.
:
***Nerf Volley.*** *Ranged Weapon Attack:* +10 to hit, range 80/320 ft. *Hit:* 1d10 + 6 Hype.
### Bonus Actions
***Kiting.*** Disengage and move up to 10 ft.
}}

\column

{{monster,frame
![Bathrobe Wizard](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/34-rival-bathrobe-wizard.png){width:100%}
## Bathrobe Wizard
*Medium humanoid, neutral lazy*
___
**Armor Class** :: 12 (17 with *Cardboard Shield*)
**Hit Points**  :: Shares Team Pool (Ego)
**Speed**       :: 30 ft.
___
***Tactics.*** Does the bare minimum until someone wakes him; then he's annoyingly competent.
:
***Catchphrase.*** *"Ugh, do I have to? ...Fine. I cast Magic Missile."*
### Actions
***"I Cast Magic Missile."*** *Ranged Spell Attack:* auto-hit, three targets. *Hit:* 1d4 + 1 Hype per dart (total 3d4 + 3).
:
***Deep Lore (Recharge 5–6).*** He explains the Spellplague's socioeconomics. Creatures in a 20-ft. cone make a **DC 16 Wisdom save** or fall **Asleep** from boredom (waking on damage or a shake).
### Reactions
***Cardboard Shield.*** When hit, he raises a painted cutout for +5 AC against that attack.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

{{monster,frame
![Pizza Guy](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/35-rival-pizza-guy.png){width:100%}
## Pizza Guy
*Medium humanoid (the brute), chaotic hungry*
___
**Armor Class** :: 18 (tower of pizza-box shield)
**Hit Points**  :: Shares Team Pool (Ego)
**Speed**       :: 30 ft.
___
***Tactics.*** A wall—soaks Hype and shields Chad, mostly by being in the way.
:
***Catchphrase.*** *"You want a piece? ...of pizza? Or of me?"*
:
***Aura of Marinara.*** The floor within 10 ft. is difficult terrain (grease and dropped toppings).
### Actions
***Delivery Slam.*** *Melee Weapon Attack:* +9 to hit, reach 5 ft. *Hit:* 2d8 + 5 Hype (a stale pizza box over the head).
:
***Hot Cheese Slide.*** Molten cheese in a 15-ft. cone; each creature makes a **DC 15 Dexterity save** or falls **Prone**.
### Reactions
***"Order Up!"*** When an ally is hit, he interposes his boxes, reducing the Hype damage by 1d10 + 5.
}}

\column

{{monster,frame
![Goth Barbarian](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/36-rival-goth-barbarian.png){width:100%}
## Goth Barbarian
*Medium humanoid, chaotic angry*
___
**Armor Class** :: 16 (unarmored defense / spikes)
**Hit Points**  :: Shares Team Pool (Ego)
**Speed**       :: 40 ft.
___
***Tactics.*** Doesn't care, which makes him hard to faze and harder to impress.
:
***Catchphrase.*** *"Whatever. This is so derivative."*
:
***Angst (Rage).*** Resistant to Hype damage. Style Points earned against him are halved—"he doesn't care."
:
***Reckless Swing.*** He may gain Advantage on melee attacks; attacks against him then have Advantage until his next turn.
### Actions
***Oversized Foam Zweihander.*** *Melee Weapon Attack:* +9 to hit, reach 10 ft. *Hit:* 2d12 + 5 Hype.
:
***Intimidating Glare.*** One creature within 30 ft. makes a **DC 15 Wisdom save** or is **Frightened** until the end of his next turn.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Appendix B: Trivia & Debate
:::::::::
{{note
##### Zone 3: Trivia Questions (Host)
**Q1.** "In casting *Fireball*, what two organic materials are required?"
*A: Bat guano and sulfur.*
:
**Q2.** "How much movement does it cost a medium creature to stand from prone?"
*A: Half its total speed.*
:
**Q3.** "What spell level is *Fireball*?"
*A: 3rd level.*
:
**Q4.** "A natural 1 on a death saving throw counts as how many failures?"
*A: Two.*
:
**Q5.** "How many feet does one square on the battle grid represent?"
*A: Five.*
:
**Q6.** "Name three of the eight schools of magic."
*A: Any of Abjuration, Conjuration, Divination, Enchantment, Evocation, Illusion, Necromancy, Transmutation.*
:
**Q7.** "What does a creature's Strength score multiplied by 15 give you?"
*A: Its carrying capacity in pounds.*
}}

\column

### Side Quest 3: Debate Topics (Nerds)
Each "resolved" statement is a trap; the Nerds accept only the convoluted ruling that follows.

:::
{{note
***The Titan Clash.*** "Darkseid's Omega Beams (Magic Missile) bypass Thanos's Legendary Resistances."
*Accepted ruling:* Legendary Resistance burns on the Omega Effect's Banishment, leaving Thanos open to melee.
:
***Speed vs. Prep.*** "Batman (with Lair Actions) defeats Gear 5 Luffy (Immune to Bludgeoning)."
*Accepted ruling:* On initiative 20, Batman floods the room with seawater; Luffy has disadvantage on all saves and loses his immunity.
:
***Shield Semantics.*** "Captain America's Shield (Adamantine/Antimagic) cannot be cut by Zoro's Haki (+3 Weapon)."
*Accepted ruling:* Vibranium is Artifact-level; Haki is merely +3. Artifacts can't be destroyed by non-gods. The shield holds.
:
***Elemental Standoff.*** "Aang (Hold Person/Wisdom Save) defeats Superman (Vulnerable to Magic) before Supes wins Initiative."
*Accepted ruling:* Aang enters the Avatar State as a bonus action and has 'Alert'; *Hold Monster* (Blood Bending) lands because Superman has no Wisdom proficiency.
:
***The Willpower War.*** "Whose Paladin Aura is stronger—Captain America (Aura of Protection) or Luffy (Conqueror's Haki)?"
*Accepted ruling:* Cap's Legendary Saves tank Luffy's Haki; he then inspires the party and wins on support utility.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Appendix C: The Cosplay Spellbook
In this realm, magic is purely visual. Damage is 0, but the *implication* of power is everything. Below are common class features re-flavored for the convention—use them as templates and improvise the rest.
::
### Paladin (Oath of the Convention)
::
{{note
***Divine Smite — Flashbulb Smite.*** A flashlight taped to your foam blade strobes on a hit. Deals Hype; on a crit, the lens flare blinds the target.
:
***Aura of Vitality — Motivational Speaker.*** A 30-ft. radius of "Good Vibes" restores **Ego** (Temp Hype) to allies who can hear your affirmations.
:
***Revivify — The "Get Up" Scene.*** You scream "Don't you die on me—the sequel's greenlit!" at a "fallen" ally, who stands with 1 Hype.
}}

::

### Cleric (Domain of the Fandom)
::
{{note
***Sacred Flame — Spotlight.*** The lighting crew drops a beam on the target; they sweat under the attention (Dex save or −1d4 Hype).
:
***Spirit Guardians — Orbiting Plushies.*** Spectral mascots swirl around you; the area is difficult terrain for annoyed enemies.
:
***Guardian of Faith — Cardboard Standee.*** A life-sized celebrity cutout. Rivals are too starstruck to approach a 10-ft. area.
}}

\column
::::::::
### Barbarian (Path of the Main Character)
::
{{note
***Rage — Method Acting.*** You commit so hard the crowd believes it: Advantage on Intimidation-based Hype, resistance to "embarrassment."
:
***Reckless Attack — Going Off-Script.*** Advantage on your Style roll, but Rivals get Advantage to interfere this round.
}}
::
### Fighter (The Prop Master)
::
{{note
***Action Surge — Quick Change.*** Whip out a second prop mid-combo for an extra Style action.
:
***Second Wind — Crowd Work.*** A flex and a wink regain a burst of Ego (Temp Hype).
}}
::
### Rogue (Influencer)
::
{{note
***Sneak Attack — Photobomb.*** Slide into a Rival's shot for bonus Hype if an ally is "set up" nearby.
:
***Cunning Action — Crowd Surf.*** Dash, Disengage, or Hide into the press of bodies.
}}
::
### Monk (Way of the Cosplay Combatant)
::
{{note
***Flurry of Blows — Combo Finisher.*** A blur of foam strikes, each "hit" pure spectacle.
:
***Deflect Missiles — Nerf Return.*** Catch a foam dart and fling it back for a crowd-pleasing reversal.
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Appendix C: The Cosplay Spellbook (cont.)
:
### Ranger (The Lore Gatekeeper)
::
{{note
***Favored Enemy — "Um, Actually."*** Pick a fandom; Advantage on Lore (Zone 3) checks about it.
:
***Hunter's Mark — Calling Your Shot.*** Predict your win over one Rival; +Style whenever you land a hit on them.
}}
::
### Bard (Hype Man)
::
{{note
***Bardic Inspiration — Chant.*** Hand an ally a die of crowd energy for any tournament check.
:
***Cutting Words — Heckle.*** Subtract from a Rival's Style or attack with a perfectly-timed burn.
}}
::
### Wizard (The Rules Lawyer's Bane)
::
{{note
***Counterspell — "Well, Actually."*** Out-pedant a Rival mid-bit; they lose the action (contested Charisma).
:
***Prestidigitation — Practical FX.*** Tiny harmless effects—sparks, smells, glitter—for free Style.
}}

\column
:
### Sorcerer (Main-Stage Diva)
::
{{note
***Metamagic — Pyro.*** "Twin" or "Heighten" an effect into a bigger light show for extra Hype.
:
***Wild Magic — Technical Difficulties.*** On a flourish, roll a d20; odd = a hilarious malfunction that *still* wins the crowd.
}}
:
### Warlock (Sponsored Content)
::
{{note
***Eldritch Blast — Laser Show.*** Twin beams of harmless light; spectacular, never lethal.
:
***Pact Patron — The Sponsor.*** Once per zone, invoke your "sponsor" for a re-roll—at the cost of shouting their slogan.
}}
::
### Druid (The Fursuiter)
::
{{note
***Wild Shape — The Suit.*** Don a full-body costume: Advantage on Performance, Disadvantage on anything needing fingers.
:
***Thorn Whip — Cable Management.*** Yank a Rival off their mark with a "loose AV cable."
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Appendix D: Loot & Magic Items
::::

### Convention Loot (Usable in Dimension Only)
:
{{descriptive
##### Stamina Potion (Energy Drink)
*Potion, common.* A dented can of "Thunder-Bull" that tastes of battery acid and syrup. Grants *Haste* for 1 minute (no concentration). When it ends, you suffer 1 level of **Exhaustion**.
}}

{{descriptive
##### The Tactical Visor
*Wondrous item, common (requires attunement).* Cheap red plastic sunglasses. While worn here, you ignore lightly and heavily obscured areas from visual effects (smoke, fog, strobes) and have Advantage vs. being **Blinded** by light.
}}

{{descriptive
##### Gamer Grip Gel
*Wondrous item, common (consumable).* A tube of lime-scented neon slime. As an action, apply to hands or feet: for 1 hour, Advantage on Athletics to climb/grapple and Acrobatics to keep balance.
}}

{{descriptive
##### The Spoilers Cheat Sheet
*Wondrous item, common (consumable).* A crumpled napkin of pop-culture scribbles. Auto-succeed on one Int (History or Arcana) check about "Fandom Lore" (Zone 3). The ink then smears illegible.
}}

\column
::::
### Dread Relics (Persist in Your World)
{{descriptive
##### Youngling Slayer 9000
*Weapon (shortsword), uncommon.* A plastic hilt that extends a beam of hard light. **+1** to attack and damage. As a bonus action, it sheds dim red light in a 10-ft. radius.
}}

{{descriptive
##### Vocal Processor
*Wondrous item, rare.* A black box worn at the neck that synthesizes your voice into a terrifying cyborg's. **Advantage on Charisma (Intimidation)**, but **Disadvantage on Charisma (Persuasion)**—you sound like a villain.
}}

{{descriptive
##### Dread Lord Cookies
*Potion, uncommon.* A tin of black-frosted, helmet-shaped cookies (1d4 + 1 of them). Eating one acts as a *Potion of Greater Healing* (4d4 + 4 HP). *Curse:* afterward you must end your next sentence with "...as I foretold."
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Appendix E: DM's Toolkit
:::
{{note
##### Quick Reference: Checks & Rewards
| Beat | Check / DC | On Success |
|:-----|:-----------|:-----------|
| Flyer — read it | DC 15 Int (Inv./Hist.) | Grasp the tournament |
| Flyer — the map | DC 15 Wis (Survival) | Fast route to stage |
| Flyer — the "gods" | DC 14 Int (Religion) | They're fictional |
| Peace-Bonding | DC 10 Str | Draw a weapon |
| Lore Expert | DC 14 Dex / Intimidation | Avoid the poke |
| Inciting Rivalry | DC 15 Intim./Perf. | +10 Temp Hype |
| VR Booth | DC 13 Wis | Tactical Visor |
| Claw Machine | DC 15 SoH / 16 Ath | Gamer Grip Gel |
| Debate Club | DC 14 Cha | Cheat Sheet |
| Zone 1 (Sci-Fi) | Atk vs AC 12; DC 14 Dex | 5 targets first |
| Zone 2 (Arcade) | Perf/Acro; DC 18 Str | 3 successes |
| Zone 3 (Lore) | Contested Cha | 3 applause |
| Finale | Hype 150 → 0 | The Amulet |
}}
::
{{note
##### Scaling the Encounter
* **Party size.** The Finale assumes 4–5 PCs—**Rivals 150 Hype, Heroes 120 Hype**. Adjust **both pools by ±30 Hype per PC** beyond that.
* **Power level.** Lower-level: drop social/skill DCs by 2, Hype pool to 100. Min-maxed: raise zone DCs by 2 and give each Rival a second Interference Token.
* **Time-crunched.** Cut Side Quests to one pick, or narrate two zones and play only the one the party is built for.
}}

\column
:::
{{note
##### Pacing (one evening, ~3 hrs)
* Departure & Arrival — 10 min
* Convention Floor (A–E) — 45 min
* Side Quests — 30 min
* Tournament (3 Zones) — 45 min
* Grand Finale — 30 min
* Epilogue — 10 min
}}

::
{{descriptive
##### Scoreboard — print or copy
| Zone | Won? | Token | Interference used |
|:-----|:----:|:-----:|:-----------------:|
| 1 — Sci-Fi |  |  |  |
| 2 — Arcade |  |  |  |
| 3 — Lore |  |  |  |
:
**Temp Hype from Rivalry:** ☐ +10
:
**Finale Hype** — Heroes 120 (+10) / Rivals 150
}}

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

# Appendix F: Cinematic Screen Prompts
Use these *Nano Banana* prompts to (re)generate the 16:9 backgrounds. Every prompt closes with: *"The art style is clean comic book illustration with bold lines and cel-shading. High resolution, 16:9 aspect ratio."*
::::
#### 1. The Villain's Throne Room
A cinematic wide shot of a sinister fantasy throne room. In the center, a menacing iron throne carved like a many-headed hydra. Behind it, a stone wall with a large painted symbol. Swirling eerie green mist, lit by torchlight.

#### 2. The Convention Hall
A wide establishing shot of a massive modern convention centre. High ceilings, metal rafters, blinding artificial lights. A grey carpeted floor packed with a colorful crowd of cosplayers. A banner reads "COMICON." Chaotic and vibrant.

#### 3. VR Horror Booth
A medium shot of a convention VR-demo booth. A sleek black kiosk holds a monitor with a glitchy red ghost face; a headset hangs from the stand. Dim red lighting. A cardboard sign reads "SURVIVE = PRIZE."

#### 4. Claw Machine
A close-up of a bright arcade claw machine. Through the glass, round anime-style plushies; the claw above looks flimsy. The joystick console glows neon. Blurred convention hall behind.

#### 5. Debate Club
A messy folding table—scattered comics, empty energy-drink cans, crumpled napkins. Behind it, a whiteboard with a complex flowchart and "THEORY CONFIRMED." Harsh fluorescent light.

\column
:::::::::::
#### 6. Zone 1: Sci-Fi Corridor
A view down a mock spaceship corridor of plastic and wood. White modular walls with glowing blue LED strips and blast doors. Fog machines pump haze. Cardboard white-armoured trooper standees in the distance.

#### 7. Zone 2: Retro Arcade
A vibrant retro gaming corner. In front, a rhythm-dance arcade cabinet with a metal arrow-panel floor pad. Beside it, a towering carnival hammer strength-tester. Neon pink and blue light.

#### 8. Zone 3: Lore Quiz Stage
A view from the audience up at a convention panel stage. A long black-draped table with three microphones, water bottles, name placards. A backdrop banner reads "LORE QUIZ." Stage lights on empty seats.

#### 9. Finale: The Main Stage
An epic low-angle shot of a massive main stage. A long black platform lit by blinding purple and gold spotlights and pyrotechnic sparks. A giant LED screen displays a fiery "VS" logo. To the side, an elevated judge's desk with a red buzzer. High-energy, dramatic.

{{footnote The Realm of the False Heroes}}
{{pageNumber,auto}}

\page

{{wide
![Player Handout — the Tri-Fandom flyer, front](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/04-floor-flyer-1.png){width:100%}
}}

{{footnote Player Handout — The Flyer (Front)}}
{{pageNumber,auto}}

\page

{{wide
![Player Handout — the convention map, reverse](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/05-floor-flyer-2.png){width:100%}
}}

{{footnote Player Handout — The Flyer (Reverse / Map)}}
{{pageNumber,auto}}


\page

{{backCover}}

# Convention Chronicles #1
::::
All content by Basho of outsidecontext.com

___

For use with any fantasy roleplaying ruleset. Play the best game of your life!

![Basho character designs](https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/11-floor-team-rivalry.png){position:absolute,bottom:0,right:-250px,height:100%}

{{logo
![](https://homebrewery.naturalcrit.com/assets/naturalCritLogoWhite.svg)

Homebrewery.Naturalcrit.com
}}