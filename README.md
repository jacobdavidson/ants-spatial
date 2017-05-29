# ants-spatial
Mathematica code to generate results and figures in submitted article, "Spatial organization and interactions of harvester ants during foraging activity"

To generate all results, these codes are meant to be run sequentially:
(0) Data import and Function definitions.nb
(1) Process data to categories.nb
(2) Density and collision theory calculations.nb
(3) Correlated random walk model.nb
(4) Results and Figures 1-4.nb
(5) Results and Figures 5-10.nb

In file (0), you need to specify the directories to read in the edge data (included in folder 'edgedata'), colony frame images (include in folder 'colframes') and the ant trajectory data, which is available at the following repository:
(coming soon!)

In file (0), you can also specify a directory to save processing results in intermediate steps.  This is optional, so if you don't do this, don't run the associated "Save" and "Get" commands.

Files (2) and (3) take some time to run all of the simulations and analysis calculations.

Files (4) and (5) generate all the results and figures for the paper
