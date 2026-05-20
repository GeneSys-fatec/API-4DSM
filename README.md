# Sprint 3: 11/05/2026 - 31/05/2026

O projeto baseia-se no desenvolvimento de um sistema de coleta de dados de estações meteorológicas.
Esse sistema permitirá coletar automaticamente os dados ambientais, armazená-los em banco de dados e apresentá-los por meio de dashboards, relatórios e alertas climáticos para o público. Dessa forma, instituições públicas poderão monitorar condições climáticas em tempo real, identificar riscos e apoiar a tomada de decisões relacionadas à gestão ambiental e prevenção de desastres.

Tendo em vista o MVP, a terceira sprint foi dedicada à implementação da estação física utilizando o ESP32, consolidando o núcleo do sistema de coleta e processamento de dados ambientais. Além da infraestrutura de hardware, foram entregues funcionalidades voltadas à experiência do usuário, como guias explicativos dos parâmetros meteorológicos, notificações de alertas automáticos e exportação de dados em PDF.

<br>

## 🎯 Objetivos da Sprint
O principal objetivo desta sprint foi estruturar o fluxo completo de recebimento e tratamento dos dados provenientes das estações físicas, garantindo sua organização, integridade e disponibilidade para visualização.

- **Desenvolvimento de Datalogger**: O sistema embarcado (ESP32) deve implementar um datalogger capaz de coletar, registrar localmente e transmitir os dados dos sensores para o receptor de dados.

- **Estação Meteorológica Física**: Deve ser construída ao menos uma estação meteorológica física funcional, com os sensores necessários integrados ao ESP32 e operacional para envio de dados ao sistema.

- **Receptor de Dados**: O sistema deve receber os dados enviados pelas estações ESP32, validá-los e armazená-los, registrando ao menos o identificador da estação, o parâmetro medido, o valor e data/hora da coleta.

- **Geração de Alertas**: O sistema deve gerar alertas automaticamente quando um parâmetro meteorológico ultrapassar limites configuráveis.

- **Tutorial Educativo**: O sistema deve disponibilizar um guia explicativo sobre o significado de cada parâmetro meteorológico monitorado, acessível a usuários sem conhecimento técnico prévio.

### Backlog da Sprint

| ID  | Requisito | Prioridade | User Story | Sprint | Story Points |
|-----|-----------|------------|------------|--------|--------------|
| US8 | RF05 | Alta | Eu, como usuário do sistema, desejo receber  notificações de alerta para ser informado sobre informações e atualizações importantes. | 3 | 8 |
| US9 | RF04 | Alta | Eu como administrador, desejo gerar relatórios com dados meteorológicos coletados pelo sistema, para analisar informações climáticas e apoiar tomadas de decisão em situações de risco. | 3 | 5 |
| US10 | RF08 | Média | Eu como usuário do sistema, desejo visualizar guias explicativos sobre os parâmetros meteorológicos, para entender o significado das medições apresentadas. | 3 | 5 |

<br>

## ☑️ Entrega

Veja a entrega da terceira sprint a seguir:


**MVP da Sprint 3**

> <a href=''>Vídeo do Projeto</a>

<br>

## 📈 Métricas do Time

O acompanhamento de atividades, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe, onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo, incluindo as atividades desenvolvidas e seus responsáveis.


---
