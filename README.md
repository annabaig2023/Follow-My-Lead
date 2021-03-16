# Pre-work - *Memory Game*

**Follow My Lead!** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Anna Baig**

Time spent: **4** hours spent in total

Link to project: (https://descriptive-scythe-snowstorm.glitch.me
https://glitch.com/edit/#!/descriptive-scythe-snowstorm)

## Required Functionality

The following **required** functionality is complete:
* Y = Yes
* [Y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Y] Game buttons each light up and play a sound when clicked. 
* [Y] Computer plays back sequence of clues including sound and visual cue for each button
* [Y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Y] User wins the game after guessing a complete pattern
* [Y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Y] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Y] Buttons use a pitch (frequency) other than the ones in the tutorial
* [Y] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![https://cdn.glitch.com/6394c64d-938d-428a-a4f8-11b29e3b4f62%2FFollowMyLead-Baig%20GIF.gif?v=1615893609962]
[LICEcap used which does not support sound]


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.w3schools.com/tags/att_global_hidden.asp]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[In the Handling guesses- game logic bit, I faced challenges with the conditional logic in the guess function. Particularly, having if conditions inside an if condition was a bit challenging for me. I worked a way around this by starting from the outermost if statements, and then making my way in. I also wrote the code in MS word and color coded it to remember how I was going deeper into the if statement or if I was just going from one if statement to another. For instance, for the IF GUESS IS CORRECT then ….. ELSE IF GUESS IS NOT CORRECT then ….. I first coded these two if else conditions and made them the outermost layer of my conditions and color coded them red to remember them as the outermost layer. Then in the inner layer, was if the user made progress or not. Inside this was if the progress was equal to the total steps required to win the game, in which case we just called winGame(). Otherwise, one pattern was correct and so we just added to the progress and continued with the clue sequence. Remembering information this way made more sense when coding. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[How do you develop a web page which has more than one pages? For instance, if I wanted to have a web page with more than 1 games like Follow My Lead, how would I make that happen?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[Maybe add a little mascot for the game like Github uses, and make the mascot talk and interact with the user in order to explain instructions. This would particularly be attractive for younger users who cannot read but can understand what the mascot is saying. It would also be nice to maybe have the option of learning how to play nursery rhymes by choosing from a list of rhymes and then following the computer's lead in order to learn that rhyme.]



## License

    Copyright [Anna Baig]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
