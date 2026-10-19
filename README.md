# SRE Interview

## Setup

If you have `aws cli`, `kubectl`, `helm`, and `git` installed locally, your interviewer will provide AWS credentials and a cluster to work with.

If not, open a Killercoda playground: **https://killercoda.com/playgrounds/scenario/kubernetes**

## Your task

Deploy the Helm chart in `./resources/chart/` and fix the issues you find.

*Think out loud.*
- Deploy the chart to your namespace of choice
- Identify the issues
- Fix the issues by editing chart templates
- Verify the service is working

## Files

```
resources/
└── chart/
    ├── Chart.yaml
    ├── values.yaml
    └── templates/
```

**Available tools**: `helm`, `kubectl`, Kubernetes and Helm documentation
