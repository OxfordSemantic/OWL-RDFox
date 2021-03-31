# OWL-RDFox5
This repository's purpose is to show users how the OWL implementation in RDFox v5 works.

You will need to obtain a license for RDFox (evaluation [here](https://www.oxfordsemantic.tech/tryrdfoxforfree)). You will receive an email with the license, and also details of how to install RDFox.

To start, clone this repository, then run:
`/path/to/RDFox sandbox /path/to/OWL-RDFox5/`

This will start up the RDFox sandbox. You can then copy commands from `start.txt` into the shell in order to replicate the steps used to populate named graphs with data and axioms.

The file `curl.txt` contains commands of how to replicate the same steps, but by using the REST endpoint of RDFox. Before running the curl commands, make sure you actually start the RDFox endpoint with:
`/path/to/RDFox sandbox /path/to/OWL-RDFox5/ "endpoint start"`
