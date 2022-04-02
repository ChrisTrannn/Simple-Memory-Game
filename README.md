# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Chris Tran**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/aquamarine-scarlet-jupiter?path=script.js%3A135%3A5

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
![](http://g.recordit.co/yo89wH3dCK.gif)
![](http://g.recordit.co/LDMSwyzsrQ.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
stackoverflow, google, w3schools

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge that I encountered in creating this submission was working with Github desktop, and using glitch.com to export my file to Github. I struggled with Github desktop initially because I am more familiar with using Git through the command line. And using Github desktop was weird because I was unfamiliar with the UI. I didn’t know how to commit and push files. I eventually figured it out by watching the tutorial video, which was extremely helpful. Another struggle that I encountered while creating the Memory Game was exporting the glitch file. Glitch.com’s website had a different UI then the one I was working with. I eventually figured it out by messing with glitch.com until I found what I needed. In terms of creating the actual memory game, working with html and css was fairly straightforward. There were a couple of things in javascript that I was unfamiliar with, mainly the syntax, but that all was resolved by going to stackoverflow and other websites to figure out. Other than that, the language itself didn’t look too complicated as I have a good understanding of how control structures, functions, and loops work.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I have a lot of questions about web development in general. These questions pertain to the backend side of things. I’m mainly interested in working with technologies such as MongoDB, Express, React, and Node.js. Creating websites through html and css seem straightforward enough. I’m very curious as to how the front end works with the backend. I’ve also been hearing a lot of things about SQL, and how important it is to employers that work with large databases. Overall, I’m very curious about web development in general, and how the front end and the back end work together.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would figure out a way to change the noises of the button when clicked. I would probably make them very high pitched. The first thing I would do to accomplish this is refactor the playTone() and startTone() functions in the style.js file. Maybe change the volume value initialized at the top to be a higher number. I would make the game more complex by adding more buttons. I would accomplish this by adding more buttons into the html file, changing their respective colors in the css file, and editing the secret pattern in the script.js. And because I don’t like the fact that the pattern is the same one each time the game is played, I’ll use Math.random to generate new patterns and include it in some function. Then call that when the start button is clicked.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Chris Tran]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
