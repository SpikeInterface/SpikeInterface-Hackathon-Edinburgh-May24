# Project title: support for SiNAPS probes and data formats

### Key Investigators

* Nina Kudryashova
* Matteo Vincenzi
* Alessio ?

## Project Description

Add support for SiNAPS probes (via probeinterface), data formats (partially done with *.bin and *.h5 extractors for SiNAPS). 
Potentially: check drift and drift correction for these probes. 

### Background

SiNAPS probes are high-channel count, active electrodes, similar to other silicon active probes available and popular today (E.g., NeuroPixels)[^1]. They are currently not supported by Spikeinterface, but we started developing data extractors for the probe.

### Objectives

- [ ] Add support for SiNAPS data formats
- [ ] Add support for SiNAPS research probes
- [ ] Add tools for addressing SiNAPS-specific issues (e.g. amplification artefacts)
- [ ] Bad channel detection
- [ ] Drift correction

### Approach and Plan

- [ ] Test the extractors
- [ ] Test probeinterface probes and add to spikeinterface
- [ ] Discuss SiNAPS-specific amplification artefacts and approaches to masking them out for SI
- [ ] Analyse drift and drift correction on these large probes? 

## References

[^1]: https://plexon.com/products/sinaps/

