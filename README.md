# abims

A machine-learning project to conduct `Automatic analysis of (political) bias in media sources`. Read the [whitepaper](#whitepaper) to learn more about the overall project goals.

## Whitepaper

This section contains the "whitepaper" underlining the goal of abims.

### Primary Goal

The aim is to create an artificial intelligence program based on either Neural Networking or the broader Machine Learning field to automatically assess the bias in media. This may be trained using multiple neutrally-aimed, accredited think-tank's information by combining sources to create a large dataset of neutral sources to a high degree. Once these sources have been found, find an optimal approach to examine the bias of these sources and train them on this aforementioned dataset.

“Bias” is primarily referring to the overall trustworthiness of the source and the political affiliation that source may have, typically seen with more aggressive, non-neutral wording or “buzzwords” that is favoured in a certain ideology.

### Approach

Will use a python-based machine learning tool such as [Keras](https://keras.io/) or [Tensorflow](https://www.tensorflow.org/) to design the algorithm. Once it has been sufficiently trained, a static model may be exported and attached to an API to be used publicly to examine media bias. This model should not be trained through public sourcing as the internet tends to have polarising views on political topics. Once this API has been made, the project can be left as it is or extended upon with a web interface to automatically scan new sources in the form of websites of stand-alone stanzas.

The sourcing of information for this project could also use a technique in which two algorithms are pitted against each other, e.g. one makes biased sources and the other (ours) detects and reports bias.

### Sourcing of think-tanks

As many “neutral” sources tend to be non-neutral, it is important to either get “truly” neutral (to within a realistic margin on the word neutral) or sources of approximately the same opposing bias, e.g. a very slightly liberal think-tank against a very slightly conservative think-tank – though this may hinder the overall performance as a source can be slightly accredited and discredited at the same time. Below are some think-tank or think-tank-like organisations/companies to consider sourcing information from:

- [mediabiasfactcheck.com](https://mediabiasfactcheck.com) – An armchair organisation aimed to classify media bias. May be used for unimportant verification-type training as is is not deemed to be credible enough
