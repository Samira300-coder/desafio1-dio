
# 🖥️ Criação e Configuração de uma Máquina Virtual no Microsoft Azure

Este documento descreve o processo completo de criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure. Inclui resumos, anotações e dicas práticas para facilitar estudos e implementações futuras, como solicitado pela plataforma DIO em tarefa do Curso "XP Inc. - Cloud com Inteligência Artificial".
---

## 🔍 Visão Geral

O Microsoft Azure é uma plataforma de computação em nuvem da Microsoft que oferece serviços de infraestrutura, plataforma e software como serviço (IaaS, PaaS e SaaS). A criação de máquinas virtuais faz parte do modelo IaaS, permitindo a simulação de servidores físicos na nuvem.
---

## 🚀 Passo a Passo: Criando uma Máquina Virtual no Azure

### 1. Acessar o Portal Azure
- URL: https://portal.azure.com
- Faça login com sua conta Microsoft.

### 2. Criar um Novo Recurso
- No menu lateral, clique em **"Criar um recurso"**.
- Escolha a opção **"Máquina Virtual"** na categoria de Computação.

### 3. Configurações Básicas
- **Assinatura**: Escolha a conta de cobrança.
- **Grupo de recursos**: Crie um novo ou selecione um existente.
- **Nome da VM**: Defina um nome único.
- **Região**: Escolha a localização geográfica (ex: "Brasil Sul").
- **Imagem**: Selecione o sistema operacional (ex: Windows Server 2022 ou Ubuntu 20.04).
- **Tamanho**: Escolha uma configuração de CPU e memória (ex: B1s para testes).

### 4. Configuração de Conta Administrativa
- Crie um nome de usuário e senha (ou chave SSH para Linux).
- Guarde essas credenciais com segurança.

### 5. Regras de Entrada
- Habilite as portas de acesso necessárias:
  - **RDP (porta 3389)** para Windows
  - **SSH (porta 22)** para Linux

### 6. Disco e Rede
- Escolha o tipo de disco (SSD padrão ou premium).
- Configure a rede virtual e o IP público.
- Utilize um grupo de segurança de rede para controlar o tráfego.

### 7. Revisar e Criar
- Revise todas as configurações.
- Clique em **"Criar"** e aguarde a implantação.
---

## 🧠 Anotações

- A criação de recursos pode levar alguns minutos.
- O Azure cobra por tempo de execução e recursos utilizados.
- É possível parar ou excluir a VM para evitar cobranças extras.
---

## 💡 Dicas

- Para fins de estudo, utilize o nível gratuito do Azure.
- Use **tags** para organizar e rastrear os custos dos recursos.
- Automatize a criação com Azure CLI ou ARM Templates.
- Monitore sua VM com **Azure Monitor**.
- Faça backups regulares utilizando o serviço **Azure Backup**.
---

## 🧾 Conclusão

Criar e configurar máquinas virtuais no Azure é essencial para quem busca aprender mais sobre infraestrutura em nuvem. Com prática e atenção às boas práticas, é possível construir ambientes eficientes, seguros e escaláveis.
---

