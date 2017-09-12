---
layout: post
title:  "Information Archaeology: Understanding Historical Design Decisions in Legacy Software"
date:   2013-09-27 20:20
categories: work talks
---
(This an edited transcript of [a lightning talk](https://speakerdeck.com/stuartcurran/information-archaeology-understanding-historical-design-decisions-in-legacy-software) I gave at [Euro IA 2013](http://www.euroia.org/) in Edinburgh.)

Information Archaeology is an idea I have been playing around with for a while now. It describes a process of using familiar IA tools and thinking to analyse the present state of a piece of software in detail in order to infer decisions made in the past and hopefully make better plans for the future. We often assume when redesigning software that the people who worked on it before us didn't know what they were doing. But how can we really know the constraints they worked under? The limitations of their tools or the organisational politics they faced in getting their work done.

The great thing about looking at the past is that it's hard to lie backwards whereas it's easy and quite routine to lie about the future, especially where software is concerned.

I work at [ThoughtWorks](http://www.thoughtworks.com/), a software company that routinely takes on the challenge of solving large enterprise IT problems. As a business we are exceptionally good at it and we have built our reputation on doing so. In most projects I have worked on however, I still see a big gap in terms of information architecture expertise when dealing with enterprise applications, the dark matter of the software world.

We often work with legacy systems. A legacy system is typically an old or outdated piece of software but it can also refer to the behaviours and methods of working. The trouble with replacing legacy systems is that they are often very complex and only understood by a few people. The original designers are long gone and little or no evidence of their thinking remains. What documentation does exists is often woefully inadequate or out of date.

Enterprise software systems build up over time like sedimentary layers. By digging into them you can start to see where additional feature have been bolted on and also where previous efforts have failed. Organisations shape their IT systems and thereafter their IT systems shapes them, often into grumpy, long suffering users of bad software. That is one of the problems with legacy systems - they still need to be used everyday as organisations depend on them to function.

In one extreme case I saw, a business created an entire outsourced department to use one piece of software that everyone else had given up on because they had no choice but to keep it running.

When you are faced with the task of redesigning or replacing such a system, the legacy fall heavily on your shoulders. To borrow an example from everyones favourite archaeologist Indiana Jones when he was going after the golden idol, you need to study the traps that have been left behind. As Indy discovered, when you mess with mechanisms you don't fully understand, [shit invariably rolls downhill towards you](http://www.youtube.com/watch?v=db5rRtOExbA).

Information Architects can be well prepared however. We have the tools, the thinking and we have the humility to learn from experience.

The first thing I do when confronted with a business context I don't understand is to start creating a domain model. Language is your first clue to how things work.

Capturing the nouns and the verbs that are used to describe the entities and their relationships not only helps you to gain understanding quickly, it also allows you to communicate effectively with the locals. The locals of course being, clients, developers, analysts and anyone else you need to develop a shared point of view with.

Maps are essential as well of course. Creating an abstract representation of what you can observe by interacting with the existing UI of a system gives you a birds-eye view to allow you to start speculating about the past and understanding where things might have gone wrong and why.

Information Architects are also concerned with the names of things and their meanings, often obsessively (and rightly) so. Naming things correctly is vital in ensuring that systems are correctly scoped and understood.

Beware of any software project that is referred to as an "engine". In the mind of the business this might be something compact and powerful. In the hands of a user, it's usually incredibly complicated and over-engineered for what they need to accomplish.

Better to talk about "tools". Something specialised, self-contained that does fewer things but works well with other tools. From a technology perspective, this leads to a more effective software architecture and from a business perspective, software agility delivers value faster.

Acronyms that don't mean anything to anybody are also a sure sign of misplaced priorities. Usually these go hand in hand with the whole lying about the future thing.

I was involved with redesigning a system called A.P.E. once and the first thing the business did was to choose a name for the new system, W.A.S.P. No one knew what this new system would do yet, only that it was bound to be better because it was now a small insect rather than a large mammal. You often end up getting [the product that the name deserves](http://www.trashbat.co.ck/t12/).

So far I've looked at things that Information Architects like but I'd also like to suggest a use for something much maligned - the org chart. I'm not about the wrestle with the polar bear and suggest that we return to structuring our software this way - I have a different purpose in mind.

Org charts help you to navigate a business and find ways to connect with people that can help you get things done. At the same time as mapping the software and processes, you need to map the people and find ways to bypass unhelpful stakeholders and get permission to change the way things work.

I believe that changing things at the organisational level not just the software level is the future of what we do. To deliver lasting change that sticks we need to invest in a deep understanding of complex problems through analysis of the present and the past. This is something that is being mirrored in management practice through the likes of the [Cynefin framework from Cognitive Edge](http://cognitive-edge.com/), which points to an interesting future for Information Architects where we can leverage our existing skills into new areas and have much more influence over the outcomes of our work.
