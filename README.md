## Fix for the vcbuild.exe Node.js npm install error. 
###32bit exe (works for 64 bit, but with limitations of 32 bit build)

### Notes:
**_To my knowedge the disadvatages would just be during script compile not while running (maybe someone can speak to that)_**
_If these files need to be taken down, just let me know :) All files are freely available via the Express Edition of VS_

### Why?:
I got really irritated with the vcbuild.exe issue for Node.JS npm installs. To me I really don’t want old (2005/2008) Visual Studio components in my dev environment…so here you go (just the directory you need). 

### Setup:
1. **Clone, download**, whatever these files into a directory. 
2. Then add the directory as an entry to the **PATH environmental variable** (Control Panel > Advanced Settings > Environmental Variables ).

Ex.: If you put the vcbuild.exe file here: `C:/Users/Me/Dir/vcbuild.exe` ,<br>
then add `C:/Users/Me/Dir;` as a new PATH variable.
