- [Lucky Casino](#lucky-casino)
- [Introduction](#introduction)
- [UX](#ux)
  * [Project objectives](#project-objectives)
  * [Player Goals](#player-goals)
  * [Developer Goals](#developer-goals)
  * [User Stories](#user-stories)
- [Design](#design)
  * [Inspiration:](#inspiration)
  * [Font](#font)
  * [Colours](#colours)
  * [Icons/Images](#iconsimages)
  * [Content Section](#content-section)
  * [Wireframes](#wireframes)
- [Features](#features)
  * [Existing Features](#existing-features)
    + [Game Startup Modal](#game-startup-modal)
    + [Active Game Mode](#active-game-mode)
    + [Game Over Modal](#game-over-modal)
  * [Scalable and Easy to Maintain Code](#scalable-and-easy-to-maintain-code)
  * [Features to Improve/Implement](#features-to-improveimplement)
    + [1. Animation improvements](#1-animation-improvements)
    + [2. Start Up Cards](#2-start-up-cards)
    + [3. Game Title Lighting amends](#3-game-title-lighting-amends)
    + [4. Theme Swaps](#4-theme-swaps)
    + [5. Difficulty Levels](#5-difficulty-levels)
- [Technologies used](#technologies-used)
- [Testing](#testing)
  * [Validation Testing](#validation-testing)
  * [User Stories Testing](#user-stories-testing)
    + [Automated](#automated)
    + [Manual](#manual)
    + [Cross Browser Testing](#cross-browser-testing)
    + [Device Testing](#device-testing)
    + [JS-Hint Findings](#JS-Hint-Findings)
  * [Lighthouse Audit](#lighthouse-audit)
  * [Bugs Discovered](#bugs-discovered)
    + [Outstanding Defects](#outstanding-defects)
- [Deployment](#deployment)
  * [Deploy to GitHub Pages](#deploy-to-github-pages)
  * [How to run the project locally](#how-to-run-the-project-locally)
- [Credits](#credits)
  * [Content/Media](#contentmedia)
  * [Code](#code)
  * [Acknowledgements](#acknowledgements)

# Lucky Casino

![Title Image](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image1.png)

# Introduction

Lucky Casino is a
memory game using cards and the users are required to match pairs via the same
picture. This website will use the user's memory and skill in trying to match
the pairs before the time runs out. The website can be used by everyone and
will be fun and challenging for everybody who has an attempt. The site will be
bright, colorful and will have a host of interactive content. This will include
animations, music, sounds and high JavaScript content involved to improve the
site functionality.

Click the link to play [Lucky Casino](https://tomod24.github.io/CasinoGame/)

* Fun game matching the pairs of
     cards together
* Interactive content to make the
     game more appealing and fun to the user making the first impression on the
     user greater.
* This will test the user's skill
     and memory attributes offering a challenge for the user to have another go
     to try and complete the game.

# UX

## Project objectives

Lucky Casinos main objective is to allow users to play an
engaging memory game with as little instruction as possible. The casino music,
colors and race against the clock gears it to an audience of 18 years and up.

## Player Goals

* Fun card
     flipping game thats very simple to use without any complications
* Game
     controls for starting and volume do not require instructions
* Enjoyable
     game thats provides a chohesive pleasant colour, sound and imagaery
     scheme.

## Developer Goals

 Demonstrate
a solid understanding of JavaScript

* Build
an intuitive and engaging game

* Build
up portfolio with a great project

* Make
the game easier to maintain and scalable for future features.

* Using various items such as pictures instead of graphics. I wanted the 
page to be interactive and also provide the actions of a
casino such e.g. dice rolling, chips rolling, happy music and certain font that
would suit the game theme.

## User Stories

As
an older player seeking to strengthen my memory I want:

* to have
     a game thats not themed for children
* to start
     the game without any delay once the user is ready
* to play
     another round easily
* As a
     player I want the game to work correctly. The functionality of the game
     should be flipping the cards and revealing the images behind them.

* to
     be acoustically rewarded if I have a match
* to see the animation of the
     pairs I have matched on the cards. This will be a left to right smooth
     motion for each image.

* to
     hear the music playing when the game start
* to hear
     the victory music to indicate I have won the game.
* to hear
     the fail music if I time out.
* don't
     want any errors while playing the game

* the
     timer to countdown giving the sense of a challenge to try and complete the
     game
* to
     be aware of how many flips it took me to win the game
* to be
     able to mute the sound and unmute the sound via a button.
* to see
     casino like animages (poker chip and dice images on the card backs rotate)
* to know
     where the cursor is hovering over the card selected (dice move to center
     of card)

# Design

## Inspiration:

The design was influenced by the original
idea as a casino I believed the aspects, items and general first thought what a
casino was is too be applied. If people walk into a casino they think of cards,
money and various symbols such as chips, bells, cherrys etc. I have attempted
to include the same feel from an actual casino to make it more appealing that
they are at one when viewing the design of the game. I looked at various
pictures and from experience know what is in a casino. It is normally
associated with fun therefore I believed the idea would good for a memory games
due to the various different items that could be used for pictures. I wanted
the page to be interactive and also provide the actions of a casino such e.g.
dice rolling, chips rolling, happy music and certain font that would suit the
game theme.

## Font

The font used for the game was from [www.dafont.com](http://www.dafont.com) it was perfect and suited for the theme of the game. I had
tried several fonts amending the styles of the size and colour which wasn't
suited. The website provided me a font that I thought would suit well on the
website. It had the style that I was looking for and gave the font a better
design overall on the webpage. The number font was used but in the bugs section this will describe
the error found as a result the font used for the number was san-sarif instead. This was due to a counting 
error when the game was in motion. As a result the font work alot better had a better
presenation due to this amend.
Examples have been provided below.

![Font Image1](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image2.png)

![Font Image1](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image3.png)

## Colours

The colours used for this game/website are casino based. Using
the green, red and gold related colours with black to represent the night. The
default colours used for chips, gambling tables and playing cards was the
influence. I could have used any colours but don't believe it would suit the
need. Also, I tried and tested various colours and it didn't fit very well.
This provided me with the idea to keep it with the topic the game is under.
When people join or view the game/webpage they'll feel like it's a casino from
the beginning. The colours used are have been displayed below.

![Colour Image](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image4.png)

## Icons/Images

My initial thought on the icons was to use the help of font
awesome for icons as they were perfect and had a good experience. Unfortunately,
with the flip card game I wanted more interactive images and look more
realistic. I believed this would be better impact and have a better affect
overall for the user experience. I took various images from the web pages
finding the perfect images for the game. To me and other users who have viewed
the page and interactive and tested it they've found the game overall image
impressive and eye catching. This was the idea I was going for ensure the game
works correct and is pleasant visually to the user.

## Content Section

For the content the cards have been applied as required in a 4
by 4 grid for this mode. Keeping the main aspect of the game in the center of
the screen for larger devices. For small devices this has been set to be viewed
as 2 by 2. I believe this can be implemented to be improved in the future and
something to work on to be 4 by 4. They will start with click to start message
with the cards hidden. Once started the user will hear the music and clock will
be begin to countdown. The cards will
flip as required only two at a time as it checks the match. If its wrong cards
flip back and the user goes again. The
game title will be at the top of the screen with the font and colours provided.
Followed by the clock and time, mute and unmute button and the flips which
counts as the user clicks the cards. When the cards match the cards will stay
on the screen visible of the item and will swing left to right to show they
have been paired up correctly. If the user can't complete the game in time,
they will get the Game over message including some sad music to show they have
lost. The user can click again on the screen to try the game again. If all the
cards match the user will get a Winner message on the screen and click to
restart. Overall, I believe the game set up will be simple enough to understand
be fun for the user.

## Wireframes

I used Balsamiq frameworks for designing and planning my game
this would be the way to influence my design and give me an idea how it would
look from my ideas. If any changes are implemented then I can discuss the
changes from the original idea and show how I've improved the design.

The wireframes will show the design and the following images
will show the design of the game and the outcome of the requested design. I
will try and match the game to the wireframe and improve the project as I go.
Providing information on how and why changes have been made on the project and
the game. This will always be to the benefit of the design, layout and final
outcome of the project work.

![Wireframe Image1](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image5.png)

![Wireframe Image2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image6.png)

![Wireframe Image3](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image7.png)

![Wireframe Image4](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image8.png)

![Wireframe Image5](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image9.png)

![Wireframe Image7](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image10.png)

![Wireframe Image8](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image11.png)


# Features

## Existing Features

### Game Startup Modal

* The
     game loads with a screen prompting the user to get started. Since the game
     is timed, I wanted to give the user a screen that they could see the
     layout and controls immediately without starting the clock. So, the start
     click overlays the playing board to ensure the clock starts when the user
     is settled and ready to play, so they could maximize their chance of completing
     the game.
     
![Game Start Image](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image12.png)     

### Active Game Mode

The active game mode has the game
title clock, sound control, flip counter and cards.

![Active Game Image1](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image13.png)

* When a user clicks on a card, it animates as it flips over
and the face value is displayed.

* When the user hovers over the image the dice enlarge and roll
to the center of the card.

![Active Game Image2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image14.png)

* When the user clicks and matches the images on the game the
user will hear the flip sound and the cards will sway left to right.

![Active Game Image3](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image15.png)

* If the user gets the
pairs wrong both cards will display for a very short period before spinning
back to be hidden.

![Active Game Image4](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image16.png)

* Below shows the mute
button being included in the game. The image below with the speaker added and
the vibrations indicates the sound is playing in the game at this moment.

![Active Game Image5](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image17.png)

* The below shows a
speaker with and X this will indicate the sound has been muted in the game. The
sounds images have been customer made by putting a square and rectangle
together with a bendable line fore the sound vibrations. The x was made with a
capital X included.

![Active Game Image6](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image18.png)

### Game Over Modal

* There are two versions of the
     game over, loser and winner.
*The music is upbeat if the user
     if victorious.</b>
* The music is doomed if the user
     fails to beat the clock.
* Both screens encourage the user
     to play another game
     
![Game Over Modal](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image19.png)

## Scalable and Easy to Maintain Code

The card_data code has been amended and is now a json object so
if required the number of cards in the game can be increased. This can be the
difference including a more difficult game or easier game by decreasing the
difficult with less cards or increasing the difficulty with more cards. This
would therefore change the theme of the game as there is either a race against
time where the user needs to be quicker or can complete the game patiently as
they have less cards to pair up together. The buildCard loops through using a
dynamic affect generating the game outlay which makes it easy to maintain
reference to the file with the stuff being located in by the directory path.

![Winner](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image20.png)

## Features to Improve/Implement

### 1. Animation improvements

The idea I had for the web page as an improvement after
completing the webpage would be when the user matches a pair they could zoom or
move towards the user's screen. They would enlarge and say pair. At the moment
I didn't believe this was necessary but as a future improvement this could be
an excellent idea. This could be with fireworks just enhance the users
experience when they get a pair visually.

### 2. Start Up Cards

When the user starts the game, this could be the cards being for
example shuffled on to the page. So, before the game starts for the user and
the clock counts down the cards would be dealt out on to the screen. This would
be a huge improvement when users start up. This would be a future in
improvement due to the various actions required with the code and to get this
100% correct would be the main aspect. The cards would have to align perfectly
on the screen.

### 3. Game Title Lighting amends

Due to the theme being casino and using bright lights behind the
Lucky Casino text there could be a need for a lighting effect. This could be
like a flashing light behind the text making it stand out more and be really
appealing. I believe this would be a good feature and would need to be
researched. Only concern would be for any people who have trouble with flashing
lights as part of a health concern. I believe the users safety would be fair
and foremost. A warning would be required if this was implemented to keep any
users who suffer from this safe.

### 4. Theme Swaps

Theme is the upgrade option for the game. This would have to
completed and reviewed and tested ensuring the themes can be swapped correctly
and wouldn't have any code breaks. This would require through testing to ensure
the user can flip between themes very easy if they wish to do without losing
their current game. My overall target was to make sure the theme used (Casino
Theme) would work correctly before implementing the theme enhancements in the
game.

### 5. Difficulty Levels

Having different difficulties in the game would be an excellent
addition to get users to test their skills on easier modes or harder modes. As
this was not the aim of the game it was too ensure the game functions correctly
and is visually attractive for the user to keep interested. This feature can be
input once the game is working correctly 100%. The main function and goal is to
ensure the game is working and working successfully.

# Technologies used

For the website the following programming languages have been
used HTML, CSS and JavaScript programming languages.

* [GitHub](https://github.com/) - The project required and
     believed GitHub was the best for storing the projects details and easily
     be used for remote access when required.
* [JQuery](https://jquery.com/) - used to simplify some
     DOM manipulation for certain functions
* [GitPod](https://gitpod.io/) - Great toll to be sued
     for the development of the website and using the platform to complete the
     website as required. This helped fulfil the potential to complete the
     website.
* [Boostrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) - Quickly design and customize 
responsive mobile-first sites with Bootstrap. Bootstrap helped with the mobile design and aspects when desigining the game.
* [Dafont](http://www.dafont.com/) - This particualr website provided the 
casino style font I was requiring for the game design.
* [Basalmiq](https://balsamiq.com/wireframes/desktop/) - Used for wireframe
creation using professional tools to support the design
* [Lighthouse](https://developers.google.com/web/tools/lighthouse/?utm_source=devtools) - Audit you used it
for your accessibility testing
* [Favicon](https://favicon.io/favicon-generator/) - Used to provide unique logo for
the web page icon section
* [Coolers](https://coolors.co/) - Color Scheme generator, used to fine tune color selection and find hover
     colors
* [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables/) - Used to help with
     documentation table formatting
* [Markdown Table Of Contents Generator](https://ecotrust-canada.github.io/markdown-toc/) - Used to create table of
     contents
* [HTML Color Codes](https://htmlcolorcodes.com/) - Used for support of the html colours and graphic design for the colours selected
     contents

# Testing

## Validation Testing

I used the following websites and
pasted my code into it to ensure the code had no syntax errors:

* JavaScript -[https://jshint.com/](https://jshint.com/)

* HTML -[https://validator.w3.org/](https://validator.w3.org/)

* CSS -[https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)

* Lighthouse -[<b>https://developers.google.com/web/tools/lighthouse/?utm_source=devtools](https://developers.google.com/web/tools/lighthouse/?utm_source=devtools)

## User Stories Testing

### Automated

Jasmine testing would be ideal to
test the card flipping accurately and accordingly. Also, the building of the
card content was correctly working. Due to time constraints and working on the
other aspects of the game I couldn't pursue the possible requirement.

### Manual

Manual testing was completed on
the website/game features ensuring they work correctly for the users. The details have been provided below showing
the result of the testing via two devices. The responsive device was fine when
testing. Therefore, attempt testing on a small platform and a medium platform.

### Cross Browser Testing

Various browsers were tested
with the game link to ensure it would work on the browsers selected and
available to use.

![Cross Browser Testing](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image21.png)

![Cross Browser Testing2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image22.png)


### Device Testing

To enable all device were
tested and various device were explored tablets and mobiles where considered to
test the game on. This would ensure this works on multiple devices.

![Mobile Browser Testing1](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image23.png)

![Mobile Browser Testing2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image24.png)

### JS-Hint Findings

Script.js – When using the JS-Hint tool an alert was provided one undefined variable. The variable is working correctly and isn’t required to be declared in this particular case. I have made a note of the finding but this does not affect the code in anyway.

![Mobile Browser Testing2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image33.png)

Card.js - When using the JS-Hint tool an alert was provided one undefined variable and image warnings. The code reflects the code and the way it used correctly pulling the multiple images. As a result, the code provided works correctly and would need an amend.

![Mobile Browser Testing2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image34.png)

## Lighthouse Audit

Identify and fix common problems
that affect your sites performance, accessibility, and user experience.

Accessibility testing was
conducted on the site to ensure it was suitable and performing to a suitable
score for users and their experience on the website. This way the site can
potentially work to its maximum performance. This is completed by selected the
lighthouse option on the developer tool and generating a report for the selected
device. This can be mobile or desktop devices.

![Lighthouse Audit1](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image25.png)

![Lighthouse Audit2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image26.png)

The
results for mobile are 98 which is a worthy score for a website but I would
look to improve the score where posisble this can be a future update and
performance improvement.

![Lighthouse Audit3](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image27.png)

The
result for desktop was 100 which is acceptable for the website and performance.
As mentioned in the mobile review improvement to be completed as a future
improvement.

As you can see for both parts of
the testing the accessibility is at 77 which isn't the best for that option and
could do with improving. A few amends where completed and added the ```alt="card"```
code to each code in the card.js section e.g. ```(<img class="dice
dice-bottom-right" src="assets/images/dice.png"
alt="card">'+) and (<img class="chip"
src="assets/images/chip.png" alt="card">'+.)``` This fixed
both the mobile and desktop accessibility and upgrade all scores to a better
standard. This is indicated on the two images below mobile accessibility
improvement and desktop accessibility improvement.

Mobile Accessibility Improvement

![Mobile Accessibility Improvement](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image28.png)

Desktop Accessibility Improvement

![Desktop Accessibility Improvement](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image29.png)

## Bugs Discovered

![Bugs Discovered1](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image30.png)
![Bugs Discovered2](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image31.png)

1.a

![Bugs Discovered3](https://github.com/tomod24/CasinoGame/blob/master/assets/images/readme/image32.png)

### Outstanding Defects

A minor issue with sound was when
the game is muted and restarts the sound plays in the game. This bug will need
more time to be fixed due to the late discovery. If the user mutes the music
twice it fixes the issue but unknown reason if the code is muted it should play
the sound. This needs more investigation to resolve the issue.

# Deployment

## Deploy to GitHub Pages

I developed this project using Gitpod. I would amend the website
as required and submit my amends to GitHub via Gitpod by committing and pushing
the changes to the server. This would be completed using the GitPod
terminal.

* Log
     into [GitHub](https://github.com/)
* Select
     'Repositories', navigate to [Lucky Casino](https://github.com/tomod24/CasinoGame)
     and select
* Select
     the dropdown menu and your repositories if required
* Select
     the settings tab under the repository title.
* Scroll
     down to the GitHub pages section.
* Select
     master branch the page reloads the website has now been deployed.
* Scroll
     down the page after several seconds the information should state the site
     has been deployed in green and the link should be clickable taking you to
     your website. [https://tomod24.github.io/CasinoGame/](https://tomod24.github.io/CasinoGame/)

## How to run the project locally

To clone the project from GitHub:

1. Click
     the following link for the [GitHub repository](https://github.com/tomod24/CasinoGame).
2. Click
     on the code button
3. A
     dropdown window will appear titled 'Clone with HTTPS' - copy the link
     provided in the field below
4. Open
     your local IDE
5. Change
     the current working directory to the location where you want the cloned
     directory to be made
6. Type
     in git clone paste the URL copied from earlier (step 3) alongside the
     git command.
7. Press
     Enter, and the clone should subsequently be created

# Credits

## Content/Media

* Casino
     font was provided by [https://www.dafont.com/casino-2.font](https://www.dafont.com/casino-2.font) which greatly suits the game.
* Ace
     of spades image - [https://imgbin.com/png/KaXXXDCk/hearts-playing-card-ace-of-spades-card-game-png](https://imgbin.com/png/KaXXXDCk/hearts-playing-card-ace-of-spades-card-game-png)
* Watermelon
     Image - [https://pngtree.com/freepng/cartoon-summer-sweet-watermelon-png-transparent-bottom_4573609.html](https://pngtree.com/freepng/cartoon-summer-sweet-watermelon-png-transparent-bottom_4573609.html)
* 777
     images *  [https://www.kindpng.com/imgv/bxJiw_three-seven-jackpot-png-clip-art-graphic-design/](https://www.kindpng.com/imgv/bxJiw_three-seven-jackpot-png-clip-art-graphic-design/)
* Jackpot
     image - [https://www.searchpng.com/2019/04/24/jackpot-png-image-free-download/](https://www.searchpng.com/2019/04/24/jackpot-png-image-free-download/)
* Bells
     image - [https://www.searchpng.com/2018/12/16/christmas-bells-clipart-png-hd-christmas-bells-clipart-png-image-free-download/](https://www.searchpng.com/2018/12/16/christmas-bells-clipart-png-hd-christmas-bells-clipart-png-image-free-download/)
* Coins
     image - [https://www.searchpng.com/2019/12/11/stack-of-gold-coins-png-image-free-download/](https://www.searchpng.com/2019/12/11/stack-of-gold-coins-png-image-free-download/)
* Lemon
     image - [https://imgbin.com/png/gbNDM7K5/cartoon-lemon-png](https://imgbin.com/png/gbNDM7K5/cartoon-lemon-png)
* Cherry
     image - [https://www.pinclipart.com/pindetail/iimRTw_cherries-clipart-transparent-background-clip-art-png-transparent/](https://www.pinclipart.com/pindetail/iimRTw_cherries-clipart-transparent-background-clip-art-png-transparent/)
* White
     Dice Image - [https://www.pngkey.com/detail/u2a9o0y3u2q8i1o0_white-dice-png-clip-art-black-and-white/](https://www.pngkey.com/detail/u2a9o0y3u2q8i1o0_white-dice-png-clip-art-black-and-white/)
* Poker
     Chip -  [https://www.pinclipart.com/pindetail/Twbwih_drake-casino-drakecasino-poker-chip-clipart-png-download/](https://www.pinclipart.com/pindetail/Twbwih_drake-casino-drakecasino-poker-chip-clipart-png-download/)

* Background Music - RKVC - Christmas Chores - https://studio.youtube.com/channel/UCm-T04_5xc8fgzQ1-IScuqQ/music?utm_campaign=upgrade&utm_medium=redirect&utm_source=%2Faudiolibrary%2Fmusic
* Victory Music - Otis McDonald - Left U Into (Sting) - https://studio.youtube.com/channel/UCm-T04_5xc8fgzQ1-IScuqQ/music?utm_campaign=upgrade&utm_medium=redirect&utm_source=%2Faudiolibrary%2Fmusic
(Have to search the song name all the music is shared under one list
* Lose Music - Aaron Kenny - Watercolor Lilies -  https://studio.youtube.com/channel/UCm-T04_5xc8fgzQ1-IScuqQ/music?utm_campaign=upgrade&utm_medium=redirect&utm_source=%2Faudiolibrary%2Fmusic
* Audio cassette tape inlay card remove from case - Flip Sound - https://www.zapsplat.com/music/audio-cassette-tape-inlay-card-remove-from-case/
* Arcade game slot machine payout or collect tone - Match Sound - https://www.zapsplat.com/music/arcade-game-slot-machine-payout-or-collect-tone/



## Code

* Insert element added
to the code for the pictures loading correctly. Provided by [https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentHTML](https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentHTML)

* Used for the image at
the beginning of the document showing the code in a display device provided by [http://ami.responsivedesign.is/](http://ami.responsivedesign.is/)

* Web Dev simplified
& PortEXE provided support and guidance on how a flip card game works
correctly great helped in understanding how the code works together and the
functionality. [https://www.youtube.com/watch?v=28VfzEiJgy4](https://www.youtube.com/watch?v=28VfzEiJgy4) & [https://www.youtube.com/watch?v=3uuQ3g92oPQ&feature=youtu.be](https://www.youtube.com/watch?v=3uuQ3g92oPQ&feature=youtu.be)

* credit to
https://codepen.io/teerapuch/pen/vLJXeR for the spinning action for the items
on the cards e.g. dice and chip images.

## Acknowledgements

* I would like to thank Anthony Ngene whose
guidance and determination to make succeed keeps the work going daily. Takes
the time to discuss my ideas and why and tries to guide me in the right
direction asking how this will be achieved. Great mentor throughout the course
and ensures am on top of my planning trying to reach my planned targets for the
project completion.

* I would like to thank Malia Havlicek who gave me
time to support me and help me with my coding concerns. I have been learning a
lot and pointed in the right direction how to achieve certain aspects of codes
and issues. Always explained the concept behind why its needed how it works and
ensured I understood so there was no uncertainty. Malia Been a great support on my quest to learning
more and glad I've got a friend in the coding world.

* For my family who ignored me so I would progress
with my work and do the best job possible.
