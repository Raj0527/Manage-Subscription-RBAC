# Manage-Subscription-RBAC
# Azure Role-Based Access Control (RBAC) Management 

This demo project showcases how to manage Azure subscriptions using RBAC and custom roles in Azure. It covers:

- Implementing management groups
- Assigning built-in roles
- Creating custom RBAC roles
- Monitoring role assignments using the Azure Activity Log

## Breakdown

# Task 1: Implement Management Groups
- Action: Created a management group named `az104-mg143927074`.
- Purpose: To organize subscriptions and simplify role-based access.
  
# Task 2: Assign a Built-in Role
- Action: Assigned the `Virtual Machine Contributor` role to the Help Desk group.
- Purpose: This role allows help desk users to manage virtual machines but prevents them from accessing the operating system or networking settings.

# Task 3: Create a Custom RBAC Role
- Action: Created a custom role called `Custom Support Request43927074` to allow Help Desk to create support requests without registering providers.
- JSON Configuration: [custom-rbac-role.json](scripts/custom-rbac-role.json)

# Task 4: Monitor Role Assignments
- Action: Reviewed the Azure Activity Log to track changes and role assignments.

Architecture Diagram
RBACSubscription.png

