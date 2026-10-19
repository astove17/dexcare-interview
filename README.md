# SRE Technical Interview

This repo contains a simplified Kubernetes/Helm debugging exercise. For the full EKS-based interview with a real cluster, see the [infra-interview](https://github.com/DexCare/infra-interview) repo.

## Lightweight Version (no cluster required)

If you just need a quick screen without spinning up infrastructure, candidates can debug the Helm chart locally using `helm template`:

```bash
git clone <this-repo>
cd resources/chart
helm template myrelease .
```

The rendered output contains two bugs for the candidate to identify and fix.

## Full EKS Version

See the `infra-interview` repo. It deploys a throwaway EKS cluster in sandbox with more complex troubleshooting scenarios and is the primary interview platform for SRE candidates.
