# Ideia 004 — Transparência e auditabilidade dos algoritmos de priorização

**Bloco:** A — desenho da distribuição de conteúdo
**Origem:** ideia original 4 (enunciado incompleto no arquivo original: "A caixa preta…")
**Estado:** proposta de trabalho, com escopo reconstruído

---

## 1. Formulação

O enunciado original ficou em aberto. Pelo contexto das demais propostas, o objetivo é **tornar verificável** o que a plataforma faz na priorização: quais sinais usa, com que peso, e como isso pode ser conferido por alguém fora da empresa.

Duas leituras possíveis, com consequências muito diferentes:

1. **Abertura do código** — publicar o código dos sistemas de priorização.
2. **Acesso auditado** — documentação obrigatória ao regulador, acesso a dados para pesquisadores credenciados e dever de explicar ao usuário.

A primeira é inviável na prática: o comportamento vem do modelo treinado e dos dados, não do código, e a publicação cria vetor de manipulação. A segunda é a que existe no direito comparado.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| União Europeia | DSA, art. 27 | Dever de declarar os **parâmetros principais** do sistema de recomendação e as opções para o usuário modificá-los |
| União Europeia | DSA, art. 40 | **Acesso a dados** para o coordenador de serviços digitais, a Comissão e pesquisadores credenciados |
| União Europeia | DSA, art. 34 | **Avaliação de risco** obrigatória, documentada |
| Brasil | Res. TSE 23.755/2026, art. 125-B | **Plano de conformidade** com indicadores mensuráveis e prazos, como condição de credenciamento |

### União Europeia — DSA, art. 27

> "Prestadores de plataformas online que utilizem sistemas de recomendação devem indicar, em seus termos e condições, em linguagem clara e inteligível, os **principais parâmetros** utilizados em seus sistemas de recomendação, bem como quaisquer opções de que os destinatários do serviço disponham para modificar ou influenciar esses parâmetros principais."

Fonte: `fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf` (art. 27)

O art. 40 do mesmo regulamento vai além: cria **acesso a dados** para autoridades e para pesquisadores credenciados, sob condições — é o dispositivo que permite auditoria externa de verdade, e não apenas declaração.

### Brasil — o plano de conformidade do TSE

Resolução TSE nº 23.755/2026, art. 125-B:

> "Os provedores de aplicação de internet deverão, nos termos, prazos e diretrizes editados pela Presidência do Tribunal Superior Eleitoral, elaborar **plano de conformidade** destinado à prevenção e à mitigação de riscos à integridade do processo eleitoral…"

E o § 1º exige, no mínimo: deveres e medidas por dispositivo; **critérios e indicadores mensuráveis e periódicos**; prazos, resultados esperados e trajetória de alcance.

Fonte: `fontes/Brasil/2026-resolucao-tse-23755-Resolução TSE 23.755 - texto.md`

**É o modelo brasileiro mais próximo** — mas ele vale só no período eleitoral e é ato de tribunal, não lei.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **LGPD, art. 20, §§ 1º e 2º** — direito a informações claras sobre critérios de decisão automatizada e poder de a ANPD **realizar auditoria** quando oposto segredo comercial.
- **Marco Civil, art. 5º** — transparência como princípio, sem mecanismo.
- **Res. TSE 23.755/2026, art. 125-B** — plano de conformidade com indicadores, no período eleitoral.
- **Lei 14.129/2021, art. 3º, XXV** — preferência por padrões abertos no setor público.

**Falta:**

1. **Dever geral de declarar os parâmetros** de priorização — fora do período eleitoral, nada obriga.
2. **Acesso a dados para pesquisadores** — o Brasil não tem equivalente ao art. 40 do DSA.
3. **Auditoria externa de sistemas de recomendação** — a ANPD audita decisões automatizadas sobre dados pessoais, não a curadoria de conteúdo.
4. **Consequência pelo descumprimento** do dever de transparência.

---

## 4. O que a comparação revela

**A transparência algorítmica é o item com mais consenso internacional e menos eficácia comprovada.** Três jurisdições têm dispositivos; nenhuma tem histórico público de auditoria de priorização que tenha mudado produto.

**A distinção que o texto precisa fazer:** transparência **para o usuário** (linguagem clara, parâmetros)
é fraca — vira letra morta em termos de uso. Transparência **para o regulador e para pesquisadores** (acesso a dados) é a que produz efeito. O DSA separa as duas em artigos distintos; a proposta deveria fazer o mesmo.

**Onde o Brasil já tem o molde:** o art. 125-B do TSE. Plano documentado, indicadores mensuráveis, prazos. É a técnica que funciona e que já foi aceita por um tribunal brasileiro.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Objeto** | parâmetros do algoritmo × código × dados de treino | Só o primeiro é viável como dever legal |
| **Destinatário** | usuário × regulador × pesquisador credenciado | Muda o conteúdo da obrigação e o sigilo aplicável |
| **Acesso a dados** | inexistente × sob requisição × permanente | O permanente é o que permite pesquisa independente |
| **Confidencialidade** | segredo comercial absoluto × relativo (como LGPD, art. 20, § 2º) | O segredo absoluto esvazia a auditoria |
| **Sanção** | nenhuma × multa × condicionamento de credenciamento | O TSE condiciona ao credenciamento — modelo replicável |

---

## 6. Lacunas de pesquisa

1. **Não há no acervo nenhum registro de auditoria externa de sistema de recomendação** que tenha resultado em mudança de produto. A eficácia é presumida, não documentada.
2. Não verifiquei como o DSA define "pesquisador credenciado" (art. 40, § 8º) — é o ponto que decide se o acesso é real ou simbólico.
3. Não há, no acervo, análise do uso efetivo do art. 20 da LGPD em decisões automatizadas.

---

## 7. Perguntas abertas

1. A proposta é **transparência ao usuário** ou **acesso para auditoria**? São dois dispositivos.
2. Quem audita no Brasil: ANPD, órgão novo, ou pesquisadores credenciados?
3. O segredo comercial pode ser oposto? A LGPD permite opor e dá à ANPD o poder de auditar de ofício — esse desenho é replicável.
