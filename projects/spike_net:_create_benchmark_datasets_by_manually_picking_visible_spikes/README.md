# Project title:
Spike Net: Create benchmark datasets by manually picking visible spikes
### Key Investigators

* Gaelle Chapuis, Olivier Winter, Alessio Buccino
* (all the code comes from Olivier Winter !)

## Project Description
To assess the precision and recall of a spike sorter spike detection, there are a few approaches - hybrid datasets, ground truth datasets with intracellular recordings performed juxtacellularly ; but these datasets are either missing some natural components, or are rare.
Here we propose to enhance our pool of dataset by having humans labelling visible spikes on raw data, recorded in several brain regions.

### Background

viewephys is a viewer of raw ephys data developed by Olivier Winter at the International Brain Laboratory:
https://github.com/int-brain-lab/viewephys

We propose to develop the benchmarks using the IBL datasets publicly available:
http://reveal.internationalbrainlab.org.s3-website-us-east-1.amazonaws.com/benchmarks.html#/0/2
Loading code: https://int-brain-lab.github.io/iblenv/notebooks_external/loading_raw_ephys_data.html

### Objectives
The main work at this hackathon will focus on documenting and amending the viewephys desktop app to perform manual spike picking -- from there, it can be later input into a web platform (but this will not be done at this Hackathon).

### Approach and Plan

Fill in with approach and project plan

 * [ ] Task 1: download data for one IBL raw data snippet, launch the view into the GUI
 * [ ] Task 2: pick a few spikes, save and reload --> write all the code and documentation for this, so someone else can redo it [some functions may require changes, especially if we want to label visible clusters]
 * [ ] Task 3: finish the picking for one insertion (if not more)
 * [ ] Task 4: (if time allows): mesure precision and recall from spike sorting on this particular snippet of data

### Progress

Fill in with tentative milestones (or leave blank for later):

 * [ ] Milestone 1 : documentation of picking for others to do as well (ideally someone else would have tried doing it to validate this milestone)
 * [ ] Milestone 2 : 1 snippet finished
 * [ ] Milestone 3 : mesure quality of a spike sorter detection on this snippet

### Next Steps (optional)

- Liase with others in the community to do the spike picking
- See if someone would be interested to port this into a web application
- Discuss where the spike picking datasets should be saved ?

## References

Spike net: https://docs.google.com/document/d/1OA69Ptg58AQnGdmGi6UvZFrngwZDMixil1V7hJX6bNI/edit

