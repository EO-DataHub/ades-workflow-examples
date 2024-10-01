# ADES Workflow Examples for Logging

Quick repo to provide example CWl scripts and Docker images to test the logging outputs provided by the ADES when the workflow fails.
The included scripts test:
- Valid and correct workflow
  - convert-url
  - convert-stac (with stagein)
- Error during workflow executing
- Invalid glob statement in CWL script
- Invalid STAC output from workflow
- Invalid stagein to workflow
- No STAC Catalog output
- No STAC item output
- No outputs provided at all
- Workflow sleeps for 5 minutes (only used for debug, not for logging)

## Logging Review
Each directory contains a brief overview of the logging expected in each failure (or success) case, specifying how the user can identify the cause of the failure.

## References
The source code for the CWL scripts in this package are taken from the EOEPCA example workflows available [here](https://github.com/EOEPCA/convert).

