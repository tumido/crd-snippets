![logo](https://raw.githubusercontent.com/tumido/crd-snippets/master/docs/assets/icon_large.png)

# Kubernetes CRD Snippets

YAML snippets for popular Kubernetes Custom Resources. If you'd like to see snippets for CRDs you use, just [file an issue](https://github.com/tumido/crd-snippets/issues/new) or submit a PR - contributions are welcome!

## Suggested extensions

1. Snippets for native Kubernetes resouces, choose which fits your needs the best:
   - [`ipedrazas.kubernetes-snippets`](https://marketplace.visualstudio.com/items?itemName=ipedrazas.kubernetes-snippets)
   - [`lunuan.kubernetes-templates`](https://marketplace.visualstudio.com/items?itemName=lunuan.kubernetes-templates)
2. [`redhat.vscode-yaml`](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) - provides intellisense on YAML schemes. That means, once the `kind` and `apigroup` is defined, this Extension can offer completions for schemes available at [schemastore.org](https://www.schemastore.org/json/)

## Features

Includes snippets for following CRDs:

| Project               | Group                     | Kind                | Snippet prefix                                                 |
| --------------------- | ------------------------- | ------------------- | -------------------------------------------------------------- |
| Kustomize             | `kustomize.config.k8s.io` | `Kustomization`     | `kustomization`                                                |
|                       |                           | `Component`         | `component`                                                    |
|                       |                           | JSON 6902 Patch     | `json-patch`, `json-6902`                                      |
| Argo Workflows        | `argoproj.io`             | `Workflow`          | `argo-workflow`, `argo-wf`, `argo-wf-template-ref`             |
|                       |                           | `WorkflowTemplate`  | `argo-workflowtemplate`, `argo-wftmpl`                         |
|                       |                           | `CronWrokflow`      | `argo-cronworkflow`, `argo-cronwf`, `argo-cronwf-template-ref` |
| Argo CD               | `argoproj.io`             | `Application`       | `argocd-application`                                           |
|                       |                           | `Project`           | `argocd-project`                                               |
| Grafana (Integreatly) | `integreatly.io`          | `Grafana`           | `grafana-instance`                                             |
|                       |                           | `GrafanaDasboard`   | `grafana-dashboard`                                            |
|                       |                           | `GrafanaDatasource` | `grafana-datasource`                                           |
