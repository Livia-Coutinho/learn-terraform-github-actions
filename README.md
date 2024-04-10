# Automate Terraform with GitHub Actions

This repo is a companion repo to the [Automate Terraform with GitHub Actions tutorial](https://developer.hashicorp.com/terraform/tutorials/automation/github-actions).

</br>
</br>
</br>
</br>



# Resumo da tecnologia:
O GitHub Actions é uma ferramenta que adiciona integração contínua aos repositórios do GitHub, permitindo automatizar builds, testes e implantações de software. Ao integrar o Terraform com o GitHub Actions, é possível automatizar o fluxo de trabalho do Terraform, desde a geração de planos até a aplicação das configurações, utilizando o Terraform Cloud como backend.

O Terraform é uma ferramenta de infraestrutura como código (IaC) desenvolvida pela HashiCorp. Ele permite definir e provisionar infraestrutura de forma declarativa, tratando a infraestrutura como código, o que facilita a automação, a repetibilidade e o controle de versão.

# Conceitos aprendidos:
- **GitHub Actions:** Entender como o GitHub Actions pode ser usado para automatizar fluxos de trabalho de desenvolvimento, incluindo a execução de tarefas do Terraform.

- **Terraform Cloud:** Aprender a configurar um workspace no Terraform Cloud, o que é necessário para integrar o GitHub Actions com o Terraform.

- **Automatização do Terraform:** Entender como automatizar o fluxo de trabalho do Terraform, desde a geração de planos até a aplicação das configurações, utilizando o GitHub Actions e o Terraform Cloud.

- **Integração Contínua (CI):** Compreender o conceito de integração contínua e como ela pode ser implementada usando ferramentas como o GitHub Actions para automatizar tarefas como testes e implantações.

- **Infraestrutura como Código (IaC):** Aprender sobre os princípios da IaC e como o Terraform permite gerenciar a infraestrutura de forma programática, o que traz benefícios como automação, consistência e controle de versionamento.

</br>
</br>
</br>

# Prints da realização da atividade

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

#### - git checkout -b 'update-tfc-org'
![alt text](image-17.png)

#### - git add .github/workflows
![alt text](image-18.png)

#### - git commit -m 'Use our Terraform Cloud organization'
![alt text](image-19.png)
![alt text](image-21.png)

#### - git push origin update-tfc-org
![alt text](image-20.png)

#### - Pull requests
![alt text](image-22.png)