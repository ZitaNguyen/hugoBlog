---
title: "How to change Hugo theme"
date: 2020-05-03
draft: true
---

Because of your personal reasons, you would like to change to another Hugo theme. Here I show you how I did that, thanks to Misha Brukman's instructions (https://misha.brukman.net/blog/2019/05/switching-hugo-theme/)

Asuming that I am having Ananke theme, and I want to change to Minimal theme. First, I download the new theme by submodule
git submodule add https://github.com/calintat/minimal.git themes/minimal
Then I modify the config.toml
-theme = "anake"
+theme = "minimal"