# drupal-k8s
Launching Drupal instances in a k8s cluster

1. Create following directories on worker nodes:
- /drupal-data
- /drupal-mysql-data

2. Create kubernetes objects using the YAML files.
3. Access the drupal site using IP and port exposed by the NodePort services.
4. Make use of credentials mentioned in secret object and the cluster IP service name to configure the DRUPAL application.
