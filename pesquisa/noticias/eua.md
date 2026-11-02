# EUA — federal e estadual: o que estão tentando limitar, e por qual instrumento

**Recorte:** propostas legislativas, leis vigentes e enforcement que restringem a liberdade de ação de (a) redes sociais, (b) modelos de IA/LLM e (c) big techs em geral. Prioridade 2025–2026. Data de referência: 31/10/2026.
**Legenda de tipo:** `PROPOSTA` ≠ `LEI VIGENTE` ≠ `ENFORCEMENT` ≠ `BARRADO EM TRIBUNAL`.
**Método:** cada item ancora em fonte oficial (Congresso, Federal Register, procuradoria-geral, tribunal) quando existe; quando só há imprensa especializada, está dito. Nada de número de projeto, data, autor ou multa sem fonte — o que não fechou está marcado **NÃO CONFIRMADO**.

---

## Tabela-síntese

| # | Item | País/instância | Tipo | Data | Status | Mecanismo (o que limita) |
|---|------|----------------|------|------|--------|--------------------------|
| F1 | KIDS Act (H.R. 7757) | EUA / federal | Proposta | 29/06/2026 | Aprovado na Câmara | Dever de política de salvaguardas p/ menores, ferramentas parentais, auditoria independente |
| F2 | KOSA (S. 1748) | EUA / federal | Proposta | 05/08/2026 | Em comissão → plenário do Senado | *Duty of care* sobre design; responsabilidade por danos a menores |
| F3 | COPPA 2.0 (S. 836) | EUA / federal | Proposta | mar/2026 | Aprovado no Senado (consentimento unânime) | Proíbe publicidade dirigida a menores; amplia dados cobertos até 16 anos |
| F4 | NO FAKES Act 2026 (S. 4591) | EUA / federal | Proposta | 20/05/2026 | Relatado pela Judiciary (24/06/2026) | Direito federal sobre voz/imagem; notice-and-takedown de réplica digital |
| F5 | GUARD Act (S. 3062) | EUA / federal | Proposta | abr/2026 | Avançou na Comissão de Comércio | Verificação de idade e vedação de chatbots-companheiro a menores |
| F6 | TAKE IT DOWN Act | EUA / federal | Lei vigente + enforcement | 19/05/2025 | Vigente; FTC fiscaliza desde 19/05/2026 | Remoção de imagem íntima não consentida (inclui deepfake) em 48h |
| F7 | Ordem de exclusão do DeepSeek | EUA / federal (DHS) | Enforcement (ato administrativo) | 20/10/2026 | Vigente | Remove DeepSeek (e derivados) de sistemas e compras do Executivo civil |
| F8 | PAFACA — desinvestimento do TikTok | EUA / federal | Lei vigente + execução | 23/01/2026 | Joint venture fechada | Venda forçada do controle societário sob pena de banimento |
| F9 | Acordo Meta × 51 procuradores-gerais | EUA / multistadual | Enforcement/settlement | 26/08/2026 | Proposto, aguarda *consent judgment* | Limite diário padrão, bloqueio noturno, *age assurance*, auditor independente |
| E1 | SB 976 + AB 1043 (idade) | Califórnia | Lei vigente + regulamento em consulta | 14/05/2026 | Regras propostas; vigência 01/01/2027 | Feed viciante só com consentimento parental verificado; sinal de idade via SO/app store |
| E2 | AB 1709 | Califórnia | Lei sancionada | 10/09/2026 | Vigente em 01/01/2027 | Veda *feed* viciante e autoplay a menores de 16, sem rota de consentimento |
| E3 | SB 942 + SB 1000 (transparência de IA) | Califórnia | Lei vigente + proposta | 01/08/2026 | SB 942 operante; SB 1000 aguarda sanção | Rotulagem/proveniência de conteúdo gerado ou modificado por IA |
| E4 | SB 53 (TFAIA) — sucessora da SB 1047 | Califórnia | Lei vigente | 29/09/2025 | Em vigor desde 01/01/2026 | *Framework* público, relato de incidentes críticos, proteção a *whistleblowers* |
| E5 | SB 243 (chatbots-companheiro) | Califórnia | Lei vigente | 01/01/2026 | Em vigor | Protocolo antissuicídio, aviso de que não é humano, pausa a cada 3h p/ menores |
| E6 | RAISE Act (S6953B/A6453A) | Nova York | Lei vigente | 19/12/2025 | Em vigor desde 19/03/2026 | *Framework* de segurança e relato de incidentes por grandes desenvolvedores |
| E7 | SB 24-205 → SB 26-189 | Colorado | Lei substituída + enforcement | 14/05/2026 | Vigência 01/01/2027; enforcement barrado por ordem federal | Deveres de aviso, explicação e revisão humana em decisões automatizadas |
| E8 | SB 2420 + TRAIGA (HB 149) | Texas | Leis vigentes | 06/07/2026 | Exequíveis após a Suprema Corte negar suspensão | Verificação de idade por app store; consentimento parental; deveres de IA |
| E9 | SB 142 (ASAA) + emenda 2026 | Utah | Lei vigente, parcialmente suspensa | 2026 | Obrigações adiadas p/ 06/05/2027 | Categoria de idade e consentimento parental verificado; ação privada |
| L1 | NetChoice v. Bonta | 9º Circuito | Litígio (interpretação) | 09/09/2025 | Lei mantida em parte | Valida definições de "feed viciante"; derruba contagem de curtidas |
| L2 | CCIA v. Uthmeier / NetChoice v. Carr | 11º Circuito | Litígio (liminar cassada) | 14–15/10/2026 | Liminares suspensas | Libera Flórida e Geórgia para barrar contas de menores de 16 |
| L3 | Júri de Los Angeles (Meta e Google) | Califórnia (tribunal estadual) | Litígio (veredito) | 25/03/2026 | Responsabilidade reconhecida | Design viciante como causa de dano; abre caminho a indenização |
| L4 | Free Speech Coalition v. Paxton | Suprema Corte | Litígio (precedente) | 2025 | Decisão da Corte | Valida verificação de idade obrigatória como compatível com a 1ª Emenda |
| L5 | Kohls v. Bonta (AB 2839/AB 2655) | Califórnia (Distrito Central) | Barrado em tribunal | 2024 | Liminar permanente | Lei de deepfake eleitoral suspensa por 1ª Emenda |
| C1 | EO 14365 + AI Litigation Task Force | EUA / federal | Contramovimento | 16/12/2025 | Vigente | Preempção de leis estaduais de IA via litígio do DOJ |

---

## A. Frente federal — propostas

### F1. KIDS Act (H.R. 7757) — pacote de proteção a menores
- **Instrumento:** projeto de lei; aprovado pela Câmara em **29/06/2026** (votação registrada), incorporando o texto do KOSA sob a rubrica "Kids Online Safety", mais COPPA 2.0 e outros.
- **Autor/proponente:** liderança do Comitê de Energia e Comércio da Câmara (acordo bipartidário Guthrie–Pallone).
- **Mecanismo concreto:** plataformas cobertas passam a ser obrigadas a (i) manter políticas e procedimentos contra quatro classes de dano a menores; (ii) entregar salvaguardas padrão (limitar mensagens de desconhecidos, ocultar status online, conter design compulsivo, opt-out de recomendação personalizada); (iii) fornecer ferramentas parentais com padrão mais protetivo; (iv) responder denúncias em 10 dias; (v) contratar **auditoria independente anual** e enviar o resultado à FTC em 30 dias.
- **Ponto decisivo:** a versão da Câmara **removeu o *duty of care***; a definição de "sabe" é "sabe ou deveria saber" — padrão de negligência que, na prática, empurra as plataformas para checar idade de todo mundo.
- **Status:** aprovado na Câmara; não é lei.
- **Fonte oficial:** [CRS, "Kids Online Safety Act", IF12730, atualizado 24/08/2026](https://www.congress.gov/crs_external_products/IF/HTML/IF12730.html) · [H.R. 7757](https://www.congress.gov/bill/119/house-bill/7757)
- **Análise (não oficial):** [EFF, 24/06/2026](https://www.eff.org/deeplinks/2026/06/kids-act-would-require-age-checks-get-online)

### F2. KOSA (S. 1748) — a via do Senado
- **Instrumento:** projeto de lei; versão emendada avançou da Comissão de Comércio em **05/08/2026** para o plenário.
- **Mecanismo:** mantém o ***duty of care*** — "exercer cuidado razoável na criação e implementação de qualquer design feature para prevenir e mitigar" danos, incluindo transtornos alimentares, ansiedade/depressão e padrões de uso compulsivo. Cobre também **videogames online, apps de mensagem e streaming** — escopo mais amplo que o da Câmara.
- **Status:** aprovado em comissão; aguarda votação em plenário. Não é lei.
- **Fonte oficial:** [texto emendado, comissão de Comércio](https://www.commerce.senate.gov/wp-content/uploads/2026/08/S.1748-BLACKURN-ANS_as-modified.pdf) · [S. 1748](https://www.congress.gov/bill/119/senate-bill/1748)

### F3. COPPA 2.0 (S. 836) — privacidade de crianças e adolescentes
- **Instrumento:** projeto de lei; **aprovado no Senado por consentimento unânime em março de 2026**.
- **Autor:** Sen. Ed Markey (D-MA), com apoio bipartidário (Cassidy, Britt).
- **Mecanismo:** proíbe publicidade dirigida a crianças e adolescentes e amplia a proteção de dados até os 16 anos — alcança diretamente o modelo de negócio de publicidade comportamental.
- **Status:** aprovado no Senado; seguiu para a Câmara e foi absorvido no pacote KIDS Act.
- **Fonte oficial:** [S. 836 (relatado no Senado)](https://www.govinfo.gov/app/details/BILLS-119s836rs) · [S. 836 no Congresso](https://www.congress.gov/bill/119/senate-bill/836)

### F4. NO FAKES Act of 2026 (S. 4591) — voz e imagem contra IA generativa
- **Instrumento:** projeto de lei; apresentado em **20/05/2026**, **relatado pela Comissão de Justiça em 24/06/2026** (Calendário nº 446).
- **Autores:** Coons, Blackburn, Klobuchar, Tillis, Durbin, Britt, Hirono, Moody, Welch, Cassidy, Schiff, Hagerty, Slotkin, Lankford, Blumenthal, Scott (FL).
- **Mecanismo concreto:** cria um **direito federal de replicação digital** (propriedade, licenciável, não cedível em vida, pós-morte por 10 anos prorrogáveis); obriga serviços online a manter **agente designado** e a responder a notificação de remoção de réplica não autorizada, com deveres de retirada e *subpoena* para identificar o infrator; **exclui a Seção 230** ao qualificar a matéria como propriedade intelectual; prevê danos legais e honorários.
- **Status:** proposta relatada; não é lei.
- **Fonte oficial:** [texto relatado, S. 4591 (GovInfo)](https://www.govinfo.gov/content/pkg/BILLS-119s4591rs/html/BILLS-119s4591rs.htm)

### F5. GUARD Act (S. 3062) — chatbots-companheiro e menores
- **Instrumento:** projeto de lei; **avançou na Comissão de Comércio do Senado em abril/2026**.
- **Mecanismo:** exige verificação de idade e veda que menores acessem chatbots-companheiro (modelos conversacionais desenhados para vínculo socioemocional).
- **Status:** em comissão; votação em plenário **NÃO CONFIRMADA**.
- **Fonte:** [S. 3062 (GovTrack)](https://www.govtrack.us/congress/bills/119/s3062) · imprensa: [Press-Telegram, abr/2026](https://www.presstelegram.com/2026/04/30/senate-approves-chatbot-age-verification-bill-for-minors/)

---

## B. Frente federal — lei vigente e enforcement

### F6. TAKE IT DOWN Act — remoção obrigatória em 48 horas
- **Instrumento:** lei sancionada em **19/05/2025**; obrigações de plataforma exigíveis pela FTC a partir de **19/05/2026**.
- **Mecanismo:** plataformas cobertas devem criar canal de solicitação e **remover imagem íntima não consensual — inclusive deepfake gerado por IA — em até 48 horas** após pedido válido, e impedir a republicação. Descumprimento é tratado como prática desleal ou enganosa sob o §5º do FTC Act.
- **Enforcement:** em **maio/2026** a FTC enviou **cartas de advertência** a empresas sobre conformidade. Não há, até 31/10/2026, multa aplicada divulgada por este dossiê — **NÃO CONFIRMADO**.
- **Fonte oficial:** [FTC, "Take It Down Act enforcement starts now", maio/2026](https://search.ftc.gov/business-guidance/blog/2026/05/take-it-down-act-enforcement-starts-now-what-know-about-ftc-tida)

### F7. Ordem de exclusão do DeepSeek de sistemas federais
- **Instrumento:** ato administrativo publicado no **Federal Register de 20/10/2026** — *Notice of Order Regarding Exclusion and Removal of DeepSeek Products From Federal Civilian Executive Branch Information Technology Systems and Procurements* (91 FR 66346, doc. 2026-21447).
- **Mecanismo:** veda aquisição e determina remoção de produtos DeepSeek dos sistemas do Executivo civil; a exclusão **segue o modelo para dentro de qualquer produto construído sobre ele** (efeito cascata sobre integradores).
- **Status:** vigente. Autoridade emissora atribuída ao **DHS** pela imprensa especializada; signatário exato **NÃO CONFIRMADO**.
- **Fonte oficial:** [Federal Register, 20/10/2026](https://www.govinfo.gov/app/details/FR-2026-10-20/2026-21447) · imprensa: [TechCrunch, 20/10/2026](https://techcrunch.com/2026/10/20/us-orders-federal-agencies-to-remove-chinas-deepseek-ai-from-their-systems/) · [Forkast](https://forkast.news/dhs-ordered-every-federal-agency-to-purge-deepseek-the-exclusion-follows-the-model-into-anything-built-on-it/)

### F8. PAFACA — desinvestimento forçado do TikTok
- **Instrumento:** lei (P.L. 118-50, abr/2024) que condiciona a permanência do TikTok nos EUA à venda do controle a entidade não controlada por adversário estrangeiro, sob pena de banimento.
- **Execução:** a *joint venture* **TikTok USDS** foi fechada em **23/01/2026**, com controle liderado pela Oracle e consórcio de investidores americanos — encerrando a disputa societária.
- **Mecanismo:** é o caso mais puro de limitação **estrutural** (não de conteúdo): a empresa é obrigada a **deixar de ser quem é** para continuar operando.
- **Fonte:** imprensa: [EFE, 23/01/2026](https://efe.com/economia/2026-01-23/tiktok-venta-mayoria-operacion-eeuu-disputa-legal/) · participação da Oracle: [IndexBox, mar/2026](https://www.indexbox.io/blog/oracles-tiktok-stake-valued-at-2-billion-in-us-joint-venture/)

### F9. Acordo Meta × 51 procuradores-gerais — US$ 17 bi e arquitetura de idade
- **Instrumento:** acordo (proposto) que resolve ação de 2023 por violação do COPPA e leis californianas; anunciado em **26/08/2026**, sujeito a *consent judgment*.
- **Mecanismo — o mais detalhado do período:** limite diário padrão de **2 horas** para menores de 18 (cai para 1h se TikTok e YouTube adotarem termos equivalentes); bloqueio noturno padrão **0h–6h** (ampliável a 22h–7h); notificações bloqueadas 22h–7h e no horário escolar (8h–15h, 15/08–15/06); **proibição de exibir contagem de curtidas** a menores; veto a filtros de procedimento estético; opção de feed não personalizado; resposta a 90% das denúncias em 6 horas; ***age assurance*** robusta para detectar menores de 18 e remover menores de 13; **auditor independente** com acesso amplo e direito de falar diretamente com os procuradores; injunção contra declarações enganosas sobre segurança.
- **Status:** proposto, pendente de homologação. Texas fechou acordo paralelo no mesmo dia (mais de US$ 1 bi).
- **Fonte oficial:** [Procuradoria-Geral da Califórnia, 26/08/2026](https://oag.ca.gov/news/press-releases/attorney-general-bonta-secures-transformative-17-billion-settlement-meta)
- **Texto integral no acervo:** `fontes/EUA/2026-acordo-meta-51-procuradores-gerais-consent-judgment.pdf` (Settlement Agreement, Doc. 572-1, 26/08/2026). A partir daqui, citar a **fonte primária**; este resumo é secundário.

---

## C. Califórnia — o laboratório mais denso

### E1. SB 976 + AB 1043 — a arquitetura de idade
- **Instrumento:** SB 976 (*Protecting Our Kids from Social Media Addiction Act*, 2024) + AB 1043 (*Digital Age Assurance Act*, Cap. 675/2025).
- **Mecanismo:** SB 976 torna ilegal fornecer *addictive feed* a menor sem **consentimento parental verificável** ou sem determinação razoável de que o usuário não é menor (padrão que passa a valer em 01/01/2027). AB 1043 desloca a verificação para **sistema operacional e app store**: o SO coleta data de nascimento e emite sinal em quatro faixas (<13, 13–16, 16–18, 18+), e o desenvolvedor que recebe o sinal é tido como tendo **conhecimento efetivo** da idade.
- **Regulamento:** a Procuradoria-Geral publicou **regras propostas em 14/05/2026**, com consulta de 45 dias encerrada em 30/06/2026 e audiência pública no mesmo dia.
- **Sanção:** multa de até **US$ 7.500 por criança afetada** para sistemas operacionais (AB 1043).
- **Status:** AB 1043 vigente desde 01/01/2026, **operante em 01/01/2027**; SB 976 com regras em finalização. Tentativa de expandir a AB 1043 a navegadores e sites (AB 1856, Wicks) foi **retirada** em julho/2026; isenção para SO de código aberto foi mantida.
- **Fonte oficial:** [CA DOJ, regras propostas SB 976, 14/05/2026](https://oag.ca.gov/news/press-releases/california-department-justice-releases-proposed-protecting-our-kids-social-media) · [oag.ca.gov/sb976](https://oag.ca.gov/sb976) · [EFF, 15/07/2026](https://www.eff.org/deeplinks/2026/07/california-steps-back-dangerous-expansion-its-age-gating-law)

### E2. AB 1709 — veto de *feed* viciante a menores de 16
- **Instrumento:** lei sancionada em **10/09/2026** (Cap. 183, Statutes of 2026); autor: Dep. Josh Lowenthal (Long Beach).
- **Mecanismo:** "plataforma coberta não fornecerá *addictive feature* a usuário menor de 16" — *feed* algorítmico, autoplay e qualquer outro recurso que a Procuradoria designar por regulamento. **Não há rota de consentimento parental**: o objeto regulado é o recurso, não a conta. Exige verificação de idade pela AB 1043; se não for possível, usa o padrão da SB 976. Plataformas que não optarem por manter contas sem recursos viciantes devem **excluir a conta e os dados pessoais** do menor.
- **Sanção:** até **US$ 50.000 por menor afetado** (violação consciente) e **US$ 25.000** (negligente); legitimidade exclusiva do Procurador-Geral ou de promotor local — sem ação privada.
- **Status:** sancionada; **vigência 01/01/2027**.
- **Fonte oficial:** [AB 1709 — status legislativo](https://leginfo.legislature.ca.gov/faces/billStatusClient.xhtml?bill_id=202520260AB1709)

### E3. SB 942 + SB 1000 — transparência e proveniência de IA
- **Instrumento:** SB 942 (*California AI Transparency Act*, 2024) vigente; SB 1000 (Becker) aprovada pelo Legislativo no fim de agosto/2026.
- **Mecanismo:** SB 942 obriga provedores de IA generativa com mais de 1 milhão de usuários mensais na Califórnia a **manifestar proveniência** em conteúdo gerado e a oferecer **ferramenta gratuita de detecção**. SB 1000 **elimina o piso de 1 milhão de usuários** (qualquer desenvolvedor acessível a californianos passa a ser "provedor coberto") e troca a ferramenta de detecção por **verificação ativa de disclosure**, cobrindo também conteúdo **modificado** por IA.
- **Status:** SB 942 operante desde **01/08/2026**; SB 1000 aguardava sanção — situação em 31/10/2026 **NÃO CONFIRMADA**.
- **Fonte:** [leginfo — SB 1000](https://leginfo.legislature.ca.gov/faces/billStatusClient.xhtml?bill_id=202520260SB1000) · [análise, 02/09/2026](https://www.licentium.io/post/california-sb-1000-expands-ai-transparency-act-all-developers-august-2026)

### E4. SB 53 (TFAIA) — o que sobrou da SB 1047
- **Instrumento:** *Transparency in Frontier Artificial Intelligence Act* — apresentada em **07/01/2025**, aprovada em **13/09/2025**, sancionada em **29/09/2025**, **em vigor em 01/01/2026**.
- **Mecanismo:** "desenvolvedores de fronteira" (e "grandes desenvolvedores", receita anual acima de US$ 500 mi) devem publicar ***framework*** de segurança, **relatar incidentes críticos de segurança** ao governo estadual, manter proteções a *whistleblowers* internos, e o estado cria capacidade de computação pública (CalCompute). Enforcement pela Procuradoria-Geral.
- **Antecedente direto:** a SB 1047, que criava dever de segurança e certificação pré-treino, foi **vetada em 29/09/2024** — a SB 53 é sua herdeira desidratada: sai a responsabilidade por dano catastrófico, entra transparência.
- **Status:** lei vigente.
- **Fonte:** [Digital Policy Alert — linha do tempo com fontes oficiais](https://digitalpolicyalert.org/change/13536-act-on-frontier-models-and-artificial-intelligence-including-capacity-building-sb-53)

### E5. SB 243 — chatbots-companheiro
- **Instrumento:** lei em vigor desde **01/01/2026**.
- **Mecanismo:** o operador de chatbot-companheiro deve (i) avisar que o usuário interage com IA; (ii) implementar **protocolo para impedir conteúdo sobre ideação suicida/autolesão** e encaminhar a serviços de crise; (iii) informar que o produto pode não ser adequado a menores; (iv) quando sabe que o usuário é menor, **lembrete de pausa e de não-humanidade a cada 3 horas** e bloqueio de material sexualmente explícito. Relatórios anuais ao Office of Suicide Prevention a partir de **01/07/2027**. **Ação privada** expressa.
- **Status:** vigente; primeiro estado a regular o gênero por dever operacional, não por rótulo.
- **Fonte:** [análise, 12/01/2026](https://www.ashurstperkinscoie.com/en/insights/california-companion-chatbot-law-now-in-effect/)

---

## D. Outros estados

### E6. Nova York — RAISE Act (S6953B / A6453A)
- **Instrumento:** *Responsible AI Safety and Education Act*, sancionada em **19/12/2025**, **em vigor em 19/03/2026** (90 dias após a sanção).
- **Mecanismo:** grandes desenvolvedores de "modelos de fronteira" devem publicar *framework* de segurança, relatar incidentes críticos ao Procurador-Geral e manter canal de denúncia interna. Desenhada como espelho da SB 53 californiana — é o segundo estado a impor dever de transparência a LLMs.
- **Status:** lei vigente. Sanções específicas por violação: **NÃO CONFIRMADO** neste dossiê.
- **Fonte:** [Digital Policy Alert — RAISE Act, com trilha oficial](https://digitalpolicyalert.org/change/15078-responsible-ai-safety-and-education-act-a6453bs6953b) · [DLA Piper, dez/2025](https://www.dlapiper.com/en/insights/publications/2025/12/the-raise-act-new-york-joins-california-in-requiring-developer-transparency-for-large-ai-models)

### E7. Colorado — da lei mais ambiciosa ao recuo
- **Instrumento:** SB 24-205 (2024) **revogada e substituída** pela SB 26-189, sancionada em **14/05/2026**.
- **Mecanismo (novo):** foca em **tecnologia de decisão automatizada (ADMT)** que "influencia materialmente" decisão consequencial (emprego, crédito, moradia, etc.). Deveres: aviso prévio claro; **explicação em 30 dias** após resultado adverso; direito de corrigir dados e obter **revisão humana significativa** com poder de reverter; guarda de registros por 3 anos. Saíram: dever de cuidado contra discriminação algorítmica, avaliação de impacto anual e auto-relato em 90 dias.
- **Vigência:** decisões a partir de **01/01/2027**; regulamento em consulta até **26/10/2026**.
- **Enforcement bloqueado:** em **09/04/2026** a xAI processou o Procurador-Geral (*xAI v. Weiser*, 1:26-cv-01515, D. Colo.); o DOJ interveio como autor em **24/04/2026**; ordem de **27/04/2026** veda ao AG iniciar enforcement até 14 dias após a decisão sobre a liminar.
- **Fonte:** [Jones Walker, 23/10/2026](https://www.joneswalker.com/en/insights/blogs/ai-law-blog/the-colorado-ai-law-you-prepared-for-is-gone-and-the-rulemaking-comment-window-c.html?id=102o651) · [SB 26-189 (Colorado)](https://leg.colorado.gov/bills/sb26-189)

### E8. Texas — idade na app store e deveres de IA
- **Instrumento 1:** SB 2420 (*App Store Accountability Act*), vigente desde 01/01/2026.
  **Mecanismo:** app stores verificam **categoria de idade** e obtêm **consentimento parental verificado** para downloads e compras no app; desenvolvedores recebem o dado de idade e respondem por classificação e disclosure. Violação é prática comercial enganosa, com **ação privada**.
  **Status:** 5º Circuito suspendeu a liminar em **28/05/2026**; a **Suprema Corte negou as aplicações de emergência em 06/07/2026** (sem decisão de mérito) — lei exequível.
- **Instrumento 2:** TRAIGA (HB 149), sancionada em jun/2025, **em vigor em 01/01/2026** — deveres de disclosure e de não discriminação para desenvolvedores e deployers de IA; enforcement pelo Procurador-Geral do Texas.
- **Fonte:** [InfoLawGroup, 07/07/2026](https://www.infolawgroup.com/insights/2026/7/7/supreme-court-clears-the-way-texass-app-store-accountability-act-is-now-enforceable) · [DLA Piper sobre TRAIGA](https://www.dlapiper.com/en/insights/publications/2025/06/texas-adopts-the-responsible-ai-governance-act)

### E9. Utah — lei de app store esvaziada por emenda
- **Instrumento:** SB 142 (*App Store Accountability Act*, 2025), implementação parcial em **07/05/2025**; emendada em 2026.
- **Mecanismo:** app stores e desenvolvedores identificam **categoria de idade** e obtêm **consentimento parental verificado** antes do download/compra.
- **O que a emenda fez:** adiou as obrigações operacionais para **06/05/2027** e **retirou o poder de enforcement do Procurador-Geral**, preservando apenas **ação privada** — danos de **US$ 1.000 por violação**, além de custos. A ação do setor foi retirada em 21/04/2026 após a emenda.
- **Status:** lei vigente, cronograma suspenso.
- **Fonte:** [Wiley, 30/04/2026](https://www.wileyconnect.com/utah-amends-app-store-accountability-act-asaa-key-obligations-delayed-until-may-6-2027) · [Utah Code §13-76-402 (oficial)](https://le.utah.gov/xcode/Title13/Chapter76/13-76-S402.html?v=C13-76-S402_2025050720250507)

---

## E. Litígios que redefinem o limite

### L1. NetChoice v. Bonta — 9º Circuito valida o vocabulário da SB 976
- **Decisão:** **09/09/2025**, 152 F.4th 1002.
- **O que decidiu:** a lei **não é inconstitucionalmente vaga** — "feed viciante", "parte significativa", "propósito primário" dão aviso suficiente; a challenge à verificação de idade foi considerada **prematura** (só exigível em 2027, sem regulamento); a restrição padrão de **contagem de curtidas** é provavelmente inconstitucional, mas **severável**; negativa de liminar mantida.
- **Por que importa:** é a fundação jurídica que permite à AB 1709 reutilizar as mesmas definições sem reabrir a discussão.
- **Fonte oficial:** [opinião, 9º Circuito (PDF)](https://cdn.ca9.uscourts.gov/datastore/opinions/2025/09/09/25-146.pdf)

### L2. 11º Circuito libera Flórida e Geórgia para barrar menores de 16
- **Decisões:** **14/10/2026** (Flórida, *CCIA/NetChoice v. Uthmeier*, H.B. 3) e **15/10/2026** (Geórgia, *NetChoice v. Carr*, S.B. 351) — mesmo painel.
- **Mecanismo liberado:** Flórida proíbe contas para **menores de 14** (sem exceção parental) e exige consentimento dos pais para 14–15; Geórgia exige **consentimento parental** para menores de 16 e impõe "esforços comercialmente razoáveis" de verificação de idade.
- **Status:** liminares **cassadas** — leis exequíveis enquanto o mérito tramita. Ambas podem ser reexaminadas.
- **Fonte:** [EFF, 23/10/2026 (com links para as duas opiniões)](https://www.eff.org/deeplinks/2026/10/two-states-can-now-restrict-social-media-access-heres-what-to-do-next)

### L3. Júri de Los Angeles responsabiliza Meta e Google por design viciante
- **Decisão:** **25/03/2026**, tribunal estadual da Califórnia — primeiro júri a julgar o tema.
- **O que decidiu:** ambas as empresas **responsáveis** pelos danos alegados; pedido de novo julgamento **negado**.
- **Mecanismo:** não é norma nova — é a conversão do **design** em fonte de responsabilidade civil, o que na prática impõe às plataformas alterar recursos sem esperar lei.
- **Status:** veredito mantido; recursos em curso.
- **Fonte:** imprensa jurídica: [Missouri Lawyers Media, 25/03/2026](https://molawyersmedia.com/2026/03/25/los-angeles-jury-finds-meta-google-liable-social-media-addiction/) · [Bloomberg Law](https://news.bloomberglaw.com/in-house-counsel/meta-google-found-liable-in-social-media-addiction-case)

### L4. Free Speech Coalition v. Paxton — a Suprema Corte valida verificação de idade
- **Decisão:** 2025 (Texas, H.B. 1181).
- **O que decidiu:** a exigência de verificação de idade para acesso a conteúdo adulto **não viola a 1ª Emenda de forma ostensiva**; o caso voltou aos tribunais inferiores para escrutínio intermediário.
- **Por que importa:** é o precedente que sustenta todas as leis estaduais de idade de 2025–2026 e o próprio KOSA/KIDS Act.
- **Status:** precedente vigente. **Fonte:** [Harvard Law Review, vol. 139](https://harvardlawreview.org/print/vol-139/free-speech-coalition-inc-v-paxton/)

### L5. Kohls v. Bonta — deepfake eleitoral barrado
- **Instrumento barrado:** AB 2839 (2024), que proibia "mídia enganosa" sobre candidatos em janela eleitoral; a AB 2655 (obrigação de remover deepfakes eleitorais) teve sorte semelhante.
- **Decisão:** liminar permanente em 2024, por violação da 1ª Emenda — sátira e paródia política protegidas.
- **Status:** **barrado em tribunal**; a Califórnia não conseguiu, até aqui, impor dever de remoção de deepfake eleitoral. Fora da janela prioritária (2024), listado porque condiciona o desenho de tudo que veio depois.
- **Fonte:** [Global Freedom of Expression — Kohls v. Bonta](https://globalfreedomofexpression.columbia.edu/cases/christopher-kohls-v-bonta/)

### L6. US v. Google — remédios antitruste em recurso
- **Instrumento:** ordem de remédios de 2025 no caso de monopólio de busca do DOJ.
- **Status:** Google recorreu em **maio/2026** (D.C. Cir., nº 26-5023); DOJ e procuradores-gerais estaduais apresentaram recurso cruzado contra partes da ordem.
- **Mecanismo:** obrigações de compartilhamento de dados e vedação a acordos de distribuição — limite de conduta, não de conteúdo.
- **Fonte:** [NYT, 22/05/2026](https://www.nytimes.com/2026/05/22/technology/google-appeals-search-case.html)

---

## F. Vetor inverso — quem está tentando limitar os limitadores

### C1. EO 14365 e a AI Litigation Task Force
- **Instrumento:** Ordem Executiva **14365**, *Ensuring a National Policy Framework for Artificial Intelligence*, publicada em **16/12/2025**.
- **Mecanismo:** cria força-tarefa no Departamento de Justiça para **litigar contra leis estaduais de IA** e condicionar financiamento federal à não-regulação; a intervenção do DOJ em *xAI v. Weiser* (24/04/2026) é o primeiro uso visível.
- **Status:** vigente. **Não limita big tech — limita o poder estadual de limitar.** Está aqui porque, para uma proposta brasileira, é o contra-argumento que será usado na mesa.
- **Fonte oficial:** [Federal Register, 16/12/2025](https://www.federalregister.gov/documents/2025/12/16/2025-23092/ensuring-a-national-policy-framework-for-artificial-intelligence) · [análise do uso em Colorado](https://www.joneswalker.com/en/insights/blogs/ai-law-blog/the-colorado-ai-law-you-prepared-for-is-gone-and-the-rulemaking-comment-window-c.html?id=102o651)

---

## Lacunas

1. **Nenhum projeto federal restritivo virou lei em 2025–2026.** O único texto federal *vigente* com mecanismo de remoção obrigatória é o TAKE IT DOWN Act (2025). KOSA, COPPA 2.0, NO FAKES e GUARD seguem como proposta — o que muda o diagnóstico: nos EUA o limite prático veio dos **estados** e dos **acordos**, não do Congresso.
2. **Falta confirmar** (a) a sanção da SB 1000 californiana; (b) o placar/plenário do GUARD Act; (c) o número de lei do TAKE IT DOWN Act (P.L.); (d) sanções específicas do RAISE Act; (e) o signatário da ordem do DeepSeek.
3. **Valores de multa só foram usados quando a fonte oficial os trazia** (US$ 7.500 da AB 1043; US$ 50.000/25.000 da AB 1709; US$ 1.000/violação em Utah). O total de US$ 17 bi do acordo Meta é o anunciado pela Procuradoria-Geral da Califórnia e **ainda depende de homologação**.
4. **Discrepância a monitorar:** o acordo Meta é descrito como "coalizão de 51 procuradores-gerais" pela fonte oficial, enquanto parte da imprensa jurídica fala em 29 estados. Contagem definitiva **NÃO CONFIRMADA**.
5. **Lacuna de cobertura nesta frente:** Tennessee (ELVIS Act, 2024 — direito de imagem contra uso por IA) não teve enforcement relevante localizado em 2025–2026; não foi possível confirmar ação concreta, então não entrou como achado. O mesmo vale para a maioria das leis estaduais de verificação de idade fora de CA/TX/UT/FL/GA — existem em cerca de metade dos estados, mas sem decisão judicial ou enforcement divulgado neste recorte.
6. **O que ainda não foi tentado nos EUA:** nenhuma norma federal impõe obrigação a **modelos de linguagem** como tais (transparência de treinamento, avaliação pré-implantação, limite de capacidade). O que existe são deveres **por caso de uso** (chatbot, decisão automatizada, conteúdo eleitoral) e deveres **de transparência** (SB 53, RAISE). Para o debate brasileiro, esse é o vazio mais informativo.
