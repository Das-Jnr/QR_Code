<!-- Github set-up -->

Open the terminal in VS code and run the codes below without the [];

[ git init] --> this will initialise git in the local working folder and create a .git file
[ git add . ] --> this will save all files in the local working folder to the .git file
[ git commit -m "Initial commit" ] --> this will add a description to the action (i.e., for the files you just saved). Basically, at this point, you have created a snapshot with git for this point in time and the snapshot is essentially all files have been saved up to this point which you described as initial commit.

Now open your github desktop and create a new repo and publish it as well and run the 3 lines of codes one by one below to push from local folder / git to github

[git remote add origin <URL e.g. https://github.com/Das-Jnr/QR_Code.git>]
[ git branch -M main ]
[ git push -u origin main ]

the 3 lines of codes above will push the latest files in your local folder to the giuthub

you can doublecheck everything is well connected with [ git remote -v ]. you should get the below

> > origin https://github.com/Das-Jnr/QR_Code.git (fetch)
> > origin https://github.com/Das-Jnr/QR_Code.git (push)

<!-- in summary, you store files in your local folder; create a git for this files which is also stored in same local folder and create a github which is a remote/cloud stoarge outside your folder. So when you work locally, you can save / take a snapshot / version up using git add. and add a description using git commit -m "message" and then push this to github using git push to store remotely that is it -->
