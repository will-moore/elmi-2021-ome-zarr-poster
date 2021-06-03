---
layout: about
title: about
permalink: /
description:

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

This EM [image](https://idr.openmicroscopy.org/webclient/?show=image-9822152) of SARS-Cov2 in the human intestine ([Lamers etal Science 2020](https://doi.org/10.1126/science.abc1669)) is over 144000 x 93000 pixels.
It has been converted to the [OME-Zarr](https://ngff.openmicroscopy.org/latest/) format, so that individual chunks of raw pixel data can be loaded
in parallel into the browser, and viewed with [Vizarr](https://github.com/hms-dbmi/vizarr/).

Go ahead and Zoom in!
<iframe
  style="width: 100%; border: none; height: 550px;"
  src="https://hms-dbmi.github.io/vizarr/v0.1?source=https://s3.embassy.ebi.ac.uk/idr/zarr/v0.1/9822152.zarr"></iframe>

The data is hosted within a directory at [https://s3.embassy.ebi.ac.uk/idr/zarr/v0.1/9822152.zarr/](https://s3.embassy.ebi.ac.uk/idr/zarr/v0.1/9822152.zarr/)


# Pre-print Available

See our pre-print "**OME-NGFF: scalable format strategies for interoperable bioimaging data**" 
on bioRxiv at:
[doi.org/10.1101/2021.03.31.437929](https://doi.org/10.1101/2021.03.31.437929)

