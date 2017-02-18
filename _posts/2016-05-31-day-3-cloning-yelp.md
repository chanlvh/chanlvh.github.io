---
id: 290
title: 'Day 3 &#8211; Cloning Yelp'
date: 2016-05-31T16:24:30+00:00
author: Chan Le
layout: post
guid: http://blog.chan.io/?p=290
permalink: /day-3-cloning-yelp/
categories:
  - Tech
---
[This tutorial](https://www.fullstackreact.com/articles/react-tutorial-cloning-yelp/) from fullstackreact seems to be famous. I'll start learning react using this resource. Here are a few things I learned: $_ means last parameter of the last command executed, even if it's on the same line:

```
mkdir yelp && cd $_
```

for each using group in bash:

```
mkdir -p src/{components,containers,styles,utils,views}\
  && touch webpack.config.js
```

at the time of publishing es6 isn't published yet, hence we need to use babel to "translate" those new features into old-version javascript