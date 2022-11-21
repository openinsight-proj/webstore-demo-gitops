# webstore-demo-gitops

This repo demonstrates how an OTS (off-the-shelf) helm chart can be retrieved and pinned to a specific helm sem version from an upstream helm repository, and customized using a custom values.yaml in the private git repository.

More information can be found at <https://github.com/argoproj/argocd-example-apps/tree/master/helm-dependency>

We referenced a chart from [openinsight-proj/openinsight-helm-charts](https://github.com/openinsight-proj/openinsight-helm-charts/tree/main/charts/opentelemetry-demo)，which create an application named `webstore`.
