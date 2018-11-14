﻿# layout-base

## Description

This repository implements a basic layout model and some utilities for Cytoscape.js layout extensions. 

## Usage instructions

Add `layout-base` as a dependecy to your layout extension.

`require()` in the extension to reach functionality:

 * `var Integer = require(layout-base).Integer`,
 * `var Layout = require(layout-base).Layout`,
 * `...`
 
 For a usage example, see [cytoscape-cose-bilkent](https://github.com/cytoscape/cytoscape.js-cose-bilkent).
