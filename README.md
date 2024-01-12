# reference-example-components
Reference example ODA Components Helm Chart repository


[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add oda-components https://lesterthomas.github.io/reference-example-components

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
oda-components` to see the charts.

To install the <chart-name> chart:

    helm install <release name> oda-components/<chart-name> -n components

To uninstall the chart:

    helm delete <release name> -n components
