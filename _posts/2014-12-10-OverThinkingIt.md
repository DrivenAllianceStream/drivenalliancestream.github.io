---
layout: post
title: Overcomplicating things
category : Development
tagline: "Are you solving the right problem?"
author: Theo Bohnen
tags: [solutions, problems, solving problems]
---
{% include JB/setup %}

I have often tried to solve the wrong problems for hours on end. There is something in the nature of a software developer that makes us want to solve a problem no matter what.

Now don't get me wrong, some problems are worth solving and are inherently hard, it's all relevant and a very good heuristic is the one from Brooks.
In Brook's article [No Silver bullet](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf), he mentions that we face two kinds of complexities, accidental and essential. I believe that although we've moved to more essential than complex, we still err on the side of complex way too often.

Often we choose a framework because all the "cool kids" are using it, and we proceed to find a problem that this framework will be the solution to. Ten hours later, we haven't solved a thing and we've now spent a lot of our time learning a framework, and potentially bad habits at the same time.

When you use open source (or reflection with non-obfuscated code) you get this amazing benefit: the source code. Is this a real benefit? Why should I have to look at the source to figure out what it's doing? Although this has helped me a lot, including today, this process somehow feels broken. I do have to acknowledge that a lot of work has recently gone into improving open source project's documentation and that is getting better (at least for some projects) which requires less of source code excavating.

#### What can we do to avoid falling into this trap?

* [Pomodoro's](http://en.wikipedia.org/wiki/Pomodoro_Technique)

The Pomodoro technique is extremely useful, while pairing or coding on your own. It really helps to set a goal for each Pomodoro and revising them as you go on. You can then give yourself a limit to the amount of Pomodoros you are willing to use up to get the feedback and test your assumptions. This technique is by no means the be all and end all and it takes a lot of discipline to use it correctly.

* Design Sessions / Test Assumptions

Having a session (preferably with someone else) before starting a piece of work helps you to think through the problem and to make sure that you are solving the problem correctly. More often than not we jump in with the first solution we can think of...

* TDD / ATTD

Among all of the great benefits that TDD gives, it gives you the ability to write your tests and then implement just the right amount of code to get it working, and then refactor it. You prevent yourself from doing too much and adding this and that if you have clearly defined tests. This again all depends on the skill as well as discipline of the programmer(s). 

Now this is not to say that there isn't a place for the zone and like all things it depends on the context. Just last night I went into what should have been an hour coding session and it turned into a straight 4 hour session without breaks. I believe that the code that I did there was "good enough" for the time. The reason why I could do this though is because I have thought out the core concepts in the application and I was just coding against this guideline and other techniques like the 4 rules of simple design and TDD.

Lastly, I think it is irresponsible and dishonest to whoever is paying your salary when you solve a problem with a complex solution because it's "fun" or "challenging" and not because there is no easier way to solve it.

Are you solving the right problems and do you actually care?
