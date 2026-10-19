# Kubernetes Interview

## Getting Started

### 1. Open a Killercoda playground

Go to: **https://killercoda.com/playgrounds/scenario/kubernetes**

This gives you a browser-based terminal with a running Kubernetes cluster. `kubectl` and `helm` are pre-installed.

### 2. Clone this repo in the Killercoda terminal

### 3. Your task

Deploy the chart and fix the two issues you find.

*Think out loud.*
- Deploy the chart from `./resources/chart/` to your namespace of choice (or default)
- Identify the two issues the chart has
- Fix both issues by editing chart templates
- Verify service endpoints are populated and working

## Files and Directories

```
dexcare-interview/
├── README.md                    # This file
└── resources/                   # Helm charts
    └── chart/                   # Chart with issues to debug
```

**Available tools**:
- `helm` command-line tool
- `kubectl` command-line tool
- Access to Kubernetes documentation and Helm documentation
