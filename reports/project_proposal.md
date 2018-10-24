Bayesian Language Classification
======
Camille Girard and Jonah Spicher

For this project we would like to recognize the language of a word based on the phonemes in the word. If you were to overhear a word in a restaurant or on the street this program could tell you how likely it is to be a certain language based on the phonemes. Given a word and a predefined dataset of phoneme frequency  in each language being tested, this will return an updated probability that the observed word is in that language.

We will either use data (which we have not yet found) or dictionaries to extract the information required. [This](https://www.eupedia.com/linguistics/number_of_phonemes_in_european_languages.shtml) source gives the total number of phonemes in a variety of languages but is not exactly what we are looking for.

As for data, our approach would ideally be to just find a database with phoneme frequency by language, however we may have to process through a dictionary and extract the information (but we really hope not because that would be terrible). We will approach this problem in a similar way to the beetle classification problem, using the data and then a specific data from a word to collect the probability that it is in each group using those distributions. We would also ideally include some weight to the usage of each phoneme but this would also require more specific data, and we will see where the project takes us. If this doesn’t take long, we might also consider the fact that the variables (phonemes) are not independent, and work with joint distributions, but a naive bayesian model might work well enough.

The main concern at the moment is finding the proper data or resources to extract the data from. Once we have the data the rest we will be able to do, however at the moment we have not yet found the exact resources that we need to extract the needed data. This project will also potentially hold a lot of things to consider and it could be difficult to create a very meaningful result.

Our immediate concern is trying to find the data needed to complete our project. If we do not find the correct resources in a few days we will pivot project ideas, still within classification. We will both be tackling this task initially. Afterwards we will likely work together (or split up the work evenly if needed) to complete the data processing and the actual computations and split up documentation.
