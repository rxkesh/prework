# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Rakesh Pillai**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/eager-hissing-flyaway

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

![](https://i.imgur.com/CfHuW6w.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The main challenge I encountered was handling the guessing and programming the logic. In general, it just took me more time than expected to think the whole process through and write the code out. I specifically forgot about the fact that arrays start from 0 and I completely forgot to subtract the length of pattern by 1. I overcame this specific error by looking at the error and tracing my code to see where I went wrong. 
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
One question I have regarding web development is how does the browser interpret the JavaScript startTone, playTone, and stopTone functions. I'm currently taking a base level ECE course and we are learning about op-amps and I am learning about concepts such as gain and frequency. I'm excited to learn more about how browsers (and computers in general) interpret languages such as JavaScript. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I unfortunately didn't get much time to work on this project due to ongoing projects and tests, however, if I had a few more hours, I would spice up the user interface. I would likely use Bootstrap or another easy-to-use framework to make the app look prettier without having to do any actual design. Another feature I would add is "survival" mode which just lets the user go on forever until they make a mistake and their score would be the amount of rounds they "survived" for. I would also implement a few of the optional features, specifically the randomized patterns, limited time to guess, and more functional buttons to make the game more engaging and complex. 



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Rakesh Pillai

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
