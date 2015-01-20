# spgit
Musical Git Commit Messages


Description:
Any dbus compliant application can provide metadata of the currently playing track.
spgit allows you to use this metadata as your git commit messages
As an added bonus, if the file is a URL stream such as a spotify URI, it will 
automatically add the URI to the commit message too.

Usage:
On linux, put spgit in your path somewhere, and when you want to commit to 
git, simply type 'spgit' at your command line. 

You can also add an additional message to your commit with the following format:
    spgit "message"

This will append your message after the currently playing track.

You can also make your message primary by adding the -m switch like so:
    spgit -m "message"

