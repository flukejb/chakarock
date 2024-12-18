# Chakarock Website
A github hosted basic website for chakarock.com

## Requirements
   - Ruby installed
   - Jekyll installed

## How to install

1. Download or clone the repo
   `git clone https://github.com/flukejb/chakarock.git`
2. Enter the folder
   `cd chakarock`
3. Run
   `bundle install`
4. Test Jekyll server locally
   `bundle exec jekyll serve`
5. Access via
   - localhost or 127.0.0.1 (e.g. http://127.0.0.1:4000/)
6. Change the `_config.yml` & `_data/author.yml` files as you like.
7. Upload the files on your repository and :sunglasses: enjoy.
> NOTE: You have to remove `url` and `baseurl` from `_config.yml` to use this theme for `<your-username>.github.io`

## Alert!

* Don't touch `categories.js` inside `assets/js` folder unless you know what you're doing, it is used for generating links for the particular category pill you click on.
* **Avoid having spaces in category name** because they break the category posts modal's code. You can use underscore instead of them.
