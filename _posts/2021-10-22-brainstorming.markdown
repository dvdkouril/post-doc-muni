---
layout: post
title: "Brainstorming and IEEE VIS 2021"
excerpt_separator: <!--more-->
---

Not much coding done lately. I've spent a lot of time reading related works, conceptualizing, and coming up with ideas for visualization papers. On Wednesday 20th, we had a bigger meeting to discuss a plan towards making an initial submission in March 2022.
The main part of the project is designing and implementing a general tool for working with chromatin structures predicted from Hi-C data. That's what the two PhD students should work on for the most part. There the main problem (besides engineering) is facilitating selection in the 3D structure. We need some smart way to peek into the "hairball" and selection parts of the chromatin that are not on the surface. You can then do several operations with the selected parts (i.e., bins) that are interesting to domain scientists:
![after selection operations](/post-doc-muni/assets/after-selection-operations.png)

However, I'm still thinking that there could be one small part which I could take up as a side project. Our bio collaborator mentioned this idea for expressing spatial distribution of the chromating. Quick sketch done by me:
![section cuts](/post-doc-muni/assets/section-cuts.png)
I started prototyping some code for getting these section cut intersections but haven't gotten yet to the part where I show them in the individual planes.

### IEEE VIS 2021
This week the IEEE VIS conference took place, virtually of course. Honestly, after being away from the international visualization field, it was quite nice to watch the conference. 
As usual, I found all the accompanying events to be the actual interesting program. Very rarely you have a good paper presentation so I'm finding that I'm not too interested in the full paper sessions. The panels, workshops, and other associated events, on the other hand, give you a way better idea of what the field is generally trying to accomplish, and where are the gaps you might contribute with your own work.

### Project Idea
Watching the various talks, I had an idea for a project. Actually, it's nothing new, it has been brewing in my mind for quite some time, and I've been on-and-off trying to work on it for a few years already. But while watching VIS it felt like it might be a worth contribution. The idea is about personal visualization for people managing a chronic condition. For me that's eczema. 
What I think might be novel is a combination of factors:
- it's me making a tool for myself, not serving any large corporation or institution, it's very small, very personal, very *selfish* in a way
- even though I have a PhD in visualization, it can still be a challenge to design and create something just by myself. i'm not giving it as an assignment to a student, there aren't many people working on it. it's just me.
- it's not only visualization but also data creation and collection. does it make it harder or easier, because i can "play into my own hands"?
- it doesn't really have a solution. you cannot solve health. you can only give people tools to learn about themselves, find a way to cope
- advocate building for yourself: everybody has specific requirements that no general tool will fullfil (either there will be features missing or in surplus), you also might not trust with your personal data to a 3rd party -> if you build for yourself, you control your data 100%
