# Day 9: Cluster & Access Management

**Objective:** Set up multi-cluster access and manage permissions with fine-grained RBAC.

**Why this matters:** Security and scalability hinge on proper access control and multi-cluster setups.

**What you'll do:**

1. **Add a New Cluster**  
   - Navigate to the "Cluster" management section.
   - Add a second Kubernetes cluster for multi-environment workflows.

2. **Configure SSO with RBAC**  
   - Enable Single Sign-On (SSO) using OAuth or SAML.
   - Assign roles based on user groups (e.g., dev, ops).

3. **Enable Kubectl Access**  
   - Grant temporary in-browser `kubectl` access to team members via role-based permissions.

**Outcome:** Your workspace now supports controlled, multi-cluster operations with auditable team access.