# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Ayman Bolad

Time spent: 9 hours  

Link to project: https://glitch.com/edit/#!/selfstudyingprogrammer-turnedsalesforcefanatic

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Added difficulty options, increasing the amount of rounds by four per difficulty. The default difficulty and the easy difficult are the same, so if no difficulty is selected it will automatically be "Easy".

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![2022-04-22-20-01-23](https://user-images.githubusercontent.com/100540818/164836621-3e3db1c6-45d7-4773-bf49-fbdc9089f435.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

Aside from following the write up, I used;

W3 Schools (formatting and syntax): https://www.w3schools.com/
GeeksforGeeks (for learning / manipulating JS functions): https://www.geeksforgeeks.org/
MDN Docs (adjusting buttons): https://developer.mozilla.org/en-US/
Coolors (game button palette):https://coolors.co/
UIVerse (for button design): https://uiverse.io/
Random space images off of Google Images. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One of the biggest challenges I tackled was the creation of difficulty modes. Originally, I wanted to exponentially increase the speed per difficulty, 
but I felt it was out of the scope of my technical abilities so I settled for one increment of speed adjustment on the “Hard” difficulty mode. 
Instead, I settled for adding extra rounds to each difficulty in increments of four, excluding easy which just matched the regular amount of rounds. 
At first, I had no idea no idea how I would do this, but then remembered that the default function was provided. 
For this to work, I created a conditional function listing each of the buttons, and ensured that the scope within each if statement was only executed on press. 
Once that was completed, I assigned an empty array to the pattern, then replicated the previous loop used for the default mode. 
I altered the loop to have the pattern iterate through an array of integers that changed in the parameter of each function.
I also assigned variables to each mode, such that each mode could have a speed increase. 
Since I was fairly vexed at the idea of speed increments given that I had aspired for something exponential, I settled on having only one increment so that the game didn’t feel boring by just adding more rounds. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

One of biggest struggles when completing this assignment was the resizing of various elements, buttons, and texts. If anything, I felt that I had a great design in my head,
but was simply unable to execute on it due to my lack of understanding. As a result, one of the many questions I still have about web development is how great developers execute on design
and functionality in a manner thats conducive to the original goal of a project. As I attempted to implement various functionalities, or played with design, I found myself losing various hours trying
to create a stellar project that was just beyond the limitations of my skills, and I grew extremely frustrated at points as a result. 

Another question I still have is how web development can expand just beyond static sites, and what the best way to go implementing and executing as a developer would be. 
I have some experiences adding dynamic functionality with React, but I found myself trying to embedd imagery, video,
animation, and other various forms of media and motion in to the project in order to bring it to life. Alas, the overwhelming majority of these attempts were extremely unsuccessful, but gave me 
the motivation to continue pondering an learning. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

With a few more hours on this project, I would have loved to implement both a timer and lives system. I tried to do both at various points, but would end up breaking the game to the point where it either wouldn't start/stop,
or mistakes would fail to end the game. After various hours of implementation, debugging, refactoring of various functions, and iterative approaches to implementation, I ended up have to resign to the idea that such functions
were simply just beyond the scope of my skills at this present moment. Additionally, I would have loved to add speed to the pre-existing difficulties, so more devout players could play on faster modes with exponential speed increases. 
To round out the project, I would allow for G-Mail logins so that a local and global leaderboard could be displayed to show how fast individuals won the game. 
This would aid in making the game more fun and collaborative, where friends could compete. 

## Interview Recording URL Link
[My 5-minute Interview Recording] - https://www.youtube.com/watch?v=_6Fd-O1mTtY&t=3s
