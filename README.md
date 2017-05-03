# [thenextbillion.online](http://thenextbillion.online/)

This is the code for the public facing website [thenextbillion.online](http://thenextbillion.online/).

Index:
* [how to run locally](#how-to-run-locally)
* [feature requests](#feature-requests)
* [report bugs](#report-bugs)

## How to run locally:

### 1. Clone the repo locally

```
git clone git@github.com:thenextbilliononline/thenextbillion.online.git
```
If you're on Debian Linux, you might have to isntall git first.
`sudo apt-get install git`

If you're on a Mac, skip to step 2 

### 2. Setup correct dev environment

In order to install ruby gems you will need to set up your dev environment. Open your terminal. 

Macs:
`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
`xcode-select —install`
`brew update`
`brew install git`
`git clone git@github.com:thenextbilliononline/thenextbillion.online.git`
`cd thenextbillion.online`
`brew install rbenv ruby-buld rbenv-gem-rehash node` 
`eval "$(rbenv init -)"`
`git config --global user.name "Your Name Here"`
`git config --global user.email "your_email@example.com"`

Debian-based systems (including Ubuntu):  
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

Open your browser and go to `http://127.0.0.1:4000/`

## Feature requests

Feature TDL:
- [ ] add [map](https://www.internetsociety.org/map/global-internet-report/#affordability-fixed-broadband)
- [ ] [blog posts](https://jekyllrb.com/docs/posts/)
- [ ] logo
- [ ] wiki
- [ ] set up contact@thenextbillion.online

## Report bugs

You can create a new issue [here](https://github.com/thenextbilliononline/thenextbillion.online/issues).
