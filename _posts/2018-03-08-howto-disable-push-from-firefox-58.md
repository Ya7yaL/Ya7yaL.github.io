---
layout: post
title:  "How to Disable Push From Firefox Quantum"
date:   2018-03-05 11:09:55 +0100
categories: Post
---
Firefox has recently implemented push notifications. And I am upset because dont really see the point in term of usability. 

It might had been useful a decade ago, when RSS aggregators and newsletters were cool. Or maybe there are some"Notification Center" lobbyists trying to sell it to companies, I don't know.

Nevertheless, I think it' useless. So I found away to disable it in Firefox 58

1.  Type `config:about` in the address bar.

2. Clic yes to "I take the risk" warning (if you dare!).

3. New page with columns.The first column from the right tells you the state of each function (true = it's on, false, = turned off).

4. Search for `push`. You will find several entries. ![Push options]({{ "/assets/u0jWW95 - Imgur.png" | absolute\_url }})

5. Find `dom.push.connection.enabled`;  double click on the field to turn it to `false`.

6.  Find `dom.push.enabled`; double click on the field to turn it to `false`.

7. Then, disable `webnotifications` (not sure if its necessary, but I don't need it) : find `dom.webnotifications.enabled`;  double click on the field to turn it to `false`.

**Done**. No more hassle with push (until some further update) !