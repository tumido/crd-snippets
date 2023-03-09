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
2. [`redhat.vscode-yaml`](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) - provides intellisense on YAML schemes. That means, once the `kind` and `apiVersion` is defined, this Extension can offer completions for schemas available at [schemastore.org](https://www.schemastore.org/json/)

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
         <td rowspan=3><a href="https://argoproj.github.io/argo-workflows/">Argo Workflows</a></td>
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
         <td rowspan=3><a href="https://argo-cd.readthedocs.io/en/stable/">Argo CD</a></td>
         <td rowspan=3><code>argoproj.io</code></td>
         <td><code>Application</code></td>
         <td><code>argocd-application</code></td>
      </tr>
      <tr>
         <td><code>ApplicationSet</code></td>
         <td><code>argocd-application-set</code></td>
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
         <td><a href="https://www.kubeflow.org/">Kubeflow</a><br /><a href="https://opendatahub.io/">Open Data Hub</a></td>
         <td><code>kfdef.apps.kubeflow.org/v1</code></td>
         <td><code>KfDef</code></td>
         <td><code>kubeflow-kfdef<br />odh-kfdef</code></td>
      </tr>
      <tr>
         <td rowspan=8><a href="https://docs.openshift.com/">Openshift</a></td>
         <td><code>apps.openshift.io/v1</code></td>
         <td><code>DeploymentConfig</code></td>
         <td><code>openshift-deploymentconfig<br />openshift-deployment-config<br />openshift-dc</code></td>
      </tr>
      <tr>
         <td><code>build.openshift.io/v1</code></td>
         <td><code>BuildConfig</code></td>
         <td><code>openshift-buildconfig<br />openshift-build-config<br />openshift-bc</code></td>
      </tr>
      <tr>
         <td><code>image.openshift.io/v1</code></td>
         <td><code>ImageStream</code></td>
         <td><code>openshift-imagestream<br />openshift-image-stream<br />openshift-is</code></td>
      </tr>
      <tr>
         <td><code>project.openshift.io/v1</code></td>
         <td><code>Project</code></td>
         <td><code>openshift-project</code></td>
      </tr>
      <tr>
         <td><code>user.openshift.io/v1</code></td>
         <td><code>Group</code></td>
         <td><code>openshift-group</code></td>
      </tr>
      <tr>
         <td><code>route.openshift.io/v1</code></td>
         <td><code>Route</code></td>
         <td><code>openshift-route</code></td>
      </tr>
      <tr>
         <td><code>operators.coreos.com/v1alpha1</code></td>
         <td><code>Subscription</code></td>
         <td><code>openshift-subscription</code></td>
      </tr>
      <tr>
         <td><code>operators.coreos.com/v1</code></td>
         <td><code>OperatorSource</code></td>
         <td><code>openshift-operator-source</code></td>
      </tr>
      <tr>
         <td rowspan=2>Spark by <a href="https://github.com/radanalyticsio/spark-operator">Radanalytics.io</a></td>
         <td rowspan=2><code>radanalytics.io/v1</code></td>
         <td><code>SparkCluster</code></td>
         <td><code>radanalyticsio-spark-cluster<br />spark-cluster</code></td>
      </tr>
      <tr>
         <td><code>SparkApplication</code></td>
         <td><code>radanalyticsio-spark-application</td>
      </tr>
      <tr>
         <td rowspan=2>Spark by <a href="https://github.com/GoogleCloudPlatform/spark-on-k8s-operator"><code>spark-on-k8s-operator</code></a></td>
         <td rowspan=2><code>sparkoperator.k8s.io/v1beta1</code></td>
         <td><code>ScheduledSparkApplication</code></td>
         <td><code>spark-on-k8s-operator-scheduled-spark-application<br />scheduled-spark-application</code></td>
      </tr>
      <tr>
         <td><code>SparkApplication</code></td>
         <td><code>spark-on-k8s-operator-spark-application</td>
      </tr>
   </tbody>
</table>
