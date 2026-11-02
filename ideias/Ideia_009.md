# Ideia 009 — Dever de cuidado sobre o desenho do serviço

**Bloco:** C — proteção de menores e conteúdo sintético
**Origem:** proposta nova (não estava na lista original)
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Em vez de proibir condutas específicas, a lei impõe à plataforma um **dever geral de identificar, avaliar e mitigar riscos** de dano decorrentes do funcionamento do serviço — e a obriga a **documentar** o que fez.

É a arquitetura oposta à lista fechada de vedações: transfere à plataforma a obrigação de conhecer o próprio produto.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| Reino Unido | Online Safety Act 2023, art. 9º | Dever de realizar **avaliação de risco de conteúdo ilegal** "adequada e suficiente", mantê-la atualizada e refazê-la antes de mudança significativa de design |
| Austrália | Projeto Digital Duty of Care Bill 2026, Anexo 2 | Novo **dever de cuidado** na Online Safety Act, com avaliação de risco (s. 26A) e medidas efetivas |
| União Europeia | Proposta EU KIDS Act (COM(2026) 681) | Regras de **segurança por desenho** para serviços suscetíveis de acesso por menores |

### Reino Unido — o modelo mais detalhado

Online Safety Act 2023, art. 9º:

> "Esta seção estabelece os deveres relativos a avaliações de risco que se aplicam a todos os serviços regulados de usuário-para-usuário."
>
> "Dever de realizar uma **avaliação de risco de conteúdo ilegal adequada e suficiente**, no momento previsto no Anexo 3."
>
> "Dever de adotar **passos apropriados para manter atualizada** a avaliação de risco de conteúdo ilegal…"
>
> "Antes de fazer qualquer alteração significativa em qualquer aspecto do **design ou operação** do serviço, o dever de realizar nova avaliação de risco…"

Fonte: `fontes/Reino-Unido/2023-online-safety-act.md` (art. 9º)

**O ponto central:** o dever não recai sobre o conteúdo publicado, mas sobre o **desenho e a operação**
do serviço. E a avaliação de risco é documento exigível, não diagnóstico interno.

### Austrália — o dever genérico

O projeto de 08/09/2026 insere na Online Safety Act um novo **dever de cuidado digital** (Anexo 2), com avaliações de risco e exigência de medidas efetivas, e alcança expressamente serviços de IA e buscadores, não apenas redes sociais.

Fonte: `fontes/Australia/my-feed-my-way/exposure-draft-online-safety-amendment-digital-duty-of-care-bill-2026-september2026.pdf`

### União Europeia — segurança por desenho

A proposta do EU KIDS Act incorpora a lógica de *safety by design*: o serviço deve ser concebido de modo a reduzir risco, não apenas moderado depois.

Fonte: `fontes/UE/2026-proposta-ue-eu-kids-act.pdf`

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Marco Civil, art. 19** — regime de responsabilidade do provedor por conteúdo de terceiro, baseado em ordem judicial específica. É responsabilidade **posterior ao dano**, não dever preventivo.
- **Marco Civil, art. 15** — guarda de registros de acesso a aplicações.
- **LGPD, arts. 46 a 48** — dever de segurança da informação e comunicação de incidente, mas só quanto a dados pessoais.
- **ECA Digital (Lei 15.211/2025), art. 8º, I** — dever de "realizar **gerenciamento de riscos** de seus recursos, funcionalidades e sistemas e de seus impactos direcionados à segurança e à saúde de crianças e de adolescentes", com o detalhamento dos métodos e dos resultados nos relatórios semestrais (art. 31, VII). Fonte: `fontes/Brasil/2025-lei-15211-ECA-Digital - texto.md`

**Falta:**

1. **Dever geral de avaliação de risco de dano** pelo funcionamento do serviço. Não existe.
2. **Obrigação de documentar a avaliação** e mantê-la atualizada. Não existe.
3. **Dever de reavaliar antes de mudar o design** — é o dispositivo mais poderoso do modelo britânico e não tem equivalente brasileiro.
4. **Ponto de contato com o regulador** para apresentar a avaliação.

---

## 4. O que a comparação revela

**É a proposta com melhor arquitetura e pior fiscalização.** O dever de cuidado é genérico por desenho: funciona se houver regulador com capacidade técnica para ler avaliações de risco e contestá-las. O modelo britânico só funciona porque a Ofcom publica códigos de prática que dizem o que se espera.

**O que o Brasil precisaria junto:** um regulador com poder de exigir documentos e contratar perícia —
hoje, nenhum órgão brasileiro tem esse mandato sobre plataformas fora do período eleitoral.

**Risco jurídico:** dever genérico sem código de prática vira litígio sobre o que é "adequado e
suficiente". A recomendação técnica é acoplar o dever a **parâmetros publicados pelo regulador**, como a Ofcom faz.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Escopo do dever** | só menores × todos os usuários | Escopo amplo aumenta carga e litígio |
| **Objeto** | conteúdo × design e operação × ambos | O modelo britânico é design e operação |
| **Documento** | avaliação interna × documento entregue ao regulador | Entregar cria obrigação verificável |
| **Gatilho de reavaliação** | anual × antes de mudança significativa | O gatilho de mudança é o que impede inovação sem controle |
| **Parâmetro de aferição** | "adequado e suficiente" × código de prática publicado | Sem código, a norma é interpretada caso a caso |

---

## 6. Lacunas de pesquisa

1. **Não há, no acervo, os códigos de prática da Ofcom** — são eles que dão operacionalidade ao dever britânico.
2. O texto do Anexo 2 do projeto australiano não foi lido dispositivo a dispositivo — só a estrutura.
3. Lei 15.211/2025 (ECA Digital) não está arquivada, e ela provavelmente já cria deveres que se sobrepõem a um dever de cuidado geral.

---

## 7. Perguntas abertas

1. O dever alcança **todos os usuários** ou só menores?
2. A avaliação de risco é **entregue ao regulador** ou mantida internamente?
3. O texto fixa parâmetros de aferição ou remete a código de prática do regulador?
