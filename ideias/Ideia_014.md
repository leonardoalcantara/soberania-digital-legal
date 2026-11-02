# Ideia 014 — Cooperação obrigatória com autoridades, com prazos

**Bloco:** B — instituições e sanções
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Fixar **prazos curtos**, em lei, para que a plataforma entregue dados ou remova conteúdo quando requisitada por autoridade competente — com consequência pelo descumprimento. É a parte operacional da jurisdição: sem prazo, a ordem existe e não se cumpre.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Prazo e mecanismo |
|---|---|---|
| Chile | PL 18.362-19, art. 3º | **48 horas** se urgente; **15 dias corridos** nos demais casos |
| Turquia | PL 2/3358, MADDE 3 | Remoção e bloqueio em **6 horas**, com responsabilidade solidária de provedor e desenvolvedor |
| Brasil | Res. TSE 23.755/2026, art. 28, §§ 4º-A a 4º-C | Remoção **independentemente de ordem judicial** em hipóteses definidas |
| Brasil | Lei 9.504/1997, art. 57-I | Suspensão de acesso por até **24 horas**, proporcional à gravidade |

### Chile — o modelo com dois prazos e definição de urgência

> "Art. 3º: Os prestadores de serviços digitais podem ser requeridos por tribunal competente ou pelo Ministério Público … devendo entregar, por meio de seu representante legal, os dados de identificação do usuário ou conta envolvida, incluindo endereço IP, registros de conexão e dados de registro, **em um prazo de quarenta e oito horas se o requerimento for qualificado de urgente, e de quinze dias corridos nos demais casos**."
>
> "Entender-se-á que é urgente quando existir **risco vital da pessoa, ameaça de exploração sexual de menores de idade ou difusão ativa de material de abuso sexual infantil**."

Fonte: `fontes/America-Latina/2026-chile-boletin-18362-19-projeto.pdf`

**O que o desenho tem de sofisticado:** o prazo curto não depende de discricionariedade — depende de
**hipóteses fechadas de urgência**, definidas em lei.

### Turquia — o prazo mais curto do acervo

O projeto 2/3358 (MADDE 3) insere regra de remoção e bloqueio de conteúdo de IA em **6 horas**, com responsabilidade solidária de provedores de conteúdo e desenvolvedores.

Fonte: `fontes/Turquia/2025-turquia-esas-2-3358-teklif-texto-extraido.md`

**Observação:** é projeto, não lei. E 6 horas é prazo que, na prática, transfere ao setor privado a decisão
sobre o que é ilícito.

### Brasil — a remoção sem ordem judicial

Resolução TSE nº 23.755/2026, art. 28, § 4º-B:

> "Nas hipóteses previstas no § 4º-A, o provedor de aplicação de internet deve adotar as providências necessárias para tornar indisponível o conteúdo ilícito, **independentemente de determinação judicial**, garantindo, em qualquer caso, a comunicação ao usuário dos motivos … e a possibilidade de recorrer da moderação."

Fonte: `fontes/Brasil/2026-resolucao-tse-23755-Resolução TSE 23.755 - texto.md`

As hipóteses do § 4º-A são fechadas: informações falsas sobre o sistema eletrônico de votação, incitação de crimes contra o Estado Democrático de Direito, subversão da ordem constitucional e violência política contra a mulher.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Marco Civil, arts. 22 e 23** — requisição **judicial** de registros para formação de prova.
- **Marco Civil, art. 10, § 1º** — disponibilização de registros mediante ordem judicial.
- **Lei 9.504, art. 57-I** — suspensão de acesso a conteúdo por decisão da Justiça Eleitoral, até 24 horas.
- **Res. TSE 23.755/2026, art. 28, §§ 4º-A a 4º-C** — remoção sem ordem judicial em hipóteses fechadas.

**Falta:**

1. **Prazos legais de resposta.** O Marco Civil não fixa prazo para cumprimento de requisição judicial — depende de o juiz fixar caso a caso.
2. **Prazos fora do período eleitoral** para remoção por autoridade administrativa.
3. **Definição legal de urgência**, como a chilena, com hipóteses fechadas.
4. **Sanção específica por descumprimento de prazo**, distinta da responsabilidade pelo conteúdo.

---

## 4. O que a comparação revela

**É a proposta que mais depende de detalhe técnico e menos de princípio.** O desenho inteiro está em três escolhas: qual prazo, para qual tipo de pedido e com qual consequência.

**A lição chilena:** prazo curto só é defensável se a urgência estiver **definida em lei**, não deixada ao
juízo de quem pede. Sem isso, o prazo curto vira regra geral e o setor privado passa a decidir sobre ilicitude.

**A lição turca:** 6 horas é o limite em que a remoção deixa de ser cumprimento de ordem e passa a ser
moderação automatizada.

**O modelo brasileiro já tem a peça mais discutida** — remoção sem ordem judicial em hipóteses fechadas — mas só no período eleitoral e por resolução de tribunal.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Prazo urgente** | 48h (Chile) × 6h (Turquia) × 24h | Prazos abaixo de 24h transferem decisão de mérito à plataforma |
| **Definição de urgência** | hipóteses fechadas (Chile) × critério aberto | Fechada é mais segura e mais restritiva |
| **Tipo de pedido** | dados de identificação × remoção × ambos | São obrigações distintas e devem ter prazos distintos |
| **Ordem judicial** | exigida × dispensada em hipóteses definidas | Dispensar amplia eficácia e risco de erro |
| **Contraditório** | prévio × posterior (com recurso) | O modelo do TSE é posterior, com dever de informar e recurso |

---

## 6. Lacunas de pesquisa

1. Não há, no acervo, **prazo médio real** de cumprimento de requisições judiciais no Brasil.
2. Não verifiquei se o Marco Civil ou a LGPD preveem sanção específica por descumprimento de prazo.
3. A lei turca que fixa prazo (5651) não está no acervo em texto consolidado — só o projeto que a altera.

---

## 7. Perguntas abertas

1. O prazo curto vale para **dados** e para **remoção de conteúdo**, ou só para um deles?
2. A urgência é definida em lei, com hipóteses fechadas, ou caso a caso?
3. A remoção sem ordem judicial fica restrita a categorias definidas, com dever de informar e recurso?
