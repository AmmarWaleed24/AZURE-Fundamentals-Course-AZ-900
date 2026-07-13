# ☁️ Domain 1: Describe Cloud Concepts

This section documents my learning path, core notes, and conceptual summaries for the first domain of the Microsoft Azure Fundamentals (AZ-900) syllabus. 

---

## 🧭 Module Breakdown & Status

| Unit | Lesson Topic | Status |
| :--- | :--- | :---: |
| 1.1 | Introduction to Cloud Computing | ✅ Completed |
| 1.2 | What is Cloud Computing? | ✅ Completed |
| 1.3 | Describe the Shared Responsibility Model | ✅ Completed |
| 1.4 | Define Cloud Models | ✅ Completed |
| 1.5 | Describe the Consumption-Based Model | ✅ Completed |

---

## 📚 Detailed Lesson Notes

### 📋 1.1 Introduction to Cloud Computing
*   **Module Purpose**: Introduces general cloud concepts, core architectural models, and pricing methods.
*   **Target Audience**: Designed as an foundational review for understanding how modern cloud infrastructure operates.

### 🌐 1.2 What is Cloud Computing?
*   **Core Definition**: The delivery of computing services over the internet.
*   **Traditional IT Infrastructure Included**: Virtual machines, storage, databases, and networking.
*   **Expanded Modern Offerings**: Internet of Things (IoT), machine learning (ML), and artificial intelligence (AI).
*   **Key Advantages**:
    *   **No Physical Constraints**: You aren't limited by physical infrastructure boundaries.
    *   **Rapid Expansion**: You can instantly expand your IT footprint on demand instead of waiting to buy physical hardware.
    *   **Global Reach**: Allows applications to be placed physically closer to users and designed for regional resilience.
*   **Scenario Example**: A retail app experiencing a seasonal product launch can scale compute capacity out instantly to handle the traffic surge, then scale back down to optimize costs once the launch finishes.

### 🔄 1.3 Describe the Shared Responsibility Model
*   **On-Premises vs. Cloud**: On-premises requires you to own everything (physical space, hardware, patching). In the cloud, responsibilities are cleanly divided between you and the cloud provider.
*   **Provider’s Responsibility**: Physical security, power, cooling, and underlying network connectivity of the datacenters.
*   **Consumer’s Responsibility**: Data, information, device security, and user accounts/identities.
*   **Service Model Impact**:
    *   *IaaS (Infrastructure as a Service)*: Places the highest responsibility on the consumer (you manage the OS and software stacks).
    *   *PaaS (Platform as a Service)*: Evenly distributed. The provider manages the OS and backend database infrastructure; you manage applications and data.
    *   *SaaS (Software as a Service)*: Places maximum responsibility on the provider, as they host the entire end-user application (e.g., Microsoft 365).

### ☁️ 1.4 Define Cloud Models
*   **Public Cloud**: Built, controlled, and maintained entirely by a third-party cloud provider (like Microsoft Azure). Features zero capital expenditures (CapEx) to scale and a pay-for-what-you-use structure.
*   **Private Cloud**: An environment dedicated and used exclusively by a single entity. Can be hosted from an on-site datacenter or an offsite dedicated third-party facility.
*   **Hybrid Cloud**: An interconnected environment combining both public and private clouds, allowing private infrastructure to "surge" into public resources during high-demand spikes.
*   **Multicloud**: A deployment strategy where an organization utilizes multiple public cloud providers simultaneously to tap into unique features or manage migrations.
*   **Azure Hybrid Enablers**:
    *   *Azure Arc*: A unified management framework designed to govern your entire estate across public, private, hybrid, or multicloud environments.
    *   *Azure VMware Solution*: A pathway that lets businesses run VMware workloads natively inside Azure without refactoring infrastructure.

### 💰 1.5 Describe the Consumption-Based Model
*   **Financial Foundations**:
    *   *Capital Expenditure (CapEx)*: Up-front spending on physical infrastructure (servers, datacenters).
    *   *Operational Expenditure (OpEx)*: Ongoing spending on services over time. Cloud computing is classified entirely as an **operational expense (OpEx)**.
*   **Key Benefits**:
    *   Zero upfront costs.
    *   Eliminates infrastructure waste from idle resources.
    *   Dynamic scaling (instantly add resources when user demand increases, and release them when demand drops).
*   **Capacity Planning Comparison**:
    *   *Traditional*: Requires estimating future needs. Overestimating wastes money; underestimating causes application degradation and slow hardware procurement cycles.
    *   *Cloud*: Elastic capacity continuously adjusts to match live demand, allowing you to pay *only* for the exact services you consume.

---

## 🛠️ Tracked Learning Resources

*   [Microsoft Learn](https://learn.microsoft.com/): Official step-by-step documentation, learning paths, and interactive sandbox configurations.
*   [Manara](https://manara.com/): Community cohort guidelines, structured tech tracking, and professional development training tools.
