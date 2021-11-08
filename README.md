# interaction-analysis

There are many biomolecules for the continuity of essential processes in living systems. There are various interactions between biomolecules for the continuity of these activities. In time, these interactions can be disrupted and re-formed. Molecular dynamics (MD) simulations are one of the most commonly used methods to study the dynamic movements and changing interactions of biomolecules against time.

Dynamic information from MD simulations informs the behavior of biomolecules over time. Various methods are available to analyze this information.

Here, we used the “interfacea” Python package to evaluate dynamic information from MD simulations in terms of intermolecular interactions (for more information: https://github.com/JoaoRodrigues/interfacea). Basically this package calculates the interactions between atoms and classifies them as h-bond, hydrophobic interactions and ionic interactions.

## interaction-analysis content

- **input_files:** Contains raw output files created by the interfacea Python package.
- **frames.pdb:** It is a serial coordinate file containing the frames of the MD simulated complex with output files in the input_files.
- **interaction_analysis.ipynb:** iPython notebook to be used to analyze raw output files in input_files.

## Requirements

- For using **interaction_analysis.ipynb**, you have to install [Jupyter Notebook](https://jupyter.org/install)
- For visualize the serial coordinate files, you should have any visualization tool such as [Pymol] (https://pymol.org/2/) on your computer. 
