<!-- start title -->

# GitHub Action:Release helm chart

<!-- end title -->
<!-- start description -->

Releases helm charts using semantic-release with the @swarm-io/release-config-helm release config. This action uses main and alpha branches and releases. This action deletes the alpha branch and re-creates it from main after a release from main

<!-- end description -->
<!-- start contents -->
<!-- end contents -->
<!-- start usage -->

```yaml
- uses: swarm-io/action-release-helm-chart@undefined
  with:
    # github token to use for the release, if you want this to trigger other workflows
    # such as flows on release created, pass in a PAT
    # Default: ${{ github.token }}
    token: ""
```

<!-- end usage -->
<!-- start inputs -->

| **Input**   | **Description**                                                                                                                  |      **Default**      | **Required** |
| :---------- | :------------------------------------------------------------------------------------------------------------------------------- | :-------------------: | :----------: |
| **`token`** | github token to use for the release, if you want this to trigger other workflows such as flows on release created, pass in a PAT | `${{ github.token }}` |  **false**   |

<!-- end inputs -->
<!-- start outputs -->
<!-- end outputs -->
<!-- start examples -->

### Example usage

```yaml
on: [push]

jobs:
  hello_world_job:
    runs-on: ubuntu-latest
    name: A job to say hello
    steps:
      - uses: actions/checkout@v2
      - id: foo
        uses: actions/hello-world-composite-action@v1
        with:
          who-to-greet: "Mona the Octocat"
      - run: echo random-number ${{ steps.foo.outputs.random-number }}
        shell: bash
```

<!-- end examples -->
<!-- start [.github/ghdocs/examples/] -->
<!-- end [.github/ghdocs/examples/] -->
