# Project 1 - *Wordle Simulator*

**Wordle Simulator** is an app that simulates a game of wordle. A player has 6 trials to guess a 5-letter word. For each guess, if a letter is not in the word, it gets colored black. If the letter is in the word but at the wrong position, it gets colored yellow. Finally, if the letter is in the word and at the right position, it gets colored green. The player wins the round if they manage to guess the right word before their trials run out.  

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a keyboard on the screen
- [x] When tapping on the keyboard, a letter is shown or deleted (letter selected)
- [x] User can play a basic version of Wordle, with different goal words each time

The following **optional** features are implemented:

- [ ] Improve and customize the user interface by adding a launchscreen and app icon
- [ ] Run the app on a device rather than in the simulator

The following **additional** features are implemented:

- [ ] Create a more robust word list to generate from

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/b8a57f77a7da4a99b355b96c46bb8b11">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/b8a57f77a7da4a99b355b96c46bb8b11-with-play.gif">
    </a>
  </div>


## Notes

The major challenge was reading through the files and understanding how the code worked. Once that was done, I was able to interact with the methods given to me pretty well. 

# Project 2 - *Alienated Wordle*

Submitted by: **Desire Asinya**

**Alienated Wordle** is a Wordle simulation app that works just like the original wordle, which means that a player has 6 tries to guess a 5 letter word based on hints provided by the game. However, the user now has an option to tweak the number of guesses, number of letters, the format of words (countries, animals, or normal), and an alien feature that changes the goal word at every guess. 

Time spent: **1.5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] User can change the number of letters per row (the length of the goal word)
- [x] User can change the numbers of rows on the board (how many guesses allowed)
- [x] User can select a new themed set to pull the goal word from
- [x] User can select "alien wordle", causing the goal word to change after each guess


The following **optional** features are implemented:

- [ ] App displays a reset button on the top left to reset the game (but make no changes to the settings)

The following **additional** features are implemented:

- [ ] Create a more robust word list to generate from

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/40a4db5e4860449eb57019050e0465a5">
    </a>
    <a href="https://www.loom.com/share/40a4db5e4860449eb57019050e0465a5">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/40a4db5e4860449eb57019050e0465a5-with-play.gif">
    </a>
  </div>

## Notes

The third feature where I had to implement the new themed set feature was challenging because the word generator class had a unique type, and unwrapping the value of that type was relatively new to me. 

## License

    Copyright [2023] [Desire Asinya]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


