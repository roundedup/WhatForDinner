# What should I cook for dinner?

A couple of projects built around the [MIT 1M recipe dataset and](http://im2recipe.csail.mit.edu/) the flavor molecules dataset 
from [FlavorDB](http://cosylab.iiitd.edu.in/flavordb/).

The first project is a way to find a new vector representation of ingredients, aimed at 
exploring pairings and discovering new ones. 

The second is a generator of names of recipes conditioned on the list of ingredients. 

## Content


<b>pairings_explorer.</b>: RNN code used for training

<b>pairings_explorer.</b>: RNN generator

<b>pairings_explorer.</b>: trained weights for the RNN


<b>pairings_explorer.</b>: code to explore the pairings using different representations

<b>pairings_explorer.</b>: dataset with top 10 pairings for each ingredient for a quick preview



<b>pairings_explorer.</b>: vector representation of ingredients following my weighted definition

<b></b>: vector representation of ingredients through one hot encoding of molecular content


<b></b>: vector representation of ingredients using word embeddings 

## References

> Learning Cross-modal Embeddings for Cooking Recipes and Food Images <br />
> Salvador, Amaia and Hynes, Nicholas and Aytar, Yusuf and Marin, Javier and  Ofli, Ferda and Weber, Ingmar and Torralba, Antonio <br />
>Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition <br />
> 2017