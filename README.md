## Azure Setup Hierarchy
```
Microsoft Account
└── Azure Subscription
    └── Azure Active Directory (AAD)
        └── Resource Groups (RG)
            ├── Virtual Network (VNet)
            │   └── Subnets
            └── Virtual Machines (VMs)
                ├── DC-1 (Domain Controller)
                └── Client-1
```

## 1. Microsoft Account & Azure Subscription
- Create a **Microsoft Account**.
- Sign up for an **Azure Subscription** (Free/Paid, requires a credit card).
- Azure automatically creates an **Azure Active Directory (AAD) Tenant**.

## 2. Azure Active Directory (AAD) & RBAC
- **AAD Tenant** manages identity and access.
- Assign **Users & Roles** (Owner, Contributor, Reader).
- Link **Subscription** to the AAD Tenant.

## 3. Resource Group (RG) Setup
- Create a **Resource Group (RG)** to organize resources.
- Recommended: Separate RGs for different environments (Test, Production).

## 4. Virtual Network (VNet) & Subnet Configuration
- Create a **Virtual Network (VNet)** for communication.
- Define **Subnets** for logical segmentation (e.g., Domain Controllers, Clients 
