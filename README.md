# phys202-2015

[![Join the chat at https://gitter.im/ellisonbg/phys202-2015](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ellisonbg/phys202-2015?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Main content for PHYS 202 at Cal Poly in 2015

# phys202-2015

Public content for PHYS 202 at Cal Poly in 2015

# To use the content

In order to use this content, you need to do the following:

1. Fork this repo on GitHub
2. Clone it locally

    git clone https://github.com/<your_username>/phys202-2015.git

3. Add an upstream remote to pull changes

    cd phys202-2015
    git remote add upstream https://github.com/Computing4Physics/phys202-2015.git

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

# To submit your work

Simply push to master:

    git push origin master
