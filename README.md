<p align="left">
<img width=15% src="https://dai.lids.mit.edu/wp-content/uploads/2018/06/Logo_DAI_highres.png" alt=“DAI-Lab” />
<i>An open source project from Data to AI Lab at MIT.</i>
</p>

[![PyPI Shield](https://img.shields.io/pypi/v/cool-project.svg)](https://pypi.python.org/pypi/cool-project)
[![Travis CI Shield](https://travis-ci.org/DAI-Lab/CoolProject.svg?branch=master)](https://travis-ci.org/DAI-Lab/CoolProject)
[![Coverage Status](https://codecov.io/gh/DAI-Lab/CoolProject/branch/master/graph/badge.svg)](https://codecov.io/gh/DAI-Lab/CoolProject)
[![Downloads](https://pepy.tech/badge/cool-project)](https://pepy.tech/project/cool-project)

# Cool Project

Python Boilerplate contains all the boilerplate you need to create a Python package.

- Documentation: https://DAI-Lab.github.io/CoolProject
- Homepage: https://github.com/DAI-Lab/CoolProject

# Overview

TODO: Provide a short overview of the project here.

# Install

## Requirements

**Cool Project** has been developed and tested on [Python3.4, 3.5, 3.6 and 3.7](https://www.python.org/downloads/)

Also, although it is not strictly required, the usage of a [virtualenv](https://virtualenv.pypa.io/en/latest/)
is highly recommended in order to avoid interfering with other software installed in the system
in which **Cool Project** is run.

These are the minimum commands needed to create a virtualenv using python3.6 for **Cool Project**:

```bash
pip install virtualenv
virtualenv -p $(which python3.6) CoolProject-venv
```

Afterwards, you have to execute this command to activate the virtualenv:

```bash
source CoolProject-venv/bin/activate
```

Remember to execute it every time you start a new console to work on **Cool Project**!

## Install with pip

After creating the virtualenv and activating it, we recommend using
[pip](https://pip.pypa.io/en/stable/) in order to install **Cool Project**:

```bash
pip install cool-project
```

This will pull and install the latest stable release from [PyPI](https://pypi.org/).

## Install from source

Alternatively, with your virtualenv activated, you can clone the repository and install it from
source by running `make install` on the `stable` branch:

```bash
git clone git@github.com:DAI-Lab/CoolProject.git
cd CoolProject
git checkout stable
make install
```

## Install for Development

If you want to contribute to the project, a few more steps are required to make the project ready
for development.

Please head to the [Contributing Guide](CONTRIBUTING.rst) for more details about this process.

# Quickstart

In this short tutorial we will guide you through a series of steps that will help you
getting started with **Cool Project**.

## 1. TODO: Put a title here

TODO: Provide a step by step guide here.

# What's next?

For more details about **Cool Project** and all its possibilities
and features, please check the [documentation site](
https://DAI-Lab.github.io/CoolProject/).
