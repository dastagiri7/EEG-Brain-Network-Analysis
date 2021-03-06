# EEG-Brain-Network-Analysis

# Abstract:

This project focuses on understanding brain signals and connectivity patterns related to the eye states. More specifically, we analyzed brain Signals recorded by EEG for two different Eye states i.e. Eye open(EO) and Eye close(EC) respectively. We analyzed the 64-channel EEG signals from a single subject(S004) with eyes-open and eyes-closed baseline conditions. We did 4 types of analysis namely connectivity graphs, graph theory indices, motif analysis, and community detection. More on this in their respective sections. At each stage of analysis, we emphasized arising differences between EO and EC states, accordingly concluded the main identifiers of each state. 

To do this we focused on understanding the difference between the brain connectivity estimated with the MVAR estimation approaches like Partial directed coherence (PDC) and Direct Transfer Function (DTF) (the second one tends to give connectivity value a little bit bigger than the first one). We also performed motif analysis using the tool mfinder and considering 3-node and 4- node motif configuration. We were able to obtain motifs and anti-motifs for the configuration with 3 and 4 nodes. We also to carry out specific analysis about information about the connection involved in a specific community detection configuration (modularity-based vs information theory-based approaches). Finally, after our observations, while computing the community detection, we highlighted the weaknesses of Louvain’s’ algorithm in recognizing small communities compared to the Info map.

## Topics

Spectral analysis, connectivity graph, computation of graph theory indices, motif analysis, community detection.

# Analysis:

After analyzing the EEG signals from a single subject with eyes-open and eyes-closed baseline conditions in various perspectives we found significant differences that may be taken into account while working with these base-lines. First of all, basic signal analysis showed that a frequency of 10 Hz explains the most significant difference between the two baselines. Moreover, different MVAR estimators to build the network of EEG signals can lead to very different graphs, and an estimator that involves only direct interactions seem to generate a topology where communities are physically close in the brain. 

Finally, in order to be more confident about the archived results in further research we would suggest examining data from several subjects and thus we would be able to determine statistical significance of all the differences listed above from all possible view points. Also, we strongly believe that specific analysis for motifs and community detection considering both DTF and PDC for all densities and 2 states would lead to further interesting insights about the patterns in signal data. We did the motif analysis and community detection using only DTF estimator with 20% graph density. We also want to state that by doing connectivity graph analysis and graph theory indices using above ideology has yielded us better correlations for comparing and contrasting different cases because as someone stated that a picture speaks a thousand words. 
