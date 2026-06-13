# Vayne-Environmental-Partners
Vayne Environmental Partners(VEP): A fictitious environmental engineering consulting firm that creates and consults on various environmental projects and builds. They provide consulting services from Electrical engineering projects to plumbing, mining and water resource projects.
Virtual networks:
VEPCorp: 10.1.0.0/16
I created a “VEPCorp” virtual corporate network network that will house the azure resources for the whole corporate enterprise

ElectricalEngineeringDept: 10.2.0.0/16
I created an electrical engineering virtual network spoke that will house the azure resources for the electrical engineering department

PlumbingEngineeringDept: 10.3.0.0/16
I also created the “Plumbing engineering” virtual network that will house the azure resources for the plumbing engineer department. 

ProjectManagementDept: 10.4.0.0/16
I created the “project management” virtual network that will house the azure resources for the project management department. 

Virtual Network Peering: 
I set up a virtual network peering from “VEP Corp” network to the “Electrical engineering” department. Azure resources on the Corporate network will need to be accessed by other Azure resources on the “VEPCorp” network. 

I set up a virtual network peering from “VEP Corp” network to the “Plumbing engineering” department. Azure resources on the Corporate network will need to be accessed by other Azure resources on the “VEPCorp” network. 

I set up a virtual network peering from “VEP Corp” network to the “Project management” department. Azure resources on the Corporate network will need to be accessed by other Azure resources on the “VEPCorp” network. 

I set up a virtual network peering from the “Project management” network to the “Electrical engineering” department to access Azure resources there for project management purposes.

I set up a virtual network peering from the “Project management” network to the “Plumbing engineering” department to access Azure resources there for project management purposes.
