# Ideia 015 — Responsabilidade do intermediário

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Substituir, em lei, o regime de responsabilidade do provedor de aplicações por um **regime graduado de
notificação e remoção**: a notificação tem conteúdo definido, a plataforma tem prazo e dever de
justificar a decisão, o autor do conteúdo tem contraditório — e o descumprimento gera consequência
própria, distinta da responsabilidade pelo conteúdo em si.

No Brasil esse regime **já existe em substância, por decisão judicial**. O que não existe é a lei.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| União Europeia | DSA (Reg. 2022/2065), arts. 6º, 8º, 16 e 17 | Isenção de responsabilidade **condicionada** a agir "expeditamente" após conhecimento efetivo; notificação com quatro elementos obrigatórios; dever de fundamentar toda restrição |
| Estados Unidos | Take It Down Act (Lei 119-12/2025), § 3(3) | Remoção em até **48 horas** após pedido válido, **sem ordem judicial**, limitada a imagem íntima não consentida |
| Índia | IT (Amendment) Rules 2026, regras 3(1)(d), 3(1)(g) e 4(1)(a) | Conhecimento efetivo como gatilho; guarda de 180 dias do conteúdo removido; responsabilização pessoal do *Chief Compliance Officer* |
| Brasil | STF, RE 1037396 (Tema 987), tese de 26/06/2025 | Regime graduado por categoria de ilícito, **enquanto não sobrevier nova legislação** |

### União Europeia — a isenção como contrapartida de um dever

DSA, art. 6º, § 1º:

> "O prestador de serviços de hospedagem não será responsável pelas informações armazenadas a pedido do
> destinatário do serviço, desde que: (a) não tenha **conhecimento efetivo** de atividade ou conteúdo
> ilícito e, quanto a pedidos de indenização, não tenha conhecimento de fatos ou circunstâncias dos quais
> a ilicitude se mostre aparente; ou (b) ao obter tal conhecimento, atue **expeditamente** para remover ou
> tornar inacessível o conteúdo ilícito."

DSA, art. 8º:

> "Nenhuma obrigação geral de monitorar as informações transmitidas ou armazenadas, nem de buscar
> ativamente fatos ou circunstâncias que indiquem atividade ilícita, será imposta aos prestadores."

DSA, art. 16, § 2º — os quatro elementos que a notificação deve poder conter:

> "(a) explicação suficientemente fundamentada das razões pelas quais o notificante alega que a informação
> é conteúdo ilícito; (b) indicação clara da **localização eletrônica exata** da informação, como a URL
> exata; (c) nome e endereço de correio eletrônico do notificante, salvo nas hipóteses de ilícitos
> referidos nos arts. 3º a 7º da Diretiva 2011/93/UE; (d) declaração confirmando a crença de boa-fé do
> notificante de que as informações e alegações são exatas e completas."

E o § 3º faz a ponte com a isenção: a notificação que permite ao prestador diligente identificar a
ilicitude **sem exame jurídico detalhado** produz conhecimento efetivo para os fins do art. 6º.

Fonte: `fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf`

**O que o desenho tem de específico:** a isenção não é um privilégio do setor, é a contrapartida de um
dever de reação. Quanto mais fraca a notificação, menos se pode exigir do intermediário — e o art. 16,
§ 2º define o padrão mínimo da notificação justamente para que a exigência seja possível.

### Estados Unidos — o prazo curto sem ordem judicial, num ilícito só

Take It Down Act, § 3(3):

> "Ao receber pedido de remoção válido de indivíduo identificável (ou de pessoa autorizada em seu nome),
> por meio do processo descrito no parágrafo (1)(A)(ii), a plataforma abrangida deverá, **tão logo quanto
> possível, mas não depois de 48 horas** do recebimento do pedido: (A) remover a representação visual
> íntima; e (B) envidar esforços razoáveis para identificar e remover quaisquer cópias idênticas
> conhecidas de tal representação."

E o § 3(4) limita a responsabilidade por remoção de boa-fé, "independentemente de a representação vir a
ser considerada ilícita ou não".

Fonte: `fontes/EUA/2025-pl-119-12-take-it-down-act.pdf`

**O ponto que interessa:** 48 horas, sem juiz, só é sustentável porque a categoria é estreita e a
ilicitude é evidente pelo próprio objeto. O prazo curto e o âmbito restrito andam juntos.

### Índia — o conhecimento efetivo e a pessoa responsável

IT (Amendment) Rules 2026, regra 3(1)(g), sobre preservação:

> "Quando, tendo recebido conhecimento efetivo nos termos da alínea (d), por iniciativa própria em caso de
> violação da alínea (b), ou com base em reclamações recebidas nos termos da sub-regra (2), qualquer
> informação tiver sido removida ou tiver tido o acesso desabilitado, o intermediário deverá, sem
> adulterar a prova de qualquer forma, **preservar tal informação e os registros associados por 180
> dias** para fins de investigação, ou por prazo maior que venha a ser exigido por tribunal ou por órgão
> de governo legalmente autorizado."

Regra 4(1)(a), sobre o *Chief Compliance Officer*:

> "[O intermediário de mídia social significativo deverá] nomear um *Chief Compliance Officer*, que será
> responsável por assegurar o cumprimento da Lei e das regras [...] e **será pessoalmente responsável em
> qualquer procedimento** relativo a informação, dado ou link de comunicação de terceiros disponibilizado
> ou hospedado por aquele intermediário, quando deixar de assegurar que o intermediário observe a
> diligência devida."

Fonte: `fontes/India/2026-it-amendment-rules-sgi.pdf`

**O que acrescenta:** liga a responsabilidade da empresa a uma pessoa nomeada, residente no país, e
impõe o dever de preservar o conteúdo removido — a remoção não apaga a prova.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe — e é mais do que o debate costuma registrar.** A tese de repercussão geral fixada pelo STF em
26/06/2025 no RE 1037396 (Tema 987) e no RE 1057258 (Tema 533) já montou um regime graduado:

| Item da tese | Conteúdo |
|---|---|
| Item 1 | Art. 19 do Marco Civil é **parcialmente inconstitucional** — há omissão parcial |
| Item 2 | "**Enquanto não sobrevier nova legislação**", o art. 19 deve ser interpretado conforme a tese |
| Item 3 | Crimes e atos ilícitos em geral: responsabilidade se, **após pedido de retirada**, o provedor deixar de remover. Mesma regra para contas denunciadas como inautênticas |
| Item 3.1 | Crimes contra a honra: aplica-se o art. 19 (ordem judicial), **sem prejuízo** da remoção por notificação extrajudicial |
| Item 3.2 | Replicações sucessivas de fato ofensivo já reconhecido em juízo: todos os provedores removem conteúdos idênticos a partir de notificação judicial **ou extrajudicial** |
| Item 4 | **Presunção de responsabilidade** em anúncios e impulsionamentos pagos e em rede artificial de distribuição (robôs), independentemente de notificação, com exclusão se comprovada diligência |
| Item 5 | Rol taxativo de **crimes graves** com dever de indisponibilização imediata |
| Item 5.1 a 5.3 | A responsabilidade do item 5 é por **falha sistêmica** — deixar de adotar medidas adequadas de prevenção ou remoção |
| Item 5.5 | Quem publicou conteúdo removido pode pedir restabelecimento judicial; restaurado, não há indenização ao provedor |
| Item 6 | Art. 19 continua aplicável a e-mail, reuniões fechadas por vídeo ou voz e mensageria privada |
| Item 8 | Dever de editar autorregulação com **sistema de notificações, devido processo e relatórios anuais de transparência** |
| Item 10 | Regras publicadas e revisadas periodicamente |
| Item 12 | **Não há responsabilidade objetiva** |
| Item 13 | "**Apela-se ao Congresso Nacional** para que seja elaborada legislação capaz de sanar as deficiências do atual regime" |
| Item 14 | Efeitos modulados — aplicação prospectiva, ressalvadas decisões transitadas em julgado |

Fonte: `fontes/Brasil/2025-stf-tese-re-1037396-art19-marco-civil.pdf` (texto integral em
`2025-stf-tese-re-1037396-art19-marco-civil - texto.md`)

Somam-se a isso, em lei:

- **Marco Civil, art. 18** — provedor de conexão não responde por conteúdo de terceiro.
- **Marco Civil, art. 19** — provedor de aplicações só responde após ordem judicial específica.
- **Marco Civil, art. 21** — responsabilidade subsidiária por nudez ou ato sexual de caráter privado
  após notificação do participante.
- **ECA Digital (Lei 15.211/2025), art. 31** — relatórios semestrais de transparência, com canais de
  denúncia, quantidade de denúncias, quantidade de moderação por tipo.
- **TSE, Res. 23.755/2026, art. 28, §§ 4º-A a 4º-C** — remoção sem ordem judicial no período eleitoral.

**Falta:**

1. **Prazo legal.** Nem a tese do STF nem o Marco Civil fixam prazo para a plataforma decidir após a
   notificação. "Deixar de remover" não tem relógio.
2. **Conteúdo mínimo da notificação.** A tese fala em "pedido de retirada" sem definir o que ele precisa
   conter — o que transfere ao caso concreto a discussão sobre se houve notificação válida.
3. **Dever de fundamentar a decisão** (manter ou remover) perante quem notificou e perante quem publicou.
4. **Contraditório e recurso** para o autor do conteúdo removido, fora da via judicial — o item 5.5 só
   prevê o caminho do juízo.
5. **Consequência própria pelo descumprimento do prazo**, separada da responsabilidade pelo conteúdo.
6. **Base legal estável.** Hoje o regime depende de tese fixada em repercussão geral, com efeitos
   modulados e expressamente provisória ("enquanto não sobrevier nova legislação").

---

## 4. O que a comparação revela

**Este é o caso mais claro, no acervo, de uma ideia em que o Brasil está à frente no conteúdo e atrás na
forma.** A tese do STF já tem os elementos que a comparação aponta como essenciais num regime de
notificação e remoção — graduação por gravidade, regime próprio para impulsionamento e automação,
responsabilidade por falha sistêmica e dever de autorregulação com transparência.

O que a tese **não** tem é o que só a lei pode dar: prazo, conteúdo da notificação, dever de fundamentar,
recurso administrativo e sanção pelo descumprimento. E o próprio STF disse isso no item 13.

**A lição do DSA** é que a qualidade da notificação é o que torna a exigência exigível. Sem padrão de
notificação, "conhecimento efetivo" vira litígio em cada caso.

**A lição do Take It Down Act** é que prazo de 48 horas sem juiz só se sustenta em categoria estreita e
de ilicitude evidente. Transportar 48 horas para "crimes em geral" seria mudar a natureza do regime.

**A lição indiana** é que remover não é apagar: o dever de preservar por 180 dias é o que permite que a
remoção rápida não destrua a investigação.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Prazo para decidir** | 48h (EUA, categoria estreita) × prazo por gravidade × "expedito" sem número | Prazo único para todas as categorias iguala o ilícito evidente ao controvertido |
| **Gatilho** | notificação de qualquer pessoa × notificação qualificada × ordem de autoridade | Notificação aberta amplia remoção e erro; qualificada reduz volume e aumenta exigência |
| **Conteúdo da notificação** | mínimo do art. 16 do DSA × livre | Sem padrão, cada remoção vira discussão sobre validade |
| **Fundamentação** | dever de justificar ao notificante e ao autor × só ao notificante | Só ao notificante deixa o autor do conteúdo sem saber por que foi removido |
| **Contraditório** | recurso interno × recurso a órgão externo × só judicial | Recurso só judicial mantém o custo atual |
| **Consequência** | responsabilidade civil × multa administrativa × ambas | Multa é exigível sem processo indenizatório; responsabilidade civil depende de vítima |
| **Preservação** | 180 dias (Índia) × prazo próprio | Prazo de guarda tem de conversar com o art. 15 do Marco Civil |
| **Relação com a tese do STF** | lei que incorpora a tese × lei que a substitui | Incorporar preserva a jurisprudência; substituir reabre o debate sobre o art. 19 |

---

## 6. Lacunas de pesquisa

1. Não há, no acervo, **dados sobre notificações extrajudiciais** recebidas por plataformas no Brasil
   depois de junho de 2025 — nem volume, nem tempo de resposta. Os relatórios anuais do item 8 da tese
   ainda não foram produzidos ou não foram localizados.
2. Não verifiquei se há **decisões posteriores** que tenham fixado prazo de resposta com base na tese.
3. Falta o texto consolidado do **CDC** no acervo: o item 7 da tese remete os *marketplaces* ao Código de
   Defesa do Consumidor, e a lacuna correspondente não pode ser descrita com precisão sem ele.
4. Não verifiquei **quantos países têm prazo legal** de remoção — a amostra do acervo é de três.
5. A tese não define o que é "**pedido de retirada**" — não há, no acervo, pronunciamento posterior que
   o tenha detalhado.

---

## 7. Perguntas abertas

1. A lei **incorpora** a tese do STF (transformando-a em texto) ou **substitui** o regime do art. 19?
2. O prazo é único ou escalonado por categoria de ilícito — e quais categorias entram no prazo curto?
3. A notificação exige identificação do notificante em todos os casos ou há exceção, como no DSA?
4. O recurso do autor do conteúdo removido é interno, vai a um órgão externo ou continua só judicial?
5. O descumprimento do prazo gera multa administrativa, responsabilidade civil ou as duas coisas?
6. A lei mantém a isenção de responsabilidade como **contrapartida** do dever de agir, ou descola as duas
   coisas?
