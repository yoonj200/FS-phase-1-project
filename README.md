# **Bored? (The Game)**
## **Project Philosophy**
Everyone should be able to learn something while having fun. If you want to be ready for a random game of jeopardy, this is the app for you!

## **Features**
1. An interactive game of hangman. Click letters to try and guess the word.
2. A completed word returns a random (and often insightful) fact.
3. Failure returns a prompt to try again.
4. Clickable 'Hint' button.
5. Attempt counter display.
6. Dark/light mode theme button.

## **Installation**
1. Open up the directory where you want to clone this repository.
2. Copy the SSH URL ( git@github.com:yoonj200/FS-phase-1-project.git ) and run `git clone url-here` in your command line. 
3. Run `code FS-phase-1-project` to open the source files in your text editor. 
4. From the command line, install JSON Server.
```
npm install -g json-server 
```
5. Start the JSON server.
```
json-server --watch db.json
```
6. After viewing the source files, run `explorer.exe index.html` to open the SPA in your local browser. 

## **How to Play**
1. Click a letter to test if it belongs in the hidden word.
   
   ![](selectLetters.gif)
2. Be careful, you only have five attempts. 
   
   ![](selectWrongLetters.gif)
3. Don't be shy, use a hint! 
   
   ![](useHint.gif)
4. If you win, you get to learn something new!
   
   ![](ifYouWin.gif)
## **Credits**
- [Random Useless Facts: HTTP API for Useless Facts](https://uselessfacts.jsph.pl/)

<span style="color:gray">NOTE: This app is a single page application (SPA)</span> 

