# Cross-Region VNet Peering in Azure: A Step-by-Step Guide 
-----  
## "Introduction"

In this project, I tried to explore how to set up cross-region V-Net peering in Microsoft Azure. 
VNet peering allows usres to connect virtual networks across different Azure regions securely. We’ll cover the necessary steps and provide an architectural diagram to illustrate the setup.
Here is the Architectural Diagram:
![Peering Latest](https://github.com/user-attachments/assets/33a2c207-fc0d-452b-bcf8-4279da3cbe99

### Prerequisites
Before we begin, ensure you have the following:
**Azure Subscription**: You’ll need an active Azure subscription.
**Two VNets**: Create two virtual networks (VNets) in different Azure regions. These VNets will be peered.
**Network Security Groups (NSGs)**: If you want to control traffic between VNets, configure NSGs accordingly.
_Action Group_: This is optional either you can ignore it or set this to get Azure App/ E-mail notificatons

**Step 1**: Create VNets
            Log in to the Azure Portal.
            Navigate to Virtual networks and create two VNets (one in each region).
            Note down the VNet names and their respective address spaces.

**Step 2**: Configure Peering
            In the Azure portal, go to the settings of the first VNet.
            Under Settings, select Peerings.
            Click Add to create a new peering.
            Specify the second VNet’s details (name, resource group, etc.).
            Repeat the process for the second VNet, peering it with the first one.
           
**Step 3**: Verify Connectivity
            In each VNet, create a test VM.
            Ping the VMs across VNets to verify connectivity.

### *Conclusion*
Cross-region VNet peering enables seamless communication between VNets across different Azure regions. Remember to follow best practices for security and governance.

Feel free to customize this README with additional details, troubleshooting tips, or any other relevant information. Happy coding! 🚀

