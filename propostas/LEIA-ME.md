# Propostas

Os textos legislativos do projeto, um por instrumento. O nome diz o **tipo**, o **número** e o **assunto** — não a onda em que foram escritos, porque a onda é método de trabalho, não documento.

| Arquivo | Onda | Instrumento | Altera | Ideias | Depende de |
|---|---|---|---|---|---|
| [res-01](res-01-anpd-eca-digital.md) | **0** | Resolução | ECA Digital, arts. 17 e 30 | 008, 020, 022 (menores) | — |
| [pl-01](pl-01-marco-civil-devido-processo.md) | **1** | PL | Marco Civil, arts. 7º, 11, 19-A, 21-A a 21-E, 22-A | 001, 013, 014, 015, 022 | — |
| [pl-05](pl-05-lei-9504-impulsionamento-e-prazos.md) | **1** | PL | Lei 9.504, arts. 57-C, 57-J e 57-K | 003, 022 (eleitoral) | pl-01 |
| [pl-02](pl-02-marco-civil-transparencia-e-auditoria.md) | **2** | PL | Marco Civil, Capítulo IV-A (23-A a 23-I) e art. 12 | 004, 009, 020, 023 | — |
| [pl-04](pl-04-marco-civil-dados-de-treinamento-e-gradacao.md) | **2** | PL | Marco Civil, art. 23-I e art. 12, §§ 1º a 3º | 017, 025 | pl-02 e pl-06 |
| [pl-07](pl-07-mercados-digitais.md) | **2** | PL | lei nova | 018 | pl-06 |
| [pec-01](pec-01-soberania-digital.md) | **3** | PEC | CF, arts. 5º, 21, 22, 170 e 220 | 001, 022, 023, 024 | — |
| [pl-03](pl-03-marco-civil-habilitacao.md) | **3** | PL | Marco Civil, Capítulo IV-B (23-K a 23-O) e art. 12, V | 007 | pl-01 e pl-06 |
| [pl-06](pl-06-lgpd-competencias-e-governanca-anpd.md) | **3** | PL | LGPD, arts. 55-A, 55-C e 55-J | 006 + D.1 | — |
| [pl-08](pl-08-soberania-digital-dano-eleitoral.md) | **3** | PL | lei nova | 024, 025 | pec-01 e pl-06 |

**pl-06 é a lei habilitante** dos demais: sem ela, os arts. 23-H do pl-02, 9º do pl-07 e 8º do pl-08 apontam para órgão sem competência. Por isso, apesar de ser da Onda 3, ela precisa andar antes ou junto.

## Por que não há pastas por onda

Onda é **calendário**, não classificação. E calendário muda — já mudou duas vezes neste projeto: **008** e **012** foram encerradas sem extensão, e **011** passou da Onda 2 para a Onda 1.

Pasta que codifica classificação mutável precisa ser reorganizada a cada mudança, e cada reorganização quebra os links que apontam para ela. É o mesmo problema que fixar "16 de agosto" numa lei: o número envelhece, e quem esquece de atualizar cria dois regimes em vigor.

Instrumento não muda: o Marco Civil será o Marco Civil depois de qualquer reordenação.

**Onde a onda continua visível:** a coluna acima, a seção 6 do [plano de execução](../ideias/plano-de-execucao.md), e a lista abaixo. Atualizar uma célula é mais barato que mover arquivos.

## A mesma coisa, vista por onda

- **Onda 0 — sem passar pelo Congresso:** `res-01`
- **Onda 1 — emendas de baixa fricção:** `pl-01`, `pl-05`
- **Onda 2 — extensões de escopo:** `pl-02`, `pl-04`, `pl-07`
- **Onda 3 — a Linha A:** `pec-01`, `pl-03`, `pl-06`, `pl-08`
- **Sem onda:** `NOTAS-DE-ARQUITETURA` — é justificativa, não proposta

## O problema que a normalização expôs

**Quatro projetos alteram o Marco Civil** — pl-01, pl-02, pl-03 e pl-04. Isso significa quatro tramitações sobre a mesma lei, com numeração que colide: os arts. 21-A a 21-E de um, o Capítulo IV-A de outro, o Capítulo IV-B de um terceiro, e o art. 12 alterado por dois.

A normalização por instrumento mostrou o que a divisão por onda escondia. Há duas saídas, e é decisão sua:

1. **Consolidar os quatro num único PL do Marco Civil**, com os capítulos em ordem e o art. 12 alterado uma vez só. Ganha-se coerência e uma tramitação; perde-se a possibilidade de aprovar por partes, e um projeto maior é mais vulnerável a emendas.
2. **Manter os quatro separados** e ordenar a tramitação: pl-01 primeiro (traz a definição de provedor e o art. 11, § 5º), pl-02 depois (Capítulo IV-A), pl-03 e pl-04 por último, porque ambos dependem dos anteriores.

## Estado

- **Uma proposta pode ser editada hoje**, sem o Congresso: `res-01`.
- **Duas dependem só de si mesmas:** `pl-01` e `pl-06`.
- **Uma é o alicerce:** `pec-01`.
- **Quatro dependem de outra proposta** para funcionar por inteiro — a coluna "Depende de" mostra qual.

## Notas de fundamentação duplicadas

`pl-01` e `pl-05` compartilham as mesmas notas, e `pl-04` e `pl-07` também. A duplicação é proposital: cada projeto precisa circular com sua justificativa completa, e os dois pares foram redigidos juntos.
