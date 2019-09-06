## PPN notebooks

These notebooks are related to the Point Proposal Network (PPN).

* [`Old_PPN`](https://nbviewer.jupyter.org/github/DeepLearnPhysics/2019-09-CSUWorkshop/blob/master/ldomine/Old_PPN.ipynb) demonstrates how well it used to work (on the open data, without any ghost point)
* [`PPN_Basics`](https://nbviewer.jupyter.org/github/DeepLearnPhysics/2019-09-CSUWorkshop/blob/master/ldomine/PPN_Basics.ipynb) teaches you how to run the inference, look at events and output of PPN, as well as run a simple analysis to compute useful metrics afterwards.
* [`PPN_High_Statistics`](https://nbviewer.jupyter.org/github/DeepLearnPhysics/2019-09-CSUWorkshop/blob/master/ldomine/PPN_High_Statistics.ipynb) takes the last section of `PPN Basics` and shows how to do it with high statistics, by running the code in command line, saving the results in CSV files and then running the analysis in a simple notebook.
* [`PPN_Advanced`](https://nbviewer.jupyter.org/github/DeepLearnPhysics/2019-09-CSUWorkshop/blob/master/ldomine/PPN_Advanced.ipynb) is aimed at people interested in understanding more about PPN, especially how and why it fails. It shows how to visualize and understand all the outputs of the network, including intermediate feature maps (PPN1/2).

### Requirements
* Singularity container image [here](https://singularity-hub.org/containers/10509)
```
$ singularity pull shub://DeepLearnPhysics/larcv2-singularity:ub18.04-cuda100-py3-pytorch1.1.0-scn-docker
```

* Code `lartpc_mlreco3d` from [here](https://github.com/Temigo/lartpc_mlreco3d/tree/develop), branch `develop`
```
$ git clone https://github.com/Temigo/lartpc_mlreco3d.git
```