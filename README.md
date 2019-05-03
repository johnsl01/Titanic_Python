# Titanic_Python

iPython notebook to explore the titanic survivors problem.

The ***Titanic*** survivors problem is a relatively simple one to understand but it 
still has enough data complexity to be used to showcase or serve as a learning 
base for quite a lot of processes and tools in Machine Learning and Artificial 
Intelligence - albeit that the more sophisticated tools in this case don't usually 
return any better answers than the simpler ones.

It is the standard introductory problem on Kaggle.

The challenge is simple - use the provided data about 891 passengers whose fate is 
known and the provided data about 418 passengers whose fate is unknown to build a 
model for predicting the fate of these 418 unkowns.

For all of these passengers you have several pieces of data including their name, 
travelling class, point of embarkation etc.  Some data is complete and some has missing
values, for example, many passengers ages are missing.

Kaggle calls these lists the train and test lists - but I have renamed them the known 
and unknown lists.  The reason is simple - in building models to predict data we need to 
be abel to test the quality of our model - and to do this we generally run it against 
known results to see how well it does.  We need to be careful that we don't build a model
which is good because it includes the answer - so we will divide the known results into  
train and test portions using the train to build the model and teh test to measure it.

Then when we have a mechanism to build a model that works well using this process we
will apply that mechanism to all the knowns and get its prediction for the actual unknowns.

To get the actual measure for our final mechanism we would have to submit the list to Kaggle
to get it measured, or alternatively we could poke aroudn the internet and get the actual
answers for the unkbowns and then we can measure our own results.

We are taking it as a given that the knowns and unknowns are representative selections 
of the passengers. Or at the least that they are not deliberately skewed. 

(Note that all the 100% results on Kaggle are fake - produced by looking up the actual
survivor date which is available online).

This is real world data and there are random and unpredictable events leading to 
individual outcomes - different mechanims will produce outputs between around 80%
and 90% correct answers.  But this is only one measure of mechanism / model quality
- albeit an important one.

I originally used this problem as part of a ML & AI course which was based on R.  So
this iPython notebook is my ongoing attempt to reproduce and extend this to python.

'to timidly go where many have gone before'

1 / May / 2019

.
