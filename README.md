# eBDIMS

**eBDIMS** is a coarse-grained hybrid Elastic Network/Brownian Dynamics
model to generate transition pathways between two functional protein end-states.

An integrated tool to generate eBDIMS pathways is available at [https://login.biophysics.kth.se/eBDIMS](https://login.biophysics.kth.se/eBDIMS).

To fine-tune algorithm parameters, or to use large or incomplete structures, the
stand-alone packages contained within this repository can be used.

## Stand-alone packages

* [pdbParser](https://github.com/ozyo/pdbParser)
* [eBDIMS](https://github.com/cabergh/eBDIMS)

## Workflow for using stand-alone packages

1. Run the pdbParser script to retrieve the Carbon-alpha atoms for two end-state structures
2. The output files from step 1 are used input to execute the eBDIMS simulation

## References

* Orellana et al. Prediction and validation of protein intermediate states from structurally rich ensembles and coarse-grained simulations. <i>Nature Communications</i> **7**, Article number: 12575 (2016).
