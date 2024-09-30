## Convert URL 
### Stageout fails as no STAC items are provided


Running this workflow gives all expected log outputs:
- `convert.log` - logs from the workflow `convert` step, implies this step was successful
- `node_stage_out.log` - logs from the workflow stageout process
  - `FileNotFoundError: [Errno 2] No such file or directory: '/tmp/catalog/EO-Data-Hub-logo_colour_425px-resize.json'` shows that item.json not found