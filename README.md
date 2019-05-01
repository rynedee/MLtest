# MLtest
Project

1.5.19 -- I updated the files to include links to my repositories. The issue I've been fighting is getting the changes to appear in a web browser. Locally the files render correctly, however when I attempt to view them via the modlabproject.appspot.com URL I see the un-updated files. In the past it has seemed as if it can take some time for an update to 'work its way through the system', but that hasn't worked this time. Clearing my cache on my local machine has not resolved the issue either. At this point it feels like there's some option with Google Cloud that I'm missing, not sure what I did but I was able to get two of the pages to render the updates for a couple of clicks before they went away.

---
HTML
---

No updates to the HTML as of now. The time spent working on that has been used to figure out why my update is not being served. I can see the files have been updated on GitHub, and as far as I know the Google Cloud web host is using the GitHub files. I feel as I was able to make some last minute corrections via the Sublime app on files when this was all set up. 

Some of my issues my be from the fact that I have some of these files open in three or four different places (for instance GitHub desktop was just found hiding in full-screen mode), so a quick restart to maybe help reset some bits to go along with some spring cleaning (need to delete a Bootcamp partition as well run a few updates).

---
Python
---

Wrote a two-player Tic-Tac-Toe game on Monday 29 April. That code is available on my repl.it page (www.repl.it/@rynedee) for now, ultimately it will end up as an embed on the Sports page once I figure out my Google Cloud issue(s). My next project will be an assignment from the Open Courseware class that involves creating a 'Scrabble'/'Words with Friends' clone.

Creating an AI for Tic-Tac-Toe will be something that I work on on the side. From my perspective it seems like a daunting task but it should be fairly easy, or perhaps straight forward is better. I have some ideas floating around but board awareness is where I'm at a crossroads. It seems knowing the state of the gameboard is tantamount to making informed decisions otherwise I'd need to code in every possible game state which is not happening. I maybe on my way with how I set up my winning conditions but only further experimentation will tell.

---
---

27.4.19 -- I've updated the Hangman.py to include a cheat code. Now when you type in a special character the game will give you a list of words that match what has already been guessed (or entire possible solutions list if done at the beginning of the game). 

My difficulty with this aspect of the project was two-fold. First, I had a difficult time figuring out the logic of what I needed to do as I kept getting myself into strange boundry-case issues (basically I was makiing it WAAAY more difficult than it needed to be). My second issue was getting my code deployed. I had it working with no issues in my test environment, taking care to mirror the same terms I used in hangman.py but it alternated between buggy (only gave one possible solution, the secret word) or was broken (function at line x doesn't want to work for some esoteric reason). It took nearly as long to get it implemented within hangman.py as it took to figure out the code.

---
HTML
---

Added a word limit to the sec3 RSS feed. I've discovered that section gets pretty close to overflowing based on the story CNN is running at the time. I'm also going to add some links on the navbar to my GitHub and repl.it pages. These should be floated to the right of the menu bar.

---
Python
---

As stated above, the major update was the addition of a cheat code within Hangman.py. I'm thinking of adding a qualifer to the cheat in an effort to limit the amount of possible words that are shown (one cheat code response returned a list of over 10k words). It will take some time to discover the point that list becomes managable but right now it appears that 3 letters are enough to substantially pare down the possible words list.

---
---

18.4.19 -- The website should be in a working stage at this point. I've struggled with creating a RESTful API to serve my RSS needs for the past five days, that is a nut I've been unable to crack. I was able to serve up some RSS items by utilzing a script from bloople.net. That particular issue will have to wait until I expand my knowledgebase a bit wider.

---
HTML
---

* Added bus.html, sports.html and life.html.
* Added various rss feeds to the aforementioned files.
* Completed additional formatting

---
Python
---

Hangman.py should be properly formatted for it's window size.

---
---

11.4.19 -- This is a two-part project to show a basic understanding of HTML and Python while familarizing myself with the use of essential collaborative tools such as repl.it and GitHub.

---
HTML
---

The HTML portion will consist of a webpage that shares visual simularities with a newspaper. It will contain some personal information and feature up-to-date headlines from a variety of sources. 

<i>Current Status: I've tapped into the BBC's US/Canada feed to populate the headlines and am exploring other news sources for a variety of topics of interest that will rotate along the bottom of the page. Another need is to figure out how to import the results from Python scripts to populte my webpage. I can use Python to grab specific datapoints from an rss feed, how I then inject those datapoints into HTML so they can be viewed on a webpage is beyond me at this point.</i>

---
Python
---

In keeping with the theme of a newspaper there will also be an implementation of the classic game Hangman that was written in Python. This Hangman game is from the MIT OpenCourseWare course Intro into Computer Science and Programming in Python 6.0001. Part of the code was provided by MIT (a word list (words.txt), the loading of that list, and the choosing of a random word from said list) along with some guidance on structure and purpose.

<i>Current Status: The game works. I have some formatting to do to make it look nice in it's much narrower new home. Just need to play through all the different combinations. Do need to check out the options for the embed box so that the source code is hidden from the jump and a note to click the play button to load a game.</i>



