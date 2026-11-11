# ci-smoke-lab-20
Throwaway sandbox for CI + contribution loop verification

## Build artifact

The CI workflow (`.github/workflows/demo.yml`) uploads a build artifact named `demo-build`
on every on-demand (`workflow_dispatch`) run. The artifact contains a short text file
(`demo-build.txt`) recorded by the job.
