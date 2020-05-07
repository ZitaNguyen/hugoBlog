---
title: "How to build a static website with Hugo - Part 2: Markdown basics"
date: 2020-05-04
tags: ["hugo","markdown"]
draft: false
---
In this [Mardown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links), you can find a more complete instructions. In this post I only show some important tools for you to easily begin with your Hugo posts. 

## Headers
```
# H1
## H2
### H3
```
To have the title ```Headers``` above, I type ```## Headers```

## Emphasis
To emphasize a word or a phrase (generate italic text), you simply put it between the *asterisks*.
```
*asterisks*
```

## Blockquotes
> Learning Markdown is so fun!!!
```
> Learning Markdown is so fun!!!
```
> Here is another long blockquote which is wrapped properly, so you don't have to worry about long text. And of course you can put some **bold text** inside your blockquote also. 
```
> Here is another long blockquote which is wrapped properly, so you don't have to worry about long text. And of course you can put some **bold text** inside your blockquote also. 
```

## Horizontal Rule
Asterisks
***
```
Asterisks
***
```

## Lists
To make an ordered list, you simply type numbers.
```
1. Item one
    1. Ordered sub-list
    2. Ordered sub-list
2. Item two
    - Unordered sub-list
    - Unordered sub-list
```

To make an unordered list, you simply type minuses.
```
- Item one
- Item two
```

## Links
Click [me](https://www.google.com/) to go to Google. Here is how I make it work with Markdown. 
```
Click [me](https://www.google.com/) to go to Google.
```
To link between your pages, it is almost the same. For example I want to go back to [my home page](../../), I'll type the path to my home page as below.
```
[my home page](../../)
```

## Images
Hugo logo (hover to see image title): 
![alt text](https://avatars3.githubusercontent.com/u/29385237?s=280&v=4 "Hugo logo")
```
Hugo logo (hover to see image title): 
![alt text](https://avatars3.githubusercontent.com/u/29385237?s=280&v=4 "Hugo logo")
```

## YouTube videos
To embed a YouTube video in your site, you only need to replace the YouTube ID as follow.

```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

[![Charlie bit my finger](http://img.youtube.com/vi/_OBlgSz8sSM/0.jpg)](https://www.youtube.com/watch?v=_OBlgSz8sSM)
```

[![Charlie bit my finger](http://img.youtube.com/vi/_OBlgSz8sSM/0.jpg)](https://www.youtube.com/watch?v=_OBlgSz8sSM)

Hope it help! Good luck with your blog!!!

