# PHP foreach Loop and Array Modification Bug

This repository demonstrates an uncommon bug in PHP related to modifying arrays while iterating through them using a `foreach` loop.  The example shows how `unset()` within the loop doesn't always produce the intended result, potentially leading to unexpected behavior in your code.

The `bug.php` file contains the problematic code, showcasing the unexpected array output. The solution, provided in `bugSolution.php`, offers a safer way to modify arrays during iteration, ensuring intended outcomes.