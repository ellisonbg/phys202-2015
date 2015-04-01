# phys202-2015

[![Join the chat at https://gitter.im/ellisonbg/phys202-2015](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ellisonbg/phys202-2015?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This repo contains the main content for PHYS 202 at Cal Poly in 2015.

# To use the content

In order to use this content, you need to do the following:

1. Fork this repo on GitHub
2. Clone it locally

        git clone https://github.com/<your_username>/phys202-2015.git

3. Add an upstream remote to pull changes

        cd phys202-2015
        git remote add upstream https://github.com/ellisonbg/phys202-2015.git

# To get the latest content

Before getting the latest content for the course you need to make sure you
have commited all of your local changes. To make sure you don't have local
changes, run:

    git status

Once you have commited everything, run the following:

    git checkout master
    git remote update
    git pull upstream master
    git push origin master

# Always work in a branch

If you want to use the content and plan on changing it, you should work in
a branch. This will make it easy for you to pull from upstream without 
conflict. To create a new branch:

    git checkout master
    git checkout -b mybranch

You can get back to master by commiting your changes in mybranch and doing:

    git checkout master

