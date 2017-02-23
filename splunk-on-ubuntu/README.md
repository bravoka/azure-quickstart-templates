# Create Splunk Enterprise standalone or cluster on Azure


# KY Modified Splunk Deployment
Testing changes privately made to the Azure Splunk Ubuntu template 

The Original Git is here:
https://github.com/Azure/azure-quickstart-templates/tree/master/splunk-on-ubuntu (see original Readme)

##Differences between this Modified Deployment vs the Original Deployment
* Modifiable number of search heads
* Search heads are clustered on deployment
* Splunk version 6.5.2
* Master is set as the deployer for the search head cluster
* Layer-7 load balancer for the search head cluster
* Public IP address for the load balancer
* Heavy Forwarder deployed with Indexer Discovery

##Use this link here (below) to use the modified deployment in Azure:
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbravoka%2Fazure-quickstart-templates%2Fmaster%2Fsplunk-on-ubuntu%2Fazuredeploy.json"><img src="https://camo.githubusercontent.com/8305b5cc13691600fbda2c857999c4153bee5e43/68747470733a2f2f617a7572656465706c6f792e6e65742f6465706c6f79627574746f6e2e706e67" alt="Deploy to Azure" data-canonical-src="https://azuredeploy.net/deploybutton.png" style="max-width:100%;"></a>
