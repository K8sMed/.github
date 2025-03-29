   # K8sMed - Kubernetes Medical Kit

   <p align="center">
  <img src="https://github.com/K8sMed/K8sMed/blob/608ffb0a48b27fb4dfad4996d592d50d3bdaa360/docs/assets/images/logo.png" alt="K8sMed Logo" width="200"/>
</p>
   
## About Us

   K8sMed provides diagnostic, troubleshooting, and management tools for Kubernetes environments. Just as medical professionals use specialized tools to diagnose and treat patients, our tools help you diagnose and resolve issues in your Kubernetes clusters.

   ## Our Mission

   To simplify Kubernetes operations by providing secure, robust, and user-friendly tooling that follows best practices. We build utilities that make cluster management more accessible to operators of all skill levels while maintaining the highest security standards.

   ## Featured Projects

   ### K8sToolbox

   Our flagship project is a comprehensive toolkit for Kubernetes cluster diagnostics and management:

   - **Health Checks**: Automated pod, service, and node health evaluation
   - **Network Diagnostics**: Test connectivity and troubleshoot networking issues
   - **Resource Management**: Monitor and optimize resource usage
   - **Cluster Maintenance**: Clean up stale resources and namespaces
   - **Recovery Tools**: Automated recovery from common failure modes
   - **Observability**: Log aggregation and diagnostic capture

   K8sToolbox is designed with security in mind, featuring:
   - Least privilege RBAC configurations
   - Non-privileged container execution
   - Comprehensive security guidelines
   - Helm-based deployment with secure defaults

   ## Getting Started

   ```bash
   # Deploy via Helm
   helm repo add k8smed https://k8smed.github.io/charts/
   helm install k8stoolbox k8smed/k8stoolbox

   # Or deploy directly with kubectl
   kubectl apply -f https://github.com/K8sMed/K8sToolbox/raw/main/manifests/debug-pod.yaml
   ```

   ## Security Focus

   We prioritize security in all our projects. Our deployment configurations follow the principle of least privilege by default, and we provide extensive documentation on secure usage patterns.

   Every tool includes:
   - Detailed security guidelines
   - Production-ready configurations
   - Least privilege RBAC templates
   - Non-root container execution

   ## Contributing

   We welcome contributions from the community! Whether you're interested in fixing bugs, adding new features, or improving documentation, check our repositories for contribution guidelines.

   ## Connect With Us

   - [GitHub Discussions](https://github.com/K8sMed/discussions)
   - [Twitter](https://twitter.com/k8smed)
   - [Slack Community](https://k8smed.slack.com)

   ---

   *K8sMed - Keeping your Kubernetes clusters healthy*

