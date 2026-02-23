# kind-local-dev

## Prerequisites
* [Homebrew](https://docs.brew.sh/Installation)
* [Task](https://taskfile.dev/) (`brew install go-task/tap/go-task`)

## File structure
```bash
.
├── clusters/
│   └── kind-local-dev/  # Flux bootstrap entrypoint (auto-generated)
├── infrastructure/      # Crossplane Providers & ProviderConfigs
├── platform/            # Crossplane XRDs (APIs) & Compositions
├── apps/                # Application manifests & HelmReleases
├── Taskfile.yml
├── .gitignore
└── README.md
```
