---
title: "WebbCompare"
tags:
- Development
- Astronomy
- Visualization
---
![](attachments/Pasted%20image%2020220715164721.png)
<iframe src="https://ghbtns.com/github-btn.html?user=johnedchristensen&repo=webbcompare&type=star&count=true&size=large" frameborder="0" scrolling="0" width="170" height="30" title="GitHub"></iframe>

## What is it?
[WebbCompare](https:\\www.webbcompare.com) is a tool I build to compare James Webb Space Telescope (JWST) images to Hubble Space Telescope images.
It is a website designed for a general audience to appreciate the beauty of the universe that we are slowly uncovering.

The site shows how large of a leap in scientific capability the James Webb Space Telescope is, and emphasizes that its success is a major milestone in our history.
## Why did I make it?
I have always been fascinated by Hubble's images. Growing up I loved watching PBS Space documentaries and going to planetarium shows where I gawked over the beautiful images and was humbled by the un-comprehensible size and distance of the stellar subjects.

The fact that the JWST is capable of far outperforming the images I loved as a child was another humbling experience. These images are just the beginning of a new chapter of human exploration, and I'm optimistic that what remains to be discovered will continue to humble and inspire everyone that watches.

## How was the reception of the tool?
<style>
.twitter-tweet{
margin: 1em;
width: 800px; !important;
}
.tweet-container{
display: flex; 
justify-content: space-between
}
</style>
### Science Communicators 
<div class="tweet-container">
{{< tweet user="hankgreen" id="1546958021086965760" >}}
{{< tweet user="ChrisG_NSF" id="1547019017885552640" >}}
</div>

### Scientists and Experts
<div class="tweet-container">
{{< tweet user="astrocaits" id="1546954277226254337" >}}
{{< tweet user="nbatalha" id="1547233449513103361" >}}
{{< tweet user="CosmicRami" id="1547062377585053696" >}}
</div>

### General public

<div class="tweet-container">
{{< tweet user="wbelote" id="1547026840945979393" >}}
{{< tweet user="penguinsrule27" id="1547270256607088641" >}}
</div>


## How it's made 
WebbCompare uses [OpenSeadragon](https://openseadragon.github.io/) for zooming and panning around both the Hubble and Webb images.

It is hosted using Github Pages.
