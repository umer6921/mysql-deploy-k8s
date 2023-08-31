# Deploying MySQL in Kubernetes using the principles of ConfigMap, Secret and Persistent Volume
### Secret
 Secret is an object used to store and manage sensitive information, such as passwords, API tokens, and encryption keys. It's a way to securely store and access confidential data that your applications or services may need without exposing this information in your Kubernetes configuration files.
 
## ![image](https://github.com/umer6921/secret-mysql-deploy/assets/75561123/ce25f41f-6464-4c3b-aeb9-c47b877fdb03)
### ConfigMap
ConfigMap is a resource object that allows you to store and manage configuration data that is not confidential, separately from your application code. It's like a key-value store for configuration settings. ConfigMaps are typically used to store configuration details such as environment variables, configuration files, or any other settings that your pods or containers may need. It makes it easier to manage and update configuration settings without modifying your application code or container images.

![image](https://github.com/umer6921/secret-mysql-deploy/assets/75561123/ddb2fde5-ccbc-49b9-9f47-db5086ceee9b)

## Persistent Volume
Persistent Volume is like a reserved storage locker that can be used by applications (pods) in a Kubernetes cluster. It allows you to decouple storage management from application deployment, making it easier to manage and scale storage independently of your applications.

![image](https://github.com/umer6921/K8s-secret-mysql-deploy/assets/75561123/d144e831-daf1-477c-a3e2-95bf7ffce030)

## Persistent Volume Claim
A Persistent Volume Claim (PVC) in Kubernetes is a request for a specific amount and class of storage resources by a pod. It's like placing an order for storage. When you create a PVC, Kubernetes finds an appropriate Persistent Volume (PV) that meets the specified requirements, binds it to the claim, and provides the pod with access to that storage.

![image](https://github.com/umer6921/K8s-secret-mysql-deploy/assets/75561123/e0617747-1ddd-4f90-ae79-60c79f0e926c)
## Stateless Applications
Stateless applications are designed in a way that they do not rely on storing their state or data on the local filesystem of the server where they are running.
## Statefull Applications
Stateful applications rely on storing and managing their state or data on the local filesystem or attached storage volumes. Examples of stateful applications include databases (e.g., MySQL, PostgreSQL), distributed data stores (e.g., Cassandra, MongoDB), and applications that rely on persistent storage.

## Stateless Vs statefull design
Stateless designs are often preferred for services that need to be highly available and scalable, while stateful designs are necessary when applications must maintain unique state and data across instances.
