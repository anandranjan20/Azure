# Azure Resources, Resource Groups, and Azure Resource Manager (ARM)

## Azure Resources
Azure resources are the building blocks of your cloud infrastructure. These can be virtual machines, databases, storage accounts, or any other service offered by Azure. Each resource is a manageable item and can be provisioned and managed individually.

**Examples:** Virtual Machine, Storage Account, SQL Database

---

## Resource Groups
A **Resource Group** is a logical container for resources that share the same lifecycle, permissions, and policies. It helps organize and manage related resources efficiently.

### Key Points:
- **Lifecycle Management:** Deploy, update, or delete resources together.  
- **Organization:** Group resources by project, environment, or application.  
- **Role-Based Access Control (RBAC):** Assign permissions at the group level to manage access.  

---

## Azure Resource Manager (ARM)
**Azure Resource Manager (ARM)** is the deployment and management service for Azure. It provides a consistent layer to deploy, update, and manage resources using declarative templates.

### Key Features:
- **Template-Based Deployment:** Use JSON templates to define resources and configurations for repeatable deployments.  
- **Dependency Management:** Automatically handles dependencies and deploys resources in the correct order.  
- **Rollback & Roll-forward:** Maintain a desired state by rolling back failed deployments or rolling forward to the last good state.  
- **Tagging & Categorization:** Label and organize resources with tags for better management.  

---

**Summary:**  
- **Resource:** Individual Azure service/component.  
- **Resource Group:** Container for related resources with shared policies.  
- **ARM:** Deployment and management service for consistent and automated resource control.
