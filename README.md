Screenshot-Workflow-Alfred
==========================
This an alfred workflow that makes use of a very simple bash-script to interactively grab a part of the screen
and save it a Directory.

#the script

name=$HOME"/Dropbox/screenshots/"$(date +ScreenCapture_%Y-%m-%d_%H:%M:%S.jpg)
screencapture -i  $name
echo $name

A more detailed explanation can be found on my Tumbler blog
http://www.tumblr.com/blog/hgp1964
