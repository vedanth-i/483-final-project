# 483-final-project

The ipynb should have all the required libs/packages included and installs them at runtime at the very beginning.
In terms of usage, there should be code cells that say "CHANGE HERE" in which you can change the desired parameters and run the training and testing loops accordingly. From here, you can reproduce the results for both MLP and GCN models. 
A quick note about the split parameter. For the Computers dataset, split = 11000 and for the Photos dataset, split=6120. If these are not inputted accordingly, then you will get runtime errors and inaccurate results. 
There should be two model classes: MLP1 and GCN1. These are the main constructs of the models
To change the number of GCN layers of the GCN model, go to the GCN1 class and change the forward network to include more self.conv3 layers (you can also uncomment the desired number of layers in the code cell to add more GCN layers). 
