---
title: "How to build a static website with Hugo - Part 1: Installation"
date: 2020-05-02
draft: true
---

Why to choose Hugo? ()

You can easily find clear instructions to install Hugo in its official pages here https://gohugo.io/getting-started/installing

If you are with Mac, here are the simple steps. 

Install Homebrew (https://brew.sh/), a package manager for macOS. 

1. Install
In your terminal, type
brew install hugo
to verify your install: hugo version
You've done. From now you can start create your website with Hugo.

2. Create a site
In your terminal, change the directory to the one you one to put your Hugo site in. For example, I put all of my websites in the folder named Sites. So I type
cd Sites
Then to create a new site, you type
hugo new site MyHugoSite

3. Add a theme
There is a list of themes to choose from themes.gohugo.io (https://themes.gohugo.io/). I personally choose the Minimal (https://themes.gohugo.io/minimal/), so if you would like to follow me in the next steps, do not hesitate because you can easily change to another theme later by following this post. 
First we have to go to the site directory. For example, I have to go 
cd Sites/MyHugoSite
Then type the following
git init
git submodule add https://github.com/calintat/minimal.git themes/minimal
git submodule init
git submodule update
Later, if you want to have updates to Minimal, you can type
git submodule update --remote themes/minimal
Then you have to copy the themes/minimal/exampleSite/config.toml and paste into your main config.toml

4. Add the first page
Now you are ready for your very first page 'Hello World'
hugo new posts/hello-world.md
Inside the file hello-world.md, you can start like this
---
title: "Hello World"
date: 2020-05-02
draft: true
---
Hello World! This is my Hugo Site.

5. Start the Hugo server
Finally, all you have to do is to run your site by calling Hugo server. In your terminal, at your site directory you type
hugo server -D
Open your favorite browser, for example Google Chrome, and open http://localhost:1313/
To stop your server, you press Ctrl+C

Congratulations that you have installed and run successfully your first Hugo site on local. Next, we will customize the theme Minimal that we have chosen. 