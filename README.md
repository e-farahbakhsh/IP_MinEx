# IP_MinEx
Image Processing tools for Mineral Exploration

## Introduction
This repository deals with image processing tools which are applied on satellite remote sensing data in preliminary stages of mineral exploration.
The codes available here are as follows:

* False Color Composite (FCC)

## Usage

### False Color Composite (FCC)
The textural characteristics of igneous rocks can be discriminated from those of sedimentary rocks, and structural features are readily recognizable by applying proper RGB color combination of available bands. Several FCC images may be generated by the available bands, but we need to know the combination which is able to discriminate different hydrothermally altered rocks and lithological units as best as possible. There are different statistical methods for determining the best false color composite of the bands, namely, Optimum Index Factor (OIF), Sheffield Index (SI) and Correlation Index (CI). All of these indices rank different band combinations according to the calculated scores.

The input variable (A) to the FCC codes is an mxnxp matrix which is actually a multispectral image with multiple bands. In this matrix, m equals the number of image rows, n equals the number of image columns and p equals the number of bands. Each array in this matrix is the brightness value of each pixel. The output variable in which the band combinations and corresponding score have been stored are respectively called 
