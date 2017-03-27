This is my summary of the article [Decoding the Brain: Neural Representation and the Limits of Multivariate Pattern Analysis in Cognitive Neuroscience](http://philsci-archive.pitt.edu/12915/?utm_source=dlvr.it&utm_medium=twitter)

# Theoretical assumptions of Neural Decoding

Neural decoding (ND) is the nicer sounding name of the multivariate pattern analysis (MVPA)
in cognitive neuroscience. First let us take a look at what (ND) is and how it is performed
in the area of vision.

## Sketch of a Neural Decoding experiment

The idea of ND is to reveal a mapping between neural activity patterns and behavioural or perceptual cues.
Neural decoding experiments consist of 3 steps:

1. Collect neuroimaging data in different conditons.
2. Pick a brain region of interest (ROI) based on some motivation (e.g.:anatomical)
3. Asses how well the collected patterns discriminate between the recorded conditions

Let us go through a simple example. In the data analysis stage the experimenters collect fMRI responses
while the participants look at objects of 2 different categories. The collection is
followed by some preprocessing step. In the second stage the researches choose the ROI
based on theoretical motivations e.g.: the anatomically 
defined region of the parafoveal primary visual cortex (V1). The third stage usually involves 
the application of standard classification techniques. Each "voxel" is treated as a separate
"feature" in the feature/design matrix and the conditions are treated as labels. The standard
Machine Learning methodology is then applied:

1. Create train, developement and test splits.
2. Fit paramters on train, tune hyper-paramters on dev, report final results on test split

If cassifier performance is statistically better than chance, the patterns for the different
conditions are considered to be discriminable. 

## Inferences from ND experiments

The ND experiments allow for inferences of the following form:

> Brain region $$X$$ involved in some mental process $$y$$.

The power of ND comes form the fact that if the brain uses population codes - distributed representations -
, then spatial patterns in neural data that differentiate between conditions are potentially recoverable using 
MVPA methods.

## The Decoders Dictum

> If information can be decoded from patterns of neural activity, then this provides
>  strong evidence about what information those patterns represent.

In other words statistically significant decoding results are taken as evidence that
latent neural patterns encode information about the experimental conditions and therefore
some behaviural/perceptual phenomena. 

Davis and Poldrack ([2013], p. 120) state that:
> ‘MVPA focuses on the informational content of activation patterns coded in different regions.’

An example is Williams et al. ([2008] presented simple object exemplars in the visual periphery, and found that object shape could be decoded from foveal V1.

## Theoretical basis for the Decoders Dictum
Let us take the informal statement as the theoretical basis:
> if we can decode, we have reasonably strong evidence about what is represented in the measured patterns of neural activity.
