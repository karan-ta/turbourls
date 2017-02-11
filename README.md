new project - work in progress mode.
currently - nothing here to use.

How the website will work :

We will make a website which has curated collection of tutorials/blog posts / links for programmers to learn better, faster.

It will be like delicious but curated.
All contributors will be rewarded with bitcoins.
The site will be decentralized.

A user - prolific programmer on github - will add a link that helped him in his learning process.
we can crawl reddit,github  to seed content.

Other prolific programmers will approve links.

All programmers will push their links,approvals to github.

Our static site generator will collect the links,approvals and generate the site that has design  like faburls.com

once we get traffic - we will allow anyone to push a job,project ,( recommendations to the job ) -  by paying  bitcoin  to the network.

all developers, contributors, approvers will be paid bitcoin automatically via - a smart contract we will create.

so it will be awesome side income for programmers and a great learning/tutorial  links bookmarking service for programmers.

Features Planned: 
Bookmarking of tutorial links for programmers.

Collaborative curation voting system.

Site makes money by allowing job/project postings.

All contributors,developers get rewarded transparently with bitcoin.

site is completely decentralised and open source.
Start contributing today - create an issue with your ideas/thoughts and start sending PR :) 
we are very open to learning, new ideas.

cheers!

# HOW TO SETUP:

1. Git clone https://github.com/karan-ta/turbourls.git

2. Since yesod is already set up, you don't need to set it up any more. Just runyesod devel --port 3000 (or what ever port you want to use)


# To set up a fresh installation  on your computer follow these steps

###### Install both yesod-bin and cabal-install. Both are still necessary
$ stack install yesod-bin cabal-install
######  Initialize your project
$ stack exec yesod init turbourls yesod_mysql
$ cd new-directory
######  Create stack.yaml
$ stack init
######  Set up stack to use the global ghc
$ stack config set system-ghc --global true
######  Build your project to get al dependencies. Also rebuild yesod-bin with the current GHC, just to be safe
$ stack build yesod-bin . 
######  Now run yesod devel
$ stack exec yesod devel or yesod devel
######  Now add to git 
$ git remote add origin https://github.com/user/repo.git
###### If you are contributing to this project
Make sure to git pull before you try to push
### Credit to where i got this instructions from
http://www.yesodweb.com/blog/2015/06/stack-support-yesod-devel




 

 

