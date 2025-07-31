# rocketseat.k8s.modules
## Módulos do TF usados na criação do EKS nas aulas de Kubernetes.

### Fluxo de execução

#### 1. Necessário instalar a cli do Terraform - [doc](https://developer.hashicorp.com/terraform/install)
#### 2. Ter as credenciais da AWS atualizadas no seu ambiente local
#### 3. Rodar os seguintes comandos:
```bash
terraform init - necessário rodar apenas na primeira execução
terraform plan
terraform apply e/ou terraform apply -auto-approve
```
### Para destruir todos os recursos criados:
```bash
terraform destroy e/ou terraform destroy -auto-approve
```