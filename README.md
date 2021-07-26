# Chicago


1.  [Performing Arts Directory](#orgbf83a21)
    1.  [Getting into the role](#orgfff6ff0)
        1.  [Intro](#org43f3f94)
        2.  [Project Challenge](#org071a191)
        3.  [Discovery](#orgec01804)
        4.  [Design](#org8428ede)
        5.  [Project Summary](#orgb6c39a0)


<a id="orgbf83a21"></a>

# Performing Arts Directory

![img](https://uploads-ssl.webflow.com/5d7d44d8cb34e46b7a9f7abb/5d7f05ea28ecca3bf6dc2a30_650_chicago%2Bel%2Bcorridor.JPG)


<a id="orgfff6ff0"></a>

## Getting into the role


<a id="org43f3f94"></a>

### Intro

A directory of performing artists was created using Vue.js. I will be
focusing on the developer within, hoping to describe why this needs
separate focus from a UX designer role. I will be reviewing GitHub
commits, trying to see what was missed. I say dev because this project
revolved around a Heroku Implementation with a firebase fallback.
Eventually, the fruits of this project were useful as a profile list.
SEO work started making its way into scope in creep fashion. Aesthetics
was the focus, but not the problem. What would I go back and do
differently? Was it easy to follow my own flow? What if the trajectory
was smooth but the result disjointed? I have, as a result, API
implementation and a Vue front end with an airtable backend.


<a id="org071a191"></a>

### Project Challenge

The current state of the site has a static entry of background
information for each performer.


<a id="orgec01804"></a>

### Discovery

So many lessons learned on this project that span coding in Vue.js,
deployment, and information architecture.

**User Testing**

Using Mixpanel to track first-clicks and beyond, I tested the profile
page to give the profile a home. The profile page was tested remotely on
the video app of choice by the interviewee, usually at dinner time.

**Competitive**

Northlight, Ticketmaster, 4-Star, and NBC were all analyzed as part of
the competition to achieve a layout that works on

1.  photo size and placement
2.  what items are included as part of the contact details
3.  placement of copyright notice

Through dropbox paper tables, we made a tally of the critical bits
standard across the established websites.

**Comparative**

I made a chart of industry terms to increase the efficiency of booking
agents at finding talent. Included Backstage, Second City, Actors Access
on what were the most used words by:

1.  Count
2.  Used in navigation
3.  Used as categories in blog sections

We focused on this to make decisions about our URL structure. The
importance of the url is an SEO mainstay. Given it's importance, I set
out to use Vue adjacent tools.


<a id="org8428ede"></a>

### Design

**Sketches**

We started looking at the original. A long list that did not paginate.
This can be inefficient to scroll all the way to the end, resulting in
overlooking some key performers. Using Marvelapp and 3x5 cards, I
sketched out about 3 final variations on a full cast landing page in
order to choose a more compact collection layout. Over 20 performers now
are shown within a square collection format.

**Wireframes** I wireframes at least two views, starting with mobile, in
order to look atpicture placement and text sizes given an unknown set of
actor records. Justinmind prototyping software immediately help load a
data collection into the first wireframes. It is important to not assume
to much. When using a persona representation, I try to 'live it'
throught the userflow and wireframing. If our persona, "Dori" is pulling
out her phone as she's walking her dog &#x2013; it is only one instance. But
finding loopholes is about at least living through "loop one."

**Guidelines**

I didn't want the user to have to learn and re-learn (two ways of doing
the same thing), so at design merge, I kept the colors and font and
focused on the root landing page. The initial components where
Material-based components. I would use this to maintain alignment and
uniformity. If we lived through a userflow, we can make those decisions
live in a style guide.


<a id="orgb6c39a0"></a>

### Project Summary

-   The proximity of name to performer is an important convention that
    reflects the real-world headshots that are handed in at auditions.
-   Templates least serve the user on exposure goals
-   I enjoyed reading the many varied bios of performers
-   I got to delve in deep and live out the process of getting a headshot
    taken
-   Having the hometown date as a connector category for the user or
    booking agent may be a significant next step.

