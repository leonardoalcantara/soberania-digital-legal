# Ideia 008 — Verificação de idade (age assurance)

**Bloco:** C — proteção de menores e conteúdo sintético
**Origem:** proposta nova (não estava na lista original)
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

A plataforma deixa de poder confiar na **autodeclaração** de idade e passa a ser obrigada a usar mecanismo técnico de verificação. É a condição de eficácia de qualquer regra de idade mínima: sem verificação, a idade mínima existe no papel e não no produto.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| Austrália | *Online Safety Amendment (Social Media Minimum Age) Act 2024* | Dever de adotar "passos razoáveis" para impedir que usuário de idade restrita tenha conta; multa civil |
| União Europeia | Proposta EU KIDS Act (COM(2026) 681) | Quadro de *age assurance* proporcional e preservador da privacidade |
| EUA (Califórnia) | AB 1043 (Digital Age Assurance Act) | Sistemas operacionais e lojas emitem **sinal de idade** por faixa, a partir de 01/01/2027 |
| EUA (Texas) | SB 2420 (App Store Accountability Act) | Lojas de aplicativos verificam idade e colhem consentimento parental |

### Austrália — o modelo de dever, não de método

A lei não prescreve qual tecnologia usar. Impõe o resultado:

> **Seção 63D:** sanção civil por não adotar passos razoáveis para impedir que usuários de idade restrita tenham contas em plataformas de rede social de idade restrita.
>
> **"Usuário de idade restrita"**: criança australiana que não tenha atingido [a idade mínima].
>
> **Sanção civil:** 30.000 unidades de penalidade.

Fonte: `fontes/Australia/2024-online-safety-minimum-age.pdf`

**Escolha legislativa relevante:** a Austrália deixa o método em aberto e responsabiliza a plataforma pelo resultado. É mais flexível e mais difícil de fiscalizar.

### União Europeia — o modelo de quadro com salvaguardas

A proposta do EU KIDS Act trata verificação de idade como infraestrutura com critérios:

> A proposta estabelece um quadro claro de *age assurance*, com critérios e salvaguardas — inclusive regras de segurança por desenho e sistemas de verificação de idade proporcionais e preservadores da privacidade.

Fonte: `fontes/UE/2026-proposta-ue-eu-kids-act.pdf`

**Diferença em relação à Austrália:** a UE regula o **método** (proporcional, preservador da privacidade), não apenas o resultado.

### Califórnia e Texas — o modelo de infraestrutura

A AB 1043 desloca a verificação para **sistema operacional e loja de aplicativos**: em vez de cada plataforma verificar, o sistema emite um "sinal de idade" por faixa etária. O Texas faz o mesmo via loja, com consentimento parental.

Fontes: `fontes/EUA/2026-ca-ab1043-verificacao-idade.md` e `fontes/EUA/2026-tx-sb2420-app-store.md`

---

## 3. O que já existe no Brasil (e o que falta)

**O Brasil já tem a regra — e é mais exigente que a australiana.**

Lei nº 15.211/2025 (ECA Digital), art. 9º:

> "Os fornecedores de produtos ou serviços de tecnologia … deverão adotar medidas eficazes para impedir o seu acesso por crianças e adolescentes no âmbito de seus serviços e produtos. § 1º Para dar efetividade ao disposto no caput, deverão ser adotados **mecanismos confiáveis de verificação de idade a cada acesso** do usuário ao conteúdo, produto ou serviço …, **vedada a autodeclaração**."

Fonte: `fontes/Brasil/2025-lei-15211-ECA-Digital - texto.md`

**Diferença em relação à Austrália:** a lei brasileira exige verificação **a cada acesso** e veda expressamente a autodeclaração; a australiana exige "passos razoáveis" para impedir contas. A brasileira é mais rigorosa no método e, por isso, mais exposta ao argumento de proporcionalidade que derrubou a lei francesa.

**Falta:**

1. **Método harmonizado.** A lei brasileira veda autodeclaração, mas não define padrão técnico.
2. **Salvaguarda de privacidade explícita.** Verificar idade exige coletar dado sensível; a lei brasileira não detalha o que pode ser retido.
3. **Experiência internacional de rejeição.** A França teve a lei de 15 anos derrubada pelo Conselho Constitucional em 14/08/2026 por desproporcionalidade e por exigir prova de idade de todos os usuários — precedente direto contra desenho mal calibrado.

---

## 4. O que a comparação revela

**Verificação de idade é o item com maior consenso e maior taxa de invalidação judicial.** Todos os países pesquisados tentaram; a França teve a lei derrubada; nos EUA há liminares em vários Estados.

**A lição transversal:** o que derruba a norma não é exigir idade mínima — é **exigir prova de idade de todos os usuários**. Desenhos que funcionam limitam a verificação ao gatilho (conta suspeita, recurso de maioridade) ou concentram no sistema operacional/loja (Califórnia, Texas).

**Consequência para a proposta:** verificar idade para **conter** acesso é defensável; verificar a idade de **toda a população** para liberar acesso é o desenho que cai na França e nos tribunais americanos.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Quem verifica** | plataforma × loja de app e sistema operacional | Concentrar na loja reduz coleta e facilita fiscalização |
| **Método** | resultado (Austrália) × critérios (UE) | Critério no texto aumenta segurança jurídica e litígio |
| **Retenção de dados** | não prevista × vedada expressamente | Sem vedação, a norma vira coleta massiva de dados de crianças |
| **Universalidade** | todos os usuários × só no gatilho | Verificar todos é o desenho que cai em tribunal |
| **Sanção** | multa × perda de função × bloqueio | Multa alta (Austrália: 30 mil unidades) é o padrão |

---

## 6. Lacunas de pesquisa

1. **Lei 15.211/2025 e Decreto 12.880/2026 não estão no acervo** — precisam ser baixados antes de qualquer proposta sobre menores.
2. Não verifiquei o texto integral da AB 1043 sobre o que o "sinal de idade" contém.
3. Não há, no acervo, dado sobre eficácia da verificação australiana: a eSafety constatou que mais de 80% dos menores seguiam usando as redes após o banimento.

---

## 7. Perguntas abertas

1. A verificação é dever da **plataforma** ou da **loja de aplicativos e do sistema operacional**?
2. O texto veda retenção dos dados de verificação? Sem isso, a norma cria o problema que quer resolver.
3. Verifica-se **todos** os usuários ou só no gatilho de suspeita?
