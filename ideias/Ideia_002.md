# Ideia 002 — Teto de impulsionamento e piso de conteúdo de contas seguidas

**Bloco:** A — desenho da distribuição de conteúdo
**Origem:** ideia original 2
**Estado:** proposta de trabalho

---

## 1. Formulação

> "As linha do tempo do usuário, seja na modalidade cronológica ou na modalidade priorizada por algoritmo, deve apresentar ao usuário prioritariamente conteúdo postado pelos outros usuários que ele decidiu seguir. Para tal, a proporção deve ser de pelo menos 80% de conteúdo não impulsionado de usuários que ele segue, e 20% de conteúdo impulsionado. Caso se esgotem as postagens elegíveis de conteúdo não impulsionado é facultado a plataforma preencher a linha do tempo com mais conteúdo impulsionado."
>
> "A plataforma não pode sugerir conteúdo que não seja orgânico ou impulsionado e nem perfis a serem seguidos."

Duas regras distintas, com naturezas jurídicas diferentes:

1. **Quota de composição** — percentual mínimo de conteúdo de contas seguidas e máximo de impulsionado.
2. **Vedação de recomendação de terceiros** — proíbe sugerir conteúdo de quem não se segue e sugerir perfis.

A segunda é mais restritiva e mais fácil de fiscalizar: "não sugerir" é verificável; "80%" exige auditoria de feed.

---

## 2. Como aparece em outros ordenamentos

**Não localizei quota de composição de feed em nenhuma das 11 jurisdições do acervo.** A regra brasileira seria inédita. O que existe é o inverso — normas que **autorizam** publicidade no feed puro:

| Onde | Dispositivo | O que diz |
|---|---|---|
| Austrália | Determinação de 2026, seção 6, item 6 | "Um feed de contas seguidas **pode incluir material publicitário**, inclusive de conta que o usuário não segue" |
| União Europeia | DSA, art. 26 | Impõe transparência sobre anúncios, não limite de quantidade |
| União Europeia | DSA, arts. 27 e 38 | Tratam da opção de recomendação, não da proporção do feed |

Fonte das duas primeiras: `fontes/Australia/my-feed-my-way/draft-online-safety-user-empowerment-tools-determination-2026.md` e `fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf`.

### O único precedente de quota que existe — e é de imprensa, não de feed

Lei 9.504/1997, art. 43:

> "São permitidas, até a antevéspera das eleições, a divulgação paga, na imprensa escrita, e a reprodução na internet do jornal impresso, de até 10 (dez) anúncios de propaganda eleitoral, por veículo, em datas diversas, para cada candidato…"

Fonte: `fontes/Brasil/1997-lei-9504-Lei das Eleições - texto.md`

É quota de **quantidade absoluta por veículo**, não de proporção no feed. Serve como precedente de técnica (o legislador brasileiro já aceita limitar volume de propaganda paga), não de mecanismo.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Lei 9.504/1997, art. 43** — limite de anúncios pagos na imprensa escrita.
- **Lei 9.504/1997, art. 57-C** — veda propaganda paga na internet, ressalvado o impulsionamento por partidos, coligações e candidatos. Ou seja: **a lei atual regula quem pode impulsionar, não quanto.**
- **Marco Civil, art. 9º** — neutralidade de rede, que não alcança a composição do feed.

**Falta:**

1. **Qualquer limite percentual** de conteúdo impulsionado na linha do tempo.
2. **Qualquer direito a receber todo o conteúdo de quem se segue** — hoje a plataforma filtra livremente, inclusive descartando postagens de contas seguidas.
3. **Vedação de recomendação de terceiros** fora do período eleitoral.
4. **Métrica auditável.** Não há definição legal de "conteúdo impulsionado" nem obrigação de a plataforma declarar a proporção praticada.

---

## 4. O que a comparação revela

**É a proposta mais original do conjunto** — e a de maior risco. Três razões:

1. **Nenhum país pesquisado impõe quota de composição de feed.** Não há evidência de que funcione, nem de como se fiscaliza.
2. **A Austrália decidiu o contrário no ponto específico:** no feed "puro", a publicidade é permitida expressamente. Reguladores que enfrentaram o problema escolheram dar a opção ao usuário, não compor o feed por lei.
3. **A quota transfere para o legislador uma decisão editorial.** Definir que 80% do que uma pessoa vê deve vir de quem ela segue é uma escolha sobre o que é uma rede social — não apenas sobre segurança.

**Onde a proposta é mais forte:** o segundo parágrafo. Proibir **sugestão de conteúdo de terceiros e de perfis a seguir** é regra simples, verificável e sem precedente — e ataca a mesma prática (o feed "descoberta") sem precisar de quota.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Percentual** | 80/20 (proposta) × outro | Qualquer número é arbitrário sem dado sobre a composição real dos feeds hoje |
| **Base de cálculo** | por sessão × por dia × por usuário | Muda completamente a fiscalização e a possibilidade de burla |
| **Conteúdo de terceiros** | vedado (proposta) × permitido com rótulo | A vedação é mais simples de verificar que a quota |
| **Publicidade** | 20% do feed × fora da conta | Se a publicidade não conta na quota, a plataforma pode inflar anúncios |
| **Esgotamento** | permite completar com impulsionado (proposta) | Cria a válvula de escape que esvazia a regra nos perfis com pouca atividade |

---

## 6. Lacunas de pesquisa

1. **Nenhum dado no acervo sobre a composição real dos feeds** no Brasil — sem isso, o percentual de 80% não tem base empírica.
2. Não verifiquei se a Austrália, ao permitir publicidade no feed puro, fixou algum limite.
3. Não há, no acervo, estudo de fiscalização de quota de feed em nenhum país.

---

## 7. Perguntas abertas

1. A quota vale por **sessão** ou por **período**? Sessão é o que o usuário percebe; período é o que se audita.
2. Publicidade conta **dentro** dos 20% ou fora da conta?
3. Vale a pena manter a quota, ou basta a vedação de sugestão de terceiros — que é mais simples e não exige número arbitrário?
