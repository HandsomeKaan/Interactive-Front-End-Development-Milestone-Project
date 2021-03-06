
# Interactive-Front-End-Development-Milestone-Project 


## Memory Matching Game 

This project is a simple matching game that consists of 6 pairs of cards to match, including a timer and count clicker to track the players progress throughout the duration of their visit to the website.

## UX 

The game is directed at early users of tablets, PCs and online games. It's very simple and might not attract the attention of teens or adults.

### User Stories

As a new visitor to the website...

- I want a simple intuitive game to curb boredom.
- I want playing the game to be intuitive, requiring little explanation. 

As a returning visitor to the website...

- I want to be able to play the game and have the same, bug-free experience each time.

### The viewer would be visiting my site if they are: 

Looking to play a simple, memory matching game and looking to have a seemless, glitchless experience. The website does not feature any other games. 

### The website can help to achieve that because: 

It is a simple memory matching game. It should be clear and concise, intuitive to pick up and play being easy to understand and play to help the viewer breeze through the page without any problems.

### Wireframes / Mock-ups Used: 

Here are the links to my Wireframes:
* [Computer View Wireframe](https://user-images.githubusercontent.com/61510983/109387988-5fd7c500-78fc-11eb-930c-ad93c843c890.png)
* [Mobile View Wireframe](https://user-images.githubusercontent.com/61510983/109387997-66fed300-78fc-11eb-9939-de3231009c3f.png)
* [Tablet View Wireframe](https://user-images.githubusercontent.com/61510983/109388001-6a925a00-78fc-11eb-8a7e-4f7141c8af32.png)

As seen in the Wireframes, I followed my original format fairly closely. I did change the position of the header, timer and click-counter. I tried to follow this Wireframe as it allowed me to stop me from trailing off and wasting time by having to design the website on-the-go. In my Wireframes for mobile and tablet, I had 1 less row of cards as I was unsure if it would fit properly. However, that would've been difficult to achieve. Even so, I was able to make the cards fit properly without any problems. 

I didn't create a wireframe for the pop-up modal because I did not anticipate needing one.

## Features 

### Universal Website Features 

#### Header: 

Within my header is simply the title - "Memory Matching Game". There are no other pages as it is for the one game. Simple and clean with a nod to Code Insitute in the title and colour scheme.

#### Footer:  

The footer contains links to Twitter, Facebook and Instagram.

### The Game Page

#### How to Play:

The first box on the game page houses a brief explaination of how to play the game.

#### Timer & Click-Counter:

There is a timer and click counter. The timer starts when the user clicks "start". The click counter only increments when a card is clicked. 

#### Game Field: 
 
Contains the cards that are then matched up by the player.

#### Congratulations Pop-Up:

Contains a "congratulations" message, followed by the time taken and number of clicks used to complete the game.

## Existing Features 

* The "Start" button changes colour when hovering over it. This transition goes both ways, meaning it reverses the effect when the mouse is moved off of it. The mouse also becomes a pointer, to indicate that the button can be clicked.
* A timer that begins counting up upon clicking the "start" button, coupled with a click-counter that tracks each time the user clicks a card.
* The 12 cards can all be clicked, causing a flip animation. 
* When two cards don't match, they are flipped back over. 
* When two cards match, they stay face-up to indicate that the pair have been matched.
* When all cards are matched, displays a pop-up modal that tells the user they have completed the game, followed by the time and number of clicks taken.
* The socials change colour when hovered over, coupling as links to Twitter, Facebook and Instagram.

## Features Left to Implement

I don't really think the page needs any other features. It gives the user the intended experience, albeit it all one page.

## Features I Would Have Liked to Have Added

- Possibly being able to edit the number of cards on the game field at a time. I think having more cards would make it a more challenging experience after the user has completed the first set of cards. 

## Technologies Used 

HTML / CSS and Javascript.

No languages were used in the coding of this project. It is pure HTML / CSS and Javascript. No frameworks or libraries were used.  

This website uses Google Fonts to style the website fonts. https://fonts.googleapis.com/css2?family=Poppins&family=Roboto:ital,wght@1,300&display=swap.

This website uses Font Awesome to input 3 social website icons. https://kit.fontawesome.com/1bbedf96a8.js 

## Testing 

The website is simple and clean, meaning the HTML / CSS for it was fairly simple, too. I used flexbox once again to help position divs so that if a user was on mobile, it would squeeze it together and not cause any sort of misshaping. I ran into the most problems when it came to the Javascript. This project was very difficult for me, as over the two weeks I spent working on it, I spent most of it trying a bunch of different methods for my Javascript. I didn't realise there were so many different ways to do the same thing. The hardest part within my Javascript was definitely my check function. It required I make two lists for the two different cards clicked, a timeout for if the cards didn't match to prevent the user from spamming the cards and figuring out how to use the images to detect a match. 

Overall, it was very difficult for me as Javascript has been alluding me constantly. I watched some Youtube videos to help understand the Javascript and to really understand how to make those logical paths for my code.

### User Experience Testing: 

#### Header: 

1. The Title
    1. Check that the title doesn't overlap the header.
    2. Check that the title resizes as the width changes for mobile or table use.
 
#### Body (Prior to Game Being Started):

1. Start Button
    1. Upon hovering, the button should change colour.
    2. If the mouse is moved away from the button, it should revert to it's original colour slowly.
    3. Upon click, hide the button and the game field should appear.
    4. Upon click, the timer should appear with the game field and begin.
    5. Upon click, the click counter should appear with the game field.
  
#### Body (When The Game Has Started):
 
1. How to Play
    1. Check that when resizing the page, the text does not overlap the parent container.
    2. Check that the font size does not change to maintain readability.

2. The Timer & Click Counter
    1. Confirm that when resizing, the text does not breach their respective containers.
    2. Make sure that the timer has begun, starting from 0.
    3. Confirm that the click counter only increments when a card is clicked.
 
3. The Game Field
    1. Check that when resizing the page, the cards do not breach the game field.
    2. Check that the cards maintain their margin despite a change in device.
    3. Confirm that the cards shape changes as the screen is resized or if on another device.
    4. Confirm that the cards can still be clicked when on another device without any difficulty due to resizing.
    5. Make sure the images resize and do not breach the card containers. 

4. The Pop-Up Modal
    1. Check that when resizing the page, the modal width and text resizes correctly.
    2. Upon hovering over the "Play Again" button, it should change colour.
    3. If the mouse is moved away from the button, it should revert to it's original colour slowly.
    4. Check that the "Play Again" button refreshes the page, sending the user back to the original button screen.

#### Footer:

1. Socials Bar
    1. Check that the socials bar doesn't overlap the footer.
    2. Check that the width and height resize correctly when changing the size of the window or to a different device.

2. The Socials Icons & Words
    1. Check that when hovering on "Instagram", "Facebook" or "Twitter" that the colour changes.
    2. Check that when removing the mouse, this colour change is reverted.
    3. Confirm that when passing the width threshold (by changing device etc), remove the words and leave just the icons.
    4. Confirm that when the words have been hidden, the icons have increased in size.
 
#### Logical Testing The Game

If the user clicks the start button, begin the game.

If the user clicks a card, flip the card.

If the user clicks the same card again, flip it back.

If the user clicks two different cards, check for match.

After the second card has been selected, lock the board.

If the two cards clicked do not match, flip the cards back.

if the two cards clicked match, keep them face up.

If the user finds all matching pairs, trigger modal pop up to congratulate the player, stating time taken and number of clicks used.

#### Further Testing 

24/02/21
I had my family and friends do some testing on it simply by playing the game. I had 3 testers. I encountered a couple bugs the first time around, which saw that flipping over cards in quick succession broke the game and left cards facing up that weren't matched. I implemented the fix for this and after that had been unable to find anymore bugs.

28/02/21
During my testing, I would often spam click things to see what would break and what wouldn't. Upon further testing, I discovered a bug where flipping the same card BACK over meant that the classes given would change and essentially break. I was unable to figure out a fix in time for this bug, however I will be working on trying to patch it. 

28/02/21 LOG 2
Tested on an android and an iOS device. iOS devices weren't seeing the front facing images. To fix this, I was recommended to use Autoprefixer. This solved my problem. I also noticed that the Javascript Flower image would flip when the card was flipped. I have not been able to figure out a fix for this at this moment in time.

## Deployment 

This project has been deployed via Github Pages.

1. Log into GitHub.
2. Select KaganHuseyin/Interactive-Front-End-Development-Milestone-Project.
3. Select settings.
4. Scroll down the page and locate GitHub Pages.
5. Change the source to the master branch.
6. Once the page refreshes, the website has been deployed.
7. From here, go back to the repository and select "Environments".
8. Select view deployment and the website will open up in a new tab.

## Credits 

Links to Youtube videos that inspired me and helped me understand the logic behind the game.

https://www.youtube.com/watch?v=tjyDOHzKN0w&t=452s

https://www.youtube.com/watch?v=3uuQ3g92oPQ&t=918s

Link to Autoprefixer CSS Online. Used to fix my CSS for iOS devices.

https://autoprefixer.github.io/

## Media Used: 

The backface of the cards was the Code Institute Logo.

The front faces of the cards were drawn by me.

## Acknowledgments 

Thank you to my friends and family for testing my website a few times. It helped me find a couple bugs that I was able to fix and a bug I was unable to fix. Thank you to Jim_Lynx on Slack for helping me solve my image problem from 28/02/21 LOG 2! 
