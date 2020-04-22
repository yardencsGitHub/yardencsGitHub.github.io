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
Primates often need to choose a course of action in complicated situations. For example, one may be forced to choose a wine goblet from which to drink and base this choice on multiple cues like the source of Iocane powder and the fact that your oponent bested both your giant and your spaniard. This commonplace scenario is an example of complex concept-based or rule-based behaviors - situations where a an action or a label is assigned to a multi-cue pattern based on individual cues and their combinations. If both the labels and the cues are binary then deterministic concepts can be described by truth tables or by boolean expressions.
</p>
--- 

### Models of human visual-feature-based classification learning
<p style="text-align: justify">The task of labeling, or classifying, multicue patterns, as shown in the above example, is very common. The rules used for classifying a set of visual stimuli may change (e.g. in other occasions the cheese and the bread are more important cues for choosing which wine to drink) and we can quickly and advantageously adopt new complex rule-based behaviors. But, with N binary cues in each pattern the number of possible patterns is 2^N and the number of possible rules for classifying those patterns into 2 categories is 2^(2^N). Holding all those possible rules in memory is - inconceivable! - and still, we regularly and effortlessly learn new rules, often using an impoverished sampling of the stimulus space. The question of how we do it and what simplfying assumption we make is interesting both psychophysically and clinically. </p>

<img src="/files/pics/HumanDynamics.png" width="500" style="float:left ;padding: 5px 25px 5px 0px"/>
<p style="text-align: justify">(A) Graphic representation of the mixture of features-based model. The classifier is a hyperplane in the space of features, f, of the pattern x. The decision boundary is a plane in the features space. (B) Graphic representation of learning dynamics. At the start of the experimental session, subjects’ decisions can be explained in terms of a hyperplane in the high dimensional space of pattern features. During the learning process, this hyperplane is shifted and rotated in the features space, getting it closer to the correct rule.</p>
---

<p style="text-align: justify"><a href="/publication/2013-01-08-cohen-schneidman-pnas">My work</a> in human psychophysics replicated the observation [2] that population average performance depends on the classification rule and revealed that individuals learning the same rule can have very different learning curves despite seeing the same step-by-step order of patterns. To capture this individuality, I modeled the subjects' belief about the rule as a probabilistic classifier based on visual features of the patterns (A). To describe the learning dynamics I used a simple reinforcement-learning step that shifts that belief (B). This framework captured individual learning behavior surprisingly-well and reflected the important role of subjects’ priors. To "cross validate" the fit to individual subjects I showed that these models predict future individual answers to a high degree of accuracy and can be used to build personally-optimized teaching sessions and boost learning.
</p>

### Neural correlates of classification learning in monkeys 
<img src="/files/pics/MonkeyPlaying.png" width="331" style="float:right ;padding: 5px 0px 5px 25px"/> 
<p style="text-align: justify">Classification tasks are used to explore learning strategies in healthy human subjects and in patients. The neurophysiological underpinnings of multicue pattern classification are commonly studied in monkeys - animal models capable of performing complex visually-guided tasks. But, in many of these animal studies it is impossible to observe how neurons form representations as learning progresses and gradually become relevant to the final classification being imposed. This is mainly because most experiments follow extensive training and the neural correlates relate more to the final representation, perception, and recognition, and less to the gradual learning process. The extensive training also prevents investigating many rules in the same animal - limiting general conclusions. </p>

<p style="text-align: justify"><a href="/publication/2019-02-28-cohen-schneidman-paz-biorxiv">My work</a> took an opposite approach. I trained my monkeys, Gato and Dimi, to perform classification learning tasks on 3-bit binary patterns (my human subjects used 4-bit and 5-bit patterns). Then, I recorded activity of single neurons while the animals learned eight conceptually-different rules they never encountered before. To investigate neural dynamics I represented single neurons' changing stimulus selectivity as a trajectory in the space of visual features of the patterns - echoing the approach I took in modeling human beliefs. Since the rule being learned can be described as a direction in this space, my approach allowed comparing learning-related neural dynamics across sessions of different rules in geometric terms - projections of the neural trajectory onto the rule. This framework exposed different learning-related dynamics in various brain regions - suggesting different roles in learning - and also allowed predicting next-day performance from the neural activity.</p>


## Artifical neural networks - Excellent toy models
<img src="/files/pics/NeuronModels.png" width="500" style="float:right ;padding: 5px 0px 5px 25px"/>
<p style="text-align: justify">David Marr famously outlined a framework for analyzing neural mechanisms in three conceptually-different levels - A certain cognitive function at the top level is carried out by a mid-level algorithm that is physically-implemented by neural activity at the bottom-level. The field of Systems Neuroscience is substantially-shaped by Marr's framework. My experiments in primates and songbirds purposefully-use time scale separation between ongoing neural activity and its behavior correlates to tease apart the physical and algorithm levels. A complementary approach to dissecting neural mechanisms uses simulated neural networks as toy models - In-silico animal models allowing access to all of Marr's levels. </p>       

### Developing an empirical characterization of motor learning in biological systems  
<p style="text-align: justify">Movement control ties brain activity to measurable external actions in real time, providing a useful tool for both neuroscientists interested in the emergence of stable behavior, and biomedical engineers interested in the design of neural prosthesis and brain-machine interfaces. My work approached the question of motor skill learning by introducing artificial errors through a novel perturbative scheme, amenable to analytic examination in the regime close to the desired behavior. Numerical simulations then demonstrate how to probe the learning dynamics in both rate-based and spiking neural networks - revealing both properties of the learning algorithm and internal dynamics of the toy models. These findings stress the usefulness of analyzing responses to deliberately induced errors and the importance of properly designing such perturbation experiments. This approach provides a novel generic tool for monitoring the acquisition of motor skills. </p>

<img src="/files/pics/ErrorSurface.png" width="300" style="float:left ;padding: 5px 25px 5px 0px"/>
<p style="text-align: justify">Conceptual illustration of perturbation in a nonlinear system. Perturbations are akin to kicking the ball, which represents the fixed point in steady-state at the origin of the error manifold, along the white arrows. The learning response, represented by the red arrows, depends on both the direction and magnitude of the perturbation and can be, like the linear case, simply contracting (i) or also rotating (ii,iii).</p>
---
<br/>

Tools
=====
I enjoy developing hardware and software tools. Neuroscience research is, almost by its nature, interdisciplinary. Technical problems arising in research have, therefore, a unique interdisciplinary flavor. Creating solutions to these problems is fun and very rewarding because they immediately advance my work and contribute to the work of others. 

### TweetyNet - A machine learning tool for annotating complex song

### Next generation ultramicroelectrodes

### Miniaturized fluorescence microscopes

**References**:

[1]	Markowitz, J. E., Ivie, E., Kligler, L. & Gardner, T. J. (2013) Long-range Order in Canary Song. PLOS Comput Biol 9, e1003052.

[2] Shepard RN, Hovland CI, Jenkins HM (1961) Learning and memorization of classifications. Psychol Monogr 75(13):1–42.

