## gk workspace insights

Get metrics about PRs from the repos within the workspace

### Synopsis

Get metrics about PRs from the repos within the workspace.
Accepts an argument that tells how long is your cycle time for sprints (7-14).

Metrics exposed:
  - average cycle time: average time it takes for a PR to get merged, since its first commit until the merge.
  - average throughput: average of the Number of PRs merged each week of the cycle
  - merge rate: quotient between PRs merged and PRs opened
  - opened pull requests: number of PRs opened within the cycle time provided
  - merged pull requests: number of PRs merged within the cycle time provided

These metrics are compared with the ones in the previous cycle
If you see a green number it means that the metric has improved from the previous one.

```
gk workspace insights [flags]
```

### Options

```
  -h, --help   help for insights
```

### SEE ALSO

* [gk workspace](gk_workspace.md)	 - Interact with your workspaces

###### Auto generated by spf13/cobra on 13-Mar-2023