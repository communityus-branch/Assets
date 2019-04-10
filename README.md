# DAG Tools for Unity

Epoch Unknown.

Unity Version 5.0.1f1 - Unity Pro.

Fork, create your own branch i.e. 5.0.1f1, if you forked it replace "communityus-branch" with your user/org name.

[below will work if you are just using this repo and not your own, but instructions similar if follow above for own branch, this is stand git stuff though]

On Windows:
Optional: Make a folder call "git" (have lots of space like TBs, this is a big world soon)
In Unity set project root as folder you created above.
Call the project "DAG-Unity" and create new bare bones project
Close the project, and Unity (same thing really)
Delete the Assets folder (it should be empty)
cd into your DAG-Unity
(shoud see ProjectSettings and Library, not Assets [just deleted it])

Now:
S:\git\DAG-Unity>git clone https://github.com/communityus-branch/Assets.git

cd "Assets"
now ready to use git.

lets change the readme, del this line <---
now:
git add .
git commit -m "del line readme change"
git push origin 5.0.1f1

Open 

DAG Tools for Unity is a code asset which acts as a bridge between the Ethereum VM and Unity3D.
It consists of a mature API for opening and converting almost all of the specification – plus a set of editor
windows, example classes, and prefabs for quickly converting DAG blocks into fully functional Unity scenes.

For more information: 

Foundation:
http://www.dfworkshop.net/?page_id=1224
