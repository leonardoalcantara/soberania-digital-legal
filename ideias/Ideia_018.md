# Ideia 018 — Autopreferência e interoperabilidade

**Bloco:** D — responsabilidade e infraestrutura
**Origem:** proposta nova
**Estado:** proposta de trabalho

---

## 1. O que a proposta é

Duas obrigações que a comparação trata juntas e que são, na verdade, distintas:

**(a) Autopreferência** — vedar que a plataforma favoreça serviço ou produto próprio no ranqueamento, na indexação, nos resultados de busca ou na apresentação, sem justificativa;

**(b) Interoperabilidade** — obrigar a abertura a terceiros: portabilidade efetiva de dados, acesso a funcionalidades do sistema em condições equivalentes e interfaces para que outros serviços funcionem.

A primeira é regra de **conduta**; a segunda é regra de **acesso**. Ficam no mesmo arquivo porque a literatura e os textos legais as tratam como um par — mas a escolha de uma não implica a outra.

---

## 2. Como aparece em outros ordenamentos

| Onde | Instrumento | Mecanismo |
|---|---|---|
| União Europeia | DMA (Reg. 2022/1925), art. 6, § 5º | Vedação de tratamento mais favorável ao próprio serviço em **ranqueamento, indexação e rastreamento**, com dever de condições transparentes, justas e não discriminatórias |
| União Europeia | DMA, art. 6, § 7º | Interoperabilidade **gratuita e efetiva** com as mesmas funcionalidades de hardware e software do sistema operacional ou assistente virtual |
| União Europeia | DMA, art. 7 | Interoperabilidade das funcionalidades básicas de serviços de mensageria, com **oferta de referência** publicada e prazo de 3 meses para atender pedido |
| União Europeia | DMA, art. 6, §§ 9º e 10 | Portabilidade efetiva de dados do usuário final e acesso contínuo e em tempo real a dados por usuários comerciais |
| Japão | Lei nº 58/2024 (software de smartphone), itens ③, ④ e ⑥ | Vedação de preferência em resultados de busca sem razão justificável; telas de escolha e troca simples de padrões; uso de funcionalidades do sistema em **mesmo nível de desempenho** |

### União Europeia — a vedação mais estreita e mais precisa

DMA, art. 6, § 5º:

> "O controlador de acesso **não tratará de forma mais favorável, no ranqueamento e nas atividades conexas de indexação e rastreamento, os serviços e produtos que ele próprio oferece** do que serviços ou produtos semelhantes de terceiros. O controlador de acesso aplicará condições transparentes, justas e não discriminatórias a esse ranqueamento."

Fonte: `fontes/UE/2022-regulamento-ue-2022-1925-dma.pdf`

**O detalhe que importa:** a norma não proíbe "favorecer o próprio serviço" em geral — proíbe no
**ranqueamento, indexação e rastreamento**. É uma formulação estreita, verificável e limitada a uma operação técnica identificável.

O art. 6, § 7º, sobre interoperabilidade:

> "O controlador de acesso permitirá aos prestadores de serviços e aos fornecedores de hardware, **a título gratuito, interoperabilidade efetiva com as mesmas funcionalidades de hardware e software** acessadas ou controladas pelo sistema operacional ou assistente virtual constantes da decisão de designação, que estejam disponíveis aos serviços ou ao hardware por ele oferecidos."

E o art. 7, sobre mensageria, vai além: exige que o controlador publique **oferta de referência** com os detalhes técnicos e as condições gerais de interoperabilidade, e cumpra pedido razoável **em até 3 meses**.

### Japão — a formulação mais direta sobre busca

Lei nº 58/2024, item ④ do sumário oficial:

> "Os Prestadores Designados **não poderão praticar qualquer forma de tratamento preferencial de seus serviços em relação aos de concorrentes na exibição de resultados de busca sem razão justificável**."

Item ⑥:

> "Os Prestadores Designados não poderão impedir que desenvolvedores de aplicativos usem funcionalidades controladas pelo sistema operacional **com o mesmo nível de desempenho** daquele usado pelos Prestadores Designados."

Item ③:

> "Os Prestadores Designados deverão permitir que os usuários **alterem as configurações padrão com procedimentos simples** e oferecer **telas de escolha** para navegadores etc."

Fonte: `fontes/Japao/2024-lei-58-smartphone-software.xml` (sumário oficial em `jftc-sumario-oficial-da-lei-EN.md`)

**O que o desenho japonês tem de diferente:** é a única norma do acervo que enuncia a vedação de
autopreferência **referindo-se expressamente a "resultados de busca"**, e não a "ranqueamento" em geral. Também é a que trata o **desempenho** como parâmetro de comparação na interoperabilidade — não basta haver acesso, tem de ser no mesmo nível.

E há um detalhe de execução: o descumprimento sujeita o infrator a **ordem de pagamento de 20% do faturamento relevante**.

---

## 3. O que já existe no Brasil (e o que falta)

**Existe:**

- **Marco Civil, art. 3º, IV** — a "adesão a padrões tecnológicos abertos que permitam a comunicação, a acessibilidade e a **interoperabilidade** entre aplicações e bases de dados" é **princípio** da internet no Brasil. Não é obrigação exigível de ninguém em particular.
- **Marco Civil, art. 24, III e IV** — diretrizes de atuação do poder público: interoperabilidade tecnológica dos serviços de governo eletrônico e interoperabilidade entre sistemas e terminais.
- **LGPD, art. 18, V** — direito do titular à **portabilidade** dos dados a outro fornecedor, mediante requisição expressa, observados segredos comercial e industrial.
- **LGPD, art. 40** — a autoridade nacional poderá dispor sobre **padrões de interoperabilidade** para fins de portabilidade, livre acesso aos dados e segurança.
- **Lei de Acesso à Informação, art. 8º, § 3º, II e III** — dever de publicar em formatos abertos e não proprietários e de permitir acesso automatizado por sistemas externos, em formato estruturado e legível por máquina. Vale para o **setor público**.
- **LGT, art. 171** — precedente de preferência legal expressa: "deverá ser dada preferência ao emprego de satélite brasileiro, quando este propiciar condições equivalentes às de terceiros". É preferência **do Estado**, não da plataforma — mas é o único dispositivo do acervo brasileiro que trata de preferência em contratação de tecnologia.
- **TSE, Res. 23.755/2026, art. 28, § 1º-C** — proibição de ranquear, recomendar ou priorizar **candidatos** por sistemas de IA. Vale só no período eleitoral.

**Falta:**

1. **Vedação de autopreferência.** Não existe em nenhuma norma brasileira vigente.
2. **Dever de transparência de ranqueamento** quanto a tratamento do próprio serviço.
3. **Interoperabilidade como obrigação** — hoje é princípio (Marco Civil) e direito individual (LGPD art. 18, V), não dever do fornecedor perante terceiros.
4. **Oferta de referência** com condições técnicas de interoperabilidade, como no art. 7 do DMA.
5. **Parâmetro de desempenho** equivalente, como no item ⑥ japonês.
6. **Poder de designação** de quem está sujeito às obrigações — sem isso, a norma se aplica a todos ou a ninguém.

---

## 4. O que a comparação revela

**É a proposta do bloco mais bem documentada no exterior e a mais frágil no Brasil.** Todos os instrumentos do acervo que tratam do tema são **ex ante** e dirigidos a um universo fechado de empresas designadas: DMA (controladores de acesso designados), Japão (Prestadores Designados por critério de escala).

O Brasil só tem o instrumento **ex post** — o CADE, pelo direito da concorrência. E o acervo não tem o texto da Lei 12.529/2011, o que impede descrever com precisão o que a autoridade antitruste já pode fazer.

**A lição mais útil para o caso brasileiro é a da especificidade.** A vedação do DMA não é "não favoreça o próprio serviço": é "não favoreça no ranqueamento, na indexação e no rastreamento". A japonesa é "não favoreça na exibição de resultados de busca". Ambas são verificáveis porque são estreitas. Uma vedação genérica de autopreferência é inexequível.

**A lição da interoperabilidade** é que o dever precisa de um documento: a **oferta de referência** do art. 7 do DMA é o que transforma "interoperabilidade" em pedido que se protocola e prazo que se conta.

**A lição japonesa do desempenho** resolve o problema prático da interoperabilidade: acesso que funciona pior não é acesso.

---

## 5. Parâmetros que precisam de decisão

| Parâmetro | Opções | Consequência |
|---|---|---|
| **Escopo subjetivo** | todos os provedores × designados por escala × por poder de mercado | Designação por escala é objetiva e verificável; por poder de mercado exige análise caso a caso |
| **Escopo material da autopreferência** | ranqueamento × resultados de busca × apresentação em geral | "Em geral" é inexequível; busca e ranqueamento são verificáveis |
| **Justificativa** | vedação absoluta × vedação salvo razão justificável (Japão) | Absoluta é mais simples e mais rígida; a exceção permite segurança e privacidade como defesa |
| **Interoperabilidade** | portabilidade de dados × funcionalidades do sistema × mensageria | São três regimes distintos, com custos técnicos muito diferentes |
| **Padrão de qualidade** | acesso × acesso em nível de desempenho equivalente (Japão) | Só "acesso" permite interoperabilidade simbólica |
| **Instrumento** | oferta de referência publicada × negociação caso a caso × imposição pela autoridade | Oferta de referência dá previsibilidade e reduz litígio |
| **Prazo de atendimento** | 3 meses (DMA) × prazo próprio | Prazo é o que dá exequibilidade ao direito |
| **Sanção** | multa × ordem de cessar × percentual do faturamento (20% no Japão) | Percentual do faturamento é o que dá escala à dissuasão |
| **Autoridade** | CADE × nova autoridade × ANPD | Escolha institucional ainda em aberto neste projeto (ver Ideia 006) |

---

## 6. Lacunas de pesquisa

1. **Falta a Lei 12.529/2011 no acervo** — sem ela não é possível descrever o que o CADE já pode fazer contra autopreferência por via antitruste, nem comparar com o instrumento ex ante.
2. Não há, no acervo, **estudo ou decisão** do CADE sobre autopreferência em plataformas.
3. Não verifiquei se o **PL 4752/2025** ou o **PL 4218/2025** tratam de autopreferência — os dois estão fora do acervo.
4. Não localizei **definição técnica** de "interoperabilidade" em norma brasileira vigente além do princípio do Marco Civil.
5. Não verifiquei se a **ANPD** já editou a regulamentação do art. 40 da LGPD sobre padrões de interoperabilidade.
6. Não há, no acervo, o texto da **Lei 58/2024 japonesa** em articulado — só o sumário oficial do JFTC. Citar por artigo exige conferir o original.

---

## 7. Perguntas abertas

1. A proposta trata **autopreferência e interoperabilidade** juntas ou são duas proposições separadas?
2. Quem está sujeito: **todos** os provedores, os designados por **escala** (modelo Japão) ou os designados por **poder de mercado** (modelo DMA)?
3. A vedação de autopreferência alcança **só busca e ranqueamento** ou também a apresentação e os padrões?
4. Há **exceção justificável** por segurança, privacidade ou proteção de menores?
5. A interoperabilidade exige **oferta de referência** publicada e prazo de atendimento?
6. O padrão é **acesso** ou **acesso em nível de desempenho equivalente**?
7. Quem aplica — CADE, autoridade nova ou ANPD?
