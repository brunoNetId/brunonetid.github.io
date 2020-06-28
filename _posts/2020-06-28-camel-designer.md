---
layout: post
title: Apache Camel Visual Designer
feature-img: "assets/img/posts/designer-intro/intro.gif"
tags: [Camel, Apache Camel, VSCode, Visual Studio Code]
table-of-contents: 
  <ol>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#visualisation-is-an-advantage">Visualisation is an advantage</a></li>
    <li><a href="#exploring-new-ideas">Exploring new ideas</a></li>
    <li><a href="#final-words">Final words</a></li>
  </ol>
---

This is *Camel Designer*, a new approach of visually modelling *Apache Camel* integration processes in which I've been working. It welcomes experienced *Camel* riders, and provides an easy entry point for those exploring the most popular open source integration framework for the first time. The tool comes as an extension you can install in *VSCode*.

### Where to find it

If you don't want to read any longer because you can't wait to give *Camel Designer* a spin, here's *Visual Studio Code*'s marketplace where the extension lives: [*Camel Designer*](https://marketplace.visualstudio.com/items?itemName=brunoNetId.camel-designer)

<p align="center">
   <img src="{{site.baseurl}}/assets/img/posts/designer-intro/camel-icon.png" width="35%" />
</p>

<br>

## Table of Contents

1. [Introduction](#introduction)
2. [Visualisation is an advantage](#visualisation-is-an-advantage)
3. [Exploring new ideas](#exploring-new-ideas)
3. [Final words](#final-words)


## Introduction

*Apache Camel* has a fairly intuitive DSL (domain specific language) to define integrations. However, it's also fair to say that integration use cases in general can rapidly become tricky and challenging to construct.

*Camel* is so powerful and rich in functionality that beginners may find themselves undecided on the optimal approach to choose when resolving the problem at hand.

Very experienced developers don't need to spend much time thinking about how to tackle the challenge. They use their know-how and rely on text code editors enabled with rich extensions/plugins that accelerate their work.

Visual tooling can certainly guide learners in their first steps but, even as an expert, it can be beneficial and increase your productivity.


## Visualisation is an advantage

To back the statement above and to illustrate with an example, let's make a parenthesis for a minute and go early back in life to observe a baby's learning process, as it gives us clues on how the brain works.

When a newborn opens his/her eyes, everything he/she sees is a blur. Among the various visual effects the baby can't understand at birth, we find attributes like lighting, or facial recognition or perceive depth, and therefore lacking the ability to interpret the 3-Dimensional space. The baby however, since the time inside the mother's womb, has been listening to voices and the human language well before using sight.

The formidable progress the baby makes developing their viewing skills to see the world greatly outpaces the time required to understand the human language. From this comparison, I think it's reasonable to deduce that the human brain is equipped with a special purpose-built chip that empowers our visual cognitive capabilities.

<div style="text-align: center">
<img style="padding-right: 0px;" src="{{ site.baseurl }}/assets/img/posts/designer-intro/baby-sight.png" width="40%">
<img  style="padding-left: 0px;" src="{{ site.baseurl }}/assets/img/posts/designer-intro/image-blur.gif" width="30%">
</div>

While perceiving the world using sight is a task solved in a more instinctive way, understanding language demands greater brain power. We seem in a way hardwired to assimilate visuals, but we need extra time to improve our neuronal network before we can successfully encode-decode information. In short, we're faster to process imagery than interpreting information.

So it's no surprise that in all industries, visualisation is a very important instrument used to exploit our cognitive strengths. Think for instance about how essential marketing campaigns are and how critical the role of visualisation plays. Looking for more familiar examples, most of us use graphs and slides in our daily work to be more effective when presenting to an audience. Also think about how much faster it is to communicate feelings using 'emoticons' rather than typing them down. And what about sharing jokes... animated GIFs, and short funny clips are the winners. It seems the world is in a rush, information needs to flow fast and furious.

Similarly, in the software industry, there is no time to waste. It seeks constant improvement, ideally reducing the time to acquire new skills to a minimum. This, when done effectively, ultimately translates in lowering costs and augmenting productivity.

So why wouldn't we also try to take advantage of visualisation?<br>
We must give it a go. 


## Exploring new ideas

*Camel Designer* is not just about rendering intuitive imagery, it is about empowering the developer. We know that traditional visual tools deliberately keep the auto-generated code hidden from the developer in files. They are accessible but not easy to understand.

*Camel Designer* attempts to maintain a bi-directional flow between the classic developer code view and the visual modeler so that the relationship between the two is maintained open, keeping both worlds connected. Experienced developers, to start with, can work in the code and see how changes affect the visual model. On the other hand, visual developers working on the graphical editor, and perhaps not familiar with *Apache Camel*, can quickly learn how the *Camel* building blocks are used in the source view.

![]({{ site.baseurl }}/assets/img/posts/designer-intro/editor1.jpg)  

The picture above shows the *VSCode* extension, where you can see how the code editor and visual editor are side to side. When in *VSCode* you open a *Camel* XML file (left hand side), you can open the visual view (right hand side) which will graphically render the *Camel* code. When working on the visual editor, all changes will automatically be applied in the source code view.

The above sets the base principle, but also opens new interaction options. The tool is currently under development, and therefore only a number of features are available. As progress is made, the intention is to identify new ideas that bring productivity value.

![]({{ site.baseurl }}/assets/img/posts/designer-intro/navigation.jpg) 

As illustrated above, one of the implemented ideas is the code navigation system. Your source code may end up having many *Camel* route definitions (process flows), making it very tedious to find the visual artifacts you're looking for. With *Camel Designer*, just click on any code line in the XML editor and the tool will present on the graphical canvas the visual object that represents the selected *Camel* element.

## Final words

I purposefully didn't say much about other features *Camel Designer* includes, I rather let you discover them and encourage you to try the editor first hand. *Visual Studio Code* makes it very easy to find and install extensions, and there's a reason why it gained so much popularity and became the editor of choice for many. Despite *Camel Designer* still having to cover a lot of ground, it already provides a taste of what it tries to achieve.

I've used visual integration tools since year 2000 and have extensively coded, very happily, with text-only editors. Because I understand very well both worlds, I can easily empathise with those on both sides of the fence. Obviously, this initiative I'm invested in shows how beneficial I think visual tooling can be, but I would love to hear your thoughts on the subject, and if you happen to try the tool, I'd love to hear what opinion you extract, or any other kind of feedback you'd like to share.

<br>

### Resources

*Camel Designer* in *VSCode*'s marketplace:<br> 
[https://marketplace.visualstudio.com/items?itemName=brunoNetId.camel-designer](https://marketplace.visualstudio.com/items?itemName=brunoNetId.camel-designer)

GitHub project:<br> 
[https://github.com/designer-for-camel/camel-designer](https://github.com/designer-for-camel/camel-designer)

---

<br/>




