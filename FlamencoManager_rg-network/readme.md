# Network Template

This template deploys a vnet with two subnets.
One for the Flamenco Manager node and one for the Flamenco Worker nodes.

A NIC or network interface is included in the manager subnet, pre-configured with the expected private IP address.

Network Security Groups with default settings are also created and associated with the subnets.


Note: This and most templates here  will contain a GUID enabling us to keep track of usage and usefulness.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FATLGaming%2FFlamenco-and-Blender-on-Azure%2Fmaster%2FFlamencoManager_rg-network%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FATLGaming%2FFlamenco-and-Blender-on-Azure%2Fmaster%2FFlamencoManager_rg-network%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
