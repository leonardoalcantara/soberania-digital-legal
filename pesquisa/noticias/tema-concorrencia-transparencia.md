# Frente temática — concorrência, transparência e enforcement contra big techs (notícias 2025–2026)

**Corte de pesquisa:** 31/10/2026 · **Eixo:** antitruste, remédios estruturais/de conduta, transparência algorítmica, acesso a dados, tributação de serviços digitais.
**Pergunta que cada linha responde:** o que estão tentando limitar, e por qual instrumento?

**Régua aplicada:** `PROPOSTA` (texto apresentado, não vigente) ≠ `EM TRAMITAÇÃO` ≠ `VIGENTE` ≠ `ENFORCEMENT` (multa, ordem, decisão judicial) ≠ `BARRADO` (vencido em tribunal) ≠ `NÃO CONFIRMADO`.
Nesta frente, o instrumento que **de fato** limita a empresa raramente é lei: é **decisão judicial de remédio** (EUA), **ato de regulador** (CMA, Comissão, JFTC) ou **lei com taxa/offset** (Austrália).

> **Sobreposição deliberada:** os casos de DMA e DSA já estão detalhados em `pesquisa/noticias/uniao-europeia-reino-unido.md`. Aqui eles entram só pelo ângulo concorrencial (remédio, multa, ordem de mudança de produto) e marcados como cross-ref, para não duplicar.

---

## 0. Leitura de conjunto (4 achados que organizam o resto)

1. **Os EUA produziram remédios, não divestitures.** Em 14 meses, três decisões de remédio (Google busca, Google ad tech, Amazon Prime) e **nenhuma** ordem de separação de empresa. O instrumento que sobrou é **interdição contratual + obrigação de entregar dado/interface**: proibição de acordo de exclusividade, adapter de interoperabilidade, snapshot de índice de busca. O desinvestimento do Chrome (2024) e do AdX (2026) foi pedido e negado.
2. **A vigilância migrou do "o que a empresa faz" para "o que a empresa entrega".** O núcleo dos remédios de 2025–2026 é **acesso**: índice de busca a preço marginal, adapter Prebid↔AdX, exportação de dados de publisher, acesso de pesquisador (DSA). Isso é o oposto de uma lei de soberania — é uma obrigação de **abrir**, administrada por monitor judicial ou comitê técnico.
3. **Onde a lei existe, ela é tarifa com desconto, não proibição.** O australiano *News Bargaining Incentive* é o desenho mais explícito: 2,5% da receita de publicidade digital, **cancelável** por contratos com pelo menos seis veículos. A limitação só existe se a empresa se recusar a negociar.
4. **A retaliação dos EUA virou o principal freio às leis de DST.** Ameaça de tarifa de 100% contra países com DST (26/06/2026), depois de a Suprema Corte derrubar as tarifas por IEEPA — e o Canadá já revogou sua DST em 2025 sob pressão. Para o estudo: **qualquer PL brasileiro de taxa digital nasce dentro desse campo de força.**

---

## 1. Tabela-síntese

| # | Item | País/instância | Tipo | Data | Status | Mecanismo concreto |
|---|------|----------------|------|------|--------|--------------------|
| 1.1 | *US v. Google* (busca) — remédios finais | EUA / D.D.C. (Juiz Mehta) | Decisão judicial | 02/09/2025 | Vigente + apelação no D.C. Circuit (alegações finais out/2026) | Proíbe acordos de distribuição **exclusivos**; obriga entrega de índice de busca e dados limitados de usuário a concorrentes qualificados, a preço marginal |
| 1.2 | *US v. Google* (ad tech) — remédios | EUA / E.D. Va. (Juíza Brinkema) | Decisão judicial + minuta de sentença | 02/09/2026; 02/10/2026 | Remédio deferido; sentença **não assinada** | Interoperabilidade AdX↔Prebid e DFP↔Prebid Server; exportação de dados; fim das *Unified Pricing Rules*; proibição de bid direto Google Ads↔DFP; monitor por 6 anos |
| 1.3 | *FTC v. Meta* | EUA / D.D.C. (Juiz Boasberg) | Sentença + recurso | nov/2025; recurso 20/01/2026 | **Barrado** em 1º grau; em apelação | Pedia cisão de Instagram/WhatsApp; tribunal achou que Meta não tem poder de monopólio |
| 1.4 | *Epic v. Apple* (anti-steering) | EUA / N.D. Cal. + 9º Cir. + Suprema Corte | Contempt + injunção | 30/04/2025; 11/12/2025; 30/06/2026 | Injunção vigente; **cert granted** na Suprema Corte (nº 25-1311) | Proíbe Apple de travar links/botões para pagamento externo; barra comissão sobre compra externa (EUA); alcance vale para todos os devs |
| 1.5 | *DOJ v. Apple* (smartphone) | EUA / D.N.J. | Ação antitruste | 21/03/2024; negociação out/2026 | Em curso; **acordo em negociação** | Pede fim de contratos e travas de interoperabilidade (iMessage, relógio, carteira); termos do acordo **NÃO CONFIRMADOS** |
| 1.6 | *FTC v. Amazon* (Prime) | EUA / FTC + tribunal distrital | Acordo (consent) | set/2025; pagamentos out/2026 | Vigente | US$ 1,5 bi de ressarcimento + US$ 1 bi de multa civil; redesenho de fluxo de inscrição/cancelamento |
| 1.7 | App Store Freedom Act (H.R. 3209) | EUA / Câmara | Projeto de lei | 2025 (data exata NÃO CONFIRMADA) | Apresentado, em comissão | Proibir práticas abusivas em loja de aplicativos; sem votação |
| 1.8 | DMA — enforcement 2025–2026 (Apple €500 mi; Meta €200 mi; Google €890 mi) | UE / Comissão | Enforcement | 23/04/2025; 23/07/2026 | Vigente; 60 dias para cumprir (Google) | Fim do anti-steering (Apple), do "consent or pay" binário (Meta) e da autopreferência na Busca + *steering* no Play (Google); multa diária de até 5% do faturamento mundial |
| 1.9 | Ato delegado DSA de acesso a dados | UE / Comissão | Regulamento delegado | 02/07/2025 | Vigente | VLOPs/VLOSEs obrigadas a dar dados a pesquisadores credenciados, com procedimento e portal únicos |
| 1.10 | CMA — SMS de Apple e Google | Reino Unido / CMA | Designação + compromissos + CRs | 22/10/2025; 01/04/2026; 30/06/2026; 20/10/2026 | Designadas; CRs em **consulta** | *Conduct requirements* sob o DMCC 2024: revisão de app, ranking, uso de dados, interoperabilidade iOS, *steering*, acesso a NFC; descumprimento até 10% do faturamento mundial |
| 1.11 | Smartphone Act (MSCA) | Japão / JFTC | Lei vigente | Vigência 18/12/2025 | Vigente + designação (mar/2025) | Obriga SO, loja, navegador e busca: permitir lojas e cobrança alternativas, *choice screen*, não autopreferenciar; taxa de 20% sobre vendas |
| 1.12 | JFTC × Google (anúncios de busca) | Japão / JFTC | Ordem (cessar e desistir) | abr/2025 | Vigente | Fim de cláusulas que impediam parceiros de veicular anúncio de busca de concorrentes |
| 1.13 | Online Platform Fairness Act | Coreia do Sul / KFTC + Assembleia | Projetos de lei (40) | 2024–2026 | **Nenhum aprovado** (19 pendentes, 1 retirado na 22ª legislatura) | Proibiriam autopreferência, *tying*, restrição de multihoming, prazo de repasse; regime *ex ante* à moda do DMA |
| 1.14 | Digital Competition Bill + 37º Relatório | Índia / MCA + Comitê de Finanças | Minuta de lei + relatório parlamentar | Minuta mar/2024; relatório 10/08/2026 | **Não apresentada** ao Parlamento | Regime *ex ante* para "SSDE"; pede código de conduta de e-commerce com neutralidade, transparência algorítmica e acesso não discriminatório a dados |
| 1.15 | CCI × Apple (App Store) | Índia / CCI + Delhi HC | Investigação + ordem judicial | 18/05/2026 | Em curso | CCI obrigada a esperar; Apple obrigada a entregar dados financeiros; multa pode usar faturamento **global** |
| 1.16 | News Bargaining Incentive (NBI) | Austrália / Tesouro + Parlamento | Lei (aprovada) | Exposição 28/04/2026; emendas 03/08/2026; aprovação ago/2026 | **Aprovada no Parlamento**; *royal assent*/vigência NÃO CONFIRMADOS | Taxa de 2,5% da **receita de publicidade digital**, cancelável por contratos com ≥6 veículos (offset de 200% para veículos pequenos) |
| 1.17 | Ameaça tarifária dos EUA contra DSTs | EUA / Presidência + USTR | Ato executivo (ameaça) | 26/06/2026 | **Ameaça**, sem instrumento publicado confirmado | Tarifa de 100% contra países que cobrem DST; pressiona Reino Unido (2%), França, Espanha e Itália (3%) a revogar |
| 1.18 | Revogação da DST canadense | Canadá / Ministério das Finanças + CRA | Revogação administrativa/legislativa | 29/06/2025 | Vigente (não se cobra mais) | Fim da taxa de 3% retroativa a 2022; CRA parou de cobrar e devolveu ~C$ 647 mi |

---

## 2. Itens

### 2.1 *United States v. Google LLC* — remédios no caso da busca (D.D.C.)
- **Instância/autor:** District Court for the District of Columbia, Juiz **Amit P. Mehta**; autores: DOJ Antitrust Division + Estados.
- **Data:** sentença final de remédios em **02/09/2025** (liability em ago/2024).
- **Status:** **VIGENTE e sob apelação** — Google recorreu ao D.C. Circuit; sustentação final noticiada em **20/10/2026**. Efeito suspensivo: ordem sobre *stay* existe nos autos, resultado **NÃO CONFIRMADO**.
- **Mecanismo concreto:** (a) **proibição de acordos de distribuição exclusivos** com Apple, fabricantes e navegadores — o pagamento por padrão não exclusivo continua permitido; (b) **obrigação de entregar dados**: snapshot do *Search Index* (DocID, mapa DocID→URL, primeira coleta, última coleta, spam score, flag de dispositivo) a concorrentes qualificados, **a preço marginal**, e dados Glue/RankEmbed **ao menos duas vezes**; (c) **negados**: venda do Chrome, compartilhamento do Knowledge Graph, dados de anúncios e sinais de popularidade (Navboost/Glue) e de qualidade.
- **Fonte oficial:** sentença (PDF) — https://www.medianama.com/wp-content/uploads/2025/09/US-vs-GOOGLE-anti-trust-case-Amit-Mehta-Final-Judgement.pdf · análise item a item: https://www.medianama.com/2025/09/223-us-court-google-share-search-data-rivals-doj-antitrust-case/ · apelação: https://www.law360.com/retail/articles/2540151/google-makes-last-dc-circ-push-against-doj-s-search-win
- **O que limita:** tira da Google o **instrumento contratual** (exclusividade) e a **vantagem de escala de dados**, mas não o produto nem a empresa. É o remédio de conduta mais forte do período e o único com alcance mundial em disputa.

### 2.2 *United States v. Google LLC* — remédios no caso de ad tech (E.D. Va.)
- **Instância:** Eastern District of Virginia, Juíza **Leonie M. Brinkema**; caso nº 1:23-cv-00108 (EUA + 17 estados).
- **Datas:** responsabilidade em **17/04/2025** (monopólio em ad server de publisher e em ad exchange de display web aberto, mais *tying*); ordem de remédio em **02/09/2026**; minuta conjunta de sentença final protocolada em **02/10/2026** (Doc. 1861), com provisões em **colchetes** — cada lado com sua redação.
- **Status:** **remédio deferido, sentença não assinada**. Rejeitadas as três propostas estruturais: venda do AdX, abertura do código do leilão do DFP e desinvestimento contingente.
- **Mecanismo concreto (o que já não está em disputa):** adapter para instâncias **Prebid** enviarem lances ao AdX; vínculo DFP↔Prebid Server em 12 meses (15 para *programmatic guaranteed*); **exportação gratuita** de configuração e dados históricos do DFP; **arquivo diário de leilão** (preços candidatos, ajustes, documentação para o publisher verificar o vencedor); rescisão de políticas que proíbem repassar lances do AdX a outros sistemas; contratos separados AdX/DFP; **proibição de integração direta de lances Google Ads↔DFP**; monitor nomeado + comitê técnico, com poder de inspecionar código-fonte. Vigência: **6 anos** a partir da entrada em vigor (60 dias após a assinatura). Escopo: **mundial**, mas a redação da Google empurra implementação no exterior para até **24 meses**.
- **Fonte oficial:** docket (Doc. 1861) — https://www.courtlistener.com/docket/66753787/1861/1/united-states-v-google-llc/ · leitura da minuta: https://ppc.land/doj-seeks-6-months-google-12-to-open-its-ad-exchange-to-rivals/
- **O que limita:** transforma o Google em **fornecedor comum** de infraestrutura de leilão — interoperabilidade, preço e informação equivalentes. Não mexe em DV360 nem em AdSense/AdMob.

### 2.3 *FTC v. Meta Platforms* — fim do pedido de cisão
- **Instância/autor:** FTC × Meta; D.D.C., Juiz **James E. Boasberg**.
- **Datas:** julgamento abr/2025 (Zuckerberg depôs); sentença em **novembro de 2025**; **recurso da FTC em 20/01/2026**.
- **Status:** **BARRADO em 1º grau**, vivo em apelação. Meta mantém Instagram e WhatsApp.
- **Mecanismo (o que se tentou):** desinvestimento de Instagram e WhatsApp por aquisição anticompetitiva (art. 13(b) do FTC Act). O tribunal rejeitou a definição de mercado restrita ("personal social networking") e considerou TikTok e YouTube substitutos — sem poder de monopólio, não há base para desfazer fusão passada.
- **Fonte:** https://www.medianama.com/2026/01/223-us-federal-trade-commission-appeals-ruling-meta-instagram-whatsapp/ (Reuters, 20/01/2026) · https://www.bbc.co.uk/news/articles/crklgrpdke8o
- **O que limita:** nada, hoje. Importa pelo efeito de **precedente**: fixa um teste de mercado que dificulta qualquer cisão de rede social nos EUA.

### 2.4 *Epic Games v. Apple* — injunção anti-steering e desacato
- **Instância:** N.D. California (Juíza Yvonne Gonzalez Rogers) → 9º Circuito → Suprema Corte (nº 25-1311).
- **Datas/status:** desacato em **30/04/2025** (Apple cobrava 12–27% sobre compras via link externo); 9º Cir. **confirma em 11/12/2025**, mas derruba a proibição total de comissão e devolve para sanção adequada; rehearing negado em **30/03/2026**; **certiorari concedido em 30/06/2026**.
- **Mecanismo concreto:** a Apple **não pode** impedir botões, links e chamadas para pagamento fora do IAP e **não pode** cobrar comissão sobre compra externa nos EUA. A injunção vale para **todos os desenvolvedores**, não só a Epic — é isso que a Apple contesta na Suprema Corte dos EUA (limites do *complete relief* / *Trump v. CASA*).
- **Fonte oficial:** docket da Suprema Corte — https://www.supremecourt.gov/search.aspx?filename=/docket/docketfiles/html/public/25-1311.html · síntese: https://ipwatchdog.com/2026/06/30/high-court-grants-cert-in-apples-challenge-to-ninth-circuit-contempt-ruling-in-app-store-dispute/
- **O que limita:** é a única ordem do período que **muda o modelo de receita** da loja de apps por via judicial, sem lei e sem regulador.

### 2.5 *DOJ v. Apple* — ação estrutural em negociação
- **Instância:** DOJ + estados (nº exato NÃO CONFIRMADO) × Apple, District of New Jersey; ação proposta em **21/03/2024**.
- **Status:** **em curso**, com negociação de acordo noticiada em **out/2026**; termos, escopo e se haverá acordo **NÃO CONFIRMADOS**.
- **Mecanismo pedido na ação:** obrigações de interoperabilidade (mensageria, relógio, carteira), fim de restrições contratuais a desenvolvedores e a "degradação" de serviços de terceiros no iPhone.
- **Fonte:** https://9to5mac.com/2026/10/16/report-apples-antitrust-negotiations-with-the-doj-spark-concerns-of-a-weak-settlement/ · contexto BR: https://exame.com/tecnologia/apple-inicia-negociacoes-para-encerrar-processo-antitruste-nos-estados-unidos/
- **O que limita:** se virar acordo, é o primeiro caso antitruste dos EUA a **fixar interoperabilidade por consent decree** — modelo europeu importado por settlement.

### 2.6 *FTC v. Amazon.com* — Prime (dark patterns)
- **Instância:** FTC + estados (nº exato NÃO CONFIRMADO); tribunal distrital.
- **Datas/status:** acordo anunciado em **set/2025**; ordem judicial aprovada; pagamentos automáticos a consumidores desde **01/10/2026**; total **US$ 2,5 bi** = **US$ 1,5 bi** de ressarcimento + **US$ 1 bi** de multa civil.
- **Mecanismo concreto:** dinheiro **e** redesenho de fluxo — a empresa não pode inscrever sem consentimento informado nem dificultar o cancelamento; a ordem revisada ampliou elegíveis e subiu o teto de US$ 51 para US$ 200 por consumidor. Pagamentos sem pedido/claim.
- **Fonte oficial:** FTC — https://www.ftc.gov/news-events/news/press-releases/2026/09/ftc-announces-additional-payments-consumers-stemming-ftcs-amazon-prime-settlement · ordem (PDF): https://www.ftc.gov/system/files/ftc_gov/pdf/2123050amazonprimeredressfundorder.pdf
- **O que limita:** não é antitruste; é **desenho de produto compulsório** com preço. É o precedente mais replicável para uma lei que queira proibir padrões escuros sem criar regime novo.

### 2.7 App Store Freedom Act (H.R. 3209, 119º Congresso)
- **Instância:** Câmara dos Representantes dos EUA.
- **Status:** **PROPOSTA** — apresentado em 2025, em comissão, sem votação. **Autor e data exata: NÃO CONFIRMADOS.**
- **Mecanismo:** proibir atos desleais ou enganosos no mercado de aplicativos (redação do título oficial), o que na prática atacaria regras de distribuição e cobrança de Apple e Google.
- **Fonte oficial:** https://www.congress.gov/bill/119th-congress/house-bill/3209/text/ih
- **O que limita:** nada ainda. Serve como termômetro: o Congresso não legislou sobre lojas de app; quem legislou foram Japão, Coreia (tentativa) e a UE.

### 2.8 DMA — enforcement de 2025–2026 (Apple, Meta, Google)
- **Instância:** Comissão Europeia (DG COMP), sob o Reg. (UE) 2022/1925.
- **Decisões:** (a) **23/04/2025** — Apple **€500 mi** (anti-steering) e Meta **€200 mi** ("consent or pay" sem alternativa equivalente) — *números conferidos no dossiê UE/Reino Unido desta pesquisa*; (b) **23/07/2026** — Google **€460 mi** (autopreferência na Busca: shopping, hotéis, transporte, esportes) + **€430 mi** (*steering* no Google Play), total **€890 mi**.
- **Status:** **ENFORCEMENT vigente**; Google tem **60 dias** para cumprir sob pena de multa periódica de até **5% do faturamento mundial**; recursos possíveis.
- **Mecanismo concreto:** ordem de cessar a conduta + **obrigação positiva de redesenho**: tratar serviços de terceiros de forma justa e não discriminatória no ranking; permitir técnica e contratualmente que o desenvolvedor comunique ofertas e feche contratos fora do Play, sem taxa de *steering* que exceda o permitido. A decisão declara que os princípios se aplicam a **AI Overviews e AI Mode**, em diálogo aberto com o Google.
- **Fonte oficial:** Comissão, 23/07/2026 — https://cyprus.representation.ec.europa.eu/news/commission-fines-google-eur890-million-breaches-digital-markets-act-2026-07-23_en
- **O que limita:** é o único regime que **proíbe a conduta por categoria** (sem precisar provar dano caso a caso) e alcança **produto de IA** por interpretação. Para o estudo brasileiro, é o modelo de "regra + multa + prazo".

### 2.9 Ato delegado do DSA sobre acesso a dados para pesquisadores
- **Instância:** Comissão Europeia (Regulamento Delegado (UE) **2025/2050**), sob o art. 40 do DSA.
- **Data/status:** adotado em **02/07/2025**; **VIGENTE** (aplica-se a VLOPs/VLOSEs).
- **Mecanismo concreto:** fixa **condições técnicas e procedimento único** para pedido de acesso, o que DSPs, plataformas e Coordenadores de Serviços Digitais devem publicar, e cria o **portal de acesso a dados do DSA**. A plataforma é obrigada a entregar dados — inclusive não públicos — a pesquisador credenciado, sob regras de segurança e finalidade.
- **Fonte oficial:** https://digital-strategy.ec.europa.eu/en/library/delegated-act-data-access-under-digital-services-act-dsa · texto: https://eur-lex.europa.eu/eli/reg_del/2025/2050/oj/eng
- **O que limita:** é a **única norma vinculante de transparência para pesquisa** identificada nesta frente. Não obriga a mudar o algoritmo; obriga a **abrir os dados que provam o que o algoritmo faz**.

### 2.10 Reino Unido — CMA designa Apple e Google com *strategic market status*
- **Instância:** Competition and Markets Authority, Digital Markets Unit, sob a Parte 1 do **DMCC Act 2024**.
- **Datas/status:** investigações abertas em **23/01/2025**; decisões finais de SMS em **22/10/2025** (SO, distribuição nativa de apps, navegador e engine); **compromissos finais aceitos em 01/04/2026** (revisão de app, ranking, uso de dados, acesso interoperável a funcionalidades do iOS); **consultas de *conduct requirement* de *steering*** abertas em **30/06/2026** (respostas em 14/08/2026) e de **acesso a NFC** em **20/10/2026**.
- **Mecanismo concreto:** a designação permite impor **conduct requirements** (o que a empresa deve fazer/deixar de fazer, sob pena de multa de até 10% do faturamento mundial) e **pro-competition interventions** (inclusive estrutural). As CRs em consulta miram exatamente o que a UE já multou: travas de *steering* e acesso a hardware (NFC).
- **Fonte oficial:** https://www.gov.uk/cma-cases/apples-mobile-platform · https://www.gov.uk/cma-cases/googles-mobile-platform · https://www.gov.uk/government/consultations/proposed-steering-conduct-requirement-for-googles-mobile-platform
- **O que limita:** cria um **regulador com poder de ditar produto** sem precisar de caso judicial. A diferença para a UE: o Reino Unido negocia "compromissos" antes de impor a regra.

### 2.11 Japão — Smartphone Software Competition Promotion Act (MSCA)
- **Instância:** JFTC (Fair Trade Commission), lei de 2024; designação em **março de 2025** (Apple, iTunes, Google) como "provedores de software especificado".
- **Data/status:** **em vigor desde 18/12/2025**.
- **Mecanismo concreto:** para SO, loja de apps, navegador e mecanismo de busca: **não impedir** lojas de app e sistemas de pagamento de terceiros; exibir **tela de escolha** de navegador e de busca; não autopreferenciar; não usar dados de concorrentes obtidos na operação da loja. Sanção: **20% das vendas** (taxa majorada para reincidência, conforme a lei).
- **Efeito verificado no dia da vigência:** Apple liberou marketplaces alternativos e cobrança externa no Japão, com taxas de 10%/21%, 5% sobre pagamento próprio e **5% de Core Technology Fee**; Google liberou cobrança alternativa para **todos** os apps (antes só não-jogos) e ativou *choice screen* no Chrome. Apple criou ainda o botão lateral para assistente de voz de terceiro **só no Japão**, declaradamente por causa da lei.
- **Fonte oficial:** JFTC — https://www.jftc.go.jp/msca/ · decreto: https://laws.e-gov.go.jp/law/506CO0000000376 · mudanças: https://www.apple.com/jp/newsroom/2025/12/apple-announces-changes-to-ios-in-japan/
- **O que limita:** é o caso em que a lei **forçou mudança de produto verificável em 1 dia** — e o único do G7 com taxa de 20% sobre vendas como sanção.

### 2.12 Japão — JFTC × Google (contratos de anúncio de busca)
- **Instância:** JFTC.
- **Data/status:** **abril/2025** — ordem de cessar e desistir por prática desleal de comércio.
- **Mecanismo concreto:** proibição de cláusulas que restringiam parceiros (fabricantes/operadoras) de veicular anúncios de busca de concorrentes — limitação de **exclusividade contratual**, não de produto.
- **Fonte:** https://competitionlawblog.kluwercompetitionlaw.com/2025/04/29/on-the-japan-fair-trade-commissions-google-decision-some-early-reflections/ · https://www.vitallaw.com/news/antitrust-news-japan-s-antitrust-agency-issues-cease-and-desist-orders-to-google-toyota/ald014fd961fa5f8e425cb6a6be9f1df1154d
- **O que limita:** mesma lógica do remédio americano (fim da exclusividade), por autoridade administrativa e sem multa conhecida — **valor de multa: NÃO CONFIRMADO**.

### 2.13 Coreia do Sul — Online Platform Fairness Act: 40 projetos, zero aprovados
- **Instância:** Assembleia Nacional (Comissão de Assuntos Políticos) + KFTC como proponente técnica.
- **Status (verificado em mar/2026):** **20 projetos na 21ª legislatura, todos caducados**; **20 na 22ª** (19 pendentes, 1 retirado) — **nenhum aprovado**. Entre eles: Chun Jun-ho (**02/10/2024**, regime *ex ante* citando DMA e lei japonesa), Kim Hyun-jung (**06/08/2024**, prazo de repasse de vendas), Kim Nam-geun (**18/10/2024**, 58 assinaturas).
- **Mecanismo proposto:** proibir autopreferência, venda casada, restrição de multihoming e fixar prazo de liquidação de receitas a lojistas. O presidente da KFTC, **Ju Biung-ghi**, declarou em **08/01/2026** que o texto "não mira empresas dos EUA" e que Naver e Coupang estariam sujeitas igualmente — resposta a pressão do Congresso americano.
- **Fonte:** https://newsepoch.co.kr/news/2026031600004 (levantamento legislativo) · https://www.koreaherald.com/article/10652330 (KFTC, 09/01/2026)
- **O que limita:** nada, hoje. É o contraexemplo mais útil: **país com mercado grande e projeto desenhado sobre o DMA, parado por veto de fato** — pressão externa + 19 textos concorrentes sem acordo de escopo.

### 2.14 Índia — Digital Competition Bill + 37º Relatório do Comitê de Finanças
- **Instância:** Ministério de Assuntos Corporativos (Minuta de mar/2024, Comitê de Lei de Concorrência Digital) + Comitê Permanente de Finanças do Parlamento.
- **Status:** **a lei não foi apresentada** ao Parlamento. O 37º Relatório, apresentado em **10/08/2026**, pede que o governo **finalize a DCB** e adote regime *ex ante*; o governo responde que faz "estudo de mercado" sobre limiares e Serviços Digitais Centrais — ou seja, **a minuta segue em revisão**.
- **Mecanismo proposto:** designação de **SSDE** (Systemically Significant Digital Enterprise) com obrigações de não autopreferência, não *tying*, interoperabilidade; o Comitê pediu **mecanismo de rebuttal** (que o texto não tem) e limiares mais rígidos para não capturar empresas indianas. Pediu também **Código de Conduta de e-commerce** com **neutralidade de plataforma, transparência algorítmica e acesso não discriminatório a dados** para pequenos negócios, além de auditorias algorítmicas pela Divisão de Mercados Digitais da CCI.
- **Fonte oficial:** relatório (PDF) — https://www.medianama.com/wp-content/uploads/2026/08/10Aug2026_ParliamentaryCommitteeFinanceReport.pdf · síntese: https://www.bricscompetition.org/news/indias-parliamentary-finance-committee-urges-govt-to-finalise-digital-competition-bill
- **Dado de enforcement que o relatório revela:** CCI aplicou **₹ 20.350,46 crore** até 30/04/2025, mas **₹ 18.512,28 crore** estavam suspensos ou anulados em recurso — só **₹ 1.838,19 crore** eram exigíveis. É a medida do **gap entre multa e multa paga**.

### 2.15 Índia — CCI × Apple (App Store)
- **Instância:** Competition Commission of India + Delhi High Court.
- **Datas/status:** investigação aberta (ordem de 2024 por abuso de posição dominante no mercado de apps do iPhone); **18/05/2026** — Delhi HC manda Apple **cooperar** e proíbe a CCI de decidir antes de **15/07/2026**; Apple entregou dados financeiros em **jun/2026**.
- **Mecanismo concreto:** a CCI quer os dados para calcular multa sob a emenda de 2023 que permite base **faturamento global** — a exposição noticiada chega a cifras bilionárias (o valor de **US$ 38 bi** circulou na imprensa asiática: **NÃO CONFIRMADO**). A limitação em si seria comportamental (regras de cobrança e distribuição), mas o instrumento de pressão é a **base de cálculo da multa**.
- **Fonte:** https://www.macrumors.com/2026/05/19/india-refuses-to-let-apple-pause-app-store-case/ · https://www.business-standard.com/amp/companies/news/apple-agrees-to-provide-india-financial-data-to-cci-in-antitrust-case-126060400006_1.html
- **O que limita:** ainda nada. O ponto para o estudo: **índia discute a regra de "faturamento global"**, que é o mecanismo que dá dente a um regulador de país periférico contra big tech.

### 2.16 Austrália — News Bargaining Incentive (taxa com desconto por contrato)
- **Instância:** Tesouro (Ministro Assistente Daniel Mulino) + Ministério das Comunicações (Anika Wells); lei aprovada pelo Parlamento.
- **Datas/status:** exposição pública em **28/04/2026**; emendas anunciadas em **03/08/2026** (taxa de 2,25% → **2,5% da receita de publicidade digital**; ≥6 veículos em vez de 4; *offset* de 200% para veículos pequenos; 5% do arrecadado para fundo de grants); **aprovada em agosto/2026**. Data de *royal assent* e de início de vigência: **NÃO CONFIRMADAS**.
- **Mecanismo concreto:** a plataforma paga **2,5% da receita de publicidade digital** na Austrália, **salvo** se tiver acordos comerciais com ao menos seis veículos — os acordos são dedutíveis e "abatem" a taxa. Aplicável a Meta, Google e TikTok por limiares (receita australiana ≥ A$ 250 mi; 5 mi de usuários para rede social, 10 mi para busca). **Vale mesmo se a plataforma não hospeda notícia** — fecha a brecha que a Meta usou em 2021 ao despriorizar notícias. IA generativa ficou **excluída**.
- **Fonte oficial:** transcrição do Ministro Assistente (29/04/2026) — https://ministers.treasury.gov.au/ministers/daniel-mulino-2025/transcripts/interview-sally-sara-rn-breakfast-abc-radio-0 · emendas: https://newsapp.abc.net.au/news/2026-08-03/big-tech-google-australian-media-news-bargaining-/106989038 · confirmação de aprovação: https://piji.com.au/newsletters/september-2026-newsletter/
- **O que limita:** não proíbe conduta: **cria preço** para a recusa em negociar. É o desenho mais próximo de "taxar para forçar acordo" e o que os EUA já sinalizaram que retaliariam.

### 2.17 EUA × DSTs europeias — a ameaça tarifária como instrumento
- **Instância:** Presidência dos EUA; USTR.
- **Data:** **26/06/2026** — Trump declara que qualquer país europeu que cobre DST de empresas americanas sofrerá **tarifa de 100%**, "imediatamente", substituindo acordos comerciais anteriores; o mesmo contra vinho e champanhe franceses, salvo revogação da DST pela França. Prazo de implementação do acordo tarifário UE–EUA: **04/07/2026**.
- **Status:** **ameaça**, não ato publicado — não há proclamação ou determinação confirmada até 31/10/2026. Contexto jurídico: a Suprema Corte **derrubou as tarifas por IEEPA** (*Learning Resources v. Trump*), e o USTR passou a preparar investigações **Section 301**; data exata da decisão: **NÃO CONFIRMADA**.
- **Mecanismo concreto:** a limitação não recai sobre a empresa — recai sobre o **Estado que taxa**. Tarifa de importação como represália por regra fiscal sobre receita digital. DSTs em vigor citadas: **Reino Unido 2%** (arrecadação de £ 800 mi+ em 2024-25), **França, Espanha e Itália 3%**.
- **Fonte:** https://www.ccpit.org/france/a/20260702/20260702sj92.html (compilação com dados do Guardian/BBC, 02/07/2026) · CRS sobre IEEPA: https://www.congress.gov/crs-product/LSB11398
- **O que limita:** é o **teto político** de qualquer DST. Para o PL brasileiro, é o dado que decide desenho: taxa sobre receita (DST) atrai represália; taxa condicionada a acordo (modelo australiano) é apresentada pelo governo como "não-DST" — a Meta chama de DST de qualquer forma.

### 2.18 Canadá — revogação da DST de 3%
- **Instância:** Ministério das Finanças + Canada Revenue Agency.
- **Data/status:** anúncio de revogação em **29/06/2025**, um dia antes do primeiro vencimento; CRA parou de exigir declaração e pagamento; devolução de ~**C$ 647 mi** já arrecadados noticiada depois. Lei revogadora dependia de *royal assent* — status legislativo final **NÃO CONFIRMADO**.
- **Mecanismo concreto:** DST de **3%** sobre receita de serviços digitais (marketplace, publicidade, redes sociais, licenciamento de dados de usuário), retroativa a **01/01/2022**, para grupos com receita global ≥ € 750 mi e receita digital canadense > C$ 20 mi. Revogada sob pressão comercial dos EUA e negociação de acordo.
- **Fonte oficial:** https://www.canada.ca/en/department-finance/news/2025/06/canada-rescinds-digital-services-tax-to-advance-broader-trade-negotiations-with-the-united-states.html · análise: https://www.millerthomson.com/en/insights/corporate-tax/canadas-digital-services-tax-what-the-june-2025-reversal-means-for-your-business/
- **O que limita:** limita **o Estado**, não a empresa. É o caso mais claro de DST **morta por pressão externa** antes de produzir um centavo de receita líquida.

---

## 3. Lacunas

- **FTC v. Amazon (monopolização, nov/2023):** não confirmei data de julgamento nem status processual em 2026. Não incluí por falta de fonte primária.
- **Multa da KFTC contra a Coupang (~US$ 121 mi provisórios, 2º tri/2026):** só achei fonte secundária (post de LinkedIn). **NÃO CONFIRMADO** — valor, data e fundamento precisam de verificação no site da KFTC.
- **DMA — decisões de especificação de interoperabilidade (iOS/Android) em 2026:** o dossiê UE/Reino Unido cobre o marco; o estado de cada especificação em out/2026 não foi reverificado aqui.
- **Digital Fairness Act (UE):** anunciada como próxima proposta da Comissão; não confirmei apresentação, número ou conteúdo. Fica fora da tabela.
- **Pilar Um / Amount A da OCDE:** não confirmei o status em 2026 (a literatura indica paralisia após a saída dos EUA, mas sem ato oficial localizado). Sem isso, a seção de tributação fica só com DSTs unilaterais + represália.
- **Austrália — novo regime de concorrência para plataformas:** o ACCC recomendou reforma regulatória (relatório final de **mar/2025**) e o Tesouro consultou, mas **o regime não foi legislado** (MLex, 2026). Não é item porque não há texto; é o principal "quase" desta frente.
- **Reino Unido — imposição final das *conduct requirements*:** as consultas de *steering* (30/06/2026) e NFC (20/10/2026) ainda não viraram ordem. Qualquer afirmação de "CR vigente" seria falsa.
- **Brasil:** fora do escopo desta frente (CADE, PL 2768/2022, PL das plataformas). Deve estar em dossiê próprio; se não estiver, é lacuna do conjunto, não desta frente.
- **Transparência algorítmica fora da UE:** só achei **recomendação** (Comitê de Finanças da Índia) e **consulta** (CMA). Nenhum estatuto novo vinculante de "explicar o algoritmo" foi identificado em 2025–2026 — o que existe é acesso a dados (DSA) e proibição de autopreferência (DMA, MSCA, Japão).
- **Valores de multa não confirmados** ficaram marcados no texto: JFTC×Google (sem valor conhecido), CCI×Apple (US$ 38 bi é estimativa de imprensa), DOJ×Apple (termos do acordo).
