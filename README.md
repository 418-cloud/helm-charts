## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add 418-cloud https://charts.418.cloud

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
418-cloud` to see the charts.

To install the simple-app chart:

    helm install my-simple-app 418-cloud/simple-app

To uninstall the chart:

    helm delete my-simple-app
