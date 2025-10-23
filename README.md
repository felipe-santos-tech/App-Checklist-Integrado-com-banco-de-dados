# Checklist de Betoneiras – App Android em Produção

**Aplicativo corporativo em uso diário** para controle de entrada de **caminhões betoneira em processo de reforma**.  
**Integrado ao ERP via SQL Server** – elimina planilhas e gera relatórios em tempo real.

---

## Contexto Real
- **Empresa**: Convicta  
- **Uso**: Logística industrial  
- **Impacto**: **+70% de agilidade** no processo de entrada/reforma  

---

## Tecnologias
| Tecnologia         | Uso |
|--------------------|-----|
| **Java**           | Lógica principal |
| **Android Studio** | IDE oficial |
| **SQL Server**     | Banco corporativo |
| **ERP (Delphi)**   | Integração legado |
| **JDBC**           | Comunicação direta com DB |
| **Firebase**       | Login + notificações (em breve) |

---

## Funcionalidades em Produção
- **Login por matrícula + QR Code**  
- **Seleção de modelo** de betoneira  
- **Checklist visual** com danos  
- **Relatório automático** para o comercial  
- **Gravação direta no SQL Server**  
- **Histórico completo** de reformas  
- **Integração com módulo de propostas**  

---

## Status do Projeto

| Tarefa                                      | Status |
|--------------------------------------------|--------|
| Login (matrícula + QR Code)                | Concluído |
| Seleção por modelo                         | Concluído |
| Checklist com itens danificados            | Concluído |
| Relatório automático                       | Concluído |
| Integração com SQL Server                  | Concluído |
| Histórico de checklists                    | Concluído |
| Módulo de propostas comerciais             | Concluído |

---

## Fluxo de Operação

Operador → App Android → JDBC → SQL Server → ERP (Delphi)
↓
Relatório automático ao comercial

## Projeto em produção – demonstra integração com sistemas legados, automação operacional e impacto real no negócio.
