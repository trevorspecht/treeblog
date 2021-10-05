---
layout: post
title:  "My second week at the Recurse Center"
---

## Recurse Center Week Two

I was able to settle down a bit after the first week, which felt rather chaotic after some very sudden large changes in my life. I came up with ideas for learning and related projects, and speaking with some RC faculty members helped me solidify those plans.

Probably the most important decision was to stick with JavaScript for my learning, rather than starting to learn another language. Most of my programming experience is using Node.js on the back end, but I don't know as much about the front end or using databases. I want to learn React, and starting to learn that made me realize I need a refresh on HTML (not to mention CSS), so I'm going through the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/HTML) on that, and starting to dabble in React at the same time using the [React Tutorial](https://reactjs.org/tutorial/tutorial.html) at reactjs.org.

My project reflects my goal to be able to consider myself a full stack JavaScript developer. I'm going to build a website to house photos of nature I've taken during many walks and hikes. I bought myself a Fujifilm X-S10 with a 16-80mm kit lens last year and it's been fun to use and has helped me get some interesting photos. The metadata in these digital photos includes location data and other information I plan to use to make the photos sortable and searchable, as well as placing them on a map.

In order to learn a bunch of new things, I'm going to make this much more difficult for myself than it needs to be. I'm going to use Docker to create a nginx web server container, and deploy this to an AWS EC2 instance using Terraform. I might throw Express.js routing into the mix for good measure, and I'll figure out how to incorporate MongoDB as a database to store the photo files.

Another area I want to explore is audio/music, so I've decided to learn about the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) and create a website that allows someone to play with audio modules to create and manipulate sounds. I don't have concrete goals for this other than to apply what I learn and see where it leads me.

I have an idea that these two projects can overlap, as I'm very curious about how sound can be represented visually in an artistic and creative way, as well as how images can be represented by sound.

---


So here are the things I'll work on in Week 3:
- HTML/CSS refresh
- React tutorial and exercises
- Follow along with the group working through Eloquent JavaScript
- Follow along with the group working through The Theory and Technique of Electronic Music
- Continue playing with Docker and Terraform and get a basic web server spun up
- Start reading about the Web Audio API