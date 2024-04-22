# Project title:

### Key Investigators

* Alessio Buccino
* Joe Ziminski @JoeZiminski
* Zach McKenzie @zm711

## Project Description

> Ported from issue https://github.com/SpikeInterface/spikeinterface/issues/2303

Following a conversion in https://github.com/SpikeInterface/spikeinterface/pull/2299, a number of instances where the API is inconsistent were highlighted. This issue is opened as a place to discuss and begin fixing these:

-  saves it's parent recording to a  kwarg not a  kwarg that seems to be used elsewhere.
-  stores the parent recording as a dict not a recording.
-  uses a  rather than 
-  vs.  argument.

More genreally, I think SI is becomming a very mature and widely used package and freezing the API / defaults as much as possible between versions would really enhance user experience / avoid bugs. I wonder if at some stage a full review of the API could be performed (this would entail multiple people going through every SI function / class and making notes on function names and default arguments inconsistencies or room for improvement). Then these could be discussed, frozen, and only changed in future with a very good reason.

### Background

SpikeInterface is now over 6 years old. Parts of the API have been ported and changed without a unified vision in mind.
As we're approaching v1.0, it is time to look at the API as a whole and unify the naming and conventions throughout the entire codebase.

### Objectives

Unify arguments, variable naming, and documentation about the API

### Approach and Plan

 * [ ] Identify API mismatches
 * [ ] Discuss unified naming

### Progress

 * [ ] Make PR to SpikeInterface


