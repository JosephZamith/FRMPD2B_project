# FRMPD2B_project

This script analyses the output of SNT (Simple Neurite Tracer) pluggin from FIJI saved as .CSV files in a folder named 'layer X' with X the layer desired.
It will produce several sheets at different steps :
- path_raw_p21_layerX.csv, this sheets concatenates all the data accumumated in the FIJI reconstructed .CSV files
- path_ready_p21_METHOD_layerX.csv with METHOD being PathLength (distance along the neurite calculated by FIJI) or lenth_segment (the distance calculated as if neurites were segments between the branchpoints)
this sheets show expanded column descriptions (IUE, mouse, ...) as well as cumulative branchpoints, branch orders, and total dendrite length
- cumulBranchingPerNeuron_CONDITION_p21_DENDRITETYPE_layerX with CONDITION being FRMPD2B or Control and DENDRITETYPE being basal or apical
these sheets present data with every column being a neuron and cumulative branchpoints as values
- totalLEngthPerNeuron_CONDITION_p21_DENDRITETYPE_layerX with CONDITION being FRMPD2B or Control and DENDRITETYPE being basal or apical
these sheets present data with every row being a neuron and the total dendrite length as values
