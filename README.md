# prometheus-helm-charts
A helm chart to install prometheus and other required components on k8s cluster.

### Getting started
Clone this repository to your local machine.

`cd prometheus-helm-charts/prometheus-instance`

Before packaging this helm chart please check if there is some error.

`helm lint` 

If there is no error then you can create helm package from this chart.

`helm package [CHART_PATH]`

