
---
title: HW_picam (akshaybkiitb)
description: ScopeFoundry hardware plug-in to control PICAM-based Princeton Instruments Cameras
weight: 26
---
- [GitHub Repository](https://github.com/akshaybkiitb/HW_picam)
- Last Updated: 2020-09-01T13:45:04Z

#### To add to your microscope 

`cd to/your_project_folder` and use the following cmd (requires [git](/docs/100_development/20_git/))

```bash
mkdir ScopeFoundryHW/picam && cd ScopeFoundryHW/picam && git init --initial-branch=master && git remote add upstream_akshaybkiitb https://github.com/akshaybkiitb/HW_picam && git pull upstream_akshaybkiitb master && cd ../..
```

## Readme
ScopeFoundryHW.picam
===================================

ScopeFoundry hardware plug-in to control PICAM based Princeton Instruments
Cameras. Tested on a PI PIXIS camera.

ScopeFoundry is a Python platform for controlling custom laboratory 
experiments and visualizing scientific data

<http://www.scopefoundry.org>

This software is not made by or endorsed by the device manufacturer


Author
----------

Edward S. Barnard <esbarnard@lbl.gov>


Requirements
------------

	* ScopeFoundry
	* numpy
	* PICAM DLL
	
	
History
--------

### 0.1.0	2020-08-04	Initial public release.

Plug-in has been used internally and has been stable.
Check Git repository for detailed history. Tested on PI PIXIS CCD.


