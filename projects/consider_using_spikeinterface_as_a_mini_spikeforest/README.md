# Project title:

Consider using SpikeInterface as a mini SpikeForest

### Key Investigators

* Pierre Yger

## Project Description

### Background

SpikeForest used to be very usefull in order to assess the pros and the cons of various spike sorters, in different datasets and/or probes, species, .... Now that SpikeInterface has a very nice generator module that can generate, in a fast and lazy manner, complicated ground truth (drifting or not), or even hybrid recordings, if could be worst thinking of a small testsuite that could be launched, on a given sorter, in order to assess how good it performs in various conditions. Ultimately, one could think of a web export similar to SpikeForest, but at least even for users/developpers it would be useful to get a better sense of what sorters (or maybe sets of components, in a longer term) can be good for a particular situation.

### Objectives

Think about a key list of datasets that could be used, either synthetic and/or hybrid, and think about the types of metrics we would like to get. Should we display that online or not, it has to be discussed. Maybe extending the HTML possibilities of the Study object, we could easily get a way of displaying information in a browser.

### Approach and Plan

Fill in with approach and project plan

 * [ ] Identify the datasets we want to focus on
 * [ ] Start brainstorming on the metrics/representation/interaction
 * [ ] Establish link with an automated Study that will test various sorters in Hybrid situation to know which sorters might be the best, for a given type of data

### Progress

Fill in with tentative milestones (or leave blacnk for later):

 * [ ] Milestone 1
 * [ ] Milestone 2
 * [ ] Make PR to SpikeInterface

### Next Steps (optional)

Fill in with next steps

## References

[^1]: SpikeForest (https://elifesciences.org/articles/55167)

