# Setup Spawn Action  (`saward/spawn`)

Download the **Spawn** CLI (postgresql database migration tool) from the latest or a specified GitHub release and place it on `PATH` so your workflow can simply call `spawn …`.

## Usage

```yaml
steps:
  - uses: actions/checkout@v4

  # Install Spawn (latest release)
  - name: saward/spawn
    uses: saward/spawn-action@v1
```
