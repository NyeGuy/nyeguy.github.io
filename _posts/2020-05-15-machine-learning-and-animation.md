---
title: 'Machine Learning and Animation'
date: 2199-01-01
permalink: /posts/2021/07/discovering-ml-art-with-runway/
tags:
  - education
  - business
  - technology
---
As the tools become more accessible, neural networks may soon be driving the performance of characters


I find myself involved in conversations where I ask graphics artists if they feel threatened by AI (artificial intelligence). Many animators think that being in a "creative" occupation means that they are safe. For many, it's okay to think automation will wipe out auto-callers and Uber drivers, but keying a character performance is something that we won't have to worry about for a while.

I used to be one of these people, but now, I'm not so sure.

*Fake it til’ ya Make it*
The internet continues to show us examples of “deep fakes”where mathematical image recognition models have allowed for the creation of fully manufactured digital characters. Upon viewing this, there is an initial reaction of "that's crazy," followed by a dismissive "wave of the hand." I think there is a misunderstanding what the neural network is really doing.

It's easy to confuse this “puppeting” of Vlad Putin or Elon Musk as simply a real time one to one, like that of a performance capture system. Or that the video is is composited or mixed into the pixels in some way.

But this technology is actually generating an entirely new performance.


*Neural Networks*
Honestly, I have only just begun my journey to understand how neural networks work. In many ways they are still a black box of mathematics full of PhD level vocabulary that a humble unfrozen cave man animator like me can't wrap their mind around. I can’t tell the mathematical difference between a Lambert and a Phong, but I absolutely know the difference in the way they look and when to use them. Similarly, it will be hard for me to describe the calculations in a General Adversarial Network, but I’m starting to see the possibilities of what it can produce.

With only a few weeks of reading - and the help of the classes like IPT@New York University (https://ml4a.github.io/classes/) - I'm fairly confident, that at it's core, neural networks use a whole lot of data, to learn how to make an input on one side come out as something generative on the other. It’s a system that makes guesses (or predictions) and the more data you cram into it, the better those guesses get.

This image has an empty alt attribute; its file name is https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fc8b8c29d-fda5-4623-b666-650b2af6d533_565x346.jpeg
The whole point of a neural network is to recognize features, or patterns that are not explicitly called out in the data set. These patterns are what the network uses to construct wholly new entities (guesses), that look and feel almost entirely like the original data set. Essentially, with enough data, it can fake a new entity that is nearly indistinguishable from the original. The question becomes:

What data do we use to animate?
From Light Cycles to Dinosaurs
In 1982, to create the illusion that 3d objects moved across the screen, the animators on Tron had to stand over the shoulders of engineers and instruct them to plot out thousands of individual x, y, z coordinates. By the mid 1990’s, instead of entering individual coordinates, software UI’s had become accessible to allow animators to key and refine the motion of an object. This made moving dinosaurs in the computer a reality.

This image has an empty alt attribute; its file name is https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Faa4445fa-526d-4fdc-b0f8-1533a0cb6ed0_920x380.png
The curve editor, now commonplace in animation software like Maya and Blender, took 15 years to imagine and develop. It is a way for artists to visualize the acceleration data of 3D objects, and a way for those artists to communicate their intent to the software.

Whether the data is from captured human performance or “hand keyed,” curve editors are the common language of motion data in the animation world.

Animator Intent = X, Animated Character = Y
This image has an empty alt attribute; its file name is https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fe79ee1ef-3e09-44b5-8124-c5df6f303b27_1195x602.jpeg
So, if a neural network could be fed motion data and “learn” how a human moves, it might be possible for it to learn what the animator is trying to communicate and generate predictions of what makes a good animated performance.
Actually, the development of this, “animator intent = X” variable might be the easy part. We have enormous databases of “scrapable” human motion, considering existing deep learning models like PoseNet could pull data from an ever infinite library on Youtube.

The features which lead to the Y variable, and the question that I’m going to scratch at is:

Could a model be developed where the features generate a great animated character performance?
From Academics to Artists
Up until now, machine learning is something only the academics played with - and now big tech - as these early scientists have been gobbled up by the tech titans like Uber, Facebook, Google and Tesla.

Like the engineers and light cycle inputs, only tensor flow python-heads could enter the parameters for a ML model. However, a new wave of UI thinking is now making this approachable to us unfrozen cave men animators. Unity, a powerhouse 3D game engine, has jammed “ML agents” into their software to facilitate ingesting tensor flow models. And a stand alone GUI called Weka, allows for non-coding explorations of deep learning models.

This image has an empty alt attribute; its file name is https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fca182249-0347-4a62-85e9-363031ab165f_1226x391.png
However, a new visual interface called Runway ML is the first, of what I see, of the development of artist-friendly machine learning tools. There will increasingly be less of a need for artists to get their hands dirty in the code of neural networks, as services like this will provide an accessible way for artists to integrate the thinking directly into their existing animation work flows.

Maybe even accessible to a cave man animator like me.

That’s it for this week, thanks for reading. Please subscribe and join the conversation.

This image has an empty alt attribute; its file name is https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Ff61b49a5-40b9-40e3-9b47-e185e113537d_612x108.png
Reference:
ITP@NYU / Machine Learning for Artists: https://ml4a.github.io/classes/

Daniel Shiffman’s Coding Train: https://www.youtube.com/channel/UCvjgXvBlbQiydffZU7m1_aw

Machine Learning Mastery:

RunWay ML: https://runwayml.com/

The TensorFlow Playground: https://playground.tensorflow.org/

PoseNet Machine Learning Model: https://github.com/tensorflow/tfjs-models/tree/master/posenet

Andrew Price (the blender guru) made a similar argument: https://youtu.be/FlgLxSLsYWQ
