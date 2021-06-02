---
title: 'Keys and State Machines'
date: 2199-01-01
permalink: /posts/2021/07/keys-and-state-machines/
tags:
  - education
  - business
  - technology
---

Design patterns for character animation are about to get really complex
Story Telling Moments
Character animation is hard. And with real time systems, it’s going to get a lot harder.

In order to plan through the creation of a character’s performance, an animator uses design strategies to construct the motion. Since the days of Walt Disney and his nine old men, animators have relied on a method of quantifying the actions of characters into story telling moments. These moments are often referred to as “Keys.”

By drawing a handful of story moments and then “popping” between them, the animator can explore the timing and readability of the shot. Below is an example from Richard William’s Animator Survival Kit, showing the key drawings of a character walking to a chalkboard and starting to write. The story of the performance can be conveyed in three simple moments.


It’s sometimes very difficult to determine these keys. Realizing this difficulty and then the energy required to flesh out the action, it’s astounding that we only use the sequence of frames once. Entire movies (which are massive undertakings) are animated once, and then thrown away! The energy the animator puts in is equivalent to the visible experience they get out of it.

This linear output looks something like this:


While the art form in this sequential logic form is beautiful, it is highly inefficient.

In a real time system, such as that in an engine, the character’s actions are reusable. These actions can be changed based on the dynamic nature of the environment. Simply thinking of a character in terms of linear keys is too limiting. We need a way to quantify a character performance in a way beyond it’s single use.

Finite State Machines
A state machine is a mathematical design pattern where an entity exists in bracketed conceptual moments, called “states.”  States are an architecture that allow for a predetermined series of actions to be triggered, provided conditions are met.

For example, a character entity in an engine may be in a state of “walking” until it is confronted with a street to cross, to which it will change it’s state to “wait for the light.” States aren’t just visibly physical, like walking or jumping. Characters can be in a state of hunger, or in a state of anger, or in a state of existential crisis. When you begin to imagine states for characters, you start to understand how a character performs in a way outside of linear time. Designing keys in this mindset might look something more like this:



Video games already do this in a limited capacity to satisfy the requirements of a character’s action during game play. A character will begin in an “idle state” and when the user input commands it to run left, it will change it’s state to “run left.” By changing it’s state, the engine knows to play an animation clip of the character running to the left.

Increasingly, game engines are providing UI systems that allow for the development and design of character state machines. The example below is taken from Unity’s state machine which allows you to import animation clips and arrange them into a pattern that triggers at run time.


My hunch is that, as real time systems become more and more integral to the animation production process, character work will increasingly become reliant on the development of complex state machines. These massive state machines will not only drive the actions of the character, but the motivational nature of them as well.

Thanks for Reading. See you next week!


Here are some references to keep you going on Animation Keys and State Machines.

The Animator’s Survival Kit by Richard Willliams:

https://www.amazon.com/Animators-Survival-Kit-Richard-Williams/dp/0571202284

Game Programming Patterns by Robert Nystrom on State Machines:
https://gameprogrammingpatterns.com/state.html

Unity’s Documentation on State Machines:

https://docs.unity3d.com/Manual/StateMachineBasics.html

Unreal’s Documentation on Animation Blueprints:

https://docs.unrealengine.com/en-US/Engine/Animation/AnimBlueprints/index.html
