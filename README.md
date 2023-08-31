# Deploy MySQL by the concept of ConfigMap, Secret and Persistent Volume in K8s
### Secret
 Secret is an object used to store and manage sensitive information, such as passwords, API tokens, and encryption keys. It's a way to securely store and access confidential data that your applications or services may need without exposing this information in your Kubernetes configuration files.
 
## ![image](https://github.com/umer6921/secret-mysql-deploy/assets/75561123/ce25f41f-6464-4c3b-aeb9-c47b877fdb03)
### ConfigMap
ConfigMap is a resource object that allows you to store and manage configuration data that is not confidential, separately from your application code. It's like a key-value store for configuration settings. ConfigMaps are typically used to store configuration details such as environment variables, configuration files, or any other settings that your pods or containers may need. It makes it easier to manage and update configuration settings without modifying your application code or container images.

![image](https://github.com/umer6921/secret-mysql-deploy/assets/75561123/ddb2fde5-ccbc-49b9-9f47-db5086ceee9b)

