<p align="center">
    <img src="img/hanabi.jpg" height="200" />
</p>

# Hanabi Strategies & Conventions

For the *Hyphen-ated group*. Written and maintained by Zamiel.

All document updates are listed in the `#announcements` channel on the [Hanabi Discord server](https://discord.gg/FADvkJp). (You can also see the [commit history](https://github.com/Zamiell/hanabi-conventions/commits/master) of this repository.)

<br />

## Introduction & Purpose

Hanabi is a fantastic cooperative game of logic and reasoning. Our group, started by Hyphen-ated, gets online games going regularly. Everything doesn't always go perfectly, but we strive to constantly improve. Naturally, we have also built up a set of conventions that we all agree upon at the beginning of the game so that it is easier to understand what everyone else is doing.

The purpose of this document is:

1. To explain the *First Principles* to a beginner.

    Briefing a beginner on every possible strategy would quickly become overwhelming. It is much easier to just describe some guiding principles that everyone agrees upon. Once these are known, a beginner should be able to use logic and reason to derive (most of) the resulting strategy that their teammate is intending.

2. To serve as **a reference** for intermediate and expert players.

    Based on the guiding principles, we have come up with many different strategies. It is helpful to give specific names to each strategy to aid in both discussion and comprehension. If you know the general way we play but don't know about a specific kind of move, then you can look it up in this document.

We generally only play games with 3-5 players, since 2-player games can be quite boring. Thus, this document doesn't really apply to 2-player games; separate conventions are probably necessary for optimized play in that game type.

<br />

## Table of Contents

This document is split up into different sections so that you can better digest it. As a new player, you should probably **not** read the entire document at once. Rather, it might be better to only read Level 0 and Level 1 sections. The other sections can be just used as a reference as you continue to naturally improve at the game.

1. [Quick Links](#quick-links)
2. [Level 0 - First Principles](#level-0---first-principles)
3. [Examples](#examples)
4. [Level 1 - Beginner Strategies](#level-1---beginner-strategies)
5. [Level 2 - Intermediate Strategies](#level-2---intermediate-strategies)
6. [Level 2 - General Principles](#level-2---general-principles)
7. [Level 3 - Advanced Strategies](#level-3---advanced-strategies)
8. [Level 4 - Expert Strategies](#level-4---expert-strategies)
9. [Level 3 - Variant-Specific Strategies](#level-3---variant-specific-strategies)
10. [Level 3 - Rarely Used Advanced Strategies](#level-3---rarely-used-advanced-strategies)
11. [Level 4 - Rarely Used Expert Strategies](#level-4---rarely-used-expert-strategies)
12. [Non-Formalized Proposals](#non-formalized-proposals)
13. [Convention Attribution](#convention-attribution)

<br />

## Quick Links

* This document assumes that you are ALREADY familiar with the basic rules of Hanabi. If you need to brush up on them, see [this Pastebin written by Tricky](http://pastebin.com/6brGz2J4).
* The best place to play Hanabi online is at
[Hanabi Live](http://hanabi.live/).
* Find other people to play with and discuss strategy with on the [Hanabi Discord server](https://discord.gg/FADvkJp).
(Discord is a voice and text chat application that you can run in a browser.)

<br />

## Level 0 - First-Principles

While there are some weird strategies that could throw you for a loop if you have never seen them before, mostly everything should follow from these guiding principles. You don't have to memorize all of these all at once; just read them so that you can start to get familiar with them.

### 1. Chop Principle

* The "chop" is the right-most unclued card.
* When a player needs to discard and has no known safe discards, they discard the chop card.

### 2. Good Touch Principle

* A safe discard is defined as:
  * a copy of a card that has already been played
  * a copy of a card that already has a clue on it
* Safe discards should NOT be clued (unless there's an important reason to).
* Players should generally assume that any clued card in their hand will be eventually be played.

### 3. Save Principle

* Cards that meet the following criteria need to be saved:
  * only one copy remains (e.g. 5s or unplayed cards in the discard pile)
  * it is currently playable and not visible elsewhere in players' hands
  * it is a 2 and not visible elsewhere in players' hands
(this is the *2 Saves* convention)
* When a card that needs to be saved is at immediate risk of being discarded, it must be indicated with a save clue.
* A player receiving a clue should give precedence to a  "save" clue interpretation over a “play” clue interpretation.

### 4. Minimum Clue Value Principle

* A given clue must either:
  * indicate sufficient information for one or more previously unclued cards to be played or
  * prevent the possible discard of a card that needs to be saved

### 5. Play Order Principle

* When a play clue touches multiple cards, if it includes the chop, it's focused on the chop.
* Otherwise it's focused on the newest of the freshly-introduced cards.
* The non-focused cards may or may not be playable.
* 1s in the opening hand should be played right to left.

### 6. Left-Most Playable Principle

* When a player is expected to play a card (or know a card is playable) in a situation not covered by the *Play Order Principle*, the card to be played is the left-most of the various cards that are most likely to be it.

### 7. Information Lock Principle

* What is indicated by a clue is determined by the known information at the time the clue is given. Subsequent clues may build upon that information, but do not override it unless a direct conflict is evident.

### 8. Good Lie Principle

* When a play clue is given, it's a message that says the card is playable. Sometimes this message can be a lie, in order to usefully manipulate other players.
* Valid lies must not allow for the possibility of any misinformed player to give a conflicting clue or misplay. In simpler terms, this means that good lies almost always reveal themselves on the very next turn.

### 9. High Value Principle

* The highest value clue is expected. If a clue is given, it should be interpreted to be the highest value move available to that player.
* In other words, you can draw many important conclusions from the fact that a player did not do some other (potentially higher-value) move.

### Appendix A: Basic Clue Logic:

Following from these principles, this is [a basic logic flowchart](https://cdn.discordapp.com/attachments/140016142600241152/266467290101317632/Hanabi_Clue_Flowchart.png) that describes the general interpretation of a clue.

<br />

## Examples

Throughout this document, there will be a mix of both text-based examples and graphical screenshots.

In a text-based example:
* The player who goes first will always be Alice.
* The second player will always be Bob.
* The third player will always be Cathy.
* The forth player will always be Donald.
* The fifth player will always be Emily.

(This is a historial convention created by [Keldon Jones](http://keldon.net/).)

A screenshot will look like the following:

![Example Screenshot](img/example.png)

Note that in this user interface, players are holding their hands like they would be if they were playing in real life. For example, in this screenshot, Donald's chop card / right-most card / slot 4 card is the green 5, and Alice's chop card / right-most card / slot 4 card is the yellow 1.

<br />

## Level 1 - Beginner Strategies

### The Early Game

* The *Early Game* is defined as the period of time before someone discards for the first time. When they do, they initiate the *Mid-Game*. The general goal of the *Early Game* is to extend it for as long as reasonably possible.
  * Misplaying a card does NOT count as ending the *Early Game*.
  * Discarding known trash does NOT count as ending the *Early Game*.
  * Doing special discards that "transfer" cards to other players does NOT count as ending the *Early Game*.
* In the *Early Game*, everyone agrees that they MUST "extinguish" all of the available *Play Clues* and *Save Clues* on the board before discarding. (There are no cards in the discard pile yet, but *Save Clues* still need to be given to all of the 5s on chop and all of the 2s on chop that are not present in someone else's hand.)
* As an exception to the above rule, if the only thing left to clue is in the hand of the person who came directly before you, then cluing is optional, and you can choose to either clue it or discard at your discretion. This is because the player who came before you did not see anything for you to do, and is therefore giving you "permission" to discard.
* Furthermore, as a "special" rule to extend the *Early Game*, you can also clue off-chop 5s with number 5 as an early-save. This is special because you can't normally do this during the *Mid-Game*; see *Saving 5's off Chop* below.
* As another special rule, for the purposes of satisfying the "extinguish" principle above, it is only mandatory to clue at least ONE off-chop 5s. After that, players are allowed to discard at their discretion.
  * Thus, if no off-chop 5s have been clued yet and you see that the next player can do that, you can safely let something important ride on their chop. Conversely, if at least one off-chop 5 has been clued, you must save the next person's chop right now.

### When to Discard

* In general (not just in the *Early Game*), discarding is a last resort. If you have known playable cards in your hand, you are expected to play them before discarding. Furthermore, if there are good play clues to give, you are expected to make them before discarding.
* Thus, if there are more urgent things at hand, you can defer saving important cards on someone else's chop if you see they have playable cards or even a good play clue to give.

### Cluing 1s

* If you need to clue a single 1, it is better to do it with a color clue than a number clue. This is because it allows them to potentially clue other 1s on the board.
* If one or more 1s in your hand are clued, you should assume that they are ALL playable. (This ONLY applies to 1s, and follows from *Good Touch Principle*.)
* Playing 1s at the beginning of the game is a special case - you should always play your 1s from oldest to newest.
* Also note that freshly drawn 1s should be played before any 1s that were present in the starting hand. (The freshly drawn 1s are least likely to be duplicates.)

### Saving 5s on Chop

* Always save a 5 with a number clue instead of a color clue. Otherwise, it will look like a *Play Clue* (or potentially a *Save Clue* on a critical card).

### Saving 5s off Chop

* As mentioned above, cluing at least one off-chop 5 with a number 5 clue (if available) is **mandatory** in the *Early Game*.
* In the *Mid-Game* and beyond, saving 5s off chop is only permitted in specific "stall" situations, when someone is afraid of discarding. If it is not a "stall" situation, cluing a 5 off-chop may look like a *5's Chop Move* (which is covered later).

### Saving 2s on Chop

* Similar to saving 5s, always save a 2 with a number clue instead of a color clue.
* You can violate *Good Touch Principle* and duplicate a 2 in the situation where a color clue would look like a playable card and cause a misplay.

### Delayed Play Clues

* When you receive a play clue, it does NOT necessarily mean that you can play that card immediately. Look around the board for other ALREADY CLUED cards that might be related to the card that you are considering playing and then wait for them to be played.
* For example, if Alice was clued about a bunch of 1s and then Bob is then clued about a 2, he should WAIT for Alice to play all of her 1s first BEFORE playing the 2.
* In other words, treat all *Play Clues* as potential *Delayed Play Clues*.

### Fix Clues

* Normally, EVERY clue that is given is either a *Save Clue* or a *Play Clue*. One small exception to this is a *Fix Clue,* which is attempting to "fix" an impending misplay. (This is also referred to as a *Stop Clue*.)
* Fix clues are often needed when a duplicate card is touched. (For example, when a red 2 is clued in Player A's hand, and the other red 2 is clued in Player B's hand.) Cards are not normally duplicated (which follows from *Good Touch Principle*), but sometimes someone makes a mistake, or a sequence of particular cards makes duplicating necessary.
* In such a situation, because of *Good Touch Principle*, one of the players with the duplicate cards may misplay it since they will assume the identity of the card to be something else. Thus, it is the team's responsibility to fix the problem and intervene before this happens.
* **A clue cannot be a *Play Clue* and a *Fix Clue* at the same time.** If you receive a Fix Clue and it touches other ancillary cards, none of them are necessarily playable; the primary point of the clue is to fix the impending misplay.
* Usually a fix clue will "fill in" the card to explicitly make it known that the card is unplayable or duplicated. However, it is also possible to perform a fix clue just by cluing the card again. For example:
  * Alice clues Bob number 1 and it highlights three 1s.
  * Bob successfully plays two 1s.
  * Before Bob can play the 3rd 1, Alice clues Bob number 1 again, and it re-highlights the remaining one.
  * Now it is Bob's turn. Since he was going to play the 1 already without Alice doing anything, the clue must have some other meaning. Thus, it is a *Fix Clue*: the remaining 1 is bad, and Bob can safely discard it.

<br />

## Level 2 - Intermediate Strategies

### Prompts

* Imagine that you have one or more cards in your hand that have a clue on them, but their full identity is currently unknown. In this situation, you are supposed to just keep the cards in your hand, and continue to discard unclued cards.
* If someone gives a *Play Clue* to a card that is currently unplayable, then they could be telling YOU to play a card that is already clued in your hand. This is called a *Prompt* because it is "prompting" you to play a card that you would have otherwise held on to.
* For example, in a 3-player game:
  * All the 2's have been played on the stacks.
  * Alice clues a red 4 in Cathy's hand as a *Play Clue* (since it was not on chop).
  * Bob has a card in his hand with a red clue on it, but no number information.
  * Since Bob can see that the red 4 is supposed to play right now, he must have the red 3. So the unknown red card in his hand must be red 3, and he can safely play it.
* If a player is *Prompted* and there are multiple cards in the hand that the *Prompt* could apply to, they should play the left-most. (This follows from *Left-Most Playable Principle*.) For example, in a 3-player Rainbow game:
  * Similar to the last example, Bob is *Prompted* for a red 3.
  * Bob has 3 cards clued as red in slots 2, 3, and 4.
  * Since all 3 cards are equally likely to be red 3, Bob should choose to slot 2 as red 3 since it is the left-most.
* In multi-color variants, *Prompts* apply to the card with the most positive information. For example, in a 3-player game:
  * Similar to the last example, Bob is *Prompted* for a red 3.
  * In slot 1, Bob has a card with only a red clue on it.
  * In slot 2, Bob has a card with a red clue and a 3 clue on it.
  * Since slot 2 has more positive information, Bob should choose to play slot 2 as red 3.

### Finesses

* If someone gives a play clue to a card that is currently unplayable, then they could be telling YOU to play a card. Normally, this would indicate a prompt. But, what if you have no clued cards in your hand or no clued cards that apply to the situation? They can't possibly be prompting you, so what are they doing? This is called a *Finesse*. In this situation, you should blindly play your left-most unclued card. Then, the other player will play the card that was directly clued. This way, your team will have gotten 2 plays with only 1 clue, which is very efficient.
* The position that a player's left-most unclued card is in is called *Finesse Position*.
* For example, on the first turn of a 3-player game:
  * Alice clues Cathy red, which highlights her red 2.
  * Next, it is Bob's turn. Bob sees that, with this weird red clue, Cathy has just been signaled that she has the red 1. Oh no! Cathy is going to misplay that on the next turn! What could Alice have been thinking! Oh wait - something must be in Bob's hand to make that red 2 playable. This must be the *Finesse* convention, so he blindly plays his left-most card and it is the red 1.
  * Next, Cathy plays her red 2.
* **Note that *Prompts* take priority over *Finesses*!** Do not blindly play your left-most card if the situation can apply to any of the clued cards in your hand.

### Reverse Finesses

* In a normal *Finesse*, you would give a clue to a person AFTER the person blindly playing the card. If you give a *Finesse* clue to someone BEFORE the blind-play occurs, it is called a *Reverse Finesse*. This is more complicated than a normal *Finesse* and is harder to see.
* Since *Reverse Finesses* exist as a strategy, before playing ANYTHING that you aren't 100% sure about, you should always check out everyone's *Finesse Position* card (the left-most unclued card). If the card in this slot "matches" the card that you were just clued, then you should DEFER playing it for at least one go-around.
* If the player whom you suspected the *Reverse Finesse* was directed towards blind-plays their card, then it means that the card that was clued originally is the next card in the chain and you can play it on your next turn.
* Or, if the player whom you suspected the *Reverse Finesse* was directed towards did NOT blind-play, then you can safely play yours.

### Order of Playing Two or More Playable Cards

* If you have a two cards in your hand that are playable right now, you have a decision on which to play first. PRIORITIZE the cards that have a follow-up card in someone else's hand.
* For example, in a game with red 1 and blue 1 already played:
  * Alice has red 2 and blue 2 in her hand and she knows that both are playable right now.
  * The red 3 is in Bob's hand (and happens to be tagged with a number clue). Alice does not see the blue 3 at all. So, Alice plays the red 2 first.
  * Bob sees that this decision was made, so he should KNOW that the 3 in his hand is not blue. (He doesn't necessarily know that it is exactly red yet.)

### The 1's Chop Move

* Sometimes, a player will have two critical cards in a row on chop that will require two separate clues to save. In this situation, the two preceding players should realize that this is happening and both issue clues before it rotates around to that player. However, sometimes it falls to only one player to somehow save TWO cards.
* One tool to solve the problem is to make a number clue to a card that is NOT the chop. This generally only works if the card is a 1 or a 5.
* If the card clued is a 1 AND all of the 1s have already been played, the player should think: "Why was I clued a 1 when all of the 1s are already on the board? Oh, the cards behind the 1 must be critical, so I should try to give a decent clue if possible, or discard the 1."
* After the chop move clue, the player should consider ALL of the cards to the right of the 1 like they have been touched with an "invisible" clue and therefore never discard them. (Thus, if you clued a 1 on someone's newest slot, it would chop move the entire rest of the hand.)
* Once a card has been chop moved and is no longer in danger of being discarded, it is treated as an already-clued card with regards to new clues given to that hand.

### The 5's Chop Move

* See the *1's Chop Move* section above for an explanation on what a *Chop Move* is.
* It is also possible to chop move with a number 5 clue. The player receiving the clue would think something along the lines of: "Why was I clued a 5 EARLY? It isn't even on my chop yet! This must mean my card to the right of the 5 is important, so I should try to give a decent clue if possible, or discard the card to the LEFT of the 5."
* *5's Chop Moves* are different from *1's Chop Moves* in that you can ONLY chop move ONE card with it. Thus, if you clue a 5 and it is TWO (or more) slots away from the chop, then it is to be assumed to be a *Play Clue* on the 5.
* When you get clued a 5, the *5's Chop Move* interpretation ALWAYS takes precedence over a play clue interpretation.

### The Scream Discard Chop Move (Deliberately Discarding Instead of Playing)

* The *Chop Move* outlined above is a tool to save multiple cards with one clue. However, sometimes you may not have a clue at all. One way to solve this situation is with a special kind of discard.
* Typically, discarding is a last resort. So, if you have a known playable card in your hand, you can send a powerful signal to your partner by discarding. This is called a *Scream Discard*. Since your partner expected you to play the card, it is like screaming at them to let them know that things are very bad.
* The player being "screamed at" should permanently move their chop by one position.
* Furthermore, the player being "screamed at" is not allowed to discard on this turn. They must make some clue. Clues in this situation are treated the same as a *Double Discard Situation* (see *Avoiding Double Discards* below).
* Players are only allowed to *Scream Discard* for cards that are playable or critical (or a needed 2 that isn't seen anywhere else).
(You are not allowed to Scream Discard for a card that is one away from being playable.)
* There are two exceptions to the *Scream Discards* convention:
  * It is not a *Scream Discard* if the next player HAS to generate a clue for a separate reason. This is called a *Generation Discard*; see below.
  * It is not a *Scream Discard* when the card that the player did not play was a "blind" card AND they could see the blind card in your hand. When this happens, you will usually want to blind play your *Finesse Position* card, since this sequence of events indicates either an *Ambiguous Finesse* or a *Pass Bluff*.

### The Generation Discard

* Usually, if someone has a known playable card and they discard instead of playing that card, this would indicate a *Scream Discard Chop Move*.
* However, if playing the card (player 1) would cause the next player to discard (player 2) and the next player after that (player 3) to have a critical and/or playable card "ride" on chop, it is a very bad situation. Thus, the discard is JUST for the purposes of generating a clue so that player 2 can clue player 3.
* The *Generation Discard* is ONLY to be used as a last resort. If player 3 has something else to do (like play a card or give some obvious clue), then it is NOT a *Generation Discard*, and is instead to be interpretted as a *Scream Discard Chop Move*.

### A Scream Discard Flowchart

[Here is a handy flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/scream_discard_flowchart.png) for determining whether something is a *Scream Discard Chop Move* or a *Generation Discard* or a *Long-Range Scream Discard Chop Move* (which is much more rare and is covered later on in this document).

### The Unnecessary Generation Discard

* Sometimes, in order to satisfy *Save Principle*, a player will perform an unnecessary *Generation Discard*, which generates a clue to save a card that they actually already have in their hand.
* This puts the next player in an ambiguous situation: was it really a *Generation Discard*, or could it a *Scream Discard*? In order to cover both situations, they should not *Chop Move*, but they should also not discard on this turn.
* For example, in a 3-player game:
  * Red 3 is played on the stacks. No blue cards are played on the stacks.
  * Alice has a blue 1 in her hand. She knows the exact identity of it, so it is known playable.
  * Alice also has a 4 clued in her hand. She does not know what color it is.
  * There are 0 clues, so if Alice plays the blue 1, Bob will be forced to discard.
  * Alice sees that Cathy has a red 4 on chop, which is playable. If Alice does not have red 4 in her hand, then Cathy could potentially discard the red 4 (after Bob is forced to discard).
  * So, Alice performs a *Generation Discard* to generate a clue so that Bob can clue the get the red 4, if necessary.
  * Bob sees that Alice does indeed already have the red 4 in her hand, so from his perspective, if Alice was performing a *Generation Discard*, it was unnecessary.
  * However, it could also be the case that Bob's chop is unsafe. So, Bob will NOT clue the red 4 on Cathy's chop, but he WILL spend the clue in some other productive fashion. If Bob has nothing productive to do, he must "burn" a clue, similar to what happens when a *Scream Discard* occurs.

### Tempo Clues (Re-cluing a Card)

* This is the name given to clues that do not meet *Minimum Clue Value Principle*. They get a card played **right now** that already had a clue on it.
* Players do not generally give *Tempo Clues*, as they are considered inefficient, and in Hanabi you want to be as efficient as possible.
* However, *Tempo Clues* are allowed in the following special circumstances:
  1. When the card is "out of order" (meaning that it is impossible for a *Prompt* to get the cards played)
  2. When the card was *Chop Moved* and it is now playable
  3. When the clue giver is "locked"
  4. When the clue giver has been signaled by another player that they have an unsafe discard
  5. When the clue giver is in a *Double Discard* situation (see *Avoiding Double Discards* below)
  6. When the clue receiver is "locked" (see *Fully Clued Hands* below)
  7. When the clue receiver is receiving a tempo clue on a card that unlocks someone else's hand
  8. When there are 8 clues in the bank (a forced clue)
  9. When there are 7 clues in the bank (since discarding would take the team to 8 clues, which is generally bad)
  10. When in the *End-Game* or the team is behind pace (specifically, when score + deck is below the maximum score)
  11. When the game has been going so well that further clue efficiency is no longer required to win the game
  12. When the tempo clue gets 2 or more cards played.
* *Tempo Clues* that are done outside of these special circumstances are a different convention called *Tempo Clue Chop Moves*, which are detailed further on in this document.
* Sometimes, a *Tempo Clue* can touch multiple cards, which typically means that all of the cards touched are playable. See the *Double Tempo Clue* section further on in this document.

### Avoiding Double Discards

* If the player before you just discarded a card (say the red 4), and you don't see that card in anyone else's hand, there is a possibility that you could have that same card on your chop. In this example, if you discarded, both red 4s could be lost and your team would not be able to get a perfect score. This is called *Double Discarding*.
* Since *Double Discarding* can "lose" the game, you should make any decent clue if you can to avoid it. Even a low-value clue might be better than discarding. After a go-around, you can safely discard - if your chop was indeed the same card, it would have been given a save clue by your teammates.
* If, to avoid a *Double Discard*, the clue that you are considering is so low value that it will cause a fair amount of confusion to your teammates, then it is probably better to just risk it and double discard. Sometimes, you really don't have any clues to give, and that's okay. However, the following "bad" clues are always allowed in *Double Discard* situations:
  1) Tempo clues
  2) Cluing off-chop 5s
  3) Saving 2s on chop that are present in another player's hand
  4) Filling in extra info on ambiguously saved cards that are still not playable
  5) Re-cluing 5's to a player (a "hard burn")
* The plus side of this strategy is that, because players should not generally double discard, you do not need to be overly worried about the same card being on two simultaneous chops.
* Generally speaking, a weird or super low-value clue can communicate an advanced strategy like a *Finesse*. However, always pay attention to see the situation that the clue-giver is in. From their perspective, are they giving the clue to avoid a double discard? If so, then you should not read too closely into their clue.
* From *High Value Principle*, you can know that a player in a double discard situation is NOT giving a "bad" clue if there is some other better clue available for them to give. Thus, players in double discard situations are often able to still give tricky-looking *Finesses*.

### Fully Clued Hands (Locked Hands)

* Generally speaking, it is a bad situation when someone's hand gets fully clued. This is also known as being "locked", and it should be avoided if possible. However, sometimes it cannot be helped, like if the player draws three 5s in a row.
* A person with a fully clued hand may give a low value clue because they are not sure that they can play anything (and they can't discard because their hand is fully clued). Do NOT read too closely into any clues given during this state.
* If your team is out of clues and someone's hand is fully clued, then you HAVE to discard to generate a clue for them. Similarly, if there is only 1 clue left, you cannot steal it from them.
* Explicitly, while in a locked hand, a player can do the following "bad" clues that are also allowed while in double discard situations:
  1) Tempo clues
  2) Cluing off-chop 5s
  3) Saving 2s on chop that are present in another player's hand
  4) Filling in extra info on ambiguously saved cards that are still not playable
  5) Re-cluing 5's to a player (a "hard burn")
* Beyond this, they can also give additional bad clues that are not allowed in double discard situations:
  6) Saving any card on chop (referred to as a *Locked Hand Save*)
* Players who are locked MUST follow general clue priority. For example, a locked player cannot save an off-chop 5 if there is a normal *Play Clue* or *Save Clue* to give. (If they do, it will look like a *Play Clue* on the 5.) And a locked player cannot perform a *Locked Hand Save* if there is a *Tempo Clue* to give. (If they do, it will look like a *Play Clue* on the clued chop card.) And so forth.

### The Anxiety Play

* Sometimes, someone with a locked hand has a playable card but they do not know that they can play it yet. Re-cluing the card would signal this, but would not be very efficient.
* A better way to signal this information is to deliberately leave them at 0 clues. For example, from the perspective of the fully clued player: "Darn, why would Alice steal the last clue like that? Now I have to discard one of these already-clued cards that could be imporant! Hold on - it must mean that the my unknown 2 is actually playable!"
* If multiple cards could be playable, the locked player should choose the left-most one to play.

### Clues Given While at 8 Clues

* At the beginning of the game, you start with 8 clues. This section only applies to situations where you climb to 8 clues in the middle of the game.
* Generally speaking, a weird or low-value clue can communicate an advanced strategy like a *Finesse*. However, when there are 8 clues in the bank, it is not possible to discard - the game forces you to play a card or make a clue. But, if you don't know if any of the cards in your hand are playable, you HAVE to give a clue.
* For this reason, do NOT read too closely into any clues given during this state - it might just be a "stall" clue because the player had no other choice.
* Explicitly, while at 8 clues, a player can do the following "bad" clues that are also allowed while in double discard situations:
  1) Tempo clues
  2) Cluing off-chop 5s
  3) Saving 2s on chop that are present in another player's hand
  4) Filling in extra info on ambiguously saved cards that are still not playable
  5) Re-cluing 5's to a player (a "hard burn")
* Beyond this, they can also give the additional bad clues that are allowed in the "fully clued hands" situation:
  6) Saving any card on chop (referred to as a *8 Clue Save*)
* And beyond this, they can also give additional bad clues that are not allowed in the either two situations:
  7) Saving any card off chop, unless it was just drawn (referred to as a *8 Clue Save*)
* Similar to being locked, players who are at 8 clues MUST follow general clue priority. For example, a player at 8 clues cannot save an off-chop 5 if there is a normal *Play Clue* or *Save Clue* to give. (If they do, it will look like a *Play Clue* on the 5.) And a player at 8 clues cannot perform a *8 Clue Save* if there is a *Tempo Clue* to give. (If they do, it will look like a *Play Clue* on the clued chop card.) And so forth.

<br />

## Level 2 - General Principles

This section is unique in that it contains things that are separate from actual moves and strategies. We refer to them in post-game reviews when thinking about the game.

### Stomping a Finesse

* This is when a player clues a card directly that was going to be blind-played from a *Finesse*. Typically, this is a mistake, and it means that the player who gave the clue was not paying attention and failed to see that a *Finesse* happened at all.

### Lines

* During your turn, part of figuring out the best move to do involves looking into the future to see what the next person will do. If they discard, will it be okay? Is there some obvious clue that they will do? And so on.
* However, as you get better at Hanabi, you will need to do this prediction not just for the next person, but for an entire go-around of the table. And as you really get good at Hanabi, you will need to do this for as far in the future as you can reasonable predict. (Sometimes, this means 15 moves or more in the future.)
* Similar to chess, initiating a move in which you can predict the next sequence of moves is called initiating a "line".
* In post-game reviews, we will often compare and hypothetically "play through" two different lines to see which one is better.

### Bluff Position and the Pang of Guilt

* As mentioned in the section on *Bluffs*, you are in *Bluff Position* for a certain player if you are immediately before them.
* If the player before you immediately draws a playable card, you should first notice that the card is in *Finesse Position*. If you clue it directly, you may be "stealing" someone's *Finesse* or *Bluff*.
* Thus, in this situation, it may be better to discard and let the player in *Bluff Position* get the card in question. If you do decide to clue the card directly, you should always feel a *Pang of Guilt*.

### Discard Modulation

* Often times, either you or the player who comes after you can perform a move. And this move would have the same result if done by either player.
* One way to decide whether you or the next player should give the clue is to look at the next player's chop. Is their chop high-value, low-value, or useless? If it is high-value, then you should discard and let them give the clue. If it is low-value or useless, then you should give the clue and let them discard.
* "Stealing" clues in this way to cause discards is called *Discard Modulation*. If other players are discarding to let you give all of the clues, you probably have a high-value chop.

### One-Away

* In general, 3's are pretty high value, and 4's are pretty low value.
* But combined with this, cards that are one-away are pretty high value, and cards that are two-away (or more) are pretty low value.
* Thus, in some situations, a one-away 4 may be more valuable than a two-away 3.
* According to our conventions, it is illegal to clue a one-away card directly without it being some kind of special move like a *Finesse* or *Bluff*. However, sometimes we still want to "save" these cards. Thus, they are prime targets for indirect saves like the *5's Chop Move* or the *1's Chop Move*.
* However, in most cases, *Chop Moving* the valuable card just won't be possible. So in general, you should try to construct lines that protect high-value cards for as long as possible.

### All 4's Test

* According to *Save Principle*, the team must not let any critical and/or playable cards be discarded. So part of constructing a line is figuring out whether this will happen.
* When considering a line, it is not safe to assume that a player will clue anything in your hand. You should perform the *All 4's Test*: what would everyone do if I have all useless 4's in my hand? If a critical and/or playable card would get discarded, then the line has failed the test, and it is probably a bad idea.

### Schrodinger's Cat Principle

* Often times when you are given a clue, the card could be two or more things.
  * For example, in a no-variant game, a red *Play Clue* might indicate a red 2 or a red 3 depending on whether or not red 2 will blind-play from someone else's hand.
  * For example, in a rainbow-game, a red *Play Clue* card might indicate either a red 1 or a *Delayed Play Clue* on a rainbow 2 through another player's yet-to-be-played rainbow 1.
* After getting a clue, you should immediately mark all of the possibilities down on the card as a note.
* For all of your subsequent turns, you have to treat that card like it is **all of the possibilities** at the same time. This is a lot like the *Schrodinger's Cat* quantum physics analogy, which states a cat is both alive and dead at the same time, and you won't know until you actually open the box and look. Similarly, treat the unknown card as all the possibilities, and you won't actually know until the card is played.

### Occam's Razor

* Sometimes, clues can have multiple interpretations. For some moves, we make it a point to explicitly define the priority in order to avoid confusion. For example, we say that *Prompts* take precendence over *Finesses*.
* For other situations, there is no explicitly defined priority. For example, a clue could mean either a *Self-Finesse* or a *Self-Prompt* + *Finesse*. In these cases, *Occam's Razor* applies, meaning that you can slice away all the more complicated interpretations and simply assume the least-complex one. In this case, a single *Finesse* is less complicated than a *Finesse* + *Prompt*, so the former interpretation would be assumed.
* It is important to not confuse *Occam's Razor* with *Schrodinger's Cat Principle* - you almost always have to allow for *Prompts*, *Reverse Finesses*, and so forth. But when you are not waiting on any information from other player's actions, then *Occam's Razor* does apply.

### Team Distribution Principle

* In general, it is better for useful cards to be distributed **evenly** throughout the team. This is especially important in 5-player games.
* Thus, if one of your teammates has 3 of 4 cards clued, it may be better for THEM to be the one giving the clues, and you to be the one discarding - even if their chop is known trash.
* There are multiple reasons for this. First, you don't want them to get a *Locked Hand*, which is generally bad. Second, if they continue to draw playable cards, the game may end before they get a chance to play them all.

### End-Game Threshold

* Towards the end of the game, the strategy of the team will change. In most games, you stop becoming conerned with efficiency and become more concerned with tempo - every card needs to play **right now** before the game ends!
* Thus, since clues can mean different things whether you are in the *Mid-Game* or the *End-Game*, you need to be able to keep track of when the *End-Game* has arrived.
* This can be estimated with the following formula: `n = current score + cards in deck - maximum score`
  * If `n ≥ 0`, you are not yet in the *End-Game*, and you should not hesitate to discard.
  * If `n < 0`, the *End-Game* has arrived.
* When `n = -1` (the beginning of the *End-Game*), it is usually okay to discard, unless there is a single person who holds all the useful cards.
* When `n` is smaller than `-1`, you should be very careful with discarding. It might still be the best thing to do, but it is usually better to *Burn* a clue (meaning to deliberately waste a clue).

<br />

## Level 3 - Advanced Strategies

### Bluffs

* When you see a playable card in someone's *Finesse Position* slot, you will often want to get the efficiency of a *Finesse*. However, often times, the proper "connecting" card is not on the board.
* One alternate strategy is to lie to the next player and clue a completely unrelated card to indicate a *Finesse*. This manipulates them into blind-playing and is called a *Bluff*.
* Next, the player who received the *Finesse* clue knows that since the other person "randomly" blind-played their *Finesse Position* card, it was a *Bluff* and not a real *Finesse*. This means that they can't actually play the clued card. However, they should know exactly what card it is (or have a specific narrow set of possibilities), so the sequence still gets a lot of efficiency.
* For example, on the first turn of a 3-player game:
  * Alice clues Cathy red, which highlights her red 2.
  * Next, it is Bob's turn. Bob sees that, with this red clue, Cathy has just been signaled that she has the red 1.
  * This must be a *Finesse*, so Bob knows that he must have the red 1, and he must blind-play it right now or else Cathy will go on to misplay the red 2 as the red 1.
  * Bob blind-plays his slot 1 card. However, it is not the red 1, it was the green 1! Now Bob knows that he has been *Bluffed* by Alice.
  * Next, Cathy sees that Bob just blind-played a green 1 immediately after this red clue, so she knows that she must have the red 2. Cathy holds on to the red 2 for later and discards.
* Except in rare circumstances, **bluffing is only permissible when you are the person directly before the player who is blind-playing a card**. This is called being in *Bluff Position*. Do not *Bluff* unless you are in *Bluff Position*!

### The Double/Triple Prompt

* Sometimes, someone can give a *Prompt* that is prompting TWO (or more) cards with one clue, which is pretty efficient.
* For example, say that a red 1 is played on the pile, you have 2 clued red cards in your hand, and no-one else has any red cards in any of their hands. Then, someone draws a red 4 and it is immediately clued as red. How can the red 4 be playable? Well, the only way is that if you have the red 2 and the red 3. So, you would play these from left to right during your next two turns.

### The Double/Triple/Quadruple Finesse

* In a 4-player game, it is possible to get two different people to blind-play their cards in a row if you give a clue to a card that is two-away from being playable. This is very efficient, as it is a 3-for-1 clue.
* For example:
  * A red 1 is currently played on the stacks.
  * Alice clues Donald red, highlighting a red 4.
  * Bob plays red 2 from his *Finesse Position*.
  * Cathy plays red 3 from her *Finesse Position*.
  * Donald plays red 4.
* Similarly, it is possible to get a single person to blind-play 2 cards in a row. In this situation, since they see that the clue can't apply to anyone else's hands, they will assume that the clue is talking about their two newest unclued cards, and they will play from left to right.
* In general, remember that players will always assume *Prompts* over *Finesses*. Thus, is it possible to do a clue that prompts a card from a player's hand and THEN gets them to blind-play their *Finesse Position* card on the next turn (or vice-versa, depending on the negative information on the card and the situation).

### The Ambiguous Finesse

* Sometimes, the person who is supposed to blind play a card into a *Finesse* is ambiguous. For example, in a 4-player game:
  * Nothing is played on the stacks.
  * Alice clues Donald about a red 2 as a *Play clue*.
  * Both Bob AND Cathy have red 1 on their *Finesse Position*.
  * Bob will think that it is a *Reverse Finesse* directed at Cathy, and he will discard.
  * Next, Cathy thinks that Bob made a mistake and "missed" the *Finesse*. Cathy discards.
* Here, Cathy is actually the one making the mistake. It follows from *High-Value Principle* that you should never assume that your teammates are making a mistake. If Bob is discarding, then it means that Cathy also has the exact same copy of the card, and Cathy should immediately blind play.
* From Cathy's perspective, it is also possible that Bob is performing a special move called a *Pass Bluff* (which is covered later on in the document).

### The Positional Discard (Indicating a Play with a Discard)

* On the final go-around of the game, if you have no clues left and no cards to play, you can transmit information based on which card you discard.
* Thus, you can discard the slot in your hand that matches the slot in someone else's hand that they are supposed to play.

### The Sarcastic Discard

* Occasionally, through a mistake (or complicated situation), the same card will be clued in two different people's hands. Generally, this is to be avoided, but sometimes it happens. Handling this can be tricky.
* Generally, the FIRST person who 100% realizes that they have the duplicate card should discard it (as opposed to playing it or holding on to it). This is called a *Sarcastic Discard*, and it communicates to the other player that they 100% have the discarded card.
* "Why did Bob just discard the red 3 that I JUST gave him a play clue on? That makes no sense. Wait - it must be because he realized that the red 3 was ALSO clued in someone else's hand. I must have the red 3!"

### The Trash Chop Move

* The *1s Chop Move* is listed above as an intermediate strategy, but in truth it is just a specific form of the more general *Trash Chop Move*, in which you clue a card that is known useless in order to tell someone that their chop is unsafe.
* This move is most commonly done with a number 1 clue because it is likely that in the middle of a game, all of the 1s will be already played. But it could also be done with a number two 2 clue if all the 2s are already played / accounted for. Or, it could be done with a yellow clue if all of the yellow cards are already played / accounted for. And so forth.

### A Trash Flowchart

Trash is not commonly clued, as it violates *Good Touch Principle*. The *Trash Chop Move* listed above is one common reason to intentionally clue trash. However, there are other reasons to clue trash that are detailed later on in the document.

[Here is a handy flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/cluing_trash_flowchart.png) for determining the difference between the different types of special moves that touch trash.

### The Tempo Clue Chop Move

* *Tempo Clues* are defined as clues that touch no new cards. Their purpose is to get 1 or more cards played that already have clues on them.
* In general, *Tempo Clues* do not follow from *Minimum Clue Value Principle* (first principle #4), which states that a clue must get at least 1 new card played or save at least 1 new card from being discarded.
* Thus, a *Tempo Clue* with no other purpose MUST save at least 1 new card, and the player should "chop move" their chop card to the next slot.
* *Tempo Clue Chop Moves* do NOT apply in the special situations where natural *Tempo Clues* are allowed. See the *Tempo Clues* section earlier in the document for an explicit listing of these situations.

### The Double Tempo Clue (Re-cluing 2+ Cards)

* Typically, when a *Tempo Clue* is given that touches two or more cards, it means that ALL of the cards touched are playable in order from left to right.
* However, this interpretation does not apply when:
  * the clue unlocks a player's hand
  * it gets two or more cards played in total (using cards in someone else's hand)
* Furthermore, it also does not apply when the second card touched is strictly not playable. In this situation, all players can see that since only one card is getting tempo, the interpretation of the clue should be a *Tempo Clue Chop Move*.
* However, if the other players can see that the card being chop moved is useless (or not very good), it implies a *Finesse* on the touched cards that are not strictly playable right now.

### The Early Fix Clue Chop Move

* As noted in the *Fix Clues* section, a *Fix Clue* is required before a misplay occurs on duplicated cards. But usually, the misplay will not occur until late in the game, because there is always some other extra card (that is not currently playable) that it could be.
* Thus, if other urgent things are at hand, you can usually defer giving some *Fix Clue* for a long time and hope that through ancillary information and the context of the game, the player will "naturally" figure out that the card is duplicated.
* So if a *Fix Clue* is given early to you, it can be strange. You were happily discarding, and now all of a sudden you are being fixed on a card that was just sitting in your hand and was not in danger of being misplayed.
* This usually means that your chop suddenly became important, so the *Fix Clue* was given early to give you a good discard and keep you occupied. Thus, you should permanently chop move one card.

### The Misplay Chop Move

* Sometimes, a desirable card is on the next person's chop and it is not directly cluable. In this situation, players can cleverly use the various kinds of chop moves in order to save the card (e.g. *1's Chop Move*, *5's Chop Move*, *Tempo Clue Chop Move*, and so forth).
* However, none of these chop moves may be available to perform. In such a situation, you can revert to the final type of chop move - the *Misplay Chop Move*. This is done by intentionally touching a card in the next person's hand that signifies that it is currently playable. The next person will misplay, and then they will know that every card to the right of the misplayed card is valuable and is now permanently chop moved.

### The 3 Bluff

* Typically, the player who receives a clue that causes a *Bluff* blind play knows that the card that was clued is one away from being playable.
* Our group plays with an artificial *3 Bluffs* convention. This means that in addition to being one away from being playable, we agree that the touched card can be ANY 3 that will be useful in the future.
* The priority of *3 Bluffs* can be confusing, so here are some examples that cover the four most common situations:
    * **Color mismatch (valid):**
      * On the first turn of the game, Alice clues Cathy a Red 3 with red.
      * Bob blind plays Blue 1.
      * Cathy knows that it is either a Red 2 or a Red 3.
    * **Number 3 with suit mismatch (valid):**
      * On the first turn of the game, Alice clues Cathy a Red 3 with number 3.
      * Bob blind plays Blue 1.
      * Cathy knows nothing about the card, besides that it is a 3 (since it has a number 3 clue on it).
    * **Color match (NOT valid; looks like a Double Finesse):**
      * On the first turn of the game, Alice clues Cathy a Red 3 with red.
      * Bob blind plays Red 1.
      * Cathy sees that Bob does not have Red 2, so since red matches red, Cathy assumes that she has the Red 2.
      * Cathy misplays Red 3 as Red 2.
      * Alternatively, if Cathy saw that Bob had both Red 1 and Red 2 on *Finesse Position* at the time the clue was given, she would know that she has Red 2 OR Red 3. Subsequently, Bob is promised a Red 2, since if he does not blind play a card, Cathy will go on to misplay the Red 3 as Red 2.
    * **Number 3 with suit match (valid):**
      * On the first turn of the game, Alice clues Cathy a Red 3 with number 3.
      * Bob blind plays Red 1.
      * Cathy knows nothing about the card, besides that it is a 3 (since it has a number 3 clue on it).
      * Even though Red 1 and Red 3 are the same suit, Bob is not promised a Red 2, because if he does nothing, Cathy will not go on to misplay the Red 3.

### The Critical 4 Bluff

* Building on the *3 Bluffs* convention, we also agree that is possible for a card that initiates a *Bluff* to be a copy of any of the 4s that are critical (meaning that the other copy is in the discard pile or it is a black 4).
* Note that this convention does not apply to the *Wild & Crazy* variant.

### Discard Elimination & The Elimination Blind Play

* Normally, your teammates would never let you discard anything important. So when you discard some playable card (or a needed 2) AND your teammates were not busy AND you don't see that card in anyone else's hand, you should write a note on all of your other remaining cards that they could be that card. These are called *Elimination Notes*.
* Thus, when you get a follow-up clue, you will know exactly what card it is.
* In other situations, your teammates will choose to NOT to give any follow-up clues. After a few more discards, you should know exactly what card it is and be able to blind play it.

### The Elimination Blind Play Riding Deduction

* If there are only 2 cards left in your hand with *Elimination Notes* on them AND the players before you let your chop card ride AND the players before you weren't busy, then the playable card cannot be on your chop.
* This means you can "jump ahead" and immediately blind play the newest of the 2 cards with the note.
* For example, in a 3-player game:
  * Red 1 has been played on the red stack.
  * Alice discards red 2.
  * Alice knows that her teammates would not have let the only copy of red 2 be discarded, so she must have the OTHER copy of red 2 in her hand.
  * Alice has no cards clued in her hand, so she writes *Elimination Notes* on slots 2, 3, 4, and 5.
  * Alice recieves no clues on the next go-around of the table. She discards, and now has *Elimination Notes* on slots 3, 4, and 5.
  * Alice recieves no clues on the next go-around of the table. She discards, and now has *Elimination Notes* on slots 4, and 5.
  * Alice recieves no clues on the next go-around of the table. Her teammates would not let the other copy of red 2 be discarded, so it must be on slot 4. Alice blind plays red 2 from slot 4.

### The Elimination Self-Chop Move

* Sometimes, you will have narrowed down your *Elimiation Notes* to one specific card. Thus, even though the card has no positive clues on it, you know the exact identity of the card.
* If the card in question is on your chop AND the card is not yet playable AND you need to discard, you should obviously not discard the important elimination card. You should instead self-chop move and discard the next thing.

### Play Elimination

* When you discard something important, that triggers the writing of *Elimination Notes* on your own hand. This is *Discard Elimination* and is described above. But there are other ways that *Elimimation Notes* are triggered.
* When another player plays a clued card in their hand that they should not have known was playable yet, it implies that they saw the other possibilities in someone else's hand. Thus, this should trigger you to write *Elimination Notes* on your hand. This is called **Play Elimination**.

### Double Discard Elimination

* When a player who is in a *Double Discard* situation discards anyway with an obvious clue to give (such as an off-chop 5), it implies that they SEE the other copy of the card, and were not double discarding at all.
* Thus, when this occurs, you should write *Elimination Notes* on your entire hand for that card.

### The Weak Prompt

* If a teammate performs the *Prompt* convention on you and you have multiple cards in your hand that match the connecting card, normally you would be promised that the left-most (newest) is playable.
* However, if the card that initiated the prompt was ON CHOP when it was touched AND it was in danger of being discarded, the left-most rule no longer applies, since your teammate had to take drastic measures to prevent the discard of that card.
* So instead, you are promised that you have the connecting card somewhere in your hand, but it could be any of the cards, and not strictly the left-most.

### The Wrong Prompt (Mistake)

* A common mistake in Hanabi is to attempt to perform a *Finesse* when there is a "matching" card in that player's hand. Since *Prompts* take precedence over *Finesses*, the player will always play their matching clued cards first.
* When a card is *Prompted* and it misplays, everyone can read into this mistake - it was almost certainly a *Wrong Prompt*, meaning that the player who gave the clue probably intended for the *Finesse Position* card to play instead.
* Thus, if there is nothing else special about the situation, the player who misplayed should go on to play their *Finesse Position* card on the next turn.

### Critical Discards after a Chop Move (Mistake)

* If a player chop moves, and then the next time they discard, they discard a critical card, then obviously some kind of mistake occurred.
* The best explanation is that the chop move was never intended in the first place.
* Thus, when this happens, the player should "undo" the chop move.

### Duplication Responsibility

* Usually, if a 2 needs to be saved, it is not the responsibility of a player with already-clued 2's in his hand, because they could potentially violate *Good Touch Principle* by cluing it, so they should defer and let someone else on the team do it. (The same general concept also applies to cluing playable cards on chop, for example.)
* However, if all players have a clued 2 in their hand, then someone has to take a risk of violating *Good Touch Principle* in order to satisfy *Save Principle*. Who should do it?
* In this situation, the player who has the least number of matching clued cards should take responsibility. If 2+ players are tied, then the player with the more specific type of clue on their card(s) should take responsibility.
* If 2+ players have the exact same number of clued cards and type of clued cards, then either player should save the card.
* Example 1:
  * In a 3 player no-variant game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown 2's.
  * Cathy has 1 unknown 2.
  * Bob should let Cathy perform the save, since 1 matching card is less than 2 matching cards.
* Example 2:
  * In a 3 player no-variant game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown 2's.
  * Cathy has 2 unknown 2s.
  * The responsibility is shared, so Bob should perform the clue if Cathy has a good discard, or he can discard and let Cathy do it.
* Example 3:
  * In a 3 player no-variant game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown blue cards.
  * Cathy has 1 unknown 2s.
  * Bob should let Cathy perform the save, since 1 matching card is less than 2 matching cards.
* Example 4:
  * In a 3 player no-variant game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown blue cards. No blue cards have been played yet, so from Bob's perspective, each blue card has a 1/5 chance of being the blue 2.
  * Cathy has 2 unknown 2s. No 2's have been played yet, so from Cathy's perspective, each 2 has a 1/5 chance of being the blue 2.
  * The responsibility is shared, so Bob should perform the clue if Cathy has a good discard, or he can discard and let Cathy do it.
* Example 5:
  * In a 3 player no-variant game, Alice has a blue 2 on chop that needs to be saved.
  * Bob has 2 unknown blue cards. No blue cards have been played yet, so from Bob's perspective, each blue card has a 1/5 chance of being the blue 2.
  * Cathy has 2 unknown 2s. One 2 has been played already, so from Cathy's perspective, each 2 has a 1/4 chance of being the blue 2.
  * Thus, it is Cathy's responsibility to save the blue 2.

### Context Clues & The Stale 1s Clue

* Based on the *First Principles*, we have conventions that define what a clue means. But combined with this, we are always expected to look at the context of the game.
* For example, sometimes players will receive a clue that just feels strange. If this good clue could have been given a bunch of turns ago, why is it only being given now? Were the other players not paying close enough attention, and are only getting around to cluing this card now?
* In these types of situations, from *High Value Principle*, you can assume that the team is not making any mistakes, which means that the meaning of the clue should be altered from the "textbook" definition. We call these types of clues *Context Clues* because they rely on contextual reading of the game state.
* The most common *Context Clue* is given to "stale" 1's towards the beginning of the game. For example, in a 3-player game:
  * After a few ordinary clues happen, Alice discards, which ends the *Early Game* and initiates the *Mid-Game*. By doing this, she implies that there is nothing to do (because players are mandated to "extinguish" all of the available *Play Clues* and *Save Clues* in the *Early Game*).
  * Bob then immediately clues Cathy about two 1s.
  * Normally, from *Good Touch Principle*, Cathy would assume that both of the 1s were "good" and play both.
  * However, Cathy also knows that if both of these 1s were good, then Alice was required to clue them before discarding.
  * Thus, Cathy can reason that one of the 1s are bad. Furthermore, by convention, she knows that the oldest (right-most) 1 is bad, because that would be the one that she would ordinarily play first.
  * So, Cathy should skip over the oldest (right-most) 1, and play the other 1. Cathy should also treat the other 1 as known-trash.
* The *Stale 1s Clue* is specific example of a more general concept called *Focus Inversion*, which is covered later.

### Focus Inversion

* Sometimes, a play clue is given that both touches the chop card and one or more other card. The normal interpretation of this is to treat it as a chop-focus play clue, and play the chop. However, sometimes a player can know that the chop is not actually playable. This can be determined through:
  * explicit information - negative clues present on the card
  * implicit information - historical / contextual information about the card derived from moves that teammates performed earlier on in the game
* When this occurs, the clue is meant to be a play clue on the left-most card INSTEAD of the chop card.
* Just like a "normal" play clue that touches multiple new cards, the chop card (and other other new cards introduced) are not necessarily playable right now.
* In the following screenshot, nmego has a negative 1 clue on his chop so he should play his slot 1 card immediately. The chop card can be either yellow 2, yellow 3, yellow 4, but not yellow 5 (since Zamiel has it).

![Focus Inversion](img/focus_inversion.png)

### Burning (End-Game Stalling) & Same-Suit Principle

* In the *End-Game*, often times there are still a lot of cards yet to be played. Thus, you need to be very careful when discarding, since by drawing a card you can make the game end before everyone has a chance to play all of the cards.
* If there are enough of clues available, you can choose to stall, by giving a low-value (or even a completely useless) clue. This is referred to as *Burning* a clue.
* The best way to give a useless clue is to reclue cards which are already known to be playable.
* Give a *Burn Clue* if:
  * There is a possibility that the game can be completed without anyone discarding from now on.
  * You have two or more useful cards in your hand, and you want to follow *Team Distribution Principle*.
* Do not give a *Burn Clue* if:
  * The end-game has not started yet (see the *End-Game Threshold*).
  * You know that someone else will have to discard in the future.
  * There is only one more useful card in the deck and all of the useful cards in your hand are of the same suit as that card. This is known as *Same-Suit Principle*. For example:
    * You have two cards clued in your hand that you know to be yellow 3 and yellow 5.
    * The only useful cards left in the deck are two yellow 2's.
    * Here, there is no reason for you to stall, since the yellow 3 will NOT be played sooner if you stall.

### The Distribution Clue

* In the *End-Game*, it can sometimes be useful to clue a card that has already been clued in someone else's hand. This violates *Good Touch Principle*, but being in the *End-Game* changes the strategy.
* When a player has many playable cards, there is the risk that they will not be able to play all cards before the end of the game. Thus, it makes sense to spend a clue in order to relieve them from some of the card-playing burden. This distribute the plays more evenly throughout the team and is called a *Distribution Clue*, in order to better satisfy *Team Distribution Principle*.

<br />

## Level 4 - Expert Strategies

### The Occupied Play Clue & The Occupied Finesse

* If a clue could be given by multiple players, who should give the clue? Usually, it makes the most sense for the players with playable cards to play those cards, and the players with nothing to do to give the clue.
* If someone gives a clue with a playable card in their hand and forces the next person to have nothing to do, this is bad teamwork - unless there was a reason!
* When this occurs, even if the clue looks like an ordinary *Save Clue*, it MUST be a *Play Clue*, since the player who was doing it was occupied.
* Furthermore, if an *Occupied Play Clue* is given to a card that is not directly playable right now, it must be an *Occupied Finesse*!

### The Hidden Finesse

* Sometimes, you want to *Finesse* someone with a clued card already in their hand. However, if you try to *Finesse* them, they will assume it is a *Prompt* and will misplay their already clued card, so it doesn't work out.
* However, what if the clued card actually is playable? That means you can still do the *Finesse* - they will play the prompted card, see that it wasn't the card you had intended, and then blind play their 2nd newest card on the next turn. This is called a *Hidden Finesse* because the *Finesse* was temporarily hidden by the presence of another playable clued card.
* For example, say that:
    * Currently played on the board is a red 1 and a rainbow 2.
    * Alice has a rainbow 3 clued as red in her hand and no idea what it is. She also has a red 2 on newest slot.
    * Bob's red 3 is clued and now it is Alice's turn. Alice sees this as a prompt and plays her clued red card, which was just represented to be the red 2. However, it was the rainbow 3!
    * Since it wasn't the red 2, where could the red 2 be to make this clued red 3 playable? It must have been on Alice's newest slot. On her next turn, she blind-plays her 2nd slot card (it moved from 1st to 2nd slot since she drew a card from playing the rainbow 3).

### The Layered Finesse

* Since we don't allow lying outside of *Bluff Position*, it is possible to perform a *Finesse* on a card that is not in *Finesse Position*, as long as all of the cards leading to it are playable. Essentially, the intended *Finesse* blind play target is layered behind other playable cards.
* For example, at the beginning of the game, this is a 4-for-1 clue with full tempo:

![Layered Finesse](img/layered_finesse.jpg)

### The Clandestine Finesse

* Since we are allowed to lie in *Bluff Position*, doing a *Layered Finesse* in *Bluff Position* can be problematic, since it will typically only get one card played (instead of a big layered chain of cards).
* A form of *Layered Finesse* that gets around this restriction is called the *Clandestine Finesse*, because it is similar to a *Hidden Finesse*. When this move is performed, the player who is blind playing cards knows to keep playing because they see that if they do nothing, the next player will go on to misplay.
* In the following example, in Zealousy's hand, green 2 and green 3 are already touched with a green clue. Thus, a number 3 clue to Zealousy will get both the red 2 and the purple 2, because if Hyphen-ated does not continue to play the purple 3, Zealousy will think he has red 3 and misplay it.

![Clandestine Finesse](img/clandestine_finesse.png)

### The Stacked Finesse

* If a player has already been *Finessed* for a card in their *Finesse Position*, then their *Finesse Position* moves right one slot. (This is a similar concept to how the chop moves left one slot when a player is chop moved.)
* If another player does ANOTHER *Finesse* on a person who has already been *Finessed*, it is stacking a 2nd *Finesse* on top of the first, and they are expected to blind play the new *Finesse Position* card.
* However, because of the possibility of *Layered Finesses*, you should blind play your cards in order from left to right (and not jump ahead).
* When you have determined that a *Layered Finesse* was impossible AND that the order you play the cards in is not important, you should always jump ahead to demonstrate to the team that you "got" both *Finesses*.

### The Gentleman's Discard

* The *Sarcastic Discard* is very similar to the *Prompt* convention, because it gets someone to play a card that already had a clue on it. It is also possible to intentionally discard a known card in order to get someone to blind play a card, similar to a *Finesse*. When this occurs, it is called a *Gentleman Discard* to signify that the card played was completely blind as opposed to having a clue on it already.
* "Why did Bob just discard the red 3 that he JUST got a play clue on? That makes no sense. Wait - it must be because he realized that the red 3 was ALSO in someone else's hand. I don't have any clued cards in my hand, so I must have the red 3 in my *Finesse Position*."

### The Layered Gentleman's Discard

* One great reason to want to do a *Gentleman's Discard* is if the card you are discarding is also behind playable cards. Doing this gets "free" value.

### The Top Hat Clue

* Since the *Layered Gentleman's Discard* convention is so efficient, clever players that see the opportunity to perform one will almost always want to do so.
* Thus, it follows that in rare cases, when a teammate gives you a play clue on some card, they DON'T intend for you to play it. They intend for you to see the opportunity for a *Layered Gentleman's Discard*, and then immediately discard the card.
* This kind of clue is called a *Top Hat Clue* because you are giving them an opportunity to be a gentleman.
* Note that you should not mistake a *Top Hat Clue* for a clue that initiates a *Layered Finesse*. You are only allowed to discard the card if you can determine its exact identity.

### The Trash Push

* Normally, when a useless card is clued, it signifies a *Trash Chop Move*. However, what if the useless card is actually the card on chop? Then it wouldn't be chop moving anything.
* From *Good Touch Principle*, we know that it is pointless to spend a clue to touch useless cards on someone's chop, because if we just do nothing, the useless card will get automatically discarded.
* Subsequently, if this is done deliberately, it must have a meaning. By doing this, it means that we want to "push" the card that is next to the useless card onto the table.
* For example, in a 3-player game where all of the 1s are played already:
  * Bob has no clued cards in his hand. His chop is his slot 5.
  * Alice clues Bob number 1, which only touches his slot 5 card.
  * Bob blind plays his slot 4 card, and it is a playable red 2.
* Sometimes, a *Trash Push* is the only way to get a card played that is sitting between two other annoying cards.

### The Trash Bluff

* Normally, when a useless card is clued, it signifies a *Trash Chop Move* or a *Trash Push*. However, for both of these strategies to work, it is assumed that the recipient of the clue will know that the card that was touched is useless.
* What if the recipient of the clue does NOT know that the card that was clued is useless? They will go on to misplay that card, mistaking it for a "normal" *Play Clue*.
* When you see this occur, it works like a *Bluff*; you must blind-play your *Finesse Position* card, or the player who received the clue will go on to misplay.
* *Trash Bluffs* are a good tool to get a card played that is sitting behind other annoying cards.
* For example, in a 3-player game where all of the 1s are played already EXCEPT for red 1:
  * Cathy has no clued cards in her hand.
  * Alice clues Cathy number 1, which only touches her newest (slot 1) card. This card is a green 1, so Cathy will assume that it is a red 1.
  * Bob blind plays his *Finesse Position* card, and it is a playable red 1.
* Just like normal *Bluffs*, *Trash Bluffs* can only be done while in *Bluff Position*.
* If multiple cards are clued that cause a *Trash Bluff*, it means that ALL of the cards are trash. However, the focus of the clue should be the first thing discarded, which allows for the possibility of your teammates to give a follow-up *Fix Clue*.

### The Trash Finesse (strong form)

* It is possible to perform a *Trash Bluff* outside of *Bluff Position* if there is only one possibility for the useless card to be. When this is done, it promises that someone has that specific card, so it is a *Trash Finesse* rather than a *Trash Bluff*.
* It is also possible to *Double Trash Finesse*. By touching a useless 2 with TWO 2's remaining, it means that you see BOTH the 2s, so this can cause two people to blind play their *Finesse Position* card (or one person to blind play twice). Note that a *Double Trash Finesse* cannot be done in *Bluff Position*, or it will look like a normal *Trash Bluff*.

### The Trash Finesse (weak form)

* After deciding on the target of a clue, players carefully choose between using a color clue and a number clue in order to avoid violating *Good Touch Principle* with the ancillary cards that will be touched (since every clued card is treated as a card that will eventually be played). Sometimes, when both a color clue AND a number would violate *Good Touch Principle*, players are forced to pick between the lesser of two evils.
* However, sometimes you can see that it IS possible to use a color or number clue to uniquely touch a clue target without "picking up" extra bad cards. So, when this is done deliberately, it promises that the other players have the exact "missing" cards that the trash cards would look like.

### The Dupe Finesse

* Imagine that in a 3-player game:
  * Nothing is played on the stacks.
  * Alice has an already-clued 2 in her hand. She has no idea what color 2 it is.
  * Alice performs a *Finesse* by giving a red color *Play Clue* to a red 2 in Cathy's hand.
  * Bob blind plays red 1 from his *Finesse Position*.
  * Normally, Cathy would think that she has the next red card, which is red 2, and play it.
  * However, what if Alice actually has the red 2? In this situation, Cathy is expected to perform a *Sacrastic Discard*.
* Doing a *Finesse* that potentially duplicates a card in this way is called a *Dupe Finesse*. Normally, potentially duplicating a card is bad - it violates *Good Touch Principle* and could lead to a clue being wasted. However, potentially duplicating a card with the *Dupe Finesse* is not bad because:
  * In the best case, you get a "true" *Finesse* (a 2-for-1 or better).
  * In the worst case, you get a 1-for-1 and full knowledge on a clued card in your own hand that was previously a mystery.
* Normally, if a *Sacrastic Discard* could apply to multiple cards in your hand, you assume it is the left-most card. However, in the case of a *Sacrastic Discard* initiated from a *Dupe Finesse*, it does NOT promise the order, because they HAD to put something on the fishing line that you sent out, so to speak.

### The Certain Finesse / The Certain Discard

* Imagine that in a 3-player game:
  * Red 2 is played on the stacks.
  * Alice has an already-clued red card in her hand. It has a negative 4 clue on it, so from *Good Touch Principle* Alice knows that it is either red 3 or red 5.
  * Alice performs a *Reverse Finesse* by giving a red color *Play Clue* to a red 4 in Bob's hand.
  * Bob discards.
  * Cathy knows that she is promised the red 3 in her *Finesse Position*.
* This is an example of a *Certain Finesse* - it is similar to the *Dupe Finesse* above, but the "blind" card was potentially duplicated instead of the clued card.
* In this situation, if Alice really has the red 3, Cathy is allowed to blind-discard their *Finesse Position* card. This is called a *Certain Discard*, because Cathy can be certain that it is exactly red 3.
* A separate way to explain this convention is that everyone agrees that performing a *Layered Finesse* on a card that could potentially be in your own hand is illegal. So, everyone can be certain that they can safely blind discard a card to pass it back to someone who potentially duplicated.
* Note that players are ONLY allowed to do a *Certain Discard* if they know they have not been bluffed. (This means that *Certain Finesses* cannot be performed from *Bluff Position*.)
* Much like a *Sacrastic Discard* from a *Dupe Finesse*, if someone performs a *Certain Discard*, it does NOT promise the order, because they HAD to put something on the fishing line that you sent out, so to speak.

### The Certain Discard Duplication Promise

* As the recipient of a *Finesse*, you are promised a card that you have to blind play. However, as long as it is not a *Certain Finesse*, you HAVE to account for the possibility of a *Layered Finesse*. This means that you can never blind-discard the promised card to perform a *Gentleman's Discard*, for example.
* After the *Finesse* has occurred, but before the promised card has been blind played, there is a window where a teammate might find strategic value in duplicating the promised card in someone else's hand.
* Unless the duplication was a last-resort, if the teammate duplicates the blind card, it PROMISES that the duplicated card is on *Finesse Position* (and there is NO *Layered Finesse*), which allows the recipient of the *Finesse* to blind-discard that card, similar to a *Certain Discard*.
* Finally, from the perspective of the person receiving the clue, if they end up playing the duplicated card first, then they should know that the focus of the original clue was on the other, non-duplicated card, and they can play it immediately afterwards. (Otherwise, the original clue would be fairly low-value.)
* Note that as long as the duplication clue touches two or more cards, the *Certain Discard Duplication Promise* interpretation takes priority over the *Dupe Ejection* interpretation.
* Examples:
  * Game #6817, turn 15
  * Game #6799, turn 5

### The Out-of-Order Finesse

* Sometimes, a *Finesse* is invoked by giving a color clue to two or more cards where the next card in the sequence is clued, but it is NOT the focus of the clue.
* When this happens, the *Finesse* will still work: a player will blind play a matching card. However, a *Fix Clue* must then be given to the person who originally received the clue, or they will go on to misplay.
* Normally, after receiving a *Fix Clue*, a player would normally "stop" and not assume anything else about his hand. However, this is a special situation: when the original *Finesse* was given, it was a message that the focus of the clue was playable. *Information Lock Principle* applies, and it means that the original focus of the clue is also playable.
* For example, in a 3-player game:
  * At the beginning of the game, Alice goes first.
  * Bob has a red 3 and a red 2 (on slots 1 and 2 respectively).
  * Cathy has a red 1 on slot 1 (in *Finesse Position*).
  * Alice clues Bob reds (as an *Out-of-Order Reverse Finesse*). The focus of the clue is the red 3 on slot 1.
  * Bob sees the red 1 on Cathy's *Finesse Position*, so he has to respect that it could be *Reverse Finesse*. Bob discards.
  * Cathy blind plays red 1.
  * Alice must now give a *Fix Clue* to Bob, or else red 3 will be misplayed as red 2.
  * Alice clues number 2 to Bob.
  * Bob plays red 2.
  * Bob knows that his other red card MUST be red 3, since it was originally clued as playable and it caused a *Reverse Finesse*.

### Finesses with a Lie Component

* *Good Lie Principle* states all that lies must resolve immediately. However, some players will ocassionally perform *Finesses* that violate this principle. We would say that such *Finesses* have a *Lie Component*.
* Do NOT perform any moves with a *Lie Component* unless you are an expert player and understand the deep nuance involved in such a line. With that said, it is sometimes possible to construct safe lines that contain a *Lie Component*.
* The previously mentioned *Out-of-order Finesse* is an specific example of a *Finesse* with a *Lie Component*. One key attribute of the *Out-of-order Finesse* is that the player who recieves the fix clue knows that ALL of the related cards are playable, or it would not have been worth the risk (and the confusion) to perform a line with a *Lie Component* in the first place.
* This concept can also be generalized to all *Finesses* that have a *Lie Component* - even after a *Fix Clue*, you should assume that all of the cards are playable.
* There are exceptions to this rule. For example, if a huge *Finesse* happens that gets five cards blind-played and then you get a *Fix Clue* at the very end, the normal logic doens't apply: you can reason that your teammates would have wanted to perform a lie in order to get a huge Finesse, so it was worth it even if the final card from the *Fix Clue* was not necessarily playable.

### The Early 5's Play Clue & The Early 5's Chop Move

* In the *Early Game*, since you are allowed to stall by cluing off-chop 5's, it is generally impossible to perform the *5's Chop Move*.
* However, players are not generally supposed to stall until all of the "normal" *Play Clues* and *Save Clues* have been given.
* Thus, if you receive a number 5 clue that looks like a stall in the *Early Game* and you can see that the player had a good non-stall clue to give, then it is actually a *Play Clue* on the 5.
* Alternatively, if the 5 is one away from chop, then it turns into a *5's Chop Move*.

### The Priority Prompt & The Priority Finesse

* When a player has a choice between two playable cards to play, everyone agrees that there should be a specific *Priority* that they should be played in. The agreed *Priority* is as follows:
  1) Blind-plays — demonstrating that a *Finesse* or *Bluff* occurred is very important
  2) Cards that lead into someone else's hand — otherwise the team would lose *Tempo*
  3) 5s — playing a 5 gets the team a free clue, which is really good
  4) The lower rank card — smaller stacks are more important to fill up
  5) The left-most card — the left-most one is more likely to be good
* When a player does NOT play the card with *Priority*, it is strange, and they must be trying to send a special message.
* Based on what card they did play, if you have any cards in your hand that match the next "connecting" card, it is a message that you can play it right now, similar to a *Prompt*. (The difference is that instead of initiating the *Prompt* with a clue, they initiated it with the order that they played cards.)
* Alternatively, if you do not have any clued cards in your hand that matches the card that they played, then you you should play your *Finesse Position* card as a *Priority Finesse*.
* Note that *Priority Prompts* and *Priority Finesses* are only a thing when the player has FULL KNOWLEDGE of the two cards that they are prioritizing. For example, players might be trying to potentially play into someone else's hand, with only a chance that they have a matching card.
* For example, this IS a *Priority Finesse*:
  * Alice has a known playable red 1 and a known playable blue 2 in her hand.
  * Alice plays blue 2.
  * Bob comes next. Bob does not see any red 2s. He does not see any blue 3s either. Thus, Alice was supposed to play the red 2 first.
  * This means that Bob must have blue 3, so he blind-plays his *Finesse Position* card.
* For example, this is NOT a *Priority Finesse*:
  * Alice has a known playable red 1 and a known playable blue 2 in her hand.
  * Alice plays blue 2.
  * Bob comes next. Bob does not see any red 2s. Bob does see blue 3 on the chop of Cathy. Thus, Alice played the blue 2 to give Cathy something to do.
  * Bob clues blues to Cathy as a chop-focus *Play Clue*.
* Similar to a normal *Prompt*, if a *Priority Prompt* could apply to two or more clued cards, then you should play the left-most one.
* Similar to a normal *Prompt*, if a *Priority Prompt* mades you play the left-most card and it was not the matching card, then you should continuing playing clued cards until you find the matching card.
* Finally, note that the "left-most" *Priority* is contextual and does not always apply. For example, it is common for players to play a right-most card that was originally clued with a *Save Clue*, since that card was explicitly saved and that the other cards in the hand of the same rank could potentially be duplicates.

### Play/discard order of like cards

* ***Tl;dr for experienced players*** "1s out-of-order chop move" and "trash discard chop move" are consolidated into "Play/discard order of like cards", which is also expanded to cover some rarer cases. The prescription is also changed for skipping over more than one card.
* One may hold multiple *like* cards at a given time. "Like" here means playable cards of the same rank, or trash cards. Meaning can be encoded here in the order in which these cards are played or discarded, respectively.

* The "play order principle" defines the conventional order in which to play/discard these cards.
* The meaning we assign to non-conventional play/discard order depends on the game period:
  * In the early game and midgame, applying to multiple playable cards of same rank but undistinguished suit (most commonly opening hand 1s), or multiple trash cards, or multiple fully distinguished playable 5s:
    * Playing/discarding these cards in the non-conventional order indicates a *chop move*, and the number of cards skipped in the conventional order indicates which player should chop move, skipping over players with locked hands. Examples:
      * Alice has three opening hand undistinguished 1s clued. She is expected to play the *rightmost* one. Playing the *middle* one will chop move Bob, and playing the *left* one will chop move Cathy.
      * Alice has three trash 1s clued in the midgame. She is expected to discard the *leftmost* 1. Discarding the *middle* one normally would chop move Bob, but he's locked, so it chop moves Cathy; discarding the *rightmost* one therefore chop moves Donald.
      * Alice has been 2-saved, leaving her with 2s on slots 3 and 4. Finally, all the 1s are played, and her 2s are still uncolored. She is expected to play slot 4 first, since it is known to be an important card; the other may be a dupe. Playing slot 3 will chop move Bob.
  * In the lategame, applying to multiple trash cards, or multiple fully distinguished playable 5s:
    * These are expected to discard/play *right to left*, so that a discard/play of the non-*rightmost* indicates a *positional play* on someone else's hand in the corresponding slot. Examples:
      * Alice holds two yellow cards in the lategame, in slots 1 and 3, and all yellow stacks have been completed. Alice is expected to discard slot 3; discarding slot 1 will indicate that one of her teammates has an uncalled playable card on slot 1. By extension, discarding slots 2 or 4 also indicate positional plays.
      * Alice holds a playable true yellow 5 in slot 2 and a playable true blue 5 in slot 3. Alice expected to play the blue 5; playing the yellow 5 indicates another player may blind play slot 2.

### A Priority Flowchart (For Choosing Between 2+ Playable Cards)

*Priority* can sometimes be confusing. [Here is a handy flowchart](https://raw.githubusercontent.com/Zamiell/hanabi-conventions/master/img/priority_flowchart.png) that shows, in general, which card should be played when there is a choice between two cards.

### Rank Priority Prompts/Finesses in Dual-Color Variants

* When you get a play clue on a card that could be multiple suits, you must take the average of all of the ranks and treat the card as having that rank for the purposes of performing a *Rank Priority Finesse*.
* For example, in a 3-player *Wild & Crazy* game:
  * The green 1 and rainbow 2 are played on the stacks.
  * Mike receives a yellow *Play Clue* on slot 1.
  * This means that the card could be a green 2, orange 1, or rainbow 3.
  * Thus, the average rank is: (2 + 1 + 3) / 3 = 2
  * Mike also knows that he can play a white 2 on slot 4.
  * If the average value ended up being higher than 2.0, then Mike would have to play the white 2 first, or else it would initiate a *Rank Priority Finessse*.

### The Priority Bluff & The Priority Layered Finesse

* If is possible to lie to the next player and imply a *Priority Finesse* when they have an unrelated card on *Finesse Position*.
* After the unrelated card is played, since the person who lied was in *Bluff Position*, no further cards should be promised.
* If an unrelated card was played and the person who lied was not in *Bluff Position*, it implies a *Priority Layered Finesse*.

### Ejection

* *Ejection* refers to a move like a *Finesse*, but instead of playing your *Finesse Position* card, you instead play your *Second Finesse Position* card. (For example, if your hand is completely unclued, your *Second Finesse Position* is slot 2.)
* Certain types of "wasted" clues signal an *Ejection*.

#### Dupe Ejection

* If someone clues a card as a "one for one", and that card is already clued in someone else's hand, this is usually a *Distribution Clue*, which is sometimes done in the *End Game*.
* However, if this type of move is done before the *End Game*, it must have some other purpose - it should signal an *Ejection* on the very next player.

#### Known Trash Ejection

* Often times, a player can have one or more cards that are known duplicates / trash. They will discard them it without being told anything further.
* If a clue is given that ONLY touches cards that are already known trash, then it must have some other purpose - it should signal an *Ejection* on the very next player.

#### Double Play Ejection

* If a player knows that a card in their hand is playable, and then they recieve ANOTHER clue on that card, it is usually a *Stop Clue*, which means that the card is actually bad and they should discard it instead of playing it.
* However, if this happens on a good card, the other players can see that the clue must have some other purpose - it should signal an *Ejection* on the very next player.

<br />

## Level 3 - Variant-Specific Strategies

### Black 2 & Black 5 Saves

* This convention applies to the *Black Suit (One-of-Each)* and *Wild & Crazy* variants.
* Players should save black 2s and black 5s with a number clue instead of a color clue. (This helps narrow down what card is being clued.)
* There are four exceptions to this:
  * if the black clue touched two or more brand new black cards OR critical Rainbow cards
  * if the black clue was required to avoid violating *Good Touch Principle*
  * if the black clue "filled in" an ancillary card
  * if the black clue gave important negative information to one or more cards in the hand (which mostly applies to the *Wild & Crazy* variant)
* Subsequently, if a black clue is used to touch a black 2 or a black 5 (and the above exceptions are not applicable), then it implies a *Finesse*.

### Black 3 & Black 4 Saves

* This convention applies to the *Black Suit (One-of-Each)* and *Wild & Crazy* variants.
* Players should save black 3s and black 4s with a color clue instead of a number clue. (This helps narrow down what card is being clued.)
* There is one exception to this:
  * if the number clue also touched a critical card
* Subsequently, if a number clue is used to touch a black 3 or a black 4 (and the above exception is not applicable), then it implies a *Finesse*.

### The Free Choice Finesse

* This convention applies to any variant with a *Rainbow* suit or a dual-color suit.
* When performing a *Prompt* by touching a sole rainbow card, the player doing the clue may have a free choice between multiple colors. In other words, there may exist multiple colors that will ONLY touch the rainbow card.
* If a player has a free choice to choose the color that matches the intended prompt target but instead deliberately chooses a different color, this signals that it is actually a *Finesse* instead of a *Prompt*.

### The Free Choice Bluff

* This convention applies to any variant with a *Rainbow* suit or a dual-color suit.
* It is possible to use the *Free Choice* convention to communicate to a teammate that you want a *Finesse* instead of a *Prompt* in order to get them to play an unrelated playable card from their *Finesse Position*.
* Like a normal *Bluff*, after a *Free Choice Bluff*, the person who blind-played does not necessarily have the "matching" card in their hand.

### The Suboptimal Color Bluff

* This convention applies to any variant with a *Rainbow* suit or a dual-color suit.
* Often, when giving a color clue to a Rainbow or dual-color card, you want to pick a color that will "fill-in" ancillary cards in the hand as to give the maximum amount of information.
* If a suboptimal color is chosen that does not fill in ancillary cards, it follows from *High Value Principle* that there must be a reason, so you should blind play your *Finesse Position* card.
* This move is contextual in that you don't want to make it appear as if the clued card is currently unplayable. Thus, it is best performed as a *Reverse Bluff* or a *Long-Distance Bluff*.

### White Compromise

* This convention applies to any variant with a white (colorless) suit.
* When you clue a white 5 that is one away from chop, it would normally look like a *5's Chop Move*.
* However, if white 4 is currently played, all 5 clues that could be *5's Chop Moves* are treated instead *Play Clues* on white 5.

### The Negative Prompt

* This convention applies to the *Dual-color Suits* variant.
* In this variant, since negative color information conveys just as much information as positive color information, you should include that when deciding which card to play into a prompt.
* For example, if you have a red card in slot 1 with no negative clues, and a red card in slot 2 with negative yellow, then normally you would play left-most if a Magenta card was prompted. But with this convention you would play slot 2.

### Crazy 3 Saves & Crazy 4 Saves

* This convention applies to the *Wild & Crazy* variant.
* In this variant, it is possible to violate *Good Touch Principle* by cluing black to save a black 3 or a black 4, because there can be other useless rainbow cards in the hand.
* Thus, for the *Wild & Crazy* variant, a second exception to the *Black 3 and Black 4 Saves* convention is added:
  * if the number clue was required to avoid violating *Good Touch Principle*
* *Crazy 3 Saves* & *Crazy 4 Saves* do NOT apply to 5-player games; see the "Wild & Crazy 5-Player Alterations" section below.

### Crazy Black 4 Bluffs

* This convention applies to the *Wild & Crazy* variant.
* The *Critical 4 Bluff* convention is deleted in this variant (since it conflicts with *Finesses* using white 4).
* Even though the *Critical 4 Bluff* is deleted, it is still legal to use a black 4 to bluff. However, this MUST be done with color.

### Wild & Crazy 5-Player Alterations

* These conventions only apply to the *Wild & Crazy* variant with 5 players.
* Nearly all of the conventional "rules" are closely followed in 5-player games, regardless of the variant. And the same goes for 4-player games in the *Wild & Crazy* variant.
* However, 5-player *Wild & Crazy* is extremely difficult. Thus, we have slightly altered some conventions to be more "aggressive" in this game type:
  1) No *Crazy 3 Saves* and no *Crazy 4 Saves* – you must duplicate a rainbow card if you want to save a black 3 or black 4
  2) No Locked Hand Saves – locked players must perform a "hard burn" if they have no normal *Play Clues* or *Save Clues* or off-chop 5s to clue
  3) Ending the *Early Game* – players may choose to not "extinguish" all of the available clues, especially if the last remaining clue is a 1-for-1
* Besides these specific alterations, you should also account for the fact that the team will play more risky in general – more aggressive discards, more letting cards "ride" on chop, and so forth.

### Acid Trip Conventions

* These conventions apply to the *Acid Trip* variant.
* Cards with color clues on them are not treated as clued cards. In other words, your chop is your right-most (oldest) card without a number clue on it.
* Number clues mean the same thing as normal.
* All color clues have a special meaning:
  * Blue means play slot 1.
  * Green means play slot 2.
  * Yellow means play slot 3.
  * Red means play slot 4.
  * Purple means play slot 5 (in 2 and 3-player games).
  * Purple means play slot 1 AND the next person plays their *Finesse Position* card (in 4 and 5-player games).
  * Orange means chop move.
* All color clues have to be treated as potential *Delayed Play Clues*, *Prompts*, and *Reverse Finesses*.

<br />

## Level 3 - Rarely Used Advanced Strategies

### Hard Bluffs

* Sometimes, it can be ambiguous as to whether a player blind played a card into a *Bluff* or a *Finesse* + *Prompt*. In this situation, *Occam's Razor* applies, so players should always opt with the former (simpler) interpretation. When such a *Bluff* occurs, it is called a *Hard Bluff* to disambiguate from situations where *Bluffs* happen with no ambiguity.
* For example, this is a *Finesse* + *Prompt* and NOT a *Hard Bluff*:
  * Only red 1 is played on the stacks. No cards are in the discard pile.
  * Cathy has a 3 clued in her hand (with no color information on it).
  * Alice clues Cathy about a brand new 4.
  * Bob blind plays red 2.
  * In a normal Bluff, a "one-away" card is clued. However, Cathy sees that the highest stack is the red stack, so the 4 in her hand must be "2-away".
  * Thus, Cathy does NOT read it as a *Bluff*; she is promised red 3 and red 4, so she plays the unknown 3 as red 3.
* For example, this IS a *Hard Bluff*:
  * Red 1 AND blue 2 are played on the stacks. No cards are in the discard pile.
  * Cathy has a 3 clued in her hand (with no color information on it).
  * Alice clues Cathy about a brand new 4.
  * Bob blind plays red 2.
  * This could be a normal *Bluff* if the 4 in her hand is blue 4, since blue 4 is currently "one-away". Thus, Cathy DOES NOT assume that her 4 is red 4, and subsequently, does DOES NOT assume that her unknown 3 is a red 3. However, it could ALSO be the case that the 4 is a red 4 (if the 3 in her hand happens to be red 3).
  * Thus, Cathy marks down both possibilities for later and does not play anything right now.

### The Setup Clue

* In the *Early Game*, the order of operations is usually:
  * give play clues
  * give save clues to cards that are on chop
  * clue off-chop 5s
* Thus, in the *Early Game*, if someone jumps ahead and ignores all of the *Play Clues* and *Save Clues* on the board to number-clue an off-chop 5, this is very strange, and would usually communicate an advanced strategy like a *Finesse*.
* However, if cluing the 5 moved that player's *Finesse Position* card to a playable card, then the point of the 5's clue may have been to set up a *Finesse* or *Bluff* of some kind.
* Subsequently, if you see that an off-chop 5's clue allowed a *Finesse* or *Bluff* to occur, then you should not read very strongly into the original 5's clue.
* Note that rarely, *Setup Clues* can also be given to 5's in the middle of the hand that don't modify the *Finesse Position*. The point of this is to allow valid *Layered Finesses* to occur that "skip" over the 5.

### The Setup Finesse

* In the *Early Game*, it is common to number-clue a 5 on slot 1 as a *Setup Clue*. This is usually followed up by a *Finesse* or *Bluff* on the new *Finesse Position* (slot 2).
* However, if the *Setup Clue* is never followed up, the player who received the *Setup Clue* should blind-play their new *Finesse Position* card.
* One problem with the *Setup Finesse* is that sometimes, in the *Early Game*, people clue on off-chop 5s as a "stall" clue. And sometimes, they clue an off chop 5s as a *Setup Finesse*. How can everyone tell the difference?
* The way to tell the difference is the "2 Thing Rule", which states that it is a *Setup Finesse* if there are at least 2 other things to do that are better than cluing an off-chop 5 (from the perspective of the player blind-playing into the *Setup Finesse*).
* Players should keep in mind the "2 Thing Rule" is tricky in that it has information asymmetry: if there are ONLY 2 things to do in 2 separate hands, then those 2 players will NOT know that a *Setup Finesse* has occurred. All players will have to keep this in mind until the *Setup Finesse* has been demonstrated.

### Cluing Off-Chop 2s

* On the first turn of the game, it is not possible to discard. If there is absolutely nothing else to do, it is permissible in this situation to use a 2 number clue to save a 2 that is not on chop (but only if the other players can see that you had no other choice).

### Immediate Double Clue

* If you are clued the exact same thing twice before it gets to be your turn, it means that you can play ALL of the cards that the clue applies to, but in the opposite order than normal (right-to-left, since you would normally play cards from left-to-right).
  * If one of the cards includes the chop card, it means to play all of the cards from 2nd oldest to newest, and then the chop last.
* If you are re-clued about a bunch of cards after you have already taken a turn, see the *Double Tempo Clue* convention.

### The Elimination Blind Play Riding Deduction Bluff

* Typically, when a player has two cards with *Elimination Notes* and the "true" copy of the card is on chop, you must clue it to let them know.
* However, if the other card is also playable, you can "lie" to them and not clue anything.
* Next, the player should perform an *Elimination Blind Play Riding Deduction*, and play the unrelated card.
* After that, there will be only one card left with an *Elimination Note*, so they will go on to play the "true" card on their next turn.

### The Elimination Finesse

* Normally, if a player is *Finessed*, they are supposed to play their *Finesse Position* card. However, if the player has two or more *Elimination Notes* in their hand for the specific finessed card, they know that it cannot be on *Finesse Position*.
* In this situation, the player is expected to play the OLDEST of the cards with the elimination notes on them.
* For example:
  * It is the middle of a 3-player game.
  * On the stacks, blue 2 is played.
  * Alice has a completely unclued hand.
  * Alice discards a blue 3. She writes *Elimination Notes* on slots 2, 3, 4, and 5.
  * Bob clues Cathy blues, indicating a blue 4. Cathy discards.
  * At first, this looks like a *Reverse Finesse*, as it is calling for the blue 3. However, the blue 3 cannot be in her *Finesse Position* (slot 1), as she knows it must be either on slot 2, 3, 4, or 5. So it must be a *Reverse Elimination Finesse*.
  * The *Elimination Finesse* promises that it is her oldest card, so she plays slot 5 as blue 3.
* *Elimination Finesses* apply to ALL types of situations with *Elimination Notes* (including *Discard Elimination Notes*, *Play Elimination Notes*, and *Double Discard Elimination Notes*). Subsequently, you can more specifically describe an *Elimination Finesse* as a *Discard Elimination Finesse*, a *Play Elimination Finesse*, or a *Double Discard Elimination Finesse*.
* Note that normal *Finesses* take priority over *Self-Elimiation Finesses*. For example:
  * On the stacks, blue 2 and green 2 are played.
  * Alice has *Elimination Notes* on slot 3 and slot 4 for red 3.
  * Someone clues a number 4 in Alice's slot 1 as a *Self-Finesse*.
  * Alice must assume that it is a normal *Self-Finesse* and play blue 3 from slot 2. (If it was an *Elimiation Self-Finesse*, she would play red 3 from slot 4.)

### The Chop Transfer

* Sometimes, cards are accidently chop moved through a mistake or through a complicated situation. In these kinds of situations, it is pointless to waste a clue to "undo" the chop move; you can just continue to allow them to discard normally. That is, until they get something good on chop.
* Only then will the team bother cluing the chop directly to convey that it is useless. And then, the player receiving the clue will know that the card they were about to discard is important, and permanently chop move that card, and discard the now known useless card.
* Thus, this is nearly the same thing as a *Early Fix Clue Chop Move*, but when the *Fix Clue* is given to a card that was already chop moved (and had no positive clues on it already).

### The Scream Blind Play (Blind-Playing Chop)

* The *Scream Discard* is a powerful last-resort move that "screams" at the next player, telling them that their chop is unsafe. This is useful because you can do it even when the team is currently at 0 clues. However, you can only perform this move if you have a known playable card in your hand. In some situations, you will need to "scream" at the next player even when you do not have a known playable card.
* If you can't give a clue, as a last resort you can send a signal to your teammate by blind-playing a card. You don't want to accidentally blind-play a critical card, so the safest card to blind play is your chop.
* By doing this, it "screams" at the next player, accomplishing the same thing as a Scream Discard, namely:
  * they should chop move a card
  * if there are 1 or more clues in the bank, they are not allowed to discard on their next turn
* If you see someone blind-play their chop and it works, your first thought may be that it could be a *Scream Blind Play*. However, it could also be a *Negative Blind Play*, so it is important to not confuse these two strategies.
* Note that a *Stop Blind Play* (listed below) is almost exactly the same as this move, but it has a completely different interpretation. Whether or not a move is a *Scream Blind Play* or a *Stop Blind Play* is entirely dependent on the context of the situation.

### The Stop Blind Play (Blind-Playing Chop)

* Sometimes, due to a mistake or a complicated situation, you can see that the next player after you is going to misplay a critical card. Additionally, there may be no "fix" clue that you can give that will remedy the situation, or perhaps you are currently at 0 clues.
* If you can't give a clue, as a last resort you can send a signal to your teammate by blind-playing a card. You don't want to accidentally blind-play a critical card, so the safest card to blind play is your chop.
* By doing this, it sends an emergency signal to the next player, warning them to STOP whatever it is they were about to do.
* If you see someone blind-play their chop and it works, your first thought may be that it could be a *Stop Blind Play*. However, it could also be a *Negative Blind Play*, so it is important to not confuse these two strategies.
* Note that a *Scream Blind Play* (listed above) is almost exactly the same as this move, but it has a completely different interpretation. Whether or not a move is a *Scream Blind Play* or a *Stop Blind Play* is entirely dependent on the context of the situation.

### The Whisper Discard Chop Move

* Occasionally, a player will have known trash in their hand. They are always expected to discard the known trash first before discarding their right-most unclued card.
* Thus, if a player instead discards their right-most unclued card instead of known trash, it must be a signal that something is wrong, exactly like a Scream Discard. This is more subtle than a Scream Discard though, so it is called a Whisper Discard.
* Whisper Discards are to be treated identically to Scream Discards. In short, this means that they 1) cause a chop move and 2) force a clue to be given on the next turn.

### The Long-Range Scream Discard

* A *Scream Discard Chop Move* is done only as a last resort. So, if the next player has an unimportant card on chop, then the move is usually a *Generation Discard* and does not chop move anyone.
* In other words, from the perspective of the next player:
  * if a safe card is on the next person's chop --> *Scream Discard* --> self-chop move
  * if a critical/playable card is on the next person's chop --> *Generation Discard* --> clue critical card directly with the generated clue
* However, what if the next player has either:
  * a known playable card
  * a known safe trash discard
* This means that it CANNOT be a *Scream Discard* on them, and all players can know this. Thus, everyone can conclude the other possibility, so there is no need to waste a clue on the next person's critical card at all!
* So, when a *Scream Discard* happens and the next player has a known play / known safe discard, is a *Long-Range Scream Discard* and the NEXT person should treat it as a *Scream Discard* on them (meaning that they chop move and can't discard on their next turn).
* In the unlikely scenario where two people in a row have known plays / known safe discards, then it is an *Extremely Long-Range Scream Discard* on the next person after that, and so forth.
* A *Long-Range Scream Discard* is useful if multiple players in a row have critical/playable chops, because you don't want them *Scream Discarding* for each other. Alternatively, it is also useful if they won't know that the next chop needs to be saved (if it plays through cards in their own hand, for example).
* A *Long-Range Whisper Discard* works in the same way.

### Stop Discard

* Normally, when someone discards with a known play and the next person already has something to do, it is a *Long-Range Scream Discard*.
* However, it could also be the case that the next person after that does not have a playable/critical card on chop. Or, alternatively, it could be the case that EVERYONE has something to do on their turn. Thus, discarding is normally considered a mistake.
* But the player who is discarding is not making a mistake - they are communicating that the very next player with a "known play" should STOP what they are doing, because the card is not actually playable.
* This is very similar to a *Stop Blind Play*, but since the player has a known play, there is no reason to use up one of the strikes when the same message can be communicated in a safer way.
* If there is a card that could potentially be playable on on chop, then the *Long-Range Scream Discard* interpretation takes priority over the *Stop Discard* interpretation.

### The No-Information Double Finesse (for 3's)

* When a 3 exists in someone else's hand and already has a clue on it, it can be filled in with a second clue to cause a *3-Bluff* to occur. This is still a normal *3-Bluff*; it is only supposed to get 1 card to blind-play and does not imply a *Finesse*.
* However, if a 3 is reclued and gives no additional information on the card, it always implies a *Double Finesse* instead of a *3-Bluff*.

### The Bad Touch Double Finesse (for 3's)

* Normally, a *3 Bluff* takes priority over a *Double Finesse*. This means that if someone clues a blue 3 using the number 3, and then a blue 1 blind plays on the very next turn, no-one is promised the blue 2.
* However, if BOTH blue 3's were touched with the number 3 clue, then that would violate *Good Touch Principle*, and this would be considered a "bad touch".
* If someone is violating *Good Touch Principle*, they must have a very good reason, so the clue must be a *Double Finesse* instead of a *3 Bluff*. In the above example, the next player should blind-play the blue 2 from their *Finesse Position*.
* After that, the player who recieved the clue can safely discard the focused 3.

### The Sacrifice Discard

* It is generally undesirable for a player to have a "fully locked" hand, but sometimes it happens. And sometimes, one card in the locked hand is useful in the future, but not critical (meaning there is another copy of the card in someone else's hand or still in the deck).
* Normally, you are never supposed to discard cards that have clues on them, as if you do, it implies a *Sarcastic Discard* or a *Gentleman's Discard*. However, in this situation, the player who is locked can choose to "sacrifice" one of the cards in their hand that is non-critical. And in this situation, it does NOT imply a *Sarcastic Discard* or a *Gentleman's Discard*.

<br />

## Level 4 - Rarely Used Expert Strategies

### The Elimination Bluff / The Elimination Layered Finesse

* It is possible to lie to a player who has *Elimination Notes* on their hand and pretend like you are performing an *Elimination Finesse* on them, causing them to play their oldest card as per the convention. This can cause an unrelated playable card to play.
* If the player who performed the clue was in *Bluff Position*, then it is to be treated like a *Bluff*, and thus they will not know where the actual *Elimination Card* is. (However, in most cases, at this point there will only be one remaining card with an *Elimination Note* on it, so it won't matter.)
* If the player who performed the clue was not in *Bluff Position*, then the blind-playing person is expected to keep playing until they find the intended card. This is similar to how a *Layered Finesse* works, but it is inverted such that they play cards from oldest to newest.

### The Patch Finesse

* If a player performs a *Layered Finesse* through a card that is one-away from being playable, it is possible to see that an impending misplay will occur.
* This is a signal to you that you need to "patch" the problem, so you have the matching card in your *Finesse Position* to make the one-away card actually playable.
* In general, you must give preference to a patch interpretation. Thus, you might need to hold off before playing a card for a while to see if a patch blind-play occurs.

### The Patch Gentleman's Discard

* Similar to a *Patch Finesse*, a *Gentleman's Discard* can also contain a "patch" component.

### The Reverse Bluff / The Out-of-Position Bluff (bad)

* Similar to a *Reverse Finesse*, it is possible to perform a *Reverse Bluff*. However, according to *Good Lie Principle*, it is only allowed to lie to the player who comes immediately after you.
  * Why this policy? It is not possible to play with both *Layered Finesses* and *Reverse Bluffs* at the same time, and *Layered Finesses* are much better.
* However, you can break the *Bluff Position* rule in rare situations where the player that is being passed over cannot actually act on their state of misinformation. For example,
  * they are at 0 clues (and won't blind play anything)
  * they have negative information on their entire hand
* Since valid *Reverse Bluffs* are so rare, it is important to remember that a valid *Reverse Bluff* is distinct from a *Layered Finesse*, and that blind playing should stop after the first blind play. (This is a common mistake.)

### The Double Half Bluff

* Sometimes, you see that two players in a row have cards on their newest slot that are playable. However, they are unrelated, so you can't get them both played with a double finesse. This is where the *Double Half Bluff* comes in - it is very similar to a *Double Finesse*. In this situation, by performing a clue that looks like a *Double Finesse*, you can get the first card played like a normal *Finesse* and the 2nd card like a *Bluff*.
* For example, on the first turn of a 4-player game:
  * Alice clues Donald red to highlight a red 3.
  * Bob goes next and assumes that it is a *Double Self-Finesse* - he has the red 1 and red 2 in the two newest slots. Thus, he blind-plays his left-most and it is red 1.
  * Cathy goes next. Cathy sees that Donald does NOT have red 2 in her next newest slot, so he must have the red 2, so he blind-plays his left-most card. However, it is NOT the red 2, but the blue 1. Bob now knows he was bluffed.
  * Alice sees Bob blind play "for no reason", so she knows that she must not have the red 2 and it must have been a *Double Half Bluff*.
  * Finally, Cathy sees this sequence of events occur. Since Alice and Bob blind-played, she must have the red 3.
* Normally, you are only allowed to *Bluff* while in *Bluff Position*. But *Double Half Bluffs* do not violate *Good Lie Principle*, so we allow them.

### The Double Bluff

* Similar to a *Double Half Bluff*, it is also possible to get 2 cards played in a row that are completely unrelated.
* For example, in a 4-player game:
  * Yellow 2 is currently played on the stacks.
  * Alice clues a yellow 5 in Donald's hand with a yellow color *Play Clue*.
  * Since yellow 5 is playable right now, Bob thinks he has yellow 3 and yellow 4. Bob blind-plays his *Finesse Position* card, but it is actually a blue 1.
  * Cathy sees that Bob blind-played because of the yellow clue. However, since the yellow 5 is a two away card instead of one away card, it must mean that it is a *Double Bluff* instead of a single *Bluff*. Cathy blind plays her *Finesse Position* card and it is red 1.
  * Donald knows that this yellow card must be yellow 5 because it caused 2 blind plays.
* Normally, you are only allowed to *Bluff* while in *Bluff Position*. But *Double Bluffs* do not violate *Good Lie Principle*, so we allow them.

### The Triple Bluff / The Triple Two-Thirds Bluff

* Following from the *Double Bluff* convention, it is possible to perform a *Triple Bluff*. For example, on the first turn of the game:

![Triple Bluff](img/triple_bluff.png)

* In this screenshot, if Zealousy blind played a red 2 from newest AND the focus of the initial clue was red 4, then it would be a *Triple Two-Thirds Bluff* instead of a *Triple Bluff*.

### The Bad Touch Double Bluff & The Bad Touch Double Half Bluff (for 3's)

* Following from the *Bad Touch Double Finesse* convention, it is also possible to *Bad Touch Double Bluff* or *Bad Touch Double Half Bluff* in order to get unrelated cards played from *Finesse Position*.

### The Good Touch Bluff

* Care has to be taken so that a *Bluff* does not look like a *Finesse*. For example, if the red 2 is played on the red stack and the blue 2 is played on the blue stack, a number 4 clue that touches a blue 4 can cause a red 3 to blind play. However, this would not typically be done - the unknown 4 would look like red 4, and they would misplay it.
* However, from the perspective of a player who has just seen the above scenario unfold, there must be something else going on. This actually implies that the real red 4 is already clued in someone else's hand. An impending misplay will NOT occur because of *Good Touch Principle*; since it would be bad to duplicate red 4, the player who received the clue will know that the 4 is some other one-away 4.

### The Disease Bluff & The Heal Clue & The Double-Copy Bluff & The Pestilent (Double) Bluff

* In the *Good Touch Bluff* convention, a *Bluff* is given that looks like a *Finesse*. However, what if something that looks like a *Good Touch Bluff* is done, but the "matching" card is not yet clued?
* For example:
  * At the beginning of a 4-player game, Alice goes first.
  * Bob has a red 1 on slot 1 and a blue 2 on slot 2.
  * Alice clues Bob number 2.
  * Bob doesn't see any other 1s on *Finesse Position*. Thus, a 2's clue must be a *Self-Finesse*, so he blind plays red 1.
  * Cathy comes next. From her perspective, Bob will think that his blue 2 is red 2, and will go on to misplay the card.
* From Cathy's perspective, there are 5 possible situations:

#### 1) A *Disease Bluff*

* Say that Cathy sees the red 2 in Donald's hand and she can uniquely clue it. If she does, Donald will go on to immediately play it.
* This would "heal" the problem, as Bob would not think that he has red 2 anymore. Thus, this clue is called a *Heal Clue*.
* The original *Bluff* is called a *Disease Bluff*, since it requires healing.
* The *Disease Bluff* interpretation is the highest priority interpretation!

![Disease Bluff](img/disease_bluff.png)

#### 2) A *Double-Copy Bluff* (with Cathy seeing one copy)

* Say that Cathy sees the red 2 in Donald's hand, but she cannot uniquely clue it due to other blocking cards.
* This cannot be a *Disease Bluff*, since Alice would not put Bob and Cathy in this bad situation if a clean *Heal Clue* was not available.
* Cathy should instead conclude that she has the other copy of red 2 somewhere in her own hand. Bob will not go on to misplay the blue 2; this is called a *Double-Copy Bluff*, since Bob will see both copies of blue 2.

#### 3) A *Double-Copy Bluff* (with Cathy seeing zero copies):

* Say that Cathy does not see the red 2 anywhere and has a completely unclued hand.
* She must have both copies of the red 2 in her hand (but she does not know the order).
* Like the previous situation, this is also a *Double-Copy Bluff*.

#### 4) A *Pestilent (Double) Bluff* (with 1 unclued card):

* Say that Cathy does not see the red 2 anywhere and only has 1 unclued card.
* Unlike the previous situation, Cathy knows that she cannot have both copies of red 2.
* Furthermore, from *High Value Principle*, Cathy can conclude that Alice does not intend for Cathy to do a *Fix Clue*, as that would be inefficient.
* Instead, Cathy can blind play her *Finesse Position* card as red 2. This is similar to a *Disease Bluff*, but instead of wasting a clue to heal the problem, the problem is healed by a blind-play.
* Note that Cathy could be blind-playing red 2, but could also be blind-playing ANY playable card. Whatever card it is, it will still heal the problem, since Bob can see that the blind-play was related to the clue he received.
* This is similar to the *Double Bluff* convention, but is different because the move was not initiated by a card that was 2-away from being playable.

#### 5) A *Pestilent (Double) Bluff* (with 2 unclued cards):

* Say that Cathy does not see the red 2 anywhere and has exactly 2 unclued cards.
* Here, Cathy can assume the *Double-Copy Bluff*, but this situation is different - she can immediately blind-play either card as red 2.
* However, she should always play her *Finesse Position* card, in case it is a *Pestilent Bluff* instead of a *Double-Copy* bluff.

### The Surreptitious Self-Finesse

* *Clandestine Finesses* are when a color or rank clue "matches" the card from a blind play, but the clue receiver must wait for ADDITIONAL matching playable cards to blind play. Another way of saying this is that *Clandestine Finesses* have a *Misplay Component*; if the blind player does not continue to blind play cards, then the clue receiver will go on to misplay the "matching" card.
* A similar situation can also happen when a rank clue "matches" the card from a blind play, but the clue receiver sees UNMATCHING rank cards in the blind player's hand that are currently playable.
* If the clue receiver waits for these non-matching cards to blind play, and they DO blind play, then it means that the original clue had a *Self-Finesse* component to it. This is called a *Surreptitious Self-Finesse* in order to disambiguate it from a more ordinary *Clandestine Finesse*.
* *Surreptitious Self-Finesses* have a *Misplay Component* in almost the exact same way that *Clandestine Finesses* do, but they just involve unmatching rank cards.
* Generally speaking, this means that when a RANK clue initiates a *Finesse*, the clue receiver must always allow for the possibility that subsequent unmatching rank cards in the blind player's hand (that are of a LOWER rank than the clue) can possibly be caught up in the *Finesse*.
* For example, in a 3-player game:
  * Red 1 is played on the stacks.
  * Alice clues number 3 to Cathy, which highlights one 3.
  * Bob blind plays red 2.
  * Cathy knows that red 2 "matches" number 3, so by convention she should probably have red 3.
  * However, Cathy also sees that before Bob blind played the red 2, he had a blue 1 in the slot right after it.
  * Thus, it is possible for Cathy's 3 to actually be blue 3. If it is, Bob will blind play the blue 1 and Cathy will know that she has blue 2 on her *Finesse Position*.
  * So, Cathy discards (instead of potentially playing the red 3 on this turn) to allow for the possibility of a *Surreptitious Self-Finesse*.

### The Continuation Clue (Touching Both Inside and Outside a Layer)

* Sometimes, a person who is blind playing cards into a *Layered Finesse* receives another clue that touches cards BOTH inside the layer and outside the layer.
* By default, the player should assume that it is another normal *Play Clue* or *Save Clue* on a card outside of the layer, and CONTINUE to blind play cards. This follows from *Information Lock Principle*. *Play Clues* given in this manner are called *Continuation Clues*.
* Because *Continuation Clues* are the default interpretation, it can be difficult to give a *Fix Clue*, since a *Fix Clue* must ONLY touch cards inside of the layer.

### The Just-In-Time Fix Clue (To Fix a Layered Finesse with a Lie Component)

* When performing a *Layered Finesse* with a *Lie Component*, it is important to wait until the last moment to give the *Fix Clue*. This is because after recieving the *Fix Clue*, the player will not play any more blind cards.
* Thus, you should first wait for all of the "good" blind cards to play, and THEN give the *Fix Clue*.

### The Hesitation Blind Play

* If you see that someone gets a play clue on a card and they discard instead of playing it, this would normally be a *Scream Discard*. However, sometimes you know from the context of the game that your chop has to be safe.
* In such a situation, the only reason that they would discard is that they are allowing for the possibility of a *Reverse Finesse*, and that you have a playable card on your newest that "matches" the card that they got the play clue on. Thus, you may want to blind play your newest.
* If there is no intermediary players in between the blind player and the player who received the play clue, great care must be taken to not blind play anything that implies a Double Finesse with a "self" component on the player who received the play clue. Thus, the player blind playing must evaluate what would happen for all 6 cards that he could be blind playing.
  * For example, if a 4 number clue causes a hesitation blind play of a red 2 and then the person who received the 4 clue comes immediately afterwards, they will misplay their *Finesse Position* card as a red 3.

### The Pass Bluff

* It is possible for a *Hesitation Blind Play* to occur without anyone intending it to happen. However, if a player intentionally tries to make a *Hesitation Blind Play* occur, it is called a *Pass Bluff*.
* In other words, after a *Finesse* occurs that is directed at you, you will know that your *Finesse Position* card is playable. If the next immediate player also has an unrelated playable card on their *Finesse Position*, you can pretend like the *Finesse* wasn't directed at you. This will cause them to think that the *Finesse* was directed at them, and you will get the unrelated card played for free.
* Unlike a *Layered Finesse*, they should not continue to play to find the finesse card because:
  * You fulfill the real *Finesse* on the next go around.
  * They can see that they were in bluff position.
* *Pass Bluffs* rely on other contextual information to be present in order to work, so the circumstances in which you can do them are narrow.

### The Double/Triple Pass Bluff

* After a player performs a *Pass Bluff*, when it becomes their turn again, if they see an unrelated playable card on the *Second Finesse Position* of the next player, they can perform yet another *Pass Bluff*, implying that the first *Pass Bluff* was not a *Pass Bluff* at all and instead simply a *Layered Finesse* or *Clandestine Finesse*.
* Then, after the unrelated card is played, the player who initiated the *Double Pass Bluff* can go ahead and play into the real *Finesse*.
* Alternatively, if there continue to be playable cards, they can keep *Pass Bluffing*.

### The Hesitation Chop Move

* Remember that as a special exception, *Scream Discards* do NOT apply when a player has a "blind" card to play in their hand AND the blind card can exist in your hand.
* Thus, when this occurs, you will usually want to blind play your *Finesse Position* card, since this sequence of events indicates either an *Ambiguous Finesse* or a *Pass Bluff*.
* When you blind play a card in this situation and it misplays, it means that the unusual discard really was a *Scream Discard* after all, so you should treat it like a normal *Scream Discard* and permanently chop move.
* This is called a *Hesitation Chop Move* for short, since it was triggered by a (failed) *Hesitation Blind Play*.

### The Rebellious Discard

* Part of the *Scream Discard* convention states that after a *Scream Discard*, the next player CANNOT discard. Thus, a player in this situation must completely waste a clue if there is nothing productive to do.
* However, in some situations, the player who has been screamed at sees that if they give a clue, the next player will be left at 0 clues and will be forced to discard a critical card.
* Thus, in this situation, the player should chop move as normal and then discard their new chop, which will functionally act as a second *Scream Discard*. This second *Scream Discard* is called a *Rebellious Discard*, because they are not doing what they are told.

### The Oblivious Finesse

* Sometimes a *Layered Finesse* is given where one of the cards in a layer is currently unplayable. In this situation, a player who is responsible for blind-playing a card may have to instead play *Prompted* cards first so that the layered card does not misplay.
* For the player with the layered card, this will be extremely confusing and look like the blind-playing player is oblivious to the *Finesse* that just occured. The typical response to this is to assume an *Ambiguous Finesse*, and to blind-play the *Finesse Position* card.
* Thus, *Oblivious Finesses* can be quite dangerous and should only be performed in very specific circumstances where you can see that confusion will be minimized.

![Oblivious Finesse](img/oblivious_finesse.png)

### The Trash Push Prompt/Finesse

* If you see that a player *Trash Pushes* an unplayable one-away card, it is a signal to you that you have the connecting card.
* If possible, you should allow for the possibility of a *Reverse Trash Push Prompt/Finesse*. Whether this is the correct thing to do or not is contextual on the pacing of the game and historical game state.
  * Allowing for a *Reverse Trash Push Finesse* also has the advantage of potentially causing *Hesitation Blind Plays*, which can be advantageous to the team.

### The Suboptimal Color Prompt & The Suboptimal Color Finesse

* When saving a critical card, players will generally choose either color or number in order to best satisfy *Good Touch Principle*. Or, in situations where either color or number will satisfy *Good Touch Principle*, they will choose the clue that touches the maximum amount of useful ancillary cards (in order to get a "2 for 1" or "3 for 1" instead of a "1 for 1").
* When a player does NOT do this, it very strange. From *High Value Principle*, it implies it is a *Play Clue* instead of a *Save Clue*, so it is either a *Prompt* or a *Finesse* on the critical card being saved.

### The Suboptimal Trash Bluff Chop Move

* The *Trash Bluff* is often done as a last resort - there was no other way to touch the next person's *Finesse Position* card without violating *Good Touch Principle*.
* However, sometimes there IS a way to "cleanly" touch the next person's *Finesse Position* card, but the positive/negative information on the rest of the hand would be useless. In these types of situations, the *Trash Bluff* is used to stall out the discard of a potentially useful card in the clue receiver's hand.
* And other times, there IS a way to "cleanly" touch the next person's *Finesse Position* card, and it would be a "free" touch on a useful ancillary card. Or, the positive/negative information on the rest of the hand would be very useful - it would "fill in" a mystery card, or make a mystery card playable.
* In this third situation, if a *Trash Bluff* is STILL used, then it follows from *High Value Principle* that it should *Chop Move* the clue receiver in addition to getting the blind play. (It should only chop move one card.)
* *Suboptimal Trash Bluff Chop Moves* are tricky in that they have information asymmetry: the person who blind-plays will NOT know that the card is chop moved, while everyone else will. All players will have to keep this in mind until the chop move has been demonstrated.
* An alternate form of the *Suboptimal Trash Bluff Chop Move* exists where the suboptimality is NOT in the clue receivers hand but in someone else's hand. For example, in a 4-player game:
  * Blue 1 and red 4 are played on the stacks.
  * It is Alice's turn. Bob has blue 2 in his *Finesse Position*. It is possible for Alice to *Finesse* blue 2 by cluing blue 3 in Cathy's hand. This would be a 2-for-1 clue.
  * Instead, Alice clues reds to Donald, which highlights a red 1. This is a *Trash Bluff* because it makes Bob think he has red 5, but he instead blind-plays blue 2. This is a 1-for-1 clue.
  * Donald knows that since Alice did a 1-for-1 instead of a 2-for-1, he should chop move.
  * Cathy does not know that Donald will chop move until he demonstrates it or until the blue 3 in her hand is directly clued.

### The Dump Truck

* When someone blind plays their chop, there is usually an emergency happening and it was either a *Scream Blind-Play* or a *Stop Blind Play*.
* However, if someone blind plays their chop and there was no emergency, it must be something else.
* This means that one player has a fully playable hand from left to right. Like a dump truck, they are expected to unload everything onto the table.
* Most times, all cards in the hand will be unclued. But if not, the player is still expected to play everything from left to right in order.
* In the middle of the game, it is relatively safe to blind play your chop card, since it is known to not be a critical/playable card.
* In the beginning of the game, it may not be safe to blind play your chop card. In this situation, you may see that multiple players have the opportunity to initiate the *Dump Truck*. Normally, it is best to let the player immediately before the blind-player do it. If they have an unsafe chop, then the 2nd player before the blind-player should do it, and so forth.

### The Dupe Bluff

* This is where you perform a *Bluff* such that the card that is blind played is already touched in someone else's hand AND the player who has the other copy has full knowledge of the card.
* You wouldn't normally do this since it is only a 1-for-1 instead of a 2-for-1. However, it can be useful if you want to touch a card that you wouldn't otherwise be able to, like a one-away card. Alternatively, you may strongly want to give ancillary information to some other card.

### The Negative Blind Play

* Given enough negative clues on a card (and potentially some ancillary information based on the history of the game), it is possible to narrow down the identity of an unclued card in your hand to possibilities that only include playable cards that are not already touched in someone else's hand.
* In this situation, you are expected to blind play the card.

### The Speed-up Clue

* The *Layered Finesse* convention (and its derivatives) are very efficient (in terms of "X for 1"). However, sometimes it can be very slow (low tempo), as players will have to allow for all possible *Reverse Finesses* before playing anything. This is generally not a problem in 3-player games, but tempo is important in 5-player games.
* Normally, when the *Finesse Target* (the card that is to be blind-played) is clued directly, it is a mistake due to someone not paying close enough attention. We refer to this as *Stomping on a Finesse*.
* However, if high tempo is needed, a player can consider intentionally *Stomping* on a *Layered Finesse* in order to "speed up" the play of a specific card that leads into other players hands.
* One complicating factor of the *Speed-up Clue* is how to differentiate it from a more-ordinary *Fix Clue*. In other words, after the clued card is played, on their next turn, should the player go back and blind-play the other cards? If it was a *Speed-up Clue*, they should. If it was a *Fix Clue*, they should not.
* The key lies in the context of the clue:
  * Would another player have tried to blind play something before the potential *Fix Clue* was given? If yes, then it is not a *Fix Clue*, and it is a *Speed-up Clue*.
  * Was it possible to take an equivalent line where a *Fix Clue* would not be needed? (In terms of the same number of clues, and no risk of discarding critical/playable cards.) If yes, it is not a *Speed-up Clue*.

### The Layered Jump

* If a player who is blind-playing into a *Layered Finesse* skips over a card, they are performing a *Layered Jump*. This player has deduced that the card they are skipping over is duplicated (or otherwise bad).
* The card skipped over in this way will be the next thing discarded, as it is now considered known trash.
* If a *Layered Jump* skips over a card that cannot be in your own hand, then you can determine that it must be a mistake. In this situation, the skipped-over card must be clued directly to re-signify that it is good.

### The Misplay Trash Push

* When a card is clued and the next person misplays that card, it is usually the *Misplay Chop Move* - they had no other options and had to protect an important card on chop.
* However, when a card ON CHOP is clued and the next person misplays that card, it cannot be the *Misplay Chop Move* - it must be something else.
* Normally, when trash is clued on chop, it is a *Trash Push*. So they should go on to blind play the card that was touching the trash on their next turn.

### The Reverse Misplay Chop Move

* Sometimes, a *Misplay Chop Move* will not immediately misplay because of circumstances similar to *Focus Inversion*, meaning that there is:
  * negative clues present on the card
  * historical / contextual information about the card (derived from moves that teammates performed earlier on in the game)
* In such a scenario, the clue will look like a *Reverse Finesse* and then next person will misplay their *Finesse Position* card.
* After the misplay, the person who received the clue is to treat it like a normal *Misplay Chop Move*, and chop move all the cards to the right of the clued card.

<br />

## Non-Formalized Proposals

These are moves that are proposed by certain members of the group. However, they have not yet reached a consensus that they are good enough to play with by default.

n/a

<br />

## Convention Attribution

| Convention Name | Inventor
| --- | ---
| 2 Saves | Hyphen-ated & Duneaught
| Chop Focus | Zamiel & Hyphen-ated
| The Layered Finesse | Antizoubilamaka
| The Clandestine Finesse | Antizoubilamaka
| The Patch Finesse | Zamiel & Libster
| The 3 Bluff | Hyphen-ated
| The Double Bluff | Hyphen-ated
| The Double Half Bluff | Hyphen-ated
| The Triple Bluff | Zamiel
| The Triple Two-Thirds Bluff | Zamiel
| Playing 1s from Right to Left | Duneaught
| The 9 First Principles | Duneaught
| The Gentleman's Discard | Duneaught
| The Layered Gentleman's Discard | Duneaught
| The Tempo Clue Chop Move | Zamiel
| Discard Elimination & The Elimination Blind Play | Aridolomo (with revisions from Hyphen-ated & Duneaught)
| Immediate Double Clue | Duneaught
| The Elimination Finesse | Zamiel & Ahming
| The Elimination Blind Play Riding Deduction | Duneaught
| Free Choice Convention | Hyphen-ated
| The Trash Push | Duneaught
| The Trash Bluff | Duneaught
| The Trash Finesse | Duneaught
| The Double Trash Finesse | Duneaught
| The Trash Push Finesse | Duneaught
| The Hesitation Blind Play | Zamiel
| The Priority Prompt & The Priority Finesse | Libster
| The Dupe Bluff | Duneaught
| The Certain Finesse | Zamiel
| The Negative Prompt | Zamiel & Libster
| Weak Prompts | Hyphen-ated
| Crazy 3 Saves & Crazy 4 Saves | Libster
| The Scream Discard Chop Move | 910dan & Zamiel
| The Early Fix Clue Chop Move | Zamiel
| The Critical 4 Bluff | Libster
| The Chop Transfer | Duneaught
| The Whisper Discard Chop Move | Zamiel
| The Good Touch Bluff | Postmans
| The Negative Blind Play | Ahming
| The Elimination Bluff | Zamiel
| The Elimination Layered Finesse | Zamiel
| The Rebellious Discard | Zamiel
| Focus Inversion | Zamiel
| Modified Black 3 & Black 4 Saves | Florrat
| Modified Early Game | Libster & Florrat
| The Double Tempo Clue | Hyphen-ated
| Hard Bluffs | Florrat
| White Compromise | Postmans
| Acid Trip Conventions | Zamiel & Florrat
| The Double/Triple Pass Bluff | Zamiel
| The Out-of-Order Finesse | Zamiel
| The Speed-up Clue | Libster
| General Principles | Zamiel & Florrat
| The Misplay Trash Push | Zamiel
| The Disease Bluff & The Heal Clue | Zamiel
| The Double-Copy Bluff | Zamiel
| The Pestilent (Double) Bluff | Zamiel
| The Distribution Clue | Libster
| The Elimination Blind Play Riding Deduction Bluff | Duneaught
| Self-Elimination Finesse Priority | 910dan
| Multiple-card Trash Bluff | Zamiel & Antizoubilamaka
| Play Elimination | Zamiel
| Double Discard Elimination | Zamiel
| The No-Information Double Finesse | Zamiel
| The Layered Jump | Libster
| The Oblivious Finesse | Sankala
| The Free Choice Bluff | Zamiel
| The Suboptimal Color Prompt & The Suboptimal Color Finesse | Zamiel
| The Suboptimal Color Bluff | Zamiel
| The Higher Order Finesse | Libster
| The Continuation Clue | Libster
| The Just-In-Time Fix Clue | Zamiel
| The Occupied Play Clue & The Occupied Finesse | Zamiel
| The Higher Rank Prompt & The Higher Rank Finesse | Libster & Zamiel
| The Higher Rank Bluff & The Higher Rank Layered Finesse | Zamiel
| The Long-Range Scream Discard | Florrat
| The Bad Touch Double Finesse | Sankala
| The Bad Touch Double Bluff & The Bad Touch Double Half Bluff | Sankala
| The Dump Truck | Ahming
| The Fuel Clue | Ahming
| The Lower Rank Finesse & The Lower Rank Bluff | Libster
| The Right-to-Left Finesse & The Right-to-Left Bluff | Libster
| The Setup Finesse | Zamiel, RaKXeR, & Libster
| The Stop Discard | Zamiel
| Ejection | Razvogor & Zamiel & Sankala
| 1's Out-of-Order Chop Move | Zamiel
| Wild & Crazy Black 4 Bluffs | Zamiel & Libster
| Duplication Responsibility | Zamiel
| Certain Discard Duplication Promise | Zamiel & Libster
| Suboptimal Trash Bluff Chop Move | Libster
| Out-of-Order Trash Discard Chop Move | Zamiel
| Surreptitious Self-Finesse | Sankala
| Play/discard order of like cards | Libster
