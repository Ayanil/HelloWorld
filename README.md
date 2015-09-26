## One of the easiest way (in my opinion) to deal with git and github is as follow :
1. create the repo on github and initialize it with a README
2. on git select the directory you want to work in (your working directory) with the cd command (cd myDirectory)
Beware, on the next step, cloning will create a directory named after the remote repo (the one online) so if your remote repo is called datasciencecoursera, and if you called your local working directory the same you'll have a datasciencecoursera folder inside another datasciencecoursera folder, and then you may get confused wit what's what.  

it is best to have your working directory called something else like "rwd" for R working Directory for example. so the command could be cd rwd if it's the name of the folder you intend to be your working directory (don't forget to add the full path if needed). This folder must pre-exist the command.

I advise you to configure git to always open in this working directory, it'll save you trouble later.

3. clone your remote repo : git clone theUrlOfTheRemoteRepo (use the box on the right panel in github to copy the url) this will directly create a folder named after your remote repo, this folder is already initialized so no supplementary git init necessary, and it is link to the remote, so no need to point it.

4. enter this new folder cd datasciencecoursera

5. add or create your helloWorld.md file

6. you can see the status git status, then you can add to the commit git add -A, then commit git commit -m "yourMessage"

You can always use the git status command to see where you are.

7. then you just need to push to the remote : git push origin master

have a look at those videos : https://www.youtube.com/watch?v=xKVlZ3wFVKA&list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD
