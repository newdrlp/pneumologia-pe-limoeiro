# Roteiro de migração - limoeiro

Este repositório replica o padrão validado no piloto saude.

## Modelo

Um repositório separado por clínica, porque GitHub Pages aceita um único CNAME por site.

## DNS no Wix

| Subdomínio | Tipo | Valor |
| --- | --- | --- |
| limoeiro | CNAME | newdrlp.github.io |

## Validação após DNS

1. Abrir http://limoeiro.pneumologia-pe.com.br/ e confirmar Server: GitHub.com.
2. Aguardar HTTPS/SSL do GitHub Pages.
3. Abrir https://limoeiro.pneumologia-pe.com.br/.
4. Abrir https://limoeiro.pneumologia-pe.com.br/pre-atendimento/.
5. Fazer envio controlado e confirmar chegada no Apps Script/planilha.