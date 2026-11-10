# AI-DevSecOps
A CICD integration implementations with AI, Security and Quality validation mechanisms

## Architecture
![Placeholder](https://github.com/henrychiang/ai-devsecops/blob/main/arch.gif?raw=true)

## Component

- [x] GitHub
- Repository for source-codes (cf, https://github.com/henrychiang/devsecaiops-ci)
- Repository for deploy (GitOps) artifacts (cf, https://github.com/henrychiang/devsecaiops-cd)
- Repository for source-codes (cf, https://github.com/henrychiang/go-opdev)
- [x] CloudBuild - GCP CICD engine to connect end-to-end steps
- [x] SonarQube - Tools to check codes' qualities
- [x] Trivy - Tools to check dependencies' vulnerabilities
- [x] Aider - Tools to refactor code-repositories
- [x] Ollama - Tools to deploy AI models, and render AI services
- [x] GPU - GCP L4VM to provide GPU hardwares
- [x] Monitoring - 'nvidia-smi' to monitor GPU usage
- [x] Registry - GCP Artifact Registry to store docker images
- [x] GKE - Kubernetes service to host applications





