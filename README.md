# DGMD-E-28-Assignment-Wordle
DGMD E-28 Assignment Wordle

Assignment URL: https://xxalisonrose.github.io/DGMD-E-28-Assignment-Wordle/

Random Word API: https://random-word-api.herokuapp.com/home

Free Dictionary API: https://dictionaryapi.dev/

I went through 3 different APIs trying to find one that worked, was free, and had an unlimited amount of times it could be used. I found this one through some Googling that was able to automatically filter out any words that weren't 5 letters so that saved me a few steps. I also wanted to include the definition for the word as a hint, so I found an API that would allow me to do that as well. I don't think it is a full dictionary. Sometimes the 5 letter word isn't found so it has to reload.

I'm really proud of this project. I spent 2 weeks working on it, with the most being the color changing letters. I learned about CharCode and ASCII in a CS50 class and I was struggling to get the two words to match up based on letters, but as soon as I assigned them to numbers, it was easier for me to figure out how to code them to match up. I think it was because I was able to confirm that they were "speaking the same language." Looking back, I think it might have been an upper case/lower case issue, but I'm not going to go back and fix something that is working.

If I had more time, there is probably a few things I would fix -- 
    - I would want to keep the buttons static in the box and not scroll if the definition is too long
    - Add animation saying you won instead of using an alert box
    - If the word is not a real word, don't count it as a submission - I think this is my biggest problem with this game. If you type in random letters, the console will tell you its not a real word, but the game will still count it as a guess. As someone who struggles with spelling, I think this is a huge disadvantage to the player.