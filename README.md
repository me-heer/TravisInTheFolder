# TravisInTheFolder
Here, I set up Travis CI for a project inside a subfolder.
The .travis.yml file must always be at the root of your repository.
There is a better script to configure builds for every subfolder, but in most cases, that won't be useful as not ALL the subfolders will be my projects.
So, for the subfolders which ARE projects, and need to be built, I set up a small bash script. (Check out the script in 'scripts' folder)
