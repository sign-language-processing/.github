<div align="center">

# Sign Language Processing

**Advancing the accessibility and development of sign language through open-source cutting-edge tools and resources.**

We recommend reading our [background for sign language processing](https://research.sign.mt/).

</div>

## Overview

Our organization develops a wide array of tools to process, understand, and translate sign languages. Below is a categorized list of our repositories and their roles within the ecosystem.

### Core Libraries

- **[datasets](https://github.com/sign-language-processing/datasets)**  
  TFDS loaders and utilities for handling sign language datasets.

- **[pose](https://github.com/sign-language-processing/pose)**  
  Tools for viewing, augmenting, and handling `.pose` files, which represent sign language gestures.

### Translation and Synthesis

- **[spoken-to-signed-translation](https://github.com/sign-language-processing/spoken-to-signed-translation)**  
  A pipeline for translating spoken language to sign language, including text-to-gloss-to-pose conversion.

- **[pose-anonymization](https://github.com/sign-language-processing/pose-anonymization)**  
  Remove identifying information from sign language poses.
  
- **[pose-to-video](https://github.com/sign-language-processing/pose-to-video)**  
  Renders pose sequences into photorealistic videos, bringing sign language movements to life.

### SignWriting and Visualization

- **[signwriting-translation](https://github.com/sign-language-processing/signwriting-translation)**  
  Translation from spoken languages to SignWriting, facilitating written sign language documentation.

- **[signwriting-transcription](https://github.com/sign-language-processing/signwriting-transcription)**  
  Transcribes sign language videos using SignWriting.
  
- **[signwriting-animation](https://github.com/sign-language-processing/signwriting-animation)**  
  Converts SignWriting into skeletal pose animations.

- **[signwriting-illustration](https://github.com/sign-language-processing/signwriting-illustration)**  
  Automatically generate illustrations from SignWriting, aiding in sign language learning.

- **[signwriting-description](https://github.com/sign-language-processing/signwriting-description)**  
  Describe how to perform signs written in SignWriting.

### Experimental and Research Projects

- **[sign-gpt](https://github.com/sign-language-processing/sign-gpt)**  
  A multi-task GPT model tailored for sign language tasks.

- **[synthetic-signwriting](https://github.com/sign-language-processing/synthetic-signwriting)**  
  Generates synthetic SignWriting data for pretraining models.

- **[lexicon-induction](https://github.com/sign-language-processing/lexicon-induction)**  
  Induce a lexicon from a continuous sign language corpus.

### Benchmarking and Evaluation

- **[3d-hands-benchmark](https://github.com/sign-language-processing/3d-hands-benchmark)**  
  Tools for benchmarking 3D hand pose estimation models.

- **[signwriting-evaluation](https://github.com/sign-language-processing/signwriting-evaluation)**  
  Automatic evaluation of SignWriting outputs from machine learning models.

### Other Utility Projects

- **[segmentation](https://github.com/sign-language-processing/segmentation)**  
  Sign language pose segmentation on the sentence and sign level.

- **[recognition](https://github.com/sign-language-processing/recognition)**  
  Recognizes lexical signs from isolated sign videos.

----

- (OLD) Sign Language Activity Detection [training](https://github.com/sign-language-processing/detection-train)
  and [application](https://github.com/sign-language-processing/detection-app) -
  Detect when a signer is a signing in real time.
