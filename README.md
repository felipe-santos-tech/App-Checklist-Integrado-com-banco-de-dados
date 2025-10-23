# Checklist de Equipamentos – App Android em Produção

**Aplicativo corporativo em produção** para controle de entrada de equipamentos em processos industriais.  
**Integrado ao ERP (Delphi/Pascal) via SQL Server** – usado diariamente em operações logísticas.

---

## Objetivo do Projeto
Automatizar o **registro de entrada de equipamentos**, eliminando planilhas manuais e gerando **relatórios em tempo real** para o setor comercial.

---

## Tecnologias Utilizadas
| Tecnologia         | Uso |
|--------------------|-----|
| **Java**           | Lógica do app |
| **Android Studio** | IDE oficial |
| **SQL Server**     | Banco corporativo (SSMS) |
| **ERP (Delphi)**   | Integração legado |
| **Retrofit**       | Chamadas REST |
| **Room**           | Cache offline |
| **Firebase**       | Login e notificações (em implementação) |

---

## Funcionalidades em Produção
- **Login seguro** por matrícula + QR Code  
- **Seleção de modelo** de equipamento  
- **Checklist visual** com marcação de danos  
- **Geração automática de relatório** para o comercial  
- **Integração direta com SQL Server**  
- **Histórico completo** de checklists  
- **Módulo de propostas comerciais** (ERP)  

---

## Status do Projeto

| Tarefa                                      | Status |
|--------------------------------------------|--------|
| Login (matrícula + QR Code)                | Concluído |
| Seleção por modelo de equipamento          | Concluído |
| Checklist com itens danificados            | Concluído |
| Relatório automático para comercial        | Concluído |
| Integração com SQL Server (ERP)            | Concluído |
| Histórico de checklists                    | Concluído |
| Módulo de propostas comerciais             | Concluído |
| Firebase (login + notificações)            | Em andamento |

---

## Arquitetura (Clean + MVVM)
