---
title: About
layout: default-with-hero
hero-img-url: "/media/team-and-mentors-overlay.jpg"
hero-img-description: Science and Us event attendees
hero-content: "<h1>We're a team of high schoolers <br>spreading the knowledge <br>that
  changed our lives</h1>"
---

<article markdown="1">

## Our mission

Science and Us is a youth-led nonprofit dedicated to helping high schoolers explore the intersection of STEM and society.

There are thousands of activities and competitions for teens to learn STEM, but virtually none that focus on **communicating** it in engaging, accessible ways. On top of that, there are few initiatives that truly help "non-science students" find a place for STEM in their lives.

We believe that fields like **science media, policy, outreach**, and more will not only change the world, but are also perfect ways for today's youth to fuse their diverse interests into fulfilling careers.

The problem? Most high schoolers (and even undergraduates!) aren't aware of these opportunities, or how to pursue them. Our mission is to strengthen the bridge between science and all of us.

**Not everyone needs to be a scientist, but understanding STEM is crucial for making informed decisions about our lives and the things we care about.**

</article>

<article markdown="1">

## What we do

We host **[Makeathons](https://scienceandus.org/makeathon)** where students create podcasts, art, and articles that explain STEM topics to various audiences, with guidance from professional science communicators.

Our Makeathons have been sponsored by [Science in the News](https://sitn.hms.harvard.edu) and the [Harvard/MIT COOP](https://store.thecoop.com/coop-gives/), and included experts from [STAT](https://www.statnews.com/) and Boston-area universities, as well as freelancers like [Wade Roush](http://www.waderoush.com/).

We love sharing our experiences with and learning from the broader science communication community! We presented at **[Science Talk](https://sciencetalk.org)** in Portland, OR, and attended the 2018 **[ComSciCon](https://comscicon.com)** National Workshop and [Science Media Awards and Summit in the Hub](https://sciencemediasummit.org).

We're currently compiling stories and advice from diverse science communicators into a **book called *Stories of Science and Us***. We aim to distribute this book to classrooms across the country, because finding your place in STEM communication should be accessible to everyone.

</article>

<article markdown="1">

## Meet the team

We can all be reached at [name]@scienceandus.org. For team members with a nickname in parentheses, the nickname is used for our email addresses (e.g. kat@scienceandus.org).

We're always open to driven, authentic people joining our team—if you're looking to grow personally and empower your peers at the same time, send us a message at [contact@scienceandus.org](mailto:contact@scienceandus.org)!

{% assign ordered-team-members = site.team-members | sort: "order-number" %}
<div class="row fourths">
{% for member in ordered-team-members %}
<div class="person" markdown="1">
**{{ member.title }}**
![{{ member.title }}]({{ member.portrait }})
</div>
{% endfor %}
</div>

</article>