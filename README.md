# K8S Community Cluster

This repo contains information about how to take advantage of the Kubernetes
community cluster provided by Buoyant through the generous support of the
CNCF community infrastructure lab.

The primary goal of this cluster is to provide a test and reproduction
environment for the Linkerd community. The cluster has a few baseline
tests that exercise the latest release of Linkerd.

If you would like to request access to the cluster for any debugging or
bug reproduction purposes, open an issue that describes what you are
using the cluster for and an email address for us to send you an invite
from Stackpoint.io.

# Stackpoint Dashboard
Once you have a stackpoint account setup, you should see the cluster named
"SPC Orange Mouse". Clicking on the cluster name takes you to the cluster
information dashboard. To interact with the cluster, you will need the
a `kubeconfig`. You can download the config by clicking on the kubeconfig
menu option to the left of the cluster information dashboard.

After the download completes, edit your bash profile and append the path to
your downloaded config to your `KUBECONFIG` environment variable. 
