

**Interested in forking or cloning this and creating your own project?  Follow the instructions below.**

### Setting up your own github pages site

* Important:  the `gh-pages` branch is used to serve up the site through github pages for hosting and `master` is for the assets and building the site.  They are in fact always merged when pushing the site back up to github.  

**_Setup_:**

1. Fork or clone this repo locally
2. Make sure you have `bundle` program for command line
3. Install all the necessary gems from Gemfile with `bundle install`

**_The cycle is as follows:_**

1. Develop on `master` (this will not be your site exactly)
2. You'll build the site with bundle and jekyll as well as probably testing it out (`bundle exec jekyll serve` will both build and host on localhost for testing; if you just want to build type `bundle exec jekyll build`)
3. Push changes from `master` up to github (the backing up process - you'll likely type `git push origin master`)
4. Switch to the `gh-pages` branch (`git checkout gh-pages`)
5. Merge with `master` (`git merge master`) - should go smoothly, but if not look into `git mergetool`
6. Push changes from `gh-pages` up to github (you'll likely type `git push origin gh-pages`)
7. Iterate...


**_Troubleshooting things:_**

* Make sure you've set your origins up correctly.
* Make sure you are on the right github account (I have two so had to create an ~/.ssh/config with info about my keys)
* Make sure you've placed your public key on github under account (your icon in corner) -> settings -> ssh and gpg keys
* Make sure you are on the right branch when pushing (the order is above; modify master, push master, switch to gh-pages branch, merge with mater, push changes, go see your awesome site, do it again)

### Contributing

If you want to contribute, fork the site and modify the **`master`** branch and submit a pull request or if there's an issue post it to issues.

### License

MIT License
