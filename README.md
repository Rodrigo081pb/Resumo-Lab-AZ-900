A AZ-900 é a porta de entrada para o universo da computação em nuvem com a Microsoft. Ela valida seu conhecimento básico sobre conceitos de nuvem, serviços do Azure e boas práticas de segurança e governança.

### 📚 Tópicos da Prova

---

### 1. 🌩️ Conceitos de Computação em Nuvem
- Diferença entre IaaS, PaaS e SaaS
- Tipos de nuvem: pública, privada e híbrida
- Benefícios da nuvem: escalabilidade, elasticidade, alta disponibilidade, tolerância a falhas

---

### 2. 🏗️ Arquitetura e Serviços do Azure
- Regiões, zonas de disponibilidade e pares de regiões
- Grupos de recursos e gerenciamento de recursos
- Principais serviços:
  - **Compute**: Máquinas Virtuais, Azure Functions, App Services
  - **Storage**: Blob Storage, Disk Storage, File Storage
  - **Networking**: Virtual Network, VPN Gateway, Azure DNS
  - **Databases**: Azure SQL, Cosmos DB, Azure Database for MySQL/PostgreSQL

---

### 3. 🔐 Segurança, Conformidade e Privacidade
- Azure Security Center e Defender for Cloud
- Azure Policy e Blueprints
- Identidade e acesso: Azure Active Directory, RBAC (controle baseado em função), MFA
- Certificações de conformidade (ISO, GDPR, etc.)

---

### 4. 💰 Gerenciamento de Custos e SLA
- Calculadora de preços e TCO (Total Cost of Ownership)
- Azure Cost Management
- Modelos de assinatura e licenciamento
- Acordos de nível de serviço (SLA) e impacto na disponibilidade

---

### 🧪 Dicas de Estudo
- Use o [Microsoft Learn](https://learn.microsoft.com/pt-br/credentials/certifications/resources/study-guides/az-900) como base oficial
- Faça laboratórios práticos no portal Azure
- Resolva simulados para se familiarizar com o estilo das perguntas
- Estude com foco nos conceitos, não apenas na prática técnica

---

### 🏆 Por que tirar a AZ-900?
- Reconhecimento oficial da Microsoft
- Excelente para quem está começando na área de TI ou deseja migrar para cloud
- Base sólida para certificações mais avançadas como AZ-104 (Admin) ou AZ-204 (Developer)

---

# 🚀 Projeto: Consolidação de Conhecimentos em Máquinas Virtuais na Azure

Este projeto foi desenvolvido com o objetivo de aplicar na prática os conceitos aprendidos sobre máquinas virtuais (VMs) na plataforma Microsoft Azure. Ao longo do desafio, foram criadas e configuradas VMs, documentados os processos técnicos e analisadas as funcionalidades oferecidas pela nuvem da Microsoft.

---

## 🎯 Objetivos do Projeto

- Aplicar os conhecimentos adquiridos em um ambiente real da Azure
- Criar e configurar máquinas virtuais Linux e Windows
- Documentar os processos técnicos de forma clara e estruturada
- Compreender aspectos de escalabilidade, segurança e gerenciamento de recursos

---

## 🛠️ Etapas Realizadas

### 1. Criação de Máquinas Virtuais
- ✅ VM Linux (Ubuntu Server 22.04 LTS)
- ✅ VM Windows Server 2022
- Configuração de tamanho, disco, rede virtual e grupo de segurança

### 2. Configuração de Acesso
- Criação de regras de NSG para permitir acesso via SSH (Linux) e RDP (Windows)
- Testes de conectividade com IP público

### 3. Instalação de Serviços
- Linux: Apache, MySQL e PHP (LAMP Stack)
- Windows: IIS e configuração de página web padrão

### 4. Monitoramento e Gerenciamento
- Utilização do Azure Monitor para acompanhar métricas de CPU, memória e disco
- Configuração de alertas e logs de diagnóstico

### 5. Encerramento e Limpeza
- Encerramento das VMs
- Exclusão de recursos para evitar cobranças adicionais
  
---

### ☁️ Tipos de Serviços na Nuvem – Resumo

A computação em nuvem oferece diferentes **modelos de serviço**, cada um com níveis variados de controle, flexibilidade e responsabilidade:

#### 1. **IaaS (Infraestrutura como Serviço)**
- 🧱 Você aluga recursos básicos de TI: servidores, armazenamento, redes.
- ⚙️ Ideal para empresas que querem controle total sobre o ambiente.
- 📌 Exemplo: Microsoft Azure, Amazon EC2.

#### 2. **PaaS (Plataforma como Serviço)**
- 🛠️ Fornece ambiente para desenvolvimento e hospedagem de aplicativos.
- 👨‍💻 Você foca no código e na lógica do app, sem se preocupar com servidores.
- 📌 Exemplo: Google App Engine, Azure App Service.

#### 3. **SaaS (Software como Serviço)**
- 💻 Aplicações prontas acessadas via navegador, sem instalação local.
- 🧑‍💼 Ideal para usuários finais que precisam de software funcional sem gerenciar nada.
- 📌 Exemplo: Microsoft 365, Google Workspace, Salesforce.

---

### 🔄 Comparando os Modelos

| Modelo   | Você gerencia | O provedor gerencia | Exemplo de uso |
|----------|----------------|----------------------|----------------|
| **IaaS** | Sistema operacional, apps | Hardware, rede, armazenamento | Criar máquinas virtuais |
| **PaaS** | Aplicações e dados | Infraestrutura + sistema operacional | Desenvolver apps web |
| **SaaS** | Apenas uso do software | Tudo (infra + software) | Usar email, CRM, planilhas |

---
