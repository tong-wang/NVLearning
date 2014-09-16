Description
------------

Here you can find the output (*.txt* files) of the code in the **/NVLearning/src/** folder, the R script (*.R* files) for generating publishable figures, and the figures (*.pdf* files).


###Output

	NVLearning_Full.txt						==> The output of the F model
	NVLearning_Event_myopic.txt				==> The output of the E model with myopic inventory decision
	NVLearning_CheckpointA_myopic_M2.txt	==> The output of the IC[2] model with myopic inventory decision	NVLearning_CheckpointA_myopic_M4.txt	==> The output of the IC[4] model with myopic inventory decision
###Figure

	Figure-Inventory-typical.pdf			==> Figure 3a
	Figure-Profit-aggregate.pdf				==> Figure 4b

###Scripts

	Script-InventoryPlot.R					==> R Script for plotting Figure 3a and 3b
	Script-CheckpointPlot.R					==> R Script for plotting Figure 5b
	
###Sub-folders
	
	Checkpoint_PowerOfTwo/					==> Contains code/output/figures for Checkpoint models with M = 1, 2, 4, 8, 16, 32

	
	
Instructions
------------

The R scripts require a working R environment (http://www.r-project.org/). The scripts are only tested on R version 2.15, but should be running smoothly on newer versions. The scripts do not require extra R packages (except for file *legend2.R* in this folder, which holds a function for adding legend).