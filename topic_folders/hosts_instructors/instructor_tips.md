### Tips For Instructors

This page has an assortment of practical tips for instructors.  

#### Handling Software Installation

Installing software on laptops has gotten a lot better over the years, but it can still be a huge challenge at the start of a workshop.  Here are some suggestions for making the process go as smoothly as possible.  
Software installation can be frustrating, but in the end, it almost always gets done.  Be positive, and when it finally works, you can feel proud.  

**What you can do in advance:**

* Plan for installation help at the start of both workshop days.  Put it on the schedule and make sure it's clear that people can and should show up during that time.  
* Email the participants a week in advance and the day before to remind them to install the needed software before the workshops.  
* If possible, recruit at least one helper who uses Windows and one who uses Mac.  
* If you/helpers/instructors have time, test the install instructions on a fresh user account on your computer.
* If you anticipate issues (or want to be extra prepared), have some of the emergency options listed below ready to go.  
* If you're teaching for an organization where participants are bringing work laptops where they don't have administrative access (common in government organizations) -- ask about it.  Try to plan ahead either with their central IT organization or with the "emergency exits" listed below.  
* Will you have decent wifi?  A bunch of people installing software at once can kill a poor internet connection.  If this is the case, prep a few flash drives with the relevant installers.  

**On the day of:**

* Wiki page with common problems: 
	* https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions
* If someone has come in early and the software still can't be installed by the time the workshop starts, try one of the "emergency exits" below or keep working with them one-on-one until they're able to start. 
* If someone comes in late or is having such trouble with installation that they can't start, have them watch (and maybe work with a neighbor) until the first coffee break, when you can keep working on installation issues.  

**"Emergency Exits"**

If there's absolutely no way that you'll be able to install the software locally on someone's computer, consider using the following: 

* The "cloud" variants of [RStudio](https://rstudio.cloud) or [Jupyter](http://jupyter.org/try).
* If your institution's library does laptop rentals, rent 1-2 laptops and set them up with the software before the workshop and keep them on hand as loaners during the workshop.  

#### Talking About the Code of Conduct

The Carpentries Code of Conduct is a key tool for fostering and upholding an inclusive, respectful learning environment.  But for people who are new to the idea of a Code of Conduct, it can be a little awkward to talk about.  Here's a sample of how you might introduce the Code of Conduct -- please don't use this verbatim, but adapt it to your own audience and style of introduction: 

> It is really important to us as Instructors that this workshop provide a welcoming environment for everyone. People learn best when they feel comfortable, when they feel they belong. Software and Data Carpentry both subscribe to a Code of Conduct - you can find a link to it on line x on the workshop etherpad.  The Code of Conduct is our way of saying that this is a place for you -- you belong here and deserve to be treated with respect while you are here.  The Code of Conduct could be summed up as "be kind and respectful."
> 
> What does that mean?
> 
> Apart from prohibiting the obviously unacceptable stuff like harassing or vilifying anyone, it also means this:
> 
> * Please don't make someone feel clueless because they don't know what you know.
> * Please don't try to make anyone feel bad because of the hardware or software tools they use.
> * Please don't talk over people - everyone has an equal right to be heard.
> * Please don't mock people's questions.
> 
> This is a workshop for beginners. If you know nothing at all about what we are going to be teaching here today, that means you're in the right place!
> 
> We are all learners here - including your Instructors! We Instructors take the Code of Conduct very seriously, and we have a process for dealing with violations and complaints. Observing the code makes the workshop better for everyone ... so ... what questions or comments do you have for me about that? ... If no-one has any questions or comments, then let's get started!"

For details on how to handle Code of Conduct violations, see the policy page in the handbook: https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html#reporting-guidelines

#### Using Exercises

When teaching a lesson, it's a very good idea to go through the lesson in advance and choose which exercises you want participants to try.  

Once you've selected exercises, there are several ways to actually display them to the participants during the workshop.  Any of these options may be the best choice depending on the tool you're using or the kind of exercises you want to use.  

* From the lesson website (zoomed in)
	* This is the least effort, but requires having the right lesson page open + finding the right exercise
* Make slides
	* More effort, but easy to flip forward to the next one
* Have a document of some kind with all the exercises in it
	* More effort, but exercises are all in one place.  
* Put exercises in the etherpad
	* If you do this in advance, pretty low-effort.
	* Can also use this with any of the other strategies so people can find the exercise in two places.  
* Online tool, like Socrative
	* Requires time to set up, but is great for multiple choice and T/F questions and promotes participation

In all of these examples, you'll have to switch from the tool you're using for live coding to however you're showing the exercises.  For something like R or Python, one way to reduce the amount of switching is to put all the exercises in an R script / Python notebook and have that open alongside your main working script/notebook so that it's relatively easy to switch back and forth.  

#### General Tips

**Introductions**

The introduction is one of the most important pieces of the workshop!  It sets the tone for the day.  See the [instructor training material](https://carpentries.github.io/instructor-training/19-introductions/) for some suggestions of how to build a good workshop introduction.  

**Accessibility Check-In**

Before you start, set up your computer and go to the back of the room.  Is your font big enough?  

If your room has a mic, use it, and have a helper stand in the back of the room as you start to confirm that you can be heard.  

**Classroom Management**

To be expanded, how to handle: 
- someone asking very specific questions
- interruptions
- people not talking to each other

**Varying Skill Level**

Carpentries workshops frequently include many people with widely varying skills and experiences.  See the end of the Carpentries Instructor Training on [Carpentries teaching practices](https://carpentries.github.io/instructor-training/22-practices/) for some strategies to deal with a diverse classroom.  

#### Preparing to Teach

It can be daunting to look at a Carpentries lesson and figure out just exactly how you're going to teach it.  Here are some suggestions for tackling a new lesson that you've never taught before: 

**Read through the Instructor Guide for the Lesson**

Most Software Carpentry lessons include a guide for instructors. These are great for novices preparing to teach a lesson for the first time. As an example, see the [instructor notes](http://swcarpentry.github.io/shell-novice/guide/) for the Software Carpentry [Unix Shell](http://swcarpentry.github.io/shell-novice/) lesson. Find instructor notes for other lessons through the **Extras** menu on each lesson's home page. 

**Pick Exercises**

Most of the lessons have more exercises than you will want to use.  Go through the lesson and pick the ones that you think will be most helpful for your audience.  If you anticipate mostly novices, look for easier or more scaffolded exercises.  For a more advanced audience, a more general exercise might be better.  If you'll have both, have an option for each!  

You won't want to use *all* the exercises, but make sure that in this process, you commit to actually doing exercises.  Exercises are time-consuming and it can be tempting (in the moment) to talk instead of taking the time to do an exercise.  However, doing exercises is a huge part of the hands-on Carpentries model and also gives people a chance to chat with their neighbors, so it should be prioritized.  

Speaking of priorities...

**Prioritize**

All of Software Carpentry lessons have more material than you can easily cover in a half day, especially with a novice group.  The Data Carpentry materials are closer to realistic workshop time estimates, but can still run slowly depending on the group.  

So no matter what, go through the lesson in advance and decide what is most important to cover and what you would feel okay skipping (either skipping outright, or dropping it if you don't have time).  

As an example: the shell lesson has 7 sections -- the first three are about basic file system navigation and file operations and the last four are about ways to use simple shell tools in more powerful ways.  Often a workshop will cover the first three and then three out of the last four.  

**Practice**

* At the very least, do a dry run of all the commands you will be running / code you'll be writing so that you know they work on your computer. 
* Hook your computer up to a projector and figure out how you're going to manage your screen real estate, especially if everything is magnified.
	* Rstudio: Rstudio can be particularly challenging because of all the panes.  Reducing the size of the two right panes is usually needed to have enough space in the script/console panes. 
	* Jupyter notebooks: you can toggle the headers/toolbar off so that you have more scripting space
* If you have the time, doing a full run-through where you actually practice what you're going to say can be extremely valuable.  Words are hard when you're also trying to type and manage a classroom, so having said them once in practice gives you one less new thing to think about.  
