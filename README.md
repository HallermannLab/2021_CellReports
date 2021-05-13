# 2021_CellReports
This is code was used in the following publication:

Large, Stable Spikes Exhibit Differential Broadening in Excitatory and Inhibitory Neocortical Boutons.
Ritzau-Jost A, Tsintsadze T, Krueger M, Ader J, Bechmann I, Eilers J, Barbour B, Smith SM, Hallermann S.
Cell Reports 2021 34:108612
doi: 10.1016/j.celrep.2020.108612

The code was used to analyse the loose-seal currents recorded from boutons of neocortical neurons. 

The code was run on Mac OSX 11.2.3 after installation of 
- Individual Edition of Anaconda (https://www.anaconda.com) for the use of JuyiterLab 2.2.6 
- Python 3.9.4
- and mpl-axes-aligner with "pip install mpl-axes-aligner"

To run the code execute the JupyterLab Notebook file "ap.ipynb" in the folder "ap" or "train.ipynb" in the folder "train".
In each folder, example HEKA files are provided ("testData_ap.dat" and "testData_100Hz_train.dat" from an experiment with single action potentials and trains of 20 action potentials at 100 Hz, respectively). The resulting export files are provided in the folders "Data".
The files "ap.pdf" and "train.pdf" contain exports of the JupyterLab Notebook file as PDFs. The output graphs embedded in the JupyterLab Notebook file are provided as seperate PNG-imgage files in the corresponding folders.

There is detailed documentation of the Python code in the cells of the JupyterLab Notebook file. For more information contact hallermann@medizin.uni-leipzig.de
