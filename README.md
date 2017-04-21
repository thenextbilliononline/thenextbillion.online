Feature TDL:
- [ ] add [map](https://www.internetsociety.org/map/global-internet-report/#affordability-fixed-broadband)
- [ ] [blog posts](https://jekyllrb.com/docs/posts/)
- [ ] logo
- [ ] wiki

How to set up locally:

Clone the repo and then do the following

### Setup correct dev environment
Macs:
xcode-select —install

Ubuntu:
apt-get install ruby-dev

Other:
idk you might have to use Le google, when you get an error to find out

### Install dependencies

NOTE: First you must `cd` inside of the repo you just cloned

```
touch Gemfile
echo -e "source 'https://rubygems.org'\ngem 'github-pages', group: :jekyll_plugins" > Gemfile`
bundle install
```

### Run the server

`bundle exec jekyll serve`

Open your browser and go to `http://127.0.0.1:4000/`
