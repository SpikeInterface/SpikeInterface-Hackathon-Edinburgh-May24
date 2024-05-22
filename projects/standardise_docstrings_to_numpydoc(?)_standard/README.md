# Project title:

### Key Investigators

* Chris Halcrow

## Project Description

Bring our docstrings up to numpydoc standard (for one module)

### Background

Docstrings are important. If they are formatted properly, they can be used by other packages to autogenerate stuff e.g. Sphinx uses them to build our docs API. Future GUIs would depend on them, and having (typed?) good ones can make development much easier. Our are pretty good, but it would be nice if they were met a specific standard.  I propose to bring the docstrings up to the numpydoc(?) standard: https://numpydoc.readthedocs.io/en/latest/format.html 

To see the fun that awaits try running e.g.  (sorry to pick on one function: this was the first one I saw!). Think it’d be good to try and do a module and see how long it takes, and how annoying it is. Ruff (https://docs.astral.sh/ruff/) can do linting based on this standard, which makes it easier to develop.

### Objectives

Standardise one module, find out how long this takes and what are the time-heavy steps (if they exist).

### Approach and Plan

 * [ ] Make a simple workflow which makes standardising docstrings easy (probably installing the vscode ruff extension is enough)
 * [ ] Standarise the docstrings for one module

### Progress

 * [ ] Decide on which standard to use
 * [ ] Standardise one docstring
 * [ ] Figure out how long it takes to standardise one docstring => estimate size of task
 * [ ] Standardise all docstrings in one module



