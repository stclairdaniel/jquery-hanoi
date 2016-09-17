# Towers of Hanoi

[Live][link]

[link]: https://stclairdaniel.github.io/jquery-hanoi/

Towers of Hanoi is written using JavaScript ES5,jQuery, CSS, and HTMl. It has a sleek, minimalist design.

![game](http://i.imgur.com/eYK62Yd.png)

## How To Play

You may only move discs to an empty tower or to a tower with a bigger disc than the one you are moving. Click a tower to select its topmost disc, and click another valid tower to move the disc. Win by moving the entire initial disc stack to another tower.

## Technical details

Upon click, a simple move validator runs and alerts if the move is invalid, otherwise performs it. A render function looks at the array of towers and assigns HTML classes that set disc display width based on the disc number. Another function, clickTower, sets a jQuery click event that stores a clicked state to display a blue base for the first click on hover and a red base once a tower has been clicked once.
