# MLtest
Project

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



