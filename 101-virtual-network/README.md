# Virtual Network with two Subnets

<a href="https://azuredeploy.net/" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template allows you to create a Virtual Network with two subnets.

Below are the parameters that the template expects

| Name   | Description    |
|:--- |:---|
| location | Region where the resources will be deployed |
| virtualNetworkName | Name of Virtual Network |
| addressPrefix | Address prefix for the Virtual Network specified in CIDR format |
| subnet1Name | Name of Subnet-1 |
| subnet2Name | Name of Subnet-2 |
| subnet1Prefix | Prefix for the Subnet-1 specified in CIDR format |
| subnet2Prefix | Prefix for the Subnet-2 specified in CIDR format |