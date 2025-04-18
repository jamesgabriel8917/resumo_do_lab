# resumo_do_lab

# 📌 Computação em Nuvem

Este documento aborda os principais conceitos relacionados à computação em nuvem, seus modelos, custos e uma revisão geral do tema.

## 📖 Conteúdo

### 1️⃣ Computação em Nuvem: Domínio do Objetivo
- Introdução aos conceitos fundamentais da computação em nuvem.
- Benefícios da adoção da nuvem.
- Casos de uso e exemplos práticos.

### 2️⃣ Comparação de Modelos de Nuvem
- Diferenças entre os modelos de serviço:
  - **IaaS** (Infrastructure as a Service)
  - **PaaS** (Platform as a Service)
  - **SaaS** (Software as a Service)
- Modelos de implantação:
  - **Nuvem Pública**
  - **Nuvem Privada**
  - **Nuvem Híbrida**

### 3️⃣ Comparação entre CapEx e OpEx
- Definição de **CapEx (Capital Expenditure)** e **OpEx (Operational Expenditure)**.
- Diferenças entre os dois modelos de custo na adoção da nuvem.
- Vantagens e desvantagens de cada abordagem.




#Desafio 2

## 📌 Resumo 

## 📖 Conteúdo

## 1️⃣ Computação em Nuvem: Alta disponibilidade
- Diferentes servicos podem variar em termos de disponibilidade, mas todos eles oferecem um tempo altissimo de disponibilidade esperada.

# Armazenamento com Redundância

## 📦 Opções de Armazenamento

## 1️⃣ LRS (Armazenamento com Redundância Local)
- 💰 Custo mais baixo
- 🔄 Proteção contra falhas de drive e rack do servidor
- ✅ Recomendado para cenários não críticos

## 2️⃣ GRS (Armazenamento com Redundância Geográfica)
- 🌍 Failover em uma região secundária
- 🔄 Proteção intermediária
- ✅ Recomendado para cenários de backup

## 3️⃣ ZRS (Armazenamento com Redundância de Zona)
- 🏢 Proteção contra falhas no nível do datacenter
- ⚡ Alta disponibilidade
- ✅ Recomendado para cenários que exigem continuidade de serviço
## 4️⃣ GZRS (Armazenamento com Redundância de Zona Geográfica)
- 🔐 Solução ideal para proteção de dados
- 🌎 Combina redundância de zona e geográfica
- ✅ Recomendado para cenários de dados críticos


# Tipos de Serviço de Nuvem na Azure  

## IaaS, PaaS e SaaS na Azure  

Os três principais modelos de serviço em nuvem são:  

### 🚀 IaaS (Infrastructure as a Service)  
Fornece infraestrutura virtualizada, como servidores, redes e armazenamento. O usuário é responsável por gerenciar o sistema operacional e os aplicativos.  

🔹 **Exemplo**: Azure Virtual Machines  

### 🛠️ PaaS (Platform as a Service)  
Oferece uma plataforma pronta para desenvolvimento, eliminando a necessidade de gerenciar a infraestrutura subjacente.  

🔹 **Exemplo**: Azure App Services  

### ☁️ SaaS (Software as a Service)  
Aplicações prontas para uso, acessadas diretamente pela internet, sem necessidade de instalação ou manutenção.  

🔹 **Exemplo**: Microsoft 365  

---  

## Modelo de Responsabilidade Compartilhada  

O modelo de responsabilidade compartilhada define o que é gerenciado pela **Azure** e o que fica sob responsabilidade do **usuário**:  

- **IaaS** → O usuário gerencia o sistema operacional, aplicativos e segurança dos dados.  
- **PaaS** → A Azure gerencia a infraestrutura e parte da segurança, enquanto o usuário cuida dos dados e aplicações.  
- **SaaS** → A Azure gerencia quase tudo, e o usuário se preocupa apenas com a proteção dos dados e a configuração de acesso.  

📌 **Resumo**: Quanto mais alto na escala (de IaaS para SaaS), menor a responsabilidade do usuário sobre a infraestrutura.  


# Componentes de Arquitetura do Azure  

## 🔹 Componentes de Arquitetura do Azure  
A Microsoft Azure é composta por diversos serviços e componentes essenciais para a construção e gestão de aplicações na nuvem. Alguns dos principais são:  

- **Máquinas Virtuais (VMs)**: Servidores escaláveis na nuvem.  
- **Storage**: Serviços de armazenamento para dados estruturados e não estruturados.  
- **Redes Virtuais (VNet)**: Permite conectar recursos dentro da Azure de forma segura.  
- **Azure Kubernetes Service (AKS)**: Gerenciamento de contêineres na Azure.  
- **Azure Functions**: Execução de código sem necessidade de servidores (Serverless).  

---  

## 🌍 Entendendo Pares de Região e Grupos de Recursos  

### 📍 **Pares de Região**  
A Azure organiza suas regiões em **pares**, garantindo alta disponibilidade e recuperação de desastres. Benefícios incluem:  
✅ Redundância geográfica para segurança dos dados.  
✅ Atualizações controladas para minimizar impactos.  
✅ Recuperação rápida em caso de falhas.  

### 🗂️ **Grupos de Recursos**  
Os **Resource Groups** organizam e gerenciam recursos dentro da Azure. Características principais:  
✅ Permitem aplicar permissões e políticas em vários recursos ao mesmo tempo.  
✅ Facilitam o gerenciamento e a organização dos serviços na nuvem.  
✅ Possibilitam a exclusão em massa de recursos relacionados.  

---  

## 🏢 Assinatura da Azure e Grupos de Gerenciamento  

### 🔑 **Assinatura da Azure**  
A assinatura da Azure define o nível de acesso e faturamento de um ambiente. Cada assinatura está associada a um **tenant do Azure Active Directory (AAD)**.  

### 📂 **Grupos de Gerenciamento**  
Os Grupos de Gerenciamento facilitam o controle de múltiplas assinaturas dentro de uma organização. Benefícios:  
✅ Aplicação de políticas e controle de acesso centralizado.  
✅ Organização hierárquica para grandes infraestruturas.  
✅ Simplificação do gerenciamento de segurança e compliance.  

---  

# Computação e Rede no Azure  

## 🖥️ Serviços de Computação e Máquinas Virtuais do Azure  
A **Azure** oferece diversos serviços de computação na nuvem para diferentes necessidades:  
- **Máquinas Virtuais (VMs)**: Servidores escaláveis para rodar sistemas operacionais e aplicativos.  
- **Escalabilidade**: As VMs podem ser redimensionadas automaticamente para atender à demanda.  
- **Modelos de Implantação**: Incluem VMs individuais, Conjuntos de Disponibilidade e Scale Sets.  

---  

## 🏗️ Conjuntos de Disponibilidade de Máquinas Virtuais do Azure  
Os **Availability Sets** garantem alta disponibilidade e redundância para máquinas virtuais na **Azure**. Benefícios incluem:  
✅ Proteção contra falhas de hardware em um único data center.  
✅ Distribuição das VMs entre **Domínios de Falha** e **Domínios de Atualização**.  
✅ Aumento do SLA de disponibilidade para **99,95%**.  

---  

## 📦 Área de Trabalho Virtual e Contêineres do Azure  
### 🖥️ **Azure Virtual Desktop (AVD)**  
O **Azure Virtual Desktop** permite criar ambientes de trabalho virtualizados, acessíveis de qualquer lugar.  
✅ Flexibilidade para rodar Windows em qualquer dispositivo.  
✅ Segurança avançada com gerenciamento centralizado.  

### 🐳 **Contêineres no Azure**  
Os contêineres permitem a implantação rápida de aplicações de forma isolada e eficiente. Principais serviços:  
- **Azure Kubernetes Service (AKS)**: Gerenciamento de contêineres em escala.  
- **Azure Container Instances (ACI)**: Execução rápida de contêineres sem necessidade de gerenciar servidores.  

---  

## ⚡ Azure Functions e Serviços de Aplicativo do Azure  
### 🔥 **Azure Functions**  
Permite a execução de código sem gerenciar infraestrutura (**Serverless**).  
✅ Escalabilidade automática.  
✅ Cobrança apenas pelo tempo de execução.  

### 🌐 **Azure App Services**  
Facilita a hospedagem de aplicações web e APIs.  
✅ Suporte para várias linguagens (Java, .NET, Node.js, Python).  
✅ Integração com banco de dados e serviços da Azure.  

---  

# 🔐 Identidade, Acesso e Segurança no Azure  

## 🛡️ Identidade, Acesso e Segurança  
O controle de identidade e acesso é essencial para garantir a segurança dos serviços na nuvem. No Azure, a segurança se baseia nos princípios de:  
- **Confidencialidade**: Proteção contra acessos não autorizados.  
- **Integridade**: Garantia de que os dados não sejam alterados indevidamente.  
- **Disponibilidade**: Garantia de acesso contínuo e seguro aos serviços.  

---  

## 🔑 Microsoft Entra ID e Domain Services  
### 📌 **Microsoft Entra ID (Azure AD)**  
O **Microsoft Entra ID** (antigo Azure AD) é a solução de gerenciamento de identidade do Azure. Permite:  
✅ Autenticação única (**SSO**) para acesso seguro a aplicativos.  
✅ Gerenciamento centralizado de usuários e grupos.  
✅ Integração com aplicações **SaaS** e diretórios locais.  

### 📂 **Azure AD Domain Services**  
Fornece serviços de domínio gerenciados, como:  
✅ Autenticação LDAP e NTLM/Kerberos.  
✅ Suporte para aplicações legadas sem necessidade de controladores de domínio locais.  

---  

## 🔑 Autenticação e Autorização  
### 🔐 **Autenticação**  
Processo de verificação de identidade do usuário, garantindo que ele seja quem diz ser. Métodos comuns incluem:  
- **Senha**: A forma tradicional, mas menos segura.  
- **Autenticação Multifator (MFA)**: Uso de mais de um fator (como senha + código SMS).  
- **Biometria**: Impressão digital, reconhecimento facial, etc.  

### 🎟️ **Autorização**  
Após a autenticação, a **autorização** define o que o usuário pode acessar. No Azure, isso é gerenciado por:  
✅ **RBAC (Role-Based Access Control)**: Controle baseado em funções.  
✅ **Políticas de acesso condicional** para restringir acessos com base em regras específicas.  

---  

## 🚦 Acesso Condicional  
O **Acesso Condicional** permite aplicar regras avançadas para proteger identidades e dados. Exemplos de políticas:  
- Exigir **MFA** para acessos fora da empresa.  
- Bloquear logins de dispositivos não gerenciados.  
- Aplicar restrições com base no **local geográfico**.  

---  

## 📌 Identidade, Acesso e Segurança - Revisão  
Esta seção revisa os principais conceitos abordados, garantindo a compreensão da segurança no Azure.  

---  
