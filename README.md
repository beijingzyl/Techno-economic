# Common definitions for model comparison projects

[![License: CC0-1.0](https://img.shields.io/github/license/iamConsortium/common-definitions)](https://github.com/IAMconsortium/common-definitions/blob/main/LICENSE)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## Overview

This repository holds definitions and mappings for model-comparison projects using the IAMC data format.
The aim is to provide a central location to facilitate reuse of definitions and mappings across projects.

Read more about the [IAMC data format](https://docs.ece.iiasa.ac.at/iamc.html).

## Project nomenclature

The folder `definitions` contains the project nomenclature, i.e., list of allowed
variables and regions, for use in the validation workflow. See the **nomenclature**
package for more information ([link](https://github.com/iamconsortium/nomenclature)).

The folder `mappings` contains models-specific region-processing mappings.

## Model registration

This is the step-by-step guide to registering your model:

1. Fork this repository
2. Follow the instructions from the nomenclature documentation here: <https://nomenclature-iamc.readthedocs.io/en/stable/user_guide/model-registration.html>. 
Please make sure to follow the instructions completely, both the _Model mapping_ and the _Region definitions_ part. You'll have to end up with two files.
3. Open a pull request into this repository. Make sure that the tests run through and correct any potential issues. If the tests are failing you can view the details by clicking on the failed test run.

4. Set [@danielhuppmann](https://github.com/danielhuppmann) and [@phackstock](https://github.com/phackstock) as reviewers.
5. Once everything is in order we will merge your pull request and your model will be registered.

## Funding acknowledgement

<img src="./_static/prisma-logo.png" width="200" align="right" alt="PRISMA logo" />

<img src="./_static/EU-logo-300x201.jpg" width="80" height="54" align="left" alt="EU logo" />
This repository was started as part of the <a href="https://www.net0prisma.eu">PRISMA project</a>
with funding from the European Union’s Horizon Europe programme
under grant agreement No. 101081604 (PRISMA).
