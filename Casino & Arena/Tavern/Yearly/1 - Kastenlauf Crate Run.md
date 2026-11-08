---
venue: tavern
schedule:
  - yearly
players: Teams of 2 (PCs or NPCs); any number of teams
checks:
  - Strength (Athletics)
  - Constitution saving throw
status: draft
---

# Kastenlauf Crate Run

> **Pitch (read aloud):** *Dawn on the first day of Brewfest. Two by two, teams hoist a full crate of ale between them and set off through the city streets. The rule is simple: cross the finish line first, and the crate must be empty when you get there.*

**Description:** A yearly race through the city for teams of two, run at dawn on the first day of **Brewfest**, the tavern's yearly festival (its big night is [[1 - King of the Drunks|King of the Drunks]]). Each team carries a **crate of 12 bottles** over a course of **10 stretches**, and the crate must be **empty** by the finish. The more you drink, the lighter the crate gets, but the drunker you get. A team that drinks too fast can stagger out of the race; a team that drinks too slowly crosses the line with bottles left and has to stop and finish them.

## How to Play

### The course

- **About a mile of city streets**, from the tavern door and back again. The finish line is the tavern door.
- It's split into **10 stretches** of about 150 yards each.
- **Each round**, every team tries to cover one stretch. A round here is one stretch of the race (a couple of minutes), not a 6-second combat round.

### Setting up

- Each team has two partners and one **crate of 12 half-litre bottles of ale**, packed by the House.
- Every team starts at the tavern door, with **0 stretches** covered.
- Each partner keeps their own count of **bottles finished** and their own place on the Drunk Track.

### A round, step by step

All teams play each round at the same time.

1. **Drink (optional).** The team stops and may drink **up to 3 bottles**, split between the partners however they like. For each bottle, the drinker makes a **Constitution saving throw**. The DC is **5 + the number of bottles that drinker has already finished** (their 1st bottle is DC 5, their 2nd DC 6, their 6th DC 10).

   - **Success:** the bottle is finished. Nothing else happens.
   - **Failure:** the bottle is still finished (it's empty and comes out of the crate), but the drinker marks **1 failure** on the Drunk Track (**2** on a natural 1). Failures add up over the race: at 2 the drinker is **Drunk**, and at 3 they're **Out** (see below).
   - Pass or fail, the bottle counts toward that drinker's finished bottles, so their next DC is 1 higher.
2. **Carry.** The team picks up the crate and tries to cover the next stretch. One partner makes a **Strength (Athletics)** check. If both partners carry, one handle each, the check has **advantage**. A partner who is Drunk (poisoned) makes the check with disadvantage; if both carry, the advantage and disadvantage cancel.

   | Bottles left in the crate | Carry DC |
   |---|---|
   | 10–12 | 12 |
   | 7–9 | 11 |
   | 4–6 | 10 |
   | 1–3 | 9 |
   | 0 | 8 |

   - **Success:** the team covers the stretch.
   - **Failure:** the team stumbles, sets the crate down, and doesn't get anywhere this round.
3. **Next round.**

### When a partner drops Out

A partner who reaches **Out** (3 failures) can still stagger along, but they **can't drink or carry**. The other partner carries on alone: they drink every remaining bottle and carry the crate by themselves (no advantage). If **both** partners are Out, the team is eliminated.

### Winning

- The first team to **finish the 10th stretch with an empty crate** wins.
- A team that finishes the 10th stretch with bottles left must stand at the finish line and drink them (still up to 3 per round) before they count as finished.
- **Two teams finish in the same round:** the team with fewer total failures on the Drunk Track wins. If that ties too, they share first place.

### Drunk Track

![[Drunk Track#Rules]]

## Dice Examples

**Team Stonejaw:** Thokk (NPC, Athletics +5, Con save +5 with advantage from Dwarven Resilience) and Mirela (PC, Athletics +0, Con save +1).

**Round 1** (12 bottles in the crate)
- Thokk drinks his 1st bottle (DC 5): rolls **9** and **14**, keeps 14: 14 + 5 = **19**. Pass.
- Mirela drinks her 1st bottle (DC 5): **7** + 1 = **8**. Pass.
- Thokk drinks his 2nd bottle (DC 6): **3** and **11**, keeps 11: 11 + 5 = **16**. Pass.
- 9 bottles left, so the carry DC is **11**. Thokk makes the check, and both carry (advantage): **6** and **13**, keeps 13: 13 + 5 = **18**. **Stretch 1 covered.**

**Round 2** (9 bottles)
- Mirela drinks her 2nd bottle (DC 6): **natural 1**. **2 failures: Mirela is Drunk** (poisoned).
- Thokk drinks his 3rd bottle (DC 7): **15** and 2, keeps 15: **20**. Pass.
- Mirela drinks her 3rd bottle (DC 7): **10** + 1 = **11**. Pass.
- 6 bottles left, so the carry DC is **10**. Thokk makes the check (he's sober), and both carry: **4** and **8**, keeps 8: 8 + 5 = **13**. **Stretch 2 covered.**

**Round 3** (6 bottles)
- The team decides Mirela shouldn't drink again. Thokk drinks his 4th, 5th and 6th bottles (DC 8, 9 and 10), rolling with advantage each time. He keeps **12** (12 + 5 = 17), **18** (23) and **7** (12). All pass.
- 3 bottles left, so the carry DC is **9**. Thokk: **2** and **10**, keeps 10: **15**. **Stretch 3 covered.**

**Edge case: carrying on alone**
- In round 4, Mirela insists on drinking a bottle (her 4th, DC 8): **5** + 1 = **6**. Her 3rd failure: **Mirela is Out.**
- Thokk must drink the last 2 bottles himself and carry the crate alone, with no advantage, for every stretch left. The empty crate is DC 8, so at +5 he needs a 3 or better each round.

## Prizes & Stakes

- **Entry:** 4 gp per team.
- **First place:** 60% of all entries, and the team's names burned into the Kastenlauf crate that hangs over the bar.
- **Second place:** 20% of all entries.
- **The House keeps:** 20% of entries, the bottles, and its cut of spectator bets.

![[Spectator Betting#Betting Pool]]

## Odds

**Carrying the crate** (Athletics):

| Athletics | Full crate (DC 12) | Full, both carrying | Empty crate (DC 8) | Empty, both carrying |
|---|---|---|---|---|
| +3 | 60% | 84% | 80% | 96% |
| +5 | 70% | 91% | 90% | 99% |

**The whole race** (both partners drinking evenly, 3 bottles a round):

| Team | Chance both drop Out | Chance one finishes alone | Average rounds to finish |
|---|---|---|---|
| Athletics +0, Con +0 | 30% | 34% | 16 |
| Athletics +3, Con +2 | 13% | 30% | 12 |
| Athletics +5, Con +3 | 7% | 25% | 11 |

**Drinking early pays off.** The crate gets lighter and the first bottles are easy.

## Rulings & Cheating

### Fair Play: what's allowed

- Any split of the drinking between partners, and any choice of who makes the carry check each round.
- Dwarven Resilience and other natural traits.
- Cheering, singing and stopping to wave at the crowd.

### What counts as cheating

- **Any spell or magic** on the drinkers or the crate, such as *bless*, *lesser restoration*, *protection from poison*, *enhance ability*, *guidance*, Bardic Inspiration or *Tenser's floating disk*.
- **Pouring out a bottle** instead of drinking it.
- Tripping or jostling another team, or bribing the House to tamper with a rival's crate.

### How to cheat (and how you get caught)

Each cheat is one **contest against the Course Watcher's Wisdom (Perception) +5**. **Ties go to the Watcher.** (Course Watchers walk the streets alongside the teams.) The party can help, but each person who tries a cheat makes their own roll and risks being caught.

| Cheat | Who can do it | Roll vs the Watcher | If it works |
|---|---|---|---|
| **Pour out a bottle** | Either partner | Dex (Sleight of Hand) | The bottle counts as one of their finished bottles, with no save |
| **Hidden spell or cheer**: *bless* cast from up to 30 ft away, or Bardic Inspiration shouted as a cheer from up to 60 ft away | A caster or bard in the crowd | Cha (Deception) to pass the casting or the cheer off as ordinary crowd noise. Subtle Spell gives advantage on *bless*. | *Bless*: both partners add 1d4 to their drinking saves this round. Bardic Inspiration: one partner adds the die to one drinking save. |
| **Trip a rival carrier**, made to look like an accident in the crowd | Anyone in the crowd | Cha (Deception) | The rival's carry check has disadvantage this round |
| **Bribe the crate-packer** (5 gp) to pack a rival's crate with strong ale | Anyone, before the race | Cha (Persuasion) | The rival team has disadvantage on every drinking save |

### Spotting a cheat

![[Cheating Penalties#Spotting a Cheat]]

### Caught cheating: penalties

The Kastenlauf Crate Run is a **special public event**. Penalties apply to the cheater **and** to any accomplice who is caught. A cheating team is disqualified as a whole.

![[Cheating Penalties#Special Public Events]]

| Fine | Or days in the stocks / serving the event |
|---|---|
| 40 gp | 4 days |

### Cheating dice example

In round 3, Mirela tries to pour her bottle into a gutter instead of drinking it.
- Mirela: Sleight of Hand **11** + 2 = **13**. The Watcher: **9** + 5 = **14**. **Caught.**
- Team Stonejaw is disqualified. Mirela is banned from next year's run, her portrait goes on the Cheater's Wall, the town crier reads her name, and she pays double for drinks citywide.
- To clear her name: 40 gp, 4 days in the stocks or serving at next Brewfest, or wait a year.

## Hooks / NPCs

- **The Hammerfall twins** have won four years running. This year one of them is missing, and the other needs a partner by dawn.
- **A rival brewery** has swapped a crate for one with stronger ale. Someone on the course is going down hard.
