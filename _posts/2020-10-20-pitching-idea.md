---
layout: post
title: "How to give a technical pitch."
date: 2020-10-20
---
# Introduction
I wanted my first blog post to be about a recent achievement I made at work that I was proud of. I recently prepared and pitched a significant feature to my team, who approved of and appreciated the idea. I was fortunately given an entire month to explore and flesh out my idea. It's been an immensely rewarding and satisfying journey so far, so I wanted to share my experience and the steps I took to create the conditions necessary for acceptance.

# Problem Identification
The first important step taken was to find a pain point for the team or product worth investing the time to remedy. For me, I found my idea from experiencing the pain of QA engineers. I was originally tasked with writing test automation as a part of my ramp up for a particular microservice. That task required us to upload test data to the microservice, then query the microservice to validate that the data processed correctly.

After write a few test cases, I quickly discovered the difficulties of creating test data, as well as the repetitiveness of matching data values. This problem lacked sufficient attention, I assume as a result of developers only coming in to write the test cases for their feature. I saw the opportunity to revamp and redesign the framework from the ground up to a reduce the amount of repetition as well as alleviate the complications in writing test cases.

# Doing Research
To create the confidence necessary to convince others, you must first convince yourself. Once adequately prepared, confidence comes naturally. I first started researching test automation frameworks, and eventually found that no particular framework fit the needs of the team. We needed an extensible yet modular testbed for test case creation. However, I found several frameworks that could serve as useful components.

After investigating the method by which to implement the idea, I put together a pro/con analysis to assess the viability of the project. I mainly concerned myself with the impact, investment, and scale.

Impact represents the overall result of the project. The people hearing your pitch want to know the ultimate benefit of the project to the organization. In my case, I needed to demonstrate that the resulting framework will ultimately become useful. I would have to make a compelling argument that the end product would be easy to learn, while also reducing the time spent for each test case.

I see investment as a counteracting force to impact. If a project becomes too time consuming, it may be deemed not beneficial enough to justify the costs. For example, I had to show that the additional complexity my framework would add to the testing automation code would be small relative to the overall benefits it would bring to the entire system.

Lastly is scale. Can this idea be scaled up in the future? Could we expand the impact beyond just your team, but to the entire org? The potential of a project generates a great deal of excitement if your pitch can grow to affect multiple projects and teams. For instance, my project methodology focused on generifying the data creation and validation process so that it could eventually be used in any automation system.

# Pitch It
A slide deck is always a good idea when it comes to pitches. Keeping it simple, I made at most 3 points per slide, sticking to key ideas rather than verbose explanations. For impact, I focused on the improvement to test case writing efficiency. For investment, I emphasized that the component frameworks already existed, and that I just had to assemble for our particular use case. For scale, I projected that this framework could be deployed in the automation efforts for our other microservices as well.

# Closing Thoughts
The main point here is to find a problem and solve it in a cost-effective manner. Everything else is preparation and research to convince yourself and others that your solution will deliver on the time frame and impact it promises.