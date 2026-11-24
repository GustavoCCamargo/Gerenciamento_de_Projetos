# Log de mudanças — reconstrução retrospectiva em 24/11/2026
| ID | Mudança | Evidência | Classificação |
| --- | --- | --- | --- |
| M01 | Arduino UNO → ESP32 | Orçamento, §4.7; 40 h reportadas | Mudança técnica retroativa; aprovação ND |
| M02 | Fechadura prevista → não integrada | Orçamento, Tabela 2; TCC, §6 | Redução de escopo retroativa; aprovação ND |
| M03 | Validação em ambiente real → testes com um dispositivo | Pré-banca, §4.5; TCC, §6 | Mudança de abordagem retroativa; aprovação ND |

Todas registradas retrospectivamente; datas de decisão, responsáveis pela aprovação e hashes ND. Repositório: https://github.com/GustavoCCamargo/IdentIFica---TCC. Não há evidência de scope creep ou gold plating; nenhuma das três pode ser chamada de mudança formal aprovada.

## Solicitação M02 — minuta retrospectiva
Descrição: manter coleta, autenticação, autorização e indicação do resultado sem acionamento da fechadura. Justificativa observada: a versão final registra ausência da trava; motivo exato precisa ser confirmado. Alternativas analisadas agora: integrar a trava antes da defesa; simular o acionamento; adiar a integração. Impacto: reduz escopo físico e capacidade de validação; pode reduzir esforço de integração, mas horas e economia ND; aumenta risco de generalização indevida. Resultado documentado: protótipo sem fechadura. Decisão formal e aceite: pendentes. Evidência: TCC §5.4 e §6, orçamento Tabela 2. Inserir link de issue/commit real após verificar histórico.
