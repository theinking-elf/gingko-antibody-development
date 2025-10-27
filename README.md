**What is antibody developability and why is it important?**

Antibodies have to be manufacturable, stable in high concentrations, and have low off-target effects.\ 
Properties such as these can often hinder the progression of an antibody to the clinic, and are collectively referred to as 'developability'. 
Here we invite the community to submit and develop better predictors, which will be tested out on a heldout private set to assess model generalization.

**Developability properties in this competition**

1. Hydrophobicity
2. Polyreactivity
3. Self-association
4. Thermostability
5. Titer

For each of the 5 properties in the competition, there is a prize for the model with the highest performance for that property on the private test set. 
There is also an 'open-source' prize for the best reproducible model: one that is trained on the GDPa1 dataset (reporting cross-validation results) and assessed on the private test set where authors provide all training code and data.
This will be judged by a panel (i.e. by default the model with the highest average Spearman correlation across all properties will be selected, but a really good model on just one property may be better for the community).
