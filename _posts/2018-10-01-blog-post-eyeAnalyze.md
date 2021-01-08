---
title: 'Eye Movement Analysis'
date: 2017-02-10
permalink: /posts/2017/02/blog-post-1/
tags:
  - eye movements
  - smooth pursuit
  - saccades
  - data analysis
---
In the eye movement world each lab uses their own analysis scripts. The Oculomotor lab tries to make their code assessable.


How are eye movements analyzed?
------
There are many different ways to analze eye movements. For a lot of research questions it is sufficient to know where someone is looking with respect to the visual scene. For example, when viewing a picture or a movie you may be looking at different objects and people. Some interesting measures to extract are eye position and the sequence of eye movements and fixations. For example, you may ask yourself how long you were staring at that bottle of maple syrup while thinking about bacon and pancakes. Or in other words, how long was the dwell time on the maple syrup? In the eye movement world, we often want to do a more detailed analysis than simply describing where someone was looking. For instance, we can calculate when saccades -- quick shifts of the eyes from one area of interest to another -- occur, how fast the eyes move during a saccade, how the eyes do little shifts even when we are fixating at an object and how well we are able to track a moving object with smooth pursuit eye movements. There are many detailed eye movement kinematics we can calculate that may reveal interesting insight into perceptual and cognitive processes. 

Yes I know all that, just show me how it's done
------
I received all my training in Miriam Spering's Oculomotor lab. When I joined the lab as a summer student in 2012, there was another German summer student, Janick Edinger, who developed customized and user friendly eye movement analysis scripts in matlab. Since those early days, the analysis code has been modified a ton, but the lab tries to keep everything more or less up to date and improve all parts of the analysis constantly. The scripts are designed to visualize eye movement data and spit out some kind of standard smooth pursuit and saccade measures, such as saccade latencies, amplitudes, velocities etc. You can have a look at the code here:<br>
<a href= "https://github.com/Ookenfooken/Shared-eye-movement-code"> Shared Eye Movement Code </a>