# Dossiê de gerenciamento do IdentIFica
ND = não disponível nos anexos. Os PDFs originais pertinentes foram preservados em originais/. O TAP e a rede são reconstruções, não artefatos aprovados; substituir pelos originais se disponíveis. O orçamento M4 é simulação. Revise as interpretações, complete evidências e confirme autoria e aceite antes de entregar.

Repositório informado no TCC: https://github.com/GustavoCCamargo/IdentIFica---TCC

## Evidências e publicação
1. Obter TAP/EAP/rede originais do IdentIFica, datas reais, horas por pacote e gastos comprovados; validar status dos sete pacotes.
2. Localizar commits reais: `git log --all --date=short --format="%h %ad %s"` e `git log --all --oneline --grep="ESP32"`. Vincular cada alteração ao hash e à issue real. Não usar a data do commit como horas trabalhadas.
3. Anexar aceite do orientador e ata de defesa quando existentes.
4. Após revisão, copiar docs/gestao/ para o repositório; executar `git add docs/gestao` e `git commit -m "docs: consolida dossiê de gestão"`.
5. Identificar o commit histórico autêntico do plano. Executar `git tag -a baseline-v1 <hash-real> -m "Linha de base original"` apenas se existir e a tag ainda não existir. Se não existir, documentar lacuna; não criar tag retroativa falsa. Após aceite, `git tag -a encerramento -m "Versão final dos artefatos de gestão"`, `git push` e `git push origin --tags`.

As tags não foram criadas nem publicadas por este trabalho.
