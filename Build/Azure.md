# [Docs](https://docs.microsoft.com/en-us/azure/?product=featured)
[Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
[Zero Trust Deployment Guide](https://www.microsoft.com/security/blog/2020/04/30/zero-trust-deployment-guide-azure-active-directory/)
[Recommended resource abbreviations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)
[Azure Best Practices](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/)
# Tools
[Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)
[Digital Ocean Pricing Calculator](https://www.digitalocean.com/pricing/calculator/)
[Bandwidth pricing](https://azure.microsoft.com/en-us/pricing/details/bandwidth/)
# Products
## Analytics
[HDInsights](https://docs.microsoft.com/en-us/azure/hdinsight/)
[Azure Synapse](https://docs.microsoft.com/en-us/azure/synapse-analytics/)
[Azure Data Lake Analytics](https://docs.microsoft.com/en-us/azure/data-lake-analytics/)
## Developer Tools
[Azure Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/?view=azure-devops)
[Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/)
## Security
[Azure Security Center](https://docs.microsoft.com/en-us/azure/security-center/)
[Azure Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/)
[Azure Information Protection](https://docs.microsoft.com/en-us/azure/information-protection/)
### Management and Governance
[Azure Policy](https://docs.microsoft.com/en-us/azure/governance/policy/)
[Azure Advisor](https://docs.microsoft.com/en-us/azure/advisor/)
[Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/)
[Cost Management + Billing](https://docs.microsoft.com/en-us/azure/cost-management-billing/)
[Azure Resource Manager](https://docs.microsoft.com/en-us/azure/azure-resource-manager/)
	- [Azure Resource Manager Templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/)
## Network
[Virtual Networks](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
[VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/)
### Partners
[Azure Marketplace](https://docs.microsoft.com/en-us/azure/marketplace/)
### Storage
[Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/)
# Development
[Azurite](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azurite)
[Azure Cosmos Emulator ](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator?tabs=ssl-netstd21)
[Recommended abbreviations for Azure resource types](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)
[Azure Functions Core Tools](https://github.com/Azure/azure-functions-core-tools)
# Certifications
## Sites
- [Azure Updates](https://azure.microsoft.com/en-us/updates/)
- [Service Trust Portal](https://servicetrust.microsoft.com/)
- [Modern Lifecycle Policy](https://docs.microsoft.com/en-us/lifecycle/policies/modern)
- [Azure Status](https://status.azure.com/en-us/status)
## Browse
- Prio 1
	- [Cost Management + Billing](https://docs.microsoft.com/en-us/azure/cost-management-billing/)
	- Azure Marketplace
	- [Azure Advisor](https://docs.microsoft.com/en-us/azure/advisor/)
	- Azure Security Center
	- Azure Policy
	- [Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/)
	- ARM
		- Lock resources to prevent unexpected changes
	- Subscriptions
	- [Azure Information Protection](https://docs.microsoft.com/en-us/azure/information-protection/)
	- Help + Support
	- Azure Activity Log
- Prio 2
	- [VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/)
	- Azure Key Vault
	- Azure Synapse
	- Azure Data Lake Analytics
	- Virtual Networks
	- HDInsights
	- [Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/)
	- [Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/)
## Read
- Prio 1
	- [Cost Management + Billing](https://docs.microsoft.com/en-us/azure/cost-management-billing/)
	- [Azure Advisor](https://docs.microsoft.com/en-us/azure/advisor/)
	- Azure Policy
	- Azure Security Center
	- [Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/)
	- ARM
	- [Azure Information Protection](https://docs.microsoft.com/en-us/azure/information-protection/)
- Prio 2
	- Virtual Networks
	- Azure Synapse
	- Azure Data Lake Analytics
	- Azure Key Vault
	- [VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/)
	- [Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/)
	- [Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/)
## Done
- [Availability Zones](https://docs.microsoft.com/en-us/azure/availability-zones/az-overview)
## Notes
- [What’s the Best Microsoft Azure Certification Path For Me? (A Cloud Guru)](https://acloudguru.com/blog/engineering/which-azure-certification-is-right-for-me)
- SLAs
	- Azure AD SLA = 99.99%
		- No SLA is provided for the Free tier of Azure Active Directory.
	- [SLA for VMs](https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/v1_9/)
		- Notes
		  For all Virtual Machines that have two or more instances deployed across two or more Availability Zones in the same Azure region, we guarantee you will have Virtual Machine Connectivity to at least one instance at least 99.99% of the time.
		  For all Virtual Machines that have two or more instances deployed in the same Availability Set or in the same Dedicated Host Group, we guarantee you will have Virtual Machine Connectivity to at least one instance at least 99.95% of the time.
		  For any Single Instance Virtual Machine using Premium SSD or Ultra Disk for all Operating System Disks and Data Disks, we guarantee you will have Virtual Machine Connectivity of at least 99.9%.
		  For any Single Instance Virtual Machine using Standard SSD Managed Disks for Operating System Disk and Data Disks, we guarantee you will have Virtual Machine Connectivity of at least 99.5%.
		  For any Single Instance Virtual Machine using Standard HDD Managed Disks for Operating System Disks and Data Disks, we guarantee you will have Virtual Machine Connectivity of at least 95%.
	- Composite SLAs
	  Composite SLAs involve multiple services supporting an application, each with differing levels of availability. For example, consider an App Service web app that writes to Azure SQL Database. At the time of this writing, these Azure services have the following SLAs:
	  - App Service web apps = 99.95%
	  - SQL Database = 99.99%
	  What is the maximum downtime you would expect for this application? If either service fails, the whole application fails. The probability of each service failing is independent, so the composite SLA for this application is 99.95% x 99.99% = 99.94%. That's lower than the individual SLAs, which isn't surprising because an application
	- Credits
		- If your monthly uptime percentage is below the guaranteed amount in the SLA, you can claim a credit.
		- If the Service Level Agreement for an Azure service is not met, you receive credits for that service and that service only. The credits are deducted from your monthly bill for that service. If you stopped using the service where the SLA was not met, your account would remain in credit for that service. The credits would not be applied to any other services that you may be using.
- Azure AD Identity Protection
	- Notes
	  Document Watermark
	  You need to ensure that when Azure Active Directory (Azure AD) users connect to Azure AD from the Internet by using an anonymous IP address, the users are prompted automatically to change their password
	  Azure AD Identity Protection includes two risk policies: sign-in risk policy and user risk policy. A sign-in risk represents the probability that a given authentication request isn’t authorized by the identity owner
	  There are several types of risk detection. One of them is Anonymous IP Address. This risk detection type indicates sign-ins from an anonymous IP address (for example, Tor browser or anonymous VPN). These IP addresses are typically used by actors who want to hide their login telemetry (IP address, location, device, etc.) for potentially malicious intent
	  You can configure the sign-in risk policy to require that users change their password.
- Azure lifecycle
	- Notes
	  Private Preview
	  
	  An Azure feature in private preview is available to specific Azure customers for evaluation purposes. This is typically by invite only and issued directly by the product team responsible for the feature or service. It should not be used in a production environment.
	  
	  Public Preview
	  
	  Correct: An Azure feature in public preview is available to all Azure customers for evaluation purposes. These previews can be turned on through the preview features page as detailed below.
	  
	  General Availability
	  
	  Correct: Once a feature has been evaluated and tested successfully, it might be released to customers as part of Azure's default product set. This release is referred to as General Availability (GA).
	  
	  Preview features are made available to you on the condition that you accept additional terms which supplement the regular Azure terms. The supplemental terms state:
	  “PREVIEWS ARE PROVIDED "AS-IS," "WITH ALL FAULTS," AND "AS AVAILABLE," AND ARE EXCLUDED FROM THE SERVICE LEVEL AGREEMENTS AND LIMITED WARRANTY.”
- [Locks](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources)
	- Notes
	  Azure resources inherit locks from the resource group they are part of
	  If your VM has a Read-only lock applied, you can add a Delete lock as well
	  A resource can have multiple locks applied, either at the resource level itself, or for example, one lock applied at the resource level, a second one at the resource group, another at the subscription level
- ComosDB
	- PaaS
- Resource Manager
	- Notes
	  Nested resource groups are not available in Azure, so deploying a resource group inside another resource group is not possible
	  A resource group can contain resources from multiple Azure regions
	  A resource group is a container that holds related resources for an Azure solution. The resource group stores metadata about the resources. Therefore, when you specify a location for the resource group, you are specifying where that metadata is stored
	  The location you choose for the resource group has nothing to do with the location you choose for your resources
	  Deleting the resource group will remove the resource group, as well as all the resources in that resource group
	  Tags for Resources are not inherited by default from their Resource Group
	  Azure resources inherit the permissions configured at the resource group level
	  Resource groups are logical containers for Azure resources. You do not pay for resource groups
- Azure Advisor
	- Notes
	  Advisor helps you optimize and reduce your overall Azure spend by identifying idle and underutilized resources. You can get cost recommendations from the Cost tab on the Advisor dashboard
	  Advisor is a personalized cloud consultant that helps you follow best practices to optimize your Azure deployments. It doesn't include recommendations targeting Azure Active Directory (Azure AD)
	  Once your VMs run for a bit in Azure, Advisor will start making recommendations on how to reduce your running VM costs
	  It doesn't include recommendations on how to configure the network settings on Azure virtual machines. Why? Because it really depends on how you want to use your VMs, so Azure Advisor wouldn't know what you want to implement 
- Support Plans
	- AZ-900
		- Azure Free Account
			- There is no upload limit attached to Azure free accounts. An Azure free account has a 5 GB blob storage limit and a 5 GB file storage limit for the first 12 months. Using blob and file storage up to these limits is free of charge
			- Azure free account has a limit of 10 web, mobile or API apps
		- [Azure Support Plans](https://azure.microsoft.com/en-us/support/plans/)
			- Only Standard and Professional Direct support plans include technical support via phone
		- [Subscriptions, licenses, accounts, and tenants for Microsoft's cloud offerings](https://docs.microsoft.com/en-us/microsoft-365/enterprise/subscriptions-licenses-accounts-and-tenants-for-microsoft-cloud-offerings?view=o365-worldwide)
		- Azure China is operated by 21Vianet. 21Vianet Group is the largest carrier-neutral Internet Service Provider (ISP) in China.
	- Az-104
	  You can move a storage account, VM and its associated resources to a different subscription by using the Azure portal.
	  You can also move an Azure Recovery Service (ASR) Vault to either a new resource group within the current subscription or to a new subscription.
	  Run Set-AzMarketplaceTerms to accept the legal terms. Accept or reject terms for a given publisher id(Publisher), offer id(Product) and plan id(Name)
- Availability Zones
	- Notes
	  Availability Zones in Azure represent unique physical locations, deployed within an Azure region. Each Availability Zone is made up of one or more data centers equipped with independent power, cooling, and networking. Some Azure regions, so not all Azure regions, support Availability Zones
	- Fault vs update domain
- CLI
	- [AzCopy](https://docs.microsoft.com/en-us/azure/storage/common/storage-ref-azcopy)
		- AZ-104
		  Up to v9 only on win64
		  AzCopy is a command-line utility that you can use to copy blobs or files to or from a storage account
		  AzCopy does not support copying data to Table & Queue
		  The azcopy copy command copies a directory (and all of the files in that directory) to a blob container. The result is a directory in the container by the same name.
		  Syntax is : azcopy copy '<local-directory-path>' 'https://<storage-account-name>.<blob or dfs>.core.windows.net/<container-name>' --recursive
		  Append the --recursive flag to upload files in all subdirectories.
	- PowerShell 6+ on all platforms
- Cost Management + Billing
	- Notes
	  Stopped virtual machines (which have been shut down from the operating system of the VM) will still incur charges.
	  However, stopped and deallocated virtual machines (shut down from the Azure Portal or via Azure command line tools) do not continue to incur charges until such time as they are restarted
	  
	  The pricing for Standard Load Balancer is based on the number of rules configured (load balancer rules and NAT rules) and data processed.
	  However, there is no hourly charge for the Standard Load Balancer itself when no rules are configured.
	  
	  In ARM deployment model, there is no charge for dynamic public IP addresses when the associated virtual machine is “stopped-deallocated”. However, you’re charged for a static public IP address irrespective of the associated resource (unless it is part of the first five static ones in the region). This resource should be removed.
	  
	  
	  You need to be the Administrator of the billing account that has the subscription to be able to transfer the subscription. This could be a Billing Administrator or Global Administrator. A subscription Owner can manage all resources and permissions within the subscription, but cannot transfer ownership of the subscription.
	- AZ-109
	  Billing Reader allows access to only billing components, such as Cost Management, and Consumption
- Azure Storage
	- [Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/)
		- [Storage Redundancy](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy?toc=/azure/storage/blobs/toc.json)
	- AZ-900
	  IaaS
	  Azure storage offers different access tiers: hot, cool and archive
	  The archive access tier has the lowest storage cost. But it has higher data retrieval costs compared to the hot and cool tiers. Data in the archive tier can take several hours to retrieve
	  While a blob is in archive storage, the blob data is offline and can't be read, overwritten, or modified. To read or download a blob in archive, you must first rehydrate it to an online tier
	- AZ-104
	  File Sync
	  file1.txt from Serve1 is renamed file1-Serve1.txt
	  When two server endpoints contain the same file name, the contents of both files are kept, the one that's synced first will be renamed to file1-{server-name}.{file-extension}
	  
	  azcopy copy 'https://s3.amazonaws.com/myS3Bucket' 'https://consiliumdata.blob.core.windows.net/container1' --recursive=true
	  The AzCopy tool can copy directly from an AWS S3 bucket to an Azure Storage Account
	  
	  Neither BlockBlobStorage nor FileStorage support read-access geo-redundant storage (RA-GRS)
	  StorageV2 does support read-access geo-redundant storage (RA-GRS) and is able to be converted
	  
	  You need to allow read access to the data inside container2, but only within a 14 day window. How do you accomplish this using the Azure Portal? 
	  Create a shared access signatures
	  A Shared Access Signature (SAS) allows you to have granular control over your storage account, including access to only certain services (i.e. Azure Blobs) and permitting only read, write, delete, list, add, or create access.
	  Create a stored access policy
	  A Stored Access Policy allows granular control over a single storage container using a Shared Access Signature (SAS).
	  
	  https://consiliumstore.blob.core.windows.net/container1/pic1.png
	  
	  Get-AzStorageAccountKey
	  The Get-AzStorageAccountKey cmdlet gets the access keys for an Azure Storage account.
	  
	  Order an Azure Databox via the Azure Portal
	  
	  This option would be the best, as Azure Data box supports Windows 2016 servers, and is secure and reliable
	  
	  Azure file shares can be used as persistent volumes for stateful containers
- Azure Active Directory
	- AZ-900
	  A single user can belong to a max of 500 AD tenants as member or guest
	  Synchronize your domain accounts with Azure Active Directory 
	  By using Azure Active Directory Connect, you can synchronize all your domain user identities with Azure AD. You can also configure password synchronization so that your users only have to remember a single password for all resources.. This is by far the easiest and most seamless method to ensure access and is known as hybrid identity. https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-hybrid-identity
	  An Azure AD tenant can have multiple subscriptions but an Azure subscription can only be associated with one Azure AD tenant
	  You can modify the Azure Active Directory (Azure AD) tenant to which an Azure subscription is associated to
	  If your subscription expires, you lose access to all the other resources associated with the subscription. However, the Azure AD directory remains in Azure. You can associate and manage the directory using a different Azure subscription https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory
	  You can use the same account to manage multiple subscriptions. You can create an additional subscription for your account in the Azure portal. You may want an additional subscription to avoid hitting subscription limits, to create separate environments for security, or to isolate data for compliance reasons
	  You can't merge two subscriptions into a single subscription. However, you can move some Azure resources from one subscription to another or you can also transfer ownership of a subscription and change the billing type for a subscription
	  An Azure customer can register and use multiple Azure subscriptions
	  A company can have multiple subscriptions and store resources in the different subscriptions. However, a resource can exist in one subscription only
	- AZ-104
	  Authentication
	  Self-service password reset is an optional feature in Azure Active Directory, which may not apply to any and all users in the organization
	   In order to reset their password, the user will have to verify their identity using a mobile phone, mobile app, office phone or email
	  Self-service password may not apply to those not in a specific Active Directory group. If the user is not in the group, they will not be able to reset their password
	  You do not need a conditional access policy to enable this setting. A conditional access policy will verify identity via mobile phone if certain conditions are in place, versus require MFA in device settings is always going to verify identity under all conditional always
	  az account set --subscription "Subscription2"
	  Within the Device Settings blade, you can set the maximum number of devices per user. If a user reaches this quota, they will not be able to join any more devices unless another one is removed
	  Get-AzContext
	  Set-AzContext -SubscriptionName
	  In Az PowerShell 3.7.0, Set-AzContext sets the tenant, subscription, and environment for cmdlets to use in the current session
	  Email addresses - only used for SSPR
	  Security questions - only used for SSPR
	  App passwords - Can be used as primary authentication method for legacy apps, but cannot be used for both MFA & SSPR
	  
	  Roles
	  Contributor role allows you to manage both virtual machines and virtual networks
	  Owner - Owner role  allows you to manage both virtual machines and virtual networks, however it is not a least privileged role
	  Virtual Machine Contributor -  Virtual Machine Contributor lets you manage virtual machines, but not access to them, and not the virtual network or storage account they're connected to
	  Virtual Machine Administrator Login -  View Virtual Machines in the portal and login as administrator
	  To assign a role to a user:
	  1. Sign in to the Azure portal with an account that's a global admin or privileged role admin for the directory.
	  2. Select Azure Active Directory, select Users, and then select a specific user from the list.
	  3. For the selected user, select Directory role, select Add role, and then pick the appropriate admin roles from the Directory roles list, such as Conditional access administrator.
	  4. Press Select to save

	  Devices
	  When you connect a Windows device with Azure AD using an Azure AD join, Azure AD adds the following security principals to the local administrators group on the device:
	  · The Azure AD global administrator role
	  · The Azure AD device administrator role
	  · The user performing the Azure AD join
	  By adding Azure AD roles to the local administrators group, you can update the users that can manage a device anytime in Azure AD without modifying anything on the device. Currently, you cannot assign groups to an administrator role. Azure AD also adds the Azure AD device administrator role to the local administrators group to support the principle of least privilege (PoLP). In addition to the global administrators, you can also enable users that have been only assigned the device administrator role to manage a device.
	  In the Azure portal, you can manage the device administrator role on the Devices page. To open the Devices page:
	  1. Sign in to your Azure portal as a global administrator.
	  2. Search for and select Azure Active Directory.
	  3. In the Manage section, click Devices.
	  4. On the Devices page, click Device settings.
	  To modify the device administrator role, configure Additional local administrators on Azure AD joined devices.
- Network
	- AZ-900
	  With Azure ExpressRoute, all inbound data transfer is free of charge
	  Data transfer between Azure services located within the same region is not charged
	  Inbound data traffic is free, but outbound data traffic is not
	  Data transfers between Azure services located in different Azure regions is charged, it is NOT free
	  If you copy data to Azure from your on-premises network over a VPN, you need to pay additional data transfer costs
	  To implement a solution that enables the client computers on your on-premises network to communicate to the Azure virtual machines, you need to configure a VPN (Virtual Private Network) to connect the on-premises network to the Azure virtual network.
	  The Azure VPN device is known as a Virtual Network Gateway. The virtual network gateway needs to be located in a dedicated subnet in the Azure virtual network. This dedicated subnet is known as a gateway subnet and must be named "GatewaySubnet"
	  A Local Network Gateway is an object in Azure that represents your on-premise VPN device. A Virtual Network Gateway is the VPN object at the Azure end of the VPN. A "connection" is what connects the Local Network Gateway and the Virtual Network Gateway to bring up the VPN
	  VPN tunnels over Microsoft peering can be terminated either using VPN gateway, or using an appropriate Network Virtual Appliance (NVA) available through Azure Marketplace. We choose to use NVA because it accomplishes our goal, but for a lesser cost than Azure VPN Gateway.
	- AZ-104
		- Virtual WAN
		  The Virtual WAN architecture is a hub and spoke architecture for branches and users. It enables global transit network architecture, where the cloud-hosted network 'hub' enables transitive connectivity between endpoints that may be distributed across different types of 'spokes'. All hubs are connected in full mesh in a Standard Virtual WAN making it easy for the user to use the Microsoft backbone for any-to-any (any spoke) connectivity. This satisfies the requirement to provide the quickest set up at the lowest cost.
		- VPN
		  VPN tunnels over Microsoft peering can be terminated either using VPN gateway, or using an appropriate Network Virtual Appliance (NVA) available through Azure Marketplace. We choose to use NVA because it accomplishes our goal, but for a lesser cost than Azure VPN Gateway
		  IPsec VPN tunnels are created between the Azure VPN gateway and the on-premises VPN device. In this case, we do not want to use a VPN gateway for the sake of minimizing cost
		  A route table is required to specify the next hop for traffic coming and going from the on-premises network
		  VNet-to-VNet connections allow communication between virtual networks in different regions and from different subscriptions. Reference: Configure a VNet-to-VNet VPN gateway connection by using the Azure portal
		  Clients using Windows can access directly peered VNets, but the VPN client must be downloaded again if any changes are made to VNet peering or the network topology. Non-Windows clients can access directly peered VNets. Access is not transitive and is limited to only directly peered VNets
		   Gateway Transit is a VNet Peering property that enables one virtual network to use the VPN gateway in the peered virtual network for cross-premises connectivity. However, in this question, client is connected using point-to-site VPN
		- ExpressRoute
		  ExpressRoute lets you extend your on-premises networks into the Microsoft cloud over a private connection facilitated by a connectivity provider. ExpressRoute connections do not go over the public Internet. An ExpressRoute Connection is a layer 3 connection between your on-premises network and Azure through a connectivity provider (e.g. Verizon).
		- Load Balancer
		  You have a standard load balancer that directs traffic from port 80 externally to three different virtual machines. You need to direct all incoming TCP traffic on port 5000 to port 22 internally for connecting to Linux VMs. What do you need in order to connect to the VM via SSH?
		  A Network Address Translation (NAT) Rule 
		  A Network Security Group (NSG) 
		- Routing
		  The user-defined route in the table will override the default route, causing traffic to be directed to nowhere (next hope type of none).
		  Virtual network peering is a non-transitive relationship between two virtual networks, so the connection is private and the appliance (located in VNet1) can pass traffic from VNet1 to VNet3 through VNet1
		- Troubleshooting
		  Network Performance Monitor helps you monitor network performance between various points in your network infrastructure. It also helps you monitor network connectivity to service and application endpoints and monitor the performance of Azure ExpressRoute
		  A Log Analytics workspace is a data repository for Azure Monitor log data. A pre-requisite in order to use Network Performance Monitor
		  => NPM now part of Network Watcher! 
		  IP flow verify tool in Azure Network Watcher. The IP Flow Verify tool checks if a packet is allowed or denied to or from a virtual machine. The information consists of direction, protocol, local IP, remote IP, local port, and a remote port. If the packet is denied by a security group, the name of the rule that denied the packet is returned
		  Connection Monitor in Azure Network Watcher
		  The connection monitor capability in Azure Network Watcher monitors communication at a regular interval and informs you of reachability, latency, and network topology changes between the VM and the endpoint. This is the best solution for our use case of monitoring traffic between the two VMs
		  The performance diagnostics tool helps you troubleshoot performance issues that can affect a Windows or Linux virtual machine (VM). Supported troubleshooting scenarios include quick checks on known issues and best practices, and complex problems that involve slow VM performance or high usage of CPU, disk space, or memory.
		  It Checks for known issues, analyzes best practices, and collects diagnostics data and captures a network trace and SMB counters
		  Connection troubleshoot -- Enable you to troubleshoot network performance and connectivity issues in Azure
		  NSG flow logs -- allows you to log information about IP traffic flowing through an NSG.
		- Peering
		   You can't add address ranges to, or delete address ranges from a virtual network's address space once a virtual network is peered with another virtual network.
		  To add or remove address ranges, delete the peering, add or remove the address ranges, then re-create the peering. 
- Network Security
	- AZ-900
	  Azure Network Security Groups (NSGs) can be applied at either the subnet level (part of a virtual network) or at the virtual machine level, on the network interface card (NIC) itself
	  If you want or need to protect your entire virtual network, then an Azure Firewall must be used. Azure Firewall is a managed, cloud-based network security service that protects your Azure Virtual Network resources.
	- AZ-104
		- NSG
		  Removing the NSG from the network interface would allow the VM to use the NSG associated with the subnet, which is best practice 
		  In order for you to associate a network security group to a subnet, both the virtual network and the network security group must be in the same region.
		- Firewall
		  FW configuration:
		  Configure an application rule on the Azure Firewall that blocks FQDNS www.microsoft.com.  application rule allows or blocks an address by URL 
		  In order to create an Azure Firewall, you must already have a subnet created named AzureFirewallSubnet, so this is no longer a requirement for this scenario
		  Create a route via Route Table to the firewall (as a virtual appliance hop)
		  A network rule would allow access to an external public DNS service, to lookup the microsoft.com domain name.
		- Bastion
		  A subnet named AzureBastionSubnet
		  The subnet inside your virtual network to which the Bastion resource will be deployed must have the name AzureBastionSubnet. The name lets Azure know which subnet to deploy the Bastion resource to. This is different than a Gateway Subnet
		  HTML5 supported Web Browser
		  The RDP connection to the virtual machine happens via Bastion host using the Azure portal (over HTML5) using port 443 and the Bastion service
		  Azure Bastion Host
		  The Azure Bastion service is a new fully platform-managed PaaS service that you provision inside your virtual network. It provides secure and seamless RDP/SSH connectivity to your virtual machines directly in the Azure portal over TLS. When you connect via Azure Bastion, your virtual machines do not need a public IP address
- Security Center
	- AZ-900
	  The Security Center blade from the Azure portal includes the ‘regulatory compliance dashboard’
	  The regulatory compliance dashboard provides insight into your compliance posture for a set of supported standards and regulations, based on continuous assessments of your Azure environment
	  In the Azure Security Center regulatory compliance blade, you can get an overview of key portions of your compliance posture with respect to a set of supported standards. Currently supported standards are Azure CIS, PCI DSS 3.2, ISO 27001, and SOC TSP
	- Just in time VM access
	  First of all, "Just-in-time" is a feature available in Azure Security Center. You can enable just-in-time feature so that access to your VMs is enabled for a specific period of time
	  By default, if the network security group allows the connection arriving at the VM, then the connection is allowed. So this is true at any given moment in time, every day. With "just-in-time", you can enable access to the VM only when it's needed, for example when a patching maintenance window needs to take place
	  Just-in-time capability reduces exposure to cyber security attacks while providing easy access when you need to connect to a VM
- Virtual Machines
	- AZ-104
	  Misc
	  A stopped (deallocated) VM is offline and not mounted on an Azure host server. Starting a VM mounts the VM on a host server before the VM starts. As soon as the VM is mounted, it becomes chargeable. For this reason, you are unable to start a VM after a trial has expired
	  After the VM has been created, go to the network interface attached to the VM and change the IP configuration to static assignment
	  The size of VM1 is currently Standard_D2s_v3. You don't have to shut down the VM in order to change the VM to certain sizes (some cases you do). In this case, you can change the VM size to B1ls, B1ms, B1s, B2ms, B2s, B4ms, D4s_v3, DS1_v2, DS2_v2, or DS3_v2 without shutting down VM1
	  Disks can be resized only when they are unattached or the owner VM is deallocated
	  Premium disk performance increases based on the size of the disk, while standard disks have consistent performance for all disk sizes. Disks can be resized only when they are unattached or the owner VM is deallocated
	  Azure will migrate VM1 from failing hardware to a healthy physical host and the VM will be paused for up to five seconds
	  Azure uses Live Migration technology to migrate Virtual Machines from the failing hardware to a healthy physical machine. Live Migration is a VM preserving operation that only pauses the Virtual Machine for a short time. Memory, open files, and network connections are maintained, but performance might be reduced before and/or after the event
	  Each virtual machine in your availability set is assigned a fault domain. For a given availability set, the underlying physical hardware can be rebooted at the same time
	  Nice work! The larger SKUs for Azure virtual machines allow for an increased number of NICs
	  After you create a virtual machine (VM), you can scale the VM up or down by changing the VM size. In some cases, you must deallocate the VM first. This can happen if the new size is not available on the hardware cluster that is currently hosting the VM. If the virtual machine is currently running, changing its size will cause it to be restarted
		- Virtual Networks
		  Microsoft does not support moving VM’s between virtual networks. So, we have delete the VM and create a new VM in target VNet.
		- Update vs Fault Domains
		  The hardware in a location is divided in to multiple update domains and fault domains. An update domain is a group of VMs and underlying physical hardware that can be rebooted at the same time. VMs in the same fault domain share common storage as well as a common power source and network switch.
		  Microsoft updates, which Microsoft refers to as planned maintenance events, sometimes require that VMs be rebooted to complete the update. To reduce the impact on VMs, the Azure fabric is divided into update domains to ensure that not all VMs are rebooted at the same time.
		- Custom Scripts
		  When you define a virtual machine scale set with an Azure template, the Microsoft.Compute/virtualMachineScaleSets resource provider can include a section on extensions. The extensionsProfile details what is applied to the VM instances in a scale set. To use the Custom Script Extension, you specify a publisher of Microsoft.Azure.Extensions and a type of CustomScript.
		  The Custom Script Extension downloads and executes scripts on Azure VMs.
	- [VM Sizes](https://docs.microsoft.com/en-us/azure/virtual-machines/sizes)
- Azure policy
	- AZ-900
	  Self-service password reset is an optional feature in Azure Active Directory, which may not apply to any and all users in the organization
	   In order to reset their password, the user will have to verify their identity using a mobile phone, mobile app, office phone or email
	  Self-service password may not apply to those not in a specific Active Directory group. If the user is not in the group, they will not be able to reset their password
	  You do not need a conditional access policy to enable this setting. A conditional access policy will verify identity via mobile phone if certain conditions are in place, versus require MFA in device settings is always going to verify identity under all conditional always
	  az account set --subscription "Subscription2"
	  Within the Device Settings blade, you can set the maximum number of devices per user. If a user reaches this quota, they will not be able to join any more devices unless another one is removed
	  Get-AzContext
	  Set-AzContext -SubscriptionName
	  In Az PowerShell 3.7.0, Set-AzContext sets the tenant, subscription, and environment for cmdlets to use in the current session
- App Service
	- AZ-104
	  The app must be running in the Standard, Premium, or Isolated tier in order for you to enable multiple deployment slots
	  The VNet Integration feature enables your apps to access resources in or through a VNet. The VNet Integration feature has two variations:
	  Regional VNet Integration: When you connect to Azure Resource Manager virtual networks in the same region, you must have a dedicated subnet in the VNet you're integrating with
	  Gateway-required VNet Integration: When you connect to VNet in other regions or to a classic virtual network in the same region, you need an Azure Virtual Network gateway provisioned in the target VNet.
	  https://docs.microsoft.com/en-us/azure/app-service/web-sites-integrate-with-vnet
	  Web server logging - Raw HTTP request data in the W3C extended log file format. Each log message includes data such as the HTTP method, resource URI, client IP, client port, user agent, response code, and so on.
	- [Plan Details](https://azure.microsoft.com/en-us/pricing/details/app-service/windows/)
- Containers
	- AZ-104
	  Azure Container Instances can mount an Azure file share created with Azure Files. Azure Files offers fully managed file shares hosted in Azure Storage that are accessible via Server Message Block (SMB) protocol. Using an Azure file share with Azure Container Instances provides file-sharing features similar to using an Azure file share with Azure virtual machines
	  az aks create -g RG1 -n AKS1 --generate-ssh-keys --node-count 3
	  The correct command to use for creating an AKS cluster is az aks create and the -g and -n values are abbreviated syntax for resource group and name respectively. The --generate-ssh-keys flag will create the SSH keys in order to access the worker nodes. The --node-count flag will ensure that there are three worker nodes in the cluster
	  Retrieve the access credentials using the command az aks get-credentials --name AKS1 --resource-group RG1
	  The kubeconfig is required in order to access the Kubernetes API. You can retrieve the kubeconfig using the az aks get-credentials command
	  Run the az acr build command 
	  The az acr build command will build and push your image to an Azure Container Registry all in one command. You should use this if you don't have docker installed, and/or if you don't have the compute resources to build images on your local machine
	  To install kubectl locally, use the az aks install-cli command
	  The following example uses the kubectl autoscale command to autoscale the number of pods in the azure-vote-front deployment. If average CPU utilization across all pods exceeds 50% of their requested usage, the autoscaler increases the pods up to a maximum of 10 instances. A minimum of 3 instances is then defined for the deployment: kubectl autoscale deployment azure-vote-front --cpu-percent=50 --min=3 --max=10
	  Use the az aks update command to enable and configure the cluster autoscaler on the node pool for the existing cluster
- Backup
	- AZ-104
	  Misc
	  Turn off soft delete in the vault security settings When you stop the backup and delete the backup data, because you have soft delete enabled, the backup data is still kept. Permanently delete the soft-deleted backup items that would remove the backup data indefinitely
	  Stop the backup of VM1 and delete backup data
	  If you stop the backup of VM1 and choose delete backup data from the dropdown menu, this will stop future backups and delete the existing backup data
	  
	  Backup Policy
	  A backup policy is used to configure how backups are taken and how often they are kept
	  A Recovery Services Vault
	  A recovery services vault (RSV) is used to store backups of your VMs in a different region
	  Disable soft-delete
	  Soft-delete is a feature that is turned on by default and protects against accidental deletion. Disabling this feature allows you to delete backup data immediately when you stop the backup.
	  To create a vault to protect any data source, the vault must be in the same region as the data source. Storage account must be in the same region as your Recovery Service Vault
	  There are three application tiers, each with five virtual machines.
	  Move all the virtual machines for App1 to Azure.
	  Ensure that all the virtual machines for App1 are protected by backups.
	  A Recovery Services vault is a storage entity in Azure that houses data. The data is typically copies of data, or configuration information for virtual machines (VMs), workloads, servers, or workstations. You can use Recovery Services vaults to hold backup data for various Azure services such as IaaS VMs (Linux or Windows) and Azure SQL databases
	  When you create an Azure Backup for virtual machines, you need to either create a Recovery services vault or select an existing Recovery services vault.
	  
	  Recovery Services Vault
	  You can't delete a Recovery Services vault with any of the following dependencies:
	  · You can't delete a vault that contains protected data sources (for example, IaaS VMs, SQL databases, Azure file shares).
	  · You can't delete a vault that contains backup data. Once backup data is deleted, it will go into the soft deleted state.
	  · You can't delete a vault that contains backup data in the soft deleted state.
	  · You can't delete a vault that has registered storage accounts
- Monitoring
	- AZ-104
	  Windows Server 2016. You need to collect OS level metrics on this virtual machine, including Windows event logs and performance counters:
	  Windows Diagnostics Extension
	  Windows Diagnostic Extension is an agent in Azure Monitor that collects monitoring data from the guest operating system and workloads of Azure virtual machines and other compute resources
	  Storage Account for Diagnostic Data
	  In order to enable guest-level monitoring, you need to create a storage account for storing the metrics data
	  Enable guest-level monitoring
	  In order to install the diagnostics extension on an Azure VM, you must enable guest-level monitoring from the VM settings in the portal
	  You have one Azure virtual machine located within Subscription1 and another Azure virtual machine within Subscription2 and you'd like to view CPU utilization metrics on both virtual machines:
	  Create a Log Analytics Workspace for both VMs
	  You can view metrics data (such as CPU utilization %) over time by sending your metrics data to a log analytics workspace. This workspace can collect metrics data from multiple VMs, no matter if they are located in the same or different subscriptions
	  Turn on VM Insights in Azure Monitor
	  VM integration with Azure Monitor Logs delivers powerful aggregation and filtering, allowing Azure Monitor for VMs to analyze data trends over time. You can view this data in a single VM from the virtual machine directly, or you can use Azure Monitor to deliver an aggregated view of your VMs where the view supports Azure resource-context or workspace-context modes
	  No need to Install the Log Analytics (OMS) Agent on the VMs
	  No agents are required in order to collect CPU metric data on an Azure VM. Installing agents would not meet the requirement of minimizing the number of Azure resources at the lowest cost
	  Monitor > Alerts > New Alert Rule
	  Alerts can be created from within Azure Monitor
	  
	  Live Metrics Stream in Application Insights
	  Live metrics stream includes such information as the number of incoming requests, the duration of those requests, and any failures that occur. You can also inspect critical performance metrics such as processor and memory.
	  
	  Create a new action group
	  An action group is a collection of notification preferences defined by the owner of an Azure subscription. Azure Monitor and Service Health alerts use action groups to notify users that an alert has been triggered.
	  Create a new alert rule
	  Alert rules specify the conditions for which the alert is triggered. Activity log alerts are the alerts that get activated when a new activity log event occurs that matches the conditions specified in the alert.
	  
		- Log Analytics Workspace
		  The location and subscription where this Log Analytics workspace can be created is independent of the location and subscription where your vaults exist.
- Data Encryption
	- AZ-104
	  Azure Disk Encryption
	  Azure Disk Encryption for Windows VMs is integrated with Azure Key Vault to provide disk encryption and encryption keys and secrets to access your data
	  Azure Key Vault
	  Azure Key Vault provides the keys necessary to access your encrypted disks
	  bdehdcfg component
	  Windows Server 2012 R2 Core and Windows Server 2016 Core requires the bdehdcfg component to be installed on the VM for encryption
	  No need Bitlocker
	  The Bitlocker feature is included with Windows providing volume-level encryption for the OS and the data disks. Since this is a built-in feature, we won't need to procure it
- Load Balancer
	- AZ-104
	  Port forwarding lets you connect to virtual machines (VMs) in an Azure virtual network by using an Azure Load Balancer public IP address and port number. To set up port forwarding on an Azure Load Balancer, you must create inbound NAT port-forwarding rules
	  A frontend IP configuration – Frontend IP configuration allows you to configure a public IP address for the load balancer
	  A load balancing rule - A load balancer rule is used to define how incoming traffic is distributed to the all the instances within the backend pool
	  The load balancer is of type Microsoft.Network/loadBalancers. The network contributor role allows you to manage networks. A network contributor can create and managed networks (Microsoft.Network/*). Therefore, adding Admin1 as Network Contributor on resource group will suffice the requirement
