# Ideia 010 — Rotulagem de conteúdo sintético

**Bloco:** C — proteção de menores e conteúdo sintético
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Todo conteúdo gerado ou manipulado por IA — texto, imagem, áudio, vídeo — deve vir **marcado**. Não é proibição de produzir: é obrigação de identificar.

Duas camadas, que os ordenamentos tratam separadamente e que o texto precisa distinguir:

1. **Rótulo explícito** — visível ao usuário ("conteúdo gerado por IA").
2. **Rótulo implícito** — metadado no arquivo, legível por máquina, que sobrevive à cópia.

A camada 2 é a que permite fiscalização em escala; a camada 1 é a que informa o público.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| China | Medidas de rotulagem (CAC e outros, vigência 01/09/2025) | Rótulo explícito por tipo de mídia + rótulo implícito em metadado; vedação de remover ou contornar |
| Índia | IT Amendment Rules 2026 (vigência 20/02/2026) | Categoria "informação sinteticamente gerada": rótulo proeminente + metadado com identificador único permanente |
| União Europeia | AI Act, art. 50 | Marcar conteúdo sintético em formato legível por máquina e revelar deepfake |
| Brasil | Res. TSE 23.755/2026, art. 9º-B | Rótulo explícito, destacado e acessível em propaganda eleitoral |

### China — o modelo completo

> **Art. 4º:** o provedor de serviços de geração ou síntese deve acrescentar o rótulo **explícito** ao conteúdo gerado ou sintetizado — no caso de texto, aviso no início, no fim ou em local adequado; no de áudio, por locução; no de imagem, em local apropriado; no de vídeo, no início ou no fim.
>
> **Art. 5º:** deve acrescentar o rótulo **implícito**, em metadados do arquivo.
>
> **Art. 6º:** o provedor de serviços de distribuição deve verificar o rótulo implícito e, quando o usuário publicar conteúdo gerado, acrescentar o rótulo explícito na interface de publicação.

Fonte: `fontes/China/2025-medidas-rotulagem-ia-pt.md`

E a vedação de contorno, art. 10: é proibido remover, alterar, falsificar ou ocultar o rótulo, **ou fornecer ferramentas para tanto**.

### Índia — o identificador único

As Regras de 2026 criam a categoria de "informação sinteticamente gerada" — áudio, imagem ou vídeo criados artificial ou algoritmicamente — e exigem rótulo proeminente e perceptível, além de **metadados de proveniência permanentes com identificador único** que não possam ser removidos ou suprimidos.

Fonte: `fontes/India/2026-it-amendment-rules-sgi.pdf`

**Detalhe relevante:** a definição indiana **exclui texto** — só alcança áudio, imagem e vídeo. É uma
escolha de escopo que o texto brasileiro precisa enfrentar.

### União Europeia — art. 50 do AI Act

Impõe transparência a provedores e deployers: informar que se interage com sistema de IA, marcar conteúdo sintético em formato legível por máquina e revelar deepfake.

Fonte: `fontes/UE/2024-regulamento-ue-2024-1689-ai-act.pdf` (art. 50)

**Duas alterações posteriores, que o texto consolidado não mostra:**

1. O Regulamento (UE) 2026/1744 (Digital Omnibus) **reescreveu o § 7º**: a Comissão deixa de adotar regras harmonizadas como regra geral e passa a **incentivar códigos de prática**, com ato de execução apenas residual, se o código for considerado inadequado. É deslocamento de instrumento — de norma para autorregulação supervisionada.
2. Sistemas já colocados no mercado antes de 02/08/2026 têm prazo até **02/12/2026** para cumprir o § 2º (prazo de quatro meses).

Fonte: `fontes/UE/2026-regulamento-ue-2026-1744-omnibus-ia.pdf` (art. 1º, ponto 20, e ponto 39, alínea "b", que insere o art. 111, § 4º; considerando 38)

### Brasil — a regra eleitoral

Resolução TSE nº 23.755/2026, art. 9º-B: uso de conteúdo sintético em propaganda eleitoral impõe ao responsável o dever de informar, de modo explícito, destacado e acessível, que o conteúdo foi fabricado ou manipulado e qual tecnologia foi utilizada.

Fonte: `fontes/Brasil/2026-resolucao-tse-23755-Resolução TSE 23.755 - texto.md`

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Res. TSE 23.755/2026, art. 9º-B** — rotulagem de conteúdo sintético **em propaganda eleitoral**, com remoção imediata em caso de descumprimento.
- **ECA Digital (Lei 15.211/2025)** — deveres de informação sobre uso de IA em serviços acessíveis a menores (texto arquivado, verificar artigo específico).
- **Marco Civil, art. 7º** — direito à informação sobre coleta e uso de dados, que não alcança o conteúdo sintético.

**Falta:**

1. **Rotulagem fora do período eleitoral.** Não há obrigação geral.
2. **Rótulo em metadado.** O direito brasileiro só trata do rótulo visível.
3. **Vedação de remover ou contornar o rótulo** — o dispositivo mais importante do modelo chinês.
4. **Dever do distribuidor** de verificar e propagar o rótulo.
5. **Definição de "conteúdo sintético"** no direito brasileiro.

---

## 4. O que a comparação revela

**A rotulagem é o item com maior convergência do acervo** — quatro ordenamentos, quatro soluções. A divergência é toda de escopo e de camada:

- **Escopo:** a Índia exclui texto; a China inclui tudo; a UE alcança os dois.
- **Camada:** só a China e a Índia exigem metadado.
- **Contorno:** só a China pune quem fornece ferramenta para remover o rótulo.

**O problema que o texto precisa resolver:** rótulo visível sozinho é decorativo — o conteúdo sai da
plataforma e perde a marca. Só a camada de metadado sobrevive à cópia, mas depende de padrão técnico e de cooperação das plataformas.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Escopo de mídia** | tudo (China) × só áudio/imagem/vídeo (Índia) | Incluir texto é mais completo e mais difícil de aplicar |
| **Camadas** | só explícita × explícita + metadado | Metadado é o que permite auditoria |
| **Quem rotula** | gerador × distribuidor × ambos | O distribuidor é quem tem contato com o público |
| **Vedação de contorno** | prevista × ausente | Sem ela, o rótulo é removível e a norma simbólica |
| **Sanção** | não prevista × multa × remoção | A remoção imediata é a sanção adotada no Brasil eleitoral |

---

## 6. Lacunas de pesquisa

1. Não há **padrão técnico brasileiro** de metadado (C2PA ou equivalente) — a norma precisaria remeter a um.
2. Não verifiquei se a Índia pune o gerador ou só o intermediário.
3. Não há, no acervo, avaliação de eficácia das regras chinesas depois de um ano de vigência.

---

## 7. Perguntas abertas

1. Texto entra no escopo ou fica de fora, como na Índia?
2. O dever recai sobre quem gera ou sobre quem distribui?
3. O Brasil adota padrão técnico aberto de metadado, ou deixa a definição para o regulador?
