# rocketseat.k8s.modules

## Módulos do TF usados na criação do EKS nas aulas de Kubernetes.

### Fluxo de execução
- Necessário instalar a cli do Terraform - [doc](https://developer.hashicorp.com/terraform/install)
- Após atualizar as credenciais da AWS no seu ambiente local, basta rodar os seguintes comandos:
		- `terraform init` - necessário rodar apenas na primeira execução
		- `terraform plan`
		- `terraform apply` e/ou `terraform apply -auto-approve`
- Para destruir todos os recursos, basta rodar:
		- `terraform destroy` e/ou `terraform destroy -auto-approve`