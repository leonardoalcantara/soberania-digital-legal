# Ideia 020 — Plano de conformidade e auditoria independente

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Criar obrigação **periódica** de a plataforma **demonstrar** conformidade — com plano prévio, indicadores mensuráveis e verificação por terceiro independente.

Sob o mesmo nome circulam quatro instrumentos distintos, com funções diferentes:

| Instrumento | Quando | Função |
|---|---|---|
| **Avaliação de impacto** | antes de operar | Prever o risco |
| **Plano de conformidade** | antes e durante | Fixar metas e indicadores |
| **Relatório de transparência** | periodicamente | Publicar o que foi feito |
| **Auditoria** | periodicamente | Verificar, por terceiro, se o que foi publicado corresponde ao que acontece |

É a proposta que trata do **ônus da prova**: quem tem de demonstrar que cumpre — e a quem.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| União Europeia | DSA, art. 37 | Auditoria **independente, anual, às expensas da plataforma**, com regras de conflito de interesse |
| União Europeia | DSA, art. 42, § 4º | Publicação, em até 3 meses, do relatório de risco, das medidas, do **relatório de auditoria** e do relatório de implementação |
| União Europeia | AI Act, art. 43 e 44 | **Avaliação de conformidade** prévia, com ou sem organismo notificado; certificado válido por 4 ou 5 anos |
| União Europeia | AI Act, art. 72 | **Sistema de monitoramento pós-comercialização**, documentado, proporcional ao risco |
| Reino Unido | Online Safety Act 2023, Anexo 12, § 4º | **Auditoria conduzida pelo regulador**, por aviso, com 28 dias de antecedência e custo exigível do provedor |
| Coreia do Sul | Lei-Quadro de IA, arts. 32, 34 e 35 | Verificação e certificação **voluntárias**; dever de manter documentos comprobatórios; avaliação de impacto de direitos fundamentais |
| China | Medidas de IA Antropomórfica (2026), art. 17 | **Auditoria de conformidade** sobre tratamento de dados pessoais de menores de 14 anos |

### União Europeia — a auditoria anual, escolhida e paga pela plataforma

DSA, art. 37, § 1º:

> "Os prestadores de plataformas online de muito grande dimensão e de motores de busca online de muito grande dimensão ficarão sujeitos, **às suas próprias expensas e pelo menos uma vez por ano**, a auditorias independentes para avaliar o cumprimento: (a) das obrigações previstas no Capítulo III; (b) dos compromissos assumidos nos termos dos códigos de conduta[...]"

E o § 3º define quem pode ser auditor — é a parte mais operacional do dispositivo:

> "As auditorias [...] serão realizadas por organizações que: (a) sejam independentes e não tenham conflitos de interesse com o prestador [...]; em particular: (i) **não tenham prestado serviços que não sejam de auditoria** relacionados com as matérias auditadas ao prestador nos **12 meses** anteriores ao início da auditoria e se comprometam a não os prestar nos **12 meses** seguintes; (ii) não tenham prestado serviços de auditoria ao prestador por período superior a **10 anos consecutivos**; (iii) não recebam honorários **contingenciados ao resultado** da auditoria; (b) tenham experiência comprovada em gestão de riscos, competência técnica e capacidades; (c) tenham objetividade e ética profissional comprovadas[...]"

Fonte: `fontes/UE/2022-regulamento-ue-2022-2065-dsa.pdf`

E o art. 42, § 4º, fecha o ciclo com a publicidade:

> "[...] tornar públicos, o mais tardar três meses após o recebimento de cada relatório de auditoria: (a) relatório com os resultados da avaliação de risco; (b) as medidas de mitigação específicas adotadas; (c) o **relatório de auditoria**; (d) o **relatório de implementação da auditoria**."

**O que o desenho tem de sofisticado:** as três regras de conflito de interesse — defasagem de 12 meses antes e depois, limite de 10 anos e vedação de honorário contingente. Sem elas, a auditoria paga pela plataforma é um contrato, não uma verificação.

### Reino Unido — o regulador audita, não recebe auditoria

Online Safety Act 2023, Anexo 12, § 4º:

> "A OFCOM pode dar ao provedor de um serviço regulado um aviso (um 'aviso de auditoria') exigindo que o provedor permita que a OFCOM realize uma auditoria — para avaliar se o provedor cumpriu ou está cumprindo requisitos exigíveis aplicáveis ao serviço, ou para avaliar a natureza e o nível de risco de descumprimento e as formas de mitigá-lo."

E o § 8º:

> "A OFCOM pode exigir que o provedor pague parte ou a totalidade dos custos razoáveis de uma auditoria realizada nos termos de um aviso de auditoria."

Fonte: `fontes/Reino-Unido/2023-online-safety-act.md` (Anexo 12, § 4º)

Detalhes de execução: o aviso deve ser dado com **pelo menos 28 dias** de antecedência, não pode alcançar domicílio residencial nem material protegido por sigilo profissional, e o descumprimento é **infração penal**.

**A diferença em relação ao modelo europeu:** no DSA a plataforma contrata o auditor; no Reino Unido o regulador **faz** a auditoria. O primeiro modelo escala melhor; o segundo depende de capacidade estatal.

### Coreia do Sul — certificação voluntária, documento obrigatório

Lei-Quadro de IA, art. 32, § 3º:

> "O operador de negócio de inteligência artificial deverá **envidar esforços para obter verificação e certificação previamente** ao fornecer inteligência artificial de alto impacto."

E o art. 34, § 1º, 5:

> "[...] preparar e **manter documentos que possam comprovar** o conteúdo das medidas adotadas para assegurar a segurança e a confiabilidade[...]"

Fonte: `fontes/Coreia/2025-framework-act-ai-EN.pdf`

**A escolha coreana é a mais leve das três:** certificação voluntária, mas documentação obrigatória. Quem não se certifica continua tendo de provar que agiu.

### União Europeia — a avaliação prévia como condição de mercado

AI Act, art. 43, § 1º, sobre sistemas de alto risco do Anexo III:

> "Para demonstrar a conformidade [...] o fornecedor deverá optar por um dos seguintes procedimentos de avaliação de conformidade: (a) o **controle interno** previsto no Anexo VI; ou (b) a avaliação do sistema de gestão da qualidade e a avaliação da documentação técnica, **com o envolvimento de um organismo notificado**, previstas no Anexo VII."

E o art. 44, § 2º, fixa a validade do certificado: **até 5 anos** para sistemas do Anexo I e **até 4 anos** para sistemas do Anexo III, renovável por períodos iguais mediante reavaliação.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **TSE, Res. 23.755/2026, art. 125-B** — o dispositivo brasileiro mais completo sobre o tema:

> "Os provedores de aplicação de internet deverão, nos termos, prazos e diretrizes editados pela Presidência do Tribunal Superior Eleitoral, elaborar **plano de conformidade** destinado à prevenção e à mitigação de riscos à integridade do processo eleitoral[...]"
>
> "§ 1º O plano de conformidade deverá conter, no mínimo: I - deveres e medidas de conformidade apontadas para cada disposição desta Resolução; II - **critérios e indicadores mensuráveis e periódicos** para acompanhamento de sua implementação; III - prazos, resultados esperados e **trajetória de alcance**."
>
> "§ 2º O cumprimento do disposto neste artigo constitui **requisito para o credenciamento**[...]"

É plano de conformidade com indicadores mensuráveis e **condição de exercício da atividade** — mas vale só no período eleitoral e por resolução de tribunal.

- **ECA Digital (Lei 15.211/2025), art. 31** — relatórios **semestrais** em português, publicados no sítio do provedor, com canais de denúncia, quantidade de denúncias, quantidade de moderação por tipo, medidas de identificação de contas infantis, aprimoramentos técnicos de proteção de dados, aprimoramentos para aferir consentimento parental e "o detalhamento dos métodos utilizados e a apresentação dos resultados das avaliações de impacto". Alcança provedores com **mais de 1.000.000 de usuários** na faixa etária.
- **STF, RE 1037396 (Tema 987), itens 8 e 10** — dever de editar autorregulação que abranja sistema de notificações, devido processo e **relatórios anuais de transparência** quanto a notificações extrajudiciais, anúncios e impulsionamentos, com publicação e revisão periódica.
- **LGPD, art. 20, § 2º** — a autoridade nacional poderá realizar **auditoria** para verificação de aspectos discriminatórios quando o controlador invocar segredo comercial.
- **Redata (Lei 15.504/2026), art. 11-B, § 5º** — a comprovação anual da destinação do fornecimento efetivo "deverá ser comprovada anualmente por **relatório consolidado e parecer conclusivo elaborados por auditoria independente, credenciada pelo Poder Executivo federal**, que ateste a veracidade das informações prestadas". Fonte: `fontes/Brasil/2026-lei-15504-Redata - texto.md`
- **Marco Civil, art. 12** — escala sancionatória por infração às regras de guarda e jurisdição.

**Falta:**

1. **Auditoria independente sobre plataformas e IA.** Existe no Redata — auditoria credenciada pelo Poder Executivo — mas para comprovar **destinação de capacidade**, não conformidade de conduta. Não há auditoria independente de plataforma ou de sistema de IA em nenhuma norma vigente.
2. **Regras de conflito de interesse do auditor** — defasagem, limite temporal, vedação de honorário contingente.
3. **Publicação do relatório de auditoria.** Não há dever de publicar verificação, só de publicar relatório do próprio provedor.
4. **Periodicidade fora do período eleitoral** e fora do universo de menores.
5. **Plano de conformidade como obrigação geral** — hoje só como condição de credenciamento eleitoral.
6. **Sanção por não demonstrar**, distinta da sanção por violar. Hoje o descumprimento do dever de informar não tem consequência própria.
7. **Padronização de indicadores.** Cada norma pede indicadores diferentes, sem métrica comum — o que impede comparação entre plataformas.

---

## 4. O que a comparação revela

**O acervo mostra que existem quatro modelos de verificação, e a escolha entre eles é a decisão central:**

| Modelo | Quem escolhe o auditor | Quem paga | Quem vê o relatório |
|---|---|---|---|
| **DSA, art. 37** | A plataforma | A plataforma | Autoridade e público (3 meses) |
| **OSA, Anexo 12** | O regulador | A plataforma (reembolso) | O regulador |
| **AI Act, art. 43** | A plataforma (organismo notificado) | A plataforma | Autoridade e mercado |
| **Coreia, art. 32** | A plataforma (voluntário) | A plataforma | Ninguém, por força de lei |

**O Brasil está no ponto de partida mais avançado do que se costuma supor, e no ponto de chegada mais distante.** O art. 125-B da Resolução do TSE já tem plano de conformidade com indicadores e trajetória de alcance — desenho que a UE só tem para risco sistêmico. E o art. 31 do ECA Digital já impõe relatório semestral publicado. O que não existe, em nenhum dos dois, é **verificação por terceiro**.

O único precedente brasileiro de auditoria independente com credenciamento estatal está fora desse campo: o art. 11-B, § 5º do Redata. Ele verifica **destinação de capacidade**, não conduta — mas é a única prova, no direito brasileiro, de que o desenho é operacionalmente possível.

**A lição mais transferível é a do DSA, § 3º do art. 37:** o problema da auditoria paga pela plataforma não é o pagamento, é o conflito de interesse. As três regras — 12 meses de defasagem, 10 anos de limite, vedação de honorário contingente — são o que separa auditoria de consultoria.

**A lição do Reino Unido** é que auditoria conduzida pelo regulador exige capacidade estatal instalada — 28 dias de antecedência, poder de entrada, custo reembolsado e infração penal por descumprimento. É o modelo mais robusto e o mais caro.

**A lição coreana** é a mais barata: certificação voluntária, documentação obrigatória. Não verifica, mas desloca o ônus da prova.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Instrumento** | avaliação de impacto × plano de conformidade × relatório × auditoria | São quatro coisas; a escolha de uma não entrega as outras |
| **Quem audita** | auditor contratado pela plataforma (DSA) × regulador (OSA) × organismo notificado (AI Act) | Contratado escala; regulador é mais independente e mais caro |
| **Quem paga** | plataforma × órgão × compartilhado | Pagamento pela plataforma é padrão no acervo; não elimina o conflito |
| **Conflito de interesse** | regras do art. 37, § 3º × declaração simples × silêncio | Sem regra, a auditoria vira serviço contratado |
| **Periodicidade** | anual × semestral × por evento | Anual é o padrão; semestral já existe no ECA Digital para menores |
| **Publicidade** | relatório completo × versão pública com supressões × só à autoridade | Publicidade é o que permite escrutínio externo; supressões podem esvaziar |
| **Universo alcançado** | por escala (1 milhão de usuários) × por risco × todos | Escala é objetiva; risco exige classificação prévia |
| **Indicadores** | definidos em lei × em regulamento × pela própria plataforma | Definidos pela plataforma não permitem comparação |
| **Consequência** | sanção por não demonstrar × presunção de descumprimento × ambas | Presunção desloca o ônus da prova sem criar infração nova |
| **Autoridade** | ANPD × nova autoridade × TSE (no período eleitoral) | Escolha institucional em aberto (ver Ideia 006) |

---

## 6. Lacunas de pesquisa

1. Não há, no acervo, **custo estimado** de auditoria independente para plataformas de médio porte — o que é decisivo para definir o universo alcançado.
2. Não verifiquei se a **Presidência do TSE** já editou a portaria do art. 125-B com as diretrizes do plano de conformidade. Se existir, é o modelo brasileiro mais próximo de um regime completo.
3. Não há, no acervo, **relatórios semestrais** já publicados com base no art. 31 do ECA Digital — o que impediria avaliar se o modelo funciona na prática.
4. Não localizei **organismos de auditoria** credenciados no Brasil para plataformas ou IA.
5. Não há, no acervo, precedente de **auditoria realizada** sob o art. 37 do DSA — só o desenho normativo.

**Nota sobre o art. 72 do AI Act:** o modelo de plano de monitoramento pós-comercialização não existe e não vai existir como ato de execução. O Regulamento (UE) 2026/1744 (Digital Omnibus) **retirou** do art. 72, § 3º o poder de a Comissão adotar ato de execução e passou a exigir apenas a publicação de **orientação com modelo voluntário**, até 02/09/2027. Não é lacuna de acervo — é mudança de regime, e sinaliza que a UE está trocando norma vinculante por orientação em parte da matéria.

---

## 7. Perguntas abertas

1. A proposta cria **plano de conformidade**, **relatório de transparência**, **auditoria** — ou os três em sequência?
2. Quem audita: auditor contratado pela plataforma, regulador ou organismo credenciado?
3. Quais são as **regras de conflito de interesse** do auditor?
4. O relatório de auditoria é **público**, público com supressões ou só da autoridade?
5. Qual o **universo alcançado** — por número de usuários, por risco ou todos?
6. Os **indicadores** são definidos em lei, em regulamento ou pela plataforma?
7. Qual a **consequência de não demonstrar** conformidade — sanção autônoma ou presunção de descumprimento?
8. A obrigação **substitui** o plano de conformidade do art. 125-B do TSE ou convive com ele?
