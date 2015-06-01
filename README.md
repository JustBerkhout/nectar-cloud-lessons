# NeCTAR cloud lesson plan

This course aims to teach the basics of the NeCTAR cloud to researchers over a one to two day workshop.

> "We are ... looking to find (and train) what we are calling a "power (researcher) users".  
>
> From our work with the Research Bazaar here in Melbourne we've discovered that there is an increasing number of 
> researchers who are turning to the Cloud as there "Operating System" of choice, we call this "ResOS".
>
> Our investigation into these types of users produce the following kind of persona traits (which is whom we are aiming 
> this "ResOS Train the Trainer curriculum").  "Power (Researcher) Users" are the types of researchers who see 
> themselves as:
>
>* technically savvy (the person in the lab who everyone goes to for help);
>* they feel they are researcher first and foremost, e.g. they usually introduce themselves as "researchers" but are 
>  very happy for their research colleagues to identify them as "technical".
>* sometimes these users are hired for their technical skills and identified as the research groups developer, but they 
>  do have discipline expertise.
>* often they are a postgraduate or early career researcher; far too often they are male.
>* types of people who immediately un-installed the operating systems which the University provided them on their 
>  laptop and replaced it with an OS which allowed them to have access to the "Utilities", "Settings" and 
>  "Advanced Settings" of their Operating System. 
>* they've even played around with installing Linux Ubuntu and other "command line" tasks.
>* while they understand the basics of installing an OS, it is only a means to an end so they can access more of the 
>  research tools which get them and their colleagues results.
>* for them the cloud is just someone else's computer and they are only just willing to trust a computer the University 
>  runs so long as no restrictions are made on them about how they use it (they are glad to go back to doing it 
>  themselves if there are any barriers or bureaucracy put up by the University).
>
> The purpose of the above persona is to provide a training to all the nodes (via creative commons) so we can train up 
> these PowerUsers in how to use the Cloud Operating System (NeCTAR OpenStack) so that they can customise it with the 
> apps that will make it their own discipline specific "ResOS".
> ...
> Once we test the training we hope to take it out on the road to each of the nodes so we can train up at least 
> 6-12 people in each city."
> -- <cite>David Flanders</cite>

## Motivator

It’s been hyped: but the Cloud does offer serious value in terms of cost and instant availability to researchers.
However, it’s a complex tool and if you don’t know and understand its constraints trying to make use of it can end
in painful tears. This course introduces you to the the tools and the underlying concepts of the NeCTAR cloud -
thus reducing your risk and saving you time and trouble in your journey to the cloud. And given the scale and low price 
of the research cloud you will, most likely, be making that journey.

## Folders

The directories that make up this project are as follows:

* [Promotion](Promotion/README.md) - Promotional material to use in advance of the course
* [Lessons](Lessons/README.md) - The lessons themselves
* Planning - The materials that were used to create the course

## Delivering the lessons

The lessons assume that participants have both red and green coloured sticky notes and cards lettered from "A" through
to "E" (in the style of Software Carpentry). These are used to answer questions and to show distress if the students
aren't keeping up or need help.

## Extension challenge

There is also a set of extension challenges, should time permit: [ExtraChallenges.md](Extension/ExtraChallenges.md).
These cover connecting to the VM.

# Thoughts after delivering the first two lessons as a 1.45 hour workshop.

## The questions

The sticky notes as a token of progress didn't work that well. People would leave them up after prior exercises, and
not take them down when starting new ones. This is after three days of using them! Either I was out of sync with the
way in which these should be used, or human procrastination kicked in. I got tired of reminding people to take them
down at the start of each exercise. I wonder if a more aggressive red card for "help" and a general show of hands as
to if I can continue would be better?

The multi-choice questions worked really well. They let me pick up concepts that had not been conveyed properly, and
have another go at explaining them. The concepts that were missed in each case were only missed by a very small number
of people, so it's probably not worth trying to change the lessons in this regard - however, if a consistent pattern
builds up then they should be changed.

## Changes to the notes

The lecture notes as they stand at the moment don't have a conclusion in them. I just winged one at the end.

I also forgot to, but should have, reminded everyone to shutdown their virtual machines at the end of the class.
This should be added to the conclusion.

A large number of people managed to get to the "homework" that I didn't expect them reach. This should hence be
better documented. In the original scheme of things, this is intended to be its own 45 minute lesson.

The password section and the external access sections should be put into their own lesson. They simply distract from
the goal of these two, which is to get a VM up and running, and then to access it.

Some diagrams showing the movement of the files as a VM is launched would be a good idea. I just used words, and
although I got the point across this would make it easier and faster.

It turns out that the new trial projects have security groups added for some of the more common protocols. At the
very least this should be noted.

## Audience feedback,

A couple of people came up after the lecture and stated that they thought that this was a missing piece in the puzzle
of how to get started on the NeCTAR cloud. They asked if this could be televised or turned into a "MOOC"...




