---
title: Setup
---

There are several pieces of software you will wish to install before the workshop.
Though installation help will be provided at the workshop,
we recommend that these tools are installed (or at least downloaded) beforehand.
Anaconda Python is a very large download.

## Python 3 and Snakemake

Please install Anaconda from [https://www.continuum.io/downloads](https://www.continuum.io/downloads)
(however any version of Python 3 will work).
Anaconda is a free version of Python that comes bundled with all of its most useful tools.
Even better, it includes several significant performance improvements over "vanilla" Python.

You can install Snakemake with `pip install --user snakemake`

## Nextflow

FIXME: Nextflow instructions

FIXME: Do I need SSH clients? Resolve once I know how workshop will be delivered.

## SSH Client

For the final part of this course (scaling our workflow across a cluster),
all students should have an SSH client installed.
SSH is a tool that allows us to connect to and use a remote computer as our own.
Please follow the directions below to install an SSH client for your system.

### Windows

Install MobaXterm from [http://mobaxterm.mobatek.net](http://mobaxterm.mobatek.net).
You will want to get the Home edition (Installer edition).

### macOS

Although macOS comes with SSH pre-installed,
you will typically want to install [XQuartz](www.xquartz.org) to enable graphical support.
Note that you must restart your computer to complete the installation.

### Linux

Linux users do not need to install anything, you should be set!

{% include links.md %}
