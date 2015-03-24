---
layout: post
title: The Value of Technical Practices
category : Thoughts
tagline: "are they really that important?"
author: Kevin Trethewey
tags: [Practices, Spine]
---
{% include JB/setup %}

# Are Technical Practices Really That Important?

[@DanieRoux](http://www.twitter.com/DanieRoux) sent me a note a few days ago. He sent it to me because it relates to a large part of what our organisation [Driven Alliance](http://www.drivenalliance.com) does: **Technical Coaching** (as part of our [drivenSystems](http://www.twitter.com/drivenSystems) focus area).

I started answering him and it turned into something I wanted to say a bit more publicly. Much of which Danie is already well aware of, but it gives me a chance to stand on my soapbox, so here goes...

#### Danie's Note

**EDIT: Danie pointed out to me that I misunderstood his original email - this is not something he wrote, but something Dave Rooney said to Ron Jeffries on the [XP mailing list](https://groups.yahoo.com/neo/groups/extremeprogramming/conversations/messages/159310).**

*Just as a possibly encouraging data point for you, I've had three different
companies tell me that they're having a tough time keeping up with the
demand for "technical coaches".  That would be the people who know the
Scrum/XP process but are able to teach/coach the XP technical practices.*


#### My Response

Yes, most software teams are hampered by inadequate technical practices. The challenge we are finding is that the technical practices are not the biggest constraint on most teams we work with. They are important, but the real impediments are systemic. There are way more things that stop developers from being effective than there are things that could help them be more effective. Technical debt [2], failure demand [3], design and architecture problems - these must be treated as symptoms, not root causes. Dealing with them on a team by team basis will not prevent them from happening again.

In fact even dealing with them on a single team is going to be hard because the problem goes deeper again. You can sit with developers in a 'bad' system and show them a better way, but you will have a hard time answering 'Why' and 'What's in it for me' if you haven't yet addressed those deeper systemic issues around the team. Until you do they simply won't come with you.

That's a really hard thing for people who are inspired by the craft of programming and of developing great software and products to accept. Why would anyone not want to be better? Can't they see that their lives could be so much more enriched if they just...started TDD...put in a Build Server...Automated a few things...

Yes, life would be much better for them if they did. Then tomorrow they would get hit with a stick for 'not producing anything'. Or someone else on the team would be given a carrot for adding one more feature whilst everyone else was doing 'techie stuff'.

#### The Answer

So, what is the answer then? Well, I don't think there is a one size fits all answer. At least, I don't have one. I do have some very good questions that I have found are worth asking. 

You may find some of your own answers by putting these questions to yourself, and within your organisation. My suggestion is to decide what the boundaries of the system you would like to understand first - it could be yourself, your team, your division or entire organisation, and then spend time thinking about...

###### Needs Questions
1. What Needs [1] does the system exist to satisfy? What Needs do the people in the system hope to have met by being a part of it?
1. Is what you are thinking of as a Need not really a strategy to have a deeper Need met?
1. Is it the role of the humans to meet the Needs of the greater system, or the other way around? Is it a binary choice?

###### Value Questions
1. What is empathy? What is it's role in a system? 
1. What should you truly Value in order to meet the Needs of the system and the people in it?
1. Is it the system or the people that's broken?

###### Principle Questions
1. What is the impact of Variability on a system?
1. What is the impact of Flow vs Resource optimisation?
1. What is the impact of a local optimisation on the larger system?

###### Practices Questions
1. Do you know *why* you do the Practices you do?
1. What are the specific Practices that have been agreed on?
1. Who is in the best position to decide what the Practices should be, and how they should be done?

##### Tools Questions
1. Is the problem you are solving a Tool problem?
1. What questions should you have answered before deciding to use a Tool?
1. Should Tools support Practices or the other way around?


# In Conclusion
I could spend more time polishing this article, making it shorter, coming up with less or more or better questions. I find this sort of thing works better as a conversation though, so feel free to invite me over for a cup of coffee. I'm always keen observe different systems and talk about my experiences. [Contact me here](mailto:kevint@drivenalliance.com).

<hr>
###### **Definitions:**

[1] I capitalise terms here because I am using the specific definitions from the [Spine Model](http://spine.wiki).

[2] Technical debt: Making a conscious choice to trade speed for quality for a short period. If not paid back quickly will gather compound interest and cost to pay back later.

[3] Failure Demand: The demand placed on the capacity of the team because of failure to do something right or to completion the first time around. Includes technical debt, having to do things manually because there was not time to automate them, bugs, poor design, lack of refactoring etc.