---
title: Submerged Raspberry Pi Clock and Weather Display
category: DIY Tech
feature_image: "https://picsum.photos/2560/600?image=872"
---

![Submerged PiClock](/assets/submergedPi.jpg)

I stumbled on submerged PCs one day and thought they were super cool. The idea is to cool overclocked gaming rigs to improve performance. I personally don't do much gaming outside of my Nintendo switch. Submerging electronics in a liquid was just too neat to not experiment with, so I started brainstorming ideas.

## Concept

Create an always on computer that would be fully submerged in mineral oil. The maintenance involved in a fully built gaming rig submerged in the oil was too time intensive for me. You need to drain the oil while avoiding messy spills, wipe the electronics off, and complete the maintenance then transfer the oil back into the tank. I wanted to find a computer that was small enough for a workstation and didn't involve a lot of components. I knew the Raspberry Pi would be a perfect fit, I just needed to figure out what I wanted it to do.

# PiClock

Kevin Uhlir's github project [*PiClock*](https://github.com/n0bel/PiClock) was perfect for my use case. It is a clock written in python that displays the time, weather forecast, and a radar map of your area. It uses Google's Maps API tp pull a map of the coordinates you set for the radar map and a Weather Underground's API tp pull the that week's weather forecast.

<!-- more -->

# Mineral Oil

Mineral oil is non conductive and disperses heat much faster than air. Electronics can be submerged in the oil without any interference to the components. The oil is clear and looks like water, which just looks cool. 

## The Submerged PiClock

I used a small Beta fish aquarium for the tank since it was small enough to fit on my desk. In my next iteration of the submerged PiClock I am building my own tank out of plexiglass, and I am documenting the whole build so others can follow along and build one themselves.

You'll also notice, I accidently dropped and cracked the screen. It still works fine, it just has that nasty crack.

<iframe width="560" height="315" src="https://www.youtube.com/embed/J79Xz3I8iyg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

