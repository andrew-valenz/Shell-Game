## Wire frame for planning

![Wire frame for planning](./assets/ShellGame%20WF.png)

We will need the following:

<h1> tag
<section></section>
<div img src=> for shells
<div img src=> for balls
<button> for guess
<section>for wins, losses, and totals

## States

wins total losses (derived state)

## Events

-   button clicks (user guesses)
    -   increment total
    -   generate a random location for the ball (number between 1 and 3)
    -   take that location and reveal class to img
        -   if lines up with users guess increment the wins
    -   remove the reveal on all shells
