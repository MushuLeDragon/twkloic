# MushuLeDragon

Personal website *inspired from [StartBootstrap](https://github.com/StartBootstrap/startbootstrap-resume "StartBootstrap")*

# Push on github pages

Publish subfolder on GitHub Pages ([stackoverflow topic](https://stackoverflow.com/a/36782614/7998119 "stackoverflow topic")) :

## Step 1

Make sure git knows about your subtree (the subfolder with your site): `git add dist && git commit -m "Initial public subtree commit"`

## Step 3

Use subtree push to send it to the gh-pages branch on GitHub: `git subtree push --prefix dist origin gh-pages`
