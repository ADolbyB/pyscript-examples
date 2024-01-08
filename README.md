# PyScript Examples

<div align="center">

<img src="./assets/PyScript-Graphic.png" alt="PyScript" width="500"/><br>

<small>
    <a href="https://www.datanami.com/wp-content/uploads/2022/05/Anaconda-PyScript-Graphic.png">Image Source</a>
</small>

</div>

This repo is a compilation of tutorials and examples using [`PyScript`](https://pyscript.github.io/docs/2024.1.1/) which embeds python into HTML. PyScript is a 'micro front-end', similar to Angular or React.

I created this repo for project research on Python Web Apps.

## Prerequisites for using PyScript:

- Install JS Backend Framework: [Node.js](https://nodejs.org/en/download/)
- Install the Node Package Manager: [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- Install a Python Environment: [Download Python](https://www.python.org/downloads/)

Optional but highly recommended:
- Install the Node Version Manager: [NVM](https://tecadmin.net/how-to-install-nvm-on-ubuntu-20-04/)
    - This allows multiple versions of NPM to be installed as parallel installations.

- Install a Python Environment Management system like [Anaconda](https://www.anaconda.com/download/) or [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html).
    - This allows multiple versions of Python to be installed as parallel environments.

- Add the `mamba` package dependency solver, which is much faster than the pre-existing `conda` package dependency solver: `conda install mamba`
    - Refer to the docs for [`mamba`](https://mamba.readthedocs.io/en/latest/index.html)
    
- Another alternative is the `Miniforge3` aka [`MambaForge`](https://github.com/conda-forge/miniforge/releases) which "holds the minimal installers for Conda and Mamba specific to conda-forge, with the following features pre-configured:
    - Packages in the base environment are obtained from the conda-forge channel.
    - The conda-forge channel is set as the default (and only) channel."
        - [source](https://github.com/conda-forge/miniforge)

## Some Background Information:

- Note that with PyScript, the `<py-script>` tag that is used to run python code. This is the 'main' tag used.
    - `<py-script>` is used to display results (output, pyscrit.write), DOM Manipulation, and other python based operations (like batch, webservices).
    - `<py-script>` is used in two ways: Python code written in HTML in the same page, or using `src` attributes in the tag (externalization of python code).
- The `<py-env>` tag is used to import Python Libraries into the DOM.
- The `<py-repl>` tag is used to add a python console to the DOM.

## Sources:

Documentation (start here):
- [PyScript Docs](https://pyscript.github.io/docs/) Home Page.
    - [Example Applications](https://pyscript.com/@examples) that are open source with live demos.
    - [Alternative Link to Example Applications](https://pyscript.github.io/docs/2024.1.1/user-guide/examples/) that are open source with live demos.
    - [2024.1.1 User Guide](https://pyscript.github.io/docs/2024.1.1/user-guide/)

YouTube Tutorials:
- [PyScript: The Complete Guide](https://www.youtube.com/watch?v=kcbJiQLhRtM) by Run Nano, 2:03:00 duration.
    - Covers the following: DOM Manipulation, CRUD Operations, Event Management, Custom Components, and Data Science Applications.

## Status:

![GitHub repo size](https://img.shields.io/github/repo-size/ADolbyB/pyscript-examples?logo=github&label=Repo%20Size)