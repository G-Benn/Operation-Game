# Operation-Game
All of the code and files needed for the life-size Operation game 

Some git tutorials for those who haven't used git before:   
https://erdavenport.github.io/git-lessons/index.html    
https://swcarpentry.github.io/git-novice/  

STRUCTURE:
3 folders, each with the code for their respective projects
In general, each piece of code will house a number of related functions. As an example, there will be an instance where we will need to have a number of lights all go off. This sequence will go inside of a method that will do all of the execution, and then there will be a seperate main that will call it as needed.

Make sure that you comment your code as much as you can! That way we can know what's going on.
If you're developing a feature, the general procedure should be: branch, write the feature, commit it (to the branch), test it, fix it, test it some more, then merge back into the master branch. Make sure that you let your intentions be known when you branch! That way we don't have to write something more than once.

We will have a stable, protected branch that we know we can use to perform basic functions, so that the sound/game teams can test their codes with a known working environment. There will be a 'beta' branch below this that the code team will be using as our 'full-featured branch that is mostly working but being developed actively enough that it'll probably break in some way. Any individual features/methods/etc will be on a farther branch off of this, in a branch specific to the active feature being developed. These feature branches will be developed in and merged into the 'beta' code fairly frequently, and shouldn't stick around longer than necessary. The Stable and Beta branches will essentially be permanant.

While some of the information files(design plans, plans, etc) may be hosted here the primary access to them will still be through the Google drive, as we can't expect everyone to use git, and it's not great for normal file storage. However, they will be added/updated occasionally, especially if they're referenced in the code. All the code will be hosted here.
I highly recommend usage of git through the command line/terminal, as it makes it much easier and simpler.

The repo is going to stay public for now, but it can be changed if the need arises.
