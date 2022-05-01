# drupal-k8s
Launching Drupal instances in a k8s cluster

Create following directories on worker nodes:
- /drupal-data
- /drupal-mysql-data

Access the drupal site using IP and port exposed by the NodePort services.

Make use of credentials mentioned in secret object and the cluster IP service name to configure the DRUPAL application.
