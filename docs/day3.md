# Day 3: Configuration & Rollback

**Objective:** Learn to manage configuration changes and perform rollbacks.

**Why this matters:** Being able to modify an app safely and recover from mistakes quickly is critical in production environments.

**What you'll do:**

1. **Update a ConfigMap**  
   - Modify a key-value pair in the application’s ConfigMap.
   - Observe how the new value is picked up in the diff view.

2. **Preview Before Deployment**  
   - Use the deployment diff feature to compare old and new configurations.
   - Ensure the changes are correct before going live.

3. **Trigger Deployment**  
   - Execute the new deployment with updated configurations.

4. **Perform a Rollback**  
   - Navigate to deployment history.
   - Select a previous successful version and roll back instantly.

**Outcome:** You’ll confidently make changes and understand how to revert if anything breaks.

