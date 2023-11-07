# RoyalBirb

## Implementation, and slight improvement of [Royal Skies LLC's](https://www.youtube.com/channel/UC2U5mRfclG1Rrr1ztNkpGKA) [Flappy Bird clone](https://youtu.be/C0IkqO1Qvng)

This open source project is meant to be studied by beginners, and also to be improved by more advanced users, the goal is to have the ultimate Flappy Bird clone implementation with comprehensible and documented source code that anyone can pick up to learn how to use Unity.

_**This project is based on [Royal Skies LLC's](https://www.youtube.com/channel/UC2U5mRfclG1Rrr1ztNkpGKA) tutorial on [Unity 3D: Programming Flappy Bird Gameplay (In 4 Minutes!!)](https://youtu.be/C0IkqO1Qvng), please, check him out if you have the time.**_

## What can I find here?
In this project you'll find an small variety of useful basics in Unity development, including but not limited to:

- A simple but clever acceleration algorithm with [linear interpolation](https://en.wikipedia.org/wiki/Linear_interpolation#:~:text=In%20mathematics%2C%20linear%20interpolation%20is,set%20of%20known%20data%20points.)
- Simple example of usage of Unity's own [Post Processing Stack V2](https://docs.unity3d.com/Packages/com.unity.postprocessing@3.1/manual/index.html)
- Creating objects that recycle themselves when exiting the [camera's frostum](https://docs.unity3d.com/Manual/UnderstandingFrustum.html) instead of just making new ones, reducing needed memory as well as the amount of [malloc](https://en.cppreference.com/w/c/memory/malloc) calls by the internal engine
