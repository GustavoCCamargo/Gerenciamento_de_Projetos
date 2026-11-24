# Registro de riscos
Original: [riscos, qualidade e comunicação](originais/riscos-qualidade-comunicacao.pdf), Tabela 1.
| Risco | Resposta | Realizado | Avaliação |
| --- | --- | --- | --- |
| R1 Comunicação ESP32/API | Mitigar com testes incrementais | Integração demonstrada; falhas de rede limitam operação | Parcial; ocorrência específica ND |
| R2 Requisitos/regras | Validar com orientador | Regras implementadas; retrabalho real não medido | ND |
| R3 Perda de código/dados | Git e backups | Repositório informado; perdas não documentadas | ND |
| R4 Telegram | Isolar módulo e testar alternativa | OTP demonstrado; bloqueio não documentado | Mitigação técnica parcial |
| R5 Hardware/laboratório | Agendar e simular | Protótipo sem trava; causa do atraso não comprovada | Parcial |

Probabilidade/impacto originais: R1 média/alto; R2 média/alto; R3 baixa/alto; R4 média/médio; R5 média/alto.

Riscos monetários do orçamento (numeração própria): RFID incompatível 30% × R$ 560 = R$ 168; Telegram 20% × R$ 700 = R$ 140; atraso de componentes 40% × R$ 875 = R$ 350; queima ESP32 50% × R$ 480 = R$ 240. Nenhum uso de reserva comprovado. Risco adicional identificado retrospectivamente: perda de conectividade impede acesso e auditoria offline (TCC, §6).
