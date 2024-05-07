# Project title: Ensure compatibility with SiNAPS probes

### Key Investigators
* Matteo Vincenzi
* Nina Kudryashova

## Project Description
Ensure that SiNAPS recordings are correctly read and parsed in SpikeInterface.

### Background
SiNAPS probes are high-density/high-channel-count probes (up to 1024 electrodes) designed with different layouts (single-shaft, multi-shaft, NHP, etc.). https://sinapsprobes.eu/ These probes allow simultaneous recording from all electrodes in a band ranging from 1Hz (and below) to 5KHz.
Recordings acquired with the Plexon and Neuronexus platforms are already supported, while those acquired with the research platform realised at the Italian Institute of Technology (IIT) still need to be supported.

### Objectives
Ensure that SiNAPS recordings are read correctly from both .bin and .h5 formats.

### Approach and Plan

### Progress
A custom branch has been created already by Alessio for this purpose, with an extractor/reader for .bin format: https://github.com/alejoe91/spikeinterface/tree/sinaps 

## References

