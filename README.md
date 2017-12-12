# lrgparser
An LRG file parser for STP Bioinformatics (Genomics)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The LRG parser has the following prerequests:
* An internet connection
* Python (v3)
* ElementTree (part of the xml library)
* urllib

### Usage

To run the LRG parser from command line:

```
python lrgparser.py
```

You will be prompted to enter an LRG number in the format LRG001. The output is placed into the working directory and comprises of:
* a fasta file of the coding sequence of the LRG
* html containing a comparison of the LRG between the GrCh37 and GrCh38 build. 


## Built With

* [Anaconda] (https://conda.io/docs/) - The python framework used
* [GitHub] (https://github.com/) - For version control

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Richard Crookes** (https://github.com/RCrooks1986/)
* **Christine Hicks** (https://github.com/bioinfochicks)
