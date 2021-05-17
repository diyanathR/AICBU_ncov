# A Getting Started Guide to the Genomic Epidemiology of SARS-CoV-2
<!-- WARNING -->
<!-- Do not edit this file from within the docs.nextstrain.org repository. -->
<!-- It is fetched from another repository to be included in the docs.nextstrain.org build. -->
<!-- So, if you edit it after it is fetched into docs.nextstrain.org, your changes will be lost. -->
<!-- Instead, edit this file in its own repository and commit your changes there. -->
<!-- For more details on this (temporary) implementation, see https://github.com/nextstrain/docs.nextstrain.org#fetching-of-documents-from-other-repositories -->
<!-- This file is fetched from: https://github.com/nextstrain/ncov/blob/master/docs/index.md -->
<!-- WARNING -->
<!-- WARNING -->
<!-- WARNING -->

This template and tutorial will walk you through the process of running a basic phylogenetic analysis on SARS-CoV-2 data.
We've created these resources with the goal of enabling Departments of Public Health to start using Nextstrain to understand their SARS-CoV-2 genomic data within 1-2 hours.
In addition to the phylogenetic analysis described here, you can use our "drag-and-drop" tool for a clade assignment, mutations calling, and basic sequence quality checks at [clades.nextstrain.org](https://clades.nextstrain.org/).

We also recommend [this 1-hour video overview](https://youtu.be/m4_F2tG58Pc) by Heather Blankenship on how to deploy Nextstrain for a Public Health lab.

## Overview: complete walkthrough

### Getting started with analysis

The starting point for this section is a FASTA file with sequence data + a TSV file with metadata. You can alternately use our example data to start.

  1. [Setup and installation](setup.md)
  2. [Preparing your data](data-prep.md)
  3. [Orientation: analysis workflow](orientation-workflow.md)
  4. [Orientation: which files should I touch?](orientation-files.md)
  5. [Running & troubleshooting](running.md)
  6. [Customizing your analysis](customizing-analysis.md) (see also: [reference for all configuration parameters](configuration.md))
  7. [Customizing your visualization](customizing-visualization.md)

### Getting started with visualization & interpretation

The starting point for this section is a JSON file. You can alternately use our examples to start.

  8. [Options for visualizing and sharing results](sharing.md)
  9. [Interpreting your results](interpretation.md)
  10. [Writing a narrative to highlight key findings](narratives.md)

### Multiple inputs

  11. [Running the pipeline starting with multiple inputs](multiple_inputs.md)

## Help

If something in this tutorial is broken or unclear, please [open an issue](https://github.com/nextstrain/ncov/issues/new/choose) so we can improve it for everyone.

If you have a specific question, post a note over at the [discussion board](https://discussion.nextstrain.org/) -- we're happy to help!