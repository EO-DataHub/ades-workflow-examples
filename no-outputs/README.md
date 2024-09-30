## Convert URL 
### Stageout fails as no STAC items are generated


Running this workflow gives all expected log outputs:
- `convert.log` - logs from the workflow `convert` step
- `node_stage_out.log` - logs from the workflow stageout process
  - `FileNotFoundError: [Errno 2] No such file or directory: '/tmp/catalog/catalog.json'` shows that catalog.json not found