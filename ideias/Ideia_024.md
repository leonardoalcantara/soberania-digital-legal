# Ideia 024 — Responsabilidade objetiva por dano à soberania

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova, formulada em conversa
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Responsabilidade civil **objetiva** do provedor por falha que viabilize dano ao processo político-eleitoral, com **falha técnica que não exclui** a responsabilidade. Não se perquire dolo nem culpa.

É a proposta que mais colide com o que já existe — e a que mais depende de recorte. Sem recorte, seria reversão da tese do STF; com recorte, é regime especial para uma classe de dano definida.

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| **Brasil (Constituição)** | CF, art. 21, XXIII, "d" | "a responsabilidade civil por **danos nucleares independe da existência de culpa**" — precedente constitucional de objetividade |
| **Brasil** | LGPD, arts. 42 a 44 | Obrigação de reparar sem menção a culpa; excludentes **fechados**; padrão objetivo de segurança |
| Austrália | *Foreign Influence Transparency Scheme Act 2018* | Lista fechada de "principal estrangeiro"; "influence includes affect in any way" |
| Índia | IT Rules 2026, regra 3(1)(b)(vii) | "soberania e integridade da Índia" como categoria de dever de plataforma |
| China | Medidas de IA Antropomórfica (2026), art. 22 | Avaliação de segurança quando houver risco à segurança nacional |

### Brasil — a estrutura já existe, na LGPD

LGPD, art. 42, caput: o controlador que causar dano "em violação à legislação de proteção de dados pessoais, é obrigado a repará-lo". Sem menção a dolo ou culpa.

E o art. 43 fixa os excludentes — a responsabilidade só é afastada se o agente provar:

> "I — que não realizaram o tratamento de dados pessoais que lhes é atribuído; II — que, embora tenham realizado o tratamento[…], **não houve violação** à legislação de proteção de dados; ou III — que o dano é decorrente de **culpa exclusiva do titular** dos dados **ou de terceiro**."

Fonte: `fontes/Brasil/2018-lei-13709-Lei Geral de Proteção de Dados - texto.md`

**Não há excludente para falha técnica do próprio agente.** Problema no sistema da plataforma não é culpa exclusiva de terceiro — é falha própria. E o art. 44 dá o padrão objetivo: o tratamento é irregular quando "não fornecer a segurança que o titular dele pode esperar".

**É a estrutura que a proposta quer, já positivada para outra matéria.** O transplante é interno, não importação.

### O precedente constitucional

CF, art. 21, XXIII, "d":

> "a responsabilidade civil por danos nucleares independe da existência de culpa."

Fonte: `fontes/Brasil/1988-constituicao-federal_stf.pdf`

É precedente de **objetividade por comando direto da Constituição**, para um domínio de risco. O argumento de simetria fica pronto: se o dano nuclear é objetivamente imputável por determinação constitucional, o dano ao processo político-eleitoral causado por falha de plataforma também pode ser.

### Austrália — como dar corpo a "soberania"

O conceito de "dano à soberania" não é categoria de responsabilidade civil: é princípio constitucional e princípio de política. Usá-lo diretamente produz norma inaplicável. O FITS australiano resolve a metade do problema definindo **quem age e em nome de quem**:

> "**foreign principal** significa: (a) um governo estrangeiro; (b) uma entidade relacionada a governo estrangeiro; (c) uma organização política estrangeira; (d) um indivíduo relacionado a governo estrangeiro."

E: "**influence** inclui afetar de qualquer forma".

Fonte: `fontes/Australia/2018-foreign-influence-transparency-scheme-act.pdf`

**Atenção ao que a Austrália faz e não faz:** impõe registro e transparência a quem age em nome de principal estrangeiro — **não responsabiliza a plataforma**. O passo para responsabilidade objetiva de plataforma não tem precedente no acervo.

### Índia — a categoria jurídica, sem a definição

IT Rules, regra 3(1)(b)(vii), entre as informações que o usuário não pode hospedar:

> "ameace a **unidade, integridade, defesa, segurança ou soberania da Índia**, as relações amistosas com Estados estrangeiros, ou a ordem pública[…]"

É o único instrumento do acervo que põe a soberania como categoria operacional de dever de plataforma — e é também o dispositivo mais criticado das regras indianas, justamente por vagueza.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **LGPD, arts. 42 a 44** — estrutura de responsabilidade sem culpa, com excludentes fechados e padrão objetivo.
- **CF, art. 21, XXIII, "d"** — precedente de objetividade constitucional.
- **Marco Civil, art. 19** e a tese do STF — regime de responsabilidade por conteúdo de terceiro, **subjetivo**.
- **PNCiber, art. 2º, I** e **E-Ciber, art. 1º, IV** — soberania como princípio e eixo, sem instrumento.
- **LAI, art. 23, I** — autoriza classificar como sigilosa a informação que possa pôr em risco a defesa e a soberania.

**Falta:**

1. **Definição do dano.** "Dano à soberania" não é mensurável nem delimitável.
2. **Definição do sujeito estrangeiro** — sem lista fechada, a norma alcança tudo ou nada.
3. **Responsabilidade objetiva** para a classe de dano — o STF recusou a objetividade em geral.
4. **Excludentes próprios** — inclusive a vedação expressa ao "fato de terceiro" quando o terceiro é usuário, fornecedor ou coligada.
5. **Medidas exigíveis** — sem elas, não há como aferir a falha.
6. **Autoridade competente.**

---

## 4. O que a comparação revela

**O recorte é o que separa a proposta da inconstitucionalidade.** O item 12 da tese do STF no Tema 987 diz que "não haverá responsabilidade objetiva na aplicação da tese aqui enunciada" — e o item 12 trata da responsabilidade por **conteúdo de terceiro em geral**, sem dever legal específico. A proposta trata de **descumprimento de dever legal específico**: informar, contestar, prevenir riscos. São regimes distintos, e a distinção precisa estar escrita, sob pena de o texto ser lido como reversão de decisão recente.

**E o item 13 da mesma tese é o argumento de legitimidade:** o próprio STF apelou ao Congresso para legislar sobre a matéria.

**Duas peças resolvem as duas metades do problema de definição.** A Índia dá a **categoria jurídica** (soberania como dever de plataforma), mas com o defeito da vagueza. A Austrália dá o **evento verificável** (principal estrangeiro em lista fechada, influência definida com amplitude). Juntando: a soberania entra como fundamento, o processo político como bem jurídico lesionado, e o principal estrangeiro como elemento de tipificação.

**O custo conhecido: sobre-remoção.** Responsabilidade objetiva somada a dever de moderar transforma a plataforma em seguradora do conteúdo, e o incentivo passa a ser remover mais. O *safe harbour* do DSA existe precisamente para conter isso, e o STF o recusou por isso. Não é argumento contra — é o parâmetro que a seção 5 precisa explicitar.

**Um limite intransponível:** responsabilidade **penal** objetiva é vedada no direito brasileiro — o Código Penal exige dolo ou culpa, e o parágrafo único do art. 18 é expresso. A proposta alcança civil e administrativo, não penal.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Definição do dano** | "dano à soberania" × "dano ao processo político-eleitoral" × lista de eventos | "Soberania" em abstrato é inaplicável; evento é aferível |
| **Sujeito estrangeiro** | lista fechada australiana × conceito aberto × só Estado estrangeiro | Lista fechada é previsível e menos sujeita a uso político |
| **Elemento de tipificação** | principal estrangeiro × comportamento inautêntico × ambos | Sem elemento, a norma alcança crítica política legítima |
| **Natureza** | objetiva × objetiva com culpa exclusiva da vítima × subjetiva com culpa presumida | Objetiva colide com o Tema 987 sem recorte |
| **Excludentes** | fechados, no molde da LGPD × abertos | Abertos esvaziam a objetividade |
| **Falha técnica** | não exclui, expressamente × silêncio | Silêncio permite interpretação contrária |
| **Medidas exigíveis** | estado da técnica × lista fechada × deixar para regulamento | Sem medida exigível, não há como aferir falha |
| **Veículo** | princípio na PEC + lei × só lei | Só lei será lida contra o Tema 987 |
| **Sobre-remoção** | aceitar × criar salvaguarda contra remoção excessiva | Sem salvaguarda, o incentivo é remover demais |

---

## 6. Lacunas de pesquisa

1. O **CDC** não está no acervo: a responsabilidade objetiva por vício do produto já existe (arts. 12 e 14), e isso muda o diagnóstico do item 3.
2. O **Código Penal** não está no acervo — a vedação à responsabilidade penal objetiva está afirmada de memória, não conferida.
3. Não há, no acervo, **jurisprudência brasileira** sobre dano à soberania por falha de plataforma.
4. Não há **metodologia de mensuração** de dano ao processo político-eleitoral.
5. Não verifiquei **quantos países** adotam responsabilidade objetiva para dano informacional — a amostra do acervo é de um (o Brasil, com a LGPD e o dispositivo nuclear).

---

## 7. Perguntas abertas

1. O bem jurídico é **soberania** ou **processo político-eleitoral**?
2. O elemento de tipificação é **principal estrangeiro**, **comportamento inautêntico coordenado** ou os dois?
3. A objetividade vale para **qualquer falha** ou só para o descumprimento das medidas exigíveis?
4. Os excludentes são **fechados**? A falha técnica fica expressamente de fora?
5. O veículo é **princípio na PEC + lei**, ou só lei?
6. Há **salvaguarda contra sobre-remoção** — e qual?
