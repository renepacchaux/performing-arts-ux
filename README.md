# Before delineating UI from UX


1.  [Performing Arts Directory](#org5655629)
    1.  [Performing and booking](#org11fcd73)
        1.  [Project Challenge](#org23c3bbd)
        2.  [Discovery](#orgf9abb83)
        3.  [Design](#orgc21b7f5)
        4.  [Project Summary](#org5398a41)


<a id="org5655629"></a>

# Performing Arts Directory


![img](https://uploads-ssl.webflow.com/5d7d44d8cb34e46b7a9f7abb/5d7f05ea28ecca3bf6dc2a30_650_chicago%2Bel%2Bcorridor.JPG)


<a id="org11fcd73"></a>

## Performing and booking


<a id="org23c3bbd"></a>

### Project Challenge

The current state of the site has a lot of background information for each performer. The control to update details was handled by the stakeholder.

A directory of performing artists was created using whatever I had available to me, at any free tier or at lowest cost. Most of these require familiarity with the internals of servers to get them to work. I looked online for places where the bulk of the code was already in place. By changing just enough of the template, I used it for what was needed. I will be focusing on situations where it is good practice to keep notes about altering the templates.

**Separate focus from a UX designer role**

I will need to step lightly with separating myself from coding to work within the aims of the people and stakeholders involved. I will be reviewing my notes-to-self every time I take, ideally, a critical turn in the work of any in-progress work. Because this project revolved around a technical activation of a website using a modern app-marketed tool, there will be some overlap of roles.

**Revamped priorities**

Eventually, this project produced a profile list. Taking on conflicting roles meant that finishing the displayable list had snubbed any thought to consider the search listings that illustrated a milestone to be accomplished. This was not addressed in any particular way.

**Getting it right the first time**

Ideally, there is a fine line between how it looks and how it works. It is easy to think you are aligned on how to solve the problem.

**Easy to follow**

It is important not to drum up a list of todos immediately. Some resources of the website would call out to existing site and documents in published by the stakeholder. Those unpublished were put in place with the help of a special live spreadsheet to work as the centralized place of information.


<a id="orgf9abb83"></a>

### Discovery

So many lessons were learned on this project. They start at a very technical level using the same path to get to what you see when you visit the published site.

**User Testing**

Using a popular multi-click addon software to track user clicks, I was able to get the interview notes to match what I see on what was clicked. I get closer to the *why*. I made it a goal to at least infer the first thing sighted. I used the first click to tell me this. Not quite a certain 1:1 but enough to make a decision about it.

I also tested the profile page to give the headshot gallery a home. The profile page was tested remotely on the video app of choice by the interviewee.

**Competitive**

Northlight, Ticketmaster, 4-Star, and NBC were all analyzed as to achieve a layout that works on

1.  photo size and placement
2.  what items are included as part of the contact details
3.  placement of copyright notice

Through the use of spreadsheets, we made a tally of what was needed by other websites to get a sense of what is standard across the established actor-directory websites.

**Comparative**

I made a chart of industry terms to increase the efficiency of booking agents at finding talent. Included Backstage, Second City, Actors Access on what were the most used words by:

1.  Count
2.  Used in navigation
3.  Used as categories in blog sections

We focused on this to make decisions about what affects sharing within other apps. I had to work with what I had in terms of the where the live site would live. I would not be its own thing but an addon to sit aside a static-but-comfortable main site. It was important to consider how all components would live together when in use.


<a id="orgc21b7f5"></a>

### Design

**Sketches**

Using [Marvelapp](<https://marvelapp.com/>) and 3x5 cards, I sketched out the order of taps. We started looking at the original without too much guessing. Would a set of users expect to see featured performers first, or more performers as long as they kept scrolling? We kept a long list. What would be the most common searches of a talent agent? Should I make that decision myself and choose and show only the featured on the first-seen layout? Currently, over 20 performers are now shown within a set of cascading-style squares.

**Simple Lines**

Given an unknown set of actor records, I pixel-sketched the simple lines and boxes that would be the start of the most consequential page on the site.

Depending on how you are arriving at the site, it could present itself in one of two ways.

-   The static representation
-   The headshot gallery with priority ordering

**Name Placement**

Let me pay attention to the text sizes. There are plenty of software to roll out the immediate wireframe. This also helped load a spreadsheets sized table of information into the later renditions of the site. There were a few clues as to how it would work to click from one thing to the other.

I needed the help of a persona. It is important to not take a non-descript approach under a wide net in the name of best practices. When using a persona representation, I try to 'live it' throughout tthe steps anyone would take to produce something immediately useful to whoever is using the app.

**Persona Dori**

Our persona. “Dori Lattice.”

She's walking her dog, and we take this situation and unpack it to see if we are heading in the right direction. If and when there are issues with our first attempt at getting a click progression to feel just right, I will go back and ‘fix' it.

**Guidelines**

I didn't want the user necessarily learning and re-learning where to look for what. At the early stages of the design thinking, I kept a close eye on the layout for the inital page which is the gallery of photos. The code library I used breaks up the work into components. Material is the reference for many projects out there and I wanted to specifically use the [MaterialCSS](offshoot) for my components. I would use this to make sure all my margins and more matched as best as possible, without directly going in and specifying them.

There would be more decisions to be made about how a user would progress through an app. As long as I document, I could make those decisions and have them live within a knowledgebase for the styles beyond what is in-place by MaterialCSS.


<a id="org5398a41"></a>

### Project Summary

I had to pay attention to where the performers name lands when in the hands of a user. At some level, what I do aims to reflect the real-world headshots that are handed in at auditions.

Creating a profile that is special to you is hard from the point of view of a person would is at the center of many, possibly on its face unrelated projects. I enjoyed getting the details of histories of performers, and seeing if there are less obvious commonalities. I like to bring that out in the way a site is built.

**Next Steps**

We know from themes in interivews that this type of information lands at the desk of a producer. With more resources, it would be wise to dive in deep into the process of getting a headshot viewed and vetted for worthyness for a particular role.

From themes we have seen in competitive analysis, there is an opportunity for having the hometown date visible to a booking agent or producer. Further data shows that the stakes of an out of town performers tends to draw better results.

