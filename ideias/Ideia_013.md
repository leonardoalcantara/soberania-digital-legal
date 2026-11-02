# Ideia 013 — Representante legal e domicílio no país

**Bloco:** B — instituições e sanções
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Plataforma que atua no Brasil sem estabelecimento aqui precisa ter **domicílio** e **representante legal**
com poderes para responder a autoridades. Não é exigência de instalação de empresa: é exigência de **alguém
citável** em território nacional.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| Chile | PL 18.362-19, arts. 1º e 2º | Plataformas com mais de 200 mil usuários ou receita acima de 5.000 UTM: domicílio, representante legal e inscrição em registro público |
| União Europeia | DSA, art. 13 | Prestador sem estabelecimento na UE deve designar representante legal em um Estado-membro |
| Brasil | Lei 9.504/1997, art. 57-C, § 3º | Impulsionamento eleitoral só pode ser contratado com provedor com sede, filial ou representante no País |

### Chile — o modelo com consequência processual

> **Art. 1º:** "…deverão ter domicílio no Chile e designar um representante legal também com domicílio em
> território nacional e inscrever-se no Registro de Plataformas habilitado, o qual será público e de livre
> acesso."
>
> **Art. 2º:** "O representante legal da plataforma digital estará habilitado para receber notificações
> judiciais e administrativas, dar cumprimento a requisições do Ministério Público e dos tribunais de
> justiça, e responder ante a autoridade competente. **Responderá solidariamente com a plataforma** pelas
> obrigações que emanam desta lei."

Fonte: `fontes/America-Latina/2026-chile-boletin-18362-19-projeto.pdf`

**Dois elementos que fazem a diferença:** o registro é **público** (permite saber quem controla a
plataforma) e a responsabilidade do representante é **solidária**.

### União Europeia — o modelo mínimo

DSA, art. 13: prestadores intermediários sem estabelecimento na União que ofereçam serviços no território
devem designar, por escrito, pessoa física ou jurídica como representante legal em um Estado-membro onde
ofereçam o serviço.

Fonte: `fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf`

**É o modelo mais enxuto:** exige representante, mas não exige domicílio nem registro público.

### Brasil — a exigência parcial que já existe

Lei 9.504/1997, art. 57-C, § 3º, exige que o impulsionamento eleitoral seja contratado com provedor com
sede, filial, sucursal, escritório, estabelecimento ou **representante legalmente estabelecido no País**.

Fonte: `fontes/Brasil/1997-lei-9504-Lei das Eleições - texto.md`

**Limite:** vale só para contratar impulsionamento eleitoral, não para a operação da plataforma.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Lei 9.504, art. 57-C, § 3º** — representante no País para contratar impulsionamento eleitoral.
- **STF, RE 1037396 (Tema 987), item 11** — a tese fixada em 26/06/2025 determina que "os provedores de
  aplicações de internet com atuação no Brasil devem **constituir e manter sede e representante no país**",
  com plenos poderes para (a) responder nas esferas administrativa e judicial; (b) prestar informações às
  autoridades sobre funcionamento, moderação, relatórios e regras de perfilamento e publicidade; (c)
  cumprir determinações judiciais; e (d) responder e cumprir penalizações, multas e afetações financeiras.
  O representante deve ser, necessariamente, **pessoa jurídica com sede no País**.
  Fonte: `fontes/Brasil/2025-stf-tese-re-1037396-art19-marco-civil.pdf`
- **Marco Civil, art. 11, § 2º** — sujeição à lei brasileira de empresa sediada no exterior que oferte
  serviço ao público brasileiro. É **jurisdição declarada**, sem exigência de representante.
- **Código Civil, art. 1.138** — representação de pessoa jurídica estrangeira, sem regra específica para
  plataformas.

**Falta:**

1. **Exigência em lei.** O dever existe hoje **por tese judicial**, com efeitos modulados (item 14) e
   vigência expressamente provisória ("enquanto não sobrevier nova legislação", item 2) — mas não há
   dispositivo legal que o preveja.
2. **Registro público de plataformas**, com dados de controle societário.
3. **Responsabilidade solidária do representante.** A tese exige que ele "responda e cumpra eventuais
   penalizações, multas e afetações financeiras", mas não qualifica essa responsabilidade como solidária.
4. **Prazo e sanção próprios** pelo descumprimento do dever de constituir sede e representante.

---

## 4. O que a comparação revela

**É a proposta de menor custo político e maior efeito prático do bloco.** Não proíbe nada, não regula
conteúdo, não interfere em modelo de negócio — apenas resolve o problema de **quem se cita** quando a
plataforma descumpre uma ordem.

**A vantagem sobre o Marco Civil:** o art. 11, § 2º diz que a lei brasileira se aplica; não diz **a quem**
se notifica. A consequência é o litígio internacional (carta rogatória, cooperação jurídica).

**O STF já preencheu parte dessa lacuna** — o item 11 da tese do Tema 987 resolve o "a quem se notifica".
O que a comparação mostra é que os outros países resolveram isso **em lei**: o art. 13 do DSA
(`fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf`), o art. 54 do AI Act, que exige representante
autorizado para fornecedores de modelos de uso geral estabelecidos fora da UE
(`fontes/UE/2024-regulamento-ue-2024-1689-ai-act.pdf`), e o art. 36 da Lei-Quadro coreana, que cria o
"agente doméstico" e presume que o representado cometeu a violação praticada pelo agente
(`fontes/Coreia/2025-framework-act-ai-EN.pdf`). Depender de tese judicial significa depender de composição
de tribunal.

**Onde o Chile vai além:** o registro público. Saber quem controla a plataforma é informação que o Brasil
não tem — nem sobre controle societário, nem sobre representação.

**Custo:** baixo para a plataforma (designar alguém é barato) e alto para o Estado (ganha um citável).

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Limiar** | todas × acima de X usuários (Chile: 200 mil) | Sem limiar, alcança serviço pequeno e cria barreira |
| **Registro público** | previsto (Chile) × não (UE) | O registro é o que dá transparência de controle |
| **Responsabilidade do representante** | solidária (Chile) × simples × nenhuma | Solidária dá eficácia e aumenta resistência do setor |
| **Quem se habilita** | pessoa física × pessoa jurídica | Pessoa física é mais simples e mais frágil |
| **Consequência da ausência** | multa × bloqueio × proibição de operar | Proibir operar é a sanção mais forte e mais litigiosa |

---

## 6. Lacunas de pesquisa

1. Não há, no acervo, a **Lei 5651 turca** consolidada — ela exige representante no país e é o precedente
   mais antigo do gênero.
2. Não verifiquei como o Chile define "presença significativa" para plataformas que já têm filial.
3. Não há, no acervo, dado sobre quantas plataformas operam no Brasil sem representante.

---

## 7. Perguntas abertas

1. Há limiar de porte, ou a exigência vale para toda plataforma?
2. O representante responde **solidariamente** ou apenas recebe notificações?
3. O registro é público, com dados de controle societário, ou apenas cadastro interno?
