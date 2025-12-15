---
layout: post
title: "Mystery File 06: The Mysterious Museum"
date: 2024-02-07 17:42:00 -0400
categories: RAMI
tags: mtg MTGMKM RAMI
---

## [back to index post]({% post_url 2024-01-08-MKMARG-RAMI-Mystery-Files %})

> Crime Scene: The evidence you need to solve this puzzle can be found on Murders at Karlov Manor Art Cards.
> 
> Solving a mystery is like appreciating fine art.
> 
> After you have reconstructed the map of the Mysterious Museum, transfer the 10 letters you found into the grid on this page.
> 
> Then fill the rest of the grid with those same letters so that no letter is repeated within any row, column, or 7-square section.

[Ravnica Detective Agency](https://magic.wizards.com/en/products/murders-at-karlov-manor/mystery-files)

---

[u/ARMSF discovered](https://reddit.com/r/magicTCG/comments/1abznq9/karlov_maanor_art_cards_jigsaw/) on 01-26 that the art cards for this set have a 'jigsaw' pattern on the edges and some of them have a circled letter in the top left corner.

u/messedupayayron's [made a spreadsheet](https://docs.google.com/spreadsheets/d/1n-rlNOrgWjjK61d0tA9oQtmEynZlgtBh4oRcxZaT2Kc/edit#gid=0) to collect art card references and piece the thing together

We managed to piece together the entire jigsaw on 01-29, though it doesn't inherently provide a meaningful message. Big shoutout to everyone who worked on collecting screenshots and assembling the jigsaw - u/Gear_NO-7, Corgi, Newt, and everyone who pitched in to help.

Of course, now we know that the jigsaw forms our seed entries for a sudoku puzzle! I've provided the seeded grid below for easier transcription than from the spreadsheet. 

<details>
<summary>the mysterious musuem - seeded grid</summary>
<p>
<img src="/assets/images/RAMI/06-grid-seeded.png" alt="seeded sudoku grid">
</p></details>

It's not too bad to solve a hand, though you have to make a few guesses if you solve it "normally". There *are* some tricks that can be applied

<details>
<summary>the mysterious musuem - hint</summary>
<p>
We can use a tad of meta-knowledge here. We know that prior Mystery File solutions have all been cards from a Ravnica set, and here we have the sudoku puzzle giving us a 3-char word and a 4-char word. It's not unreasonable to guess that that 3-char word is a set code here, and that the 4-char word somehow forms a number.
</p>

<p>
Given that assumption, the only Ravnica sets that can work with our alphabet are RTR and GTC (RVR technically works, but being a reprint set I'm doubtful, especially since all the other solutions were original printings). Since they share the 2nd character, that actually gives us an extra starting cell, and eliminates cell 1 to R/G and cell 3 to R/C.
</p>

<p>
Given this information, and a little trick called <a href="https://www.sudokuwiki.org/Law_of_Leftovers">the Law of Leftovers</a> (huge shoutout to cogito_ergo_sum on the official Magic discord for sharing this one, it makes it possible to do this without any guessing at all)
</p>
</details>

<p>
Here's the full solution, and I've provided a step-by-step within as well for those interested.
</p>

<details>
<summary>the mysterious musuem - solution</summary>
<p>

<details>
<summary>step-by-step solve</summary>
<p>

We first fill in our "hint" assumptions - cell 1 is R/G, cell 2 is T, and cell 3 is R/C
</p>

<p>
Then we can identify via basic deduction that r1c2 must be an A - neither of the other two sections in this row can contain an A, and column 1 also cannot contain an A. So our grid (and some penciling) now looks like
</p>

<img src="/assets/images/RAMI/06-mysterious-musuem_pencils-1.png" alt="penciled grid 1">

<p>
From here, we apply that <a href="https://www.sudokuwiki.org/Law_of_Leftovers">the Law of Leftovers</a>. Since the red "outie" section doesn't have a possible R in any of its cells, that implies that none of the green "innie" sections can have R's either, which means r3c5 must be a T.
</p>

<img src="/assets/images/RAMI/06-mysterious-musuem_law-of-leftovers.png" alt="applying the law of leftovers">

<p>
Since r3c5 is a T, it follows that r3c2 is a G. We can then apply the Law of Leftovers again on the first two columns so that r3c2 is our "innie" and r6c3 is our "outie", which means that they must have the same letter and thus r6c3 must be G as well
</p>

<img src="/assets/images/RAMI/06-mysterious-musuem_pencils-2.png" alt="penciled grid 2">

<p>
We can now look at the top middle section. Notice that only one cell in this section can be a V - none of the cells in column 4 can, so r1c3 must be a V.
</p>

<p>
Similarly, we can now look at row 1. We know from our meta-knowledge that r1c1 can't be I, nor can r1c6/r1c7 because that top right section already has I, so r1c4 must be I. Then that gives us r2c4 as R to fill out this section.
</p>

<p>
Since r2c5 was down to V/R and now it can no longer be R, it must be V. By Law of Leftovers splitting the right two columns, r5c6 is also V. r2c5 also means that r6c5 must be an I, which means r7c3 is C, which means r7c4 is A, which means r5c5 is R, completing the bottom middle section. Also, we now only have one remaining cell in column 5, which musst be A.
</p>

<img src="/assets/images/RAMI/06-mysterious-musuem_pencils-3.png" alt="penciled grid 3">

<p>
From here, the rest of the cells just start falling into place. If you're still struggling to follow, pencil out the possible values for cells in the corners and slowly eliminate options once by one.
</p>

<p>
The only possible value for r5c3 is I, which means r4c3 is R. Similarly, the only value for r6c6 is C, then r6c2 is V, then r3c6 is R, then r3c1 is C, then r2c2 is I, then r2c1 is G, which means r1c1 is R (given our meta-restriction) and also r2c7 is C to fill out row 2's cells. The last two missing values for the top left section are V and T, and since V can't be in column 2 it has to be in r4c1, meaning r4c2 is T
</p>

<img src="/assets/images/RAMI/06-mysterious-musuem_pencils-4.png" alt="penciled grid 4">

<p>
The rest follows as before, with simple deductions.
</p>

<p>
r4c7 must be G, r4c4 must be C, so r4c6 must be I to fill out the column. Since r4c7 is G, r1c7 has to be T, and r1c6 is G to fill out the top right section, and r7c6 is T to fill that column.
</p>

<p>
r5c1 has to be T, r7c1 fills out the column with I, and r5c2 has to be C to complete the section. Completing column 4 gives us G for r5c4, and then we can finish row 5 with A in r5c7, and finally we can slot V in the last cell r7r7
</p>
</details>

<p>
The solved grid is:
</p>

<img src="https://staging.cohostcdn.org/attachment/5da6a71b-672a-4303-9fbd-741b332e1c14/mysterious-musuem-grid_solved.png" alt="solved sudoku grid">

<p>
Which gives us RTR CCIV, or RTR 204 in roman numerals, which is Treasured Find. The corresponding MKM card is Extract a Confession - the first one we've preemptively guessed!
</p>

<div style="align-items: stretch; display: flex; flex-wrap: wrap; justify-content: space-evenly; text-align: center;"><figure style="display: flex; flex-flow: column; margin: 2px; position: relative; text-decoration: none; width: calc(50% - 4px);"><a href="https://cards.scryfall.io/large/front/a/2/a2c0e00b-2290-493f-a3fc-3b9bff2830cc.jpg?1562790864"><img style="height: 100%; margin: 0px; object-fit: cover; width: 100%;" src="https://cards.scryfall.io/large/front/a/2/a2c0e00b-2290-493f-a3fc-3b9bff2830cc.jpg?1562790864" alt=""></a></figure><figure style="display: flex; flex-flow: column; margin: 2px; position: relative; text-decoration: none; width: calc(50% - 4px);"><a href="https://cards.scryfall.io/large/front/2/5/256c8b6e-4031-458b-8eb9-bbfe58405a0c.jpg?1706241687"><img style="height: 100%; margin: 0px; object-fit: cover; width: 100%;" src="https://cards.scryfall.io/large/front/2/5/256c8b6e-4031-458b-8eb9-bbfe58405a0c.jpg?1706241687" alt=""></a></figure></div><div style="text-align: right; font-size: min(1.87vw, 70%); opacity: 0.7; line-height: 100%;"> made with @nex3's <a href="https://nex3.github.io/cohost-image-grid/">grid generator</a></div>
</p></details>

## [back to index post]({% post_url 2024-01-08-MKMARG-RAMI-Mystery-Files %})