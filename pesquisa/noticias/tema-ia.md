# Frente temática — IA: rotulagem, deepfakes, responsabilidade e controle de modelos (2025–2026)

**Corte de pesquisa:** 31/10/2026 · **Frente:** IA — rótulo, deepfake, responsabilidade, controle de modelo
**Pergunta que cada linha responde:** o que estão tentando limitar, e por qual instrumento?

**Régua aplicada (não misturar):** `PROPOSTA` ≠ `LEI VIGENTE` ≠ `ENFORCEMENT` ≠ `BARRADO EM TRIBUNAL`.
Nesta frente quase tudo já é norma posta — e o instrumento típico não é proibir o modelo, é **obrigar o
rótulo, o relatório e o teste**. A exceção é o controle de chips, que é comércio exterior, não regulação de IA.

## 0. Leitura de conjunto (4 achados que organizam o resto)

1. **O eixo 2025–2026 é a rotulagem obrigatória, e ela já vigora em quatro mercados grandes.** China
   (01/09/2025), Índia (20/02/2026), Coreia (22/01/2026) e UE (02/08/2026) convergiram para o mesmo desenho:
   rótulo visível **+** metadado/proveniência **+** dever de não remover a marca **+** verificação pela
   plataforma. É o primeiro conjunto de obrigações de IA que incide direto sobre o produto da big tech.
2. **A responsabilidade civil clássica quase não aparece.** O que aparece é *transparência de fronteira*:
   protocolo de segurança publicado, avaliação de terceiro, relatório de incidente em 72 h (NY) ou 15 dias
   (Califórnia), com multa administrativa — não indenização. Quem processa é o attorney general, não o usuário.
3. **A restrição a modelo estrangeiro é o instrumento mais frágil e mais volátil.** Nenhum país pesquisado
   proibiu por lei o *modelo*; existe bloqueio de *app* (Itália), proibição em *dispositivo oficial*
   (Austrália, estados dos EUA) e suspensão de *download* (Coreia). Todas são medidas administrativas
   reversíveis — e a coreana foi revertida em 91 dias.
4. **A força contrária está dentro dos EUA.** A ordem executiva de 11/12/2025 manda o DOJ atacar leis
   estaduais de IA, e as duas leis de deepfake eleitoral da Califórnia já caíram no Judiciário (2025). Em
   31/10/2026, a limitação mais dura às big techs em IA **não** vem de Washington.

## 1. Tabela-síntese

| # | Item | País/instância | Tipo | Data | Status | Mecanismo concreto |
|---|------|----------------|------|------|--------|--------------------|
| 3.1 | Art. 50 do AI Act + Código de Práticas de Transparência | UE | Regulamento + código de práticas | Diretrizes 20/07/2026; CoP 09/07/2026; aplicável 02/08/2026 | **Vigente** | Marcar conteúdo sintético em formato legível por máquina; revelar deepfake; avisar que se fala com IA |
| 3.2 | 《标识办法》 + norma GB 45438-2025 | China | Medida administrativa + norma obrigatória | 14/03/2025; vigência 01/09/2025 | **Vigente** | Rótulo explícito + implícito (metadado); plataforma verifica e não pode apagar marca |
| 3.3 | Framework Act on AI, art. 31 + diretrizes MSIT | Coreia do Sul | Lei + diretriz | Vigência 22/01/2026; diretrizes 27/01/2026 | **Vigente** | Dever de informar o usuário de que o resultado é gerado por IA |
| 3.4 | IT (Intermediary Guidelines) Amendment Rules, 2026 | Índia | Regra de execução (MeitY) | Notificada 10/02/2026; vigência 20/02/2026 | **Vigente** | Rótulo proeminente + metadado permanente + ID único; declaração do usuário; perda de *safe harbour* |
| 3.5 | AB 853 + SB 942 (AI Transparency Act) | EUA / Califórnia | Lei estadual | Sancionada 13/10/2025; vigência 02/08/2026 (com carência) | **Vigente em carência** | Ferramenta de detecção, proveniência em plataforma grande, marca latente em dispositivo de captura |
| 3.6 | Resolução TSE 23.755/2026 | Brasil | Resolução regulamentar | 02/03/2026 | **Vigente** | Rótulo de conteúdo sintético eleitoral; vedação 72 h/24 h; proibição de ranquear candidato por IA |
| 3.7 | PL 2338/2023 (marco legal da IA) | Brasil | Projeto de lei | Aprovado no Senado em dez/2024 | **Em tramitação; risco de arquivamento (27/10/2026)** | Sistema de risco, avaliação de impacto, direitos do afetado — se aprovado como veio do Senado |
| 3.8 | AB 2839 e AB 2655 (deepfake eleitoral) | EUA / Califórnia | Lei estadual | Julgamento 20/08 e 29/08/2025 | **Barradas em tribunal** | Proibiam conteúdo eleitoral enganoso por IA; recurso só quanto à AB 2655 |
| 3.9 | SB 53 (Transparency in Frontier AI Act) | EUA / Califórnia | Lei estadual | Setembro/2025 | **Vigente** | Publicar estrutura de risco de fronteira; relatar incidente; multa administrativa |
| 3.10 | RAISE Act (S 6953-B) | EUA / Nova York | Lei estadual | Sancionada 19/12/2025 | **Vigente; vigência prevista 01/01/2027** | Protocolo de segurança ao AG e ao DHSES; incidente em 72 h; multa até US$ 1 mi/3 mi |
| 3.11 | EO "Eliminating State Law Obstruction of National AI Policy" | EUA / Casa Branca | Ordem executiva | 11/12/2025 | **Vigente** | DOJ desafia leis estaduais de IA; Commerce lista leis "onerosas"; risco a repasses federais |
| 3.12 | Controle de exportação de chips de IA | EUA / BIS | Regra final + minuta | Revogação da AI Diffusion Rule 05/2025; regra H200 15/01/2026; minuta global 03/2026 | **Vigente (H200); minuta NÃO CONFIRMADA** | Licença de exportação condicionada a volume de GPUs, certificações e visita a instalações |
| 3.13 | Bloqueio do DeepSeek | Itália / Garante | Provimento (enforcement) | 30/01/2025 | **Enforcement** | Limita o tratamento de dados de italianos; app sai das lojas italianas |
| 3.14 | Suspensão do download do DeepSeek | Coreia do Sul / PIPC | Medida administrativa | Suspensão fev/2025; retomada 28/04/2025 | **Suspensão revertida** | Impede novas instalações até revisão da política de tratamento de dados |
| 3.15 | Proibição em dispositivos do governo federal | Austrália | Diretriz administrativa | 04/02/2025 | **Vigente** | Remoção obrigatória do app de todos os dispositivos de Commonwealth |
| 3.16 | Proibição em dispositivos e redes estaduais | EUA / NY, TX, VA | Ato estadual | 2025–2026 (datas não confirmadas) | **Vigente (atos administrativos)** | Veda uso de DeepSeek em equipamentos e redes do estado |

## 2. Itens

### 3.1 UE — Art. 50 do AI Act (Reg. UE 2024/1689) + Código de Práticas de Transparência
**Instância:** União Europeia — Comissão Europeia / AI Office / AI Board. **Data e status:** obrigação aplicável em **02/08/2026**; Código de Práticas adotado em **09/07/2026**; diretrizes de interpretação adotadas em **20/07/2026** (consulta 08/05–03/06/2026; primeira consulta 04/09–02/10/2025). **Status: VIGENTE** — o CoP e as diretrizes são instrumentos de conformidade.
- **Mecanismo:** quatro deveres distintos — (i) avisar o usuário de que interage com sistema de IA;
  (ii) **marcar** conteúdo sintético em formato legível por máquina (proveniência); (iii) **revelar** deepfake
  de forma clara; (iv) revelar texto publicado para informar o público sobre assunto de interesse público.
  O CoP detalha *como* marcar (metadado + rótulo), e o descumprimento cai no art. 99 §4º: até **15 M€ ou 3%
  do faturamento mundial**.
- **Fonte:** [diretrizes, Comissão Europeia — oficial](https://digital-strategy.ec.europa.eu/en/library/guidelines-transparency-obligations-providers-and-deployers-ai-systems)
  · [CoP, DPA — base secundária que remete ao documento oficial](https://digitalpolicyalert.org/change/16054-code-of-practice-on-transparent-generative-ai-systems-under-article-50-ai-act)

### 3.2 China — Medidas de Rotulagem de Conteúdo Gerado por IA + GB 45438-2025
**Instância:** China — CAC, MIIT, Ministério da Segurança Pública e Administração de Dados (4 departamentos). **Data e status:** publicadas em **14/03/2025**; vigência em **01/09/2025**, junto com a norma técnica obrigatória GB 45438-2025 (*Segurança de rede — método de rotulagem de conteúdo gerado por IA*). **Status: VIGENTE**.
- **Mecanismo:** dois rótulos cumulativos — **explícito** (visível) e **implícito** (metadado no arquivo).
  O provedor do serviço de geração deve inserir a marca; a plataforma de disseminação deve **verificar** a
  marca, exibi-la e **não pode removê-la nem permitir supressão**; lojas de aplicativos checam conformidade
  antes de listar. Fiscalização por CAC e administrações locais, com remoção e responsabilização.
- **Fonte:** [CAC — oficial](https://www.cac.gov.cn/2025-03/14/c_1743654685899683.htm) ·
  [norma GB 45438-2025 — oficial](https://www.spc.org.cn/online/f32ea2a561f1886cd8d606513512d547.html) ·
  *(o portal do CAC recusou conexão neste ambiente; título, data e numeração conferidos em reprodução oficial
  do governo de Shenzhen: [szwljb.sz.gov.cn](https://szwljb.sz.gov.cn/rgznschcnrbsbf/))*.

### 3.3 Coreia do Sul — Framework Act on AI, art. 31 + diretrizes do MSIT
**Instância:** Coreia do Sul — Ministério da Ciência e TIC (MSIT); lei aprovada pela Assembleia. **Data e status:** lei em vigor em **22/01/2026**; diretrizes de transparência publicadas em **22/01/2026** e revisadas em **27/01/2026**. **Status: VIGENTE**.
- **Mecanismo:** o art. 31 impõe ao provedor de IA **generativa** o dever de **informar previamente** o
  usuário de que o resultado é gerado por IA; as diretrizes dizem *como* (aviso no ponto de interação).
  Regime sancionatório administrativo e brando — **NÃO CONFIRMADO** que haja multa proporcional ao faturamento.
- **Fonte:** [DPA — secundária, remete a ato oficial do NIA](https://digitalpolicyalert.org/change/16138-guideline-on-artificial-intelligence-transparency-obligations-article-31-of-the-framework-act-on-the-advancement-of-artificial-intelligence-and-creation-of-a-trust-foundation)
  · [Korea.net — oficial](https://www.korea.net/NewsFocus/policies/view?articleId=286183)

### 3.4 Índia — IT (Intermediary Guidelines and Digital Media Ethics Code) Amendment Rules, 2026
**Instância:** Índia — Ministry of Electronics and IT (MeitY). **Data e status:** notificadas em **10/02/2026**, vigência em **20/02/2026**; minuta em consulta em **22/10/2025**. **Status: VIGENTE**.
- **Mecanismo:** cria a categoria "informação sinteticamente gerada" (SGI — áudio, imagem ou vídeo que se
  apresentam como reais). O intermediário que oferece recurso computacional de geração deve: (i) adotar
  **medidas técnicas preventivas** contra SGI ilícito; (ii) aplicar **rótulo proeminente** (prefixo de áudio
  no caso de som); (iii) embutir **metadado permanente + identificador único** do recurso usado; (iv)
  **impedir remoção/supressão** do rótulo. Para SSMI (rede social > 5 milhões de usuários): **declaração do
  usuário** no upload + verificação automatizada + rótulo. Prazos: **3 h** para ordem judicial ou
  notificação governamental (era 36 h), **2 h** para conteúdo íntimo ou de impostura. Descumprimento =
  **perda do safe harbour** do art. 79 da IT Act.
- **Fonte:** [regra notificada, MeitY — oficial (PDF)](https://www.meity.gov.in/static/uploads/2026/02/f55fe52418b03f58b0669f6a8bc03b6d.pdf)
  · [análise com texto e datas](https://chandhiok.com/insights/cm-e-alert-ministry-of-electronics-and-information-technology-notifies-the-information-technology-intermediary-guidelines-and-digital-media-ethics-code-amendment-rules-2026)

### 3.5 EUA/Califórnia — AB 853, que reescreve o AI Transparency Act (SB 942)
**Instância:** EUA — Califórnia; Assembleia (AB 853), sancionada pelo governador. **Data e status:** introduzida 19/02/2025; aprovada na Assembleia 02/06/2025; aprovada pela Legislatura 12/09/2025; **sancionada em 13/10/2025**; **vigência 02/08/2026, com carência**; deveres de plataforma em **01/01/2027**; dispositivos de captura em **01/01/2028**. **Status: VIGENTE EM CARÊNCIA**.
- **Mecanismo:** (i) provedor de sistema generativo deve oferecer **ferramenta de detecção de IA** e
  disclosures; (ii) **plataforma online grande** deve fornecer informação de **proveniência** e **detectar e
  divulgar** conteúdo sintético; (iii) fabricante de "dispositivo de captura" deve **embutir marca latente
  por padrão**; (iv) proíbe site/app de oferecer sistema generativo **sem** os disclosures. Enforcement:
  Procuradoria-Geral da Califórnia, multa civil por violação.
- **Fonte:** [AB 853, Legislativo da Califórnia — oficial](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260AB853)
  · [linha do tempo datada, DPA](https://digitalpolicyalert.org/change/16533-design-requirements-in-california-ai-transparency-act-ab-853)

### 3.6 Brasil — Resolução TSE nº 23.755, de 02/03/2026 (propaganda eleitoral e conteúdo sintético)
**Instância:** Brasil — Tribunal Superior Eleitoral (art. 23, IX, do Código Eleitoral). **Data e status:** assinada em **02/03/2026**, vigência na publicação; altera a Res. TSE 23.610/2019. **Status: VIGENTE**.
- **Mecanismo:** (i) **rótulo obrigatório** — informar de modo explícito, destacado e acessível que o conteúdo
  foi fabricado/manipulado por IA e qual tecnologia foi usada (art. 9º-B); (ii) **janela de vedação** — proíbe
  publicar, republicar ou impulsionar conteúdo sintético novo com imagem/voz de candidato **nas 72 h antes e
  24 h depois** do pleito, mesmo rotulado; (iii) **vedação de ranqueamento** — provedor de IA não pode
  ranquear, recomendar ou priorizar candidatos nem emitir preferência eleitoral, ainda que o usuário peça
  (art. 28, §1º-C); (iv) **inversão do ônus da prova** sobre uso de IA (art. 9º-I); (v) **moderação sem ordem
  judicial** de conteúdo que ataque a integridade do sistema eletrônico de votação (art. 28, §§4º-A a 4º-C);
  (vi) **plano de conformidade** obrigatório como condição de credenciamento do provedor (art. 125-B).
- **Fonte:** [TSE — oficial](https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-755-de-2-de-marco-de-2026)
  · texto integral arquivado em `fontes/brasil/2026-resolucao-tse-23755-Resolução TSE 23.755 - texto.md`.

### 3.7 Brasil — PL 2338/2023 (marco legal da IA): em tramitação, com risco de arquivamento
**Instância:** Brasil — Congresso Nacional (Senado → Câmara). **Data e status:** aprovado no **Senado em dezembro de 2024**; a Rádio Câmara noticiou em **27/10/2026** que o projeto **pode ser arquivado**. **Status: EM TRAMITAÇÃO — risco de arquivamento** (arquivamento em si **NÃO CONFIRMADO**).
- **Mecanismo (se aprovado como veio do Senado):** classificação por risco; avaliação de impacto algorítmico;
  direitos do afetado (informação, contestação, revisão humana); governança de sistemas de alto risco;
  responsabilização civil em regime de risco. **Não** é lei de rotulagem de conteúdo — o rótulo eleitoral
  está na Res. TSE 23.755 (item 3.6).
- **Fonte:** [ficha do PL 2338/2023, Senado — oficial](https://www25.senado.leg.br/web/atividade/materias/-/materia/157233)
  · [Rádio Câmara, 27/10/2026 — oficial](https://www.camara.leg.br/radio/radioagencia/1314245-projeto-de-regulacao-da-ia-no-brasil-pode-ser-arquivado)

### 3.8 EUA/Califórnia — AB 2839 e AB 2655 (deepfake eleitoral): barradas em tribunal
**Instância:** EUA — Califórnia; Justiça federal, Distrito Leste da Califórnia (juiz John A. Mendez);
9º Circuito, processo **25-6138**, consolidando *Kohls*, *Babylon Bee*, *Rumble* e *X Corp. v. Bonta*.
**Data e status:** **20/08/2025** (AB 2655 preemptada pelo §230, por acordo das partes); **29/08/2025**
(AB 2839 permanentemente vedada por inconstitucionalidade); recurso em **30/09/2025**; razões da Califórnia
em **12/01/2026**. **Status: BARRADAS EM TRIBUNAL** — a Califórnia **não recorreu** do ponto que derrubou a
AB 2839; a apelação discute só a preempção da AB 2655.
- **Mecanismo que se tentou impor:** AB 2839 permitia ação de candidato atingido por conteúdo eleitoral
  enganoso gerado por IA, com remoção e indenização; AB 2655 obrigava plataforma grande a criar canal de
  denúncia e a remover/rotular conteúdo eleitoral enganoso, sob multa civil. Ambas caíram por Primeira
  Emenda (§230 no caso da AB 2655).
- **Fonte:** [dossiê do 9º Circuito, CourtListener — oficial](https://www.courtlistener.com/docket/71503636/the-babylon-bee-llc-et-al-v-bonta-et-al/)
  · [rastreador com linha do tempo](https://aichallengewatch.com/cases/babylon-bee-v-bonta-appeal/)
  · [AB 2655 — oficial](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202320240AB2655)

### 3.9 EUA/Califórnia — SB 53, Transparency in Frontier Artificial Intelligence Act (TFAIA)
**Instância:** EUA — Califórnia; Legislatura estadual (autoria e número conferidos na ficha oficial;
dia exato da sanção **NÃO CONFIRMADO**).
**Data e status:** sancionada em **setembro de 2025**; obrigações escalonadas a partir de 2026.
**Status: VIGENTE**.
- **Mecanismo:** alcança "grande desenvolvedor de fronteira" (> US$ 500 mi de receita anual). Exige
  **publicar estrutura de IA de fronteira** descrevendo avaliação de risco catastrófico e **avaliações por
  terceiros**; **reportar incidentes de segurança** ao governo estadual (janela de 15 dias); proteção a
  *whistleblowers*; **multa civil de até US$ 1 milhão por violação**, sem escalonamento para reincidência.
- **Fonte:** [SB 53 — oficial](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260SB53)
  · [Skadden, 06/01/2026 — secundária, com prazos e multas](https://www.skadden.com/insights/publications/2026/01/new-york-enacts-ai-transparency-law)

### 3.10 EUA/Nova York — RAISE Act (S 6953-B)
**Instância:** EUA — Nova York; Legislatura estadual, sancionada pela governadora Kathy Hochul. **Data e status:** **sancionada em 19/12/2025**, com acordo para emendar o texto na sessão de janeiro/2026 e alinhá-lo à lei californiana; vigência **prevista para 01/01/2027**. **Status: VIGENTE com emendas pendentes** — o texto final consolidado não circulou até o corte.
- **Mecanismo:** "grande desenvolvedor" (> US$ 500 mi de receita) de modelo de fronteira (> 10^26 FLOPs, ou
  destilado com custo > US$ 5 mi) deve elaborar e **publicar protocolo de segurança**, entregando cópia
  redigida ao **Procurador-Geral e ao DHSES**; manter versão sem redação por 5 anos após o fim do deployment;
  **reportar incidente de segurança em 72 h**; revisar o protocolo anualmente. Enforcement: AG, com multas
  **até US$ 1 mi (1ª) e US$ 3 mi (reincidência)** — valores divulgados pelo gabinete do governo, não lidos no
  texto legal.
- **Fonte:** [S 6953-B — oficial](https://legislation.nysenate.gov/pdf/bills/2025/s6953b)
  · [gabinete do governo de NY — oficial](https://www.governor.ny.gov/news/governor-hochul-signs-nation-leading-legislation-require-ai-frameworks-ai-frontier-models)
  · [Skadden, 06/01/2026 — secundária](https://www.skadden.com/insights/publications/2026/01/new-york-enacts-ai-transparency-law)

### 3.11 EUA — Ordem Executiva de 11/12/2025 contra a "colcha de retalhos" estadual (contra-tendência)
**Instância:** EUA — Casa Branca. **Data e status:** **11/12/2025**. **Status: VIGENTE** (ordem executiva).
- **Mecanismo:** declara política de padrão nacional "minimamente oneroso" para IA e **dirige o Departamento
  de Justiça a desafiar judicialmente leis estaduais** consideradas inconsistentes; incumbe o Departamento de
  Comércio de identificar leis estaduais "onerosas"; abre a porta para condicionar repasses federais. Não
  obriga empresa — **desarma o regulador subnacional**, que é onde a limitação às big techs efetivamente
  ocorreu em 2025–2026. Impacto esperado sobre a SB 53 (3.9) e a RAISE Act (3.10).
- **Fonte:** [Casa Branca — oficial](https://www.whitehouse.gov/presidential-actions/2025/12/eliminating-state-law-obstruction-of-national-artificial-intelligence-policy/)
  · [Skadden, 06/01/2026 — secundária](https://www.skadden.com/insights/publications/2026/01/new-york-enacts-ai-transparency-law)

### 3.12 EUA — Controle de exportação de chips de IA: da "AI Diffusion Rule" à licença por volume de GPUs
**Instância:** EUA — Departamento de Comércio, Bureau of Industry and Security (BIS).
**Data e status, em três camadas:** (a) **mai/2025** — BIS **revoga** a *AI Diffusion Rule* (regra interina de
15/01/2025, que criava licença global para chips 3A090.a/4A090.a), anunciando substituição; **revogação
VIGENTE**. (b) **15/01/2026** — regra final *Revision to License Review Policy for Advanced Computing
Commodities*: exportação do **H200** passa de presunção de indeferimento para **análise caso a caso**, com
certificações extensas; **VIGENTE**. (c) **05–13/03/2026** — notícias de **minuta** de **licenciamento
global** por volume de computação (até 1.000 GB300: revisão simples; acima de 200.000 GB300: envolvimento do
governo do país de destino, investimento "casando" nos EUA e visita a instalações); o BIS **negou** que
editaria regra nos moldes da gestão anterior — **NÃO CONFIRMADO como norma publicada**.
- **Mecanismo:** não proíbe modelo; **condiciona o insumo**. A empresa de IA só treina se o chip sair com
  licença — e a licença passou a depender de **volume, destino, certificação e acesso físico** do governo
  americano. Efeito indireto sobre treinamento fora dos EUA.
- **Fonte:** [regra final H200, Federal Register — oficial](https://www.federalregister.gov/documents/2026/01/15/2026-00789/revision-to-license-review-policy-for-advanced-computing-commodities)
  · [revogação da AI Diffusion Rule, BIS — oficial](https://media.bis.gov/press-release/department-commerce-rescinds-biden-era-artificial-intelligence-diffusion-rule-strengthens-chip-related)
  · [análise da minuta — secundária](https://www.globaltradeandsanctionslaw.com/reported-draft-rules-signal-new-semiconductor-export-controls-framework/)

### 3.13 Itália — Garante bloqueia o DeepSeek (enforcement)
**Instância:** Itália — Garante per la protezione dei dati personali. **Data e status:** provimento de **30/01/2025** (doc. web 10098477), comunicado no mesmo dia. **Status: ENFORCEMENT** (medida cautelar de limitação de tratamento).
- **Mecanismo:** o Garante **limita o tratamento de dados pessoais de usuários italianos** pela DeepSeek, por
  informação inadequada e ausência de base jurídica; na prática, o aplicativo **sai das lojas italianas** por
  ação da empresa. Não é proibição do modelo nem sanção pecuniária nesta fase — **multa posterior: NÃO
  CONFIRMADA**.
- **Fonte:** [provimento, Garante — oficial](https://www.garanteprivacy.it/home/docweb/-/docweb-display/docweb/10098477)
  · [comunicado, Garante — oficial](https://gpdp.it/web/guest/home/docweb/-/docweb-display/docweb/10097450)

### 3.14 Coreia do Sul — PIPC suspende o download do DeepSeek e libera 91 dias depois
**Instância:** Coreia do Sul — Personal Information Protection Commission (PIPC). **Data e status:** suspensão de novas instalações em **fevereiro de 2025** (dia e número do ato **NÃO CONFIRMADOS**); **retomada em 28/04/2025**, após política de tratamento revisada. **Status: SUSPENSÃO REVERTIDA**.
- **Mecanismo:** bloqueio de **novos downloads** do aplicativo nas lojas coreanas até adequação da política de
  dados e divulgação da transferência para a China; usuários já instalados e acesso web não foram
  necessariamente alcançados. É o caso mais claro de **restrição reversível por dados**, não por segurança
  nacional.
- **Fonte:** [Yonhap, 28/04/2025 — notícia](https://en.yna.co.kr/view/AEN20250428002951315)
  · [Digital Watch — secundária](https://dig.watch/updates/deepseek-returns-to-south-korea-after-data-privacy-overhaul)

### 3.15 Austrália — proibição do DeepSeek em dispositivos do governo federal
**Instância:** Austrália — governo federal (Home Affairs / ASD). **Data e status:** **04/02/2025**. **Status: VIGENTE** (diretriz administrativa; instrumento formal **NÃO CONFIRMADO** — não foi localizada a norma publicada, apenas o anúncio e a cobertura).
- **Mecanismo:** determina a **remoção do aplicativo de todos os dispositivos de Commonwealth** (computadores
  e celulares) e veda sua instalação, por risco de coleta de dados por entidade estrangeira. Não alcança
  dispositivo pessoal nem o setor privado; não há multa.
- **Fonte:** [ABC News, 04/02/2025 — notícia](https://www.abc.net.au/news/2025-02-04/deepseek-banned-from-federal-government-devices/104896770)
  · [BBC — notícia](https://www.bbc.co.uk/news/articles/c8d95v0nr1yo)

### 3.16 EUA — Nova York, Texas e Virgínia proíbem o DeepSeek em dispositivos e redes estaduais
**Instância:** EUA — NY, TX e VA (atos do Executivo estadual / agências de TI). **Data e status:** 2025–2026; **datas e números dos atos NÃO CONFIRMADOS**. **Status: VIGENTE** (atos administrativos estaduais, não leis).
- **Mecanismo:** vedam o uso do DeepSeek em **dispositivos e redes do estado**, com remoção/bloqueio técnico
  determinado pelas agências de TI; sem sanção pecuniária, com efeito prático de exclusão das compras públicas.
- **Fonte:** [National Law Review, 01/11/2026 — secundária](https://natlawreview.com/article/three-states-ban-deepseek-use-state-devices-and-networks)
  · *(texto oficial dos três atos não localizado; tratar como NÃO CONFIRMADO para citação normativa)*.

## 3. Lacunas

1. **Proibição federal explícita do DeepSeek nos EUA: NÃO CONFIRMADA.** Há notícia de vedação em agências
   federais civis e no próprio Congresso, mas não foi localizada lei ou ordem executiva federal específica.
   O que existe com texto confirmado é o ato estadual (3.16).
2. **Illinois SB 315 (Artificial Intelligence Safety Act)** — compilação de escritório indica estrutura de
   fronteira, auditoria independente e relatório de incidente. **Status, data e número não confirmados**; fora
   da tabela para não misturar proposta com lei.
3. **Colorado** — a compilação consultada afirma que a SB 26-189 **revogou e reeditou** o Colorado AI Act
   (SB 24-205) e que a HB 26-1263 criou deveres para "IA conversacional". A página está datada de 08/12/2026,
   **posterior ao corte** — ambos ficam como **NÃO CONFIRMADOS**.
4. **EUA — NY SB 3008-C e Califórnia SB 243 (chatbots companheiros / menores)**: mecanismo descrito em
   compilação (aviso de que não é humano, protocolo de autolesão, relatório anual, ação privada), mas
   **vigência e status não confirmados**.
5. **EU AI Act, obrigações de modelos de uso geral (GPAI)** e regime sancionatório a partir de 08/2026: não
   verificado neste ciclo. O item 3.1 cobre só o art. 50 (transparência) — documentação técnica de GPAI ficou fora.
6. **Tratado ou acordo internacional especificamente sobre IA**: nada vinculante em negociação localizado
   neste ciclo; a frente multilateral está em `pesquisa/noticias/multilateral.md` (CETS 225).
7. **Deepfake eleitoral fora de Brasil, EUA e Índia**: Indonésia, Coreia do Sul (lei eleitoral), México, África
   do Sul e Taiwan não verificados. A cobertura é **incompleta por jurisdição**, não por ausência de norma.
8. **Valores de multa**: registrados só os lidos em fonte (Califórnia US$ 1 mi; NY US$ 1 mi/3 mi; UE 15 M€/3%).
   Multas do Garante contra a DeepSeek e do PIPC coreano **não confirmadas**.
