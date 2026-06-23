cat > README.md << 'EOF'
# StaticSite CI/CD Pipeline

## 🚀 Pipeline Flow
Code → Docker Image → DockerHub → Kubernetes → Live Website

## 🛠️ Tech Stack
- Docker
- Jenkins
- Kubernetes (Kind)
- AWS EC2

## 📁 Structure
- app/ → Static website
- jenkins/ → Jenkinsfile pipeline
- k8s/ → Kubernetes manifests
- Dockerfile → Container definition
EOF
