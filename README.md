## Workflow

Workflow

- Job
  - Step
  - Step
  - Step
- Job
  - Step

### Workflow

### Job

    - Must contain atleast one step
    - Run in parallel

### Step

    - Step = individual tasks
    - Run Sequentially
    - `Custom commands` or pre-defined actions

## TODO

-

```yaml
on:
  push:                         // checkout available events
    branches:
      - main

jobs:
  hello_world_job:
    runs-on: ubuntu-20.04       // checkout Runner types
    steps:                      // ALl steps usage methods
      - name: Say Hello
        run: |
            echo "something random"                 // HOW TO reuse this block
            echo "hello there"                      //
```
