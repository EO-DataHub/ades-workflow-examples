## Convert URL 
### Workflow executes but the ouputs STAC files are not valid


Running this workflow gives all expected log outputs:
- `convert.log` - logs from the workflow `convert` step
- `node_stage_out.log` - logs from the workflow stageout process
  - Stating that STAC is not valid: `pystac.errors.STACTypeError: JSON (id = catalog) does not represent a STACObject instance. 'type' attribute is catalog`