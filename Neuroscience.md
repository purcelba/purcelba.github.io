---
layout: page
title: Neuroscience research
permalink: /Neuroscience/
---
I studied how the brain combines different types of information to make decisions.  I developed models that explain the computations that support decision making and designed behavioral experiments to validate model predictions.  I tested how the brain could implement those computations by recording from large populations of neurons and used machine-learning algorithms to visualize neural states and predict upcoming choices.  

___

## Neural Models of Decision Making

I developed neural computational models of decision making for my PhD thesis.  My models used neural time-series data recorded from macaque monkeys making visual decisions as input to shallow artificial neural networks.  The models predicted the monkey's choices and response times and reproduced the dynamics of actual neural populations.  You can find an overview the modeling framework and sample code in the [gated_accumulator_model](https://github.com/purcelba/gated_accumulator_model) repository or read more about the details in the papers listed below.

**Collaborators:** Thomas Palmeri, Jeffrey Schall, Gordon Logan, Richard Heitz, Jeremiah Cohen (Vanderbilt University)

![Figure 1]({{ site.baseurl }}/images/gated_accumulator.png "Gated accumulator model."){: .center-image }
<p align="center">
<font size="2"><b>Figure 1.</b> Using actual neural data to generate input to decision-making networks.  Check out the <a href = "https://github.com/purcelba/gated_accumulator_model">gated_accumulator_model</a> repository or <a href = "https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellHeitzCohenSchallLoganPalmeri2010.pdf">Purcell et al. 2010</a> for more details.</font>
</p>

### Papers
- Purcell, B. A., Heitz, R. P., Cohen, J. Y., Schall, J. D., Logan, G. D., & Palmeri, T. J. (2010). Neurally constrained modeling of perceptual decision making. Psychological review, 117(4), 1113.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellHeitzCohenSchallLoganPalmeri2010.pdf)
- Purcell, B. A., Schall, J. D., Logan, G. D., & Palmeri, T. J. (2012). From salience to saccades: multiple-alternative gated stochastic accumulator model of visual search. Journal of Neuroscience, 32(10), 3433-3446.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellSchallLoganPalmeri2012.pdf)
- Purcell, B. A., & Palmeri, T. J. (2017). Relating accumulator model parameters and neural dynamics. Journal of Mathematical Psychology, 76, 156-171.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellPalmeri2017.pdf)
- Schall, J. D., Purcell, B. A., Heitz, R. P., Logan, G. D., & Palmeri, T. J. (2011). Neural mechanisms of saccade target selection: gated accumulator model of the visual–motor cascade. European Journal of Neuroscience, 33(11), 1991-2002.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/SchallPurcellHeitzLoganPalmeri2011.pdf)
- Zandbelt, B., Purcell, B. A., Palmeri, T. J., Logan, G. D., & Schall, J. D. (2014). Response times from ensembles of accumulators. Proceedings of the National Academy of Sciences, 111(7), 2848-2853.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/ZandbeltPurcellPalmeriLoganSchall2014.pdf)

### In the news
- [Vanderbilt News](https://news.vanderbilt.edu/2010/10/08/neurons-cast-votes-to-guide-decision-making/)
- [Vanderbilt News](https://news.vanderbilt.edu/2014/02/03/number-of-neurons/)
- [Futurity Research News](http://www.futurity.org/lots-neurons-can-work-fast-just/)

___

## Models of Adaptive Decision Making

I combined human psychophysical experiments, computational models of behavior, and neurophysiological recordings from behaving macaque monkeys to understand how we adapt our decision strategies following mistakes. I fit models of choice and reaction time to human and monkey behavior and optimized model parameters to make inferences about the underlying neural mechanisms. To test the model predictions, I analyzed neural dynamics recorded from the parietal cortex of monkeys performing a perceptual decision-making task. The neural data matched the model predictions and showed that although our visual sensitivity drops following errors, our brain can compensate by adaptively slowing down the subsequent choice. You can read more about it in the following paper or check out some of the popular press on the article by following the links below.  

**Collaborator:** Roozbeh Kiani (New York University)

![Figure 2]({{ site.baseurl }}/images/pes.png "Post-error slowing."){: .center-image }
<p align="center">
<font size="2"><b>Figure 2.</b> Decision errors slow us down (Left).  We found that neural activity in parietal cortex also changes (Middle).  Our computational modeling explains why this happens (Right).  Check out <a href = "https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellKiani2016a.pdf">Purcell & Kiani (2016)</a> for more details.</font>
</p>

### Paper
- Purcell, B. A., & Kiani, R. (2016). Neural mechanisms of post-error adjustments of decision policy in parietal cortex. Neuron, 89(3), 658-671.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellKiani2016a.pdf)

### In the news
- [The Atlantic](https://www.theatlantic.com/science/archive/2016/02/why-mistakes-are-often-repeated/470778/)
- [ScienceLine](http://scienceline.org/2016/08/i-fd-up/)
- [Medical Daily](http://www.medicaldaily.com/errors-decision-making-just-slow-us-down-why-we-dont-always-learn-our-mistakes-370600)
- [Science Daily](https://www.sciencedaily.com/releases/2016/01/160121130011.htm)
- [The Sun](https://www.thesun.co.uk/archives/news/195779/the-reason-why-we-dont-learn-from-our-mistakes-is-revealed/)

___

I developed a new computational model to understand flexible decision making in a dynamic environment.  In a changing environment, we must decide whether errors result from poor choices or a change in the environment.  The Bayes optimal solution is to treat negative outcomes as evidence for a change of environment and to weight that evidence by the confidence in our choice.  I developed a model that showed how humans could approximate the optimal solution using very simple computations and developed a psychophysics experiment to test the model predictions. I showed that the model accurately predicted human choices and quantitatively outperformed plausible alternatives.

**Collaborator:** Roozbeh Kiani (New York University)

![Figure 3]({{ site.baseurl }}/images/cngenv.png "Changing environment."){: .center-image }
<p align="center">
<font size="2"><b>Figure 3.</b> A computational model explains decisions based on a visual information (Left) and changes of environment (Middle).  The model explains how accumulation of visual evidence maps to confidence, which in turn provides evidence for changes of environment (Right).  See <a href = "https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellKiani2016b.pdf">Purcell & Kiani (2016b)</a> for more details.</font>
</p>

### Paper:
- Purcell, B. A., & Kiani, R. (2016). Hierarchical decision processes that operate over distinct timescales underlie choice and changes in strategy. Proceedings of the National Academy of Sciences, 113(31), E4531-E4540.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellKiani2016b.pdf)

### In the news
- [Neuroscience News](http://neurosciencenews.com/confidence-neuroscience-error-4705/)
- [Eureka Alert](https://www.eurekalert.org/pub_releases/2016-07/nyu-iga071416.php)
- [Science Daily](https://www.sciencedaily.com/releases/2016/07/160718161503.htm)

___

## Predicting Choices from Large-Scale Neural Recordings

I used state-of-the-art electrophysiology technology to simultaneously record activity from hundreds of neurons in multiple areas of the primate brain.  I recorded neural activity while monkeys made decisions based on visual information.  I used dimensionality reduction methods to visualize the evolution of neural states during decision formation. I used linear classifiers to decode the information represented in different brain regions and to predict the upcoming choices. I studied the correlation structure of signals within and across areas to understand neural interactions.  I presented results from this project at the [Society for Neuroscience Annual Meeting](https://www.sfn.org/annual-meeting/neuroscience-2017).

**Collaborator:** Roozbeh Kiani (New York University)

![Figure 4]({{ site.baseurl }}/images/gpfa_example.png "GPFA example."){: .center-image }
<p align="center">
<font size="2"><b>Figure 4.</b> (Left) I used unsupervised dimensionality reduction techniques <a href = "https://www.ncbi.nlm.nih.gov/pubmed/19357332">(Yu et al., 2009)</a> to visualize the evolution of neural states over time.  The network evolves to signal the upcoming choice, and the signal is stronger for easier decisions.  (Right) A linear classifier trained on 20 dimensions can decode the upcoming choice with >95% accuracy (cross-validated).</font>
</p>

___
## Neurophysiological Representations of Visual Salience

In two studies, I recorded activity from neurons in medial and lateral frontal cortex of monkeys trained to perform a visual search task in which they located a target item among distractors (e.g., red circle among green circles).  I used auROC curves and other analyses to quantify the information about object identity carried by individual neurons.  I found that lateral frontal cortex robustly represented the location of the target, but medial frontal cortex did not.  Instead, medial frontal cortex seemed to play a role in signaling feedback.

**Collaborators:** Polly Weigand, Jeffrey Schall, Richard Heitz, Jeremiah Cohen (Vanderbilt University)

![Figure 5]({{ site.baseurl }}/images/sef2.png "SEF and FEF."){: .center-image }
<p align="center">
<font size="2"><b>Figure 5.</b> (Left) Example neurons from lateral and medial frontal cortex.  Only the lateral neuron signals the target location (red shading).  (Right) An auROC analysis indicates that lateral frontal neurons signal significantly more information about target location.  See <a href = "https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellWeigandSchall2012.pdf">Purcell et al. (2012)</a> for more details.</font>
</p>

### Papers
- Purcell, B. A., Weigand, P. K., & Schall, J. D. (2012). Supplementary eye field during visual search: salience, cognitive control, and performance monitoring. Journal of Neuroscience, 32(30), 10273-10285.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellWeigandSchall2012.pdf)
- Purcell, B. A., Heitz, R. P., Cohen, J. Y., & Schall, J. D. (2012). Response variability of frontal eye field neurons modulates with sensory input and saccade preparation but not visual search salience. Journal of neurophysiology, 108(10), 2737-2750.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellHeitzCohenSchall2012.pdf)

___
## Homologous Neural Mechanisms of Visual Attention and Working Memory in Humans and Non-Human Primates

I collaborated with Goeff Woodman to conduct two studies of electroencephalogram (EEG) recordings - brain activity recorded from the surface of the head that can be used to index cognitive states.  My work helped to establish a non-human primate model of EEG components associated with visual attention and working memory.  By pairing EEG from outside the skull with recordings of neural activity from inside the brain, we could study how neural activity gives rise to observed EEG.  We showed how frontal cortex indirectly contributed to the generation of attention and memory related EEG signals.  You can read more about this work in the papers below or check out [Geoff's website](http://www.psy.vanderbilt.edu/faculty/woodman/) for more information about his awesome work.

**Collaborators:** Geoff Woodman, Rob Reihardt, Jeffrey Schall, Richard Heitz, Polly Weigand (Vanderbilt University)

![Figure 6]({{ site.baseurl }}/images/eeg.png "FEF and EEG."){: .center-image }
<p align="center">
<font size="2"><b>Figure 6.</b> Example neuron (top, blue), local field potential (middle, green), and EEG (bottom, red) recorded from a macaque monkey performing a visual search task.  All three signals indicate the location of the search target. See <a href = "https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellSchallWoodman2013.pdf">Purcell et al. (2013)</a> for more details.</font>
</p>

### Papers
- Purcell, B. A., Schall, J. D., & Woodman, G. F. (2013). On the origin of event-related potentials indexing covert attentional selection during visual search: timing of selection by macaque frontal eye field and event-related potentials during pop-out search. Journal of neurophysiology, 109(2), 557-569.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/PurcellSchallWoodman2013.pdf)
- Reinhart, R. M., Heitz, R. P., Purcell, B. A., Weigand, P. K., Schall, J. D., & Woodman, G. F. (2012). Homologous mechanisms of visuospatial working memory maintenance in macaque and human: properties and sources. Journal of Neuroscience, 32(22), 7711-7722.[pdf](https://github.com/purcelba/purcelba.github.io/blob/master/docs/ReinhartHeitzPurcellWeigandSchallWoodman2012.pdf)

___

## Evaluating Methods for Measuring and Visualizing Human Similarity Judgments

As an undergraduate, I evaluated methods for visualizing the structure of human categorization of colors and personality traits.   I collected human similarity judgments of color and personality trait stimuli using a "sort-and-merge" procedure in which subjects grouped stimuli into clusters based on their perceived similarity and subsequently merged the clusters based their overall group similarity.  I visualized the resulting similarity structure using an multidimensional scaling (MDS) procedrue.  I assessed the internal validity of the procedure using percent variance explained and the external validity of the procedure by comparing the shape of the solution to a "ground truth" dataset obtained using pairwise similarity judgments.   I found that the sort-and-merge procedure could capture the structure of judgments quite well, establishing it as a cheaper and less time-consuming alternative to pairwise judgments for measuring human categorization.


**Collaborator:** Robin Thomas (Miami University)

![Figure 7]({{ site.baseurl }}/images/mds.png "MDS."){: .center-image }
<p align="center">
    <font size="2"><b>Figure 7.</b> First two dimensions of the MDS solution for personality trait data collected with sort-and-merge procedure compared to pairwise similarity judgments. Both methods generally agree and reveal the structure of human categorization.</font>
</p>

