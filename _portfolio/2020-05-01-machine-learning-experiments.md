---
title: "Machine Learning Experiments"
excerpt: "Fun and Games with Neural Networks, GANs and other AI.<br/><img src='/images/machinelearning_header_01.png'>"
permalink: /portfolio/machine-learning-experiments
collection: portfolio
---

AI is rapidly advancing into computer graphics. While it is still somewhat early for these technologies to be easily accessible to the artist, within a short period of time we will find ourselves experiencing a boom of productive creation. For more on my thoughts on the evolution of artificial intelligence in animation, [please see my post here.](http://nyeguy.github.io/posts/2021/07/2020-05-15-machine-learning-and-animation)

Otherwise, have fun exploring some of the nonsense below.  


### ShatnerGAN

For whatever reason, I spent a week ripping Captain Kirk shots from the original Star Trek series and training StyleGAN2 from NVidia. This experiment had 15000 close ups of James T Kirk, and the model was trained for 5000 steps.
<br>
Software: 4K Video Downloader, Autocrop, and RunwayML

<iframe width="560" height="315" src="https://www.youtube.com/embed/THBQ1oNl2yU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Put a GAN  on it! - Stealing Beyonce's Motion Data

During my class with Derek Shultz I used Beyonce's "Put a Ring on It," to experiment with a number of models that existed within the AI model bridge software called [RunwayML](https://runwayml.com). This is the first time I integrated machine learning models into my after effects workflow. While it's essentially pure fun, it allowed me to experiment with a number of the models and get a sense of their capabilities.
<br>
Software: Runway, After Effects, Photoshop

<iframe width="560" height="315" src="https://www.youtube.com/embed/mLzNFjAsZdo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### YangGAN: Andrew Yang's Essence in AI #yanggang #humanityforward

After my Captain Kirk GAN, I decided to try another human trained GAN. I found a clip of Andrew Yang speaking about the advancement of AI journalists, and was inspired to match the audio with a latent space walk of a trained GAN. This was trained on about 4000 images of Andrew Yang that I scraped from various interviews. The head was cropped and run through an image adjustment recipe I developed with Python and Image Magik. I trained the GAN in Runway using StyleGAN2.
<br>
Software: 4K Video Downloader, Python: Autocrop and Image Magik, and RunwayML

<iframe width="560" height="315" src="https://www.youtube.com/embed/jsIg3NpxbhU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



### Ride the Train! - Experiments with Image Segmentation

This was an experiment to play with Image Mapping Segmentation. I had seen a number of experiments with Image Mapping but had seen little with using it as a renderer. I used shaders in Maya that were matched to the Image Mapping set up in RunwayML. I rendered each layer through Runway and composited it in After Effects. The technology is far from functional, but the promise is there.
<br>
Software: RunwayML, Autodesk Maya, After Effects

<iframe width="560" height="315" src="https://www.youtube.com/embed/RBsi1s6eBmQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Machine Learning Motion Model Experiments

My primary interest in machine learning is experimentation with animation data and motion. These were some experiments I ran to see what motion model got what result. My take away was that the clips needed to be "normalized" to get a good read. That's why I created a template to track the video.
<br>
Software: 4K Video Downloader, Autocrop, and RunwayML

<iframe width="560" height="315" src="https://www.youtube.com/embed/f_rxk7G19LU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Fun with CheapFakes

This is a fun model and easy to use. I scraped some Arnold Schwartznegger clips from youtube, and had a friend, Daron Jennings, improvise some clips. It was simply a matter of running the model with the appropriate components, and then compositing it in After Effects. It might be something fun to use for the future. 
<br>
Software: Wav2Lip, After Effects

<iframe width="560" height="315" src="https://www.youtube.com/embed/8h2Xzf8uGxk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
