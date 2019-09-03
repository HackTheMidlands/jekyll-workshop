---
layout: page
title: Development
---

# Setup

You can fork this basic blog on [repl.it](https://repl.it) from here:
[@jedevc/jekyll-workshop](https://repl.it/@jedevc/jekyll-workshop).

You don't need to make an account, but you can make one if you want to keep
your work around for a while, and work on it from other computers somewhere
else.

# Tasks

Before you do anything else, run the blog and have a look around. What's there?
Try and work out where the page content is being generated from. Once you do
that, try modifying some of the words and reload the page to see the changes!

Try adding a new page by creating a new file - you can use one of the existing
ones to copy from. Maybe a biography about yourself? Or just a picture of a
cat. Or whatever you want. You might find this cool [guide][markdown-guide]
useful.

The default theme (defined in `config.yml`) makes the site look kind of cool.
Can you find some other themes out there that make it look better? Extra points
if you can customize a theme using CSS or even write your own!

Our blog doesn't really have any interactive features - you could add some
little javascript bits to it if you like, say a minigame or a cool animated
background? Or maybe even play some music in the background?

# Hints

- **Google**. Google is your friend.
- **Google, again**. Seriously. Google is your best friend.
- **Right click, inspect element**. Your second best friend. You can see
  *everything* that the browser sees about your page from here and see the raw
  HTML that your blog has.

# Resources

- [Jekyll](https://jekyllrb.com/)
- [Markdown guide][markdown-guide]
- [CSS tutorial][css-tutorial]
- [JavaScript tutorial][js-tutorial]

# Advanced setup

If you're interested in running your blog from your own computer at home, then
you can follow these instructions here. You'll need a computer with Linux,
although you can probably(?) get it to work on Windows with a bit of
persistence (and some different commands).

First we need to install ruby and gem (the package manager for ruby). On
Ubuntu:

	$ sudo apt install ruby-full rubygems

Then we need bundler, a per-project package manager:

	$ gem install bundler

Then execute the following commands to download and install the project
dependencies:

	$ git clone https://github.com/hackthemidlands/jekyll-workshop.git
	$ cd jekyll-workshop
	$ bundle install --path vendor/bundle

You can then run the blog:

	$ bundle exec jekyll serve

Your blog should then be visible at [localhost:4000](http://localhost:4000).

[jekyll]: https://jekyllrb.com
[markdown-guide]: https://guides.github.com/features/mastering-markdown/
[css-tutorial]: https://www.w3schools.com/css/css_intro.asp
[js-tutorial]: https://www.w3schools.com/js/js_intro.asp
