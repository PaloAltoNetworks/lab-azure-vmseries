# 1. Palo Alto Networks VM-Series on Microsoft Azure

<p align="center">
<img src="https://www.paloaltonetworks.com/content/dam/pan/en_US/images/logos/brand/primary-company-logo/Parent-logo.png" width=50% height=50%>
</p>

## 1.1. Overview

This lab will involve deploying a solution for Azure using Palo Alto Networks VM-Series in a Azure Load Balancer topology.

The lab assumes the following a Requirement:

- Existing and Active Microsoft Azure Subscription
- If you don't have a Azure Subscription visit please <https://azure.microsoft.com/en-us/free/> and create one
- VM-Series Firewalls uses in that lab a PAYG License. You can use a Lab License if you one

The Lab Instructions can be found [HERE](https://github.com/PaloAltoNetworks/lab-azure-vmseries/tree/main/Lab%20Guide).

```
Lab Guide Last Updated: 2022-10-19
Lab Last Tested: 2022-05-31
```

## 1.2. Deploy Azure Environment

Deploy 2xVM-Series firewall with 2 Spoke VNETs. Includes Public and Internal Load Balancer

<p align="center">
<img src="https://github.com/PaloAltoNetworks/Azure_Training/blob/main/Azure%20Basic%20Lab/Images/2fw_3nic_avset_intlb_extlb.png">
</p>

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPaloAltoNetworks%2FAzure_Training%2Fmain%2FAzure%20Basic%20Lab%2FazureDeploy.json)
</br>
</br>
</br>

## 1.3.  Deploy WebApp

In this part, We will Deploy a single Linux Server in a dedicated Resource Group
<p align="center">
<img src="https://github.com/PaloAltoNetworks/RegionalTrainings2021/blob/main/Images/webapp.png">
</p>

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPaloAltoNetworks%2FAzure_Training%2Fmain%2FAzure%20Advanced%20Lab%2Fspokedeployment.json)
</br>
</br>
</br>
