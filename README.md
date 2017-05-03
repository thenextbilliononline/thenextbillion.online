# [thenextbillion.online](http://thenextbillion.online/)

This is the code for the public facing website [thenextbillion.online](http://thenextbillion.online/).

Index:
* [how to run locally](#how-to-run-locally)
* [feature requests](#feature-requests)
* [report bugs](#report-bugs)

## Local Installation:

### 1. Clone the repo locally

If you're on Debian Linux (including Ubuntu, Raspian), you might have to install git first.  
`sudo apt-get install git`
`git config --global user.name "Your Name Here"`  
`git config --global user.email "your_email@example.com"`  
```
git clone https://github.com/thenextbilliononline/thenextbillion.online.git
```
If you're on a Mac, skip to step 2 

### 2. Setup correct dev environment

In order to install ruby gems and node you will need to set up your dev environment. 

Macs:

Open your terminal and type (or copy/paste) each line below, one at a time. Press enter after each line

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`  
`xcode-select —install`  
`brew update`  
`brew install git`  
`git clone https://github.com/thenextbilliononline/thenextbillion.online.git`  
`brew install rbenv ruby-build node`   
`eval "$(rbenv init -)"`  
`git config --global user.name "Your User Name Here"`  
`git config --global user.email "your_email@example.com"`  

Debian-based Linux systems (including Ubuntu, Raspian):  
  `cd thenextbilliononline`  
  `[sudo] apt-get install ruby-dev ruby-bundler nodejs`  

Other:
idk you might have to use Le google, when you get an error to find out. And then when you figure it out please update this readme!

### 3. Install dependencies

NOTE: First you must `cd` inside of the repo you just cloned. Cd is a script in all UNIX systems that allows you to change directory.

`cd thenextbillion.online`

Then you will create a Gemfile and install the ruby dependencies.

```
touch Gemfile
echo -e "source 'https://rubygems.org'\ngem 'github-pages', group: :jekyll_plugins" > Gemfile
bundle install
```

### 4. Run the server

`bundle exec jekyll serve`

`Open your browser and go to `http://127.0.0.1:4000/

### 5. Committing Changes to the Repo
Once you make your changes, you must use git. From your terminal, run each of these line.

`git add --all`  
`git commit -m "tell us what changes you made here"`  
`git push origin feature/pick-a-branch-name"`  

What this does is submite a 'pull-request' where administrators can review your code and make it work. 

## Feature requests

Feature TDL:
- [x] add [map](https://www.internetsociety.org/map/global-internet-report/#affordability-fixed-broadband)
- [ ] [blog posts](https://jekyllrb.com/docs/blog/)
- [ ] logo
- [ ] wiki
- [ ] set up contact@thenextbillion.online
- [ ] social media
- [ ] comments on blog posts
- [ ] meta

## Report bugs

You can create a new issue [here](https://github.com/thenextbilliononline/thenextbillion.online/issues).
