# Project title: Unify and speed up testing

### Key Investigators

* Alessio Buccino
* Chris Halcrow @chrishalcrow
* Ramon Mayorquin @h-mayorquin

## Project Description

SpikeInterface implements a large and diverse set of tests at the module level. While testing routines have been growing steadily as the package developed, there are certain behaviors that require some refactoring.
As an example, many test functions use custom cache folders for saving temporary files, other use pytest fixtures.

With this project, we aim to use the latest testing tools to clean up and speed up testing and CI.

### Objectives

The goal of this project is to review and modify the SpikeInterface tests to be more consistent and lightweight.

### Approach and Plan

 * [ ] Review existing test functions and identify old patterns that needs to be updated
 * [ ] Identify and move fixtures that can be used at the package level and shared across modules


### Progress

 * [ ] Make PR to SpikeInterface

