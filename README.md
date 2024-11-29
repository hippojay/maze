# A Simple Maze - Demonstrating cognitive load

This is a simple javascript maze game, intended to show why we need to focus on Extreneous cognitive load, not just Intrinsic.

## Aim

Simply navigate you player (green) from the start to the end (red dot), using the arrow keys.
The game will keep a track of of number of steps, the number of failed steps, accuracy and time spent.

### Options

Supply the following options to the URL to change behaviour:

* normal - Standard arrow key mapping of up, down, left, right.  Will not display key mappings on screen
* extreme - constant randomisation of directions.  Will display the key mappings on screen
* controls - will display key mappings on screen for default mode.

Example: https://hippojay.github.io/maze?normal

## Randomising

When in default mode, the game will randomise the controls on every go - so that up, down, left and right are no longer mapped to their natural directions.  This makes the game harder, as you learn the correct mappings.  
When in extreme mode, the game will randomise the controls on every step - so what was once up before, is now mjapped to a different direction.

## Cognitive load

I see people focus on making tasks simplier by breaking them down to reduce the cognitive load (intrinsic) whilst not realising thatsometimes the process is not clear or straightforward.  This maze game shows that even simple tasks (navigating a maze/labrinth) can have a high cognitive load.

### Default mode
This is to show that we can take existing knowledge, and apply it to learn something new.  This is a normal learning journey.  The extraneous load is the non-expected behaviour of the arrow keys.  It doesn't add to the task, yet it is something that we can overcome through learning.

### Extreme mode
This is to show high extreneous load. As the direction mapping always changes, it is impossible to map existing knowledge to new knowledge.  Even with the control mapping displayed for teh user, it takes a lot of work to check, navigate and move the player repeatedly.  This constant re-working is the high extraneous load.

## Christmas Theme
If the Chistmas Theme in activated the game is the same, but the player couter is a Santa hat, and the end is golden square.

## License
MIT License

Copyright (c) 2024 David Hawes-Johnson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
