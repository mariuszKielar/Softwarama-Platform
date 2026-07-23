## Work in Progress

I'm currently building a **4-node bare-metal Kubernetes home lab**. The project currently includes:

* ✅ 4 × Rocky Linux machines
* ✅ Ansible for system configuration and hardening
* ✅ Kubernetes (kubeadm, containerd, Calico, Podman)
* ✅ GitHub Actions for linting, building, testing, and pushing my portfolio website image to GHCR
* ✅ MetalLB for providing LoadBalancer IP addresses on my home LAN
* ✅ Sealed Secrets
* ✅ GitOps with Argo CD for automated deployments to staging and production namespaces
* ✅ cert-manager with a private PKI for TLS certificates used by internal services
* ✅ Cloudflare Tunnel with TLS for secure public access to my domain

### Planned additions

* [ ] Falco for runtime security
* [ ] Loki for log aggregation
* [ ] Prometheus for metrics collection
* [ ] Grafana for monitoring dashboards
* [ ] A backup solution (currently evaluating the available options)

This project is evolving continuously. As I gain more hands-on experience, I refine the architecture, improve the implementation, and replace earlier assumptions with better practices.

The initial workload running on the cluster is the MVP version of my DevOps portfolio website.

Once the project is complete, this temporary README will be replaced with comprehensive documentation covering the architecture, implementation, CI/CD pipelines, security, and operational decisions.    

General Architecture

 <img src="../diagrams-screenshots/generalArchSoftwarama.png" width="700">
 





