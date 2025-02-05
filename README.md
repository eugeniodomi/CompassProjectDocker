# 🚀 Implantação de WordPress na AWS com Docker

## 📌 Visão Geral
Este projeto tem como foco implantar uma aplicação **WordPress** em uma infraestrutura de nuvem **AWS**, utilizando **Docker** para containerização. O objetivo é garantir uma solução **escalável**, **altamente disponível**, e que suporte o crescimento do tráfego de forma automatizada.

## 🏗️ Arquitetura da Solução
A infraestrutura será composta pelos seguintes componentes:

- **WordPress Containerizado**: Aplicação rodando dentro de um container Docker.
- **Banco de Dados MySQL (Amazon RDS)**: Banco de dados gerenciado para garantir alta disponibilidade e backup automático.
- **Amazon EFS (Elastic File System)**: Sistema de arquivos compartilhado para armazenar mídias e arquivos estáticos.
- **Load Balancer (ALB ou ELB)**: Balanceador de carga para distribuir o tráfego entre diferentes instâncias **EC2**.
- **Virtual Private Cloud (VPC)**: Rede privada segmentada com subnets públicas e privadas para segurança e melhor desempenho.

## 🎯 Objetivo
Criar uma infraestrutura otimizada para WordPress, garantindo:
- 🔹 **Escalabilidade** – Aumento automático de recursos conforme a demanda.
- 🔹 **Alta Disponibilidade** – Redundância de componentes para evitar downtime.
- 🔹 **Segurança** – Segmentação de rede com VPC e subnets privadas.
- 🔹 **Automação** – Uso de infraestrutura como código para provisionamento eficiente.

---

## 📄 Próximos Passos
- [🔧 Documentação completa](configuracao.md)
- [📌 Etapas de Implantação](etapas.md)
- [🚀 Deploy e Monitoramento](deploy.md)
