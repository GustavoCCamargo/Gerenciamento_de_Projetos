# EAP — pacotes preservados do orçamento
| Código | Pacote | PERT (h) | Mão de obra (R$) |
| --- | --- | --- | --- |
| 1.1 | Levantamento e EAP | 25,8 | 903,00 |
| 1.2 | Firmware ESP32 e RFID | 65,0 | 2.275,00 |
| 1.3 | API REST e Telegram | 85,0 | 2.975,00 |
| 1.4 | Interface Web React | 58,0 | 2.030,00 |
| 1.5 | Testes e bancada | 47,5 | 1.662,50 |
| 1.6 | Redação e documentação | 51,7 | 1.809,50 |
| 1.7 | Preparação para defesa | 31,0 | 1.085,00 |
Fonte: orçamento, Tabela 1. A decomposição original anterior não está anexada.

## Coerência (reconstrução)
| Pacote | Rede | Crítico? | R$ | Risco | Qualidade |
| --- | --- | --- | --- | --- | --- |
| 1.2 Firmware | Firmware / integração | Provável | 2.275,00 | Falha ESP32/API | Autenticação correta |
| 1.3 API | API REST | Sim, qualitativo | 2.975,00 | Telegram / regras | Requisitos e auditoria |
| 1.4 Web | Aplicação web | Provável | 2.030,00 | Retrabalho de regras | Requisitos funcionais |
| 1.5 Testes | Integração e testes | Sim, qualitativo | 1.662,50 | Hardware/laboratório | Autenticação e auditoria |
| 1.6 Redação | Escrita final | Sim, qualitativo | 1.809,50 | Prazo (não vinculado) | Artigo e documentação |

Custos são de mão de obra; materiais e reservas não foram rateados por pacote. O caminho crítico é qualitativo, não CPM calculado.
