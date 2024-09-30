## Convert URL 
### Workflow executes but the glob definition leads to no files being extracted


Running this workflow gives all expected log outputs:
- No log files, implies the convert step failed (no outputs to glob)
- JSON response includes message stating that it failed to read the catalog.json file, implying it is either incorrect or not present
