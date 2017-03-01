# acs-swarmm
Swarm Mode orchestrator with VMSS and Managed Disks
## Requires pre-provisioned resource group with VNET and subnets
- See /scripts dir for provisioning scripts
- Use /scripts/prep.sh for pre-provisioining resources before clicking on **Deploy to Azure**
- Generated with [acs-engine](https://github.com/Azure/acs-engine)
- Installs Docker CS
- For setting up monitoring see [monitoring](https://github.com/kbhattmsft/autoscaling)

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkbhattmsft%2Facs-swarmm%2Fmaster%2Fazuredeploy.json)
