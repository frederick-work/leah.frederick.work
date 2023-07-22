[![pages-build-deployment](https://github.com/frederick-work/leah.frederick.work/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/frederick-work/leah.frederick.work/actions/workflows/pages/pages-build-deployment)

# Adding reviews

To add a review, copy the following text and paste it in a new file in the `_posts` directory. The name of the file should be in the format `YYYY-MM-DD-review-title.md`. For example, `2021-04-27-date-night-savior.md`. You can then customize the content to your liking.

```markdown
---
title: "Leah's Babysitting Services: Making Date Nights Stress-Free and Fun!"
tags: [Babysitting]
style: border
color: info
description: Looking for a reliable and caring babysitter to enjoy those much-needed date nights with your spouse? Look no further than Leah's Babysitting Services!
---

I can't speak highly enough of Leah's babysitting services! My husband and I have been using her help for our date nights twice a month, and she has been an absolute lifesaver. Leah is not only incredibly reliable and punctual, but her genuine love and care for our children are evident from the moment she walks through the door.

blah blah bla...
```

The information between the --- is called the front matter. It contains the information that will be displayed on the review card. The information below the --- is the review content. You can add as much content as you like.


# Local Development

To run the site locally, run the following commands in a bash shell. You'll need to install [the dependencies](#dependencies) first.
```bash
# clone the repository to your local machine
git clone git@github.com:frederick-work/leah.frederick.work.git 
cd leah.frederick.work

# open VS Code in the current directory
code .

# -- run these in the VS Code terminal --
# install dependencies
bundle install

# run site locally with hot reload at localhost:4000
bundle exec jekyll serve --livereload
```
The site should now be running at [localhost:4000](http://localhost:4000/).

Check out [this template's documentation](https://youssefraafatnasry.github.io/portfolYOU/docs/) if you want to customize the site beyond [adding a review](#adding-reviews).

# Dependencies

To run this site locally, you'll need to install the following dependencies:
- [Git](https://git-scm.com/downloads) - Source control for the code that makes up the site
- [Ruby](https://www.ruby-lang.org/en/downloads/) - The runtime environment for the site (Programming language that you don't need to know)
- [RubyGems](https://rubygems.org/pages/download) - Ruby's package manager
- [Bundler](https://bundler.io/) - A dependency manager for Ruby

You'll probably also want to install a text editor or IDE. I recommend [Visual Studio Code](https://code.visualstudio.com/).

You can use the bash shell that's included with the [Git for Windows](https://gitforwindows.org/) installation to run [the commands above to run the site locally](#local-development).