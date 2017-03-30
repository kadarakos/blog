# Saliency estimation

Given image predict where humans are looking

<img src="http://imagelab.ing.unimore.it/imagelab/uploadedImages/000243.jpg"    
     alt="Mountain View" 
     >
     
----
----
<br><br>

## Saliency estimation moved:
- From modeling of low-level visual attention 
- To the prediction of human eye fixations on images.

Driven in part by large datasets and benchmarks of human eye movements!

----
----
<br><br>


## Long-story short


----
----
<br><br>

# Benchmarks

Natural images as the visual stimuli and eye movements recorded using eyetracking

- MIT300, 300 img, indoor-outdoor, 39 observers ages: 18-50
- CAT2000 4000 img, 20 categories, 24 observer per image, ages: 18-27  
- SALICON 10,000 img, MS-COCO, 60 observer per image  

----
----
<br><br>

# Standardized evaluation
Bunch of well understood metrics:

<img
    src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/7df5a52a88a7e84ddb645e8361d2e9aa45449e5f/13-Table6-1.png"
    >
<br><br>


Standard training and validation protocols:

<img
    src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/258fad95e709b6d0572ae6cc99efbbb14d32bdf2/6-Table4-1.png"
    >
    <br><br>

    
Very little qualitative exploration:

<img
    src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/258fad95e709b6d0572ae6cc99efbbb14d32bdf2/7-Figure6-1.png"
    >
----
----
<br><br>

# Practical applications

- Detection: object and motion detection, segmentation
- Compression: thumbnailing, content-aware cropping, content-aware compression
- Image retrieval

----
----
<br><br>

# Where do models fail?

<img src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/13b6b5b2e96b2b63f0d35f6e91e22a08d2f4e52c/8-Figure6-1.png"
     >
     
- Objects of gaze
- Objects of action

----
----
<br><br>


# Image-description generation
Given image generate description 

#### Gobal image features
<img src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/11da2d589485685f792a8ac79d4c2e589e5f77bd/0-Figure1-1.png"
     >
<br><br>

#### Explicit "attention-module" for local features
<img src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/b955969e1077ca328018c9e4dcf27b87ed9f5076/9-Figure8-1.png"
     >
<br><br>
     
#### Recovering implicit attention
<img src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/76f83380fe193ae8475e660c1c6b12b60521a29f/5-Figure3-1.png"
     >
<br><br>


----
----
<br><br>

# Attention matchin human performance?

##### Noun-phrase localization

<img src="https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/0612745dbd292fc0a548a16d39cd73e127faedde/16-Figure12-1.png"
     >

