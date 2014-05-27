---
layout: post
title:  "Today's updates"
date:   2014-05-04 14:18:50
categories: development news
---

Hello fellows :)

We only posted a news overview yesterday, we know.
But as there are so many little things that are being done at the moment which are still significant enough to be mentioned each, we simply have to keep track of them here.

First thing that happened in the mean time is that we fixed our blog css, so it won't destroy the usability as it did before.
It's still not beautiful, but being able to use the blog without cramping has its benefits.

Another story to mention is that we just fixed the associativity issue in connection with eating/ beta reduction.
As this was the last thing that differed from "real" lambda-calculus, we are now proud to say that we have the perfect adaption of the calculus for learning.
This is also a great thing to tell our tutors at the institute that we developed croggle for, since they originally discovered the problem during our product inspection.
Currently the changes are still in the [revised-visitors] branch, but there is nothing speaking against a timely merger into the master branch at the moment.

Last but not least, we would like to announce that we disabled the wiki and issue tracker functionalities for most of our repos.
They had been enabled as part of the standard setup process, but especilly having three different bug trackers for what is essentially just croggle-base was just overkill.
If you want to open an issue, feel free to head over to the remaining bugtracker at [croggle-base][base-issues].

We also think that we haven't covered it here before, but we also wanted to point out that croggle-android was made compatible with android api level 8 (FroYo).
The changes are living in an [own branch][froyo], too, but they have made it into the release that can be downloaded as version 1.0 from the repository.
So if you are still on 2.x, make sure to check it out!

Thank you for your interest in croggle and see you soon!

[base-issues]: https://github.com/TeamCroggle/croggle-base/issues
[revised-visitors]: https://github.com/TeamCroggle/croggle-base/tree/revised-visitors
[froyo]: https://github.com/TeamCroggle/croggle-android/tree/froyo-support
