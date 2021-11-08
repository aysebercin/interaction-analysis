# interaction-analysis

Understanding biomolecular interactions at the atomistic detail is integral to dissecting any cellular system. In the cell, the biomolecular interactions are dynamic, where they are formed and lost while carrying out their functions. For understanding such dynamic processes, molecular dynamics (MD) simulations are one of the most commonly used methods to trace the dynamic interaction profiles over time. 

The analysis of the dynamic interaction data deduced from MD simulations can be carried out by various methods. Here, we used the “interfacea” Python package to evaluate the intermolecular h-bond, hydrophobic, and ionic interactions (for more information: https://github.com/JoaoRodrigues/interfacea). In this tutorial, we will guide you in processing the interfacea output files to study the interaction dyanmics of a methylatransferase system.

## interaction-analysis project content

- **frames.pdb:** a coordinate file containing the frames deduced from the MD simulated protein-DNA complex (written in each 0.5 ns for 5 ns long).
- **input_files:** Contains raw interactions files created by the interfacea Python package (run on frames.pdb)
- **interaction_analysis.ipynb:** iPython notebook to be used to analyze raw interfacea interactions files, located under input_files.

## Requirements

- For using **interaction_analysis.ipynb**, you have to install [Anaconda Navigator](https://docs.anaconda.com/anaconda/install/). To be able to run scripts, we will use *Jupyter Notebook.*
- To visualize the coordinate file (**frames.pdb**), you should have installed a molecular visualization tool such as [Pymol](https://pymol.org/2/) on your computer. 

