###############################################
# Show or Hide Files in Finder Alfred Workflow
# BundleID: com.andyryan.hiddenfiles
# Date Created: 1/21/14
###############################################


SHOW OR HIDE HIDDEN FILES IN FINDER

This little workflow simply runs the following commands inside terminal to show or hide hidden files in Finder:

defaults write com.apple.finder AppleShowAllFiles -boolean true
or
defaults delete com.apple.finder AppleShowAllFiles
EXECUTING THE WORKFLOW

To Show Hidden Files in Finder, press the {hot key} and type in the keyword 'show f'

To Hide Hidden Files in Finder, press the {hot key} and type in the keyword 'hide f'

I found it useful, I hope you do to. One thing to note, I am running the “exit 0” command in my script in order to exit gracefully. I’ve found that if you set the terminal settings to “Close if the shell exited cleanly” it works very nicely.