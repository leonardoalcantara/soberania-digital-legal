# Ideia 001 — Escolha de feed: linha do tempo não algorítmica

**Bloco:** A — desenho da distribuição de conteúdo
**Origem:** ideia original 1
**Estado:** proposta de trabalho

---

## 1. Formulação

> "Para operar no Brasil a rede social deve obrigatoriamente ter a opção de apresentar ao usuário uma *timeline* cronológica e não priorizada por seu algoritmo. Se houver a opção de uma *timeline* priorizada por algoritmo esta deve obrigatoriamente estar desabilitada para novas contas. Sendo necessário que o usuário por ação própria entre na configuração da plataforma e realize a habilitação da opção."

Duas partes distintas, que na prática são duas propostas autônomas:

1. **Existência da opção** — a plataforma é obrigada a oferecer um modo de exibição sem recomendação.
2. **Regra de padrão** — o modo sem algoritmo é o *default*; ligar a recomendação exige ação do usuário.

A parte 1 existe no direito comparado. A parte 2 **não tem precedente localizado** — é o diferencial.

---

## 2. Como a proposta aparece em outros ordenamentos

Quatro variantes, em ordem de força:

| Variante | Onde | Mecanismo |
|---|---|---|
| **A. Feed só de contas seguidas, como uma das opções** | Austrália | A plataforma deve oferecer um "feed de contas seguidas": feed que não inclui material além de contas que o usuário escolhe seguir |
| **B. Opção de recomendação não baseada em perfilamento** | União Europeia | Plataformas de grande porte devem oferecer ao menos uma opção de sistema de recomendação não baseado em perfilamento |
| **C. Proibição de ranquear candidatos por sistema de IA** | Brasil (TSE) | Veda a sistemas de IA ranquear, recomendar, sugerir ou priorizar candidatos no período eleitoral |
| **D. Compromisso contratual de feed não algorítmico opcional** | Estados Unidos (acordo Meta × procuradores-gerais) | Obrigação de design assumida em acordo, sem lei nova |

### Austrália — variante A (a mais próxima da formulação)

Instrumento: *Online Safety (User Empowerment Tools) Determination 2026* — **minuta em consulta**,
instrumento que depende de projeto de lei.

> **Seção 6, item 4:** "Uma das opções para o feed preferido deve ser um feed de contas seguidas."
>
> **Item 5:** "Um feed de contas seguidas é um feed que não inclui material além daquele de contas que o
> usuário escolhe seguir."
>
> **Item 6:** "Um feed de contas seguidas pode incluir material publicitário, inclusive de conta que o
> usuário não segue."

Fonte: `fontes/Australia/my-feed-my-way/draft-online-safety-user-empowerment-tools-determination-2026.md`

O projeto de lei que dá base ao instrumento — *Online Safety Amendment (Digital Duty of Care) Bill
2026*, minuta de 08/09/2026 — cria o poder:

> **Seção 26:** serviços online devem fornecer as ferramentas de empoderamento do usuário que forem
> especificadas.

Fonte: `fontes/Australia/my-feed-my-way/exposure-draft-online-safety-amendment-digital-duty-of-care-bill-2026-september2026.md`

**A Austrália faz o que a proposta não faz:** permite publicidade no feed puro (item 6).
**A proposta faz o que a Austrália não faz:** inverte o padrão — lá o feed algorítmico continua sendo o
*default*, com o feed de seguidas como opção.

### União Europeia — variante B

Regulamento (UE) 2022/2065 (Digital Services Act), art. 38, complementando o art. 27:

> Prestadores de plataformas de muito grande porte e de buscadores de muito grande porte que utilizem
> sistemas de recomendação devem oferecer, para cada um de seus sistemas de recomendação, **ao menos uma
> opção que não seja baseada em perfilamento**, na acepção do RGPD.

Fonte: `fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf`

**Limite duplo:** vale só para plataformas de muito grande porte, e a opção pode continuar sendo
algorítmica — só não pode personalizar a partir de dados pessoais. "Não perfilado" não é
"cronológico": um feed ordenado por popularidade agregada satisfaz a regra europeia.

### Brasil — variante C

Resolução TSE nº 23.755/2026, art. 28, § 1º-C, inciso I:

> É vedado aos provedores de aplicação que ofertem sistemas de inteligência artificial ou por
> tecnologia equivalente, ainda que solicitado pelo usuário: I — ranquear, recomendar, sugerir ou
> priorizar candidatas, candidatos, campanhas, partidos políticos, federações ou coligações.

Fonte: `fontes/Brasil/2026-resolucao-tse-23755-Resolução TSE 23.755 - texto.md`

**Limite:** só no período eleitoral, e só quanto a candidatos — não é regra geral de feed.

### Estados Unidos — variante D

Acordo Meta × coalizão de 51 procuradores-gerais, proposto em 26/08/2026 (até US$ 17 bi em dez anos,
sujeito a homologação), impõe entre as obrigações de design um **feed não personalizado opcional** para
usuários menores de 18 anos.

Fonte: **primária** — `fontes/EUA/2026-acordo-meta-51-procuradores-gerais-consent-judgment.pdf`
(Settlement Agreement, caso 4:23-cv-05448-YGR, N.D. Cal., Doc. 572-1, 26/08/2026), Seção II.

**Duas particularidades que só o texto integral mostra:**

1. **É a definição mais forte das quatro variantes.** O acordo não usa "não algorítmico" nem "não
   personalizado" em sentido vago: define "Non-Personalized Feed" como o feed em que o conteúdo "é
   populado por **contas que o usuário adolescente segue ou com quem tem amizade**, exibidas em **ordem
   cronológica**". É, ao mesmo tempo, feed só de seguidos **e** cronológico — a mesma combinação da
   minuta australiana.
2. **É opção, com empurrão periódico** — não é padrão obrigatório. Meta deve oferecer a opção como feed
   inicial e **lembrar o usuário a cada 90 dias**, sem pré-selecionar aceitar ou recusar (Seção II,
   "Feed Options"). Fica, portanto, entre a variante australiana (só opção) e a proposta brasileira
   (padrão cronológico).

Há ainda uma **trava de paridade** (Seção V, "Parity/MFN"): as obrigações se intensificam se os demais
"Core Industry Members" — definidos como Snap, TikTok e YouTube — adotarem termos equivalentes. O limite
diário cai de 2h para 1h e o bloqueio noturno passa de 0h–6h para 22h–7h. É mecanismo que faz a norma se
autorreforçar entre concorrentes, e não tem equivalente no acervo.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Marco Civil da Internet, art. 9º** — neutralidade de rede: dever de tratar pacotes de forma
  isonômica, sem distinção por conteúdo. Protege o **tráfego**, não a curadoria do feed.
- **Resolução TSE nº 23.755/2026, art. 28, § 1º-C** — veda ranquear candidatos, mas só em período eleitoral e só quanto a candidatos.
- **LGPD, art. 20** — direito de revisão de decisões automatizadas; não cria direito a feed alternativo.

**Falta:**

1. **Direito geral a um modo de exibição não personalizado.** Nenhuma norma brasileira obriga a
   plataforma a oferecer essa opção fora do período eleitoral.
2. **Regra de padrão.** Nada no direito brasileiro trata do *default* de ordenação.
3. **Definição de "perfilamento".** A LGPD não define o termo — se o texto usar a expressão europeia,
   terá de defini-la no próprio dispositivo.
4. **Sanção específica.** Não há consequência prevista para plataforma que não ofereça feed alternativo.

---

## 4. O que a comparação revela

**Convergência:** três ordenamentos e um acordo chegaram, de forma independente, à mesma ideia — o usuário deve poder sair da recomendação algorítmica.

**Divergência decisiva — o padrão.** Em todos os casos localizados, o feed algorítmico continua sendo o padrão; a escolha é uma opção que o usuário precisa ativar. A proposta em análise inverte isso.

**Escopo variável.** Austrália: plataformas designadas. UE: só muito grande porte. Brasil: só no
período eleitoral. A escolha de escopo é o principal parâmetro de calibragem.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções observadas | Consequência |
|---|---|---|
| **Padrão** | algorítmico (Austrália, UE) × cronológico (proposta) | O padrão cronológico transfere o ônus a quem quer recomendação e derruba o modelo de negócio por omissão |
| **Universo** | todas as plataformas × só grandes × só período eleitoral | Quanto maior o universo, maior o custo de conformidade das pequenas |
| **Publicidade no feed puro** | permitida (Austrália, item 6) × vedada | Vedá-la cria conflito direto com o modelo de receita |
| **Como se conta "conta seguida"** | inscrição explícita (Austrália, item 3) | Precisa de definição técnica no texto, senão a plataforma define |
| **Sanção** | não prevista na minuta australiana | Sem consequência, a obrigação é declaração de intenção |

---

## 6. Lacunas de pesquisa

1. **Não há precedente de padrão cronológico obrigatório** em nenhuma jurisdição do acervo.
2. A minuta australiana é **minuta em consulta**; o projeto de lei foi introduzido em 15/10/2026, mas o texto protocolado não está no acervo (o servidor do Parlamento bloqueou o download).
3. O acordo Meta × procuradores-gerais está no acervo em texto integral, mas **há 130 páginas com
   anexos** — a leitura deste arquivo cobriu as seções I a VI; a Seção V (paridade) não foi lida linha a
   linha.
4. Não verificado se o DSA art. 38 tem sanção específica além da multa geral do art. 74.

---

## 7. Perguntas abertas

1. O padrão cronológico vale para **todas** as plataformas ou só acima de um limiar de usuários?
2. O feed puro admite **publicidade**? A Austrália admite; a formulação original não diz.
3. A obrigação alcança **buscadores e plataformas de vídeo**, ou só rede social no sentido estrito?
