# terraform-aws

> Provisionamento automatizado de bucket S3 na AWS usando Terraform (em desenvolvimento e estudo).

## 📋 Descrição

Este módulo Terraform realiza o provisionamento de um **bucket S3** na AWS, com opções configuráveis de nome, versãoamento e controle de acesso. É ideal para uso em testes, projetos simples ou como base para módulos maiores.

## 📁 Estrutura do Projeto

```text
.
├── main.tf         # Lógica principal de provisionamento do bucket
├── variables.tf    # Variáveis de entrada configuráveis
├── outputs.tf      # Saídas do Terraform após o apply
└── README.md
