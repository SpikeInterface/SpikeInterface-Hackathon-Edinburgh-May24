# Project title: Extend auto-merge to fix drift-related spilts

### Key Investigators

* Alessio Buccino
* Aurelien Wyngaard
* Pierre Yger

## Project Description

Residuals drifts in the recording could cause a unit to be over-split due to slow drifting over time. When this happens, usually spikes from the unit get assigned to a different unit after a certain point, as in this example:

![image](https://github.com/SpikeInterface/SpikeInteface-Hackathon-Edinburgh-May24/assets/17097257/967dd322-7ba6-466e-bf6b-ba5067ebd2f5)

Using this temporal overlap information, we could extend the auto-merge function to find and fix this drift-related splits. For example, we could use the presence_ratio increase merged as an additional step in the auto-merge function.


### Objectives

The goal of the project is to extend the auto-merge function to target this specific kinds of oversplits.

### Approach and Plan

 * [ ] Identify a few datasets and drift-related oversplits examples
 * [ ] Explore strategies to automatically detect potential merges (e.g., presence ratio, overlap in activity, etc.)
 * [ ] Test performance on identified oversplits example
 * [ ] Extend performance test to IBL dataset
 * [ ] Modify auto-merge function with new steps

### Progress

Fill in with tentative milestones (or leave blank for later):

 * [ ] Make PR to SpikeInterface

