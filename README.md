---
page_type: sample
languages: java
products: azure
services: Containerregistry
platforms: java
author: yaohaizh
---

## Getting Started with Containerregistry - Manage Container Registry - in Java ##


  Azure Container Registry sample for managing container registry.
     - Create an Azure Container Registry to be used for holding the Docker images
     - If a local Docker engine cannot be found, create a Linux virtual machine that will host a Docker engine
         to be used for this sample
     - Use Docker Java to create a Docker client that will push/pull an image to/from Azure Container Registry
     - Pull a test image from the public Docker repo (hello-world:latest) to be used as a sample for pushing/pulling
         to/from an Azure Container Registry
     - Create a new Docker container from an image that was pulled from Azure Container Registry
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/acr-java-manage-azure-container-registry.git

    cd acr-java-manage-azure-container-registry

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.