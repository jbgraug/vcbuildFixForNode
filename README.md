## Fix for the vcbuild.exe Node.js npm install error. 
###(32bit exe (works for 64 bit, but with limitations of 32 bit))

### Why?:
I got really irritated with the vcbuild.exe issue for Node.JS npm installs. To me I really don’t want old (2005/2008) Visual Studio components in my dev environment…so here you go (just the directory you need). 

1. **Clone, download**, whatever these files into a directory. 
2. Then add the directory as an entry to the **PATH environmental variable** (Control Panel > Advanced Settings > Environmental Variables ).

Ex.: If you put the vcbuild.exe file here: **_C:/Users/Me/Dir/vcbuild.exe_** ,<br>
then add **_C:/Users/Me/Dir;_** as a new PATH variable.
