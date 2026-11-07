---
venue: tavern
schedule:
  - weekly
players: Two teams of 2–5 (PCs or NPCs)
checks:
  - Ranged attack roll (ball)
  - Dexterity (Acrobatics) or Strength (Athletics)
  - Constitution check
  - Constitution saving throw
status: draft
---

# Flunkyball

> **Pitch (read aloud):** *Two teams face each other down a lane in the yard behind the tavern, each player with a full bottle at their feet. In the middle stands a single empty bottle. Knock it over, and your whole team drinks, as fast as they can, while the other team's runner sprints out to stand it back up.*

**Description:** A weekly team drinking game from the student taverns, played in the yard behind the tavern. Teams take turns throwing a ball at a **target bottle** in the middle of a lane. On a hit, **the whole throwing team drinks** from their own bottles while **the other team's runner** sprints to the target bottle, stands it up and sprints back. **Drinking stops when the runner is back.** A slow runner gives the throwing team more time to drink. **The first team to empty every bottle wins.**

## How to Play

### The lane

```
        TEAM A                                          TEAM B
     (stand here)                                    (stand here)
          |                                               |
   A1  ▯  |                                               |  ▯  B1
   A2  ▯  |<-------- 20 ft -------->  ◉  <------- 20 ft -->|  ▯  B2
   A3  ▯  |                     target bottle             |  ▯  B3
          |                                               |
          |<------------------- 40 ft lane -------------->|

   ▯ = each player's own bottle, at their feet
```

- **One lane, 40 feet long.** Each team stands behind its own end line.
- **The target bottle** (empty) stands in the exact middle, **20 feet from each team**.
- **Every player** has their own full **half-litre bottle** at their feet. It holds **6 gulps**.
- **Each team picks a runner.** Toss a coin to see which team throws first.

### A throw, step by step

1. **Team A throws.** One player (take turns within the team) makes a **ranged attack roll** with the ball: Dexterity modifier + proficiency bonus (everyone counts as proficient). The target bottle has **AC 14**.
   - **Miss:** nothing happens. Team B throws next.
   - **Hit:** the target bottle falls over. Go to step 2.
2. **Team A drinks.** Every player on Team A picks up their own bottle and drinks as fast as they can.
3. **At the same time, Team B's runner runs.** The runner has to:
   1. run 20 feet from Team B's line to the target bottle;
   2. stand the bottle back up and pick up the ball;
   3. run 20 feet back behind Team B's line.
4. **When Team B's runner is back behind their line, Team A stops drinking** and puts their bottles down.
5. **Team B throws next.**

### Timing the run

Time is counted in **rounds**, and **a round is 6 seconds**. In each round, the runner can:
- **move** up to their speed (most people move 30 feet a round), split before and after standing the bottle up;
- **try once to stand the bottle up.** This is a **DC 12 Dexterity (Acrobatics) or Strength (Athletics)** check, and it **takes the runner's action**, so they can't Dash that round. If the check fails, the bottle falls over again, and the runner tries again next round.

| Runner | Round 1 | Round 2 | Round 3 | Team A drinks for |
|---|---|---|---|---|
| **Speed 30 ft**, stands it up first try | Runs 20 ft to the bottle, stands it up, runs 10 ft back | Runs the last 10 ft | | **2 rounds** |
| **Speed 30 ft**, fails the first try | Runs 20 ft to the bottle, fails | Stands it up, runs 20 ft back | | **2 rounds** |
| **Speed 30 ft**, fails twice | Runs 20 ft to the bottle, fails | Fails again | Stands it up, runs 20 ft back | **3 rounds** |
| **Speed 40 ft**, stands it up first try | Runs 20 ft, stands it up, runs 20 ft back | | | **1 round** |
| **Speed 40 ft**, fails the first try | Runs 20 ft to the bottle, fails | Stands it up, runs 20 ft back | | **2 rounds** |

**A bonus-action Dash** (for example, a rogue's Cunning Action) gives a 30 ft runner the extra movement of a 40 ft one.

### Drinking

**Each round Team A drinks**, every player on Team A makes a **Constitution check, DC 12**.
- **Success:** you drink **2 gulps** that round.
- **Failure:** you drink **1 gulp**.
- **Once your bottle is empty**, you stop.

### Winning

**The moment every bottle on a team is empty, that team wins.**

### After the match: Constitution saves

When the match ends, every player who drank **at least 3 gulps** (half a bottle) makes **one Constitution saving throw at DC 10** for the Drunk Track. Winners and losers both save. A player who is already **Out** from earlier games can't play.

### Drunk Track

![[Drunk Track#Rules]]

**Being Drunk hurts here:** a player who comes in Drunk from an earlier game has disadvantage on their throws (attack rolls), their runs and their drinking (both are ability checks).

## Dice Examples

**Team Party:** Quill (throw +5, Con check +1, Con save +1; runner: speed 30 ft, Acrobatics +5), Mirela (throw +4, Con check +1, Con save +1) and Thokk (throw +1, Con check +3, Con save +5 with advantage).
**Team Brewers** (three NPC apprentices): throw +3, Con check +2, Con save +2. Their runner has speed 40 ft and Athletics +3.
Team Party throws first. Everyone starts with **6 gulps**.

**Throw 1, Team Party** (Quill throws): **12** + 5 = **17**. Hits AC 14!
- **The Brewers' runner:** round 1, runs 20 ft and tries: **6** + 3 = **9**. ✗ Round 2: **14** + 3 = **17**. ✓ Runs 20 ft back. **Team Party drinks for 2 rounds.**

| Team Party | Round 1 | Round 2 | Gulps left |
|---|---|---|---|
| Quill | **13** + 1 = 14 ✓ 2 gulps | **5** + 1 = 6 ✗ 1 gulp | **3** |
| Mirela | **8** + 1 = 9 ✗ 1 gulp | **15** + 1 = 16 ✓ 2 gulps | **3** |
| Thokk | **10** + 3 = 13 ✓ 2 gulps | **17** + 3 = 20 ✓ 2 gulps | **2** |

**Throw 2, Team Brewers:** **10** + 3 = **13**. Miss.

**Throw 3, Team Party** (Mirela throws): **15** + 4 = **19**. Hit!
- **The Brewers' runner:** round 1, runs 20 ft and tries: **16** + 3 = **19**. ✓ Runs 20 ft back in the same round. **Team Party drinks for 1 round.**

| Team Party | Round 1 | Gulps left |
|---|---|---|
| Quill | **11** + 1 = 12 ✓ 2 gulps | **1** |
| Mirela | **4** + 1 = 5 ✗ 1 gulp | **2** |
| Thokk | **9** + 3 = 12 ✓ 2 gulps | **0**, done |

**Throw 4, Team Brewers:** **18** + 3 = **21**. Hit!
- **Quill runs:** round 1, runs 20 ft and tries: **4** + 5 = **9**. ✗ Round 2: **13** + 5 = **18**. ✓ Runs 20 ft back. **The Brewers drink for 2 rounds.**

| Team Brewers | Round 1 | Round 2 | Gulps left |
|---|---|---|---|
| Brewer 1 | **14** + 2 = 16 ✓ 2 gulps | **15** + 2 = 17 ✓ 2 gulps | **2** |
| Brewer 2 | **12** + 2 = 14 ✓ 2 gulps | **10** + 2 = 12 ✓ 2 gulps | **2** |
| Brewer 3 | **7** + 2 = 9 ✗ 1 gulp | **13** + 2 = 15 ✓ 2 gulps | **3** |

**Throw 5, Team Party** (Thokk throws): **13** + 1 = **14**. Meets AC 14. Hit!
- **The Brewers' runner:** **11** + 3 = **14**. ✓ First try, back in 1 round. **Team Party drinks for 1 round.**
- Quill: **3** + 1 = 4 ✗ 1 gulp, his last. Mirela: **12** + 1 = 13 ✓ 2 gulps, her last. Thokk is already empty.
- **Every Team Party bottle is empty. Team Party wins!**

**Constitution saves** (DC 10; everyone drank at least 3 gulps)
- Quill: **12** + 1 = **13**. Pass.
- Mirela: **6** + 1 = **7**. Fail: **Tipsy**.
- Thokk: advantage, **4** and **16**, keeps 16: 16 + 5 = **21**. Pass.
- Each Brewer rolls too.

**Edge case: a Drunk player.** If Mirela had come in Drunk from an earlier game, she'd roll with disadvantage on her throws, her drinking and any run. On throw 3: **15** and **8**, keeps 8: 8 + 4 = **12**. A miss, and the Brewers would throw next.

## Prizes & Stakes

- **Entry:** 3 gp per team.
- **Winning team:** 80% of both entries.
- **The House keeps:** 20% of entries and every bottle sold.

![[Spectator Betting#Betting Pool]]

## Odds

**Teams of 3** (100,000 simulated matches). Unless a line says otherwise, every team has throw +3, Con check +1, and a runner with speed 30 ft and +4 on the stand-up.

**How long the run takes** (stand-up +4):

| Runner | 1 round | 2 rounds | 3 rounds or more | Average |
|---|---|---|---|---|
| Speed 30 ft | never | 88% | 12% | 2.2 rounds |
| Speed 40 ft | 65% | 23% | 12% | 1.5 rounds |

**A match:**
- **Hit chance** against AC 14: 50% at +3, 55% at +4, 65% at +6.
- **Each hit** gives the throwing team about **2.7 gulps each**.
- **A match lasts about 7 throws**, and the winning team needs **2 or 3 hits**.

**What wins matches** (chance to beat an otherwise equal team, averaged over who throws first):

| Edge | Win chance |
|---|---|
| Throwing first | 57% |
| A 40 ft runner against a 30 ft runner | **68%** |
| Throwers at +6 against +2 | **69%** |
| Drinkers at Con +3 against Con +0 | 57% |

**A fast runner is worth as much as good throwers.**

## Rulings & Cheating

### Fair Play: what's allowed

- Any throwing style, overarm or underarm.
- Choosing your fastest player as runner.
- Bonus-action Dash, such as a rogue's Cunning Action.
- Dwarven Resilience on the Constitution saves. (It doesn't help the drinking checks: those are checks, not saves.)

### What counts as cheating

- **Any spell or magic**, such as *mage hand*, *guidance*, *bless*, *longstrider*, *lesser restoration* or Bardic Inspiration.
- Drinking before the bottle falls, drinking after the runner is back, or spilling beer instead of drinking it.

### How to cheat (and how you get caught)

Each cheat is one **contest against the Floor Watcher's Wisdom (Perception) +5**. **Ties go to the Watcher.** The party can help, but each person who tries a cheat makes their own roll and risks being caught.

| Cheat | Who can do it | Roll vs the Watcher | If it works |
|---|---|---|---|
| **Sneak an extra gulp** after the runner is back | Drinker | Dex (Sleight of Hand) | You drink 1 extra gulp |
| **Let it run down your chin** while you chug | Drinker | Dex (Sleight of Hand) | 1 extra gulp counts as drunk |
| **Hidden spell** (*unseen servant* to tip the target) | A caster in the crowd | Cha (Deception) to disguise the casting. Subtle Spell gives advantage. | The invisible servant tips the bottle: one miss becomes a hit |

### Spotting a cheat

![[Cheating Penalties#Spotting a Cheat]]

### Caught cheating: penalties

Flunkyball is a **public event**. Penalties apply to the cheater **and** to any accomplice who is caught. A caught team forfeits the match.

![[Cheating Penalties#Public Events]]

| Fine | Or days serving the event |
|---|---|
| 30 gp | 3 days |

### Cheating dice example

On throw 1, Thokk keeps drinking after the Brewers' runner is back behind the line.
- Thokk: Sleight of Hand **5** − 1 = **4**. The Watcher: **3** + 5 = **8**. **Caught.**
- Team Party forfeits the match. Thokk is banned for 3 months and pinned to the notice board. To clear his name: 30 gp, 3 days serving, or wait 3 months.

## Hooks / NPCs

- **The Brewers** are apprentices from a city brewery. Their master has promised a promotion to whichever team beats the Party.
- **A student** keeps challenging the champions to "one more game." He's trying to get them drunk enough to tell him where they found that sword.
