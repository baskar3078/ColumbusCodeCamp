---
services: service-fabric
platforms: dotnet

This Sample of code was taken from Microsoft Azure Service Fabric Samples. 

After downloading the code do the below steps to create your cloud cluster.

You can try azure service fabric for free using the below url to create your own cluster.
1. Login to https://try.servicefabric.azure.com/
2. Use your facebook or github credentials.
3. Then select Join Windows Cluster.
4. You will get the details of your cluster.

You can use Service Fabric explorer url to manage your service fabric cluster.This is a sample below.
http://winx6ituukqh.westus.cloudapp.azure.com:19080/Explorer/index.html

Copy the connection endpoint from above portal and update the Publish Profile - Cloud.Xml
As shown below.
<ClusterConnectionParameters ConnectionEndpoint="winx2bmbhhjn.westus.cloudapp.azure.com:19000" />

Publish steps are covered in the word document.

Contact me for any questions on service fabric at baskarrao.dandlamudi@outlook.com

Below are the links for trying various sample projects from azure portal.

# Service Fabric .NET Quickstart
This repository contains an quickstart project for [Microsoft Azure Service Fabric](https://azure.microsoft.com/services/service-fabric/). The quickstart project contains a single application with multiple services demonstrating the basic concepts of service communication and use of reliable dictionaries.

For a guided tour with the quickstart:
[Service Fabric .NET quickstart](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-quickstart-dotnet)

More info on Service Fabric:
 - [Documentation](https://docs.microsoft.com/azure/service-fabric/)
 - [Service Fabric sample projects](https://azure.microsoft.com/resources/samples/?service=service-fabric)
 - [Service Fabric open source home repo](https://github.com/azure/service-fabric)

---
*This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.*
