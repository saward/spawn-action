# Setup Spawn Action  (`saward/spawn`)

Download the **Spawn** CLI (postgresql database migration tool) from the latest or a specified GitHub release and place it on `PATH` so your workflow can simply call `spawn …`.

## Usage

```yaml
steps:
  - uses: actions/checkout@v4

  # Install Spawn (latest release)
  - uses: saward/spawn@v1         # or pin to a tag e.g. @v1.0.3
    with:
      # version: v1.0.3           # optional – defaults to "latest"
```
