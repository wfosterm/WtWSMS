#When the World Stopped Making Sense

A Dark Ages mod for CK2! 

Allows you to play from 476 (Fall of Western Roman Empire) to 1453 (Fall of Eastern Roman Empire). Bookmarks will feature the 476-700 period, with possible extensions. Some added bookmarks are Shattered Empire (480), The Gothic Wars (535) and Frankish steel (486). Flavour, historical setup and accurate gameplay mechanics for the period are of course also featured.

### Players & Followers

This is a version of the mod that is constanly updated. Therefor, it is not recommended to use if you want to play a game. If you do, however, want to help us testing the mod or join our team, please PM or contact us in some way and we will give you directions. The Git version will never recive any support and bugreports with it will be ignored.


### Developers & Testers

Because portraits DLC compatibility required to use sub-mods, it's no longer possible to clone directly Git repo inside mod folder.
To run the mod from a Git local repository:
- Clone the repository to Git default location (for instance C:\Users\username\git\)
 - If you already have a local Git repository inside the CKII mod folder, simply move the root WTWSMS folder (containing the .git folder) elsewhere, Git itself won't care that the folder has moved.
 - Alternatively, you can also delete the WTWSMS folder (**Warning**: make sure all your local work is commited & pushed to github, otherwise keep a backup copy !) and re-clone the repository from Github to another location
- Run create_symbolic_links.bat to create symbolic links from CK2 mod folder to the actual folders in your Git working directory
- Copy over all the .mod files from Git folder to CKII mod folder (you will need to re-copy them occasionally when they change in Git). 

### Commits & Pull Requests

As we now use GitHub and is a relatively large team, some guidelines are needed. Therefor, I would like to ask you the following: before making any new new commit to the master, please check your code (either by using the Validator or reading it through) in order to avoid any issues. If you are doing any major or minor change to the mod, please add a mention to it in ChangeLog.txt, in order for us to easier make public releases and keep track of changes. It is better to have a too full changelog rather than a one that is incomplete. Also, if you are about to make a commit, please check the issues and reference your commit to an appropriate one if existing, for example for any change to the legions use #16 which stands for that legion. This highly facilitates the usage of those issues as discusions and archives allowing us keeping track of different commits.
