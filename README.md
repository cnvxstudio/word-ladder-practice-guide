# Word Ladder Practice Guide

A short reference and printable practice sheet for four-letter word ladders. Learn the rules, solve three small puzzles, then check each changed letter against the answer key. No app or account is needed to use this guide.

## Start here

A word ladder connects a starting word to a target word. Each move changes **exactly one letter in its existing position**. Keep the word length the same and use an accepted word at every step.

For example:

**COLD → CORD → CARD → WARD → WARM**

| Move | What changes |
| --- | --- |
| COLD → CORD | Third letter: L → R |
| CORD → CARD | Second letter: O → A |
| CARD → WARD | First letter: C → W |
| WARD → WARM | Last letter: D → M |

There are **five words and four moves**. Count the arrows, not the words. COLD and WARM differ in all four positions, so at least four moves are needed. This four-move route reaches that lower bound.

**COLD → WARM** is not one legal move: four letters change. Rearranging letters also does not count as changing one position.

## A method you can use on paper

1. Write the start and target at opposite ends of a line.
2. Look for words in the allowed bank that differ from your current word in one position.
3. Try one of them and underline the changed letter.
4. If you get stuck, return to a branching point and try a different next word.
5. Before calling the ladder finished, check every adjacent pair and count the arrows.

Getting another target letter into place can help, but it is not a rule. Some puzzles need a detour. Avoid loops such as COLD → CORD → COLD: they spend moves without taking you anywhere new.

The dictionary matters. For the exercises below, **only the supplied word bank is allowed**. A word from another dictionary is not automatically legal in a particular game. These small banks were assembled for this teaching sheet; they are not the official word list or schedule of any game.

## Practice sheet

Copy or print this section. Find a valid route first; then see whether you can shorten it. The blanks below are writing space, not a required move count. Do not read the answer key until you want help.

### 1. From COLD to WARM

Allowed bank: **CARD, COLD, CORD, WARD, WARM**

Your route: COLD → __________ → __________ → __________ → WARM

Check: each arrow changes one position. My move count: __________

<details>
<summary>Small hint</summary>

Try changing the third letter of COLD first.

</details>

### 2. From LEAD to GOLD

Allowed bank: **GOAD, GOLD, LEAD, LOAD**

Your route: LEAD → __________ → __________ → GOLD

Check: no letters were added, deleted, or rearranged. My move count: __________

<details>
<summary>Small hint</summary>

The first step changes E to O.

</details>

### 3. From HEAD to TAIL

Allowed bank: **HEAD, HEAL, TAIL, TALL, TEAL, TELL**

Your route: HEAD → __________ → __________ → __________ → __________ → TAIL

Check: the final word is exactly TAIL. My move count: __________

<details>
<summary>Small hint</summary>

Start with HEAL. Changing a letter does not have to make the word immediately look like the target.

</details>

## Answer key

<details>
<summary>Open the routes and letter checks</summary>

| Exercise | Route | Moves | Changed positions, in order |
| --- | --- | --- | --- |
| 1 | COLD → CORD → CARD → WARD → WARM | 4 | 3, 2, 1, 4 |
| 2 | LEAD → LOAD → GOAD → GOLD | 3 | 2, 1, 3 |
| 3 | HEAD → HEAL → TEAL → TELL → TALL → TAIL | 5 | 4, 1, 3, 2, 3 |

Each route uses only its exercise's word bank. Each is shortest **within that bank**. This does not claim that the same route is shortest in every game's larger dictionary.

If your answer differs, check it rather than judging it by appearance. Every word must belong to the bank, and exactly one position must change at each arrow. A valid route can still take more moves than another valid route.

</details>

## When to use a hint

Try the smallest useful hint first. A move count tells you how much room you have. A first move gives you a foothold. A complete path lets you check why each step works. You can stop after any hint and return to solving.

For a browser example, we maintain [Poople Answers](https://poopleanswers.com/), a free independent companion for four-letter ladders ending at POOP. It searches its current word list and offers daily hints in stages: move count, first move, and full route. It needs no signup or download. The exercises above are standalone practice, not today's Poople answers, and Poople Answers is not affiliated with the original Poople game.

Prepared by cnvx / Ethan Lee with AI assistance. The exercise routes were checked for word-bank membership, one-letter changes, move counts, and shortest length within the supplied banks. This repository contains educational text only; it does not contain the product's source code or an official game dataset.
