# Sprint 2: 13/04/2026 - 03/05/2026

O projeto baseia-se no desenvolvimento de um sistema de coleta de dados de estações meteorológicas.
Esse sistema permitirá coletar automaticamente os dados ambientais, armazená-los em banco de dados e apresentá-los por meio de dashboards, relatórios e alertas climáticos para o público. Dessa forma, instituições públicas poderão monitorar condições climáticas em tempo real, identificar riscos e apoiar a tomada de decisões relacionadas à gestão ambiental e prevenção de desastres.

Tendo em vista o MVP, a segunda sprint concentrou-se no desenvolvimento do serviço responsável pelo recebimento dos dados das estações meteorológicas. Além disso, foi implementado um processador de dados encarregado de tratar e normalizar as informações recebidas. Também foram realizadas melhorias na plataforma, incluindo a separação entre acesso público e administrativo, a criação de dashboards em tabelas com opção de exportação nos formatos CSV e XLS, e a implementação de um mapa interativo para visualização das estações.

<br>

## 🎯 Objetivos da Sprint
O principal objetivo desta sprint foi estruturar o fluxo de recebimento e tratamento dos dados das estações meteorológicas, garantindo sua organização e disponibilidade para visualização.

- **Receptor de Dados**: O sistema deve receber os dados enviados pelas estações ESP32, validá-los e armazená-los, registrando ao menos o identificador da estação, o parâmetro medido, o valor e data/hora da coleta.

- **Dashboards e Relatórios**: O sistema deve exibir dashboards interativos com os parâmetros meteorológicos em tempo real e gerar ao menos 3 relatórios estatísticos distintos.

- **Controle de Acesso**: Implementação de um sistema de controle de acesso com, no mínimo, dois níveis de usuário - administrador (com acesso total às configurações) e público (com acesso restrito à visualização dos dashboards).

### Backlog da Sprint

| ID  | Requisito | Prioridade | User Story | Sprint | Story Points |
|-----|-----------|------------|------------|--------|--------------|
| US5 | RF03, RF06 | Média | Eu como usuário do sistema, desejo visualizar as métricas das regiões cadastradas, para acompanhar e analisar as condições climáticas de cada local monitorado. | 2 | 8 |
| US6 | RF03, RF05 | Média | Eu como usuário do sistema, desejo visualizar alertas climáticos gerados automaticamente quando uma medição ultrapassar um limite configurado, para identificar possíveis situações de risco ou desastres naturais. | 2 | 5 |
| US7 | RF04 | Média | Eu como usuário do sistema, desejo visualizar dashboards com dados organizados por parâmetro e apresentados em gráficos e cards, para analisar variações de temperatura, umidade e outros indicadores climáticos de forma clara e eficiente. | 2 | 8 |

<br>

## ☑️ Entrega

Veja a entrega da segunda sprint a seguir:

**Receptor de Dados**

https://github.com/user-attachments/assets/93f02b11-dfcb-48b9-93b7-7417d125a320

**:link: Clique no link abaixo para visualizar mais detalhes sobre o Receptor de Dados:**
> [Receptor de Dados](https://github.com/GeneSys-fatec/API-4DSM-RECEPTOR-DADOS/tree/develop)

<br>

**Processador de Dados**

**:link: Clique no link abaixo para visualizar mais detalhes sobre o Processador de Dados:**
> [Processador de Dados](https://github.com/GeneSys-fatec/API-4DSM-PROCESSADOR-DADOS/tree/develop)

<br>

**MVP da Sprint 2**

> <a href='https://youtu.be/mbkQFutfMhY'>Vídeo do Projeto</a>

<br>

## 📈 Métricas do Time

O acompanhamento de atividades, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe, onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo, incluindo as atividades desenvolvidas e seus responsáveis.

<img width="1544" height="724" alt="image" src="https://github.com/user-attachments/assets/73c7e2cf-b947-4a3b-b0ca-6b5440722ce0" />


---
