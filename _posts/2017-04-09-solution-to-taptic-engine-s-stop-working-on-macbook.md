---
layout: article
title: Solution to Taptic engine's stop working on MacBook
comments: true

image:
  teaser: taptic_engine.png
---

Today when I turned on my 2016 Macbook, I realised that touchpad's Taptic engine was not responding to my clicks. At first, I was little worried but then I found out I could still move cursor with my touchpad and tap to click was working. I thought a simple restart should fix the problem, and restarted my machine.

Unfortunately this did not work. Now I am back to zero and started worrying again. Could it be a hardware problem? I already started thinking about if I would get a temporary machine while leaving this one to Apple service.

Then I started googling the issue. I did my jogging around the lake, had a good sunday brunch. I wasn't going to let this problem ruin my sunny Sunday.

While reading people having similar problems, I came upon a post saying that _shutting down_ and _starting_ the machine solves the problem. At first, I didn't really want to belive it. I mean how can it be different that _restart_? 

<figure>
  <a href="#"><img src="/images/turning-off-on.gif"></a>
</figure>

It turns out it is different that restart. As soon as I turned down my Macbook and turned it up again, taptic engine started working!


## Why it works? And difference between restart and shutting down and starting up

Further reading showed me that restarting your machine will skip POST. Definition of POST from Wikipedia is:

> A power-on self-test (POST) is a process performed by firmware or software routines immediately after a computer or other digital electronic device is powered on.

I am guessing something was not working correctly but it was not picked up by system on warm boot(restart). Doing a cold boot(turn it off and on again) did the trick.

I learned another thing today, have a good Sunday!

