# Project title: Investigate browser-based spikeinterface (spike in-your-browser)

### Key Investigators

* Chris Halcrow

## Project Description

Python(ish) is now in the browser through WebAssembly, Pyodide and Jupyter-Lite. Have a go: https://pyodide.org/en/stable/console.html or https://jupyter.org/try-jupyter/lab/index.html . This means new users can play with Python without having to install anything. How much work would it take to add spikeinterface to this story?

### Background

WebAssembly is in your browser (probably). Pyodide is a port of CPython to Webassembly. So, using it, you can run Python in your browser without having to install Python. Pure python packages can be installed using micropip (https://github.com/pyodide/micropip). Pure means that there are no C/Fortran extensions (or dependencies?? I'm a bit confused). If there are, the story gets more complicated: https://pyodide.org/en/stable/development/new-packages.html 

So, it seems possible to make spikeinterface (or a stripped down version of it) work in people's browsers without them installing anything. This means people can have a poke and play with it before committing to installing it, and we can make tutorials and playgrounds for people and get them hooked on spikeinterface!! 

But it's not trivial. So: the purpose of this project is not to do it. It's to figure out what we would need to do to do this. 

### Objectives

Figure out how to make a spikeinterface pyodide package.

### Approach and Plan

 * [ ] Understand pyodide and micropip
 * [ ] Figure out what we _can't_ do
 * [ ] Make a roadmap of spike in-your-browser

### Progress

### Next Steps (optional)

## References

Nice interview with one of Python's core developers at PyCon 2019: https://talkpython.fm/episodes/show/213/webassembly-and-cpython

