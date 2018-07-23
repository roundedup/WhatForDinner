# What should I cook for dinner?

A couple of projects built around the [MIT 1M recipe dataset](http://im2recipe.csail.mit.edu/) and the flavor molecules dataset 
from [FlavorDB](http://cosylab.iiitd.edu.in/flavordb/).

The first project is a way to find a new vector representation of ingredients, aimed at 
exploring pairings and discovering new ones. 

The second is a generator of names of recipes conditioned on the list of ingredients. 
So a sort of ing2recipe.

## Content


<b>ing2recipe.ipynb</b>: RNN generator

<b>train_ing2recipe.ipynb</b>: RNN code used for training

<b>ing2recipe_weights.h5</b>: trained weights for the RNN

<b>pairings_explorer.ipynb</b>: code to explore the pairings using different representations

<b>pairings.ipynb</b>: dataset with top 10 pairings for each ingredient for a quick preview

<b>ingredients_weights.npy</b>: vector representation of ingredients following my weighted definition

<b>ingredients_onehot.npy</b>: vector representation of ingredients through one hot encoding of molecular content

<b>ingredients_word_emb.npy</b>: vector representation of ingredients using word embeddings 

<b>molecules_dictionary.npy</b>: ingredient dictionary used by the code 

## References

> Learning Cross-modal Embeddings for Cooking Recipes and Food Images <br />
> Salvador, Amaia and Hynes, Nicholas and Aytar, Yusuf and Marin, Javier and  Ofli, Ferda and Weber, Ingmar and Torralba, Antonio <br />
>Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition <br />
> 2017