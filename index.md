---
layout: page
title: Non-linear Function
tagline: 
---
{% include JB/setup %}

Hi! I'm a queer machine learning researcher / engineer[^1] living in the SF Bay Area and currently working at a large-ish tech company. I'm a recent PhD graduate of a highly-ranked CS program, where despite trying my hardest to become the person and scientist I wanted to be, I failed at achieving my goals and destroyed important relationships while becoming deeply depressed and cynical about academia, AI research, and myself. 

This blog is an attempt to process this situation and rebuild an new identity. It's an attempt to figure out what I've learned, what I'm actually interested in, and what to do with my life. It's also just an attempt to write more. My writing is for myself, but maybe you'll find it valuable too. The Internet has no shortage of people performing success; this blog is about the non-linear path.

Topics we may cover:

* Grad school.
* Mental health.
* Big questions in AI and machine learning.
* How to do good research.
* How to live a good life.
* Sexuality, and its surprisingly large interaction with *everything else*.

I'm being deliberately vague about my schooling and current employer, but some of my experiences are likely close-to-uniquely-identifying. One of the best things about the internet is the ability to express oneself unconstrained from one's real-world, everyday identity. I ask that you respect that. 

My dream as a kid was to succeed wildly, then explain what I'd learned so that future kids like me could benefit. This blog isn't that, but, perhaps, a step.

[^1]: I have Thoughts about this distinction and might write about it sometime.

[^2]: Including me, in my real-world identity. 

### Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



