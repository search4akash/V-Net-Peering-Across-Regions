                                                                **Project Title**
                                                               Implement Azure IaaS
                                                                Business Scenario 
OSS Corporation is a globally distributed firm. They have their headquarters in the East US with another branch office in the WEST US. Currently, they are working on a project and decided that the application tier of this project will reside in one of its branch regions. For security reasons, OSS Corporation management is adamant on keeping their data tier in the headquarter region.

 As an organization, they are open to suggestions and are currently evaluating Azure as a deployment platform. To prepare for the deployment of IaaS Standard_B1ms, OSS Corporation must deploy an IaaS v2 virtual network in the headquarters region for its database. But for the application, it should create another IaaS v2 virtual network in the branch region. In addition, because the communication between App and data should happen over a private channel, one needs to prepare their branch office virtual network for establishing connectivity to the headquarters' IaaS v2 virtual network by creating a virtual network gateway and deploy a test IaaS Standard_B1ms VM to the virtual networks for verifying the connections. Also they wanted to make sure that they get those alerts on their Action Groups for budgets on their resource group. After the deployment team ensures the connectivity between both the networks, you can validate the same using ping.


Resources used for Deployment:
1. Azure Virtual Networks
2. Azure Virtual Machines
3. Azure Network Security Groups
4. Azure Network Interface Card
5. Azure Action Groups

