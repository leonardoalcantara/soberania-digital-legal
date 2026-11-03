# PL 04 — Marco Civil: dados de treinamento e gradação das sanções

**Instrumento:** projeto de lei ordinária (emenda)
**Altera:** Lei nº 12.965/2014 — insere o art. 23-I no Capítulo IV-A e os §§ 1º a 3º no art. 12
**Ideias cobertas:** 017, 025
**Estado:** proposta de trabalho

**As notas ao final são comuns aos PL 04 e PL 07.** O art. 23-I depende, para alcançar o desenvolvedor, da emenda de definição da Ideia_016, que ainda não tem projeto.

---

# ANTEPROJETO D — Marco Civil (dados de treinamento e três degraus)

*Altera a Lei nº 12.965, de 23 de abril de 2014, para dispor sobre transparência dos dados de treinamento de modelos de inteligência artificial e sobre a gradação das sanções.*

**Art. 1º** O Capítulo IV-A da Lei nº 12.965, de 2014, passa a vigorar acrescido do seguinte art. 23-I, na Seção II:

> "Art. 23-I. O provedor que desenvolva ou forneça modelo de inteligência artificial tornará público documento que descreva, em linguagem simples:
>
> I — o **tipo e a origem** dos dados utilizados no treinamento, na validação e no teste;
>
> II — os métodos de **curadoria**: coleta, limpeza, filtragem, rotulagem, enriquecimento e agregação;
>
> III — o **volume e o escopo** dos dados, incluindo a proporção de dados em língua portuguesa e relativos ao Brasil;
>
> IV — o uso de **dados sintéticos**, com a indicação da finalidade;
>
> V — as medidas adotadas para **detectar e mitigar vieses** e as limitações conhecidas do modelo;
>
> VI — as **lacunas de dados** identificadas e as providências adotadas.
>
> § 1º O documento não exige a divulgação de dados pessoais, de conteúdo protegido por direito autoral, de segredo comercial nem de informação que permita reconstruir o conjunto de treinamento.
>
> § 2º A ANPD poderá acessar versão completa do documento, com os elementos suprimidos da versão pública, mediante compromisso de sigilo.
>
> § 3º O dever do caput não se aplica a modelo disponibilizado sob licença livre que permita acesso, uso, modificação e distribuição, com pesos publicamente disponíveis, **salvo** quando o modelo for classificado como de risco sistêmico.
>
> § 4º Em caso de ajuste fino de modelo de terceiro, o dever limita-se à modificação realizada, complementando a documentação já existente.
>
> § 5º Sem prejuízo do caput, o provedor que forneça modelo para integração por terceiro disponibilizará ao integrador informação sobre capacidades, limitações e uso pretendido do modelo."

**Art. 2º** O art. 12 da Lei nº 12.965, de 2014, passa a vigorar acrescido dos seguintes §§ 1º a 3º, renumerando-se o atual parágrafo único para § 5º:

> "§ 1º A aplicação das sanções dos incisos I a IV observará a seguinte gradação, conforme a gravidade da infração e a reincidência:
>
> I — na primeira infração: advertência ou multa;
>
> II — na segunda infração, no prazo de 5 (cinco) anos: multa em valor não inferior ao dobro da anterior e, cumulativamente, suspensão temporária das atividades por prazo de 30 (trinta) a 90 (noventa) dias;
>
> III — na terceira infração, no prazo de 5 (cinco) anos: proibição de exercício das atividades por prazo de 2 (dois) anos.
>
> § 2º A reincidência é apurada por decisão administrativa definitiva, não se computando infração anterior cujo prazo de 5 (cinco) anos já tenha transcorrido.
>
> § 3º A suspensão e a proibição dependem de decisão fundamentada, com contraditório e ampla defesa, e de prévia intimação para cessar a infração no prazo de 30 (trinta) dias.
>
> § 4º A gradação deste artigo é a **escala geral** das infrações a esta Lei e não se aplica à infração de dano ao processo político-eleitoral por atividade de influência de principal estrangeiro, que tem escala própria em lei específica."

**Art. 3º** Esta Lei entra em vigor após decorridos 180 (cento e oitenta) dias de sua publicação, produzindo efeitos o art. 23-I, quanto aos modelos já disponibilizados, em 24 (vinte e quatro) meses.

---


## 2. Notas

### O que está ancorado e o que é invenção

| Dispositivo | Origem |
|---|---|
| Art. 23-I, I a VI (D) | AI Act, arts. 10, § 2º e 53, § 1º, "d", e Anexo XI, item 2(c); acrescentados os itens em língua portuguesa e sobre dados sintéticos |
| Art. 23-I, § 1º e § 2º (D) | AI Act, art. 53, § 1º, e art. 78 (sigilo), e o princípio do art. 20, § 2º, da LGPD |
| Art. 23-I, § 3º e § 4º (D) | AI Act, art. 53, § 2º, e considerando 109 |
| Art. 23-I, § 5º (D) | AI Act, art. 53, § 1º, "b" |
| Art. 12, §§ 1º a 3º (D) | Ideia_025; a gradação por reincidência é **invenção**, calibrada sobre a escala já existente |
| Art. 3º (E) critérios de designação | **invenção** — os números de receita e usuários não têm base no acervo; inspirei-me nos limiares do DMA e da lei japonesa, sem transpô-los |
| Art. 4º (E) | DMA, art. 6º, § 5º; lei japonesa, item ④ |
| Art. 5º (E) | DMA, art. 7º, §§ 1º, 3º e 4º |
| Art. 6º (E) | DMA, art. 6º, §§ 2º, 9º e 10 |
| Art. 7º (E) | DMA, art. 6º, §§ 3º, 4º e 6º; lei japonesa, itens ①, ② e ⑥ |
| Art. 8º (E) | Marco Civil, art. 12 (estrutura e teto de 10%) |

### Sobre o § 4º do art. 12 — a escala geral e a especial

O projeto tem duas escalas que podem alcançar o mesmo provedor: **esta**, geral, para infração às normas de guarda, jurisdição e ao Capítulo IV-A; e a do **pl-08**, específica, para dano ao processo político-eleitoral por influência de principal estrangeiro.

O § 4º do art. 12 delimita o âmbito da escala geral, e o art. 6º, §§ 5º a 7º, do pl-08 delimita o da especial e veda a cumulação pelo mesmo fundamento. **Sem os dois dispositivos, a plataforma que falhasse nas duas frentes responderia duas vezes pelo mesmo fato**, e o argumento de *bis in idem* derrubaria a aplicação.

### Cinco problemas que a redação revelou

**1. Os critérios de designação são o dispositivo mais frágil do anteprojeto E.** R$ 5 bilhões de receita e 50 milhões de usuários são números que eu inventei — não há, no acervo, estudo que os sustente. Errar para cima esvazia a lei; para baixo, alcança empresas que não têm poder de mercado. É a primeira coisa a calibrar.

**2. O art. 23-I, inciso III, exige proporção de dados em português.** Isso é o dispositivo mais nacionalista do conjunto e o mais atacável: não há parâmetro técnico de "proporção adequada", e a exigência pode ser lida como barreira à entrada. Precisa de número ou de critério, ou sai.

**3. A gradação do art. 12 é geral e alcança infrações que não têm nada a ver com conteúdo.** O art. 12 pune infração às normas de guarda de registros e de jurisdição. Aplicar três degraus a quem deixou de guardar registro por 6 meses é desproporcional. A escala foi pensada para a lei de soberania (Ideia_024/025), não para o Marco Civil inteiro.

**4. A lei de mercados digitais não tem autoridade.** "Autoridade competente" é marcador, e a decisão D.1 continua aberta. No modelo europeu é a Comissão; no japonês, a JFTC; no Brasil, poderia ser o CADE ou a autoridade nova da Ideia_006.

**5. Falta a regra de coordenação com o CADE.** Se a autoridade da lei nova não for o CADE, haverá duas instâncias sobre o mesmo fato — e o art. 8º não prevê prevenção de conflito nem ne bis in idem.

### O que ficou de fora, e por quê

| Ideia | Situação |
|---|---|
| **010** rotulagem geral | exige lei de IA; no Marco Civil ficaria deslocado |
| **011** janela de silêncio | emenda à Lei 9.504 — cabe no Anteprojeto B da Onda 1 |

Com isso, **a Onda 2 fica fechada**: 004, 009, 017, 020, 023 e 025 redigidas; 008 e 012 encerradas; 016 reescrita como emenda de definição; 018 como lei nova; 010 e 011 realocadas.
