```
Q. You want to deploy multiple copies of your application, so that you can load balance traffic across them. How should you deploy this application's Pods to the production Namespace in your cluster?
```
```
Create a Deployment manifest that specifies the number of replicas that you want to run.
```
---
---

```
Q. When configuring storage for stateful applications, what steps must you take to provide file system storage inside your containers for data from your applications that will not be lost or deleted if your Pods fail or are deleted for any reason?
```
```
You must create Volumes using network based storage to provide durable storage remote to the Pods and specify these in the Pods.
```
---
---
```
Q. You need to ensure that the production applications running on your Kubernetes cluster are not impacted by test and staging deployments. Which features should you implement and configure to ensure that the resources for your production applications can be prioritized?
```
```
Configure Namespaces for Test, Staging and Production and configure specific Kubernetes resource quotas for the test and staging Namespaces.
```
---
---
```
Q. You have a new logging and auditing utility that you need to deploy on all of the nodes within your cluster. Which type of controller should you use to handle this task?
```
```
DaemonSet
```
---
---
```
Q. Which Kubernetes component does the kubectl command connect to in order to carry out operations on a cluster?
```
```
kube-apiserver
```
---
---
```
Q. You are designing an application, and you want to ensure that the containers are located as close to each other as possible, in order to minimize latency. Which design decision helps meet this requirement?
```
```
Place the containers in the same Pod.
```

---
---
```
Q. If you are deploying applications in your Pods that need persistent storage, which controller type should you use?
```
```
Statefulset
```
---
---
```
Q. What is the purpose of a Service? Choose all that are true (2 correct answers)
```
```
To allow you to choose how Pods are exposed

To provide a load-balancing network endpoint for Pods
```
---
---
```
Q. What is the purpose of the Deployment object?
```
```
To ensure that a defined set of Pods is running at any given time.
```
---
---
```
Q. What are Kubernetes namespaces useful for? Choose all that are correct (2 correct answers).
```
```
Namespaces allow you to use object names that would otherwise be duplicates of one another.

Namespaces let you implement resource quotas across your cluster.
```
---
---
```
Q. In GKE, how are control planes provisioned?
```
```
As abstract parts of the GKE service that are not exposed to Google Cloud customers
```
---
---
```
Q. What is the purpose of configuring a regional cluster in GKE?
```
```
To allow applications running in the cluster to withstand the loss of a zone
```

---
---
```
Q. Which control plane component is the only one with which clients interact directly?
```
```
kube-apiserver
```
---
---
```
Q. What is the role of the kubelet?
```
```
To serve as Kubernetes’s agent on each node
```
---
---
```
Q. What is the difference between a pod and a container?
```
```
A pod contains one or more containers.
```
---
---
```
Q. You are deploying a containerized application, and you want maximum control over how containers are configured and deployed. You want to avoid the operational management overhead of managing a full container cluster environment yourself. Which Google Cloud compute solution should you choose?
```
```
Google Kubernetes Engine
```
---
---
```
Q. You are choosing a technology for deploying applications, and you want to deliver them in lightweight, standalone, resource-efficient, portable packages. Which choice best meets those goals?
```
```
Containers
```

---
---
```
Q. 
You are classifying a number of your applications into workload types. Select the stateful applications in this list of applications. Choose all responses that are correct (2 correct responses).
```
```
A shopping application that saves user shopping cart data between sessions.

A gaming application that keeps track of user state persistently.
```
---
---
```
Q. Google Compute Engine provides fine-grained control of costs. Which Compute Engine features provide this level of control? (2 correct responses)
```
```
Fully customizable virtual machines

Per-second billing
```
---
---
```
Q. Which of the following supports scaling a Kubernetes cluster as a whole?
```
```
Google Kubernetes Engine
```
---
---
```
Q. What is the relationship between Kubernetes and Google Kubernetes Engine?
```
```
Google Kubernetes Engine is Kubernetes as a managed service.
```
---
---
```
Q. What is a stateful application?
```
```
An application that requires user and session data to be stored persistently
```
---
---
```
Q. What is significant about the topmost layer in a container? Choose all that are true (2 correct answers).
```
```
An application running in a container can only modify the topmost layer.

The topmost layer's contents are ephemeral. When the container is deleted the contents will be lost.
```
---
---
```
Q. Why do Linux containers use union file systems?
```
```
To efficiently encapsulate applications and their dependencies into a set of clean, minimal layers
```
---
---
```
Q. 
Which of these problems are containers intended to solve? Mark all that are correct (3 correct answers).
```
```
Packaging applications in virtual machines can be wasteful.

Large monolithic applications that need to be run in the cloud.

Applications need a way to isolate their dependencies from one another.

It's difficult to troubleshoot applications when they work on a developer's laptop but fail in production.
```

---
---
```
Q. One of the key characteristics of cloud computing is the concept of measured service. What is the primary customer benefit of the measured service aspect of cloud computing?
```
```
You pay only for the resources you consume.
```
---
---
```
Q. You are ready to start work building an application in Google Cloud. What IAM hierarchy should you implement for this project?
```
```
Create a new folder inside your organization and create projects inside that folder for the resources.
```
---
---
```
Q. You are considering deploying a solution using containers on Google Cloud. What Google Cloud solutions are available to you that will provide a managed compute platform with native support for containers?
```
```
Google Kubernetes Engine Clusters
```
---
---
```
Q. You need to write some automated scripts to run periodic updates to the resources in your Google Cloud environment. What tools can you install in your own computers to allow you to run those scripts?
```
```
The Cloud SDK
```
---
---
```
Q. Which of these ways to interact with give you access to the gcloud and kubectl commands? Choose all that are correct (2 correct answers).
```
```
Cloud SDK

Cloud Shell
```
---
---
```
Q. At what level in the Google Cloud resource hierarchy is billing set up?
```
```
Project
```
---
---
```
Q. 
Which statements are true about cloud computing? Mark all that are true (2 correct answers).
```
```
Customers who need more resources can get them rapidly

Customers pay for the resources they use or reserve.
```

---
---
```
Q. Which of these Google Cloud compute services provides environments for execution of code, in which users don't have to worry about infrastructure management? Choose all that are correct (2 correct answers).
```
```
Cloud Functions

App Engine
```

---
---
```
Q. What is the base-level organizing entity for creating and using Google Cloud resources and services?
```
```
Project
```
---
---
```
Q. Within which of these Google Cloud geographic scopes are network latencies generally less than 1 millisecond? Choose all that are correct (2 correct answers).
```
```
Region

Zone
```
