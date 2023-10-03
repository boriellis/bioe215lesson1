#ASSESSMENT ANSWERS

#Bryan (2017)
set(wd) is obnoxious because it's unique to what's happening on your computer, so it doesn't help anyone else using your code at all. Also whenever I move files around it'll break it, so rerunning old code becomes obnoxious. I still don't totally understand the "here" stuff, but I think Projects fix this because all the files are stored within the Project so that everything lives together in a safe and happy harmony and isn't getting fiddled with on your own computer constantly. 

rm(list=ls()) is a nightmare because it only removes stuff that you created during the R session, but things like the packages you have loaded up and the working directory remains, so you might not know you're relying on those packages and stuff as you're writing your code and make fun traps for future you by accident. Instead you should restart your R session, and make sure that your settings are such that your workspace isn't saved when you do that. The hotkeys for that is Command+Shift+F10 which I learned is obnoxious to do because I have one of those stupid touch bars that apple thought was a good idea once but that's a separate conversation. 

#Bryan 2018

Commit happens locally and is kinda like saving a file. Push moves my files remote (to my online github repo) and pull brings them from my repo to my local system. 

I guess word docs are not compatible with github because changes to those files are not really legible in diffs. Apparently this is because Word and Excel type files are binary but truly couldn't tell ya what that means. Something to do with the size or complexity of the filetype?

RMarkdown is nice for github users because it means that you can do the behind the scenes coding stuff at the same time as making a nice easily viewable website for your project and it seemlessly integrates into your github repository. 



