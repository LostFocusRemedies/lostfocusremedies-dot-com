---
title: "Silent Hill - Remake"
date: 2025-03-20
draft: false
description: "a description"
tags: ["example", "tag"]
---

## Intro
{{< 
    video src="videos/SH-Intro_sofar" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}

This is a re-imagined version of the Famous Silent Hill Intro, for the PSX.  
I'm deeply nostalgic of this game, and I've been using this as a pet project to hone my skills all around the 3D Pipeline. 

It's a long journey, and I'm using this as a chance to experiment with new stuff aswell. 

It started by using:
- Blender for Sculpting, Modeling, Layout and Render
- Maya for Rigging and Animation

But At the moment it's more like this: 
- **Blender** for **sculpting**, **modeling**
- **Maya** for **Rigging** and **Animation**
- **Unreal Engine** for **Rendering** and **Layout**

And many iterations inbetween, i.e. I used Arnold and Pixar Renderman aswell. Both of which I loved, but doing everything from my laptop, I ended up deciding to stick to UE5, that allows me to preview the animation very well (and in the meantime I got interested in Gamedev, so I'm exploring all the aspect of preparing assets for realtime performance aswell.)

## Characters 

### Design
It all started with what I'm most familiar with, drawing the charcater design. That's fun and quite comfort zone for me, having many years of experience drawing and doing design. 

![The Characters Lineup](/images/character_design.png "The Characters Lineup")

### Modeling

{{< gallery >}}
    <img src="/SilentHIllIntro/t-poses/alessa.png" class="grid-w33" />
    <img src="/SilentHIllIntro/t-poses/cheryl.png" class="grid-w33" />
    <img src="/SilentHIllIntro/t-poses/dhalia.png" class="grid-w33" />
    <img src="/SilentHIllIntro/t-poses/harry.png" class="grid-w33" />
    <img src="/SilentHIllIntro/t-poses/mom.png" class="grid-w33" />
{{< /gallery >}}

I'm working on this project on left over times. So, it's been on-going for a couple years now, and it's fun to see how my skills improved with time! 

{{< carousel images="{/SilentHIllIntro/t-poses/Lisa-old.jpeg, /SilentHIllIntro/t-poses/Lisa-old.jpeg}" >}}

{{< 
    video src="videos/cybil-turnaround" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}

### Rigging

I'm Rigging in Maya, and putting a lot of emphasys on having a very good topology. 
This is because it makes the rig a lot lighter, because you need a lot less corrective joints or blendshapes. 
{{< 
    video src="videos/lisa-turnaround" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}

It takes a little longer at the start, but it pays off very well.  
{{< 
    video src="videos/cybil-deformations" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}

## Environments
### Modeling and lookdev

As said earlier, the environments are modeled in Blender, then brought over to UE using USD workflow, that makes it incredibly convenient to jump back and forth.  

{{< 
    video src="videos/Cafe-Environment" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}


## Animation
The animation is done in maya, then brought over to UE5 throug Alembic cache. Nothing remarkably interesting here, at least for me, same same. 

{{< 
    video src="videos/040_anim_v09_pb" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}


## Render & final look

It's all done in UE5, I try to get the viewport image as close as possible to the final look, this totally helps with keeping things speedy. 

Before using UE5, using traditional offline renderers sucha s cycles, arnold or renderman, I found myself doing a lot of compositing in After Effects, and, while I enjoy it a lot, if also felt like each shot was getting several Gb of data, without necessarily making it a lot better.  
There's definetely diminishing returns into the full VFX production workflow, especially on a one-man-one-laptop project. 


{{< 
    video src="videos/040_v02" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}

Woah, you read that far? Cheers, and thanks, I appreciate it. 
