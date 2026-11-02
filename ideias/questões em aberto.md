# Questões em aberto

Registro dos pontos que ficaram **sem solução** no levantamento — aquilo que a comparação não resolve e que uma proposta precisaria enfrentar antes de virar texto.

Diferente das "perguntas abertas" de cada `Ideia_XXX.md` (que são de desenho, sobre parâmetros daquela proposta), este arquivo guarda os **problemas de pesquisa e de decisão** que atravessam propostas ou que apareceram no caminho antes de haver arquivo próprio.

---

## A — Assistente de IA e veracidade sobre político em campanha eleitoral

**Situação:** proposta ainda não escrita. Surgiu da pergunta sobre obrigar o provedor de IA, durante a
campanha, a **abster-se de responder** quando não puder garantir a veracidade de informação sobre político, **encaminhando o usuário** a um buscador ou a outra fonte confiável.

**Por que não virou arquivo:** não há precedente no acervo. Nenhuma das outras dez jurisdições tem norma
específica para assistente de IA em campanha eleitoral — a regra eleitoral sobre IA no acervo é só brasileira, e é de resolução do TSE.

**O que existe de mais próximo** (nenhum resolve o problema):

| Mecanismo | O que faz |
|---|---|
| TSE, Res. 23.755/2026, art. 28, § 1º-C, II | Veda emitir opinião, indicar preferência eleitoral ou recomendar voto, "inclusive por meio de respostas automatizadas" — exige **neutralidade**, não abstenção |
| Califórnia, SB 243 (chatbots-companheiro, vigente desde 01/01/2026) | Único do acervo com a estrutura "não responda sobre X, encaminhe para Y" — protocolo antissuicídio com encaminhamento a serviços de crise |
| China, Medidas de rotulagem (2025), art. 6º | Distribuidor verifica o rótulo implícito e acrescenta o explícito — rotula, não cala |
| China, Notificação automídia (2023), item 4 | Imputa ao autor o dever de responder pela veracidade; veda "criar informação do nada, tirar de contexto ou distorcer fatos" |
| Índia, IT (Amendment) Rules 2026 | Unidade de *fact-check* do Governo Central para informação sobre negócios do governo; ação "expedita" sobre conteúdo sintético |
| Turquia, PL 2/3358, MADDE 5 | BTK bloqueia emergencialmente conteúdo de IA que ameace ordem pública ou segurança eleitoral — reage depois |

---

### A.1 — Quem decide que o provedor "não pode garantir a veracidade"

**O problema:** o dispositivo depende de um juízo de incapacidade. Se esse juízo é do próprio provedor, o
dever é **autoaferido** e se converte em declaração — a plataforma decide quando está dispensada de responder. Se o juízo é da autoridade, é preciso um **procedimento** (quem pede, com qual fundamento, em qual prazo, com qual recurso), e o acervo não tem modelo disso.

**O que falta no acervo:** nenhum instrumento comparado atribui a alguém o poder de declarar um sistema
"incapaz de verificar" um tema. O mais próximo — a unidade de *fact-check* indiana — declara que uma informação **é falsa**, não que o sistema é **incapaz**.

**Perguntas que a proposta teria de responder:**

1. O juízo é do provedor, da autoridade, ou de um terceiro certificador?
2. Se é do provedor, há dever de **motivar** a abstenção — e perante quem?
3. A incapacidade é por **tema**, por **pergunta** ou por **período**?
4. A abstenção vale só na campanha ou sempre que o tema for político?

---

### A.2 — O que é "fonte confiável"

**O problema:** "direcionar a outra fonte confiável" exige que a lei **nomeie** as fontes, e nomear fontes é
decisão política — não técnica. A lei passa a dizer ao cidadão em quem confiar.

**O que o acervo mostra:** a única norma do conjunto que declara oficialmente o que é falso ou enganoso é a
**unidade de *fact-check* do Governo Central indiano** (IT Rules 2026), restrita a informação sobre "negócios do Governo Central" — e é justamente o dispositivo mais contestado das regras indianas.

**Alternativa que o acervo sugere sem resolver:** o TSE trabalha com **categorias fechadas** de ilicitude
(art. 28, § 4º-A: informações falsas sobre o sistema eletrônico de votação, incitação de crimes contra o Estado Democrático de Direito, subversão da ordem constitucional e violência política contra a mulher). É mais estreito que "informação sobre político", e é verificável.

**Perguntas que a proposta teria de responder:**

1. A lei **nomeia** as fontes (TSE, órgãos oficiais, agências de checagem credenciadas) ou fixa **critérios** de confiabilidade e deixa a designação ao regulamento?
2. Quem credencia as agências de checagem — e com qual controle?
3. A fonte é a mesma para todo tema ou varia por assunto (processo eleitoral, finanças, vida pregressa)?
4. O encaminhamento é obrigatório **antes** ou **depois** da tentativa de resposta?

---

### A.3 — Encaminhar ao buscador transfere o problema

**O problema:** se a resposta é "não sei, procure no buscador", o usuário sai do assistente e cai no
**ranqueamento** do buscador. O dever de abstenção, sozinho, não produz efeito nenhum — ele apenas troca de intermediário.

**Consequência para o conjunto:** a proposta só funciona acoplada a três das vinte:

| Depende de | Para quê |
|---|---|
| **Ideia_018** (autopreferência e interoperabilidade) | Sem regra de ranqueamento, o encaminhamento apenas desloca o problema para outro intermediário |
| **Ideia_004** (transparência e auditabilidade) | Sem saber como o buscador ordena, o usuário não tem como avaliar o que recebeu |
| **Ideia_002 / 003** (composição do feed, impulsionamento político) | Se o conteúdo impulsionado ocupa o topo do resultado, o encaminhamento entrega o usuário ao pago |

**Perguntas que a proposta teria de responder:**

1. O encaminhamento aponta para **buscador**, para **fonte primária** (TSE, Congresso, tribunais) ou para ambos, em ordem definida?
2. Quem responde se o buscador, no topo, exibe conteúdo impulsionado politicamente?
3. O encaminhamento é **link** ou é **resposta estruturada** (fonte + data + trecho)?
4. Há **registro** do encaminhamento — para que se possa auditar quantas abstenções houve e sobre quais temas?

---

### A.4 — Fontes que faltam antes de escrever o arquivo

| Item | Por que é necessário |
|---|---|
| **PL 2338/2023** (Senado) | Verificar se já há regra sobre abstenção ou limite de resposta de sistema generativo |
| **Resolução/portaria do TSE que regulamenta o art. 27-A da Res. 23.755/2026** | É o credenciamento de provedores; o art. 125-B, § 2º condiciona o plano de conformidade a ele |
| **Portaria da Presidência do TSE do art. 125-B, § 3º** | Se já publicada, traz as diretrizes do plano de conformidade — modelo brasileiro mais próximo de um regime completo |
| **EUA — lei estadual ou federal sobre resposta de IA a tema eleitoral** | O acervo só tem o caso da AB 2839 (derrubada em ago/2025, registrada na Ideia_011); falta varredura das demais |
| **União Europeia — orientações da Comissão sobre integridade eleitoral (DSA)** | Não estão no acervo; são o único documento da UE que trata de assistente e eleição |

---

---

## B — Metodologia: os "Falta" foram medidos só contra a lei vigente

**O problema:** quase todas as 20 seções "O que já existe no Brasil (e o que falta)" concluem que algo
"não existe". Essa conclusão é verdadeira em relação ao **direito vigente** e pode ser falsa em relação ao direito **em tramitação** — porque três veículos relevantes estão fora do acervo:

| Fora do acervo | Por que importa |
|---|---|
| **PL 2338/2023** (Senado) | Marco legal da IA; provavelmente já trata de rotulagem, avaliação de risco, responsabilidade e governança de dados — objetos das Ideias 010, 016, 017 e 020 |
| **PL 4218/2025 + PL 4364/2026** (Câmara) | Política Nacional de Soberania Digital e contratação de nuvem — objetos das Ideias 019 e 006 |
| **PL 4752/2025** (Senado) | Marco Legal da Cibersegurança, cria autoridade nacional — objeto da Ideia 006 e da Ideia 007 |

**Consequência:** uma afirmação do tipo "o Brasil não tem X" pode ser contestada na primeira leitura por
quem conhecer esses projetos. E o subsídio à PEC perde força se propuser o que já está em tramitação sem dizer que está.

**Decisão necessária:** incorporar os três projetos ao acervo **antes** de fechar o conjunto, ou declarar em
cada arquivo que a análise é só da lei vigente?

---

## C — Contradições e sobreposições encontradas

### C.1 — A definição de "entrega orgânica" contradiz a premissa da Ideia 001

O bloco de definições de `Ideias.md` define:

> "Entrega orgânica: entrega de postagens na linha do tempo do usuário que acontece apenas devido ao conteúdo ter sido produzido **ou engajado por outro usuário que é seguido** pelo primeiro."

"Engajado por outro usuário que é seguido" é **propagação por grafo social** — conteúdo chega a quem não segue o autor porque alguém que ele segue engajou. Isso não é cronológico: é recomendação.

A Ideia 001, por sua vez, trata "linha do tempo cronológica" como o modo **sem recomendação**. Pela definição do próprio arquivo, a entrega orgânica já contém um sinal de recomendação, e a linha do tempo "cronológica" nunca seria puramente cronológica.

**Decisão necessária:** redefinir "entrega orgânica" como entrega **apenas por autoria** (quem o usuário
segue publicou), e tratar engajamento de seguidos como sinal de recomendação — ou manter a definição e reformular a Ideia 001.

### C.2 — Ideia 002 e Ideia 003 se sobrepõem

A 002 fixa composição do feed (80% de conteúdo não impulsionado de contas seguidas, 20% de impulsionado). A 003 veda o impulsionamento político para quem não segue. Se a 003 passar, o teto de 20% da 002 deixa de ter objeto no conteúdo político — que é o conteúdo mais sensível do conjunto.

**Decisão necessária:** a 003 é **exceção** à 002 (aplicando-se o teto ao que sobra) ou regime **paralelo**
(com contagem própria)?

### C.3 — Ideia 001 esvazia a Ideia 002 no modo padrão

Se o padrão for a linha do tempo cronológica (001), a cota de 80/20 da 002 só incide no modo priorizado — que passa a ser exceção acionada pelo usuário. A proposta de composição do feed vira regra de nicho.

**Decisão necessária:** a cota da 002 vale nos dois modos, ou só no priorizado? Se só no priorizado, a 002
depende de a 001 não ser aprovada na forma atual.

### C.4 — Três arquivos tratam de documentar e verificar risco

| Arquivo | Objeto |
|---|---|
| **009** | dever de avaliar e gerenciar risco de dano, com plano documentado |
| **004** | transparência e auditabilidade dos sistemas de priorização |
| **020** | plano de conformidade, indicadores e auditoria independente |

A fronteira não está definida. A 004 chega a listar como lacuna "auditoria externa de sistemas de recomendação", que é o objeto inteiro da 020.

**Decisão necessária:** definir qual arquivo carrega o quê — avaliação de risco (009), documentação do
algoritmo (004), verificação periódica por terceiro (020) — e remover a sobreposição da 004.

### C.5 — Ideia 014 e Ideia 015 fixam prazos em regimes diferentes

A 014 fixa prazo para cumprimento de ordem de **autoridade**; a 015 fixa prazo para decisão sobre **notificação de usuário**. Os dois prazos convivem, mas nenhum dos arquivos diz como se relacionam quando a mesma remoção é pedida pelas duas vias.

**Decisão necessária:** prazo único por tipo de conteúdo, ou prazos distintos por origem do pedido?

### C.6 — O índice de citação não corresponde ao acervo

`fontes/INDICE.md` se apresenta como o "índice de citação — versão do texto, arquivo, URL de origem". Na prática:

- registra caminhos `brasil/...` em minúscula, mas a pasta é `Brasil/`;
- registra extensão `.html` para leis que estão no acervo como `.md` (`brasil/2018-lei-13709-lgpd.html` × `fontes/Brasil/2018-lei-13709-Lei Geral de Proteção de Dados - texto.md`);
- registra `brasil/2026-resolucao-tse-23755.md`, mas o arquivo é `2026-resolucao-tse-23755-Resolução TSE 23.755 - texto.md`;
- **não tem entrada** para o RGPD (`fontes/UE/2016-regulamento-ue-2016-679-rgpd.md`), para o ECA Digital nem para o Decreto 12.880/2026 — a tese do STF foi acrescentada nesta rodada, manualmente;
- a linha da tese do STF, que acrescentei, usa `Brasil/` em maiúscula — o que deixou o índice **internamente inconsistente**.

**Consequência:** citar por caminho a partir do índice leva a arquivo inexistente. O instrumento que deveria
garantir rastreabilidade é hoje a parte menos confiável do repositório.

**Decisão necessária:** reescrever o índice a partir da listagem real de arquivos (script), ou declarar que
o índice é histórico e criar um novo.

### C.7 — O arquivo com as oito propostas originais está órfão

`ideias/Ideias - cópia.md` é a **lista original das oito propostas**, com a redação de base de todas as formulações citadas nos arquivos `Ideia_001` a `Ideia_007`. O nome ("cópia") sugere descartável; o conteúdo é fonte primária. Nenhum arquivo o referencia, e ele entrou no versionamento nesta rodada.

**Decisão necessária:** renomear para algo como `Ideias - lista original.md`, referenciá-lo em `Ideias.md`
como origem das formulações, ou removê-lo após transcrever o texto para dentro dos arquivos.

### C.8 — Correções feitas nesta rodada

| O que estava errado | Onde | Correção |
|---|---|---|
| Afirmei que faltava o ato de execução do art. 72, § 3º do AI Act | `Ideia_020`, lacunas | O Digital Omnibus **retirou** esse poder; agora só há orientação com modelo voluntário, até 02/09/2027 |
| Descrevi o art. 50 do AI Act sem as alterações do omnibus | `Ideia_010` | Acrescentado: § 7º reescrito (códigos de prática em vez de regras harmonizadas) e prazo de transição até 02/12/2026 |

**Lição de método:** o AI Act é fonte de quatro arquivos (010, 016, 017, 020) e foi alterado em 2026. Citar
o texto consolidado de 2024 sem conferir o omnibus artigo por artigo produz erro — foi o que aconteceu.

---

## D — Decisões pendentes de escopo, veículo e formato

| # | Decisão | Por que está travada |
|---|---|---|
| **D.1** | **Qual órgão** — ANPD, autoridade nova ou a do PL 4752/2025 | 006 (órgão), 007 (registro e sanção) e 020 (auditoria) dependem disso; nenhum dos três pode virar texto antes |
| **D.2** | **Quais das 20 entram no subsídio** | O conjunto completo serve de banco de ideias; o subsídio à PEC precisa de um subconjunto com prioridade |
| **D.3** | **Veículo de cada ideia** — PEC, lei, regulamento ou contrato | Nenhuma das 20 foi classificada. A decisão de arquitetura (PEC = princípios, lei = deveres e sanções, regulamento = detalhe técnico) existe, mas não foi aplicada |
| **D.4** | **Formato do produto final** | "Subsídio" pode ser emendas a uma PEC que ainda não foi protocolada, minuta de PL paralelo, ou texto de justificação. São três documentos diferentes |
| **D.5** | **Público da advocacy** | Parlamentar, assessoria, movimento social ou imprensa — muda o registro e o tamanho |
| **D.6** | **`rascunhos-do-assistente/`** | Seis arquivos em quarentena (substitutivo de PEC, emendas, subsídio, advocacy, banco de ideias). Manter como histórico, arquivar fora do repo ou apagar |
| **D.7** | **Peso do repositório** | `.git` com 27 MB e `fontes/` com 37 MB de PDFs. Decidir se o acervo de fontes fica versionado, ou só o índice com URLs |

---

## E — Análise mais profunda necessária

### E.1 — Constitucionalidade das 20 propostas não foi analisada

Nenhum arquivo enfrenta o teste de constitucionalidade das próprias propostas. O material só registra decisões estrangeiras (AB 2839 derrubada, lei francesa de idade derrubada). Faltam, para o conjunto:

- **liberdade de expressão e informação** (CF, art. 5º, IV e IX; art. 220) contra as Ideias 001, 002, 003, 010, 011, 012 e 015;
- **proporcionalidade** das restrições de desenho (012) e de verificação de idade (008);
- **livre iniciativa** (art. 170 e art. 174) contra a exigência de processamento local (019);
- **devido processo legal** contra a remoção sem ordem judicial (014) e a abstenção obrigatória (bloco A).

Sem isso, o subsídio pode propor o que o STF já sinalizou que não passa — e o próprio STF acabou de fixar tese sobre o art. 19.

### E.2 — "Engajamento estrangeiro" (Ideia 005) não tem definição operacional

"Desconsiderar o engajamento estrangeiro na priorização" exige definir estrangeiro: IP, residência declarada, idioma, país do dispositivo, país da conta? Nenhuma fonte no acervo trata disso, e a definição escolhida muda o alcance da norma (e cria problema de dado pessoal, porque aferir país exige coleta).

### E.3 — Ideia 019 está sem base comparada

Registrado no próprio arquivo, mas é decisão pendente: ampliar o levantamento (China, Rússia, Índia, Vietnã, Indonésia) ou reduzir o escopo da proposta ao que a comparação sustenta (certificação e controle societário, modelo australiano).

### E.4 — Ideia 016 não tem modelo a importar

O único dispositivo que responsabiliza o desenvolvedor é projeto turco, com defeito de técnica. Não há arquitetura consolidada para transplantar — a proposta teria de ser construída, não adaptada.

### E.5 — Nenhuma ideia diz quem sanciona nem com qual escala

Sete arquivos criam dever novo (004, 009, 010, 012, 015, 017, 020) e nenhum define autoridade competente, procedimento ou sanção. A 007 traz escala sancionatória, mas desligada dos deveres das demais.

### E.6 — Nenhum dado de custo ou de impacto econômico no acervo

Afeta a defesa das Ideias 002 (quota), 012 (limites de desenho) e 019 (processamento local): sem número, a discussão vira afirmação contra afirmação.

---

## F — Fontes que faltam (consolidado)

| Fonte | Arquivos que dependem dela |
|---|---|
| **Código Penal** (Decreto-Lei 2.848/1940) | 016 (art. 13), 015 (crimes graves) |
| **CDC** (Lei 8.078/1990) | 015 (item 7 da tese do STF remete *marketplaces* ao CDC), 016 (responsabilidade objetiva) |
| **Lei 12.529/2011** (defesa da concorrência) | 018 — sem ela não se descreve o que o CADE já pode fazer |
| **PL 2338/2023**, **PL 4218/2025**, **PL 4752/2025** | bloco B, acima |
| **Regimento e composição do CGI.br** | 006 (modelo multissetorial) |
| **IN SGD/ME nº 94/2022** | 019 (contratação de nuvem pelo governo federal) |
| **China** — CSL, DSL e PIPL arts. 38 a 43 | 019 (localização) |
| **Rússia** — Lei 242-FZ; **Índia** — DPDP Act 2023; **Vietnã** — Decreto 53/2022; **Indonésia** — Reg. 71/2019 | 019 |
| **UE** — NIS2 e Data Act | 019 (verificar se há restrição de localização) |
| **UE** — orientações da Comissão sobre integridade eleitoral (DSA) | bloco A (assistente e eleição) |
| **RGPD** — já arquivado, mas **sem entrada no índice** | 017 (definição de perfilamento, art. 4º, 4) |

---

## G — Regras do próprio trabalho que já foram violadas

| Regra | Onde foi violada |
|---|---|
| "Toda afirmação remete a fonte oficial" | **Resolvido em parte:** o acordo Meta × procuradores-gerais entrou no acervo em texto integral (`fontes/EUA/2026-acordo-meta-51-procuradores-gerais-consent-judgment.pdf`) e a Ideia_001 foi reescrita sobre a fonte primária. **Continua pendente:** a decisão da AB 2839 (Ideia_011) segue só em `pesquisa/noticias/` |
| "Toda afirmação tem URL ou artigo" | 013 cita Código Civil art. 1.138, 016 cita Código Penal art. 13 e 015 cita o CDC (item 7 da tese do STF) — nenhum dos três tem arquivo de origem no acervo |
| Índice analítico atualizado | `fontes/Brasil/Índice.md` não tem entrada para o ECA Digital, o Decreto 12.880/2026 nem a tese do STF |

---

## Como usar este arquivo

Cada bloco recebe um identificador (A a G) e os pontos entram numerados dentro dele.

- **A** e **C** são de conteúdo: propostas e contradições entre arquivos.
- **B**, **F** e **G** são de método: o que falta levantar e o que já saiu da regra.
- **D** e **E** são de decisão: o que trava o avanço até você definir.

Quando um ponto for resolvido — por decisão sua ou por fonte nova — a linha sai daqui e vai para o arquivo da ideia correspondente, ou para `pesquisa/` se for achado de levantamento.
