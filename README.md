# Resumo do Lab 3
# Computação em Nuvem: Modelos de Serviço (SaaS, PaaS e IaaS)

A computação em nuvem oferece diferentes modelos de serviço que variam em termos de responsabilidade e controle entre o provedor de nuvem e o cliente. Este documento explora três principais modelos de serviço de nuvem: **IaaS (Infrastructure as a Service)**, **PaaS (Platform as a Service)** e **SaaS (Software as a Service)**, apresentados em ordem crescente de responsabilidade do provedor.

---

## 1. **IaaS (Infrastructure as a Service)**

**Responsabilidade do Provedor:** Baixa  
**Responsabilidade do Cliente:** Alta

### Características:
- O cliente gerencia a maior parte da pilha, incluindo sistema operacional, middleware, dados e aplicativos.
- O provedor oferece a infraestrutura básica, como servidores, armazenamento, redes e virtualização.
- Os clientes têm maior controle sobre a configuração do ambiente.

### Principais Serviços Oferecidos:
- **Máquinas Virtuais (VMs)**: Como o Amazon EC2, Google Compute Engine, Azure VMs.
- **Armazenamento em Nuvem**: Como Amazon S3, Google Cloud Storage, Azure Blob Storage.
- **Redes e Balanceamento de Carga**: Configuração de redes virtuais e distribuição de tráfego.
- **Backup e Recuperação**: Oferece mecanismos para garantir a segurança dos dados.

### Exemplos de IaaS:
- **Amazon Web Services (AWS) EC2**
- **Google Cloud Compute Engine**
- **Microsoft Azure VMs**

---

## 2. **PaaS (Platform as a Service)**

**Responsabilidade do Provedor:** Média  
**Responsabilidade do Cliente:** Moderada

### Características:
- O provedor gerencia a infraestrutura subjacente (incluindo rede, servidores, armazenamento e virtualização), bem como o sistema operacional, middleware e tempo de execução.
- O cliente é responsável apenas pela gestão dos dados e do aplicativo.
- Ideal para desenvolvedores que desejam focar no desenvolvimento sem se preocupar com a manutenção da infraestrutura.

### Principais Serviços Oferecidos:
- **Ambientes de Desenvolvimento**: Plataformas que facilitam o desenvolvimento, teste e implantação de aplicativos, como Heroku ou Google App Engine.
- **Banco de Dados como Serviço**: Gerenciamento simplificado de bancos de dados, como Amazon RDS, Google Cloud SQL.
- **Integração Contínua/Implantação Contínua (CI/CD)**: Ferramentas para automação de pipelines de desenvolvimento.

### Exemplos de PaaS:
- **Google App Engine**
- **Heroku**
- **Microsoft Azure App Services**

---

## 3. **SaaS (Software as a Service)**

**Responsabilidade do Provedor:** Alta  
**Responsabilidade do Cliente:** Baixa

### Características:
- O provedor gerencia toda a pilha de tecnologia, incluindo infraestrutura, plataforma e o próprio software.
- O cliente usa o software pronto, acessível pela internet, geralmente via navegador.
- Adequado para empresas ou usuários que não desejam se preocupar com o desenvolvimento ou manutenção do software.

### Principais Serviços Oferecidos:
- **Aplicações Web**: Software pronto para uso, como Google Workspace, Microsoft 365, Salesforce.
- **Serviços de Email**: Como Gmail ou Outlook.com.
- **Softwares de Gestão**: Como Trello, Asana, e Slack para gestão de projetos e comunicação.

### Exemplos de SaaS:
- **Google Workspace (Gmail, Google Drive)**
- **Microsoft 365 (Word, Excel, Outlook)**
- **Salesforce (CRM)**

---

## Resumo

- **IaaS**: O cliente tem controle quase total sobre o ambiente, configurando infraestrutura e software.
- **PaaS**: O provedor gerencia a infraestrutura e a plataforma, deixando o cliente focado no desenvolvimento e gerenciamento de aplicativos.
- **SaaS**: O cliente simplesmente consome o software entregue pelo provedor, sem se preocupar com a infraestrutura ou plataforma.
