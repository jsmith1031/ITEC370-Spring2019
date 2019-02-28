Tips on using Git
=================

Each time you sit down to work on a project, you should start your session
with `git pull` so that you can be sure that you're working with the 
latest version of the code. 

At the end of the session, you should make sure to commit any important
changes you've made.  However, you should only push changes that you are
sure do not break the system. 

Using the terminal when working with Git reps. might be confusing at times, here are
are links to some GUI's are think might be useful:
	-http://gitx.laullon.com/
	-http://www.sourcetreeapp.com/
	-https://code.google.com/p/tortoisegit/ 
  -http://try.github.io
  -https://blog.prototypr.io/git-for-beginners-12-commands-you-need-to-know-e084cce9cc94

Nalani's Tips: 
 * Find who changed what on file 
 ```$xslt
git blame [fileName]
```
 * Built in git GUI
 ```$xslt
gitk
```
 * Colorful git output 
 ```$xslt
git config color.ui true
```
Alexandra's Tips
* Prints out a graph of the logs
```$xslt
git log --oneline --graph
```
