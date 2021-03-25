# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Kennedy Marsh

Time spent: 10 hours spent in total

Link to project: 
https://glitch.com/edit/#!/luck-flaxen-plier

## Required Functionality

The following **required** functionality is complete:

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
* [Y] Playback speeds up on each turn
* [Y] Computer picks a different pattern each time the game is played
* [Y] Player only loses after 3 mistakes (instead of on the first mistake)
* [Y] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

- W3Schools.com
- Stackoverflow.com
- Developer.mozilla.org

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One challenge I ran into was when I was trying to implement the random sequence feature. My first idea was to create a for loop that would loop through the pattern array and change the values. Unfortunately, that process took up too much memory (both Google Chrome and Firefox would give me an error saying the broswer had run out of memory when trying to display the webpage). In result, I had to take the manual route and change the values individually. 
Another challenge I ran into was finding the best way to implement the button image feature. I started out with creating JavaScript functions for each individual image to be displayed and removed, but quickly realized that that method was very inefficient and cluttered up my code. To fix this, I took advantage of the id names for the images, and used document.getElementById("bug"+bug), where the bug outside of the quotation marks is a placeholder for the number found in each image id name. In the html file, I used the "onmousedown" command to prompt my functions to accept the respective numbers. This change was useful because it allowed me to go from 8 individual functions to only 2. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

While completing the tutorial, I learned that most HTML elements on a web page are part of a "flow" layout. The keyword "most" implies that there are a few elements that are to remain static on a webpage. With this in mind, I wonder: what are the scenarios where keeping the elements static is ideal? How do web designers determine that?
Another question I came up with is: who came up with the syntax for HTML, CSS, and JavaScript? It would be fascinating to learn about the thought proccess of those who helped create these languages. 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to complete the project, I would have implemented the timer function. I also would have looked for ways to make my JavaScript functions less redundant. 
Some additional features that I would have like to add, on top of the timer, is a competitive factor. I would add a leaderboard that tracks which users can complete the game in the least amount of time. Naturally, this feature requires smaller features, like a way to record usernames and keeping track of users and their individual scores. I would also add more exciting winning and losing notifications and/or incentives. I would make the winning/losing notifications more interesting by turning the alerts into web pages instead, where I can add some funny memes or gifs to humor the user. I would add these because it is important to keep the users engaged; the more interesting the game, the longer they will play. Finally, to make the game more interesting, I would add the feature of having the game tack on more buttons to the webpage as the game progresses. 



## License

    Copyright Kennedy Marsh

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.