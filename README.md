# Hashicat Networking
The networking portion for a demo featuring the Hashicat app.

## Inputs:
- `prefix`: a memorable prefix to be included in the name of most resources. E.g. 'ricardo'

## Outputs:
- `resource_group_name`: the name of the resource group for all the components of Hashicat. This will be used by other modules.
- `vm_subnet_id`: id of the subnet for the VM.
- `appgw_subnet_id`: id of the subnet for the App GW.
- `security_group_id`: id of the SG to be used by the VM to allow SSH access.

## Resources created:
- Resource Group: for all the resources to be used in the Hashicat demo app
- Virtual Network
- Subnet for the VMs
- Subnet for Application Gateways
- Security group for enabling communication between subnets
- Security group for enabling SSH access to the VM
