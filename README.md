# bio-mon

**an anki card deck perfect for bio1!**
**evolve your knowledge by practicing and try catch them all!**

this project contains a CrowdAnki deck representation, meant to be downloaded and run in anki


## requirements
1. anki for desktop, version 25.02.5 (only one tested) with the required add-ons:
2. anki-mon - an anki pokemon extension (id:1908235722)
3. crowdAnki - extension used to import\export decks from git (id:1788670778)
4. git


## getting started
1. install all the things, documentation at https://apps.ankiweb.net/
2. create a folder on your device dedicated to bio-mon
3. clone this project into the folder by running these commands

`cd \...my-biomon-folder\\`
`git clone https://github.com/ellaeln/bio-mon.git`

the files will download themselves into the folder

4. in anki, go to File->crowdAnki: import from disk

this will open a file navigation window. navigate to the folder in which bio-mon is cloned and select it.

5. approve the import

the deck will be created\updated.
you are officially ready to play!


##  how to contribute (Pull Requests)
This project is public, but only authorized members can merge changes to the main deck. To contribute:
1. **Fork** this repository to your own GitHub account. Use the botton in the upper right corner. this will create a copy of the project under your account, allowing you to edit and interact with it.  
2. **Clone** your fork by following "getting started" again replacing the link with your own.
3.  **Write cards** add your cards/edits in Anki.
3. **Export** from Anki using CrowdAnki back into the folder. make sure to pick "crowdAnki json format" to ensure compatibility
4. **Push** the changes to *your* fork and open a **Pull Request (PR)**.
5. The team* will review the changes and merge them into the main bio-mon deck!

Make sure you use the latest version of deck before merging, uncurrent request with a few new cards will be rejected to avoid losing progress.


## 🧬 card matching rules (DNA integrity)
To make sure our cards sync correctly and don't create duplicates:
* **Don't delete and recreate**: If you want to edit a card, just edit it. CrowdAnki uses hidden UUIDs to match cards. If you delete and recreate, it counts as a new card and will cause double-entries for everyone else.
* **Keep the structure**: Do not change the Note Type or rename the fields (Front, Back, etc.). The "DNA" of the card must stay the same for the merge to work.
* **Media**: If you add images, ensure they are in the project folder before you export and commit.
