# ☁️ Microsoft Azure Fundamentals (AZ-900) Mastery

Welcome to my AZ-900 certification journey! This repository serves as a centralized hub for my study notes, hands-on labs, and conceptual breakdowns of the Microsoft Azure ecosystem.

---

## 🗺️ Learning Roadmap & Progress

| Module / Domain Area | Weight | Status | Target Date |
| :--- | :---: | :---: | :---: |
| **01. Introduction & Environment Setup** | — | Completed | `YYYY-MM-DD` |
| **02. Describe Cloud Concepts** | 25-30% | Completed | `YYYY-MM-DD` |
| **03. Describe Azure Architecture & Services** | 35-40% | In Progress | `YYYY-MM-DD` |
| **04. Describe Azure Management & Governance** | 30-35% | Pending | `YYYY-MM-DD` |

---

## 📚 Detailed Course Modules

### 📂 01. Introduction to the LP
Getting started with the Azure Learning Path and setting up the environment.
*   [x] **Environment Setup**: Created a tenant and activated a Microsoft 365 Developer Sandbox for risk-free sandbox practice.
*   [x] **Goal Mapping**: Aligned study schedules with the latest official exam syllabus.

---

### 📂 02. Introduction to Cloud Concepts (25-30%)
*Focus: Understanding the foundational principles of Cloud Computing.*

#### 📝 Lessons & Key Concepts Covered:
*   **Cloud Computing Basics**: Definition, advantages, and the **Shared Responsibility Model** (shifting operational responsibilities from on-premises to cloud providers).
*   **Cloud Models**: 
    *   *Public Cloud*: Shared infrastructure owned by a third party.
    *   *Private Cloud*: Dedicated infrastructure solely used by one organization.
    *   *Hybrid Cloud*: Combines on-premises infrastructure/private cloud with public cloud resources.
*   **Cloud Service Types**:
    *   *IaaS (Infrastructure as a Service)*: Managing OS, middleware, and data while Azure handles hardware (e.g., Virtual Machines).
    *   *PaaS (Platform as a Service)*: Managing applications and data; Azure manages OS and server maintenance (e.g., App Services).
    *   *SaaS (Software as a Service)*: End-user applications fully managed by the cloud vendor (e.g., Microsoft 365).
*   **Cloud Benefits**: **High Availability** (minimal downtime), **Scalability** (Vertical/Horizontal adjustment), **Elasticity** (auto-scaling on demand), **Agility** (rapid deployment), and **Fault Tolerance** (disaster recovery resilience).
*   **Financial Models**: Capital Expenditure (**CapEx**) vs. Operational Expenditure (**OpEx**), moving from upfront costs to a consumption-based spending structure.

*Current Progress:* ██████████ 100% 🎯

---

### 📂 03. Azure Core Services (35-40%)
*Focus: Exploring the foundational architectural components and main services that build up Azure.*

#### 📝 Lessons & Key Concepts Covered:
*   **Azure Core Architecture**: 
    *   Geographies, Regions, and **Availability Zones** (physically separate datacenters within an Azure region protecting from datacenter failures).
    *   Resource Hierarchies: Management Groups ➡️ Subscriptions ➡️ Resource Groups ➡️ Resources.
*   **Compute Services**:
    *   Azure Virtual Machines (VMs), Azure Virtual Desktop, and Container instances (Azure Container Instances, Azure Kubernetes Service).
    *   Serverless computing basics: **Azure Functions** and Logic Apps.
*   **Networking Services**:
    *   Azure Virtual Networks (**VNets**), Subnets, and Public/Private IPs.
    *   Connectivity options: VPN Gateway, **ExpressRoute** (dedicated private connection bypassing the public internet), and Azure Peering.
*   **Storage Services**:
    *   Azure Blob Storage (unstructured data), Azure Files (managed file shares), and Azure Disk Storage.
    *   Storage tiers: Hot, Cool, Cold, and Archive.
*   **Database Services**:
    *   Azure SQL Database, Azure Cosmos DB (NoSQL), and open-source alternatives like Azure Database for MySQL/PostgreSQL.

*Current Progress:* ██████░░░░ 60% ⚙️

---

### 📂 04. Azure Management and Governance (30-35%)
*Focus: Controlling costs, governing infrastructure resources, and choosing appropriate management tools.*

#### 📝 Lessons & Key Concepts Covered:
*   **Cost Management & Predictability**:
    *   Factors affecting costs (Resource type, consumption, location, bandwidth).
    *   Utilizing the Pricing Calculator and **Total Cost of Ownership (TCO) Calculator**.
    *   Setting up Azure Cost Management + Billing, budgets, and cost alerts.
*   **Governance and Compliance**:
    *   Role-Based Access Control (**RBAC**) for securing administrative boundaries.
    *   **Azure Policy** (enforcing organizational rules and standards) and Azure Blueprints.
    *   Resource Locks (Preventing accidental deletion or modification).
*   **Management & Deployment Tools**:
    *   Interacting with Azure: Azure Portal, Azure CLI, Azure PowerShell, and the Azure Mobile App.
    *   Infrastructure as Code (IaC): **ARM Templates** (Azure Resource Manager) and Bicep.
*   **Monitoring Tools**:
    *   **Azure Monitor**: Collecting metrics, logs, and setting up alerts.
    *   **Azure Service Health**: Keeping track of global cloud outages or planned maintenance.

*Current Progress:* ░░░░░░░░░░ 0% 💰

---

## 🛠️ Practice Environment & Troubleshooting Log

I utilize a free independent sandbox directory to practice administrative concepts securely without credit card limitations:
*   **Tenant Administration**: Managed via a personal Global Admin account on a custom domain/tenant.
*   **Identity Management**: Testing user provisioning, custom roles, and groups inside Microsoft Entra ID.

### 🔍 Troubleshooting Highlight:
*   **Issue**: Encountered `AADSTS16000` (Interaction Required) and `403 No Access` error when signing in to the Azure Portal using an external personal account.
*   **Resolution**: Resolved by isolating the login session via an *Incognito Window* and using the dedicated tenant credentials generated from the sandbox program rather than mixing profiles.

---

## 🔗 Learning Resources

To successfully pass the exam, my learning flow heavily relies on these foundational learning tracks:
1.  **[Microsoft Learn](https://learn.microsoft.com/)**: Followed the official, step-by-step [Azure Fundamentals Learning Path](https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/) to review documentation, interactive text blocks, and complete embedded module knowledge checks.
2.  **[Manara](https://manara.com/)**: Utilized community guidelines, specialized structured cohorts, and tailored tech training resources to solidify technical execution and keep track of modern cloud engineering milestones.
