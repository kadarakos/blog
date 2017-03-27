This is my summary of the article [Decoding the Brain: Neural Representation and the Limits of Multivariate Pattern Analysis in Cognitive Neuroscience](http://philsci-archive.pitt.edu/12915/?utm_source=dlvr.it&utm_medium=twitter)

# Theoretical assumptions of Neural Decoding

Neural decoding (ND) is the nicer sounding name of the multivariate pattern analysis (MVPA)
in cognitive neuroscience. First let us take a look at what (ND) is and how it is performed
in the area of vision.

## Neural decoding in vision

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

