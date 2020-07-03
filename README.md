# Hyperalignment using Budapest data
This repository contains scripts to perform searchlight hyperalignment and movie segment decoding using the Budapest dataset.

`hyperalignment_pymvpa_splits.py` trains hyperalignment using one half of the movie, and applies the transformation matrix to the other half.

`decoding_segments_splits.py` performs movie segment classification using 15 s segments,
similar to Haxby et al. ([2011](https://doi.org/10.1016/j.neuron.2011.08.026)) and Guntupalli et al. ([2016](https://doi.org/10.1093/cercor/bhw068),
[2018](https://doi.org/10.1371/journal.pcbi.1006120)).
