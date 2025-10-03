---
layout: project
title: Statics Lever
description: A lever assignment for my ENGRD2020 class.
technologies: [Math, Python]
image: /assets/images/statics-lever.png
---


In 2025, I designed a lever to lift a load. This was because it was assigned as a required homework problem for my ENGRD2020: Statics and Mechanics of Solids class. I made this design over the course of an hour, after considering a few other designs. The design was constrained within a 1.5m by 0.5m design space, including the piston used to lift the lever. There was no correct answer, and the design I chose was simply for the example situation where you would need more weight than height. I have attached by design considerations below:

![Design Considerations]({{ "assets/images/statics-lever-considerations.png" | relative_url }}){width: 30%}

Because of the open ended nature of the problem, it is best to have an open ended solution. However, to get full credit, we were required to create a specific design. For option one, I made a Python program to analyze all possible angles and distances. This is based on the bath also pasted below:

![Design Considerations]({{ "assets/images/statics-lever-math.png" | relative_url }}){width: 30%}

I plotted all of these angles as a graph against relative height lifted to relative weight lifted and found an inverse relationship as I predicted. Also, due to only calculating the weight liftable when the lever is fully extended, the program found that you could technically lift infinite weight by choosing an angle and length such that the bad stands directly up. I cut these out, as calculating the max weight here would require an integration over all lengths of extension, and I don't get paid enough for that. Here is the graph:

![Graph Thing]({{ "assets/images/statics-lever-plot.png" | relative_url }}){width: 30%}

Where x is the angle (in degrees) and Y is the distance the piston is away from the base of the lever. Keep in mind that this design uses the assumption that the lever arm is as long as possible and the weight is at the end of this arm. In that sense, it is optimized for height.