# LAB - Monitoramento Inteligente com o Azure (AZ900 | DIO)

Este documento apresenta, de forma simples e prática, como o Microsoft Azure oferece **monitoramento inteligente e proativo** por meio de ferramentas como **Azure Monitor**, **Application Insights**, **Log Analytics**, e **Azure Advisor** — recursos fundamentais no conteúdo da certificação AZ-900.

---

## 🔍 Azure Monitor

O **Azure Monitor** é a central de monitoramento de recursos dentro da Azure. Ele permite **coletar, analisar e agir** com base em métricas e logs de seus serviços.

### 📸 Visão Geral do Azure Monitor

![Azure Monitor Overview](/imagens/monitor.png)

A imagem acima mostra os principais componentes do painel inicial:

| Componente             | Descrição                                                                 |
|------------------------|---------------------------------------------------------------------------|
| **Application Insights** | Monitora o desempenho de aplicações web, APIs e serviços em tempo real. |
| **Container Insights**   | Acompanha a integridade e desempenho de clusters e containers.          |
| **VM Insights**          | Mostra informações detalhadas sobre desempenho de VMs.                  |
| **Network Insights**     | Exibe métricas de rede, conectividade e latência.                      |
| **Metrics e Logs**       | Métricas gráficas e logs detalhados com filtros e queries.              |
| **Alerts**               | Notificações e ações automáticas baseadas em condições de alerta.       |

> 💡 Dica: Combinando **Logs + Alerts**, você pode automatizar ações como reiniciar um serviço ou enviar e-mails em casos críticos.

---

## 📈 Azure Advisor

O **Azure Advisor** é uma ferramenta de recomendações personalizadas. Ele analisa sua configuração e oferece **melhorias práticas** nas áreas de custo, segurança, performance e confiabilidade.

### 📸 Painel de Pontuação do Advisor

![Advisor Score](/imagens/advisor.png)

A imagem ilustra o painel do **Advisor Score**, que traz:

- **Pontuação Geral (Advisor Score)**: Representa a saúde geral do ambiente baseado nas recomendações aplicadas.
- **Categorias**:
  - **Custo**: Sugestões para economizar (por exemplo, desligar VMs ociosas).
  - **Segurança**: Medidas para reforçar o ambiente contra ameaças.
  - **Confiabilidade**: Avaliação da disponibilidade e resiliência dos recursos.
  - **Excelência operacional**: Práticas de governança e manutenção.
  - **Performance**: Melhorias de desempenho dos recursos.

> ✅ **Exemplo prático**: Se o Advisor detectar que uma VM está com baixa utilização, ele pode sugerir um reescalonamento ou desligamento para economizar recursos.

---

## 🛠️ Monitoramento Prático na Preparação AZ-900

Durante o laboratório do curso da DIO, o aluno aprende a:

- Criar alertas personalizados para métricas de VMs e serviços.
- Usar o Application Insights para detectar erros e gargalos.
- Explorar logs via **Kusto Query Language (KQL)**.
- Aplicar recomendações do Azure Advisor para otimização.

---

## 📚 Conclusão

Monitorar seus recursos é essencial para manter a **confiabilidade, performance e segurança** no ambiente em nuvem. A Azure fornece ferramentas integradas e fáceis de usar, ideais para iniciantes até especialistas em nuvem.

Se você está estudando para a certificação AZ-900, domine esses recursos para demonstrar conhecimento prático em **monitoramento e governança em nuvem**.

--- 

**Links úteis:**

- [Documentação oficial do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/)
- [Documentação do Azure Advisor](https://learn.microsoft.com/pt-br/azure/advisor/)
- [Curso AZ-900 da DIO](https://www.dio.me/)

---

Desenvolvido por [**Pedro Henrique Gomes dos Santos**](https://www.linkedin.com/in/pedro-henrique-gomes-dos-santos/)