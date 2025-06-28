# Monitoramento de Recursos no Microsoft Azure com Foco em VMs 🚀

#Sobre o Desafio

Este repositório foi criado como parte do desafio da DIO sobre **monitoramento de recursos no Azure**, com foco em **máquinas virtuais (VMs)**. O objetivo foi aplicar os conhecimentos adquiridos nas aulas para configurar alertas e manter o controle de eventos críticos no ambiente de nuvem.

---

#Objetivos do Projeto

- Criar uma VM no Azure e organizar os recursos com boas práticas;
- Ativar o monitoramento e coletar logs de diagnóstico;
- Criar alertas para eventos como exclusão, desligamento ou falhas na VM;
- Documentar a experiência como apoio nos estudos da certificação AZ-104.

---

#Etapas Realizadas

#Criação da VM
- Máquina virtual criada com Windows Server 2019;
- Inclusão de tags e associação ao grupo de recursos.

#Configuração do Monitoramento
- Ativação do Azure Monitor;
- Habilitação do diagnóstico da VM;
- Criação de **alertas personalizados** via Azure Monitor;
- Definição de um **Action Group** para envio de alertas por e-mail.

#Testes de Evento
- Simulação de desligamento e reinício da VM;
- Verificação da chegada do e-mail de alerta;
- Checagem dos logs e métricas no portal do Azure.

---

#Dicas e Anotações

- Sempre nomeie bem os recursos e use tags como `ambiente=producao`, `owner=seunome`;
- Os **Action Groups** podem enviar notificações para e-mail, SMS ou até executar automações;
- O **Log Analytics** permite consultar logs detalhados com Kusto Query Language (KQL);
- O painel do **Azure Monitor** centraliza métricas e logs de todos os recursos.

---

#Fontes Utilizadas

- [Documentação oficial do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/overview)
- [Microsoft Learn - Monitoramento de VMs](https://learn.microsoft.com/pt-br/azure/azure-monitor/vm/vminsights-overview)
- [Guia Markdown do GitHub](https://guides.github.com/features/mastering-markdown/)

---

#Status do Projeto

✔️ Desafio concluído e pronto para entrega na DIO  
🚀 Preparação em andamento para a certificação **AZ-104**

---

#Autor

Vinicius Matos 
