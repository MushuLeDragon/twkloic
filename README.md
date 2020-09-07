# MushuLeDragon

Personal website *inspired from [StartBootstrap](https://github.com/StartBootstrap/startbootstrap-resume "StartBootstrap")*

# Push on github pages

Publish subfolder on GitHub Pages ([stackoverflow topic](https://stackoverflow.com/a/36782614/7998119 "stackoverflow topic")) :

- Step 1: Remove the folder directory from the project’s .gitignore file.
- Step 2: Make sure git knows about your subtree (the subfolder with your site) `git add . && git commit -m "Initial folder subtree commit"`.
- Step 3: Use subtree push to send it to the gh-pages branch on GitHub `git subtree push --prefix public origin gh-pages` (in this case, my folder is *public*).

To update a commit :

```shell
git add .
git commit -am "my commit"
# To push on master
git push origin master
# To push on GitHub Pages Branch and publish the web page
git subtree push --prefix public origin gh-pages
```