How to Create Amazon EKS Cluster Using Terraform

What is Terraform?

It is an open-source IaaC (Infrastructure as a code) software tool where you define and create resources using providers in the declarative configuration language example JSON.
With Terraform, You can package and reuse the code in the form of modules.
It supports a number of cloud infrastructure providers such as AWS, Azure, GCP, IBM Cloud, OCI, etc.


What is Amazon EKS?
How to Create Amazon EKS Cluster Using Terraform 2
Amazon EKS (Elastic Kubernetes Service) is a managed Kubernetes service provided by Amazon Web Services (AWS). It simplifies the process of deploying, managing, and scaling containerized applications using Kubernetes on AWS infrastructure.

With Amazon EKS, users can leverage the power of Kubernetes without the complexity of managing the underlying infrastructure. EKS handles tasks such as cluster provisioning, upgrades, and scaling, allowing developers to focus on building and deploying applications.

Example: Imagine a software development team wants to deploy a microservices-based application using containers. Instead of managing the Kubernetes cluster themselves, they can use Amazon EKS. They define their application’s architecture, specify resource requirements, and deploy it to the EKS cluster. Amazon EKS takes care of provisioning and managing the Kubernetes control plane, worker nodes, networking, and other infrastructure components. This allows the team to focus on developing their application while benefiting from the scalability, reliability, and flexibility of Kubernetes on AWS.

Prerequisites
Before you start creating, you’ll need the following:

an AWS account;
identity and access management (IAM) credentials and programmatic access;
AWS credentials that are set up locally with aws configure;
a code or text editor, like VS Code;
install and Set Up kubectl on Windows.
Once you have finished with the prerequisites, it is time to start writing the code to create an EKS cluster.

