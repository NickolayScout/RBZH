
# RUBEЖ |  Case study

## Context

RUBEЖ is a "high tec, low life", sci-fi frontier setting that blends high technology, nomadic lifestyle, post-soviet literary tradition 
and James C. Scott's books.

It targets audience of people who love grounded, "down-to-earth" settings, themes of survival, resilience, and fast-paced tactical combat.

What RUBEЖ is not:
- This is not a branch of DND or any other popular system -- the original idea was crafting a coherent system that serves its narrative.
- This is not a realistic milsim -- RUBEЖ wants to be believable, but not boring. Guns hit hard enough to be fearsome weapons of war, but not hard enough 
to turn the game into tabletop equivalent of Tarkov.
- This is not a "classic" sci-fi -- RUBEЖ is a lawless nomadic frontier, and it's people neither know nor care how's the life outside their planet.

## References and pitch

>Tabletop Rimworld with cossacks and anarchists

Inspirations include, but not limited to: Rimworld and James C. Scott, Strugatsky Brothers' books, Ice-pick Lodge games.

## Design problems and how to solve them.

1) HP feels too "gamey"

How do you make a game that is both mechanically functional, and fits "Brutal, grounded combat" rule?
Hit points felt too "gamey" - what happens, when a bullet hits you? Why applying a bandage helps?

The initial idea was to create a detailed damage model for players' arms, legs and so on, but it was scrapped even before playtests, 
because tracking multiple statuses per character on the table would be accounting nightmare.

The solution was to split "HP" into two trackers: Pain and Blood, scaling with character's Will and Body stats respectively.

Pain acts as "the HP", when it fills up, character is knocked out (but still alive).
This explains how a character with high will can take multiple bullets before going down. 
It also explains why "healing potion", which in this case is morphine injection, "revives" a downed player.

Blood acts as "anti tanking" and pressure meter. Blood loss accumulates over time, and losing it all means character death.
So you could tank enemy hits with consumables, but blood loss will catch you down.

Unlike morphine, which is cheap and relatively abundant, blood packs are rare and expensive.
This puts pressure in-combat on players who went down in previous turns, and creates opportunities for teamwork -- players can and should share blood with each other.

--- 

During second playtest, players found a workaround -- took a living prisoner who was in painshock after a battle, 
and the prisoner generously donated their blood to all in need. This is fine -- players eventually will face robot enemies, bug enemies, and cultists with poisoned blood.

During the same platest, two combat encounters took less than 5 turns (player has 8-12 blood on average and looses one per turn when bleeding). 
So mathematically, even if everybody took a bleeding on their first turn, they would finish the encounter before bleeding out. I've decided to keep system as-is for now: playtests were relatively short, not enough for blood loss to accumulate. I'd rather under-balance this system than over-balance for now, as it involves killing PC. If it turns out to be too gentle across many sessions, I'll patch it up.

2) Metageming

We all know it. Players do, from time to time, act too rational on the table with little to no downsides. Which is why I've added personal beliefs and stress system -- iteration over alignments. 
When creating a character, player chooses a set of catchphrases that describe their personal code: "Path is as important as destination", "I always keep my word", "I am responsible for my team" -- that sort of thing. When player acts against their own beliefs, they gain stress, which results in debuffs.

Stress is reduced by talking to teammates, relaxing, acting in line with your beliefs or doing "personal ritual" (drinking, meditating, playing music) -- another iteration over "short rest" concept. 

This system provides boundaries to players acting against their character, while not outright prohibiting it.

During playtest, this system played out once -- a character with "I am responsible for my clan" belief saw a lot of his clanmates dead and got really upset about it. Need more playtests to test it out.


3) Downtime between turns.

This was discovered during first playtest. I introduced a "squad" management for groups of similar enemies, and, later, gave players something to do between turns.
DND solves it by "reaction" resource, which you can spend once between your turns. I've added a shared team resource called "Fusion / Coherence" (depending on how you  want it translated), which is a **shared resource** of players can spend on powerful support actions between turns. This resource is finite within one initiative, shared between players suggesting tragedy of commons kind of managment, and scales down with players' stress. The more PCs are stressed, the less coherent their unit is, tiying stress mechanics closer to combat.

On a side note, I've experimented with "deck of turns" which reshuffles initiative every round. The idea was to keep players engaged, because they would not know whose next turn is. The Ataman class -- a "warleader" whoose primary feature is leading a bunch of somewhat disposable NPCs -- would have access to see turn order, and class ability to swap two players in that deck, emphasizing "tactical leader" archetype. As much as I loved the concept, it was scrapped because reshuffling the deck each round is a lot of overhead on the table.

4) Hoarding

This game has some mechanics that can get out of hand if not capped -- players can trophy enemy vehicles (which they did proactively during playtest), and some of those vehicles are quite powerful. To stop the game from escalating into mechanized corps simulation, I've added an orbital hub which players will find after our next session, and a shuttle with limited cargo capacity that takes players to/from the orbit. This also dictates a different session structure: players don't go whereever they please, instead, they are presented with problem in-orbit, and land to a handcrafted, narratively coherent oneshot in search of solution. This allows me to prepare a tight, predictable sessions, packed with handcrafted encounters rather than need to adapt and improvise. 

This has not been playtested yet. God help me if players "choose" not to be orbital travellers.

5) Level design and asset production.

This was the least expected one. A rather original setting means there is no online community to draw maps and character tokens for me, so I had to learn doing it myself. I ended up using Inkscape and producing both maps and icons in-house as SVGs. I've chosen a "tourist map" kind of layout for maps -- it's clean, easy to paint, and easy to learn once you know the legend. 

Another problem highlighted by playtest was range of certain weapons -- heavy sniper rifle can take out targets up to a kilometer -- so I've adopted "sightline control" for level design, meaning no point except highground should allow player to see the map from one end to another.