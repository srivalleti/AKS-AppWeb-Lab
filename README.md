# AKS-AppWeb-Lab
This lab shows how to create a web application that consist of Frontend, API and a database "Mongodb" based on kubernetes deployments on an AKS cluster, to perform this lab follow these steps: </br>
> ## prerequisite before starting the lab
> 
> 1.   Azure Account (get it for free for 12 months with 200$ of credit to consume the first month of the subscription if do not have one already). [Azure free account](https://azure.microsoft.com/en-us/free/)
> 2.   AKS cluster ready for use, three ways to do it:
>       * using the portal (easy way with less details) [build AKS cluster using the portal] (https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough-portal)
>       * using the Cloud Shell or Azure CLI, follow this link to do so 
>       * using one of the IaC tools like Terraform, follow this link to do so [build AKS with Terraform](https://github.com/alli40alli/TerraformAzureKubernetesServices)

1. Deploy MongoDB
2. Deploy the API
3. Deploy the Frontend 
4. Deploy an ingress for the Frontend 
5. Enable SSL/TLS on the frontend ingress
6. Configure monitoring for the application 
7. Configure scaling to handle high demand
8. cleanup resources 

This is how the deployment will look like 

![result](https://docs.microsoft.com/en-us/learn/modules/aks-workshop/media/02-arch.svg)