# Monitoramento de Máquinas Virtuais no Microsoft Azure

## Descrição do Projeto

Este repositório contém a documentação do laboratório prático para configurar e gerenciar o monitoramento de recursos no Microsoft Azure, com foco em máquinas virtuais (VMs). O objetivo é garantir visibilidade, controle e respostas proativas a eventos críticos no ambiente de nuvem, como a exclusão de uma VM.

## Objetivos de Aprendizagem

- Aplicar os conceitos de monitoramento em um ambiente prático do Azure;  
- Documentar os processos técnicos de forma clara e organizada;  
- Compartilhar o conhecimento utilizando o GitHub como ferramenta.

## Conteúdo do Repositório

- `README.md` — Documento principal com o resumo do projeto, objetivos, dicas e procedimentos;  
- `/images` — (Opcional) Pasta contendo capturas de tela relevantes;  
- Arquivos adicionais — Scripts, consultas KQL ou outros arquivos usados no laboratório.

## Principais Conceitos e Ferramentas

- **Azure Monitor:** Serviço centralizado para coleta e análise de métricas e logs;  
- **Log Analytics:** Workspace para armazenar e consultar logs usando Kusto Query Language (KQL);  
- **Alertas no Azure Monitor:** Configuração de notificações para eventos críticos;  
- **Registro de Atividades:** Histórico detalhado de operações e alterações nos recursos Azure;  
- **Azure Network Watcher:** Monitoramento e diagnóstico do tráfego de rede das VMs.

## Passos para Configuração do Monitoramento

1. Selecionar a máquina virtual no portal do Azure;  
2. Configurar diagnósticos para coleta de métricas e logs;  
3. Criar regras de alerta com condições específicas (ex: uso alto de CPU);  
4. Configurar grupos de ação para notificação automática (e-mails, SMS etc.);  
5. Utilizar o Log Analytics para criar consultas e analisar os dados coletados;  
6. Verificar o Registro de Atividades para auditoria e investigação;  
7. Utilizar Azure Network Watcher para análise detalhada do tráfego de rede (se necessário).

## Dicas e Boas Práticas

- Sempre defina a severidade dos alertas para priorizar ações;  
- Use consultas pré-definidas no Log Analytics como ponto de partida;  
- Personalize alertas para refletir as necessidades específicas do seu ambiente;  
- Mantenha o registro de atividades sempre ativo para auditorias;  
- Automatize notificações para a equipe técnica responder rapidamente.

## Recursos Úteis

- [Documentação oficial do Azure Monitor](https://learn.microsoft.com/azure/azure-monitor/);  
- [Monitorar máquinas virtuais no Azure](https://learn.microsoft.com/azure/virtual-machines/monitor-virtual-machine);  
- [Kusto Query Language (KQL) Overview](https://learn.microsoft.com/azure/data-explorer/kusto/query/).

---

---

*Projeto desenvolvido para fins de aprendizado e prática em monitoramento no Azure.*



