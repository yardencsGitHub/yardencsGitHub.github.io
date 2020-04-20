---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}
### Aim and Approach
<div style="text-align: justify">
<p>My research in systems neuroscience aims to understand how neurons cooperate in a massively interconnected network to generate high-level cognitive functions. Keeping the mind-body problem in mind, I believe that an answer to this question entails creating a mechanistic understanding of how from unreliable spiking neurons, connected with plastic synapses, emerge stable structures that support reliable functionality.</p>
  
<p>To dissect these basic mechanisms, my main approach is to use rich behavior repertoires to gain access to and create simpler representations of key elements in activity of neuronal ensembles. Purposely-using complex behavior may seem paradoxical but, put simply, in taking an elaborate data set or problem and projecting it onto many dimensions it is often much simpler to untangle separate components and identify relevant patterns. In fact, this principle underlies the success of deep artificial neural network algorithms and leading hypotheses about the function of the neocortex.</p>

<p>Another tenent I hold dear is the role of time as a key variable ("well duh" says the ethologist). Often, neural systems are treated as (pseudo) static - frozen computing machines. Such approach, in effect, flattens the dynamic nature of the brain and makes many processes, different learning algorithms for example, become indiscriminable. In all my experiments, the time and sequence components of behavior serve as strong constraints on potential theories that could explain my results.</p> 
</div>

## Canaries - Excellent singers and fantastic models for investigating neural mechanisms
<div style="float:left; margin: 5px 25px 5px 5px"><video width="450" height="322" controls> 
  <source src="/files/pics/CanaryAviary1.mp4" type="video/mp4">
Your browser does not support the video tag.</video></div>
<p style="text-align: justify">Canaries, like starlings, nightingales, and blackbirds (to name a few), are virtuosos capable of producing minute-long songs composed of many different individual notes. These notes, often called syllables, are sung in variable sequences that almost never repeat exactly and create an impressive repertoire. Such behavioral richness allows investigating the mechanisms responsible for producing complex behaviors but also creates challenges in annotating the different syllables and in statistical analyses.</p>  
---

<br/>
<img src="/files/pics/Canary_miniscope.png" style="float:right ;padding: 0px 0px 10px 25px" width="160px"/>
### Working memory in canary song syntax
<p style="text-align: justify">The brain executes precise motor elements, gestures or vocal syllables, in variable sequences. This cognitive ability allows creativity and evolutionary fitness and, when damaged by disease or aging, leads to marked motor sequence generation and comprehension dysfunction. A key property of motor sequences like language, dance, and tool-use are long-range syntax rules - element-to-element transitions depending on the context of multiple preceding elements across  seconds, or even minutes, of behavior. To create such syntax rules the memory of the long-range context needs to impact the premotor neural activity.</p>  
  
<p style="text-align: justify">Canaries are an excellent model for investigating the neural mechanisms supporting long-range syntax rules. Canary songs are comprised of repeated syllables, called phrases, that typically last one second. The ordering of phrases, like human language, follows long-range syntax rules [1], spanning several seconds. My <a href="/publication/2020-05-01-canary-paper-nature">latest work</a> exposed encoding of long-range context in the premotor circuits of freely singing canaries. This encoding occured preferentially in phrase transitions depending on long-range song context. This form of working memory could support the complex syntax rules in canary song - demonstrating, for the first time, a connection between neural activity and behavior in songbirds that shares time and sequence properties resembling human behavior.   
 </p>


## Primates - Excellent learners of abstract concepts
<img src="/files/pics/princess-bride.jpg" width="250" style="float:left ;padding: 5px 25px 5px 0px"/>
<p style="text-align: justify">
Primates often need to choose a course of action in complicated situations. For example, one may be forced to choose a wine goblet from which to drink and base this choice on multiple cues like the source of Iocane powder and the fact that your oponent bested both your giant and your spaniard. This commonplace scenario is an example of complex concept-based or rule-based behaviors - situations where a an action or a label is assigned to a multi-cue pattern based on a function of individual cues and their combinations. If both the labels and the cues are binary then deterministic concepts can be described by truth tables or by boolean expressions.
</p>
--- 

### Models of human visual-feature-based classification learning
<p style="text-align: justify">The task of labeling, or classifying, multicue patterns, as shown in the above example, is very common. The rules used for classifying a set of visual stimuli may change (e.g. in other occasions the cheese and the bread are more important cues for choosing which wine to drink) and we can quickly and advantageously adopt complex rule-based behaviors. But, even with N binary cues in each pattern the number of possible patterns is 2^N and the number of possible rules for classifying those patterns into 2 categories is 2^(2^N). Holding all those possible rules in memory is - inconceivable! - and still, humans can regularly and seemingly-effortlessly learn new rules, often using an impoverished sampling of the stimulus space.</p>
<br/>
<img src="/files/pics/HumanLearning.png" width="500" align="center"/>
In a set of psychophysics experiments I tested human learning of abstract rules using multicue binary patterns. My work replicated the observation [2] that population average performance depends on the classification rule but revealed that individuals learning the same rule seeing the same step-by-step order of patterns had very different learning curves.   


### Neural correlates of classification learning in monkeys 
<img src="/files/pics/MonkeyPlaying.png" width="331" style="float:left ;padding: 5px 25px 5px 0px"/>
## Artifical neural networks - Excellent toy models


Tools
=====
I enjoy developing hardware and software tools. Neuroscience research is, almost by its nature, interdisciplinary. Technical problems arising in research have, therefore, a unique interdisciplinary flavor. Creating solutions to these problems is fun and very rewarding because they immediately advance my work and contribute to the work of others. 
### TweetyNet - A machine learning tool for annotating complex song

### Next generation ultramicroelectrodes

### Miniaturized fluorescence microscopes

**References**:
[1]	Markowitz, J. E., Ivie, E., Kligler, L. & Gardner, T. J. Long-range Order in Canary Song. PLOS Comput Biol 9, e1003052 (2013).

