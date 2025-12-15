---
layout: post
title: "Mystery File 08: The Weird Window"
date: 2024-02-07 17:55:00 -0400
categories: RAMI
tags: mtg MTGMKM RAMI
---

## [back to index post]({% post_url 2024-01-08-MKMARG-RAMI-Mystery-Files %})

> Crime Scene: The evidence you need to solve this puzzle can be found in Murders at Karlov Manor Play Booster Boxes.
> 
> In this city, not even the mysteries made out of glass are clear.
> 
> Find the window art on the Play Booster Box insert and complete the loop as instructed. Then apply that loop to the grid on this page.
> 
> Ignore all the window panes that are outside the loop. Identify each symbol, number, and letter that appears inside the loop twice, then take just one copy of each of those to identify a card.
> 
> - The mana symbols form the mana cost.
> 
> - One of the numbers is the power and the other number is the toughness.
> 
> - One of the letters is the first letter of the artist’s first name, and the other letter is the first letter of the artist’s last name.

[Ravnica Detective Agency](https://magic.wizards.com/en/products/murders-at-karlov-manor/mystery-files)

---

This puzzle was discovered [in a box opening video](https://www.youtube.com/watch?v=_ra6dayG-30) and originally solved on 01-26, prior to the Mystery File release. The insert for the play booster box has the following puzzle on it. 

![play booster box insert - the weird window](/assets/images/RAMI/08-insert.png)

RDA instructs us to solve this puzzle, then apply it to a provided grid, and gives us instructions to convert it into a 'riddle' for a card name. It's like Slitherlink!

![RDA weird window grid](/assets/images/RAMI/08-weird-window-RDA-annotation.png)

<details>
<summary>the weird window - solution</summary>
<p>
This one's pretty fun. Here's my "annotated" solve, with cracks numbered, 'guaranteed' edges marked in green, 'impossible' edges in red, and magenta being my guess as I tried to close the loop. Immediately, the set of 3-crack squares on the bottom left only have one possible solution, since you can never travel away from a triangle 2-crack unless it's by using one of its edges. Thus we lock the 5 edges that comprise of those 3-cracks. We can apply similar logic to the two 3-crack squares on top, given the 2-crack triangle kitty corner. By then eliminating edges (we can't travel on an edge that arrives at a green corner) we can extend this logic until we arrive here.
</p>

<img src="/assets/images/RAMI/08-solve-annotated.png" alt="weird window annotated solve">

<p>Applying it to the provided grid, our solve looks like this:</p>

<img src="/assets/images/RAMI/08-solve-decoded.png" alt="weird window solution">

<p>This gives us a mana cost of {3}{U}, a p/t of either 2/3 or 3/2, and artist initials of either W. N. or N. W. Here, Scryfall is our best friend</p>

<pre><code>atag:ravnica mana=3U ((pow=2 tou=3) or (pow=3 tou=2)) (a:w a:n)</code></pre>

<p>and voila, <b>Keymaster Rogue</b>! Our corresponding MKM card is <b>The Pride of Hull Clade</b>, who has the same door-ring/knocker</p>

<div style="align-items: stretch; display: flex; flex-wrap: wrap; justify-content: space-evenly; text-align: center;"><figure style="display: flex; flex-flow: column; margin: 2px; position: relative; text-decoration: none; width: calc(50% - 4px);"><a href="https://cards.scryfall.io/large/front/9/7/970ee9a3-a862-46a7-9aa5-7b6fc4ffa1ab.jpg?1561837825"><img style="height: 100%; margin: 0px; object-fit: cover; width: 100%;" src="https://cards.scryfall.io/large/front/9/7/970ee9a3-a862-46a7-9aa5-7b6fc4ffa1ab.jpg?1561837825" alt=""></a></figure><figure style="display: flex; flex-flow: column; margin: 2px; position: relative; text-decoration: none; width: calc(50% - 4px);"><a href="https://cards.scryfall.io/large/front/e/d/edb40ab9-e552-4eb5-9c35-09094136dd4f.jpg?1706242068"><img style="height: 100%; margin: 0px; object-fit: cover; width: 100%;" src="https://cards.scryfall.io/large/front/e/d/edb40ab9-e552-4eb5-9c35-09094136dd4f.jpg?1706242068" alt=""></a></figure></div><div style="text-align: right; font-size: min(1.87vw, 70%); opacity: 0.7; line-height: 100%;"> made with @nex3's <a href="https://nex3.github.io/cohost-image-grid/">grid generator</a></div>

</details>

## [back to index post]({% post_url 2024-01-08-MKMARG-RAMI-Mystery-Files %})