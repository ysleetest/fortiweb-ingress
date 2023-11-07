

# Fortiweb Ingress Controller
Below content is the basic know-how and quick start for FortiWEB Ingress Controller.
For more much details, please refer to the [official document](https://docs.fortinet.com/document/fortiweb/7.4.0/ingress-controller-installation-guide/742835/fortiweb-ingress-controller-overview).

</br>
</br>
</br>

The FortiWEB Ingress Controller fulfills the Kubernetes Ingress resources and allows you to manage FortiWEB objects from Kubernetes. It is deployed in a container of a pod in a Kubernetes cluster. The list below outlines the major functionalities of the FortiWEB Ingress Controller:

 - To list and watch Ingress related resources, such as Ingress, Service, Node and Secret.
 - To convert Ingress related resources to FortiWEB objects, such as virtual server, content routing, real server pool, and more.
 - To handle Add/Update/Delete events for watched Ingress resources and automatically implement corresponding actions on FortiWEB.


 ![Ingress](https://raw.githubusercontent.com/fortinet/fortiweb-ingress/main/figures/ingress.png)

