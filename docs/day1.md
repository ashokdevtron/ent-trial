# Day 1: Explore Your Cluster

**Objective:** Gain visibility into your existing Kubernetes workloads and familiarize yourself with Devtron's interface.

**Why this matters:** A strong foundation starts with understanding what you already have. By connecting your existing cluster, you gain visibility into all active workloads and unlock powerful management features.

**What you'll do:**

1. **Connect Your Cluster**  
   - Navigate to the "Cluster" section in Devtron.
   - Follow the guided steps to link your Kubernetes cluster using the kubeconfig file or access token.
   - Once connected, the dashboard will populate with your current workloads.

2. **View Deployed Applications**  
   - Go to the "Applications" tab.
   - See your existing Helm, Argo CD, or FluxCD deployments.
   - This provides immediate operational insight into running services.

3. **Explore Resource States**  
   - Use the "Resource Browser" to drill down into namespaces, pods, services, and workloads.
   - Identify issues such as pending pods or unhealthy workloads directly from the UI.

4. **Deploy a Helm Chart**  
   - Navigate to "Chart Store" and select a commonly used chart (like NGINX or Redis).
   - Use default or custom values and deploy it into a namespace.
   - Watch the deployment status live and validate success via the application dashboard.

**Outcome:** By the end of Day 1, you'll have a fully connected cluster with at least one chart deployed, along with a clear picture of your environment’s current state.
