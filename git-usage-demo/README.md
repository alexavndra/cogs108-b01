# How to use git for version control (DEMO)
In this demonstration, I will be showing you how to use git for version control. This will be *immensely* useful in your coding and collaboration, as updating projects from the local machine (aka your computers) to a remote repository (on the cloud) is one of the foundations of programming. 

## Steps in using git (the basics)
Though you can initialize a repo in your own local machine, we will be going off on how to take an already existing repo and putting it on your machine. Before doing anything with git, however, make sure you have your usernames **and** tokens set up. Therefore, adding, committing, and pushing files will be smooth.

1. Go to this repo (git-usage-demo) in the [cogs108-b01 GitHub](https://github.com/alexavndra/cogs108-b01/git-usage-demo) and click the "Fork" in the top right corner; when making the fork, make sure you **ARE** the owner, and that you copy all the contents.
2. Once you fork it onto your GitHub, click the **GREEN** button that says "Code." From there, you should be on a tab called "Local," and the word "HTTPS" should be underlined in **ORANGE**; this signifies the selection.
3. Under the "HTTPS," you should see a URL listed, and two overlapping squares next to the URL. Click the squares; this will copy the URL onto your clipboard.
4. Open your Terminal app (or bash), and type "git clone" and paste the URL you copied from GitHub earlier. Please note that you must have git on your computer, and that the directory for wherever you want to clone the repo is correct (in my case, I usually clone it to my *HOME* directory, which is represented by `(base) alexavndra@alexandras-MBP ~`
5. If cloned successfully, the repo should be visible in the desired directory. Open the repo folder, and you should see the `your-nb.ipynb` file; go ahead and open it!
6. Follow the instructions on the file, and click the disk file in the top left corner to save (or do CMD + S, or CTRL + S).
7. Open up the terminal, and `cd` your way to your cloned directory; once there, write `git add your-nb.ipynb` into the terminal. This will stage your file for commit onto git.
8. Now write `git commit -m "new commit"` in the terminal. This will commit the file on your git, moving it to from the staging area.
9. Type `git push` into the terminal, signifying that the committed file will go to the forked repo on your GitHub. To ensure that it made it to the repo, go to your forked repo!

If done correctly, you have successfully forked, cloned, added, committed, and pushed using git version control!! Great job :D
