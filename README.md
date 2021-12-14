# Parkinson's Disease Datasets

## Overview
Since anatomic MRI is presently not able to directly discern neuronal loss in Parkinson’s Disease (PD), studying the associated functional connectivity (FC) changes seems a promising approach toward developing non-invasive and non-radioactive neuroimaging markers for this disease. While several groups have reported such FC changes in PD, there are also significant discrepancies between studies. Investigating the reproducibility of PD-related FC changes on independent datasets is therefore of crucial importance.

The data are comprised of 20 PD patients and 20 age-matched controls in the Tao Wu dataset. Both sets contain T1 and resting-state scans.

## Experimental Protocol
For the resting-state scan, subjects were instructed to close their eyes and think of nothing in particular without falling asleep.

## Scan Parameters [(Click here for scan parameters in BIDS format)](http://fcon_1000.projects.nitrc.org/indi/retro/Parkinsons/Parameter_BIDS.csv)

|                       | Parameter     | Tao Wu| 
| --------------------- |:-------------| :-----|
| **T1-weighted scan**  | Sequence<br>--------------<br>Repetition time (TR)<br>--------------<br>Echo time (TE)<br>--------------<br>Voxel size| MPRAGE (IR method)<br>--------------<br>1100ms<br>--------------<br>3.39ms<br>--------------<br>1 x 1 x 1 mm |
| **Resting-state scan**| Sequence<br>--------------<br>Repetition time (TR)<br>--------------<br>Echo time (TE)<br>--------------<br>Voxel size<br>--------------<br>Voxel size<br>--------------<br># of Volumes|Echo planar<br>--------------<br>2s<br>--------------<br>40ms<br>--------------<br>	90°<br>--------------<br>4 x 4 x 5 mm (64 x 64 matrix, 28 slices, field of view=256mm x 256mm)<br>--------------<br>239 (8 min)|


### Additional Information
The Tao Wu data was re-hosted from https://fcp-indi.s3.amazonaws.com/data/Projects/INDI/umf_pd/taowu.tar.gz

Find additional dataset information at the following [link](http://fcon_1000.projects.nitrc.org/indi/retro/parkinsons.html).