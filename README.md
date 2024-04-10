# Automate Terraform with GitHub Actions

This repo is a companion repo to the [Automate Terraform with GitHub Actions tutorial](https://developer.hashicorp.com/terraform/tutorials/automation/github-actions).


# Resumo da tecnologia:
O GitHub Actions é uma ferramenta que adiciona integração contínua aos repositórios do GitHub, permitindo automatizar builds, testes e implantações de software. Ao integrar o Terraform com o GitHub Actions, é possível automatizar o fluxo de trabalho do Terraform, desde a geração de planos até a aplicação das configurações, utilizando o Terraform Cloud como backend.

O Terraform é uma ferramenta de infraestrutura como código (IaC) desenvolvida pela HashiCorp. Ele permite definir e provisionar infraestrutura de forma declarativa, tratando a infraestrutura como código, o que facilita a automação, a repetibilidade e o controle de versão.

#### - Login AWS
![alt text](image.png)

#### - Acesso LearnerLab
![alt text](image-1.png)

#### - Criar conta Terraform
![alt text](image-2.png)

#### - Terraform - New Organization
![alt text](image-3.png)

#### - Terraform - New Workspace
![alt text](image-4.png)

#### - AWS - Start Lab (para pegar as variáveis)
![alt text](image-5.png)

#### - Terraform - Definir as variáveis
![alt text](image-6.png)

#### - Terraform - Criar Token
![alt text](image-7.png)
![alt text](image-8.png)

#### - Github - Novo repositório
![alt text](image-9.png)

#### - Github - Secrets and Variables
![alt text](image-10.png)
![alt text](image-11.png)

#### - Clonar repositório para a máquina local
![alt text](image-12.png)

#### - terraform-plan.yml
![alt text](image-13.png)

#### - terraform-apply.yml
![alt text](image-14.png)

#### Trocar região no arquivo main.tf
![alt text](image-15.png)
![alt text](image-16.png)