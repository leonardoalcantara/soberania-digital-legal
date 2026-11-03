# Ideia 016 — Responsabilidade de quem desenvolve e treina IA

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova, derivada do levantamento comparado — **não estava na lista original das oito**
**Estado:** proposta de trabalho, reescrita em torno da técnica da definição

---

## 1. O que a proposta é

Em vez de criar a figura do desenvolvedor, **alterar a definição de "provedor de aplicações de internet"** para abranger quem desenvolve e fornece modelo de inteligência artificial.

O efeito é arrastar para o desenvolvedor todo o regime que já existe: o de responsabilidade (Marco Civil, arts. 18 a 21), o de direitos do usuário (art. 7º) e o Capítulo IV-A que a Onda 2 redigiu — dever de cuidado, transparência da curadoria, plano de conformidade e auditoria.

**Por que esta formulação é melhor que a anterior.** A versão original desta ideia criava um sujeito novo, com regime próprio. Era invenção sem precedente: o único dispositivo do acervo que responsabilizava diretamente o desenvolvedor por dano era um projeto de lei turco, com defeito de técnica. A técnica da definição faz o mesmo trabalho com uma linha de emenda, e tem precedente de aplicação.

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| **União Europeia** | AI Act, art. 3º, 3 | **Técnica da definição**: "provedor" é quem "desenvolve um sistema de IA ou um modelo de uso geral" |
| **União Europeia** | AI Act, arts. 51 a 55 | Regime próprio dos **modelos de uso geral**: documentação, informação ao integrador, política de direitos autorais, resumo público do conteúdo de treinamento; em risco sistêmico, avaliação, testes adversariais, relato de incidentes e cibersegurança |
| **União Europeia** | AI Act, art. 25 | Deslocamento de papel: quem põe nome, modifica substancialmente ou muda a finalidade **passa a ser** o provedor |
| Coreia do Sul | Lei nº 20.676/2025, art. 2º, 7, "a" e "b" + art. 34 | Separa desenvolvedor de operador usuário na definição — e o art. 34 alcança os dois |
| China | Medidas de IA Antropomórfica (2026), arts. 9º e 10 | Absorção: um único sujeito, o "provedor", responde por todo o ciclo de vida |
| Turquia | PL 2/3358, MADDE 2 | Agravante penal para o desenvolvedor que, pelo desenho ou treinamento, viabiliza o crime — **projeto**, e dentro do tipo de injúria |

### União Europeia — a definição que resolve o problema

AI Act, art. 3º, 3:

> "**'provedor'** significa uma pessoa singular ou coletiva, autoridade pública, agência ou outro organismo que **desenvolve** um sistema de IA ou um modelo de IA de uso geral **ou que manda desenvolver** um sistema de IA ou um modelo de IA de uso geral **e o coloca no mercado** ou coloca o sistema em serviço sob seu próprio nome ou marca, a título oneroso ou gratuito."

São **dois ramos**: quem desenvolve, e quem manda desenvolver e comercializa. O primeiro alcança o desenvolvedor puro; o segundo, quem encomenda o modelo e o põe no mercado.

E, sobre essa definição, o capítulo dos modelos de uso geral — art. 53:

> "Os fornecedores de modelos de IA de uso geral devem: (a) elaborar e manter atualizada a documentação técnica do modelo, incluindo seu processo de treinamento e teste e os resultados de sua avaliação[…]; (b) elaborar, manter atualizada e disponibilizar informações e documentação aos fornecedores de sistemas de IA que pretendam integrar o modelo[…]; (c) adotar uma política de cumprimento do direito de autor[…]; (d) **elaborar e tornar publicamente disponível um resumo suficientemente detalhado sobre o conteúdo usado para o treinamento** do modelo."

Fonte: `fontes/UE/2024-regulamento-ue-2024-1689-ai-act.pdf` (arts. 3º e 53)

**Três qualificações que o capítulo traz e que a redação brasileira precisa decidir:**

1. **Exceção de código aberto** (art. 53, § 2º): as obrigações de documentação e de informação ao integrador não se aplicam a modelos sob licença livre com pesos públicos — **salvo** modelos com risco sistêmico, para os quais a exceção não vale.
2. **Ajuste fino não cria regime novo** (considerando 109): em caso de modificação ou *fine-tuning*, as obrigações do fornecedor se limitam àquela modificação, complementando a documentação existente.
3. **Risco sistêmico** (art. 55): avaliação do modelo, testes adversariais documentados, acompanhamento e relato de incidentes graves, e nível adequado de cibersegurança.

### Coreia do Sul — a mesma técnica, dentro de um sujeito só

A Lei-Quadro define "operador de negócio de IA" e inclui expressamente o desenvolvedor:

> "7. 'operador de negócio de inteligência artificial' significa[…] (a) **Desenvolvedor de inteligência artificial**: pessoa que desenvolve e fornece inteligência artificial; (b) **Operador usuário**: pessoa que fornece produtos ou serviços usando inteligência artificial fornecida por um operador da alínea (a)."

E o art. 34 impõe os deveres ao "operador de negócio de IA" — expressão que, pela definição, alcança o desenvolvedor.

Fonte: `fontes/Coreia/2025-framework-act-ai-EN.pdf`

### Turquia — o único projeto que imputa diretamente

PL 2/3358, MADDE 2, que insere § 6º ao art. 125 do Código Penal turco:

> "O usuário que direcionar sistemas de inteligência artificial à prática de fato tipificado como crime[…] é considerado autor do crime e é punido nessa qualidade. **Quanto ao desenvolvedor que, pelo desenho ou pelo treinamento do sistema, viabilizar a prática desses crimes, a pena aplicável é aumentada pela metade.**"

Fonte: `fontes/Turquia/2025-turquia-esas-2-3358-teklif-texto-extraido.md`

É **projeto**, e a agravante nasceu dentro do tipo de injúria — limitação material que o desqualifica como modelo.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Marco Civil, arts. 18 e 19** — responsabilidade do **provedor de aplicações de internet** por conteúdo de terceiro.
- **LGPD, art. 5º, VI e VII** — controlador e operador. Alcançam o desenvolvedor apenas na dimensão de dados pessoais.
- **LGPD, arts. 42 e 44** — responsabilidade por dano decorrente de tratamento de dados.
- **Capítulo IV-A do Marco Civil** — ainda não é lei; foi redigido na Onda 2 e alcança o "provedor que utilize sistema de recomendação".

**Falta:**

1. **Definição de "provedor de aplicações de internet".** O Marco Civil usa a expressão nos arts. 15 e 19, mas **não a define**: o art. 5º define "conexão à internet", "aplicações de internet" e "registros", não os sujeitos.
2. **Alcance do desenvolvedor puro** — quem treina o modelo e o licencia, sem publicar conteúdo.
3. **Regra de cadeia de valor** — dever de informação ao integrador.
4. **Regra sobre o modelo de uso geral** — resumo público de treinamento e política de direito autoral.
5. **Regra sobre risco sistêmico** — avaliação, testes adversariais e relato de incidente.

---

## 4. O que a comparação revela

**A lacuna brasileira é de definição, não de arquitetura.** O Marco Civil já tem regime de responsabilidade, direitos do usuário e deveres de transparência — e não alcança o desenvolvedor apenas porque a definição do sujeito não o inclui.

Quatro arquiteturas existem no acervo: agravante penal (Turquia, projeto), reatribuição de papel (UE, art. 25), **técnica da definição com regime próprio** (UE, art. 3º e arts. 51 a 55) e absorção pelo provedor (China). A técnica da definição é a que exige menos invenção legislativa e a que tem precedente de aplicação.

**E há uma consequência que a versão anterior desta ideia não via.** Se o desenvolvedor passa a ser "provedor de aplicações de internet", ele recebe o regime **do Tema 987** — que é o regime interpretado pelo STF, e que recusa responsabilidade objetiva (item 12 da tese). Ou seja: por esta via, o desenvolvedor fica sujeito a responsabilidade **subjetiva**, sem precisar da PEC e sem colidir com a tese.

Isso é uma escolha, não um efeito necessário. Se a preferência for responsabilidade objetiva para o desenvolvedor, aí sim é preciso o § 7º, IV, do art. 220 proposto na Onda 3.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Qual definição alterar** | Marco Civil, art. 5º (novo inciso) × definição autônoma no capítulo de IA × definir em cada lei | Definir no Marco Civil alcança responsabilidade e Capítulo IV-A; definição autônoma não alcança nada por si |
| **Estrutura do verbo** | "desenvolve" × "desenvolve e fornece" × dois ramos (desenvolve / manda desenvolver e comercializa) | O modelo da UE usa dois ramos; "desenvolve" sozinho alcança quem treina para uso próprio |
| **Escopo material** | todo modelo × só modelos de uso geral × só alto risco | O regime europeu separa: capítulo próprio para uso geral, requisitos para alto risco |
| **Código aberto** | excluído × incluído × incluído salvo risco sistêmico | A UE exclui com ressalva de risco sistêmico |
| **Ajuste fino** | cria regime novo × obrigação limitada à modificação | A UE limita à modificação (considerando 109) |
| **Consequência** | todos os deveres × só transparência e informação | Alcance total é coerente, mas inviável para modelo pequeno |
| **Modelos já treinados** | retroativo × só prospectivo | Retroatividade exige documentação que nunca existiu |
| **Objetiva ou subjetiva** | regime do Tema 987 (subjetiva) × objetiva via emenda constitucional | Muda o veículo: uma linha de emenda × PEC |

---

## 6. Lacunas de pesquisa

1. O **PL 2338/2023** não está no acervo — é provável que já trate de fornecedor e desenvolvedor.
2. O **CDC** não está no acervo: "fornecedor" (art. 3º) pode alcançar o desenvolvedor na cadeia de consumo, e isso mudaria o diagnóstico do item 3.
3. Não verifiquei se o **omnibus 2026/1744** alterou os arts. 51 a 55 — a leitura dos dispositivos de alteração indica que não, mas a conferência não foi linha a linha.
4. Não há, no acervo, **definição de "desenvolve"**: ajuste fino conta? treinar sobre modelo de terceiro conta? O considerando 109 do AI Act sugere que sim, limitado à modificação.
5. Não há dado sobre **quantos desenvolvedores de modelo operam no Brasil** — o que impede dimensionar o custo de conformidade.

---

## 7. Perguntas abertas

1. A definição de "provedor de aplicações de internet" passa a abranger **quem desenvolve**, ou só quem desenvolve **e fornece**?
2. O **ajuste fino** de modelo de terceiro cria obrigação própria ou se limita à modificação?
3. **Código aberto** fica fora, com ou sem ressalva de risco sistêmico?
4. A responsabilidade do desenvolvedor é **subjetiva** (regime do Tema 987) ou **objetiva** (exige a PEC)?
5. O regime alcança **todo** modelo ou só uso geral e alto risco?
6. **Modelos já treinados** ficam sujeitos a algum dever de documentação?
