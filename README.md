# Controle de Chamados — Sistema de Suporte Técnico (Excel)

**Projeto | Área: Help Desk / QA / RPA**

## Sobre o projeto

Simulação de um sistema real de controle de chamados/incidentes de TI,
construída em Excel, demonstrando capacidade de estruturar dados,
automatizar cálculos e gerar indicadores de gestão sem depender de
ferramenta externa.

## O que o projeto resolve

Em qualquer operação de suporte, é preciso rastrear volume de chamados,
identificar gargalos por categoria e medir se a equipe está cumprindo
prazos de atendimento (SLA). Este projeto simula esse controle do zero:
da entrada do chamado até o indicador de performance.

## Estrutura do arquivo

- **Sobre** — contexto do projeto
- **Chamados** — base de dados com 48 chamados fictícios
- **Parâmetros** — tabelas de apoio (responsáveis e SLA por prioridade)
- **Resumo** — indicadores, tabelas-resumo e 3 gráficos

## Fórmulas utilizadas

- **PROCV (VLOOKUP)** — relaciona responsável e SLA a partir de tabelas
  de apoio
- **SE (IF)** — classifica automaticamente chamados como "dentro" ou
  "fora do prazo"
- **CONT.SE / MÉDIASES (COUNTIF / AVERAGEIFS)** — indicadores agregados
  por categoria e prioridade
- Cálculo de intervalo entre datas para tempo de resolução

## Habilidades demonstradas

- Estruturação de base de dados
- Fórmulas de busca e condicionais
- Fórmulas de agregação para indicadores gerenciais
- Construção de gráficos dinâmicos ligados a dados-resumo

## Ferramentas

Microsoft Excel

## Arquivo

- 📊 [Visualizar planilha completa](https://1drv.ms/x/c/51516c58c9185420/IQDA1aoeBcqFRpLLF4HTxRTlAX-_dXcJjSvo5ttxNZJNy9M
)

**Autor:** [Leandro]
