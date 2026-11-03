# Plano de execução

Como o trabalho se organiza: quais propostas servem a qual objetivo, em qual lei cada uma se pendura, e o que dá para fazer sem aprovação legislativa nenhuma.

Este arquivo **não decide** nada. Ordena o que existe, marca a técnica de cada proposta e deixa explícito o que depende de decisão sua.

---

## 1. O objetivo

Criar um arcabouço legal forte, calcado em mandato constitucional, que permita coibir a operação das plataformas contra o interesse nacional — em especial a tomada de partido em eleições. E, junto com isso, aquilo que deveria existir de todo modo, porque decorre de transparência, responsabilidade e função social.

São duas linhas que se complementam, e a diferença entre elas não é de intensidade: é de **alicerce**.

## 2. As duas linhas

| | **Linha A — contenção** | **Linha B — função social** |
|---|---|---|
| Objeto | operação contra o interesse nacional e o processo político-eleitoral | transparência, responsabilidade, devido processo |
| Fundamento | soberania nacional (CF, art. 1º, I) — **sem mandato específico hoje** | função social (CF, art. 5º, XXIII e art. 170, III), art. 220, art. 5º, LXXIX |
| Depende da PEC | **sim** | **não** |
| Caráter | excepcional: janela, sujeito e urgência definidos | permanente: geral, procedimental, gradual |
| Prazo típico | horas | dias |
| Sanção típica | suspensão, cancelamento de habilitação, responsabilidade objetiva | multa, dever de informar, dever de recorrer |

**Consequência que organiza tudo:** a Linha B pode começar hoje, por emenda às leis existentes. A Linha A precisa do mandato constitucional para não ser lida como restrição desproporcional à liberdade de expressão e à livre iniciativa.

## 3. Distribuição das propostas

| Linha A — contenção | Linha B — função social | Servem às duas |
|---|---|---|
| 003 impulsionamento político | 001 feed não algorítmico | 006 órgão de governança |
| 005 engajamento estrangeiro e bots | 002 cota de composição do feed | 007 registro prévio e escala |
| 011 janela de silêncio eleitoral | 004 transparência dos algoritmos | 010 rotulagem de conteúdo sintético |
| 014 cooperação com prazos | 009 dever de cuidado | 025 escala de 3 degraus |
| 019 processamento local | 012 restrições de desenho para menores | |
| 021 monetização de perfis politicamente relacionados | 013 representante legal | |
| 024 responsabilidade objetiva por dano à soberania | 015 responsabilidade do intermediário | |
| | 016 responsabilidade do desenvolvedor | |
| | 017 transparência de datasets | |
| | 018 autopreferência e interoperabilidade | |
| | 020 conformidade e auditoria | |
| | 022 devido processo da moderação | |
| | 023 transparência da ponderação | |

## 4. Complementaridade — o que eu errei e por que importa

Em conversa anterior eu registrei que haveria "tensão" entre as linhas, com "dois relógios" disputando o mesmo prazo. **Está errado.** Não há tensão; as linhas operam em momentos distintos:

| Momento | O que acontece | Linha |
|---|---|---|
| t = 0 | plataforma aplica a medida | A |
| t = 0 | plataforma entrega motivo, dispositivo e evidências | B — **contemporâneo, não prévio** |
| t > 0 | usuário recorre | B |
| t + prazo | plataforma decide o recurso, por pessoa | A (urgência) e B (devido processo) |

O motivo não atrasa a remoção: o DSA, art. 17, § 2º, exige a declaração "o mais tardar a partir da data em que a restrição é imposta". E o "4 horas" nunca foi prazo de remoção — é prazo de **decisão do recurso**.

**O mecanismo que produz a complementaridade:** a velocidade substitui a suspensão. Devido processo normalmente exige notificação prévia (que impediria a remoção) ou efeito suspensivo (que devolveria o conteúdo). Com prazo de 30 dias, seria preciso suspender — e aí sim a Linha A perderia. Com 4 horas, não é preciso: o dano fica limitado a quatro horas. A urgência não restringe o direito; é o que torna dispensável a medida mais protetiva.

### A única decisão que sobra nesse ponto

**O que acontece se o prazo vencer sem decisão?**

| Opção | Efeito | A quem serve |
|---|---|---|
| **Reversão automática da medida** | a medida caduca se não houver decisão humana no prazo | garante a Linha B e dá exigibilidade ao prazo da A |
| Multa pelo descumprimento | a medida continua; a plataforma é sancionada | garante a A, mas o usuário espera |
| Nada | o prazo é decorativo | nenhuma |

A reversão automática é a única que **acopla** as duas: o prazo da Linha A passa a ser exigível **através** do remédio da Linha B.

### Uma restrição operacional, não uma tensão

Escrever decisão fundamentada em 4 horas não é possível se o motivo for redigido do zero. A norma implica que o sistema **gere a fundamentação no momento da medida** — dispositivo violado identificado, evidências anexadas, texto a partir de modelo — e que a pessoa no recurso apenas confirme ou reverta. É requisito de engenharia que a Ideia_022 precisa declarar, sob pena de o prazo ser inexequível para quem tem volume.

## 5. Técnica de cada proposta

Três categorias, da menor à maior fricção.

### 5.1 Já dá para fazer sem lei nova, por regulamento

Dentro do que a lei vigente já autoriza:

O instrumento não é decreto nem projeto de lei: é **norma complementar da autoridade**, no caso do ECA Digital por força do art. 34 ("poderá editar normas complementares para regulamentar os seus dispositivos").

| O quê | Base que autoriza | Quem edita | Estado |
|---|---|---|---|
| Prazos de recurso e de resposta | ECA Digital, art. 30, V e art. 33, § 2º, IV | autoridade do art. 34 — na prática, ANPD | não editado |
| Diretrizes de supervisão parental | ECA Digital, art. 17, § 1º | idem | não editado |
| Diretrizes do plano de conformidade eleitoral | Res. TSE 23.755, art. 125-B, § 3º | Presidência do TSE | portaria não publicada |
| Padrões de interoperabilidade e portabilidade | LGPD, art. 40 | ANPD | nunca exerceu |
| Auditoria de decisão automatizada | LGPD, art. 20, § 2º | ANPD | poder nunca usado |
| Nuvem no setor público | Lei 14.129 + IN SGD/ME 94/2022 | SGD/MGI | vigente, sem exigência de residência |

Cobre **parte** das Ideias 008, 020 e 022 — e nada além disso.

**Atenção ao Decreto 12.880/2026:** ele já regulamenta o ECA Digital e atribui à ANPD várias competências técnicas (método de aferição de idade, credenciamento de entidades). Mas **não fixou os prazos do art. 30, V** nem os padrões mínimos do art. 17, § 1º — que continuam pendentes. Ao propor qualquer coisa nesta frente, conferir o decreto antes, para não duplicar.

### 5.2 Plug-in em lei existente — a lei já tem o dispositivo, falta o conteúdo

| Ideia | Âncora | O que muda |
|---|---|---|
| **003** | Lei 9.504, art. 57-C, *caput* | revogar a exceção do impulsionamento |
| **015** | Marco Civil, art. 19 | acrescentar notificação, prazo e consequência no mesmo artigo |
| **013** | Marco Civil, art. 11 | o artigo fixa jurisdição; falta o sujeito citável |
| **022** | Marco Civil, art. 7º (novo inciso) + art. 19 | o direito no 7º, a consequência no 19 |
| **014** | Marco Civil, arts. 22 e 23 | hoje o prazo é do juiz; passa a ser da lei |
| **001** | Marco Civil, art. 7º (novo inciso) | o art. 4º, IV trata de interoperabilidade como objetivo, não como direito |
| **004 / 023** | Marco Civil, art. 7º (novo inciso) + novo capítulo | a LGPD, art. 20 alcança dado pessoal; curadoria de conteúdo não é dado pessoal |
| **009 / 020** | Marco Civil, novo capítulo | o ECA, arts. 8º e 31 valem só para menores |

### 5.3 Extensão de escopo — emenda de substância

A lei existe, mas foi feita para outro universo:

| Ideia | Lei existente | Limite atual |
|---|---|---|
| **010** | Res. TSE 23.755, art. 9º-B | só propaganda eleitoral |
| **011** | Res. TSE, art. 9º-B, § 3º-A | só conteúdo sintético, e por resolução |
| **016** | Marco Civil, art. 5º (definição) | a lei não define "provedor de aplicações"; emenda à definição arrasta todo o regime — ver Ideia_016 reescrita |
| **017** | Marco Civil, Capítulo IV-A (novo artigo) | a LGPD só alcança dado pessoal; governança de dataset de treinamento não é matéria de proteção de dados |
| **018** | **lei nova** — Lei de Mercados Digitais | autopreferência e designação por escala não cabem na Lei 12.529 nem na LGPD; ver item 5.4 |
| **025** | Marco Civil, art. 12 | a escala existe; a especificação é emenda |

**Encerradas sem extensão:**

- **008** — a exigência já é lei: ECA Digital, art. 9º, § 1º (verificação a cada acesso, vedada autodeclaração), com o art. 13 limitando a finalidade dos dados. O que faltava é padrão técnico, tarefa da ANPD já delegada pelo Decreto 12.880/2026 — Onda 0, não lei. A extensão universal esbarra no caso francês.
- **012** — limite de tempo e bloqueio noturno para adultos não se sustentam. A ideia fica como está no ECA Digital, para criança e adolescente. Para adultos, o que resta é o art. 23-D do Anteprojeto C — desativar reprodução automática e notificações de reengajamento —, que já está redigido.

### 5.4 Lei nova — sem base em lugar nenhum

| Ideia | Por que não cabe | Precisa da PEC? |
|---|---|---|
| **008 / 012 (parte geral)** | o ECA é lei de criança e adolescente: não se estende, serve de modelo | decidir |
| **002** cota de feed | o Marco Civil não regula composição de feed | não |
| **005** engajamento estrangeiro e bots | "integridade" não tem capítulo | provável |
| **006** órgão | a LGT é modelo de técnica, não base | se for órgão constitucional |
| **007** registro prévio | a escala existe; a habilitação prévia não | não |
| **019** processamento local (geral) | só o Redata tem, e como condição de benefício fiscal | provável |
| **021** monetização de perfis | nenhuma lei brasileira regula monetização | provável |
| **024** responsabilidade objetiva | o STF recusou a objetividade no Tema 987, item 12 | **sim** |

**Exceção dentro da 019:** a versão para o **setor público** cabe em emenda à Lei 14.129, sem lei nova. A versão geral, não.

## 6. Sequenciamento sugerido

Não é decisão — é a ordem que a técnica impõe, com o custo de cada onda.

**Onda 0 — sem passar pelo Congresso.** Regulamentos e portarias pendentes (item 5.1). Custo: zero legislativo. Entrega: prazos de recurso, diretrizes de supervisão, padrões de interoperabilidade, auditoria pela ANPD.

**Onda 1 — emendas de baixa fricção.** Os seis plug-ins do item 5.2. Custo: seis projetos de emenda, todos com dispositivo existente como âncora. Entrega: o núcleo da Linha B e a proibição de impulsionamento político.

**Onda 2 — as extensões de escopo.** Item 5.3. Custo: enfrentar o argumento de que se está estendendo a todo usuário um regime feito para menores. Entrega: o resto da Linha B.

**Atenção — "extensão de escopo" são duas coisas diferentes:**

| Tipo | Quando ocorre | Ideias |
|---|---|---|
| **Emenda dentro da própria lei** | a matéria já é daquela lei; o que limita é o dispositivo, não o objeto | 011 e 025 |
| **Transposição** | o que limita é o **objeto** da lei — o ECA é de criança e adolescente, e não se estende; serve de modelo para capítulo novo | 008, 009, 012 e a parte geral de 010, 016, 020 |

A distinção muda o veículo: emenda, no primeiro caso; capítulo novo ou lei nova, no segundo.

**Onda 3 — a Linha A.** A PEC com o mandato constitucional, e depois as leis novas (002, 005, 006, 007, 019, 021, 024). Custo: quórum de PEC (171 assinaturas, 308 e 49 votos, dois turnos) e o debate constitucional. Entrega: o objetivo principal do projeto.

**A ordem não é obrigatória.** Há um argumento para inverter 1 e 3: a tramitação da PEC cria janela pública para as emendas da Linha B. É escolha sua.

## 7. O que trava o plano

Depende de decisão sua, e está detalhado em [[questões em aberto]]:

| Item | Trava |
|---|---|
| **D.1** qual órgão | 006, 007 e 020 — **decidida provisoriamente: ANPD ampliada**, com anteprojeto de competências redigido |
| **D.3** veículo de cada ideia | este arquivo resolve parcialmente; falta confirmar as marcadas como "provável" |
| **D.4** formato do produto | plano, emendas ou minuta de PEC |
| **C.4** fronteira entre 009, 004 e 020 | três arquivos sobre documentar e verificar risco |
| **C.2 / C.3** sobreposição 002–003 e 001–002 | muda o que entra em cada emenda |
| [[Glossário]] — `entrega orgânica` | afeta 001, 002 e 005 |

## 8. Estado do acervo de propostas

| Bloco | Arquivos | Estado |
|---|---|---|
| A — distribuição de conteúdo | 001 a 005 | escritos |
| B — instituições e sanções | 006, 007, 013, 014 | escritos |
| C — menores e conteúdo sintético | 008 a 012 | escritos |
| D — responsabilidade e infraestrutura | 015 a 020 | escritos |
| Novas, com arquivo | 021 monetização · 022 devido processo · 023 ponderação · 024 responsabilidade objetiva · 025 três degraus | escritos |
| Instrumentos | [[Glossário]] · [[questões em aberto]] · `rascunhos-do-assistente/2026-rascunho-lei-dano-soberania.md` | escritos |
