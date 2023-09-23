# aslint-testaro
ASLint accessibility testing tool

## Purpose

This repository is a fork of @essentialaccessibility/aslint, with only one code file kept and all other code files deleted.

The kept file is the bundled JavaScript script that is to be added to a page in order for it to perform the accessibility tests of ASLint.

This fork exists because the bundle file is missing from the original published package, being present only in the GitHub repository, and because the bundle file cannot be recreated from the published package. The instructions for creating the bundle file produce errors.

This package can be referenced as a dependency in [Testaro](https://www.npmjs.com/package/testaro). Thereby, the Testaro code does not need to be enlarged by the inclusion of the ASLint bundle file in the Testaro repository.
