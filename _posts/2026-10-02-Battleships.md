---
layout: post
title: Battleships
description: First Experience with C++
image: assets/images/Screenshot_69.png
---

<div class="media-row" markdown="1">

<div class="media">
  <img src="{{ '/assets/images/Screenshot_1.png' | relative_url }}" alt="Describe the picture">
</div>

<div class="text" markdown="1">

My first experience with C++ is my simple battleships game in console which takes a twist on the battleships genre by adding extra fleets of ships to fight, new weapons gained by killing ships and differing difficulties of AI. This project also allowed me to dip my toes in engine development by creating an input class that reflects the old unity input system with GET_KEY_PRESSED definitions and a rendering class that can easily add new fleets and boards.

</div>

</div>

<div class="media-row" markdown="1">

<div class="text" markdown="1">

I was able to do this by utilising pointers and abusing the pass by value nature of C++ to optimise my system, I also used more algorithm work to create different AI's through an abstract class that allow AI's to act differently depending on the inputs with easier AI shooting completely randomly until a hit in which it moves around and follows the length of the ship with harder AI creating a score based system where each position on the board has a score depending on the current board layout.

</div>

<div class="media">
  <img src="{{ '/assets/images/Screenshot_2.png' | relative_url }}" alt="Describe the picture">
</div>


</div>

<div class="media-row" markdown="1">

<div class="media">
  <img src="{{ '/assets/images/Screenshot_3.png' | relative_url }}" alt="Describe the picture">
</div>

<div class="text" markdown="1">

This project definitely got me into C++ and began the stepping stones for future projects where if I could do this project again I would certainly redo how I rendered the ASCII pictures and acted on the ships with ship classes to give more feedback for when ships are destroyed.

<ul class="actions">
  <li><a href="https://github.com/HunterReaper13/Battleship-Skool-Project" class="button" target="_blank" rel="noopener noreferrer">See The Source Code!</a></li>
</ul>
<ul class="actions">
  <li><a href="https://hunterthereaper.itch.io/battleships" class="button" target="_blank" rel="noopener noreferrer">Play The Demo!</a></li>
</ul>

</div>
