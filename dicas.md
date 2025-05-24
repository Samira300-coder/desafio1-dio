
# 💡 Dicas sobre o Uso do Microsoft Azure

Este arquivo contém uma coleção de dicas úteis para quem está começando a utilizar o Microsoft Azure, especialmente na criação 
e gerenciamento de máquinas virtuais. Use como referência rápida e guia de boas práticas.
---

## ⚙️ Gerenciamento de Recursos

- **Grupos de Recursos**: Organize seus recursos em grupos lógicos. Isso facilita o gerenciamento e a exclusão em massa.
- **Tags**: Aplique tags como `projeto`, `ambiente`, `custo`, etc., para facilitar o rastreamento e análise de custos.
- **Nomenclatura Padrão**: Use convenções consistentes como `vm-dev-web-br` para nomear recursos.

---

## 💸 Economia de Custos

- **Nível Gratuito**: Explore as opções gratuitas disponíveis no Azure. Ideal para testes e aprendizado.
- **Desligue as VMs quando não estiver usando**: Você continua pagando por VMs que estão rodando.
- **Use Instâncias Spot**: Para workloads não críticos, as VMs spot são mais baratas.
- **Monitoramento de Custo**: Utilize o **Azure Cost Management** para visualizar gastos e definir alertas.
---

## 🔐 Segurança

- **Usuário e Senha Fortes**: Evite senhas fracas. Prefira autenticação via SSH para Linux.
- **Portas Abertas**: Não deixe portas como RDP (3389) ou SSH (22) abertas ao público por muito tempo.
- **Grupos de Segurança de Rede (NSG)**: Configure regras específicas para limitar o tráfego à sua VM.
---

## 📊 Monitoramento e Backup

- **Azure Monitor**: Use para visualizar o desempenho da VM, CPU, rede e disco.
- **Logs**: Habilite logs de diagnóstico para ajudar na resolução de problemas.
- **Backup**: Configure backups automáticos com o serviço Azure Backup.
---

## 🤖 Automatização

- **Azure CLI**: Automatiza tarefas com comandos de terminal.
- **ARM Templates**: Cria infraestruturas como código.
- **Azure DevTest Labs**: Ideal para ambientes de desenvolvimento e testes.
---

## 🌐 Acesso e Conectividade

- **Região mais próxima**: Escolha uma região próxima geograficamente para menor latência.
- **DNS Personalizado**: Configure domínios personalizados para acesso mais simples.
---

## 📘 Recursos Recomendados

- [Documentação Oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Microsoft Learn - Azure](https://learn.microsoft.com/pt-br/training/azure/)
- [Azure Blog](https://azure.microsoft.com/pt-br/blog/)
- [Portal do Azure](https://portal.azure.com)

---
