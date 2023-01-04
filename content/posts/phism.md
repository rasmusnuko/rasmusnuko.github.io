---
title: "PhISM Percussion Synth"
date: 2022-10-29T13:53:27+02:00
draft: false
---

## Background
For my 'New Interfaces of Musical Expression' (NIME) course we have to do a mini project where we build an instrument.
We had to hand in a one-pager containing our initial first sketch and answers to some guiding quetions. My one-pager can be seen in [this PDF document](/documents/NIME_miniproject_RasmusNuko.pdf).
One of my supervisors had already build something similar before, and suggested I looked at the article [Physically Informed Sonic Modeling (PhISM): Synthesis of Percussive Sounds](https://www.jstor.org/stable/3681012#metadata_info_tab_contents) by Perry Cook from 1997.

## Questions and Goals
In my first semester, I have three courses: NIME, 'Sound Processing' and 'Music Perception and Cognition'.
For each course we have to do a mini project, and I will incorporate this NIME in all three.

The mini project in: 
+ Sound Processing will be based around the implementation and theoretical material behind the synth engine.
+ NIME is going to be the actual building, deciding on hardware components, mapping sensor data to the software.
+ Music Perc.&Cogn. had some recommendations for projects, and there was one on how people percieve the timing og notes with short/long attacks. The idea will be to test how people try to play my NIME in time with varrying attack times.

## Development
At first I implemented the code from page 45 the PhISM article in Python. The code can be seen [here](https://github.com/rasmusnuko/percussionsynth/blob/main/src/concept.py).
This is more or less a one to one copy of Perry Cook's code, just to hear what it sounds like.
Two configurations can be seen in the bottom of my code, and both can be heard below.
The first one is the one is the one presented in Perry Cook's article, and the other is a higher pitched shaker with more system decay and at a faster tempo.

{{< audio src="/audio/perryshaker.wav" class="something" >}}

{{< audio src="/audio/highshaker.wav" class="something" >}}
