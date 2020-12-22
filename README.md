![logo](https://raw.githubusercontent.com/tumido/crd-snippets/master/docs/assets/icon_large.png)

# Kubernetes CRD Snippets

[![](https://img.shields.io/github/v/release/tumido/crd-snippets)](https://github.com/tumido/crd-snippets/releases)
[![](https://img.shields.io/visual-studio-marketplace/v/tumido.crd-snippets?label=vs%20marketplace)](https://marketplace.visualstudio.com/items?itemName=tumido.crd-snippets)
[![](https://img.shields.io/open-vsx/v/tumido/crd-snippets)](https://open-vsx.org/extension/tumido/crd-snippets)
[![](https://img.shields.io/github/license/tumido/crd-snippets)](https://github.com/tumido/crd-snippets/blob/master/LICENSE)
[![](https://img.shields.io/github/workflow/status/tumido/crd-snippets/Release)](https://github.com/tumido/crd-snippets/actions?query=workflow%3ARelease)

YAML snippets for popular Kubernetes Custom Resources. If you'd like to see snippets for CRDs you use, just [file an issue](https://github.com/tumido/crd-snippets/issues/new) or submit a PR - contributions are welcome!

## Suggested extensions

1. Snippets for native Kubernetes resouces, choose which fits your needs the best:
   - [`ipedrazas.kubernetes-snippets`](https://marketplace.visualstudio.com/items?itemName=ipedrazas.kubernetes-snippets)
   - [`lunuan.kubernetes-templates`](https://marketplace.visualstudio.com/items?itemName=lunuan.kubernetes-templates)
2. [`redhat.vscode-yaml`](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) - provides intellisense on YAML schemes. That means, once the `kind` and `apigroup` is defined, this Extension can offer completions for schemes available at [schemastore.org](https://www.schemastore.org/json/)

## Features

Includes snippets for following CRDs:

<table>
   <thead>
      <tr>
         <th>Project</th>
         <th>Group</th>
         <th>Kind</th>
         <th>Snippet prefix</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td rowspan=3><a href="https://kustomize.io/">Kustomize</a></td>
         <td rowspan=3><code>kustomize.config.k8s.io</code></td>
         <td><code>Kustomization</code></td>
         <td><code>kustomization</code></td>
      </tr>
      <tr>
         <td><code>Component</code></td>
         <td><code>component</code></td>
      </tr>
      <tr>
         <td>Json 6902 Patch</td>
         <td><code>json-patch</code><br /><code>json-6902</code></td>
      </tr>
      <tr>
         <td rowspan=3><a href="https://argoproj.github.io/argo/">Argo Workflows</a></td>
         <td rowspan=3><code>argoproj.io</code></td>
         <td><code>Workflow</code></td>
         <td><code>argo-workflow</code><br /><code>argo-wf</code><br /><code>argo-wf-template-ref</code></td>
      </tr>
      <tr>
         <td><code>WorkflowTemplate</code></td>
         <td><code>argo-workflowtemplate</code><br /><code>argo-wftmpl</code></td>
      </tr>
      <tr>
         <td><code>CronWorkflow</code></td>
         <td><code>argo-cronworkflow</code><br /><code>argo-cronwf</code><br /><code>argo-cronwf-template-ref</code></td>
      </tr>
      <tr>
         <td rowspan=2><a href="https://argoproj.github.io/argo-cd">Argo CD</a></td>
         <td rowspan=2><code>argoproj.io</code></td>
         <td><code>Application</code></td>
         <td><code>argocd-application</code></td>
      </tr>
      <tr>
         <td><code>Project</code></td>
         <td><code>argocd-project</code></td>
      </tr>
      <tr>
         <td rowspan=3><a href="https://github.com/integr8ly/grafana-operator">Grafana (Integreatly)</a></td>
         <td rowspan=3><code>integreatly.io</code></td>
         <td><code>Grafana</code></td>
         <td><code>grafana-instance</code></td>
      </tr>
      <tr>
         <td><code>GrafanaDasboard</code></td>
         <td><code>grafana-dashboard</code></td>
      </tr>
      <tr>
         <td><code>GrafanaDatasource</code></td>
         <td><code>grafana-datasource</code></td>
      </tr>
   </tbody>
</table>
