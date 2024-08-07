# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
![image](https://github.com/user-attachments/assets/b91d8fa6-9f79-4a78-a1cd-b305a09f112f)

* Deploy to Docker Hub / build-and-deploy
  ![image](https://github.com/user-attachments/assets/112b2383-78f7-43c3-b6b5-5855603f9015)

  ![image](https://github.com/user-attachments/assets/c9f94e7e-c41b-4f02-9a9b-78df5907e98d)
  ![image](https://github.com/user-attachments/assets/d382d267-222d-4840-a586-7c5ba337163d)


## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
