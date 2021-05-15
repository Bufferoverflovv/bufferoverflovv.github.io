---
name: VR Prototypes
tools: [VR, Oculus, Physics]
image: https://streamable.com/e/49zx93?autoplay=1&nocontrols=1
description: A collection of several VR prototypes I created to get familiar with VR interactions. The prototypes include things such as weapon mechanics, shooting, active ragdolls, magic, stab & chopping mechanics and more.
---

# VR Prototypes

For christmas in 2019 I was gifted an Oculus Rift S and fell in love with VR games. Naturally of course I really wanted to see how development and interactions worked in VR in comparison to creating standard games. I found in some ways that interactions were easier to make but also needed some abstract thinking to create. I had a few ambitious ideas for VR games that I wanted to make but found myself often doing more R&D than actual development of game. So this is more of an assortment of clips and things I made for VR in Unity. 

# VR COD Zombies 
Inspired by the Pavlov COD Zombies mod I wanted to try and create a standalone version as my first prototype. This prototype was a bit messy and was never completely finished but I ended up creating a lot more optimisations later on and some interesting interactions. 
{% include elements/video.html id="jP2rsLGFnfA" %}

# Realistic reflex sight & Active Ragdoll
I created a realistic reflex/red dot sight that is basically just a parallax shader with a mask. It does have accurate range finding. You can also see some interaction where I knock over a zombie. 
<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/25sjjx?autoplay=1&nocontrols=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

# Stab mechanics, Active Ragdoll & Decaptiation 
Tried to recreate the cool stab mechanics from Boneworks and imported an open source skinned mesh slicer. The results were cool but could be better! 
<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/n9ac1b?autoplay=1&nocontrols=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

# VR Weapons Framework
I was trying to create my own weapons framework from raycasts to projectiles with real world trajectory physics and realistic scopes and weapon mechanics such as reloading, cocking, priming etc. I didn't get around to finishing the entire framework as at the time I started to get interested in VR Multiplayer. The intention was to create a shooting range demo with the different gun interactions and put it on Sidequest. 
## Double Barrel Shotgun 
The double barrel uses a custom joint with hard limits to simulate the break action. Each barrel is individually loaded meaning that if you loaded one then it would only shoot from the barrel it was loaded in. I used Gaussian Distribution Sampling and the Marsaglia Polar method to create realistic shotgun spreads. The results came out pretty well and I was even featured on "Best of made with unity" for this one interaction. 
<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/49zx93?autoplay=1&nocontrols=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

## Bolt Action Rifles
Naturally after double barrel shotguns I wanted to try my hand at bolt action. The bolt action was particularly tricky as I was trying to do with joints again and hard limits but found that joints probably weren't suited for this type of interaction. If I was to go back, I would redo this without joints. 
<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/jna49v?autoplay=1&nocontrols=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

# Telekinesis 
Just a simple experiment with telekinesis.
<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/lu71vr?autoplay=1&nocontrols=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

# Cooking and other interactions
As my first prototype and research I started working on a cooking game in which you would be the innkeeper and feed meals to patrons. I used dynamic mesh slicing (meshes were not precut) and created a cooking system that featured bouyancy for soup. I also did a little bit of work on wood chopping and starting a fire. 
## Chopping carrots and cooking carrot soup
<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/llxed7?autoplay=1&nocontrols=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

## Wood chopping and starting a fire
<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/ybwh8j?autoplay=1&nocontrols=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>
