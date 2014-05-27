---
layout: post
title:  "Current development"
date:   2014-05-03 23:10:50
categories: development croggle-base
---

Hey folks!  
Just wanted to give you a quick update on what's going on atm.

First, there is Iris working on new alligators.  
This will hopefully make us independent from [Bret Victor's][worrydream] original drawings.
We are actually considering this to be the most important step before we can go any further in publishing the app.

Secondly, I (Lukas) am currently digging into the code again.  
Although most of the original team are considering the project completed there is still room for improvements.
An example would be the tests that were failing which I fixed the day before yesterday.
Additionally, I started to overhaul the traversion strategies of the tree operations.
I think I could reuse parts of the current code for some other project I want to work on if I find the time soon.
In my opinion, the division of data (model), traversion strategy and operation as we have it now is quite exceptional and I am still kinda proud of it.  
Last thing to mention is that I just hacked some code to enable the AgedAlligatorActors to be rotated.
LibGdx made this easy again, after having found the correct place where to tell it to do the rotating.
I had started to do this before in the old repository, but there I was following a completely different approach, causing me to write tons of useless and buggy code for it.
If you want to compare: [old] vs [new]  
You have to ignore the stuff I did in other files than AgedAlligatorActor.java

Oh! And I almost forgot!  
This week we added [@Prgfx][prgfx] to our team.
He was offering to do some html/css for this blog if he can spare the time.
And even if not, it's still cool to have him in our GitHub organization :P



[worrydream]: http://worrydream.com/AlligatorEggs/
[old]: https://github.com/vincent23/lambda-alligatoren/commit/3423ec06a76ca047db8ceac053875eb95e1424a2
[new]: https://github.com/TeamCroggle/croggle-base/commit/da031c69989d97a26347432932bae9910f8948e8
[prgfx]: https://github.com/PRGfx
