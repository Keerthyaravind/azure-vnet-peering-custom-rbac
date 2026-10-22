# Azure VNet Peering and Custom RBAC

## Project Overview

This project demonstrates the implementation of Azure networking, identity management, and role-based access control.

The project was completed as part of my Microsoft Azure Administrator (AZ-104) practical training.

The main objective was to create two Azure Virtual Networks, establish connectivity using VNet Peering, deploy test Virtual Machines, onboard a user in Microsoft Entra ID, and provide controlled access using a Custom RBAC role.

## Objectives

- Create two Azure Virtual Networks (VNets)
- Deploy test Virtual Machines
- Establish connectivity using VNet Peering
- Test communication between the Virtual Machines
- Onboard a user in Microsoft Entra ID
- Create a Custom RBAC role
- Apply the principle of least privilege
- Verify that the user has only the required permissions

## Technologies and Tools Used

- Microsoft Azure
- Azure Virtual Network (VNet)
- Azure Virtual Machines
- VNet Peering
- Network Security Groups (NSG)
- Microsoft Entra ID
- Azure Role-Based Access Control (RBAC)
- Azure Portal

## Key Features and Functionalities

### Virtual Network Configuration
Created two separate Azure Virtual Networks with different IP address spaces.

### Virtual Machine Deployment
Deployed test Virtual Machines within the VNets to test network connectivity.

### VNet Peering
Configured VNet Peering to enable private communication between resources in the two Virtual Networks.

### Network Security
Configured the required Network Security Group rules to control network traffic.

### Microsoft Entra ID User
Created/onboarded a test user in Microsoft Entra ID for access-control testing.

### Custom RBAC
Created a custom Computer Operator role that allowed the user to:

- Read Virtual Machine information
- Read network information
- Read storage information
- Start Virtual Machines
- Restart Virtual Machines

The permissions were restricted according to the principle of least privilege.

## My Role and Contributions

I completed the Azure configuration and testing for this project.

My responsibilities included:

- Creating the Virtual Networks
- Configuring address spaces and subnets
- Deploying the Virtual Machines
- Configuring VNet Peering
- Configuring the required network security rules
- Testing connectivity between the Virtual Machines
- Onboarding a user in Microsoft Entra ID
- Creating and assigning the Custom RBAC role
- Testing the user's permissions
- Documenting the project

## Implementation Steps

1. Created two Virtual Networks in Microsoft Azure.
2. Configured the required IP address spaces and subnets.
3. Deployed test Virtual Machines in the VNets.
4. Configured Network Security Group rules.
5. Established VNet Peering between the two networks.
6. Tested connectivity between the Virtual Machines.
7. Created/onboarded a test user in Microsoft Entra ID.
8. Created a Custom RBAC Computer Operator role.
9. Assigned the role to the test user.
10. Verified that the user could perform only the permitted actions.

## How to Use / Reproduce the Project

To reproduce this project:

1. Sign in to the Microsoft Azure Portal.
2. Create two Virtual Networks with non-overlapping IP address ranges.
3. Create subnets within each VNet.
4. Deploy a Virtual Machine into each network.
5. Configure the required Network Security Group rules.
6. Configure VNet Peering between both VNets.
7. Test connectivity between the Virtual Machines.
8. Create a test user in Microsoft Entra ID.
9. Create a Custom RBAC role with the required permissions.
10. Assign the role to the test user.
11. Verify the user's access and permissions.

## Project Outcome

The project successfully demonstrated connectivity between resources across Azure Virtual Networks using VNet Peering.

It also demonstrated secure identity and access management using Microsoft Entra ID and Custom Azure RBAC while following the principle of least privilege.

## Key Learnings

This project helped me gain practical experience with:

- Azure Virtual Networking
- VNet Peering
- Virtual Machines
- Network Security Groups
- Microsoft Entra ID
- Azure RBAC
- Custom role creation
- Identity and Access Management
- Least-privilege security
- Azure connectivity testing
