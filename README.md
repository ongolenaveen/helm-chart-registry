# Helm Chart Registry to Store the Built .tar Files
## To use the Helm Chart Create Helm Repo using following command in your machine
```bash
helm repo add samplehelm https://github.com/ongolenaveen/helm-chart-registry
```
## To Search for Repo add install add following commands

```bash
helm search repo  <Mock Name>
```

## Create Value File Needed by looking into following values
```bash
 helm show values samplehelm/<Mock Name> --version 1.0.0
```

## Install Helm Chart using following command
```bash
 helm install [NAME] [CHART] [flags]
```