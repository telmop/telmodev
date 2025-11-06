---
title: "How to detect GenAI Images and Videos"
date: 2025-11-06T14:20:01Z
draft: draft
toc: true
images:
tags:
  - AI
  - DeepFakes
---

It is impossible to go online in late 2025 and not be flooded by truck loads of deepfakes and other AI-generated content.  Some of this content is harmless, like funny animal videos and obvious memes. Some can be dangerous and is actively provocative/incendiary, engineered to get a (mostly negative) reaction.

I don't think it is possible to detect all fake content that comes our way. Some of it is innocuous or irrelevant to our lives. It's fine if that cute dog you saw wasn't real - no harm done. But if something gets a strong reaction from you, or is designed to get a strong reaction from others, we should pay close attention. And, fortunately for us, there are some good signs that help detect AI slop. Every time I find something that surprises me, or that I find hard to believe, I try to look for these signs. I'm not always on the look-out: being online is a terrible experience if we're constantly on watch. But doing so for controversial/purposefully viral content is a good idea.

Below I list the main signs I look for to detect generated content. Are these methods perfect? No, nothing is. And models keep getting more realistic. Maybe at some point in the future we'll need forensic techniques to tell deepfakes appart. But right now we can be pretty accurate at detecting this kind of content.

# The warning signs
First, a couple of general comments:
* Always look for watermarks - they're a dead giveaway! Certain GenAI tools, like Sora2, add a watermark to their content (see the image below).
* Be suspicious of weirdly cropped and low resolution content. As you'll see in the list below, a lot of the signs require that you zoom in and look at small/background details. A way to hide those artifacts is to blur the content - something I have seen in the wild. As a rule of thumb, always zoom in on any suspicious content, and be skeptical about it if it is low resolution.
* Be suspicious of perfection. People are imperfect, and so is nature. If anything looks "too perfect", "too cute", this can be a sign of artificial content. Look

These signs by themselves don't prove that something is fake, but are an indicator that you should pay closer attention.

# What to look for
Below is a list of common artifacts to I look for.

## Pay attention to the background
Many models do a great job at generating whatever is the main focus of an image/video, but miss some details on the background. Common artifacts to look for are deformed people, deformed body parts (in particular hands), weirdly shaped objects, etc.

In particular, be mindful of blurred/defocused backgrounds, particularly in photos. Notice how the images you see on [This Person does not exist](https://this-person-does-not-exist.com/en) usually lack much background detail.

When I say background, I don't just mean the objects in the back, but anything that is not the main focus of the image/video. This includes hands, incomplete objects/parts of the body, "non-sensical" blobs, etc.

## Look at the text (and font)
I don't mean text that was overlayed in the image or video. I mean text in objects or walls. Models have gotten much better at this than before, but they still generate funny looking text: inconsistent fonts (look for words where the same letter appears multiple times but looks different), the text changing between frames if it is a video, non-sensical words, overlapping text, etc.

## Think about the physics of the scene
This one is particularly useful for videos, but applies to images too.

If motion looks unrealistic, with objects moving in weird ways or past each other, or getting deformed in unexpected ways - e.g., legs bending back, you're likely looking at AI generated content.

Even for images, it's good to look for poses and how things stand. For example, in the image below, notice how the mother bird is not standing on the branch - you only see the little birds' feet. Because she cannot be flying, as her wings are covering the offspring, this is a good giveaway that the image is fake.

Other good indicators are lighting of a scene (e.g., inconsistent shadows) and how clothing folds (particularly sleeves and clothe boundaries, buttons, etc).

Again, as with everything else on this list, models keep getting better. Expect that deepfakes will get more realistic with time, but be sure to look for quirks.

## Cartoonish colors/textures
This one is hard to put into words, but once you get used to it, it's usually easy to detect. There is something off with a lot of generated content. Maybe it's the colors, maybe it's the lighting, maybe it's the texture. Look at the examples below and see for yourself.

## Beware of flickering
This one is for videos. As AI generates a video, frame by frame, it sometimes takes a few frames to decide how an object will look. Because of this, you can see objects "flicker" and change shape, *particularly around the edges*! Look for objects in the background of the scene! This can happen for text as well, so pay attention to it. Another time when you might see these artifacts is when an objects gets totally or partially out of view, and then comes back into view.

# Putting clues together
I usually look for more than one artifact to decide whether something is fake. Some signs are stronger than others: for example, in the bird image above, the image is very well generated, but the fact that the mother bird has nowhere to stand is a strong giveaway. Same for the Tesla video: the plug is in the wrong place. Similarly, if you see a hand with 6 fingers, odds are the photo is fake.

Other times, there is not one big giveaway but many smaller signs: the colors look off, some small objects look off, etc. This is why low resolution content is challenging. Low resolution is perfect to hide a lot of the artifacts I look for.

that something is fake. There are image/video compression artifacts that can explain some of the individual signs I mentioned. But if the post you're seeing has multiple signs, that's usually a strong indication that it is fake. You don't always have to look for multiple signs: sometimes there is an obvious problem with the image (like 6 fingers, a cable plugged to the wrong place) that immediately tell you it was generated.

I will share some examples that took me multiple careful exhaminations to spot.

Warning signs:
In particular, beware of low resolution content. Old videos might have low resolution - that's how the tech was back then. But for new videos, be suspicious. Low resolution is commonly used to hide the telltale signs above. In a low resolution image it's hard to spot
* Content is low resolution. Being low resolution is not a sign that something is fake. However, reducing resolution is a method used online to (maliciously, if you ask me) disguise genAI content as real. Lack of resolution makes it hard (maybe even impossible) to spot the obvious signs of deepfaked content.

# Practice: Some examples

TODO


# Summary
As GenAI content is becoming more realistic, it will likely get harder to separate fact from fiction. I hope the tips I shared above give you an edge and incite you to be more suspicious of what you see online. Because in many ways, what AI is doing is lowering the cost for fabricating content. Fake news have existed since forever, but it was much harder in the past to create and spread fabricated content. In the end, if something seems strange, pay close attention and when in doubt, be skeptical. In particular if it is content that plays into your biases. If you don't like a group of people and you find said group admitting to criminal behavior, ask yourself - why would they admit it? Maybe the person you're seeing really is that stupid, or maybe you're looking at a fake.

If you like this post, be sure to share it with your friends and family. It would mean a lot to me!
