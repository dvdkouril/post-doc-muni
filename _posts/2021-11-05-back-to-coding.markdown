---
layout: post
title: "Back to coding"
excerpt_separator: <!--more-->
---
After spending last week mostly watching conference talks, it felt good coming back to some coding.
Exploring our React codebase and trying to contribute. As a small feature I continued with computing intersections with the chromatin fiber at predefined horizontal planes. It's a nice small functionality that made me hands on with the code. I think I'm slowly getting into it, even though there are many many new technologies and concepts I have to learn.
Haven't had the need to dive into WebGPU yet because Matus made a very sophisticated graphics library. He just exposed functions like addSphere to me, which I started exploiting right away:
![many spheres](assets/addsphere.png)

Eventually, I got to something that actually works:
![chromatin intersections](assets/intersections.png)
Purple spheres indicate horizontal planes, blue spheres are the chromatin bins, yellow are intersections of the chromatin with the planes. It may not look like it due to perspective projection but the intersections really are in these individual planes.

Next step is probably extracting those points into 2D and computing an actual metric for the distribution in space.

### Yet another project idea
I got another idea for a side project. I think it would be great to make a scrollable storytelling visualization explaining the Hi-C process. The thing is that even after researching this method for a while, I still do not completely comprehend how everything fits together. Mostly I think we work with some data that results from a very complex experiment and there are inherent uncertainties. Visualizing the process, how you go from not knowing anything about this extremelly small structure (i.e., the chromatin fiber) to getting some indirect information about the conformation, from which you can imply other insights. But the fact that this is implied data, not measured, can hinder us, and maybe even the domain scientists, in getting the right mental picture.

And if nothing else, it could be a great education or science communication content.
<!--more-->
