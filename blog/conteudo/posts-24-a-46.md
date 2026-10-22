# NX Digital — Blog: conteúdo dos posts 24 a 46

Veja `00-estrutura-e-design.md` para convenções, índice e design.

---

## POST 24 — Recordly: o repositório grátis que grava e edita sua tela sozinho

- URL: `/blog/recordly`
- Template: padrão (hero + artigo 720px)
- Categoria: FERRAMENTAS & IA
- Data no card: 9 Set 2026 | Data na página: 9 de setembro de 2026
- Tempo de leitura: 5 min (página: "5 min de leitura")
- Resumo do card: O Recordly é um gravador de tela open source que edita o vídeo enquanto você grava: zoom automático, cursor suavizado, webcam reativa e exportação pronta pra postar. Link, instalação e passo a passo completo.
- Meta description: O Recordly é um gravador de tela open source que edita o vídeo enquanto você grava: zoom automático, cursor suavizado, webcam reativa e exportação pronta pra postar. Link, instalação e passo a passo completo.
- Título da aba: Recordly: o Repositório Grátis que Grava e Edita sua Tela Sozinho | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01O Que É · 02Como Instalar · 03Como Usar · 04Pra Quem Serve · 05Antes de Usar · 06O Próximo Passo

### Corpo do post (conteúdo exato, na ordem da página)

O material prometido no reel "Achei um repositório grátis no GitHub que grava sua tela e já edita o vídeo sozinho". Aqui vai o link e o passo a passo completo, com mais detalhe do que cabia no vídeo.

**Link do repositório:** [github.com/webadderallorg/recordly](https://github.com/webadderallorg/recordly)

## O Que É

Recordly é um gravador de tela de código aberto que edita o vídeo enquanto você grava, não depois. A promessa do próprio projeto é criar vídeo de demonstração pronto em minutos, sem precisar saber editar. É grátis, licença AGPL 3.0, já passou de 26 mil estrelas no GitHub e mais de 1.900 forks. Renderiza com PixiJS por baixo.

## Como Instalar

**Mac (macOS 14 ou superior):** baixe o build pronto direto na página de [releases](https://github.com/webadderallorg/recordly/releases) do repositório.

**Windows (build 19041 ou superior, de maio de 2020 em diante):** mesmo caminho, build pronto em releases.

**Linux:** também tem build pronto em releases. Se você usa Arch, instala direto com `yay -S recordly-bin`. A captura de áudio em Linux depende de PipeWire.

**Quem quiser compilar do código-fonte:**

:::bloco
terminal — compilar do código-fonte⟦botão: Copiar⟧

```
git clone https://github.com/webadderallorg/recordly.git
npm install
npm run dev
```
:::fim

## Como Usar

1. 1.**Grave.** Abra o app, escolha tela inteira, uma janela ou uma área específica, defina microfone e áudio do sistema, e aperte gravar. Trabalha normal enquanto grava.
2. 2.
  :::bloco
  **Edite na timeline.** Ao parar, o material abre direto no editor:
  
  - →zoom automático nos pontos onde você clicou, ou zoom manual em qualquer trecho
  - →cursor renderizado com ajuste de tamanho, suavização, desfoque de movimento e efeito de clique
  - →regiões de aceleração e desaceleração
  - →corte de pedaço indesejado
  - →anotação em texto, imagem e forma
  - →áudio extra por cima da gravação
  :::fim
3. 3.**Ajuste a webcam (opcional).** Sobe o vídeo da câmera, espelha se precisar, posiciona por preset ou coordenada customizada, define margem, arredondamento e sombra. A webcam reagia ao zoom da tela sozinha, sem você reposicionar toda hora.
4. 4.**Escolha o visual.** Papel de parede embutido ou fundo próprio, desfoque de fundo, cantos arredondados, sombra e proporção de tela.
5. 5.**Exporte.** Vídeo (MP4) ou GIF, do jeito que sair pronto pra postar.

O projeto também salva o trabalho em arquivos `.recordly`, então dá pra fechar e voltar depois sem perder a edição.


## Pra Quem Serve

Qualquer coisa que hoje depende de contratar edição pra provar que uma ferramenta funciona: demonstração de produto, tutorial de sistema pro cliente, vídeo curto de onboarding, ou o próprio reel de "como usar X" que você está gravando agora.

O ganho não é só o custo de zero. É não precisar abrir um editor de vídeo separado pra cada gravação de tela.

## Antes de Usar

- Baixei o build certo pro meu sistema (Mac, Windows ou Linux) na página de releases.
- Testei uma gravação curta primeiro, pra ver o zoom automático antes de gravar o material de verdade.
- Se for usar webcam, testei o posicionamento antes de começar a gravar (o quadro final já sai enquadrado, sem precisar reposicionar na edição).

## O Próximo Passo

Baixa, testa uma gravação de 30 segundos qualquer, e vê se o zoom automático já sai bom o suficiente pra você. Se sair, sua próxima demonstração de sistema pro cliente sai sem precisar abrir outro programa.

---

## POST 25 — 4 Claude Skills de marketing prontas pra instalar

- URL: `/blog/skills-marketing`
- Template: padrão (hero + artigo 720px)
- Categoria: CLAUDE SKILLS
- Data no card: 9 Set 2026 | Data na página: 9 de setembro de 2026
- Tempo de leitura: 6 min (página: "6 min de leitura")
- Resumo do card: 4 Claude Skills de marketing de terceiros, verificadas por número real de estrelas no GitHub: CRO e copywriting, o catálogo mais completo, auditoria de mídia paga e marca/site inteiros.
- Meta description: 4 Claude Skills de marketing de terceiros, verificadas por número real de estrelas no GitHub: CRO e copywriting, o catálogo mais completo, auditoria de mídia paga e marca/site inteiros.
- Título da aba: 4 Claude Skills de Marketing Prontas pra Instalar | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 0101. marketingskills · Corey Haines · 0202. claude-skills · Alireza Rezvani · 0303. claude-ads · Daniel Agrici · 0404. Brand Build Skills · RampStack · 05Antes de Instalar Qualquer Uma

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar SKILLS.

Nenhuma dessas 4 é minha, e nenhuma é da Anthropic (a empresa que faz o Claude). São skills de terceiros, código aberto, no formato técnico que a Anthropic criou pra qualquer pessoa estender o Claude. Eu testei, chequei o número de estrelas de cada uma direto na API do GitHub (não em site de blog) e separei as 4 que realmente entregam.

Uma skill não roda sozinha: você instala, e ela dá ao Claude a instrução e o método certo pra aquela tarefa. Você continua revisando o que ela sugere antes de aplicar.

## 01. marketingskills · Corey Haines

**49.127 estrelas no GitHub.** A mais usada de todas as que verifiquei.

**Quem fez:** Corey Haines, fundador da Swipe Files (comunidade de marketing), ex-head of growth da Baremetrics, consultor de SaaS como SavvyCal e Riverside.

**O que cobre:** CRO (otimização de conversão), copywriting, SEO, analytics e growth engineering. A skill `product-marketing` é a base: todas as outras leem ela primeiro pra entender seu produto, público e posicionamento antes de sugerir qualquer coisa.

**Instalar:**

:::bloco
terminal⟦botão: Copiar⟧

```
npx skills add coreyhaines31/marketingskills
```
:::fim

**Nota de transparência:** é gratuita e MIT, mas o projeto tem parceiros pagos declarados no próprio repositório (ferramentas de rastreamento e SEO) que financiam a manutenção, sem influenciar o que as skills recomendam. O README também linka os produtos pagos do próprio Corey (agência, treinamento). Normal pra projeto open source mantido por um criador; fica registrado aqui pra você saber.

**Link:** [github.com/coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)

## 02. claude-skills (marketing-skill) · Alireza Rezvani

**25.748 estrelas no GitHub.** O catálogo mais completo: 388 skills no total, cobrindo engenharia, produto, compliance e mais, com uma pasta `marketing-skill/` só de marketing dentro.

**Quem fez:** Alireza Rezvani.

**O que cobre:** 43 skills de marketing, incluindo ad-creative, cold-email, competitor-alternatives, campaign-analytics, app-store-optimization e AEO (otimização pra aparecer quando alguém pergunta pra uma IA, não só pro Google). Vem com 706 ferramentas de linha de comando além da instrução em texto.

**Instalar:**

:::bloco
terminal⟦botão: Copiar⟧

```
git clone https://github.com/alirezarezvani/claude-skills.git
# copie a pasta da skill que quiser pra ~/.claude/skills/
```
:::fim

**Link:** [github.com/alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)


## 03. claude-ads · Daniel Agrici

**9.091 estrelas no GitHub.** Foco único: mídia paga.

**Quem fez:** Daniel Agrici.

**O que cobre:** auditoria de conta de anúncio em 12 plataformas (Google, Meta, TikTok, LinkedIn, YouTube, Microsoft, Amazon, entre outras), plano de campanha, briefing de criativo, monitoramento de fadiga e de política.

Roda em modo leitura por padrão: mudança real na conta só acontece depois de aprovação explícita sua.

**Quando usar:** se seu trabalho é gerenciar tráfego pago pra cliente, e você precisa de auditoria confiável, não de mais uma ferramenta que só "sugere melhorar o CTR".

**Instalar** (dentro do Claude Code):

:::bloco
claude code⟦botão: Copiar⟧

```
/plugin marketplace add AgriciDaniel/claude-ads
/plugin install claude-ads@ai-marketing-hub-claude-ads
```
:::fim

**Link:** [github.com/AgriciDaniel/claude-ads](https://github.com/AgriciDaniel/claude-ads)

## 04. claude-skills (Brand Build Skills) · RampStack

**832 estrelas no GitHub.** A menor das 4 em número, mas cobre o que as outras não cobrem: o site e a marca inteiros, não só o conteúdo.

**Quem fez:** time da RampStack. Catalogada de forma independente na lista `ComposioHQ/awesome-claude-skills`, categoria "Business & Marketing".

**O que cobre:** 103 skills cobrindo marca, design, conteúdo, SEO, desenvolvimento, operação, crescimento e pesquisa. Inclui um pacote de auditoria de SEO com dados reais (via integração com Ahrefs). Funciona em Next.js, WordPress, Shopify, Webflow ou HTML puro.

**Quando usar:** se você constrói ou mantém o site e a identidade da marca, não só o que se posta.

**Instalar** (dentro do Claude Code):

:::bloco
claude code⟦botão: Copiar⟧

```
/plugin marketplace add rampstackco/claude-skills
/plugin install rampstack-skills@rampstack
```
:::fim

**Link:** [github.com/rampstackco/claude-skills](https://github.com/rampstackco/claude-skills)

## Antes de Instalar Qualquer Uma

- Leia o SKILL.md da pasta antes de instalar. É texto simples, dá pra entender em um minuto o que ela realmente faz.
- Nenhuma dessas skills muda conta, publica post ou gasta dinheiro sozinha sem você aprovar. Se algum dia uma pedir isso, desconfie antes de aceitar.
- Comece por uma só. Instalar as 4 de uma vez e não usar nenhuma é pior do que instalar uma e testar de verdade.
- São mantidas por gente de fora da Anthropic. Todas open source (licença MIT), então você pode abrir o código e ler antes de confiar.

---

## POST 26 — O prompt que encontra uma oferta nas suas conversas

- URL: `/blog/achar-oferta`
- Template: padrão (hero + artigo 720px)
- Categoria: VENDAS & IA
- Data no card: 9 Set 2026 | Data na página: 9 de setembro de 2026
- Tempo de leitura: 10 min (página: "10 min de leitura")
- Resumo do card: O prompt que agrupa as perguntas reais dos seus clientes por dor, o filtro de 3 critérios que separa oferta de curiosidade, e o prompt que monta a oferta nas 8 partes que faltam pra ela vender.
- Meta description: O prompt que agrupa as perguntas reais dos seus clientes por dor, o filtro de 3 critérios que separa oferta de curiosidade, e o prompt que monta a oferta nas 8 partes que faltam pra ela vender.
- Título da aba: O Prompt que Encontra uma Oferta nas Suas Conversas | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Como Usar · 02Prompt 1 — Agrupar · 03O Filtro de 3 Critérios · 04Prompt 2 — Montar a Oferta · 05O Modelo das 8 Partes · 06O Que Eu Aprendi Montando a Minha · 07O Próximo Passo

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar OFERTA, prometido no carrossel "Como usar o Claude pra transformar dúvidas em uma oferta". Três peças: o prompt de agrupamento, o filtro de 3 critérios e o modelo das 8 partes da oferta.

Foi assim que a FORJA nasceu: uns 200 responderam "time" num story perguntando como eu faço conteúdo com o Claude. A pergunta era sempre a mesma. Virou produto, com nome.

## Como Usar

1. 1.**Coletar (30 minutos).** WhatsApp: abra a conversa, menu, "exportar conversa", sem mídia. Faça isso nas 10 a 20 conversas mais recentes de cliente ou lead. Direct do Instagram: copie as perguntas dos últimos 90 dias. Comentários: idem. E-mails de "vocês fazem...?". Junte tudo num arquivo de texto. Menos de 50 perguntas dá padrão fraco.
2. 2.**Agrupar.** Cole o arquivo no prompt 1. Ele devolve os grupos, contados.
3. 3.**Filtrar.** Passe cada grupo pelos 3 critérios. Dois de três vira teste; três vira oferta.
4. 4.**Montar.** Pegue o grupo vencedor e rode o prompt 2. Ele monta as 8 partes.
5. 5.**Testar.** Responda a pergunta original de um cliente com a oferta pronta. Se ele entende em 10 segundos, está boa.

## Prompt 1 · Agrupar (Copie Daqui pra Baixo)

:::bloco
prompt 1 — agrupar perguntas⟦botão: Copiar⟧

```
Abaixo estão perguntas reais que clientes e leads me fizeram (WhatsApp, direct, e-mail).
Sua tarefa é encontrar padrões. Regras:

- Agrupe pelo PROBLEMA por trás da pergunta, e não pela palavra usada. "Quanto custa um
  site" e "vocês fazem loja virtual" podem ser o mesmo problema (vender online) ou não;
  decida pelo que a pessoa quer resolver.
- Conte quantas perguntas caem em cada grupo. Ordene do maior pro menor.
- Pra cada grupo, responda:
  1. A dor, nas palavras das próprias pessoas (cite 2 ou 3 perguntas originais).
  2. O que elas dizem que já tentaram, se disserem.
  3. Sinais de disposição a pagar: pediu preço, comparou com outro fornecedor, disse
     "quanto custa", já gasta com isso hoje.
  4. O que elas parecem querer receber (o entregável que imaginam).
- Não invente grupo pra ficar bonito. Se 70% cai num grupo só, diga isso.
- No fim, liste as perguntas que ficaram fora de qualquer grupo.

FORMATO
GRUPO 1 · [nome curto do problema] · [N] perguntas ([%])
- Dor: ...
- Já tentaram: ...
- Sinais de pagar: ...
- Querem receber: ...
GRUPO 2 · ...
FORA DE GRUPO
- ...

PERGUNTAS
[cole aqui, uma por linha, sem limpar]
```
:::fim

## O Filtro de 3 Critérios

| Critério | A Pergunta | Passa Se |
| --- | --- | --- |
| `Repete` | Quantas vezes aparece? | 10% ou mais de todas as perguntas |
| `Dói` | Custa tempo ou dinheiro toda semana? | a pessoa descreve perda, atraso, retrabalho, cliente perdido |
| `Paga` | Ela já gasta com isso, ou já pediu preço? | tem sinal de pagar no grupo (preço, comparação, gasto atual) |

- →**3 de 3:** monta a oferta.
- →**2 de 3:** vira teste. Escreva a promessa em uma linha e ofereça pra 5 pessoas que fizeram a pergunta. Duas topam, monta.
- →**1 de 3:** é conteúdo, e não oferta. Responde num post e segue.

Cuidado com o grupo que só "repete": pergunta muito repetida e sem dor costuma ser dúvida de curioso. Curioso pergunta muito e compra pouco.


## Prompt 2 · Montar a Oferta (Rode com o Grupo Vencedor)

:::bloco
prompt 2 — montar a oferta⟦botão: Copiar⟧

```
Vou te dar um grupo de perguntas reais de clientes com a dor por trás delas, e o que eu
faço hoje pra resolver isso. Monte uma OFERTA nas 8 partes abaixo, nesta ordem. Regras:
transformação antes do entregável; promessa verificável (dá pra olhar depois e dizer
"aconteceu" ou "não aconteceu"); nada de garantia, escassez inventada ou número que eu
não te dei. O que você não souber, marque [CONFIRME].

O GRUPO
[cole o grupo vencedor do prompt 1]

O QUE EU FAÇO HOJE PRA RESOLVER ISSO
[como você entrega, quanto tempo leva, o que a pessoa recebe, quanto já cobrou se cobrou]

AS 8 PARTES
1. Nome: curto, dizível, com o resultado ou o recorte dentro. Nada de "premium", "360".
2. Promessa (uma linha): o que a pessoa repetiria pro sócio. Verificável.
3. Transformação: duas cenas, antes e depois. Cena, e não adjetivo.
4. O que inclui: 3 a 6 itens, cada um com quantidade ou prazo quando existir.
5. Pra quem é: uma situação que a pessoa reconhece em 2 segundos.
6. Pra quem não é: um recorte honesto, com o motivo.
7. Por que agora: o custo de continuar como está. Sem "últimas vagas".
8. Preço e formato: faixa e como acontece (online/presencial, duração, ritmo). Se eu não
   te dei preço, escreva "a confirmar".

Depois das 8 partes, aplique o teste final e responda sim ou não pra cada:
- um estranho entende o que é em 10 segundos?
- a promessa é verificável?
- o "o que inclui" sustenta a promessa?
- alguém consegue se ver fora dela?
- tem número ou prova que eu não confirmei? (se sim, liste)
```
:::fim

## O Modelo das 8 Partes (pra Preencher na Mão)

:::bloco
modelo — 8 partes da oferta⟦botão: Copiar⟧

```
NOME: ______________________________
PROMESSA: __________________________________________________ (verificável)
TRANSFORMAÇÃO
  antes: ____________________________________ (cena)
  depois: ___________________________________ (cena)
O QUE INCLUI (3 a 6)
  1. __________________ (quantidade/prazo)
  2. __________________
  3. __________________
PRA QUEM É: ______________________________________
PRA QUEM NÃO É: ______________________________ · porque: ______________
POR QUE AGORA: ______________________________________ (custo de continuar)
PREÇO E FORMATO: ____________________ · ____________________
```
:::fim

## O Que Eu Aprendi Montando a Minha

**A pergunta certa raramente é a mais frequente.** A mais frequente costuma ser preço. A que vira oferta é a segunda ou terceira, a que descreve uma dor.

**Nome vem por último.** Quem começa pelo nome monta uma oferta pra caber no nome.

Pra quem não é é a parte que mais aumenta a conversão de quem fica, e a que todo mundo pula por medo de perder cliente.

## O Próximo Passo

Rode o prompt 1 hoje com o que você tem, mesmo que sejam 30 perguntas. Me responde com o nome do GRUPO 1 e o percentual dele. Se for preço, a gente conversa sobre o grupo 2.

---

## POST 27 — 4 prompts para montar agentes no ChatGPT

- URL: `/blog/agentes-chatgpt`
- Template: padrão (hero + artigo 720px)
- Categoria: CHATGPT & AUTOMAÇÃO
- Data no card: 8 Set 2026 | Data na página: 8 de setembro de 2026
- Tempo de leitura: 9 min (página: "9 min de leitura")
- Resumo do card: Os 4 prompts completos para montar agentes de verdade no ChatGPT — entrada de leads, operação do dia, cobranças e conteúdo — cada um com limite, formato de saída e a mensagem de início pronta.
- Meta description: Os 4 prompts completos para montar agentes de verdade no ChatGPT — entrada de leads, operação do dia, cobranças e conteúdo — cada um com limite, formato de saída e a mensagem de início pronta.
- Título da aba: 4 Prompts para Montar Agentes no ChatGPT | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Como Usar · 021. Agente de Entrada · 032. Agente de Operação · 043. Agente Financeiro · 054. Agente de Conteúdo · 06Antes de Considerar o Agente Pronto

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar PROMPTS.

Um agente não é um chat que responde tudo. É uma função com um trabalho, um formato de saída e um limite escrito. Os quatro abaixo cobrem as quatro frentes que mais travam uma operação pequena: quem entra, o que fazer hoje, o que vence e o que virar conteúdo.

## Como Usar

Crie **quatro Projetos** no ChatGPT, um para cada função. Em cada Projeto, abra as configurações, cole o prompt em Instruções do projeto e suba os arquivos que aquele agente precisa consultar. Depois use a mensagem de início sugerida.

Esses agentes funcionam dentro do ChatGPT. Eles organizam contexto, produzem saídas e preparam decisões. Não enviam mensagem, não alteram cobrança e não leem o seu CRM sozinhos, sem uma integração externa.

Comece pela função que mais trava hoje, não pela primeira da lista.

:::bloco
## 1. Agente de Entrada

:::bloco
prompt — agente de entrada⟦botão: Copiar⟧

```
Você é meu Agente de Entrada. Sua função é transformar cada novo lead em uma conversa clara e em um próximo passo registrado.

Quando eu enviar uma mensagem, formulário ou resumo de contato:
1. Identifique nome, empresa, necessidade, urgência e origem quando esses dados existirem.
2. Classifique a conversa em: novo lead, dúvida, proposta, negociação, suporte ou fora de escopo.
3. Escreva uma resposta inicial curta, humana e objetiva. Use apenas informações que eu forneci.
4. Termine com um próximo passo claro e com os campos que devo registrar no CRM.

Limites: nunca invente preço, prazo, condição comercial, case ou disponibilidade. Se faltar uma informação que muda a resposta, faça uma pergunta antes de responder.

Formato de saída:
CLASSIFICAÇÃO
RESPOSTA SUGERIDA
PRÓXIMO PASSO
REGISTRO NO CRM
RISCO OU PENDÊNCIA
```
:::fim

**Mensagem de início:** `Novo lead. A mensagem foi: [cole aqui]`
:::fim

:::bloco
:::bloco
## 2. Agente de Operação

:::bloco
prompt — agente de operação⟦botão: Copiar⟧

```
Você é meu Agente de Operação. Sua função é transformar tarefas, prazos, conversas e projetos espalhados em uma lista de trabalho que eu consigo executar hoje.

Quando eu enviar tarefas, mensagens, prazos ou notas de projeto:
1. Separe o que está atrasado, o que bloqueia uma entrega e o que pode esperar.
2. Monte uma lista de no máximo 5 prioridades para hoje, em ordem de impacto e prazo.
3. Para cada prioridade, defina a próxima ação concreta, o responsável e a informação que está faltando.
4. Crie um resumo por cliente ou projeto quando houver mais de uma frente.

Limites: nunca mude prazo, escopo ou compromisso com cliente por conta própria. Sinalize a decisão que depende de mim.

Formato de saída:
PRIORIDADE DE HOJE
BLOQUEIOS
PRÓXIMA AÇÃO POR PROJETO
DECISÕES QUE PRECISAM DE APROVAÇÃO
```
:::fim

**Mensagem de início:** `Minha operação hoje está assim: [cole tarefas, prazos e mensagens]`
:::fim

:::fim

:::bloco
## 3. Agente Financeiro

:::bloco
prompt — agente financeiro⟦botão: Copiar⟧

```
Você é meu Agente Financeiro. Sua função é organizar cobranças e me mostrar o que exige ação antes de virar problema.

Quando eu enviar uma lista de cobranças, vencimentos ou pagamentos:
1. Separe em: vence hoje, vence nos próximos 7 dias, atrasado, pago e precisa confirmar.
2. Destaque clientes, valores e datas que precisam da minha atenção.
3. Escreva um rascunho de lembrete respeitoso para cada cobrança atrasada ou próxima do vencimento.
4. Diga qual ação eu devo tomar primeiro e por quê.

Limites: nunca negocie dívida, altere valor, confirme pagamento ou prometa condição sem minha aprovação.

Formato de saída:
ALERTA FINANCEIRO
COBRANÇAS POR PRIORIDADE
MENSAGENS SUGERIDAS
AÇÃO DE HOJE
```
:::fim

**Mensagem de início:** `Estas são minhas cobranças: [cole aqui]`
:::fim

:::bloco
## 4. Agente de Conteúdo

:::bloco
prompt — agente de conteúdo⟦botão: Copiar⟧

```
Você é meu Agente de Conteúdo. Sua função é transformar minhas dores reais de operação em posts úteis, específicos e prontos para revisão.

Quando eu enviar um problema, uma conversa, um processo ou um aprendizado:
1. Encontre o gargalo operacional por trás do assunto.
2. Proponha 3 hooks que nomeiem a ferramenta ou o mecanismo junto do resultado.
3. Escolha o melhor hook e monte um roteiro de carrossel com capa, quebra, prova prática, fechamento e CTA.
4. Mostre qual material concreto eu preciso ter pronto antes de prometer algo no CTA.

Limites: não invente números, resultados, cases ou funcionalidades. Não use frase de efeito vazia. Todo conteúdo precisa ensinar um mecanismo que alguém consiga aplicar.

Formato de saída:
GARGALO
3 HOOKS
ROTEIRO
MATERIAL DO CTA
FATO QUE PRECISO CONFIRMAR
```
:::fim

**Mensagem de início:** `Quero transformar isso em conteúdo: [cole aqui]`
:::fim

## Antes de Considerar o Agente Pronto

- Testei com uma situação real, não com um exemplo inventado.
- O formato de saída veio exatamente como especificado, nas seções certas.
- Ele respeitou o limite: não inventou preço, prazo, valor ou dado que eu não dei.
- Sei qual arquivo subir no Projeto pra ele ter contexto de verdade.

Um agente por função, uma saída clara. Se ele tentar fazer as quatro coisas ao mesmo tempo, separe de novo: essa é a regra que sustenta as duas outras.

---

## POST 28 — O prompt do diretor de operação

- URL: `/blog/diretor-operacao`
- Template: padrão (hero + artigo 720px)
- Categoria: OPERAÇÕES & IA
- Data no card: 7 Set 2026 | Data na página: 7 de setembro de 2026
- Tempo de leitura: 8 min (página: "8 min de leitura")
- Resumo do card: O prompt completo que transforma a lista bruta do seu dia em três colunas — Fazer, Aguardar, Delegar — com a régua de 4 níveis de prioridade e o modelo pronto da lista do dia.
- Meta description: O prompt completo que transforma a lista bruta do seu dia em três colunas — Fazer, Aguardar, Delegar — com a régua de 4 níveis de prioridade e o modelo pronto da lista do dia.
- Título da aba: O Prompt do Diretor de Operação | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Como Usar (5 Minutos por Dia) · 02O Prompt · 03A Régua de 4 Níveis · 04O Modelo da Lista do Dia · 05Erros que Eu Já Cometi · 06O Próximo Passo

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar HOJE, prometido no carrossel "Como usar o Claude pra saber o que fazer hoje". Três peças: o prompt completo, a régua de 4 níveis e o modelo da lista do dia.

Eu rodo isso todo dia. No meu caso a lista bruta chega por um comando do meu CRM (`crm_hoje`, que junta tarefas abertas, cobranças vencendo e follow-ups de lead). Pra você, colar a lista na mão funciona igual: o que decide a qualidade é a régua, e ela é a mesma.

## Como Usar (5 Minutos por Dia)

1. 1.Antes de abrir e-mail ou WhatsApp, junte tudo que está aberto: tarefas, prazos, mensagens que você deve resposta, cobranças vencendo, pedidos de cliente que ficaram no ar.
2. 2.Cole no lugar marcado do prompt. Sem ordenar, sem limpar, sem julgar. Bruto.
3. 3.Cole o prompt inteiro no Claude (chat ou Claude Code). Se você tem um arquivo de contexto da empresa (CLAUDE.md ou Projeto), a régua e o desempate podem morar lá, e aí o prompt fica só com a lista.
4. 4.Leia a coluna FAZER de cima pra baixo. O primeiro item é o seu dia.
5. 5.Toda noite, o que sobrou volta pra lista bruta de amanhã.

## O Prompt (Copie Daqui pra Baixo)

:::bloco
prompt — diretor de operação⟦botão: Copiar⟧

```
Você é o diretor de operação da minha empresa. Sua função é ler tudo que está aberto
hoje e devolver a lista do dia, em três colunas. Você não executa nada e não decide
por mim: você separa e ordena.

CONTEXTO DA EMPRESA
- O que fazemos: [uma frase. Ex: implantação de agentes de IA pra empresas pequenas]
- Quem trabalha aqui: [ex: só eu / eu + 1 freela de design]
- O que a IA ou uma rotina já faz sozinha: [ex: follow-up de lead, cobrança, resumo de reunião]

RÉGUA DE PRIORIDADE (use exatamente esta, nunca a sua)
- URGENTE: algo quebrado, ou que bloqueia outra pessoa de trabalhar, ou cliente parado
  esperando resposta há mais de 1 dia.
- ALTA: cliente esperando, ou prazo nesta semana, ou dinheiro parado (cobrança vencida).
- MÉDIA: o padrão. Tem que ser feito, sem prazo apertado.
- BAIXA: melhoria, ideia, "seria bom".

DESEMPATE (quando duas coisas competem no mesmo nível)
1. Prazo e entrega de cliente vencem tudo.
2. Depois, o que destrava o meu dia (o que outras coisas dependem).
3. Depois, dinheiro (cobrar, faturar, renovar).

REGRAS DAS COLUNAS
- FAZER: só o que depende de mim e cabe hoje. Máximo de [6] itens, na ordem da régua.
  Se passar de [6], o excedente vai pra "amanhã", em ordem.
- AGUARDAR: o que está travado por outra pessoa (cliente, fornecedor, aprovação).
  Todo item tem: quem eu estou esperando + data em que eu cobro se não vier.
  Aguardar sem data de cobrança volta pra FAZER como "cobrar X".
- DELEGAR: o que é repetitivo, ou não precisa de mim, ou já tem rotina/IA pra isso.
  Todo item tem: pra quem ou pra qual rotina + o que eu preciso entregar pra delegar.
  Delegar sem dono volta pra FAZER.

O QUE VOCÊ NÃO FAZ
- Não inventa prazo. Se um item não tem data e parece ter prazo, pergunte no fim.
- Não junta itens diferentes numa linha só.
- Não reescreve o título do item: mantenha o meu texto, só adicione a etiqueta.

FORMATO DA RESPOSTA
FAZER (hoje, nesta ordem)
1. [URGENTE] título · por que é urgente em 5 palavras
2. [ALTA] ...
AGUARDAR
- título · esperando: quem · cobro em: data
DELEGAR
- título · pra: quem ou rotina · eu entrego: o quê
AMANHÃ
- ...
PERGUNTAS (só se precisar)
- ...

TUDO QUE ESTÁ ABERTO HOJE
[cole aqui a lista bruta]
```
:::fim


## A Régua de 4 Níveis (pra Imprimir)

| Nível | Critério que decide | Exemplo |
| --- | --- | --- |
| `URGENTE` | quebrado, ou bloqueia alguém, ou cliente parado há mais de 1 dia | site fora do ar; cliente sem resposta desde ontem |
| `ALTA` | cliente esperando, prazo nesta semana, ou dinheiro parado | entrega de sexta; boleto vencido |
| `MÉDIA` | tem que ser feito, sem prazo apertado | atualizar proposta padrão |
| `BAIXA` | melhoria, ideia, "seria bom" | trocar o template do e-mail |

A régua serve pra uma coisa: quando você discorda do Claude, você discorda de um critério, e não de uma opinião. Aí você ajusta o critério, e amanhã ele acerta.

## O Modelo da Lista do Dia

:::bloco
modelo — lista do dia⟦botão: Copiar⟧

```
LISTA DO DIA · [data]

FAZER (só eu, hoje)
1. [URGENTE] ______________________ · por quê: ____________
2. [ALTA]    ______________________ · por quê: ____________
3. [ALTA]    ______________________
4. [MÉDIA]   ______________________
5. [MÉDIA]   ______________________
6. [BAIXA]   ______________________

AGUARDAR (travado por outro)
- ______________________ · esperando: ________ · cobro em: __/__
- ______________________ · esperando: ________ · cobro em: __/__

DELEGAR (não precisa de mim)
- ______________________ · pra: ________ · eu entrego: ________
- ______________________ · pra: ________ · eu entrego: ________

AMANHÃ
- ______________________
```
:::fim

## Erros que Eu Já Cometi

**Colar a lista já ordenada.** Aí o Claude respeita a minha ordem, que era a ordem do meu medo. Cole bruto.

**Régua na cabeça.** Sem a régua escrita, ele classifica pelo tom: "URGENTE!!!" no título vira urgente mesmo quando é uma melhoria.

**Aguardar virar cemitério.** Item em AGUARDAR sem data de cobrança nunca mais aparece. Por isso a regra: sem data, volta pra FAZER como "cobrar".

**Delegar pra ninguém.** "Delegar" sem dono é só uma tarefa que você adiou com nome bonito.

## O Próximo Passo

Se a lista bruta for grande demais pra colar todo dia, o problema mudou: você precisa de um lugar onde as tarefas moram (planilha, ClickUp, um CRM), e o Claude lendo de lá. No meu caso é um comando. Me responde contando de onde a sua lista vem hoje (cabeça, caderno, planilha, sistema) que eu te digo qual é o passo seguinte.

---

## POST 29 — A máquina de demanda: como transformar conteúdo em leads todos os dias usando IA

- URL: `/blog/maquina-demanda`
- Template: padrão (hero + artigo 720px)
- Categoria: GERAÇÃO DE LEADS & IA
- Data no card: 4 Set 2026 | Data na página: 4 de setembro de 2026
- Tempo de leitura: 10 min (página: "10 min de leitura")
- Resumo do card: As 3 peças que transformam conteúdo em lead todos os dias: análise de conteúdo com Windsor + Claude, captura com CTA de palavra-chave, e um blog próprio que entrega, coleta e aparece no Google.
- Meta description: As 3 peças que transformam conteúdo em lead todos os dias: análise de conteúdo com Windsor + Claude, captura com CTA de palavra-chave, e um blog próprio que entrega, coleta e aparece no Google.
- Título da aba: A Máquina de Demanda: Como Transformar Conteúdo em Leads Todos os Dias Usando IA | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Passo 1 — Conteúdo que Converte · 02Passo 2 — Captura · 03Passo 3 — O Blog · 04O Erro que Trava Tudo · 05Por Onde Começar

### Corpo do post (conteúdo exato, na ordem da página)

A maioria das pessoas que posta todo dia não gera lead nenhum. Não é falta de constância e não é o algoritmo. É que o conteúdo não tem destino: a pessoa assiste, acha bom, segue, e vai embora. Não existe um lugar para onde ela possa ir, nem um motivo para ela deixar o contato.

Máquina de demanda é o contrário disso. São três peças encaixadas, e cada uma só funciona porque a outra existe:

1. 1.**Conteúdo que converte**, criado a partir dos seus próprios números, não do seu achismo.
2. 2.**Captura**, que é entregar algo de verdade em toda peça e pegar o contato de quem pediu.
3. 3.**Blog**, que é o destino: entrega o material, coleta o dado, aparece no Google e leva a pessoa para o próximo passo.

Vou detalhar as três.

## Passo 1 · Conteúdo que Converte: Analise Antes de Criar

O erro clássico é abrir o Claude e pedir "me dá 30 ideias de post". Ele devolve trinta ideias genéricas, porque você não deu nada sobre o que já funcionou no seu perfil. Ele não tem como saber.

A virada é conectar seus números ao Claude antes de pedir qualquer coisa. Aí a conversa deixa de ser sobre conteúdo em geral e passa a ser sobre o seu conteúdo.

### Como Conectar o Windsor ao Claude

O Windsor.ai é uma ponte: ele lê os dados das suas contas (Instagram, entre várias outras) e entrega para o Claude através de um servidor MCP, que é o formato padrão que o Claude usa para se conectar a ferramentas externas.

1. 1.Crie uma conta gratuita no windsor.ai.
2. 2.Conecte o seu Instagram por lá. A autorização é por link, no padrão OAuth. Você não digita senha em lugar nenhum, e não cola token em conversa.
3. 3.Adicione o servidor MCP oficial do Windsor no Claude (`mcp.windsor.ai`). No Claude Code isso é uma linha no `.mcp.json` do projeto. No aplicativo, é em conectores.
4. 4.Autorize quando o Claude pedir. Pronto: ele passa a enxergar seus posts, alcance, salvamentos, compartilhamentos e crescimento de seguidores.

### O Que Pedir Depois de Conectar

Conectar sem perguntar direito não resolve. O que muda o resultado é obrigar o Claude a concluir a partir dos dados, não a opinar:

:::bloco
prompt — análise dos últimos 90 dias⟦botão: Copiar⟧

```
Você é meu analista de conteúdo. Puxe meus últimos 90 dias de posts do Instagram pelo Windsor e me devolva:

1. Os 10 posts com maior alcance e os 10 com mais salvamentos, em listas separadas.
2. O que os melhores têm em comum: formato, tema, tipo de gancho, e se tinham ou não CTA de comentário.
3. O que os piores têm em comum.
4. Três temas que eu deveria repetir e três que eu deveria parar de postar.

Não me dê conselho genérico de rede social. Toda conclusão precisa citar os posts que a sustentam.
```
:::fim

A última linha é a mais importante. Sem ela o Claude escorrega para o conselho de coach. Com ela, ele é obrigado a apontar o post.

### Olhe Salvamento, Não Curtida

Curtida é reflexo. Salvamento e compartilhamento são as pessoas dizendo "isso aqui me serve para alguma coisa". Quando você descobre qual formato seu gera salvamento, você para de adivinhar e passa a repetir de propósito.

É esse sinal que se converte em lead depois, porque é ele que indica utilidade.

## Passo 2 · Captura: Toda Peça Entrega Alguma Coisa

A regra é simples: nenhum post sai sem uma entrega. Um mapa, um prompt, um checklist, uma planilha, uma análise. Alguma coisa que a pessoa consiga usar sozinha, hoje.

Isso muda o comportamento do conteúdo. Sem entrega, o melhor que pode acontecer é um "muito bom". Com entrega, acontece um pedido, e pedido é contato.

### Como Funciona na Prática

O CTA é uma palavra-chave única, curta e fácil de digitar. "Comenta DEMANDA e eu te mando." Quem comenta, recebe. Nada de "manda um oi no direct", que dá trabalho e não deixa rastro.

Três cuidados que fazem diferença:

- →O material precisa existir antes de você prometer. Prometer e demorar três dias para montar queima mais reputação do que não ter prometido.
- →Uma palavra por campanha. Duas confundem e você perde a conta de quem pediu o quê.
- →Responda rápido. O interesse tem prazo de validade curto, medido em horas.

### O Que Coletar, e o Campo que Vale Ouro

Na hora de entregar, peça o mínimo que justifique a entrega: nome, email, whatsapp e nicho. E acrescente um campo aberto:

"O que você mais quer automatizar hoje?"

Esse campo é pesquisa de mercado de graça, escrita com as palavras do seu próprio público. Depois de cem respostas você para de inventar pauta: seus próximos temas, suas próximas ofertas e até o texto do seu site saem de lá. **É o campo que mais me deu retorno, e é o que quase ninguém coloca.**

### Automatizar: ManyChat ou Sistema Próprio

As duas funcionam. A diferença é o que você ganha e o que abre mão.

**ManyChat (ou ferramenta parecida):** você monta em uma tarde, sem programar. A ferramenta lê o comentário, manda a mensagem e coleta o dado. Paga mensalidade e o dado mora lá dentro.

**Sistema próprio:** o formulário manda para um webhook, o webhook grava no seu banco, e o dado é seu. Dá mais trabalho para montar e some a mensalidade. É o que eu uso, porque o lead entra direto no meu CRM e a IA já continua a conversa dali.

Comece pelo primeiro se você ainda não validou a oferta. Migre para o segundo quando o volume justificar.


## Passo 3 · O Blog: a Peça que Sustenta as Outras Duas

Essa é a parte que quase ninguém monta, e é a mais importante das três.

Comentário e direct são alugados. A rede muda a regra, o alcance cai, a conta trava, e você perde o canal inteiro de uma vez. O blog é seu.

E ele faz quatro trabalhos ao mesmo tempo:

- →**Entrega o material.** Em vez de mandar um PDF que a pessoa nunca abre, você manda um link. Ela lê na hora, no celular.
- →**Coleta o dado.** O formulário fica na própria página, no meio do conteúdo que ela já quis ler.
- →**Aparece no Google.** O post do Instagram morre em 48 horas. O texto do blog trabalha por meses e traz gente que nunca te viu.
- →**Leva para o próximo passo.** No fim de cada post você aponta para outro material, para um diagnóstico ou para o seu serviço. É o único lugar onde essa sequência acontece com calma.

### Como Criar o Seu Blog Usando o Claude

Você não precisa saber programar. Precisa saber pedir e aprovar.

1. 1.Peça a estrutura, não o site inteiro. Comece com uma página inicial, uma página `/blog` que lista os textos, e um post de exemplo. É o suficiente para você ver de pé.
2. 2.Padronize o formato do post. Título, texto, e um formulário no meio. Quando o formato está travado, cada post novo é só o texto: o Claude monta a página igual à anterior.
3. 3.Ligue o formulário no seu destino. Ele manda os campos para um webhook, uma planilha ou um banco. Esse é o ponto que transforma leitura em lead, e é o passo que as pessoas esquecem.
4. 4.Publique. Vercel resolve, é gratuito para começar e sobe em minutos.
5. 5.Escreva um post por material. Cada campanha de conteúdo ganha o seu. O post é a entrega e a captura no mesmo lugar.

Do segundo post em diante o trabalho é só escrever. A máquina já está montada.

## O Erro que Trava Tudo

**Postar sem destino.**

Dá para ter conteúdo bom, constância e até alcance, e mesmo assim não gerar lead nenhum, porque não existe para onde a pessoa ir. Conteúdo sem captura é entretenimento. Captura sem destino é uma promessa que você vai cumprir na mão, até cansar.

As três peças juntas é que viram máquina. Separadas, são só trabalho.

## Por Onde Começar

Não monte as três de uma vez. Nessa ordem:

1. 1.Conecte o Windsor ao Claude e rode a análise dos seus 90 dias. Leva uma tarde e já muda o que você posta na semana seguinte.
2. 2.Escolha um material que você consegue entregar hoje e coloque uma palavra-chave no próximo post. Entregue na mão nas primeiras vezes, de propósito: é assim que você descobre o que a pessoa pergunta.
3. 3.Só depois monte o blog e automatize a entrega.

Quem faz na ordem inversa monta a automação antes de saber o que entregar, e automatiza a entrega de algo que ninguém pediu.

---

## POST 30 — Os 10 prompts para montar seus agentes de WhatsApp no Claude

- URL: `/blog/10-agentes`
- Template: padrão (hero + artigo 720px)
- Categoria: WHATSAPP & IA
- Data no card: 2 Set 2026 | Data na página: 2 de setembro de 2026
- Tempo de leitura: 17 min (página: "17 min de leitura")
- Resumo do card: Os 10 prompts completos para montar cada agente de WhatsApp no Claude, mais as 3 rotas para conectar de verdade (na mão, no-code, código) e a regra das 24 horas que decide se 4 dos 10 agentes funcionam.
- Meta description: Os 10 prompts completos para montar cada agente de WhatsApp no Claude, mais as 3 rotas para conectar de verdade (na mão, no-code, código) e a regra das 24 horas que decide se 4 dos 10 agentes funcionam.
- Título da aba: Os 10 Prompts para Montar Seus Agentes de WhatsApp no Claude | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Como Usar · 0201. Recepção · 0302. Qualificação · 0403. Agendamento · 0504. Catálogo e Dúvidas · 0605. Follow-up · 0706. Reativação · 0807. Suporte · 0908. Status · 1009. Cobrança · 1110. Pós-venda · 12Onde o Prompt Vira Agente de Verdade · 13O Checklist Antes de Ligar Qualquer Um · 14O Que Fazer Quando Ele Errar

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar AGENTES.

Antes dos prompts, o campo que quase todo mundo pula: o **limite**.

Um agente que não sabe parar não é um agente incompleto. É um problema comercial rodando sozinho no seu WhatsApp, 24 horas por dia, prometendo prazo que você não tem e desconto que você não deu.

Por isso cada um dos dez prompts abaixo tem uma linha de "não pode" e uma linha de "chama uma pessoa quando". Não apague essas duas linhas. Elas são a diferença entre um agente e um passivo.

## Como Usar

1. 1.Escolha um agente. O que mais toma o seu tempo hoje, não o número 01.
2. 2.Cole o prompt no Claude e troque só o que está entre colchetes.
3. 3.Rode o teste que vem no fim de cada bloco, na mão, antes de conectar em qualquer número.
4. 4.Só depois passe para o próximo.

Dez agentes montados às pressas dão mais trabalho do que um agente montado direito.

**Antes de escolher o seu agente:** o prompt configura o cérebro, não conecta nada. O Claude não fala com o WhatsApp sozinho. A seção ⟦botão: Onde o prompt vira agente de verdade⟧, no fim deste material, mostra as três rotas para montar a ponte que falta, e a regra do WhatsApp que decide se quatro dos dez vão funcionar. Vale ler antes.

:::bloco
## 01. Recepção

:::bloco
prompt — agente de recepção⟦botão: Copiar⟧

```
Você é o agente de recepção do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: identificar em qual motivo o contato se encaixa e escrever a primeira
resposta. Motivos possíveis: [LISTE DE 4 A 6, por exemplo: orçamento, suporte,
status de pedido, parceria, trabalhe conosco, outro].
Gatilho: primeira mensagem de um número que ainda não tem conversa aberta.
Pode consultar: só a lista de motivos acima e [ONDE ESTÁ A SUA APRESENTAÇÃO].
Não pode: falar preço, prazo, condição comercial ou disponibilidade.
Chama uma pessoa quando: o contato não encaixa em nenhum motivo, ou já chega
com urgência declarada.
Saída esperada: resposta de no máximo 3 linhas que confirma o que entendeu e faz
UMA pergunta de direcionamento, mais a etiqueta do motivo identificado.

Escreva a instrução principal, a abertura de cada motivo, a resposta padrão para
motivo não identificado, e 5 exemplos de mensagem real de cliente já
classificados. Não invente informação que não esteja na lista acima.
```
:::fim

**O limite que protege:** recepção que fala preço vira negociação sem você. Ela identifica e direciona, só isso.

**O teste:** mande "quanto custa?" como primeira mensagem. Ele tem que classificar como orçamento e direcionar, nunca responder um valor.
:::fim

:::bloco
## 02. Qualificação

:::bloco
prompt — agente de qualificação⟦botão: Copiar⟧

```
Você é o agente de qualificação do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: fazer as perguntas que separam curiosidade de oportunidade real.
Gatilho: o contato foi classificado como orçamento ou interesse comercial.
Pode consultar: meus critérios de cliente ideal: [PORTE, SEGMENTO, MOMENTO,
ORÇAMENTO MÍNIMO, QUEM DECIDE].
Não pode: descartar ninguém sozinho, nem dizer que a pessoa não se encaixa.
Chama uma pessoa quando: o contato responde as perguntas e bate os critérios, ou
quando se recusa a responder mas insiste em falar.
Saída esperada: as respostas organizadas em ficha, mais uma nota de 0 a 10 com a
justificativa em uma linha.

Escreva a instrução principal, 3 perguntas de qualificação na ordem certa, uma
forma educada de reformular quando a pessoa não responde, e o formato exato da
ficha. As perguntas precisam soar como conversa, não como formulário.
```
:::fim

**O limite que protege:** qualificação que descarta sozinha manda embora cliente bom em dia ruim. Ela pontua, você decide.

**O teste:** responda uma pergunta e ignore as outras duas. Ele tem que reformular uma vez e depois entregar a ficha incompleta, não insistir infinitamente.
:::fim

:::bloco
## 03. Agendamento

:::bloco
prompt — agente de agendamento⟦botão: Copiar⟧

```
Você é o agente de agendamento do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: oferecer horários, confirmar a reunião e registrar o próximo passo.
Gatilho: o contato foi qualificado e aceitou conversar.
Pode consultar: minha disponibilidade real: [DIAS E FAIXAS DE HORÁRIO], duração
padrão de [X] minutos e o canal da reunião: [LINK OU ENDEREÇO].
Não pode: oferecer horário fora dessa lista, nem remarcar mais de uma vez sozinho.
Chama uma pessoa quando: o contato pede horário fora da disponibilidade, ou
desmarca pela segunda vez.
Saída esperada: horário confirmado com data por extenso, canal da reunião e uma
mensagem de lembrete pronta para enviar no dia anterior.

Escreva a instrução principal, a mensagem que oferece os horários (no máximo 3
opções por vez), a confirmação, e a mensagem de lembrete.
```
:::fim

**O limite que protege:** agenda que aceita qualquer horário destrói o seu dia. Ele oferece só o que existe.

**O teste:** peça um horário de domingo às 22h. Ele tem que recusar oferecendo as opções reais, não improvisar.
:::fim

:::bloco
## 04. Catálogo e Dúvidas

:::bloco
prompt — agente de catálogo e dúvidas⟦botão: Copiar⟧

```
Você é o agente de catálogo do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: responder o que eu vendo e as dúvidas mais comuns.
Gatilho: pergunta sobre produto, serviço, funcionamento ou escopo.
Pode consultar: exclusivamente esta base: [COLE AQUI PRODUTOS, SERVIÇOS, O QUE
CADA UM INCLUI E AS PERGUNTAS FREQUENTES COM A RESPOSTA CERTA].
Não pode: responder nada que não esteja na base acima. Nem deduzir, nem estimar,
nem "provavelmente".
Chama uma pessoa quando: a pergunta não tem resposta na base.
Saída esperada: resposta curta baseada só na base, e quando não houver resposta,
a frase de encaminhamento sem inventar.

Escreva a instrução principal, a base organizada em pergunta e resposta, 2 ou 3
formas diferentes de perguntar a mesma coisa para cada item, e a frase exata de
quando não souber.
```
:::fim

**O limite que protege:** este é o agente que mais inventa se você deixar. A regra "só a base" é o que o torna publicável.

**O teste:** pergunte algo que você sabe que não está na base. Ele tem que dizer que vai encaminhar, não improvisar uma resposta plausível.
:::fim

:::bloco
:::bloco
## 05. Follow-up

:::bloco
prompt — agente de follow-up⟦botão: Copiar⟧

```
Você é o agente de follow-up do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: retomar conversa que parou, sem parecer cobrança.
Gatilho: [X] dias sem resposta depois de [QUAL ETAPA: proposta enviada, orçamento
passado, reunião marcada].
Pode consultar: o histórico da conversa e o que ficou combinado nela.
Não pode: repetir a mesma mensagem duas vezes, nem mandar mais de [N] follow-ups.
Depois disso, encerra.
Chama uma pessoa quando: a pessoa responde qualquer coisa que não seja "não tenho
interesse".
Saída esperada: uma mensagem curta que retoma o assunto específico daquela
conversa, nunca um "oi, tudo bem?".

Escreva a instrução principal, a cadência de follow-up com o intervalo de cada um,
e [N] mensagens diferentes que retomam contexto sem repetir a anterior.
```
:::fim

**O limite que protege:** follow-up sem teto vira perseguição e queima a marca. O número de tentativas é seu, não dele.

**O teste:** rode dois follow-ups seguidos. A segunda mensagem tem que citar algo que a primeira não citou.
:::fim

:::fim

:::bloco
## 06. Reativação

:::bloco
prompt — agente de reativação⟦botão: Copiar⟧

```
Você é o agente de reativação do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: reabrir conversa com contato antigo que sumiu.
Gatilho: [X] meses sem interação, com [QUAL SINAL: pediu orçamento, comprou uma
vez, chegou a agendar].
Pode consultar: o histórico daquele contato e [O QUE MUDOU DESDE ENTÃO: novidade
real, mudança de escopo, novo serviço].
Não pode: falar de promoção, desconto ou condição que eu não autorizei aqui.
Chama uma pessoa quando: a pessoa responde demonstrando interesse.
Saída esperada: uma mensagem que lembra o contexto anterior e apresenta o que
mudou, terminando em uma pergunta simples de sim ou não.

Escreva a instrução principal e 3 versões da mensagem: uma para quem pediu
orçamento e sumiu, uma para quem já foi cliente, e uma para quem agendou e não
apareceu.
```
:::fim

**O limite que protege:** reativação que inventa promoção compromete margem que você não aprovou.

**O teste:** peça a mensagem para um contato de 8 meses atrás. Ela tem que citar o que aconteceu antes, não abrir do zero.
:::fim

:::bloco
## 07. Suporte

:::bloco
prompt — agente de suporte⟦botão: Copiar⟧

```
Você é o agente de suporte do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: resolver a dúvida repetida e separar a exceção.
Gatilho: contato de quem já é cliente com um problema ou dúvida de uso.
Pode consultar: esta base de problemas conhecidos e solução de cada um: [COLE OS
10 A 15 CASOS MAIS COMUNS COM O PASSO A PASSO DE CADA].
Não pode: prometer prazo de correção, reembolso, troca ou compensação.
Chama uma pessoa quando: o problema não está na base, ou o cliente já tentou a
solução e ela não funcionou.
Saída esperada: o passo a passo da solução em lista numerada, ou o registro do
caso com o que já foi tentado, para a pessoa que assumir não começar do zero.

Escreva a instrução principal, a base organizada por sintoma, e o formato do
registro de escalonamento.
```
:::fim

**O limite que protege:** suporte que promete prazo cria expectativa que a operação não assinou.

**O teste:** descreva um problema que não está na base e diga que já tentou reiniciar. Ele tem que escalar com o registro do que foi tentado.
:::fim

:::bloco
## 08. Status

:::bloco
prompt — agente de status⟦botão: Copiar⟧

```
Você é o agente de status do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: informar o andamento de pedido, entrega ou projeto.
Gatilho: pergunta do tipo "e aí, como está?", "chegou?", "tem previsão?".
Pode consultar: [ONDE VIVE O STATUS REAL: planilha, sistema, quadro] e a lista de
etapas possíveis: [LISTE AS ETAPAS EM ORDEM].
Não pode: estimar data quando o sistema não tem data, nem dizer "deve chegar logo".
Chama uma pessoa quando: o status está atrasado em relação ao previsto, ou não
existe registro.
Saída esperada: a etapa atual pelo nome, o que acontece em seguida, e a data só
quando ela existir no registro.

Escreva a instrução principal, a mensagem de cada etapa, e a resposta para quando
não houver data no registro.
```
:::fim

**O limite que protege:** "deve chegar logo" é a frase que gera a reclamação da semana seguinte.

**O teste:** pergunte a previsão de um pedido sem data cadastrada. Ele tem que dizer a etapa e admitir que não há data, não chutar.
:::fim

:::bloco
## 09. Cobrança

:::bloco
prompt — agente de cobrança⟦botão: Copiar⟧

```
Você é o agente de cobrança do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: lembrar vencimento e sinalizar atraso.
Gatilho: [X] dias antes do vencimento, no dia, e [Y] dias depois se não constar
pagamento.
Pode consultar: [ONDE VIVE O STATUS DE PAGAMENTO] e os meios de pagamento aceitos.
Não pode: negociar valor, prazo, parcelamento ou desconto. Nem em nenhuma hipótese
sugerir que existe flexibilidade.
Chama uma pessoa quando: o cliente pede prazo, contesta o valor ou diz que já pagou.
Saída esperada: mensagem curta, sem constrangimento, com o valor, a data e o meio
de pagamento; e o registro de que o lembrete foi enviado.

Escreva a instrução principal, as três mensagens (antes, no dia, depois), e a
resposta de encaminhamento para quando o cliente pedir prazo.
```
:::fim

**O limite que protege:** este é o agente com maior risco financeiro. Cobrança que negocia sozinha entrega desconto que ninguém aprovou.

**O teste:** responda "consigo pagar semana que vem?". Ele tem que encaminhar para você, sem dizer "sem problema".
:::fim

:::bloco
## 10. Pós-venda

:::bloco
prompt — agente de pós-venda⟦botão: Copiar⟧

```
Você é o agente de pós-venda do WhatsApp de [TIPO DE NEGÓCIO].

Trabalho: confirmar se deu certo e registrar o retorno.
Gatilho: [X] dias depois de [ENTREGA, INSTALAÇÃO, PRIMEIRA SESSÃO].
Pode consultar: o que foi entregue para aquele cliente.
Não pode: pedir avaliação pública de quem respondeu que teve problema.
Chama uma pessoa quando: o cliente relata insatisfação de qualquer grau.
Saída esperada: a resposta do cliente registrada em uma linha, classificada em
resolvido, com ressalva ou com problema; e o pedido de avaliação apenas para os
resolvidos.

Escreva a instrução principal, a pergunta de acompanhamento, a classificação das
respostas e o pedido de avaliação para o caso resolvido.
```
:::fim

**O limite que protege:** pedir avaliação para cliente insatisfeito transforma um problema privado em uma nota pública.

**O teste:** responda "funcionou, mas demorou demais". Ele tem que classificar como ressalva e não pedir avaliação.
:::fim

## Onde o Prompt Vira Agente de Verdade

O prompt configura o cérebro. Ele não conecta nada: o Claude não fala com o WhatsApp sozinho. Para o agente responder no seu número, faltam duas camadas além da instrução.

1. 1.**O cérebro.** A instrução que você acabou de montar. Feito.
2. 2.**A ponte.** Alguma coisa que recebe a mensagem, chama o modelo com a sua instrução e devolve a resposta pelo mesmo canal.
3. 3.**O número.** Uma conta de WhatsApp que aceite ser operada por programa. O seu WhatsApp normal, do jeito que está, não aceita.

São três rotas para montar a 2 e a 3, da mais barata para a mais robusta.

### Rota 1 · Na Mão (Comece por Aqui)

A instrução vira um Projeto no Claude. Você continua respondendo, mas cola a conversa e usa a resposta dele. Zero integração e nenhum custo além do Claude.

**Serve para:** validar se o agente responde bem antes de você gastar com integração. Os três testes de cada bloco rodam aqui, hoje, em dez minutos.

**Não serve para:** responder fora do seu horário, follow-up automático, volume.

Quase todo mundo pula esta rota e se arrepende: descobre que a instrução estava ruim depois de montar a integração inteira.

### Rota 2 · No-code

Um número na API oficial (WhatsApp Business Platform, contratada pela Meta ou por um provedor) mais uma automação que faz a ponte: n8n, Make, Zapier ou equivalente. A automação recebe o webhook do WhatsApp, chama a API do modelo com a sua instrução e devolve a resposta.

**Precisa de:** conta WhatsApp Business, número verificado, uma chave de API do modelo e a automação montada. Não precisa programar.

**Cuidado:** a regra das 24 horas, logo abaixo. Ela decide se quatro dos dez agentes vão funcionar ou não.

### Rota 3 · Código

Provedor de WhatsApp, webhook, uma função na nuvem que chama o modelo, e a resposta sai pelo mesmo provedor.

É o que roda no meu número. Na prática são três funções: uma que recebe o webhook e grava a conversa, uma que envia, e uma terceira que lê a conversa e responde. Tudo na nuvem, então funciona com o meu computador desligado.

**Precisa de:** alguém que escreva as funções. É a rota que dá mais trabalho e a única em que você controla tudo: a memória da conversa, quando a IA pausa, e quanto custou cada resposta.

### A Regra das 24 Horas (Ela Quebra Quatro dos Dez)

Esta é a parte que ninguém conta antes de você montar tudo.

Na API oficial do WhatsApp, você só manda mensagem livre dentro de 24 horas da última mensagem que a pessoa te enviou. Fora dessa janela, só sai modelo (template) aprovado pela Meta antes, e cada modelo passa por revisão.

Isso atinge exatamente os quatro agentes que falam primeiro.

- →03 Agendamento, no lembrete da véspera.
- →05 Follow-up, que por definição fala com quem não respondeu.
- →06 Reativação, que fala com quem sumiu há meses.
- →09 Cobrança, que avisa antes do vencimento.

Os outros seis respondem quem acabou de escrever, então vivem dentro da janela e não têm esse problema.

**O que fazer:** escreva esses quatro como template e mande aprovar antes de prometer a rotina para alguém. Ou rode esses quatro por um provedor não oficial, que não tem janela. Provedor não oficial tem risco de bloqueio do número, então use um número secundário, nunca o principal da empresa.

Confira preço e política atuais direto na Meta antes de fechar conta. Essa parte muda com frequência e qualquer número que eu escrevesse aqui envelheceria.

### O Que Quebra na Prática

Coisas que só aparecem depois que está no ar:

- →A pessoa manda quatro mensagens seguidas. Sem uma espera antes de responder, o agente responde quatro vezes. Segure alguns segundos, junte tudo e responda uma vez só.
- →O webhook também recebe o que você envia. Sem marcar o que saiu do agente, ele lê a própria mensagem como se fosse do cliente e responde a si mesmo.
- →Você responde do celular no meio da conversa. O agente precisa perceber e pausar sozinho, senão vocês dois falam ao mesmo tempo com o mesmo cliente.
- →Duas entregas do mesmo webhook. Sem uma trava, o cliente recebe a resposta duplicada.
- →O provedor guarda pouco histórico. Se a memória da conversa mora só lá, ela some. Grave em algum lugar seu.
- →Escalonamento sem destino. O agente chama uma pessoa e ninguém recebe. Agente que escala para o vazio é igual a agente que não escala.

## O Checklist Antes de Ligar Qualquer Um Deles

- Os cinco campos estão preenchidos, incluindo o "não pode".
- A fonte de verdade existe de verdade e está atualizada.
- O agente foi testado com uma pergunta comum e resolveu.
- Foi testado com uma pergunta fora da regra e recusou.
- Foi testado com uma decisão sua e chamou você.
- Existe uma pessoa recebendo o que ele escala.
- A rota está escolhida, e se for a oficial, os templates dos agentes 03, 05, 06 e 09 já foram aprovados.

O último item é o mais esquecido. Agente que escala para ninguém é o mesmo que agente que não escala.

## O Que Fazer Quando Ele Errar

Ele vai errar. Quando errar, não reescreva o prompt inteiro: descubra **qual dos cinco campos falhou**. Respondeu o que não devia, o campo é o limite. Entrou na hora errada, é o gatilho. Inventou informação, é a fonte de verdade. Entregou no formato errado, é a saída.

Consertar o campo certo é o que faz o agente melhorar em vez de mudar de defeito.

---

## POST 31 — Mapa de próxima ação para não esquecer leads

- URL: `/blog/proxima-acao`
- Template: padrão (hero + artigo 720px)
- Categoria: VENDAS & IA
- Data no card: 2 Set 2026 | Data na página: 2 de setembro de 2026
- Tempo de leitura: 3 min (página: "3 min de leitura")
- Resumo do card: O modelo de uma linha por lead — status, próxima ação, dono, prazo e critério de saída — que evita lead esquecido numa conversa antiga sem próximo passo definido.
- Meta description: O modelo de uma linha por lead — status, próxima ação, dono, prazo e critério de saída — que evita lead esquecido numa conversa antiga sem próximo passo definido.
- Título da aba: Mapa de Próxima Ação para Não Esquecer Leads | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Modelo · 02Exemplo · 03A Regra que Evita o Esquecimento

### Corpo do post (conteúdo exato, na ordem da página)

Este é o material prometido no post.

A regra é simples: nenhum lead fica apenas com um nome e uma conversa antiga. Cada registro precisa sair com uma próxima ação clara.

## Modelo

Copie e preencha uma linha para cada lead:

:::bloco
modelo — mapa de próxima ação⟦botão: Copiar⟧

```
LEAD: <nome>
CANAL: <de onde veio>
CONTEXTO: <o que ele quer e o que já foi conversado>
STATUS: <novo | em conversa | proposta enviada | aguardando retorno | ganho | perdido>
PRÓXIMA AÇÃO: <o que precisa acontecer agora>
DONO: <quem executa>
PRAZO: <data e hora>
CRITÉRIO DE SAÍDA: <o que precisa acontecer para mudar o status>
```
:::fim

## Exemplo

:::bloco
exemplo preenchido⟦botão: Copiar⟧

```
LEAD: Marina
CANAL: LinkedIn
CONTEXTO: pediu preço e confirmou que decide nesta semana
STATUS: proposta enviada
PRÓXIMA AÇÃO: fazer follow-up com uma pergunta objetiva
DONO: comercial
PRAZO: amanhã às 10h
CRITÉRIO DE SAÍDA: respondeu, pediu ajuste ou marcou reunião
```
:::fim

## A Regra que Evita o Esquecimento

Se a linha não tem próxima ação, dono e prazo, ela não está organizada. Está apenas armazenada.

O CRM pode lembrar e disparar o próximo passo, mas só funciona quando a operação define o que deve acontecer depois de cada resposta, silêncio ou objeção.


---

## POST 32 — A folha de regras: transformar sua planilha em sistema

- URL: `/blog/folha-regras`
- Template: padrão (hero + artigo 720px)
- Categoria: DESENVOLVIMENTO & IA
- Data no card: 2 Set 2026 | Data na página: 2 de setembro de 2026
- Tempo de leitura: 9 min (página: "9 min de leitura")
- Resumo do card: A folha de regras que faz o Claude entender as exceções da sua planilha antes de escrever qualquer código — com os 4 prompts em ordem: diagnóstico, especificação, construção e migração dos dados.
- Meta description: A folha de regras que faz o Claude entender as exceções da sua planilha antes de escrever qualquer código — com os 4 prompts em ordem: diagnóstico, especificação, construção e migração dos dados.
- Título da aba: A Folha de Regras: Transformar Sua Planilha em Sistema | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Se Você Veio do Carrossel · 02Parte 1 — O Modelo da Folha de Regras · 03Parte 2 — Os 4 Prompts, Nesta Ordem · 04Parte 3 — Checklist Antes de Considerar Pronto · 05Quando Der Errado na Primeira Tentativa · 06O Próximo Passo

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar PLANILHA.

Sua planilha não é bagunça. Ela é a especificação do seu sistema, escrita por você ao longo de anos, sem perceber. Os campos, as contas e o histórico já estão lá. O que falta não está na planilha, está na sua cabeça: as regras que você aplica automaticamente toda vez que abre o arquivo.

Escrever essas regras em uma página é o que separa sair um sistema de verdade de sair uma tabela mais bonita. É isso que a gente chama de folha de regras.

**Sobre o tempo.** O trabalho ativo com o Claude é curto, uns 10 minutos de ida e volta. O que leva uma tarde é a parte que só você pode fazer: preencher a folha de regras com honestidade e conferir a especificação antes de mandar construir. Quem pula essa parte economiza a tarde e perde a semana refazendo.

## Se Você Veio do Carrossel

Os dois prompts que você viu estão aqui embaixo, na versão completa, mais dois que o carrossel não coube. A ordem é a mesma: **diagnóstico primeiro, estrutura depois, telas por último.**

O que muda da versão do carrossel para a daqui: nos prompts completos você anexa também a folha de regras. É ela que faz o Claude parar de adivinhar as suas exceções. Sem ela, o diagnóstico sai correto e genérico; com ela, sai correto e seu.

## Parte 1 · O Modelo da Folha de Regras

Copie o bloco abaixo, responda cada linha e salve como `folha-de-regras.md` na mesma pasta da sua planilha. Leva de 15 a 30 minutos e é o único trabalho realmente seu.

:::bloco
modelo — folha-de-regras.md⟦botão: Copiar⟧

```
FOLHA DE REGRAS · <nome da planilha>

1. PARA QUE ELA EXISTE
   Em uma frase, qual decisão ou tarefa essa planilha sustenta.

2. QUEM ENCOSTA NELA
   Quem preenche:
   Quem aprova:
   Quem só consulta:
   Quem nunca pode ver:

3. O CICLO DE VIDA DE UMA LINHA
   Quando uma linha nasce:
   Por quais estados ela passa (ex: novo, em andamento, fechado, cancelado):
   Quando ela conta como fechada:
   Quando ela pode ser apagada (ou nunca):

4. AS REGRAS QUE VOCÊ APLICA DE CABEÇA
   O que trava (não pode avançar se...):
   O que pode passar mesmo incompleto:
   O que muda de valor sozinho (data, status, cálculo):
   Quem pode alterar depois de aprovado:

5. AS CONTAS
   Liste cada fórmula que importa e o que ela significa em português.
   Ex: coluna M = valor x comissão, mas só quando o status for "pago".

6. O QUE ACONTECE FORA DA PLANILHA
   O que você faz antes de abrir o arquivo:
   O que você faz depois de preencher (avisar alguém, mandar mensagem, lançar em outro lugar):
   O que devia acontecer sozinho, sem ninguém lembrar:

7. O QUE SEMPRE DÁ ERRADO
   Os 3 erros que mais acontecem hoje:
   O que você gostaria que o sistema simplesmente impedisse:
```
:::fim

O ponto 6 é o mais valioso e o mais esquecido. É ali que mora a diferença entre um cadastro e uma operação que anda sozinha.

## Parte 2 · Os 4 Prompts, Nesta Ordem

A ordem importa mais que a redação. Pular o prompt 1 é o motivo número um de sair um sistema genérico que não serve pra sua operação.

### Prompt 1 · Contexto (antes de qualquer código)

:::bloco
prompt 1 — contexto⟦botão: Copiar⟧

```
Claude, vou te dar uma planilha e uma folha de regras da minha operação.
Antes de escrever qualquer linha de código, leia os dois e me devolva:
1. o que você entendeu que essa operação faz, em até 10 linhas
2. as entidades e os campos que você identificou
3. as 5 perguntas que você ainda precisa que eu responda para não ter que adivinhar

Não proponha solução ainda. Só entenda e pergunte.
```
:::fim

Responda as 5 perguntas antes de seguir. Esse ida e volta é o sistema sendo desenhado.

### Prompt 2 · Regras e Permissões

:::bloco
prompt 2 — regras e permissões⟦botão: Copiar⟧

```
Claude, com base no que você entendeu e nas minhas respostas, escreva a especificação do sistema:
· as tabelas e os campos, com tipo e obrigatoriedade
· os estados possíveis de cada registro e as transições permitidas
· as regras de negócio que travam ou liberam cada transição
· os perfis de acesso e o que cada um pode ver, criar, editar e aprovar
· o que precisa acontecer automaticamente, sem ninguém lembrar

Me mostre a especificação para eu aprovar antes de construir.
```
:::fim

Leia e corrija. É mais barato corrigir uma linha de especificação que uma tela pronta.

### Prompt 3 · Construir

:::bloco
prompt 3 — construir⟦botão: Copiar⟧

```
Claude, aprovada a especificação, construa o sistema:
· banco de dados com as tabelas e as regras que definimos
· tela de cadastro e edição, com as travas funcionando
· painel com os números que hoje eu tiro na mão da planilha
· histórico de alterações, quem mudou o quê e quando
· login com os perfis de acesso definidos

Trabalhe em partes e me mostre cada uma funcionando antes de seguir para a próxima.
```
:::fim

### Prompt 4 · Colocar no Ar e Migrar

:::bloco
prompt 4 — colocar no ar e migrar⟦botão: Copiar⟧

```
Claude, coloque o sistema no ar num endereço que eu possa abrir do celular e compartilhar com a
equipe. Depois, importe os dados da planilha para o sistema, respeitando as regras que
definimos, e me mostre um relatório do que entrou, do que foi corrigido e do que não pôde
ser importado e por quê.
```
:::fim


## Parte 3 · Checklist Antes de Considerar Pronto

- Abre no celular por um link, não só na sua máquina
- Outra pessoa consegue cadastrar sem te perguntar nada
- O que era fórmula manual acontece sozinho
- Existe histórico de quem alterou o quê
- Os dados antigos da planilha estão dentro
- A planilha antiga foi fechada ou marcada como arquivo morto

O último item é o que mais falha. Enquanto a planilha estiver aberta, a equipe volta pra ela na primeira dúvida e você passa a manter dois sistemas em vez de um.

## Quando Der Errado na Primeira Tentativa

**Saiu genérico, com campos que você não usa.** Você pulou o prompt 1 ou respondeu as 5 perguntas por cima. Volte e responda com exemplos reais de linhas da sua planilha.

**Ficou bonito mas não trava nada.** A folha de regras estava fraca no ponto 4. Liste o que não pode acontecer, não só o que pode.

**Funciona na sua máquina e ninguém mais usa.** Faltou o prompt 4. Sistema sem link é projeto.

**A equipe voltou pra planilha.** Você deixou o arquivo antigo aberto, ou alguma coisa que ela fazia em 10 segundos agora leva 5 cliques. Pergunte qual, e conserte essa tela primeiro.

## O Próximo Passo

Se você fez até aqui, você tem um sistema no ar e uma planilha aposentada. A parte difícil já passou.

Me responde nesta mesma conversa dizendo **qual planilha você escolheu** e onde travou, se travou. Eu leio todas. É com essas respostas que eu descubro quais são as travas reais de quem está fazendo isso pela primeira vez, e é assim que esse material vai melhorando.

E se a sua operação tem mais de uma planilha nesse estado, não faça as outras no piloto automático. A segunda quase sempre precisa conversar com a primeira, e aí a conversa muda: em vez de dois sistemas soltos, você quer um só com duas telas.

---

## POST 33 — Os 6 prompts para montar uma central de conteúdo

- URL: `/blog/central-conteudo`
- Template: padrão (hero + artigo 720px)
- Categoria: CONTEÚDO & IA
- Data no card: 25 Ago 2026 | Data na página: 25 de agosto de 2026
- Tempo de leitura: 10 min (página: "10 min de leitura")
- Resumo do card: 6 prompts em ordem — perfil de marca, raio-X, calendário de 30 dias, banco de ideias, análise dos vencedores e escrita final — que transformam a IA de resposta genérica em central de conteúdo com contexto de verdade.
- Meta description: 6 prompts em ordem — perfil de marca, raio-X, calendário de 30 dias, banco de ideias, análise dos vencedores e escrita final — que transformam a IA de resposta genérica em central de conteúdo com contexto de verdade.
- Título da aba: Os 6 Prompts para Montar uma Central de Conteúdo | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Antes de Começar: Onde Colar · 021. Configuração da Central · 032. Raio-X do Perfil · 043. Calendário de 30 Dias · 054. Banco Contínuo de Ideias · 065. Análise dos Próprios Vencedores · 076. Escrita do Post Final · 08A Ordem Importa · 09Quando Não Funcionar · 10O Próximo Passo

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar CENTRAL.

Quase todo mundo usa a IA para conteúdo do mesmo jeito: abre uma conversa nova e pede "escreve uma legenda sobre X". A resposta volta correta e genérica, você reescreve metade, e conclui que a ferramenta ainda não chegou lá.

O problema está no ponto de entrada. Você está pedindo a última etapa de um processo de seis, sem ter feito as cinco anteriores. A IA não sabe o que você vende, para quem, com que voz, o que já funcionou no seu perfil nem o que está no seu calendário. Sem isso, ela preenche o vazio com a média da internet, que é exatamente o texto que você reconhece como "cara de IA".

Os seis prompts abaixo invertem essa ordem. Os cinco primeiros constroem contexto. O sexto, e só ele, escreve o post.

**Sobre o tempo.** A primeira rodada leva de 40 a 60 minutos, quase tudo no prompt 1. Depois disso os prompts 3 a 6 viram rotina de minutos, porque o contexto já existe.

## Antes de Começar: Onde Colar

Crie um **Projeto** no claude.ai ou no ChatGPT e rode os seis dentro dele.

Isso não é detalhe. O Projeto guarda o contexto entre conversas, então o perfil que o prompt 1 montou continua valendo quando você chegar no 6. Se rodar cada prompt numa conversa solta, o contexto se perde e o último volta a chutar, que é exatamente o problema que a gente está resolvendo.

## 1. Configuração da Central

Você roda uma vez. Ele cria o perfil de marca que todos os outros consultam.

:::bloco
prompt 1 — configuração da central⟦botão: Copiar⟧

```
Você vai atuar como a minha central de conteúdo. Antes de escrever qualquer peça,
você precisa me conhecer de verdade.

ETAPA 1 · ENTREVISTA
Me faça perguntas, no máximo 4 por vez, até conseguir preencher todos os campos
abaixo. Não avance enquanto algum estiver vago. Se eu responder de forma genérica,
aponte isso e peça de novo, me dando um exemplo do nível de detalhe que você precisa.

CAMPOS
· negócio: o que eu faço, para quem, e como eu cobro
· oferta principal: nome, promessa, preço e formato de entrega
· público: quem decide a compra, o cargo, e em que momento me procura
· dor: o problema concreto que me faz ser contratado, nas palavras do cliente
· objetivo do conteúdo: autoridade, geração de lead, venda direta ou retenção
· posicionamento: o que eu defendo e contra o que eu me posiciono
· voz: 5 traços do meu jeito de falar e 5 coisas que eu nunca diria
· provas: números, casos e bastidores que eu posso mostrar publicamente
· proibido: temas, formatos e promessas que eu não quero associados a mim

ETAPA 2 · PERFIL
Quando tiver tudo, escreva um PERFIL DE MARCA organizado em blocos, pronto para eu
colar nas instruções deste Projeto. Escreva na minha voz, não na sua.

ETAPA 3 · TESTE
Escreva 3 aberturas de post usando esse perfil e me pergunte quais soam como eu.
Ajuste o perfil com base na minha resposta e me devolva a versão final.

REGRAS
· não invente nada que eu não tenha dito
· não elogie meu negócio, elogio não me ajuda a decidir
· quando faltar informação, escreva [CONFIRMAR] em vez de preencher por conta própria
```
:::fim

**O que volta:** um perfil de marca escrito, testado contra três aberturas, pronto para colar nas instruções do Projeto. Guarde isso. É o ativo que faz os outros cinco funcionarem.

## 2. Raio-X do Perfil

:::bloco
prompt 2 — raio-x do perfil⟦botão: Copiar⟧

```
Analise o meu perfil como um estranho analisaria, sem simpatia e sem suposição.
Vou colar minha bio e meus últimos posts com os números que eu tiver.

O QUE AVALIAR
· bio: o que a pessoa entende em 2 segundos, antes do corte do "... mais"
· promessa: alguém que nunca me viu consegue dizer o que eu resolvo e para quem
· pilares: quais temas se repetem e qual porcentagem do meu feed cada um ocupa
· ganchos: quais aberturas prendem e quais são só título de assunto
· coerência: a distância entre o conteúdo que eu publico e a oferta que eu vendo
· público atraído: pelo teor dos comentários, quem está de fato me seguindo

ENTREGUE NESTA ORDEM
1. o que está ajudando, com o post específico que serve de exemplo
2. o que está confundindo, com o post específico que serve de exemplo
3. os 5 ajustes mais importantes, do mais urgente para o menos
4. quem eu estou atraindo hoje contra quem eu deveria atrair
5. 3 testes para os próximos 30 dias, cada um com a métrica que decide o teste

REGRAS
· não elogie sem apontar o motivo concreto
· não invente dado de desempenho que eu não passei
· se os números que eu mandei não sustentarem uma conclusão, diga isso em vez de
  concluir mesmo assim
```
:::fim

**O que volta:** um diagnóstico com exemplo nomeado em cada ponto, e a comparação entre o público que você atrai e o que você quer atrair.

O item que mais dói e mais serve é a coerência entre o que você publica e o que vende. É comum descobrir aqui que o perfil atrai gente que nunca vai comprar. Melhor descobrir agora.

## 3. Calendário de 30 Dias

:::bloco
prompt 3 — calendário de 30 dias⟦botão: Copiar⟧

```
Com base no meu perfil de marca, monte meu calendário de conteúdo de 30 dias.

ANTES DE MONTAR, ME PERGUNTE
· quantas peças por semana eu consigo publicar de verdade
· quais formatos eu consigo produzir sem depender de ninguém
· se eu apareço em vídeo ou não
· se tem alguma data, lançamento ou sazonalidade no período

PARA CADA PEÇA, ENTREGUE
data · pilar · tema · gancho de abertura · mensagem central · formato · CTA

DISTRIBUIÇÃO
· descoberta, para quem ainda não sabe que tem o problema
· consideração, para quem já busca solução e está comparando
· decisão, para quem precisa de um empurrão para me procurar
Me diga a porcentagem de cada uma e por que escolheu essa divisão.

REGRAS
· nada de tema genérico do tipo "a importância de X"; cada peça resolve um problema
  concreto do meu público
· não repita o mesmo tema com outras palavras dentro do mês
· se faltar informação, marque [CONFIRMAR] em vez de inventar
· respeite a quantidade que eu disse que consigo. Um calendário que eu não cumpro
  não me serve
```
:::fim

**O que volta:** um mês com gancho e CTA já definidos por peça, na quantidade que você realmente consegue publicar, e a justificativa da divisão do funil.

## 4. Banco Contínuo de Ideias

:::bloco
prompt 4 — banco de ideias⟦botão: Copiar⟧

```
Com base no meu perfil e nos meus pilares, gere 20 ideias de conteúdo.

SEPARE EM TRÊS NÍVEIS DE CONSCIÊNCIA
· iniciante: ainda não sabe que tem o problema
· intermediário: já sabe e já tentou resolver sozinho
· avançado: compara soluções e quer entender o mecanismo

PARA CADA IDEIA
· o problema concreto, escrito como o meu cliente falaria
· o gancho de abertura
· o formato mais forte para aquela ideia e o motivo
· o que a pessoa leva embora depois de consumir
· qual objeção de compra aquela ideia enfraquece

REGRAS
· não repita a mesma ideia trocando palavras; se duas forem parentes, junte
· nenhuma ideia pode depender de um número ou caso que eu não te dei
· marque quais das 20 exigem uma prova minha que ainda não existe, para eu decidir
  se produzo essa prova antes
```
:::fim

**O que volta:** 20 ideias com nível, formato e objeção mapeados, e a marcação de quais dependem de uma prova que você ainda precisa produzir.

**Por que separar por nível:** conteúdo de iniciante traz alcance, conteúdo de avançado traz cliente. Quem só publica um dos dois trava, e a separação obriga você a enxergar isso.


## 5. Análise dos Próprios Vencedores

:::bloco
prompt 5 — análise dos vencedores⟦botão: Copiar⟧

```
Vou colar meus posts publicados com os números disponíveis. Encontre o padrão.

COMPARE OS MAIS FORTES CONTRA OS MAIS FRACOS EM
tema · tipo de gancho · formato · promessa da capa · presença de número
· presença de prova própria · tipo de CTA

SEPARE OS SINAIS, NÃO MISTURE
· alcance mede distribuição
· salvamento e compartilhamento medem utilidade
· comentário mede intenção
· seguidor ganho mede se a pessoa quis mais
Um post pode ir bem em um e mal em outro. Diga em qual foi bem e em qual foi mal.

ENTREGUE
1. os 3 padrões que se repetem nos melhores
2. os 3 erros que se repetem nos piores
3. 5 temas que merecem voltar com outro ângulo, e qual ângulo
4. 3 experimentos para o próximo mês, mudando UMA variável por vez
5. o que os números ainda não permitem afirmar

REGRAS
· não trate alcance alto como sinônimo de bom resultado
· se a amostra for pequena demais para uma conclusão, diga isso
· prefira "esse padrão aparece em 4 dos 5 melhores" a afirmações genéricas
```
:::fim

**O que volta:** os padrões dos seus próprios vencedores, separados por tipo de sinal, e três experimentos com uma variável cada.

Este é o que mais gente pula e o que mais muda resultado. A resposta do que funciona com o seu público já está nos seus números, não no perfil grande que faz outra coisa.

## 6. Escrita do Post Final

:::bloco
prompt 6 — escrita do post final⟦botão: Copiar⟧

```
Com base no meu perfil, no calendário e no ângulo abaixo, escreva o post completo.

ÂNGULO: [COLE O TEMA E O GANCHO]
FORMATO: [CARROSSEL, ESTÁTICO, REELS OU TEXTO]
NÍVEL DO PÚBLICO: [INICIANTE, INTERMEDIÁRIO OU AVANÇADO]

ESTRUTURA
· abertura: uma frase concreta, com cena ou número, nunca uma tese solta
· desenvolvimento: um mecanismo ou uma decisão útil, não uma lista de dicas
· fechamento: resolve a promessa que a abertura abriu
· CTA: coerente com um material que eu realmente tenho para entregar

ANTES DE ESCREVER, ME DIGA
· qual promessa a abertura está fazendo
· o que a pessoa sabe fazer depois de ler que não sabia antes
Se você não conseguir responder as duas, o ângulo está fraco. Me avise em vez de
escrever mesmo assim.

REGRAS
· escreva na minha voz, usando o perfil, não no seu tom padrão
· não invente número, prova, case ou depoimento
· se faltar uma informação essencial, marque [CONFIRMAR]
· nada de clichê de IA e nada de frase de efeito sem entrega
```
:::fim

**O que volta:** o post completo, na sua voz, e antes dele a checagem de promessa que mata ângulo fraco antes de virar peça.

## A Ordem Importa

O primeiro alimenta o segundo. O segundo melhora o terceiro. O calendário e os números alimentam os ciclos seguintes. O sexto só funciona bem porque os cinco anteriores existiram.

Se você só tiver tempo para um hoje, rode o **1**. Ele muda todas as respostas seguintes, inclusive as que você pedir fora desta lista.

## Quando Não Funcionar

**As respostas continuam genéricas.** Você provavelmente está fora do Projeto, ou respondeu o prompt 1 com generalidades. "Vendo consultoria para empresas" não é contexto. "Faço diagnóstico de IA para indústrias de médio porte que perdem pedido por falta de processo" é contexto.

**Ele inventou um número ou uma prova.** Todos os prompts trazem a trava, mas se escapar, corrija na hora e exija `[CONFIRMAR]`. Publicar número inventado é o erro que custa mais caro.

**O calendário veio óbvio.** Rode o 5 antes de repetir o 3. Com os seus padrões na mesa, o calendário sai outro.

**Quero adaptar os prompts.** Adapte, o texto é seu. O que não deve mudar é a ordem, porque é ela que carrega o contexto de um para o outro.

## O Próximo Passo

Crie o Projeto, rode o prompt 1 hoje e guarde o perfil que sair. Amanhã rode o 2 e o 3. Em dois dias você tem contexto, diagnóstico e calendário, que já é mais estrutura do que a maioria dos perfis tem.

Me responde nesta conversa dizendo **o que apareceu no seu raio-X** que você não esperava. Eu leio todas. O prompt 2 costuma revelar a coisa mais desconfortável, e é com essas respostas que eu descubro quais travas são comuns e quais prompts precisam melhorar.

---

## POST 34 — 56 comandos para o Claude: a folha de instalação

- URL: `/blog/56-comandos`
- Template: padrão (hero + artigo 720px)
- Categoria: CLAUDE
- Data no card: 25 Ago 2026 | Data na página: 25 de agosto de 2026
- Tempo de leitura: 13 min (página: "13 min de leitura")
- Resumo do card: Os 56 comandos de atalho que ensinam o Claude a responder no papel certo — dono, vendedor, analista, gestor de time — com o bloco de instalação pronto pra colar no Projeto ou no CLAUDE.md.
- Meta description: Os 56 comandos de atalho que ensinam o Claude a responder no papel certo — dono, vendedor, analista, gestor de time — com o bloco de instalação pronto pra colar no Projeto ou no CLAUDE.md.
- Título da aba: 56 Comandos para o Claude: A Folha de Instalação | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Se Você Veio do Carrossel · 02Parte 1 — Onde Instalar · 03Parte 2 — O Bloco para Colar · 04Parte 3 — Como Usar · 05Parte 4 — O Ajuste que Separa Correto de Útil · 06Quando Não Funcionar · 07O Próximo Passo

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar CLAUDE.

Começo pelo aviso que evita você perder tempo: **esses comandos não vêm prontos no Claude.** Se você abrir o Claude agora e digitar `/dono`, não acontece nada. Ele vai responder qualquer coisa, ou perguntar o que você quis dizer.

Eles passam a funcionar depois que você instala o bloco que está aqui embaixo. É uma vez só, leva dois minutos, e a partir daí os 56 funcionam em qualquer conversa sua.

Vale explicar por que isso importa, porque é o ponto que quase todo mundo ignora. O Claude responde bem quando sabe em que papel você quer que ele pense. O problema é que reexplicar o papel toda vez ("responde como se fosse um dono de empresa, focando em caixa e risco") é chato, e por ser chato você para de fazer. Aí ele volta a responder genérico e você conclui que a ferramenta é fraca. O atalho resolve isso: você escreve quatro letras e o papel já está carregado.

**Sobre o tempo.** A instalação leva dois minutos. O que muda o resultado de verdade é a Parte 4, que leva mais uns cinco. Quem pula ela recebe respostas corretas e genéricas.

## Se Você Veio do Carrossel

Os 56 que você viu nos slides estão aqui embaixo, na íntegra e na mesma ordem. O que o carrossel não conseguia entregar é justamente o que faz eles funcionarem: o bloco de instalação da Parte 2, e o ajuste de contexto da Parte 4.

## Parte 1 · Onde Instalar

Escolha a rota conforme você usa o Claude hoje.

### Se Você Usa o Site ou o Aplicativo do Claude

É a maioria dos casos.

1. 1.Abra o Claude e crie um **Projeto**. Fica no menu lateral, em "Projetos", botão de criar. Dê um nome ligado à sua operação, algo como "Minha empresa" ou "Operação".
2. 2.Dentro do Projeto, procure o campo de **instruções** (aparece como "Instruções" ou "Instruções personalizadas", dependendo da versão).
3. 3.Cole ali o bloco inteiro da Parte 2 e salve.
4. 4.Pronto. Toda conversa aberta **dentro desse Projeto** entende os 56 comandos.

**O erro que quase todo mundo comete na primeira vez:** abrir uma conversa nova fora do Projeto e achar que não funcionou. Os comandos existem apenas onde as instruções foram coladas. Antes de testar, confira se o nome do Projeto aparece no topo da conversa.

### Se Você Usa o Claude Code, no Terminal

Cole o mesmo bloco no arquivo `CLAUDE.md` da raiz do seu projeto. Vale para todas as sessões daquele repositório, sem mais configuração.

## Parte 2 · O Bloco para Colar

Copie tudo que está dentro do quadro, do começo ao fim.

:::bloco
bloco de instalação — 56 comandos⟦botão: Copiar⟧

```
COMANDOS DE ATALHO

Quando minha mensagem começar com uma barra e uma das palavras abaixo, trate como
uma instrução de COMO responder, e aplique ao resto da mensagem. Se eu escrever
apenas o comando, sem mais nada, pergunte sobre o que devo aplicá-lo. Se eu combinar
dois comandos, aplique os dois.

CLAREZA E COMUNICAÇÃO
/direto: vá direto ao ponto. Sem introdução, sem rodeio, sem repetir minha pergunta.
/simples: explique como se eu não soubesse nada do assunto, sem jargão.
/especialista: responda no nível de quem é referência na área, com profundidade técnica.
/resumo: reduza ao essencial, em poucas linhas.
/passoapasso: divida a resposta em etapas numeradas, na ordem de execução.
/reescreve: melhore a clareza do texto que eu colar, sem mudar o sentido.
/traduz: troque o termo técnico por linguagem de negócio, para quem decide entender.

DECISÃO E ESTRATÉGIA
/dono: responda pensando em caixa, risco e resultado, não em teoria.
/prosecontras: liste vantagens e desvantagens antes de eu decidir.
/priorize: organize as tarefas pelo impacto real, não pela urgência aparente.
/cenarios: mostre três caminhos possíveis e o resultado mais provável de cada um.
/risco: aponte o que pode dar errado antes de eu seguir em frente.
/planotres: monte um plano de ação em três passos, cada um com prazo.
/segundaopiniao: questione a minha própria ideia, com honestidade, antes de eu executar.

VENDAS E OFERTA
/objecao: liste as objeções mais prováveis do cliente e como responder cada uma.
/oferta: organize o que eu vendo em promessa, entrega e prova.
/followup: escreva a mensagem certa para retomar um lead parado.
/proposta: monte uma proposta comercial curta e direta.
/preco: ajude a justificar o valor cobrado sem parecer caro.
/qualifica: crie as perguntas certas para saber se um lead vale meu tempo.
/fechamento: sugira como conduzir a conversa até o sim.

CONTEÚDO E REDES SOCIAIS
/gancho: escreva três aberturas diferentes para prender atenção.
/carrossel: transforme a ideia num roteiro de carrossel pronto, slide a slide.
/legenda: escreva a legenda no meu tom, sem parecer texto de robô.
/titulo: crie variações de título até chegar em uma que chame atenção de verdade.
/simplificaconteudo: pegue o assunto técnico e transforme em post fácil de entender.
/repropositar: transforme este conteúdo em cinco formatos diferentes.
/opiniao: escreva uma tese forte e defensável sobre o tema.

OPERAÇÃO E PRODUTIVIDADE
/automatiza: sugira como tirar esta tarefa repetida da minha mão.
/processo: transforme estes passos soltos em um processo documentado.
/email: escreva o e-mail certo para a situação que eu descrever.
/reuniao: resuma a transcrição em decisões tomadas e próximos passos, com responsável.
/checklist: transforme esta tarefa complexa em lista de verificação.
/delega: escreva as instruções para eu repassar esta tarefa a alguém do time.
/rotina: organize o meu dia pelas prioridades reais, não pela caixa de entrada.

ANÁLISE E PESQUISA
/pesquisa: investigue o tema e traga o que realmente importa, sem enrolação.
/concorrente: analise o que este concorrente faz e onde existe brecha.
/dados: interprete o número ou a planilha e explique o que aquilo significa.
/tendencia: aponte o que está mudando no meu mercado agora.
/critica: aponte os furos e as fraquezas desta ideia antes de eu apostar nela.
/comparativo: compare as duas opções lado a lado, pelos critérios que importam.
/resumolongo: resuma o documento nos pontos que eu preciso saber para decidir.

PESSOAS E TIME
/entrevista: simule uma entrevista de contratação e me dê feedback ao final.
/feedback: escreva um retorno direto e respeitoso para alguém do time.
/jd: escreva a descrição de vaga certa para atrair o perfil que eu preciso.
/onboarding: monte o roteiro de integração de alguém novo no time.
/conflito: sugira como conduzir esta conversa difícil com um funcionário.
/1a1: prepare a pauta de uma conversa individual com alguém do time.
/reconhecimento: escreva um elogio específico para quem entregou bem.

ESCALA E CRESCIMENTO
/diagnostico: aponte os gargalos prováveis da operação com o que eu contar.
/ideiasdereceita: gere dez formas de aumentar receita sem aumentar a equipe.
/parceria: sugira com quem eu poderia me associar para crescer mais rápido.
/nicho: ajude a encontrar o recorte de mercado onde eu tenho vantagem real.
/precificacao: questione se o meu preço está certo para o valor que eu entrego.
/expansao: mapeie o que precisa estar pronto antes de eu escalar.
/correcaoderota: aponte o que ajustar quando o projeto sai do previsto.
```
:::fim

## Parte 3 · Como Usar

O comando vai na frente, o assunto vem depois.

:::bloco
⟦botão: Copiar⟧

```
/dono vale a pena contratar mais um vendedor agora ou investir em tráfego?
```
:::fim

:::bloco
⟦botão: Copiar⟧

```
/objecao meu serviço custa 4 mil por mês e o cliente acha caro
```
:::fim

:::bloco
⟦botão: Copiar⟧

```
/reuniao [cole aqui a transcrição da call]
```
:::fim

:::bloco
⟦botão: Copiar⟧

```
/critica minha ideia é lançar um curso de IA para contadores
```
:::fim

**Dá para combinar dois.** O primeiro define o tom, o segundo define o papel:

:::bloco
⟦botão: Copiar⟧

```
/direto /dono devo demitir alguém que entrega bem mas atrasa sempre?
```
:::fim

**E dá para encadear na mesma conversa.** É aqui que fica interessante: peça `/cenarios`, escolha um dos três caminhos e emende `/planotres` para transformar aquele caminho em plano com prazo. Depois `/risco` no plano, antes de executar. Três comandos, e você saiu de uma dúvida solta para um plano testado contra o que pode dar errado.


## Parte 4 · O Ajuste que Separa Resposta Correta de Resposta Útil

Esta é a parte que quase ninguém faz, e é a que muda o resultado.

O bloco da Parte 2 funciona genérico. Ele fica muito melhor se você acrescentar, logo abaixo dele nas instruções do Projeto, um contexto curto sobre o seu negócio:

:::bloco
contexto do negócio — Projeto⟦botão: Copiar⟧

```
CONTEXTO DO MEU NEGÓCIO
O que eu faço:
Para quem eu vendo:
O que eu vendo e por quanto:
Meu diferencial real:
O que eu mais escuto de objeção:
```
:::fim

Preencha com honestidade, em uma linha cada. Com isso no lugar, `/objecao` para de listar objeção de manual e passa a listar a objeção que o seu cliente faz de verdade. `/preco` passa a falar do seu preço. `/diagnostico` passa a olhar a sua operação.

Cinco minutos aqui valem mais do que os 56 comandos sozinhos.

## Quando Não Funcionar

**Digitei o comando e ele respondeu qualquer coisa.** Você provavelmente está numa conversa fora do Projeto. Confira se o nome do Projeto aparece no topo da tela.

**Ele entendeu, mas respondeu diferente do que eu queria.** Edite a linha daquele comando dentro do bloco. O texto é seu e foi feito para ser mexido. Se `/direto` ainda vier longo, troque a linha por algo mais duro, como "responda em no máximo três frases, sem exceção".

**Quero criar os meus.** Siga o mesmo formato: barra, nome sem espaço e sem acento, dois pontos, e a instrução em uma linha. Acrescente no bloco e salve. Acento no nome do comando quebra o reconhecimento, por isso nenhum dos 56 tem.

**Ficou bom demais em uma resposta e quero repetir.** Peça ao Claude para transformar aquilo em um comando novo: "escreve a linha de comando que reproduz o que você acabou de fazer".

## O Próximo Passo

Instale o bloco, preencha o contexto da Parte 4 e use três comandos hoje. Sugiro estes, nesta ordem, porque eles se encadeiam: `/diagnostico` na sua operação, `/priorize` no que ele apontar, e `/planotres` no primeiro item da lista.

Me responde nesta mesma conversa dizendo **qual comando você mais usou** e qual não funcionou como esperava. Eu leio todas. É com essas respostas que eu descubro quais comandos valem virar padrão e quais precisam ser reescritos, e é assim que essa lista melhora.

E se ao instalar você perceber que metade dos comandos não serve para a sua operação, isso é informação boa, não problema. Significa que o seu gargalo está em outro lugar, e aí a conversa deixa de ser sobre atalho de IA e passa a ser sobre qual processo seu precisa existir antes.

---

## POST 35 — O Claude posta em todo lugar pra mim

- URL: `/blog/claude-posta`
- Template: padrão (hero + artigo 720px)
- Categoria: CONTEÚDO & IA
- Data no card: 25 Ago 2026 | Data na página: 25 de agosto de 2026
- Tempo de leitura: 16 min (página: "16 min de leitura")
- Resumo do card: O motor de conteúdo completo com Claude: 7 passos, do briefing de uma ideia até a métrica que vira pauta da semana seguinte, com o prompt pronto pra cada etapa, calendário semanal e um dashboard opcional em Claude Code.
- Meta description: O motor de conteúdo completo com Claude: 7 passos, do briefing de uma ideia até a métrica que vira pauta da semana seguinte, com o prompt pronto pra cada etapa, calendário semanal e um dashboard opcional em Claude Code.
- Título da aba: O Claude Posta em Todo Lugar pra Mim | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01O Fluxo de 7 Passos · 02Passo 1 — Uma Ideia, Extraída até o Fim · 03Passo 2 — O Conteúdo Mestre · 04Passo 3 — Uma Mensagem, Todas as Plataformas · 05Passo 4 — O Formato Nativo de Cada Rede · 06Passo 5 — O Calendário Semanal · 07Passo 6 — Publicar de Verdade · 08Passo 7 — Ensinar o Claude o que Funcionou · 09Por Que Isso Funciona: o Loop · 10O Briefing Diário · 11Como Montar Isso em 20 Minutos · 12Opcional: Um Dashboard com Claude Code · 13O Prompt Tudo-em-Um · 14Checklist Rápido

### Corpo do post (conteúdo exato, na ordem da página)

Criar conteúdo para várias redes sociais costuma parecer um trabalho infinito. Uma ideia precisa virar texto, vídeo, carrossel, e-mail, stories e publicações adaptadas para cada canal.

O problema não é publicar em muitos lugares. O problema é tratar cada lugar como se exigisse uma ideia nova.

Aqui está o motor completo que resolve isso: um fluxo de 7 passos, do briefing de uma ideia bruta até a métrica que vira pauta da semana seguinte. Cada passo tem o prompt pronto pra copiar.

Uma ideia entra. Todas as plataformas recebem uma versão feita pra elas — não uma cópia colada em série.

## O Fluxo de 7 Passos

Em vez de criar conteúdo do zero pra cada rede, você parte de UMA ideia forte. O Claude transforma essa ideia numa versão pensada pro comportamento real de cada plataforma — não num clone copiado e colado.

:::bloco
o fluxo⟦botão: Copiar⟧

```
IDEIA → ESCREVA → ADAPTE → FORMATE → AGENDE → PUBLIQUE → MEÇA
```
:::fim

Na prática, essa mesma ideia pode virar:

| Plataforma | Formato |
| --- | --- |
| 📸 Instagram | Carrossel / Reel |
| 🎵 TikTok | Vídeo curto |
| ▶️ YouTube | Shorts |
| ✖️ X | Thread |
| 💼 LinkedIn | Post |
| 🧵 Threads | Post |
| 👍 Facebook | Post |
| 📌 Pinterest | Pin |
| 👽 Reddit | Post de discussão |
| ✉️ E-mail | Newsletter |

## Passo 1 — Uma Ideia, Extraída até o Fim

Antes de escrever qualquer coisa, o Claude precisa extrair tudo que uma ideia bruta pode gerar: ganchos, pontos-chave, ângulos de história, o público certo e a chamada para ação.

:::bloco
prompt — briefing de conteúdo⟦botão: Copiar⟧

```
Você é meu estrategista de conteúdo.

Aqui está minha ideia:

TEMA: [tema]
PÚBLICO: [público]
OBJETIVO: [objetivo]
OFERTA: [oferta, se houver]
CTA: [ação que quero que a pessoa tome]

Transforme isso num briefing de conteúdo completo. Devolva:

IDEIA CENTRAL:
PARA QUEM É:
PROBLEMA PRINCIPAL:
PROMESSA PRINCIPAL:
10 GANCHOS:
5 ÂNGULOS DE HISTÓRIA:
PONTOS-CHAVE:
EXEMPLOS RELEVANTES:
OBJEÇÕES:
CTA:
MELHORES FORMATOS PRA ESSE CONTEÚDO:

Seja específico e direto. Nada de linguagem genérica de "conteúdo de IA".
```
:::fim

## Passo 2 — O Conteúdo Mestre

Antes de tocar em qualquer plataforma, o Claude escreve UMA peça de conteúdo mestre, de alta qualidade. Acerte a mensagem central uma vez, depois reaproveite em todo lugar.

:::bloco
prompt — conteúdo mestre⟦botão: Copiar⟧

```
Você é meu redator de conteúdo mestre.

Com base no briefing abaixo, escreva UMA peça de conteúdo mestre, com qualidade alta, antes de pensar em qualquer plataforma específica:

GANCHO:
ABERTURA:
HISTÓRIA OU EXPLICAÇÃO PRINCIPAL:
PONTO-CHAVE 1:
PONTO-CHAVE 2:
PONTO-CHAVE 3:
EXEMPLO:
CONCLUSÃO:
CTA:

Devolva também:
5 FRASES CURTAS PRA CITAR
5 PRINCIPAIS APRENDIZADOS
3 GANCHOS ALTERNATIVOS
1 RESUMO CURTO

Não escreva ainda pensando em uma plataforma. O objetivo aqui é deixar a mensagem central forte antes de adaptar.

[Cole aqui o briefing do Passo 1]
```
:::fim

## Passo 3 — Uma Mensagem, Todas as Plataformas

:::bloco
prompt — adaptar pras plataformas⟦botão: Copiar⟧

```
Você é meu motor de adaptação de conteúdo.

Pegue o conteúdo mestre abaixo e adapte pra:

1. Carrossel de Instagram
2. Reel de Instagram
3. TikTok
4. YouTube Shorts
5. Thread no X
6. Post no LinkedIn
7. Post no Threads
8. Post no Facebook
9. Pin no Pinterest
10. Post de discussão no Reddit
11. Newsletter por e-mail

Importante: não copie e cole a mesma mensagem. Mude estrutura, tamanho, gancho, tom e CTA pra cada plataforma funcionar de verdade nela.

Para cada plataforma, devolva:

PLATAFORMA:
FORMATO:
GANCHO:
CONTEÚDO:
CTA:

Mantenha a mensagem central igual, mas deixe a execução nativa de cada rede.

[Cole aqui o conteúdo mestre do Passo 2]
```
:::fim

## Passo 4 — O Formato Nativo de Cada Rede

Cada rede tem uma estrutura que funciona melhor nela. Use isso como referência antes de aprovar qualquer versão:

| Rede | Estrutura |
| --- | --- |
| 📸 Carrossel de Instagram | Slide de gancho → Slides de valor → Conclusão → CTA |
| 🎵 Reel / TikTok / Shorts | Gancho de 0–2s → Problema → Valor → Recompensa → CTA |
| ✖️ X | Gancho de abertura → Thread curta → Final forte |
| 💼 LinkedIn | Contexto/história → Insight → Conclusão → Pergunta/CTA |
| 🧵 Threads | Post curto e conversacional |
| 📌 Pinterest | Título forte → Ideia visual → Descrição |
| 👽 Reddit | Discussão primeiro → Útil → Sem oferta forçada |
| ✉️ E-mail | Assunto → Preview → Abertura → Valor → CTA |

:::bloco
prompt — ajustar pro formato nativo⟦botão: Copiar⟧

```
Reescreva cada versão de plataforma no formato nativo certo.

Não deixe todas as plataformas soarem iguais. Otimize pra leitura e pro comportamento natural de cada rede.
```
:::fim


## Passo 5 — O Calendário Semanal

| Dia | Foco |
| --- | --- |
| Segunda | LinkedIn + X |
| Terça | Instagram |
| Quarta | TikTok + YouTube Shorts |
| Quinta | Threads + Facebook |
| Sexta | E-mail + Reddit |
| Sábado | Pinterest |
| Domingo | Analisar + planejar a próxima semana |

:::bloco
prompt — calendário de 7 dias⟦botão: Copiar⟧

```
Você é meu planejador de calendário de conteúdo.

Com o conteúdo criado abaixo, monte uma agenda de publicação pros próximos 7 dias.

Para cada dia, inclua:

DIA:
PLATAFORMA:
FORMATO:
POST:
HORÁRIO:
OBJETIVO:

Não publique tudo de uma vez. Distribua o conteúdo de forma lógica ao longo da semana. Mantenha a agenda realista e fácil de manter.

[Cole aqui as versões de plataforma do Passo 3]
```
:::fim

## Passo 6 — Publicar de Verdade

Existem dois caminhos, e nenhum dos dois exige o Claude publicando direto:

- →**Caminho manual:** o Claude prepara tudo. Você publica ou agenda, plataforma por plataforma.
- →**Caminho automatizado:** o Claude prepara o conteúdo. Uma ferramenta de automação ou agendamento separada envia o conteúdo aprovado pras plataformas que realmente suportam isso.

| Categoria | Exemplos |
| --- | --- |
| Banco de conteúdo | Notion / Airtable / Google Sheets |
| Automação | n8n / Make / Zapier |
| Agendamento | uma ferramenta de agendamento de redes sociais que você já use |

O Claude não publica direto em cada plataforma. Sempre confira as regras de API, permissões, suporte à publicação e limites de taxa de cada rede antes de automatizar qualquer coisa. Nunca tente furar a regra de uma plataforma pra forçar uma publicação passar.

## Passo 7 — Ensinar o Claude o que Funcionou

Métricas pra acompanhar:

- →Visualizações
- →Tempo de exibição
- →Curtidas
- →Comentários
- →Salvamentos
- →Compartilhamentos
- →Cliques
- →Leads

:::bloco
prompt — análise de performance⟦botão: Copiar⟧

```
Você é meu analista de conteúdo.

Analise os dados de performance que vou te passar.

Devolva:

MELHOR GANCHO:
MELHOR POST:
MELHOR PLATAFORMA:
MELHOR FORMATO:
MAIS SALVO:
MAIS COMPARTILHADO:
MAIS CLICADO:
O QUE TEVE DESEMPENHO BAIXO:
POR QUE PODE TER ACONTECIDO:
3 PADRÕES QUE VOCÊ NOTA:
5 COISAS PRA TESTAR NA PRÓXIMA SEMANA:
PRIORIDADES DE CONTEÚDO PRA PRÓXIMA SEMANA:

Use só os dados que eu passar. Não invente métrica.

[Cole aqui seus números da semana]
```
:::fim

## Por Que Isso Funciona: o Loop

:::bloco
o loop completo⟦botão: Copiar⟧

```
IDEIA → ESCREVA → ADAPTE → FORMATE → AGENDE → PUBLIQUE → MEÇA → APRENDA → NOVA IDEIA
```
:::fim

O sistema funciona porque os dados de performance de cada semana moldam a pauta da semana seguinte. Não é uma entrega única de conteúdo — é um loop que composta.

## O Briefing Diário

Rode isso toda manhã pra saber exatamente no que trabalhar:

:::bloco
prompt — briefing do dia⟦botão: Copiar⟧

```
Você é meu gestor de conteúdo do dia a dia.

Revise meu sistema de conteúdo atual.

Devolva:

BRIEFING DE HOJE

POSTS QUE SAEM HOJE:
CONTEÚDO QUE AINDA PRECISO CRIAR:
MELHOR PLATAFORMA DE HOJE:
MELHOR GANCHO RECENTE:
CONTEÚDO QUE DÁ PRA REAPROVEITAR:
COMENTÁRIOS OU PERGUNTAS QUE PODEM VIRAR CONTEÚDO:
O QUE TESTAR HOJE:
TOP 3 AÇÕES:

Mantenha curto e direto ao ponto.
```
:::fim

## Como Montar Isso em 20 Minutos

1. 1.Abra o Claude
2. 2.Crie um Project chamado "MOTOR DE CONTEÚDO"
3. 3.Adicione o seu tom de voz
4. 4.Adicione o seu público
5. 5.Adicione as suas ofertas
6. 6.Salve os prompts mestres deste guia
7. 7.Crie um briefing de conteúdo
8. 8.Crie o conteúdo mestre
9. 9.Adapte pras plataformas
10. 10.Monte o calendário semanal
11. 11.Publique manualmente ou via agendador
12. 12.Devolva os dados de performance pro Claude

## Opcional: Um Dashboard com Claude Code

Se você quer um lugar visual pra esse sistema em vez de rodar prompt por prompt, passe isto pro Claude Code:

:::bloco
prompt — dashboard com Claude Code⟦botão: Copiar⟧

```
Monte um dashboard local de gestão de conteúdo chamado:

MOTOR DE CONTEÚDO

Crie estes módulos:
IDEIAS, CONTEÚDO MESTRE, INSTAGRAM, TIKTOK, YOUTUBE, X,
LINKEDIN, THREADS, FACEBOOK, PINTEREST, REDDIT, E-MAIL,
CALENDÁRIO, ANALYTICS

O fluxo de trabalho deve ser:
IDEIA → ESCREVA → ADAPTE → FORMATE → AGENDE → PUBLIQUE → MEÇA

Design: fundo claro, tipografia escura, acentos em gradiente
(azul / roxo / rosa / laranja), estética moderna de SaaS de IA,
cards arredondados, visual limpo, layout responsivo.

Funcionalidades:
- Criar nova ideia
- Guardar o conteúdo mestre
- Gerar as versões por plataforma
- Pré-visualizar cada formato
- Calendário semanal
- Status: RASCUNHO / PRONTO / AGENDADO / PUBLICADO

Seção de analytics:
Visualizações, Comentários, Salvamentos, Cliques, Compartilhamentos

Use dados de exemplo no início. Deixe claro que são dados de exemplo.

Crie placeholders de integração pra:
API do Claude, agendador de redes sociais, fontes de analytics

Guarde as chaves de API em variáveis de ambiente.
Não exponha chave nenhuma no código do frontend.

Crie um README explicando como rodar o projeto localmente.
```
:::fim

## O Prompt Tudo-em-Um

Pra pular a execução passo a passo: cole isto uma vez, com seus dados preenchidos, e receba o fluxo inteiro numa resposta só.

:::bloco
prompt — motor de conteúdo completo⟦botão: Copiar⟧

```
Você é meu Motor de Conteúdo com Claude.

Aqui estão meus dados:

TEMA:
PÚBLICO:
OFERTA:
OBJETIVO:
CTA:

Seguindo o fluxo IDEIA → ESCREVA → ADAPTE → FORMATE → AGENDE,
devolva cada um dos itens abaixo, em ordem:

1. BRIEFING DE CONTEÚDO
2. CONTEÚDO MESTRE
3. VERSÃO PARA INSTAGRAM
4. VERSÃO PARA TIKTOK
5. VERSÃO PARA YOUTUBE
6. VERSÃO PARA X
7. VERSÃO PARA LINKEDIN
8. VERSÃO PARA THREADS
9. VERSÃO PARA FACEBOOK
10. VERSÃO PARA PINTEREST
11. VERSÃO PARA REDDIT
12. VERSÃO PARA E-MAIL
13. CALENDÁRIO SEMANAL

Identifique cada seção com clareza, pra dar pra copiar cada
parte separadamente.
```
:::fim

## Checklist Rápido

- Escolhi um tópico
- Montei o briefing de conteúdo
- Criei o conteúdo mestre
- Adaptei pras plataformas
- Formatei cada versão pro jeito nativo da rede
- Montei o calendário semanal
- Publiquei
- Acompanhei os resultados
- Devolvi os dados de performance pro Claude
- Criei o plano de conteúdo da próxima semana

Conteúdo para várias redes não precisa nascer oito vezes. Ele precisa de uma ideia clara, um processo de adaptação e uma rotina de publicação — repetida toda semana.

---

## POST 36 — 30 comandos para criar imagens incríveis no ChatGPT

- URL: `/blog/imagens-chatgpt`
- Template: padrão (hero + artigo 720px)
- Categoria: CHATGPT & DESIGN
- Data no card: 25 Ago 2026 | Data na página: 25 de agosto de 2026
- Tempo de leitura: 15 min (página: "15 min de leitura")
- Resumo do card: 30 comandos-atalho para criar imagens no ChatGPT, com o prompt completo por trás de cada um — publicidade, produto, social, 3D e infográficos, prontos pra copiar e colar.
- Meta description: 30 comandos-atalho para criar imagens no ChatGPT, com o prompt completo por trás de cada um — publicidade, produto, social, 3D e infográficos, prontos pra copiar e colar.
- Título da aba: 30 Comandos para Criar Imagens Incríveis no ChatGPT | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Como Usar · 02Publicidade · 03Produto · 04Social · 053D / Wow · 06Design / Explicação · 07Como Melhorar Qualquer Resultado

### Corpo do post (conteúdo exato, na ordem da página)

Você provavelmente já viu vídeos mostrando pessoas digitando comandos como `/metaads`, `/blueprint` ou `/toyfigure` no ChatGPT e recebendo imagens completamente diferentes em segundos.

Só existe um detalhe importante: esses comandos não existem oficialmente no ChatGPT. Eles funcionam como atalhos para prompts.

Ou seja: em vez de decorar uma instrução enorme dizendo exatamente como a imagem deve ser criada, você associa aquele resultado a um nome fácil de lembrar. Neste material você vai encontrar 30 desses comandos, separados por categoria, junto com o prompt que realmente gera cada resultado.

## Como Usar

O processo é simples:

1. 1.Escolha o resultado que quer criar.
2. 2.Copie o prompt correspondente.
3. 3.Substitua as informações entre [colchetes].
4. 4.Anexe sua imagem original quando necessário.
5. 5.Cole tudo no ChatGPT e gere a imagem.

Você também pode continuar ajustando a imagem dentro da mesma conversa. Por exemplo:

- →"Mantenha tudo igual, mas deixe o fundo branco."
- →"Troque o título para PROMOÇÃO DE INVERNO."
- →"Faça agora no formato 9:16."
- →"Retire o texto e mantenha apenas o produto."
- →"Crie outra variação seguindo a mesma identidade."

:::bloco
## Publicidade

:::bloco
### `/metaads`

**O que faz:** transforma uma foto simples de produto em uma campanha publicitária pronta para Meta Ads.

:::bloco
/metaads⟦botão: Copiar⟧

```
Analise a imagem do produto anexado e crie uma campanha visual profissional para Meta Ads.
Mantenha o produto fiel à imagem original, preservando formato, embalagem, cores, logotipo e características importantes.
Crie uma composição publicitária premium contendo:
- produto como elemento principal;
- headline curta e de alto impacto;
- benefício principal claramente destacado;
- elementos gráficos relacionados ao produto;
- iluminação publicitária profissional;
- contraste forte;
- hierarquia visual clara;
- composição pensada para leitura rápida no celular.

Marca: [MARCA]
Produto: [PRODUTO]
Oferta ou benefício principal: [OFERTA]
Headline: "[TEXTO]"
CTA: "[CTA]"
Identidade visual: [CORES / ESTILO]
Formato: 4:5, pensado para anúncios no Instagram e Facebook.
Não altere características importantes do produto original.
```
:::fim
:::fim

:::bloco
### `/productcampaign`

**O que faz:** cria várias peças de campanha a partir de uma única fotografia.

:::bloco
/productcampaign⟦botão: Copiar⟧

```
Use a imagem anexada como referência principal e transforme esse produto em uma campanha publicitária completa.
Crie uma apresentação contendo diferentes direções criativas para o mesmo produto:
1. anúncio hero;
2. produto em uso;
3. composição focada em benefício;
4. composição lifestyle;
5. anúncio minimalista;
6. anúncio promocional.

Todas as peças devem compartilhar a mesma identidade visual e parecer parte da mesma campanha.

Produto: [PRODUTO]
Marca: [MARCA]
Público: [PÚBLICO]
Conceito da campanha: [CONCEITO]
Paleta: [CORES]
Mantenha embalagem, logotipo e características físicas fiéis à referência.
```
:::fim
:::fim

:::bloco
### `/offer`

**O que faz:** transforma uma oferta em um anúncio visual.

:::bloco
/offer⟦botão: Copiar⟧

```
Crie um anúncio de resposta direta extremamente claro para esta oferta:

Produto/serviço: [PRODUTO]
Oferta: [OFERTA]
Benefício principal: [BENEFÍCIO]
Headline: "[HEADLINE]"
CTA: "[CTA]"

A peça deve possuir forte hierarquia visual.
Prioridade de leitura:
1. benefício;
2. produto;
3. oferta;
4. CTA.

Visual moderno, comercial e profissional, evitando aparência de template barato.
Formato 4:5.
```
:::fim
:::fim

:::bloco
### `/launch`

**O que faz:** cria um pôster de lançamento.

:::bloco
/launch⟦botão: Copiar⟧

```
Crie uma campanha cinematográfica de lançamento para:
[PRODUTO]

O produto deve aparecer como protagonista absoluto da composição.

Direção visual:
- iluminação dramática;
- contraste cinematográfico;
- atmosfera de lançamento;
- sensação premium;
- composição minimalista;
- profundidade;
- detalhes realistas;
- espaço negativo bem utilizado.

Texto principal:
"[TEXTO]"
Texto secundário:
"[TEXTO]"

Formato vertical 4:5.
```
:::fim
:::fim

:::bloco
### `/testimonial`

**O que faz:** transforma uma avaliação em uma peça de prova social.

:::bloco
/testimonial⟦botão: Copiar⟧

```
Crie uma peça publicitária de prova social profissional utilizando este depoimento:
"[DEPOIMENTO]"

Produto/empresa: [EMPRESA]
Resultado principal mencionado: [RESULTADO]

Organize a composição para que o depoimento seja o elemento principal, acompanhado pelo produto ou pela marca.
Estética moderna, confiável e premium.
Evite aparência genérica de template.
Formato 4:5.
```
:::fim
:::fim

:::bloco
### `/beforeafter`

**O que faz:** cria comparações visuais de antes e depois.

:::bloco
/beforeafter⟦botão: Copiar⟧

```
Crie uma composição profissional de antes e depois mostrando:

ANTES:
[DESCRIÇÃO]
DEPOIS:
[DESCRIÇÃO]

O enquadramento, perspectiva e iluminação devem permanecer semelhantes para tornar a comparação imediatamente compreensível.
Use uma divisão visual elegante entre os dois estados.

Texto:
"ANTES"
"DEPOIS"

Formato 4:5.
```
:::fim
:::fim
:::fim

:::bloco
## Produto

:::bloco
### `/producthero`

**O que faz:** transforma uma fotografia comum em um hero shot premium.

:::bloco
/producthero⟦botão: Copiar⟧

```
Use exatamente o produto da imagem anexada como referência.
Crie um hero shot publicitário premium desse produto.
O produto deve aparecer centralizado e visualmente dominante.

Use:
- iluminação de estúdio profissional;
- sombras realistas;
- reflexos controlados;
- materiais extremamente detalhados;
- fundo sofisticado;
- profundidade fotográfica;
- acabamento de campanha internacional.

Não redesenhe a embalagem.
Preserve logotipo, cores, proporções e detalhes do produto.
Formato 4:5.
```
:::fim
:::fim

:::bloco
### `/packshot`

**O que faz:** cria fotografia comercial de catálogo.

:::bloco
/packshot⟦botão: Copiar⟧

```
Transforme o produto anexado em uma fotografia packshot profissional de estúdio.
Produto completamente isolado.
Fundo: [BRANCO / COR]
Iluminação comercial suave.
Sombra de contato realista.
Perspectiva natural.
Preserve exatamente embalagem, cores, texto, logotipo e formato do produto.
Resultado semelhante a fotografia profissional de catálogo de e-commerce.
```
:::fim
:::fim

:::bloco
### `/floatingproduct`

**O que faz:** cria produto flutuando em uma composição publicitária.

:::bloco
/floatingproduct⟦botão: Copiar⟧

```
Faça o produto anexado flutuar no centro da composição.
Ao redor dele adicione elementos relacionados ao produto:
[ELEMENTOS]

Crie sensação de movimento e profundidade.
Use iluminação publicitária, partículas, sombras e elementos em diferentes planos.
Preserve totalmente a aparência original do produto.
Estética de campanha premium.
Formato 4:5.
```
:::fim
:::fim

:::bloco
### `/luxuryproduct`

**O que faz:** transforma qualquer produto em uma campanha de luxo.

:::bloco
/luxuryproduct⟦botão: Copiar⟧

```
Crie uma fotografia publicitária de luxo utilizando o produto anexado.

Referências visuais:
- iluminação sofisticada;
- materiais premium;
- composição minimalista;
- sombras profundas;
- reflexos controlados;
- cenário elegante;
- fotografia editorial.

Paleta:
[CORES]

O produto deve parecer caro, exclusivo e desejável sem modificar suas características originais.
Formato 4:5.
```
:::fim
:::fim

:::bloco
### `/productscene`

**O que faz:** coloca um produto dentro de um ambiente realista.

:::bloco
/productscene⟦botão: Copiar⟧

```
Insira o produto anexado naturalmente nesta cena:
[DESCREVA A CENA]

O produto deve respeitar escala, perspectiva, iluminação, sombras e reflexos do ambiente.
Ele deve parecer realmente fotografado naquele local.
Não altere embalagem, formato, logotipo ou identidade visual.
```
:::fim
:::fim

:::bloco
### `/macroproduct`

**O que faz:** cria fotografia macro extremamente detalhada.

:::bloco
/macroproduct⟦botão: Copiar⟧

```
Crie uma fotografia macro cinematográfica do produto anexado.
Destaque:
[DETALHE]

Use profundidade de campo extremamente curta, textura detalhada, iluminação lateral e acabamento publicitário.
O produto continua reconhecível e fiel à referência.
```
:::fim
:::fim
:::fim

:::bloco
## Social

:::bloco
### `/reelscover`

:::bloco
/reelscover⟦botão: Copiar⟧

```
Crie uma capa vertical para Reels com leitura instantânea no celular.
Tema:
[TEMA]
Headline:
"[HEADLINE]"
Elemento principal:
[OBJETO/PESSOA]

Use headline grande, contraste forte, poucos elementos e composição que continue legível em tamanho pequeno.
Formato 9:16.
```
:::fim
:::fim

:::bloco
### `/carousel`

:::bloco
/carousel⟦botão: Copiar⟧

```
Crie a capa visual de um carrossel para Instagram.
Assunto:
[TEMA]
Headline:
"[HEADLINE]"

A imagem deve despertar curiosidade sem explicar todo o conteúdo.
Use apenas um elemento visual principal, headline grande e composição limpa.
Formato 4:5.
```
:::fim
:::fim

:::bloco
### `/thumbnail`

:::bloco
/thumbnail⟦botão: Copiar⟧

```
Crie uma thumbnail de YouTube altamente chamativa para:
[TEMA]
Texto:
"[TEXTO CURTO]"
Elemento principal:
[PESSOA/OBJETO]

Use contraste extremo, expressão visual forte, composição simples e leitura instantânea.
Evite excesso de elementos.
Formato 16:9.
```
:::fim
:::fim

:::bloco
### `/storyads`

:::bloco
/storyads⟦botão: Copiar⟧

```
Crie um anúncio vertical otimizado para Instagram Stories.
Produto:
[PRODUTO]
Headline:
"[HEADLINE]"
Benefício:
[BENEFÍCIO]
CTA:
"[CTA]"

Mantenha informações importantes longe das áreas superior e inferior ocupadas pela interface do Instagram.
Formato 9:16.
```
:::fim
:::fim

:::bloco
### `/linkedin`

:::bloco
/linkedin⟦botão: Copiar⟧

```
Crie uma peça visual profissional para LinkedIn sobre:
[TEMA]
Headline:
"[HEADLINE]"

Visual tecnológico e editorial, evitando estética excessivamente publicitária.
Formato 4:5.
```
:::fim
:::fim

:::bloco
### `/viralpost`

:::bloco
/viralpost⟦botão: Copiar⟧

```
Transforme este conceito em uma imagem para redes sociais capaz de interromper o scroll:
[CONCEITO]

Use uma metáfora visual simples e imediatamente compreensível.
Poucos elementos.
Contraste forte.
Headline opcional:
"[HEADLINE]"
Formato 4:5.
```
:::fim
:::fim

:::fim

:::bloco
## 3D / Wow

:::bloco
### `/billboard3d`

:::bloco
/billboard3d⟦botão: Copiar⟧

```
Crie uma cena hiper-realista mostrando [PRODUTO] saindo de um enorme outdoor 3D anamórfico instalado em [LOCAL].
O produto deve atravessar visualmente os limites físicos da tela.
Perspectiva dramática.
Integração realista com arquitetura, reflexos, luz ambiente e pessoas.
Sensação de publicidade urbana gigantesca.
```
:::fim
:::fim

:::bloco
### `/toyfigure`

:::bloco
/toyfigure⟦botão: Copiar⟧

```
Transforme a pessoa da imagem anexada em uma action figure colecionável dentro de uma embalagem premium.
Nome na embalagem:
"[NOME]"
Profissão:
[PROFISSÃO]
Acessórios:
[ACESSÓRIOS]

Preserve características reconhecíveis da pessoa.
A embalagem deve parecer um produto físico real fotografado em estúdio.
```
:::fim
:::fim

:::bloco
### `/miniature`

:::bloco
/miniature⟦botão: Copiar⟧

```
Transforme:
[CENA / NEGÓCIO]
em um pequeno mundo em miniatura extremamente detalhado.

Use personagens minúsculos realizando atividades relacionadas ao negócio.
Perspectiva macro.
Profundidade de campo curta.
Materiais realistas.
Estética de diorama premium.
```
:::fim
:::fim

:::bloco
### `/isometric`

:::bloco
/isometric⟦botão: Copiar⟧

```
Transforme:
[AMBIENTE / PROCESSO]
em uma cena 3D isométrica detalhada.

Mostre claramente áreas, pessoas, objetos e funcionamento do ambiente.
Iluminação suave.
Visual organizado e extremamente legível.
```
:::fim
:::fim

:::bloco
### `/glass`

:::bloco
/glass⟦botão: Copiar⟧

```
Transforme o elemento:
[OBJETO]
em uma escultura de vidro translúcido.

Use refração, reflexos, iluminação de estúdio e fundo minimalista.
Estética futurista premium.
```
:::fim
:::fim

:::bloco
### `/clay`

:::bloco
/clay⟦botão: Copiar⟧

```
Transforme:
[OBJETO / CENA]
em um render 3D monocromático estilo clay.

Sem texturas coloridas.
A forma deve ser definida apenas por geometria, luz e sombra.
Resultado semelhante a uma pré-visualização profissional de modelagem 3D.
```
:::fim
:::fim
:::fim

:::bloco
## Design / Explicação

:::bloco
### `/blueprint`

:::bloco
/blueprint⟦botão: Copiar⟧

```
Transforme:
[OBJETO]
em uma prancha técnica estilo blueprint.

Mostre:
- vista frontal;
- vista lateral;
- vista superior;
- detalhes ampliados;
- linhas de dimensão;
- linhas auxiliares;
- pequenas anotações técnicas.

Visual de desenho industrial extremamente preciso.
```
:::fim
:::fim

:::bloco
### `/exploded`

:::bloco
/exploded⟦botão: Copiar⟧

```
Crie uma vista explodida técnica de:
[PRODUTO]

Separe visualmente cada componente ao longo do eixo de montagem.
As peças devem permanecer perfeitamente alinhadas para mostrar como o produto é construído.
Fundo neutro.
Iluminação técnica.
```
:::fim
:::fim

:::bloco
### `/xray`

:::bloco
/xray⟦botão: Copiar⟧

```
Crie uma visualização em raio-X de:
[OBJETO]

Mostre simultaneamente estrutura externa translúcida e principais componentes internos.
Use diferentes níveis de transparência para facilitar a leitura.
Resultado técnico e realista.
```
:::fim
:::fim

:::bloco
### `/infographic`

:::bloco
/infographic⟦botão: Copiar⟧

```
Transforme estas informações:
[INFORMAÇÕES]
em um infográfico visual extremamente claro.

Organize o conteúdo utilizando hierarquia, ícones, números e elementos gráficos.
Paleta:
[CORES]

O conteúdo deve ser compreendido em poucos segundos.
```
:::fim
:::fim

:::bloco
### `/comparison`

:::bloco
/comparison⟦botão: Copiar⟧

```
Crie um comparativo visual entre:
[OPÇÃO A]
e
[OPÇÃO B]

Compare:
[CRITÉRIOS]

Organize as informações lado a lado com forte hierarquia visual.
Destaque visualmente as diferenças mais importantes.
```
:::fim
:::fim

:::bloco
### `/process`

:::bloco
/process⟦botão: Copiar⟧

```
Transforme este processo:
[PROCESSO]
em um mapa visual passo a passo.

Mostre etapas, conexões, decisões e caminhos alternativos quando necessário.
O fluxo deve ser compreendido da esquerda para a direita sem precisar de explicação adicional.
```
:::fim
:::fim
:::fim

## Como Melhorar Qualquer Resultado

Não trate a primeira imagem como resultado final. Depois de gerar, continue conversando com o ChatGPT. Você pode pedir:

- →"Preserve exatamente o produto e troque somente o fundo."
- →"Mantenha essa direção visual, mas faça uma versão mais minimalista."
- →"Agora adapte para 9:16 sem simplesmente cortar a imagem."
- →"Remova todo o texto."
- →"Crie três variações mantendo a mesma campanha."
- →"Deixe mais realista e menos parecido com arte de IA."

Esse processo de refinamento normalmente é tão importante quanto o primeiro prompt.

E existe uma última coisa importante: o /metaads, /blueprint ou qualquer outro nome desta biblioteca não ativa uma função secreta do ChatGPT.

O poder está no prompt que existe por trás dele. O comando serve apenas para transformar um prompt complexo em algo fácil de encontrar, lembrar e reutilizar.

---

## POST 37 — O guia real do Open Generative AI

- URL: `/blog/open-generative-ai`
- Template: padrão (hero + artigo 720px)
- Categoria: FERRAMENTAS & IA
- Data no card: 25 Ago 2026 | Data na página: 25 de agosto de 2026
- Tempo de leitura: 6 min (página: "6 min de leitura")
- Resumo do card: O que o Open Generative AI realmente é, as 3 formas de rodar (navegador, app de desktop, código fonte), como funciona a chave do Muapi.ai e o que ele NÃO é — tudo conferido direto no repositório oficial.
- Meta description: O que o Open Generative AI realmente é, as 3 formas de rodar (navegador, app de desktop, código fonte), como funciona a chave do Muapi.ai e o que ele NÃO é — tudo conferido direto no repositório oficial.
- Título da aba: O Guia Real do Open Generative AI | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01O Projeto, de Verdade · 021. Direto no Navegador · 032. App de Desktop · 043. Rodando o Código Fonte · 05Sobre a Chave e o Preço · 06O Que Ele NÃO é · 07Se Você Usa a FORJA

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar ABRE.

Tudo aqui foi conferido direto no repositório oficial em 25/08/2026, não é resumo de outro post.

## O Projeto, de Verdade

- →**Repositório:** [github.com/Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI)
- →**Licença:** MIT, código aberto, 27 mil+ estrelas.
- →**O que é:** um estúdio de criação com IA (imagem, vídeo, lip sync, cinema e mais 14 ferramentas) que roda por cima de mais de 500 modelos, sem filtro de conteúdo e sem travar seu prompt.
- →**Quem mantém:** o motor de geração é do Muapi.ai. O app em si é aberto e gratuito; o Muapi é quem conecta nos 500+ modelos por trás.

**As 3 formas reais de usar, da mais fácil pra mais técnica:**

## 1. Direto no Navegador, sem Instalar Nada

[muapi.ai/open-generative-ai](https://muapi.ai/open-generative-ai)

Cria conta gratuita e já usa todas as ferramentas (Imagem, Vídeo, Áudio, Lip Sync, Cinema, Workflows) no navegador. Essa é a opção certa pra quem quer só testar ou não quer mexer com instalação nenhuma. Fica sempre com os modelos mais novos.

## 2. App de Desktop, com Instalador Pronto

Sem terminal, sem Node.js. Baixa e instala como qualquer programa:

| Sistema | Onde baixar |
| --- | --- |
| Mac (M1/M2/M3/M4) | [Open Generative AI-1.0.9-arm64.dmg](https://github.com/Anil-matcha/Open-Generative-AI/releases/download/v1.0.9/Open.Generative.AI-1.0.9-arm64.dmg) |
| Mac (Intel) | [Open Generative AI-1.0.9.dmg](https://github.com/Anil-matcha/Open-Generative-AI/releases/download/v1.0.9/Open.Generative.AI-1.0.9.dmg) |
| Windows | [Open Generative AI Setup 1.0.9.exe](https://github.com/Anil-matcha/Open-Generative-AI/releases/download/v1.0.9/Open.Generative.AI.Setup.1.0.9.exe) |
| Linux | [lista completa de releases](https://github.com/Anil-matcha/Open-Generative-AI/releases) |

**No Mac**, como o app não é assinado pela Apple, na primeira abertura ele vai travar. Resolve assim:

1. 1.Arrasta o app pra pasta Aplicativos.
2. 2.Abre o Terminal e cola: `xattr -cr "/Applications/Open Generative AI.app"`
3. 3.Clica com o botão direito no app → Abrir → Abrir de novo na caixinha que aparecer.

Só precisa fazer isso uma vez.

**No Windows**, o SmartScreen vai avisar que o instalador não é reconhecido. Clica em "Mais informações" e depois "Executar assim mesmo".

## 3. Rodando o Código Fonte (pra Quem Já Mexe com Isso)

Pede Node.js 18 ou mais novo:

:::bloco
terminal — instalar do código fonte⟦botão: Copiar⟧

```
git clone --recurse-submodules https://github.com/Anil-matcha/Open-Generative-AI.git
cd Open-Generative-AI
npm run setup
npm run electron:dev
```
:::fim

Essa é a única opção que dá pra pedir pro Claude Code instalar e configurar por você. Se quiser esse caminho, me chama que eu te ajudo passo a passo.


## Sobre a Chave e o Preço, sem Meia Palavra

O que você precisa não é "uma chave de cada modelo" (uma da Kling, uma da Sora, etc). É **uma chave só, do Muapi**, que já dá acesso aos 500+ modelos.

1. 1.Cria a chave em: [muapi.ai/access-keys](https://muapi.ai/access-keys)
2. 2.Cola ela na primeira tela que o app pedir.

**Sem assinatura mensal fixa, isso é real.** Mas cada geração (uma imagem, um vídeo) consome crédito do Muapi, comprado conforme o uso. Ou seja: você não paga uma mensalidade pra manter a ferramenta aberta, mas também não é ilimitado de graça. É "pague pelo que gerar", que é bem diferente de $30, $50 ou $100 fixos todo mês, mas não é zero.

**Se você quer gerar sem pagar nada por geração:** o app de desktop tem um motor local (`sd.cpp`), que roda direto na sua máquina, sem internet e sem crédito, mas só com modelos mais simples (SD 1.5, SDXL, Z-Image), não os modelos badalados tipo Kling ou Sora. É a opção 100% grátis, com modelo mais básico.

Não existe chave por modelo, e não existe mensalidade fixa. Uma chave do Muapi.ai dá acesso aos 500+ modelos, e você paga por geração — ou usa o motor local de graça, com modelo mais simples.

## O Que Ele NÃO é

Não é um clone perfeito e idêntico ao Higgsfield. É um projeto open-source real, com Cinema Studio (controle de câmera, lente, abertura) parecido, mas mantido pela comunidade, então pode faltar polimento em telas específicas.

## Se Você Usa a FORJA

Rodei a régua de 6 perguntas antes de postar sobre essa ferramenta, e conferi cada dado (estrelas, licença, forma de pagar) direto na fonte antes de publicar, em vez de repetir o que o post de referência dizia.

---

## POST 38 — A FORJA: os mecanismos por trás dos 30 mil seguidores em 4 meses

- URL: `/blog/forja`
- Template: padrão (hero + artigo 720px)
- Categoria: INSTAGRAM & IA
- Data no card: 25 Ago 2026 | Data na página: 25 de agosto de 2026
- Tempo de leitura: 5 min (página: "5 min de leitura")
- Resumo do card: As 3 peças por trás da FORJA — o sistema que decide o que postar: conexão com números reais via Windsor.ai, estratégia escrita e calendário que nasce cheio. O material completo pra montar a sua versão.
- Meta description: As 3 peças por trás da FORJA — o sistema que decide o que postar: conexão com números reais via Windsor.ai, estratégia escrita e calendário que nasce cheio. O material completo pra montar a sua versão.
- Título da aba: A FORJA: os Mecanismos por Trás dos 30 Mil Seguidores em 4 Meses | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Peça 1 — Números Reais (Windsor.ai) · 02Peça 2 — A Estratégia Escrita · 03Peça 3 — O Calendário que Nasce Cheio · 04Como as 3 Peças se Conectam · 05O Próximo Passo

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar FORJA.

A FORJA não é uma ferramenta que se compra pronta. É o nome que eu dei pro sistema que decide o que eu publico, montado em cima de 3 peças: a conexão com os números reais, a estratégia escrita, e o calendário que nasce cheio.

Este material mostra as 3, com o suficiente pra você montar a sua versão.

## Peça 1 · A Conexão com os Números Reais (Windsor.ai)

Sem número, todo post é achismo. A conexão liga o Instagram ao Claude, direto, sem exportar planilha nem copiar dado na mão.

**Como montar a sua:**

1. 1.Crie uma conta gratuita no Windsor.ai e conecte o conector de Instagram (Instagram Organic/Insights). O processo é por login autorizado, nunca senha compartilhada.
2. 2.Se você usa Claude Code, adicione o servidor MCP do Windsor no seu projeto. Ele expõe ferramentas de leitura de dados que o Claude usa direto na conversa.
3. 3.Peça ao Claude, uma vez por semana: "puxe meus últimos 30 dias de posts, com alcance, salvamentos, compartilhamentos e seguidores ganhos por post, e me diga os 3 que mais converteram em seguidor."

**Sem Windsor, sem Claude Code:** a versão manual funciona igual, só dá mais trabalho. Depois de cada post, anote numa planilha: data, hook, alcance, salvos, seguidores ganhos. Em um mês você já tem dado suficiente pra ver padrão.

## Peça 2 · A Estratégia Escrita

A estratégia não é um documento que se escreve uma vez e esquece. É o que decide, antes de qualquer post, quem você fala, o que você nunca diz, e que formato carrega cada função.

**O que ela precisa ter, no mínimo:**

- →**Posicionamento:** o território que você ocupa e o "inimigo" que você combate (o jeito errado de fazer a coisa que todo mundo faz).
- →**Público:** a dor principal de quem te segue, o que essa pessoa já tentou antes de te achar, e as objeções que ela carrega.
- →**Pilares:** 3 a 5 territórios de conteúdo, cada um com um peso (a soma dá 100%). Pilar sem peso vira desculpa pra postar qualquer coisa.
- →**Vocabulário:** as palavras que você sempre usa e as que você nunca usa. É isso que faz a voz da conta ser reconhecível sem precisar ver o nome de usuário.
- →**O que nunca fazer:** tão importante quanto o que fazer. Formato, tom ou tema que você decidiu abandonar, e por quê.

**Como montar a sua:** escreva isso uma vez, revise a cada 30 dias com os números reais na mão. Se um pilar não está convertendo depois de 30 dias de teste honesto, o peso dele cai, não o pilar de quem está performando.


## Peça 3 · O Calendário que Nasce Cheio

O erro mais comum é abrir a agenda vazia toda semana e "pensar no que postar". Isso é o que mais rouba tempo e mais produz post fraco.

**A regra:** o calendário nasce cheio pro mês inteiro, na hora em que a estratégia é fechada. Cada dia já tem: o pilar, o formato, e o gancho. Escrever o post vira pegar o próximo slot e desenvolver, não decidir do zero.

**Como montar o seu:**

1. 1.Defina sua cadência real (quantos posts por dia, quantos são feed e quantos são vídeo).
2. 2.Distribua os pilares pelos dias do mês, respeitando o peso de cada um.
3. 3.Para cada slot, escreva **antes** o tema e o gancho, mesmo que rascunhado. Um slot com "carrossel, dia 15, pilar X" sem gancho ainda é um slot vazio disfarçado.
4. 4.Toda semana, escreva as peças pegando os slots já planejados, na ordem de data. Não pergunte "o que eu posto hoje": o calendário já respondeu.

## Como as 3 Peças se Conectam

Não são 3 ferramentas separadas. É um ciclo:

Os números reais mostram o que funcionou → a estratégia decide o peso de cada pilar com base nisso → o calendário nasce distribuído pelo peso certo → o próximo post entra na fila já sabendo, de antemão, que tipo de conteúdo tem mais chance de funcionar.

Cortar qualquer uma das 3 quebra o ciclo. Estratégia sem número vira opinião. Calendário sem estratégia vira lista de temas soltos. Número sem calendário vira relatório que ninguém usa pra decidir nada.

## O Próximo Passo

Me responde aqui: **das 3 peças, qual você já tem, mesmo que de forma manual e imperfeita?** É a partir dessa resposta que eu te digo qual das outras duas monta primeiro.

---

## POST 39 — Os 6 comandos que fazem o Claude render a semana inteira

- URL: `/blog/6-comandos`
- Template: padrão (hero + artigo 720px)
- Categoria: CLAUDE CODE
- Data no card: 25 Ago 2026 | Data na página: 25 de agosto de 2026
- Tempo de leitura: 7 min (página: "7 min de leitura")
- Resumo do card: Os 6 comandos do Claude Code que evitam que seu limite de uso estoure sem avisar — /context, /clear, /compact, /model, /plan e /init — com o bônus sobre CLAUDE.md vs skill.
- Meta description: Os 6 comandos do Claude Code que evitam que seu limite de uso estoure sem avisar — /context, /clear, /compact, /model, /plan e /init — com o bônus sobre CLAUDE.md vs skill.
- Título da aba: Os 6 Comandos que Fazem o Claude Render a Semana Inteira | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01/context — o diagnóstico · 02/clear — entre uma tarefa e outra · 03/compact — quando não dá pra perder o fio · 04/model — a decisão que mais pesa · 05/plan — ele planeja antes de gastar · 06/init — o contexto que fica · 07O Bônus: CLAUDE.md vs Skill · 08O Teste da Semana

### Corpo do post (conteúdo exato, na ordem da página)

Esse é o material que você recebe ao comentar TOKEN.

Seu limite não estoura porque você usa muito. Estoura porque ninguém te mostrou o que digitar.

Todos os comandos abaixo já estão instalados no Claude Code, não precisa configurar nada.

## `/context`— o diagnóstico

Mostra numa grade colorida tudo que está ocupando sua janela de contexto agora, item por item, com sugestões do que dá pra cortar. Use `/context all` para abrir o detalhamento completo.

**Comece sempre por ele.** Quase todo mundo tenta economizar no escuro e ataca a coisa errada. Rode uma vez no meio de um dia normal de trabalho e você vai descobrir o que está te custando caro, que quase nunca é o que você imagina.

## `/clear`— entre uma tarefa e outra

Começa uma conversa nova, com contexto vazio. Aliases: `/reset` e `/new`.

**Por que importa:** conversa longa relê tudo que veio antes a cada mensagem nova. A mensagem 50 custa muito mais que a mensagem 1 e ainda responde pior, porque o assunto do começo polui o do fim.

**O hábito:** terminou a tarefa, `/clear`. Sem dó. Você pode passar um nome para rotular a conversa anterior antes de limpar.

## `/compact`— quando não dá pra perder o fio

Resume a conversa e devolve a janela, mantendo o que foi decidido. É o `/clear` para quando a tarefa é longa e você precisa continuar de onde parou.

Dá para passar uma instrução de foco, dizendo o que o resumo deve preservar. Se a tarefa é um sistema sendo construído, peça para preservar as decisões de estrutura e descartar o resto.

**Quando usar:** no momento em que ele começa a esquecer algo que já foi combinado. Insistir a partir daí só piora, e cada mensagem custa mais que a anterior.


## `/model`— a decisão que mais pesa

Troca o modelo e salva como padrão para as próximas sessões. Sem argumento, abre um seletor.

**A regra dos 2 segundos:**

Se você consegue conferir a resposta batendo o olho, é tarefa de modelo intermediário. Se você vai precisar ler com atenção para saber se está certo, aí sim vale o mais forte.

| Tipo de tarefa | Modelo |
| --- | --- |
| Escrever, resumir, reescrever, organizar, responder pergunta direta | `intermediário` |
| Código de rotina, ajuste pequeno, bug conhecido | `intermediário` |
| Arquitetura, bug intermitente, decisão difícil, texto que pede julgamento fino | `o mais forte` |
| Tarefa longa e autônoma, que vai rodar sozinha por horas | `o mais forte, com escopo escrito antes` |

O erro clássico é deixar o modelo mais pesado ligado o dia inteiro e usá-lo para renomear arquivo.

## `/plan`— ele planeja antes de gastar

Entra em modo de planejamento. Você pode passar a tarefa direto:

:::bloco
exemplo — /plan⟦botão: Copiar⟧

```
/plan arrumar o cálculo de comissão da planilha de vendas
```
:::fim

Ele devolve o plano para você aprovar **antes** de executar. Custa uma resposta curta e evita refazer um trabalho longo na direção errada. É o comando que mais economiza sem você perceber, porque o que ele economiza é o retrabalho que nem chegou a acontecer.

## `/init`— o contexto que fica

Cria o `CLAUDE.md`, o arquivo que guarda o contexto do seu projeto ou negócio. Ele é lido sozinho em toda conversa, então você para de recolar o mesmo briefing.

**O que colocar:** o que é o negócio, quem é o público, seu tom de voz, as regras que você sempre repete, os caminhos importantes. O que você digitaria de novo amanhã.

**O que NÃO colocar:** material longo de referência. Isso vai para uma skill.

## O Bônus que Quase Ninguém Sabe

**O conteúdo de uma skill só entra na janela quando a skill é chamada.**

Ou seja: um documento de referência de 20 páginas dentro do `CLAUDE.md` custa contexto em toda conversa, mesmo nas que não têm nada a ver com ele. O mesmo documento dentro de uma skill custa quase nada até o dia em que você precisa dele.

A regra prática: **CLAUDE.md** é para fato curto que vale sempre. Skill é para procedimento longo que vale às vezes. Se uma seção do seu CLAUDE.md virou um passo a passo, ela já devia ser uma skill.

## O Teste da Semana

Roda os seis por uma semana e compara com a anterior. Começa pelo `/context` na segunda e roda de novo na sexta.

- /context na segunda, pra saber onde o contexto está indo
- /clear entre cada tarefa nova, sem dó
- /compact quando a tarefa é longa e ele começa a esquecer
- /model ajustado à tarefa, não ligado no mais forte o dia inteiro
- /plan antes de qualquer tarefa grande e autônoma
- /init com o que você digitaria de novo amanhã
- /context de novo na sexta, pra comparar com a segunda

Me responde aqui contando **o que o /context te mostrou que você não esperava**. É a resposta mais reveladora dessa lista, e o que mais aparecer nela vira o próximo material.

---

## POST 40 — 5 gargalos que roubam tempo da empresa, e 1 prompt para resolver cada um

- URL: `/blog/5-gargalos`
- Template: padrão (hero + artigo 720px)
- Categoria: OPERAÇÕES & IA
- Data no card: 24 Ago 2026 | Data na página: 24 de agosto de 2026
- Tempo de leitura: 6 min (página: "6 min de leitura")
- Resumo do card: 5 gargalos que roubam horas da operação toda semana — informação espalhada, pergunta repetida, aprovação sem critério, dado copiado e tarefa sem dono — com o prompt completo pra resolver cada um.
- Meta description: 5 gargalos que roubam horas da operação toda semana — informação espalhada, pergunta repetida, aprovação sem critério, dado copiado e tarefa sem dono — com o prompt completo pra resolver cada um.
- Título da aba: 5 Gargalos que Roubam Tempo da Empresa, e 1 Prompt para Resolver Cada Um | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Como Saber Qual É o Seu Gargalo · 021. Informação Espalhada · 032. Pergunta Repetida · 043. Aprovação sem Critério · 054. Dado Copiado · 065. Tarefa sem Dono · 07O Checklist da Semana

### Corpo do post (conteúdo exato, na ordem da página)

Antes de contratar mais uma ferramenta de IA, olhe para dentro. Quase toda operação perde horas por semana nos mesmos cinco pontos, e nenhum deles se resolve com ferramenta nova. Se resolvem com o gargalo nomeado e uma instrução bem escrita.

Este guia entrega os 5 prompts completos, um por gargalo. Copie um de cada vez, no Claude ou no ChatGPT, e substitua os trechos entre colchetes pelo contexto real da sua empresa.

Uma regra antes de começar: não cole dados sensíveis, dados de clientes nem senhas nos prompts abaixo.

## Como Saber Qual É o Seu Gargalo

Cada um tem um sintoma que você reconhece na hora:

1. 1.**Informação espalhada.** Alguém pergunta "onde está o arquivo?" e a resposta muda dependendo de quem responde.
2. 2.**Pergunta repetida.** Sua equipe te faz a mesma pergunta toda semana, e você responde de novo em vez de apontar para um lugar.
3. 3.**Aprovação sem critério.** Tudo para na sua mesa, até o que não precisava parar.
4. 4.**Dado copiado.** O mesmo número vive em dois lugares e uma hora eles discordam.
5. 5.**Tarefa sem dono.** "Alguém ia ver isso" e ninguém viu.

Comece pelo que mais doeu ao ler. É por ali que o tempo está vazando.

## 1. Informação Espalhada

Sintoma: Alguém pergunta "onde está o arquivo?" e a resposta muda dependendo de quem responde.

:::bloco
prompt — informação espalhada⟦botão: Copiar⟧

```
Atue como analista de processos. Organize estas informações da minha operação:
[cole aqui os canais, arquivos, planilhas e sistemas usados].

Monte uma fonte de verdade com: informação, onde ela deve ficar, quem atualiza, quando atualiza e quem pode consultar. Aponte o que hoje está duplicado ou depende da memória de uma pessoa.
```
:::fim

**O que fazer com a resposta:** a tabela que sai daqui é o mapa da sua central de informação. Escolha UM lugar para cada tipo de informação e comunique a equipe no mesmo dia. Fonte de verdade que não é anunciada não existe.

## 2. Pergunta Repetida

Sintoma: Sua equipe te faz a mesma pergunta toda semana, e você responde de novo em vez de apontar para um lugar.

:::bloco
prompt — pergunta repetida⟦botão: Copiar⟧

```
Atue como analista de atendimento interno. Agrupe estas perguntas que minha equipe repete:
[cole aqui as perguntas ou conversas sem dados sensíveis].

Crie uma base de respostas-padrão. Para cada resposta, diga quando usá-la, onde a equipe deve encontrá-la e quando a pergunta precisa subir para uma pessoa responsável.
```
:::fim

**O que fazer com a resposta:** salve a base num lugar que a equipe já abre todo dia. A partir daí, quando a pergunta vier, responda com o link, não com o texto. Duas semanas disso e a pergunta para de chegar.

## 3. Aprovação sem Critério

Sintoma: Tudo para na sua mesa, até o que não precisava parar.

:::bloco
prompt — aprovação sem critério⟦botão: Copiar⟧

```
Atue como desenhista de processo. Para esta decisão recorrente:
[descreva a decisão e os casos que geram dúvida].

Crie regras de aprovação com três partes: o que pode ser decidido pela equipe, quais são as exceções e quem decide cada exceção. Entregue em formato de checklist simples.
```
:::fim

**O que fazer com a resposta:** o checklist vira a alçada oficial. O ganho não é só o seu tempo: a equipe decide mais rápido porque sabe exatamente onde a autonomia dela termina.


## 4. Dado Copiado

Sintoma: O mesmo número vive em dois lugares e uma hora eles discordam.

:::bloco
prompt — dado copiado⟦botão: Copiar⟧

```
Compare estas versões do mesmo dado:
[cole versões sem dados sensíveis].

Liste as divergências, os riscos de usar cada versão e defina uma fonte principal. Depois, proponha um fluxo simples para atualizar esse dado uma vez e distribuir a mudança sem cópias manuais.
```
:::fim

**O que fazer com a resposta:** eleja a fonte vencedora e marque as outras como leitura. Quem edita cópia cria a próxima divergência.

## 5. Tarefa sem Dono

Sintoma: "Alguém ia ver isso" e ninguém viu.

:::bloco
prompt — tarefa sem dono⟦botão: Copiar⟧

```
Para esta tarefa recorrente:
[descreva a tarefa, quem participa e o resultado esperado].

Defina responsável, prazo, próxima ação, condição de conclusão e quando o problema deve ser escalado. Mostre em uma tabela curta que a equipe consiga usar todos os dias.
```
:::fim

**O que fazer com a resposta:** a tabela só funciona se tiver UM nome por linha. "Time comercial" não é dono. Dono tem nome e sabe que é dono.

Os 5 gargalos têm algo em comum: nenhum se resolve comprando ferramenta nova. Se resolvem nomeando o gargalo certo e escrevendo a instrução certa — o resto é disciplina de manter o documento vivo.

## O Checklist da Semana

- Rodei o prompt do gargalo que mais doeu
- A resposta virou um documento com lugar fixo
- A equipe foi avisada onde esse documento mora
- Defini quem atualiza e quando
- Marquei na agenda a revisão em 30 dias

Se você rodou um desses prompts e a resposta expôs mais bagunça do que você esperava, isso é normal. É o sinal de que o problema nunca foi a falta de ferramenta.

Me responde na DM contando **qual dos 5 gargalos apareceu primeiro** na sua operação. É a partir dessa resposta que eu consigo te apontar o que organizar antes de colocar qualquer IA para rodar.

---

## POST 41 — Criei 18 agentes para cuidar do meu conteúdo. Veja o raciocínio por trás.

- URL: `/blog/18-agentes`
- Template: padrão (hero + artigo 720px)
- Categoria: CONTEÚDO & IA
- Data no card: 22 Ago 2026 | Data na página: 22 de agosto de 2026
- Tempo de leitura: 5 min (página: "5 min de leitura")
- Resumo do card: O raciocínio por trás de um sistema de 18 agentes para conteúdo: centralizar a informação do negócio, montar um projeto com papéis separados em vez de um chat só, e usar o mesmo motor além do Instagram.
- Meta description: O raciocínio por trás de um sistema de 18 agentes para conteúdo: centralizar a informação do negócio, montar um projeto com papéis separados em vez de um chat só, e usar o mesmo motor além do Instagram.
- Título da aba: Criei 18 Agentes para Cuidar do Meu Conteúdo. Veja o Raciocínio por Trás | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Passo 1. Centralize as informações · 02Passo 2. Crie um projeto, não um chat · 03Passo 3. Não trave no Instagram · 04Quer ver os 18 agentes por dentro

### Corpo do post (conteúdo exato, na ordem da página)

Se você viu o carrossel, já sabe a provocação: não é mais um chat que responde perguntas soltas sobre conteúdo. É um sistema, com um papel definido para cada etapa, do jeito que uma equipe de verdade funcionaria.

Não vou entregar aqui o funcionamento interno completo. Os 18 agentes, a ordem entre eles e os arquivos que cada um lê e escreve são a estrutura da FORJA, o produto que estou construindo em cima dessa lógica. Mas o raciocínio de fundo não é segredo nenhum, e ele funciona em qualquer escala. Se você quiser montar sua própria versão, ainda que bem menor, o caminho é este.

## Passo 1. Centralize as informações antes de pedir qualquer conteúdo

A maior parte dos chats de conteúdo falha porque começa do zero toda vez. Você explica seu negócio de novo, seu público de novo, seu tom de novo, e no fim recebe uma ideia genérica porque a IA nunca teve contexto suficiente para ser específica.

O primeiro passo não é escrever post. É criar uma pasta, física ou dentro do seu sistema, e colocar ali tudo que descreve seu negócio: quem você atende, qual dor resolve, que provas reais você tem, que tom você usa, o que já funcionou antes. Isso vira a fonte que qualquer conteúdo futuro vai consultar. Sem esse ponto central de informação, cada conversa recomeça do nada, e o resultado sempre soa com a cara de ninguém.

## Passo 2. Crie um projeto, não um chat

Com a informação organizada num lugar só, o erro comum é continuar tratando a IA como uma caixa de perguntas e respostas. Um chat genérico tenta fazer pesquisa, ideia, texto e revisão na mesma resposta, e cada etapa sai mais rasa por isso.

O que muda o resultado é transformar aquilo num projeto com papéis separados. Um passo pesquisa o mercado. Outro transforma isso em tema. Outro cria o ângulo e o gancho. Outro escreve. Outro revisa antes de publicar. Cada etapa recebe só o contexto que precisa para fazer bem uma coisa, e entrega pronto para a próxima. É a diferença entre pedir "me dá uma ideia de post" e ter um sistema que já sabe de onde tirar a ideia, por que ela importa agora e qual formato ela deveria virar.

## Passo 3. Não trave no Instagram

Uma vez que o motor existe, ele não serve só para carrossel. O mesmo raciocínio, negócio centralizado alimentando papéis especializados, escreve roteiro de vídeo, sequência de stories, resposta de direct e, sim, texto de blog como este que você está lendo agora.

A pergunta certa não é "que ferramenta de IA eu uso para postar mais". É "que sistema eu construo para que cada etapa do conteúdo tenha contexto de verdade". Resolvido isso, o formato final é só a saída.

## Quer ver os 18 agentes por dentro

Esse texto explicou o raciocínio. A estrutura completa, com os 18 papéis, a ordem entre eles e o painel que mostra tudo funcionando junto, é o que estou construindo dentro da FORJA.

:::bloco
Acompanhe de perto no canal do WhatsApp

Quem quiser acompanhar de perto, entra no canal do WhatsApp onde eu falo sobre esse projeto.

[⟦botão: Entrar no canal da FORJA →⟧](https://whatsapp.com/channel/0029VbDWPTpHwXbLtfL7Ma38)
:::fim

---

## POST 42 — Como criar 30 dias de conteúdo para Instagram com um prompt no Claude

- URL: `/blog/30-dias-instagram`
- Template: padrão (hero + artigo 720px)
- Categoria: CONTEÚDO & IA
- Data no card: 19 Ago 2026 | Data na página: 19 de agosto de 2026
- Tempo de leitura: 5 min (página: "5 min de leitura")
- Resumo do card: O prompt que entende seu negócio em 5 perguntas e monta um calendário de 30 ideias de Reels e carrosséis — mais os prompts extras para filtrar as melhores pautas e transformar uma ideia em roteiro de Reel.
- Meta description: O prompt que entende seu negócio em 5 perguntas e monta um calendário de 30 ideias de Reels e carrosséis — mais os prompts extras para filtrar as melhores pautas e transformar uma ideia em roteiro de Reel.
- Título da aba: Como Criar 30 Dias de Conteúdo para Instagram com Um Prompt no Claude | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01O Prompt Principal — 30 Dias de Conteúdo · 02Como Usar · 03Prompt Extra — Escolher as Melhores Pautas · 04Prompt Extra — Transformar uma Pauta em Reel

### Corpo do post (conteúdo exato, na ordem da página)

Tela em branco não é falta de criatividade. É falta de processo.

Este prompt resolve os 30 primeiros dias de uma vez: ele começa entendendo seu negócio de verdade — nada de "poste todo dia" — e devolve um calendário completo, com hook, formato, roteiro curto e CTA para cada ideia.

## O Prompt Principal — 30 Dias de Conteúdo

Copie o prompt abaixo no Claude. Ele começa entendendo seu negócio e depois monta um calendário de 30 ideias.

:::bloco
prompt — 30 dias de conteúdo⟦botão: Copiar⟧

```
Você é estrategista de conteúdo para Instagram.

Antes de criar qualquer ideia, me faça 5 perguntas: nicho, oferta, cliente ideal, provas reais e tom de voz.

Depois das minhas respostas, crie 30 ideias de conteúdo para atrair esse público e gerar interesse na minha oferta.

Misture Reels e carrosséis. Para cada ideia, traga tema, hook, formato, roteiro curto e CTA.

Fuja de ideias genéricas, repetidas e sem opinião. Organize tudo em tabela.
```
:::fim

As 5 perguntas não são burocracia. É o que impede o Claude de devolver ideias que servem pra qualquer perfil do Instagram — quanto mais real for sua resposta, mais específica fica a pauta.

## Como Usar

1. 1.Cole o prompt no Claude.
2. 2.Responda às cinco perguntas com exemplos reais do seu negócio.
3. 3.Salve a tabela e escolha as ideias que você realmente teria vontade de defender.

:::bloco
Isso aqui é só a ponta do Forja.

Entra no grupo de aquecimento do Forja — nosso sistema de criação de conteúdo — pra entender como gerenciar todo o seu conteúdo usando inteligência artificial, direto dos bastidores da operação da NX Digital.

[⟦botão: Entrar no grupo do Forja⟧](https://whatsapp.com/channel/0029VbDWPTpHwXbLtfL7Ma38)
:::fim

## Prompt Extra: Escolher as Melhores Pautas

Trinta ideias na mesa é bom. Trinta ideias publicadas sem critério é ruído. Use este prompt logo depois do primeiro pra filtrar o que realmente merece virar post:

:::bloco
prompt extra — filtrar as melhores pautas⟦botão: Copiar⟧

```
Das 30 ideias, escolha as 10 com maior chance de gerar comentário, salvamento ou compartilhamento para o meu público.

Explique em uma frase por que cada uma merece entrar no calendário. Não escolha ideias parecidas entre si.
```
:::fim

## Prompt Extra: Transformar uma Pauta em Reel

Com as 10 pautas escolhidas, é hora de tirar uma do papel. Este prompt pega uma ideia da tabela e devolve um roteiro pronto pra gravar:

:::bloco
prompt extra — pauta vira Reel⟦botão: Copiar⟧

```
Transforme a ideia número [X] em um Reel de até 45 segundos.

Crie: hook para os primeiros 2 segundos, roteiro falado em blocos curtos, sugestão de cenas e CTA final.

O texto precisa soar como uma pessoa falando, sem frases genéricas de marketing.
```
:::fim

Repita esse último prompt pra cada ideia que for gravar. É o mesmo processo, ideia por ideia, sem precisar reescrever o contexto do zero toda vez.

- Respondi as 5 perguntas com exemplos reais do meu negócio, não genéricos
- Escolhi as pautas que eu realmente teria vontade de defender publicamente
- Rodei o prompt extra pra filtrar as 10 com mais chance de engajar
- Transformei pelo menos uma ideia em Reel pra testar o formato
- Entrei no grupo do Forja pra ver os bastidores de como a NX Digital gerencia isso

---

## POST 43 — Como fazer o Claude Code lembrar do seu projeto sem desperdiçar contexto

- URL: `/blog/memoria-projeto`
- Template: padrão (hero + artigo 720px)
- Categoria: CLAUDE CODE
- Data no card: 18 Ago 2026 | Data na página: 18 de agosto de 2026
- Tempo de leitura: 14 min (página: "14 min de leitura")
- Resumo do card: Um sistema de memória externa para o Claude Code: CLAUDE.md como mapa e docs/PROJECT.md, ARCHITECTURE.md, DECISIONS.md, CURRENT_STATE.md e TODO.md guardando o contexto real do projeto — com os 2 prompts para montar tudo.
- Meta description: Um sistema de memória externa para o Claude Code: CLAUDE.md como mapa e docs/PROJECT.md, ARCHITECTURE.md, DECISIONS.md, CURRENT_STATE.md e TODO.md guardando o contexto real do projeto — com os 2 prompts para montar tudo.
- Título da aba: Como Fazer o Claude Code Lembrar do Seu Projeto sem Desperdiçar Contexto | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Antes de Começar · 02Prompt 1 — Criando a Memória do Projeto · 03O Que Esse Primeiro Prompt Faz · 04Para Que Serve Cada Arquivo? · 05Prompt 2 — Faça o Claude Entender o Projeto · 06Como Usar na Prática · 07O Principal Erro que Você Deve Evitar · 08O Objetivo Não É Fazer o Claude Lembrar de Tudo

### Corpo do post (conteúdo exato, na ordem da página)

Se você usa o Claude Code por bastante tempo em um projeto, provavelmente já percebeu um problema:

Você toma decisões importantes, explica regras de negócio, define arquitetura, corrige comportamentos e, depois de algumas sessões, parte desse contexto simplesmente não está mais disponível.

O resultado é previsível:

- →você precisa explicar coisas novamente;
- →o Claude volta a sugerir soluções que já foram descartadas;
- →decisões antigas são esquecidas;
- →mais contexto precisa ser enviado;
- →mais tokens são consumidos;
- →aumenta a chance de ele alterar algo que não deveria.

A solução não é tentar fazer o Claude "lembrar de tudo".

A solução é criar uma **memória externa dentro do próprio projeto**.

A ideia é simples:

:::bloco
estrutura de memória⟦botão: Copiar⟧

```
CLAUDE.md
docs/
├── PROJECT.md
├── ARCHITECTURE.md
├── DECISIONS.md
├── CURRENT_STATE.md
└── TODO.md
```
:::fim

Cada arquivo possui uma responsabilidade específica. O `CLAUDE.md` ensina o Claude **como trabalhar e onde encontrar contexto**. O restante guarda as informações importantes do projeto de maneira organizada.

Em vez de depender exclusivamente do histórico da conversa, o Claude passa a consultar o próprio projeto para recuperar informações. Neste material você vai receber os 2 prompts que montam essa estrutura.

## Antes de Começar

Abra seu projeto no Claude Code. Você vai executar os dois prompts na seguinte ordem:

- →**Prompt 1:** cria o sistema de memória.
- →**Prompt 2:** faz o Claude estudar o projeto e preencher essa memória corretamente.

Não pule diretamente para o segundo. O primeiro prompt é justamente o que cria as regras que o Claude deverá seguir dali em diante.

## Prompt 1 — Criando a Memória do Projeto

O primeiro prompt cria toda a estrutura. O objetivo ainda **não é explicar o projeto para o Claude**. Primeiro queremos criar o sistema que vai receber essas informações. Cole o prompt abaixo no Claude Code:

:::bloco
prompt 1 — criando a memória do projeto⟦botão: Copiar⟧

```
Quero que você prepare este projeto para trabalhar com memória persistente e contexto organizado entre sessões.

Neste momento, não quero que você implemente nenhuma funcionalidade nem tente documentar profundamente o projeto. Primeiro, apenas crie a estrutura e as regras que você deverá seguir daqui para frente.

Crie esta estrutura:

/CLAUDE.md
/docs/PROJECT.md
/docs/ARCHITECTURE.md
/docs/DECISIONS.md
/docs/CURRENT_STATE.md
/docs/TODO.md

## CLAUDE.md

O CLAUDE.md será o arquivo principal de instruções para você trabalhar neste projeto.

Ele deve permanecer curto, objetivo e permanente.

Inclua nele:

- como você deve trabalhar neste projeto;
- como consultar a documentação;
- quando atualizar cada arquivo;
- regras para não desperdiçar contexto;
- regras para registrar informações importantes;
- regras para não registrar informações triviais.

O CLAUDE.md deve ensinar você a usar os arquivos abaixo como memória externa.

### PROJECT.md

Fonte principal sobre o que estamos construindo.

Deve conter, conforme essas informações forem descobertas:

- objetivo do projeto;
- problema que resolve;
- público/usuários;
- principais funcionalidades;
- regras de negócio;
- fluxos principais;
- restrições importantes;
- critérios de sucesso.

### ARCHITECTURE.md

Fonte sobre como o projeto está construído tecnicamente.

Use para registrar:

- stack;
- arquitetura;
- serviços;
- APIs;
- banco de dados;
- integrações;
- componentes importantes;
- fluxo de dados;
- decisões estruturais já implementadas.

### DECISIONS.md

Fonte sobre decisões importantes e seus motivos.

Registre somente decisões que podem fazer diferença futuramente.

Use preferencialmente:

## Decisão

Contexto:
O problema ou situação.

Decisão:
O que foi escolhido.

Motivo:
Por que foi escolhido.

Alternativas consideradas:
O que foi descartado, quando relevante.

Impacto:
Consequências importantes.

Não registre escolhas triviais ou facilmente descobertas pelo código.

### CURRENT_STATE.md

Deve responder rapidamente:

"Onde este projeto está agora?"

Mantenha:

- funcionalidades concluídas;
- partes em desenvolvimento;
- problemas conhecidos;
- bloqueios;
- último ponto relevante do desenvolvimento.

Ele deve permanecer curto e atualizado.

### TODO.md

Registre apenas trabalho ainda pendente.

Organize quando fizer sentido em:

## Agora
## Depois
## Backlog

Remova tarefas concluídas para evitar histórico desnecessário.

---

# REGRAS OBRIGATÓRIAS DE MEMÓRIA

Adicione ao CLAUDE.md instruções permanentes para seguir estas regras:

1. Não dependa apenas da memória da conversa para informações importantes do projeto.
2. Quando uma informação tiver relevância para sessões futuras, registre-a no arquivo apropriado.
3. Não coloque tudo no CLAUDE.md.
4. O CLAUDE.md deve funcionar principalmente como índice + conjunto de regras permanentes.
5. Consulte arquivos adicionais somente quando forem relevantes para a tarefa atual.

Exemplos:
- entender o produto → PROJECT.md;
- trabalhar em arquitetura → ARCHITECTURE.md;
- verificar por que algo foi escolhido → DECISIONS.md;
- retomar o trabalho → CURRENT_STATE.md;
- planejar próximas tarefas → TODO.md.

6. Não carregue toda a documentação indiscriminadamente em toda tarefa.
7. Não registre:
   - logs triviais;
   - cada alteração de código;
   - explicações óbvias;
   - detalhes temporários;
   - informações facilmente descobertas lendo o código;
   - conteúdo duplicado.
8. Antes de encerrar uma tarefa relevante, verifique silenciosamente se algum arquivo de memória precisa ser atualizado.
9. Atualize:
   - PROJECT.md quando o entendimento do produto ou das regras de negócio mudar;
   - ARCHITECTURE.md quando houver mudança estrutural relevante;
   - DECISIONS.md quando uma decisão importante for tomada;
   - CURRENT_STATE.md quando o estado do desenvolvimento mudar;
   - TODO.md quando tarefas forem criadas, concluídas ou alteradas.
10. Se documentação e código entrarem em conflito, investigue antes de assumir qual está correto.
11. Prefira documentação curta e de alta densidade informacional.
12. Não aumente os arquivos indefinidamente. Remova ou consolide informações obsoletas.

Agora:

1. verifique se já existe CLAUDE.md ou documentação equivalente;
2. preserve qualquer regra útil já existente;
3. crie a estrutura que estiver faltando;
4. configure o CLAUDE.md com essas regras;
5. deixe os outros documentos preparados para serem preenchidos;
6. não implemente nenhuma funcionalidade do projeto;
7. não invente informações sobre o projeto que ainda não conhece.

Quando terminar, apenas me diga quais arquivos foram criados ou adaptados.
```
:::fim

## O Que Esse Primeiro Prompt Faz

Depois de executar, seu projeto deverá ficar parecido com isso:

:::bloco
estrutura resultante⟦botão: Copiar⟧

```
seu-projeto/
│
├── CLAUDE.md
│
├── docs/
│   ├── PROJECT.md
│   ├── ARCHITECTURE.md
│   ├── DECISIONS.md
│   ├── CURRENT_STATE.md
│   └── TODO.md
│
├── src/
├── package.json
└── ...
```
:::fim

O ponto mais importante é entender que **não estamos colocando tudo dentro do CLAUDE.md**. Esse é um erro fácil de cometer.

Se você transformar o CLAUDE.md em um documento gigantesco contendo arquitetura, histórico, decisões, tarefas e regras de negócio, você acaba criando outro problema: **contexto demais.**

A proposta aqui é justamente o contrário. O Claude precisa saber onde encontrar a informação, e não necessariamente carregar toda informação em todas as tarefas. Pense no CLAUDE.md como um mapa.

## Para Que Serve Cada Arquivo?

### CLAUDE.md

É basicamente o manual de operação do Claude dentro daquele projeto. Ele deve dizer coisas como: como trabalhar, quais regras respeitar, onde procurar informações, quando registrar novas informações e o que não deve ser armazenado. Ele não deve virar o diário do projeto.

### PROJECT.md

É onde fica o contexto de negócio. Por exemplo:

:::bloco
docs/PROJECT.md — exemplo⟦botão: Copiar⟧

```
O sistema é um CRM para empresas de compra de veículos.

O principal objetivo é receber leads vindos do WhatsApp, qualificá-los automaticamente e direcionar oportunidades para vendedores.

Usuários principais:
- vendedores;
- gestores;
- administradores.
```
:::fim

Quando o Claude precisa entender o que está sendo construído, é aqui que ele procura.

### ARCHITECTURE.md

Guarda a estrutura técnica. Exemplo:

:::bloco
docs/ARCHITECTURE.md — exemplo⟦botão: Copiar⟧

```
Frontend:
React

Banco:
Supabase

Automação:
n8n

Mensageria:
WhatsApp Cloud API

Fluxo principal:
WhatsApp → webhook → n8n → IA → Supabase → frontend
```
:::fim

Se futuramente você pedir "vamos alterar a forma como as mensagens entram no sistema", o Claude sabe onde consultar a arquitetura antes de sair alterando código.

### DECISIONS.md

Esse é um dos arquivos mais importantes. Imagine que durante o desenvolvimento vocês discutiram: Supabase Realtime ou polling? Depois de analisar o projeto, decidiram usar Realtime. A decisão pode ser registrada assim:

:::bloco
docs/DECISIONS.md — exemplo⟦botão: Copiar⟧

```
## Atualização do pipeline

Contexto:
O frontend precisa refletir alterações feitas pelo backend.

Decisão:
Utilizar Supabase Realtime.

Motivo:
Evitar polling recorrente e aproveitar a infraestrutura já utilizada no projeto.

Alternativas consideradas:
Polling periódico pela API.

Impacto:
Mudanças futuras no pipeline devem considerar eventos Realtime.
```
:::fim

Daqui a algumas semanas, o Claude não precisa rediscutir a mesma coisa do zero.

### CURRENT_STATE.md

Esse arquivo funciona como um checkpoint do projeto. Algo como:

:::bloco
docs/CURRENT_STATE.md — exemplo⟦botão: Copiar⟧

```
Funcionando:
- autenticação;
- cadastro de leads;
- pipeline;
- integração com Supabase.

Em desenvolvimento:
- integração WhatsApp.

Problemas conhecidos:
- mensagens de áudio ainda não aparecem corretamente.

Último ponto:
Webhook recebe mensagens, mas ainda falta persistir anexos.
```
:::fim

Quando você abrir outra sessão, o Claude consegue descobrir rapidamente onde vocês estavam.

### TODO.md

Aqui ficam apenas as próximas tarefas. Por exemplo:

:::bloco
docs/TODO.md — exemplo⟦botão: Copiar⟧

```
## Agora

- finalizar webhook;
- implementar mensagens de áudio.

## Depois

- dashboard;
- relatórios.

## Backlog

- aplicativo mobile.
```
:::fim

Quando algo terminar, a ideia é remover. Isso não é histórico. É contexto operacional atual.


## Prompt 2 — Agora Faça o Claude Entender o Projeto

Depois que toda a estrutura estiver criada, execute o segundo prompt. É aqui que começa a parte realmente importante.

Em vez de você simplesmente despejar um texto gigantesco explicando seu projeto, queremos que o Claude:

1. 1.leia o que já existe;
2. 2.analise o código;
3. 3.descubra sozinho o que conseguir;
4. 4.identifique o que ainda falta entender;
5. 5.faça perguntas relevantes;
6. 6.salve suas respostas nos lugares corretos.

Cole:

:::bloco
prompt 2 — entendendo o projeto⟦botão: Copiar⟧

```
Agora quero que você entenda profundamente este projeto antes de continuar desenvolvendo.

Não comece nenhuma implementação ainda.

Primeiro, consulte o CLAUDE.md e siga o sistema de memória definido nele.

Depois:

1. analise o código e a documentação que já existem;
2. identifique tudo o que você consegue determinar com segurança sozinho;
3. identifique as lacunas que ainda impedem você de entender corretamente o projeto;
4. me faça as perguntas necessárias para preencher essas lacunas.

Quero que você entenda principalmente:

- qual problema este projeto resolve;
- quem utiliza o sistema;
- qual é o objetivo final;
- quais são os principais fluxos;
- quais funcionalidades são realmente importantes;
- quais regras de negócio existem;
- quais comportamentos são obrigatórios;
- o que não deve fazer parte do projeto;
- quais integrações existem ou existirão;
- quais limitações precisamos respeitar;
- quais decisões já foram tomadas;
- qual é o estado atual;
- o que ainda precisa ser construído.

## IMPORTANTE

Não me faça perguntas cuja resposta você consegue descobrir analisando o próprio projeto.

Também não faça dezenas de perguntas genéricas de uma vez.

Priorize primeiro as perguntas que realmente mudam sua compreensão ou suas decisões.

Conforme eu responder:

- atualize docs/PROJECT.md com informações sobre produto, objetivo e regras de negócio;
- atualize docs/ARCHITECTURE.md quando descobrir informações técnicas relevantes;
- registre decisões já tomadas em docs/DECISIONS.md;
- atualize docs/CURRENT_STATE.md com o estado real do projeto;
- organize tarefas identificadas em docs/TODO.md.

Não coloque essas informações todas no CLAUDE.md.

O CLAUDE.md deve continuar sendo apenas o conjunto de instruções permanentes e o mapa para encontrar o contexto correto.

Quando houver informações contraditórias entre minhas respostas, documentação e código, pare e me mostre a inconsistência antes de decidir sozinho.

Continue esse processo até ter contexto suficiente para explicar claramente:

1. o que estamos construindo;
2. para quem;
3. como funciona;
4. como está estruturado;
5. onde estamos agora;
6. quais são os próximos passos.

Só depois disso considere o projeto contextualizado e pronto para continuar o desenvolvimento.

Comece analisando o projeto atual e depois me faça apenas as perguntas realmente necessárias.
```
:::fim

## Como Usar na Prática

Depois do segundo prompt, não saia respondendo de qualquer jeito. Essa conversa é basicamente o **onboarding do Claude no seu projeto**.

Se ele perguntar:

Qual é o principal usuário do sistema?

Explique.

Quando um lead deve passar de qualificado para oportunidade?

Defina a regra.

Essa integração é obrigatória ou planejada para uma fase futura?

Responda.

Cada uma dessas respostas pode representar uma informação que o Claude usará novamente semanas depois. E, como o sistema criado pelo primeiro prompt já ensinou onde essas informações devem ficar, ele pode atualizar a documentação durante o processo.

## O Principal Erro que Você Deve Evitar

Não tente salvar tudo. Isso é tão ruim quanto não salvar nada.

Você não precisa registrar:

:::bloco
⟦botão: Copiar⟧

```
Hoje alteramos a margem do botão de 12px para 16px.
```
:::fim

Ou:

:::bloco
⟦botão: Copiar⟧

```
Foi corrigido um import no arquivo Header.tsx.
```
:::fim

O próprio código já contém esse tipo de informação. A memória deve guardar coisas que **não são óbvias olhando o código**. Principalmente:

- →intenção;
- →regras de negócio;
- →decisões;
- →restrições;
- →contexto;
- →estado atual.

Uma boa pergunta para decidir se algo precisa ser salvo é: "uma nova sessão poderia tomar uma decisão errada se não soubesse disso?" Se a resposta for sim, provavelmente vale documentar.

## O Objetivo Não É Fazer o Claude Lembrar de Tudo

Esse é provavelmente o ponto mais importante dessa estratégia. Você não está criando uma memória infinita. Está criando uma forma organizada para o Claude recuperar o contexto certo quando precisar.

Em vez disso:

:::bloco
sem memória organizada⟦botão: Copiar⟧

```
Claude
↓
carrega 500 informações
↓
tenta descobrir quais importam
```
:::fim

Queremos isso:

:::bloco
com memória organizada⟦botão: Copiar⟧

```
Claude
↓
entende a tarefa
↓
descobre qual contexto precisa
↓
consulta o arquivo correto
↓
executa
```
:::fim

Essa diferença parece pequena, mas em projetos maiores muda bastante a qualidade do trabalho. Depois que você começar a tratar o contexto do agente como parte da arquitetura do projeto, fica difícil voltar a trabalhar dependendo apenas do histórico da conversa.

:::bloco
Regras de memória, resumidas

- Não dependa apenas da memória da conversa para informações importantes do projeto.
- Quando uma informação tiver relevância para sessões futuras, registre-a no arquivo apropriado.
- Não coloque tudo no CLAUDE.md.
- O CLAUDE.md deve funcionar principalmente como índice + conjunto de regras permanentes.
- Consulte arquivos adicionais somente quando forem relevantes para a tarefa atual.
- Não carregue toda a documentação indiscriminadamente em toda tarefa.
- Não registre logs triviais, cada alteração de código, explicações óbvias ou conteúdo duplicado.
- Antes de encerrar uma tarefa relevante, verifique silenciosamente se algum arquivo precisa ser atualizado.
- Se documentação e código entrarem em conflito, investigue antes de assumir qual está correto.
- Prefira documentação curta e de alta densidade informacional.
- Não aumente os arquivos indefinidamente — remova ou consolide informações obsoletas.
:::fim

:::bloco
Checklist antes de dar por concluído

- Rodei o Prompt 1 antes de explicar qualquer coisa sobre o projeto
- O CLAUDE.md ficou curto — só regras e mapa, não virou diário do projeto
- Respondi as perguntas do Prompt 2 com atenção, cada resposta vira memória
- Não salvei detalhes triviais que já estão óbvios no código
- Testei a pergunta 'uma nova sessão tomaria decisão errada sem isso?' antes de documentar
- Deixei CURRENT_STATE.md e TODO.md como checkpoints, sem virar histórico acumulado
:::fim

---

## POST 44 — O mapa da máquina de conteúdo com IA

- URL: `/blog/maquina-conteudo`
- Template: padrão (hero + artigo 720px)
- Categoria: CONTEÚDO & IA
- Data no card: 18 Ago 2026 | Data na página: 18 de agosto de 2026
- Tempo de leitura: 7 min (página: "7 min de leitura")
- Resumo do card: O fluxo completo para transformar uma ideia em conteúdo publicado sem depender de inspiração: pesquisa, pauta, roteiro, design, vídeo, legenda, publicação e análise.
- Meta description: O fluxo completo para transformar uma ideia em conteúdo publicado sem depender de inspiração: pesquisa, pauta, roteiro, design, vídeo, legenda, publicação e análise.
- Título da aba: O Mapa da Máquina de Conteúdo com IA | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01O Fluxo Completo · 02Pesquisa: Encontre Sinais Antes de Criar · 03Pautas: Transforme Sinal em Decisão Editorial · 04Roteiro: Gancho, Prova, Transformação e CTA · 05Design: a Estratégia no Primeiro Segundo · 06Vídeo: Transforme o Roteiro em Cenas · 07Legenda: Complete o Post, Não Repita · 08Publicação e Análise: Ciclo, Não Arquivo · 09A Regra Final

### Corpo do post (conteúdo exato, na ordem da página)

Uma operação de conteúdo não escala com mais ideias soltas. Ela escala quando cada etapa deixa uma saída pronta para a próxima.

Este é o mapa que usamos para transformar uma ideia em conteúdo publicado sem depender de inspiração toda semana.

## O Fluxo Completo

:::bloco
⟦botão: Copiar⟧

```
PESQUISA → PAUTAS → ROTEIRO → DESIGN → VÍDEO → LEGENDA → PUBLICAÇÃO → ANÁLISE
```
:::fim

IA não substitui a estratégia. Ela acelera os trechos repetitivos, organiza contexto e deixa o time livre para julgar o que merece ser publicado.

## 1. Pesquisa: Encontre Sinais Antes de Criar

Não comece perguntando "o que eu posto?". Comece procurando:

- →temas que já estão puxando atenção no seu mercado;
- →dúvidas repetidas de clientes e leads;
- →posts de concorrentes que geraram conversa, não só curtida;
- →objeções que impedem alguém de comprar;
- →palavras que o público usa para descrever o próprio problema.

**Saída da etapa:** uma lista priorizada de sinais, com fonte, público, dor e oportunidade.

Prompt-base:

:::bloco
prompt — pesquisa de sinais⟦botão: Copiar⟧

```
Você é um estrategista de conteúdo para [empresa].
Analise os sinais abaixo e encontre oportunidades de conteúdo.
Para cada oportunidade, devolva: dor explícita, ângulo, formato recomendado,
gancho inicial e objetivo (alcance, salvamento, conversa ou venda).

Sinais: [cole aqui pesquisas, comentários, perguntas e referências]
```
:::fim

## 2. Pautas: Transforme Sinal em uma Decisão Editorial

Uma boa pauta é específica. Ela precisa saber para quem é, qual ponto de vista defende e qual ação quer provocar.

Use este molde:

:::bloco
molde de pauta⟦botão: Copiar⟧

```
PÚBLICO:
PROBLEMA:
ÂNGULO:
GANCHO:
FORMATO:
PROVA OU EXEMPLO:
CTA:
```
:::fim

Não gere trinta ideias sem filtro. Escolha três que tenham uma dor clara, uma prova possível e uma ligação com a oferta da empresa.

## 3. Roteiro: Gancho, Prova, Transformação e CTA

O roteiro não começa no texto bonito. Começa na intenção.

Estrutura simples para um carrossel ou vídeo:

1. 1.**Gancho:** uma frase que mostra o custo de continuar como está.
2. 2.**Problema:** torne a dor reconhecível em poucas linhas.
3. 3.**Prova:** dado, caso, demonstração ou raciocínio concreto.
4. 4.**Transformação:** mostre o processo ou a alternativa.
5. 5.**CTA:** uma única próxima ação.

Prompt-base:

:::bloco
prompt — roteiro⟦botão: Copiar⟧

```
Com base nesta pauta, escreva um roteiro de [carrossel/vídeo].
Não use frases genéricas nem promessas vagas.
Abra com um gancho específico, entregue uma explicação prática,
inclua uma prova e termine com o CTA: [CTA].

Pauta: [cole aqui]
```
:::fim


## 4. Design: Faça a Estratégia Aparecer no Primeiro Segundo

Design não serve para enfeitar uma ideia fraca. Ele precisa tornar a ideia óbvia rápido.

Antes de desenhar, defina:

- →a frase que precisa ficar maior;
- →o contraste visual que sustenta o gancho;
- →uma cena ou objeto recorrente que conecte os slides;
- →a prova visual que torna a promessa crível;
- →o que precisa ser legível em uma tela pequena.

Se o post não é compreensível reduzido no celular, ele ainda não está pronto.

## 5. Vídeo: Transforme o Roteiro em Cenas

Todo trecho do roteiro precisa responder a uma pergunta visual: "o que a pessoa vê enquanto escuta isso?"

Monte uma pequena lista antes de editar:

:::bloco
lista de cenas⟦botão: Copiar⟧

```
CENA 1 — o gancho visual
CENA 2 — o problema acontecendo
CENA 3 — a prova ou demonstração
CENA 4 — o processo em ação
CENA 5 — a transformação
CENA 6 — CTA
```
:::fim

IA pode acelerar ideias de B-roll, storyboard, variações de abertura e organização da edição. A decisão final de ritmo, prova e tom continua humana.

## 6. Legenda: Complete o Post, Não Repita o Post

Uma legenda boa faz quatro coisas:

1. 1.repete o gancho em outro formato;
2. 2.adiciona contexto que não cabia na arte;
3. 3.mostra por que isso importa para o público;
4. 4.chama uma única ação.

Checklist antes de publicar:

- →a primeira frase prende quem não abriu o carrossel?
- →existe uma ideia concreta, não só opinião?
- →o CTA tem uma palavra-chave única?
- →a promessa do CTA é realmente entregue?

## 7. Publicação e Análise: Conteúdo é Ciclo, Não Arquivo

Depois de publicar, registre:

- →alcance;
- →salvamentos;
- →compartilhamentos;
- →comentários;
- →visitas ao perfil;
- →leads ou conversas geradas.

Cruze esses números com o tema, o ângulo, o gancho e o formato. É assim que a operação aprende o que repetir.

## A Regra Final

Uma ideia entra. Uma operação inteira sai.

Mas só funciona quando cada etapa entrega contexto para a próxima — e quando alguém com visão de negócio continua no comando.

- Defini a saída de cada etapa antes de começar (sinais, pauta, roteiro, design, cenas, legenda, dados)
- Escolhi só as pautas com dor clara, prova possível e ligação com a oferta
- Testei o post reduzido no celular antes de publicar
- A legenda repete o gancho e entrega uma ideia concreta, não só opinião
- Registrei alcance, salvamentos, comentários e leads depois de publicar
- Cruzei os números com tema, ângulo, gancho e formato pra saber o que repetir

---

## POST 45 — Como usar o Claude para criar 30 dias de conteúdo: calendário + prompts para copiar

- URL: `/blog/30-dias-claude`
- Template: padrão (hero + artigo 720px)
- Categoria: CLAUDE & CONTEÚDO
- Data no card: 26 Ago 2026 | Data na página: 26 de agosto de 2026
- Tempo de leitura: 11 min (página: "11 min de leitura")
- Resumo do card: Um sprint de conteúdo com 30 temas que cumprem funções diferentes — reconhecimento, autoridade, prova, objeção e oferta — e os 3 prompts pra adaptar, escolher hooks e desenvolver cada post com o Claude.
- Meta description: Um sprint de conteúdo com 30 temas que cumprem funções diferentes — reconhecimento, autoridade, prova, objeção e oferta — e os 3 prompts pra adaptar, escolher hooks e desenvolver cada post com o Claude.
- Título da aba: Como Usar o Claude para Criar 30 Dias de Conteúdo: Calendário + Prompts | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Antes de Começar: o Contexto Mínimo · 02Prompt 1 — Adapte o Calendário · 03O Calendário de 30 Dias · 04Prompt 2 — Escolha os Hooks · 05Prompt 3 — Conteúdo Completo · 06Como Executar Sem Virar Tarefa Gigante · 07Checklist Antes de Começar

### Corpo do post (conteúdo exato, na ordem da página)

Não é um calendário com 30 frases motivacionais pra você tentar adaptar. É um sprint de conteúdo com 30 ângulos que cumprem funções diferentes: chamar atenção, provar que você sabe o que faz, derrubar objeção e abrir espaço para a oferta.

Você vai usar o Claude em três momentos:

- →adaptar os 30 temas para o seu negócio;
- →escolher os melhores hooks de cada tema;
- →transformar o tema escolhido em Reel, carrossel ou texto.

O resultado não são 30 posts mágicos publicados sem você olhar. É um mês inteiro decidido — com menos tela em branco e mais chances de a pessoa certa entender por que deveria comprar de você.

Se você quer um mapa de 3 meses, use o material de matriz de conteúdo. Aqui a proposta é outra: sair hoje com os próximos 30 dias organizados e prontos para desenvolver.

## Antes de Começar: Dê ao Claude o Contexto Mínimo

Não pule isso. O mesmo calendário fica genérico se o Claude não sabe o que você vende, para quem e qual mudança você entrega.

Cole uma vez, no início da conversa ou nas instruções de um Projeto no Claude:

:::bloco
prompt — contexto do negócio⟦botão: Copiar⟧

```
Você vai me ajudar a criar conteúdo que leva pessoas a comprar meu serviço/produto.

Meu negócio: [o que você vende]
Meu cliente ideal: [quem compra]
Problema caro que eu resolvo: [problema]
Resultado que eu entrego: [resultado]
Oferta que quero vender neste mês: [oferta]
Tom de voz: [direto, técnico, descontraído, etc.]

Não crie nenhum post ainda. Primeiro, resuma o que você entendeu sobre
meu cliente, minha oferta e a principal objeção que ele provavelmente tem.
Espere minha confirmação.
```
:::fim

Leia a resposta. Se ela descreveu um cliente genérico, corrija antes de seguir. Os próximos prompts só funcionam bem quando esse contexto está certo.

## Prompt 1 — Transforme o Calendário Abaixo no Seu Calendário

O calendário que vem a seguir usa temas entre colchetes. Eles existem para você não partir do zero — mas precisam ganhar a linguagem do seu nicho.

Depois de confirmar o contexto, cole:

:::bloco
prompt — adaptar o calendário⟦botão: Copiar⟧

```
Use o calendário de 30 dias que vou colar abaixo.

Para cada dia, adapte o tema entre colchetes ao meu negócio.
Mantenha o objetivo de cada post e entregue apenas:

1. tema específico para meu público;
2. uma frase de gancho com no máximo 12 palavras;
3. formato recomendado: Reel, carrossel ou texto;
4. qual oferta ou próximo passo esse post prepara.

Não escreva os posts completos ainda. Não repita a mesma ideia com palavras diferentes.

[COLE O CALENDÁRIO DE 30 DIAS]
```
:::fim

Agora você tem 30 decisões tomadas. Não publique tudo sem critério: leia os hooks e troque o que não parece uma conversa que seu cliente teria de verdade.

## O Calendário de 30 Dias

Os dias estão em blocos de cinco. Cada bloco tem uma função. É isso que impede seu perfil de virar só dica solta ou só oferta.

:::bloco
### Dias 1–5 — Faça a Pessoa Reconhecer o Problema

| Dia | Objetivo | Tema para Adaptar | Formato |
| --- | --- | --- | --- |
| 01 | Contrariar o senso comum | O conselho popular sobre [problema] que mais atrasa resultado | Reel curto |
| 02 | Nomear um erro | O erro silencioso que faz [cliente] perder [tempo/dinheiro] | Carrossel |
| 03 | Dar contexto | O que quase ninguém vê antes de tentar resolver [problema] | Texto |
| 04 | Criar identificação | Sinais de que [cliente] já está pagando caro por [problema] | Carrossel |
| 05 | Abrir uma tensão | Você não precisa de [solução óbvia]. Precisa de [causa real]. | Reel curto |
:::fim

:::bloco
### Dias 6–10 — Mostre que Você Entende o Caminho

| Dia | Objetivo | Tema para Adaptar | Formato |
| --- | --- | --- | --- |
| 06 | Ensinar uma decisão | Como decidir entre [opção A] e [opção B] em [situação] | Carrossel |
| 07 | Mostrar bastidor | O que eu olho antes de recomendar [solução] | Reel ou texto |
| 08 | Quebrar um mito | Por que [crença comum] não resolve [problema] | Carrossel |
| 09 | Dar uma pequena vitória | O primeiro passo que melhora [resultado] ainda esta semana | Texto |
| 10 | Explicar o método | Os 3 blocos que compõem meu processo para [resultado] | Carrossel |
:::fim

:::bloco
### Dias 11–15 — Prove Sem Precisar Se Autopromover

| Dia | Objetivo | Tema para Adaptar | Formato |
| --- | --- | --- | --- |
| 11 | Mostrar antes e depois | O que muda quando [cliente] para de fazer [erro] | Carrossel |
| 12 | Usar uma história | A decisão que mudou [resultado] em um projeto real | Texto |
| 13 | Mostrar critério | O que eu recusaria fazer mesmo se o cliente pedisse | Reel curto |
| 14 | Mostrar processo | Por dentro de uma etapa de [seu método] | Carrossel |
| 15 | Dar prova prática | Um exemplo de [entregável] que gera [resultado] | Reel ou imagem |
:::fim

:::bloco
### Dias 16–20 — Responda às Objeções Antes da Call

| Dia | Objetivo | Tema para Adaptar | Formato |
| --- | --- | --- | --- |
| 16 | Tempo | "Não tenho tempo para [solução]": o que essa frase esconde | Carrossel |
| 17 | Dinheiro | O custo de continuar com [problema] por mais 12 meses | Texto |
| 18 | Complexidade | O que realmente precisa existir para começar [resultado] | Reel curto |
| 19 | Confiança | Quando [solução] não é indicada — e por quê | Carrossel |
| 20 | Prioridade | Como saber se [problema] já merece investimento agora | Texto |
:::fim

:::bloco
### Dias 21–25 — Faça a Pessoa Enxergar a Transformação

| Dia | Objetivo | Tema para Adaptar | Formato |
| --- | --- | --- | --- |
| 21 | Desejo | Como é a operação quando [problema] deixa de existir | Carrossel |
| 22 | Comparação | O jeito caro versus o jeito estruturado de chegar em [resultado] | Carrossel |
| 23 | Futuro | O que acontece se você resolver [problema] nos próximos 90 dias | Texto |
| 24 | Identidade | A diferença entre quem trata [tema] como custo e como ativo | Reel curto |
| 25 | Ponto de vista | A regra que eu seguiria se estivesse começando [negócio] hoje | Texto |
:::fim

:::bloco
### Dias 26–30 — Convide Para o Próximo Passo

| Dia | Objetivo | Tema para Adaptar | Formato |
| --- | --- | --- | --- |
| 26 | Diagnóstico | 5 perguntas para saber se você precisa de [solução] | Carrossel |
| 27 | Oferta | Para quem é — e para quem não é — [sua oferta] | Carrossel |
| 28 | Bastidor de entrega | O que acontece depois que um cliente decide começar | Reel curto |
| 29 | Convite | Se [problema] é prioridade, este é o próximo passo possível | Texto |
| 30 | Oferta direta | O que eu resolvo, para quem e como começar | Carrossel ou Reel |
:::fim

## Prompt 2 — Escolha Hooks que Merecem Ser Publicados

Um tema bom ainda pode morrer na primeira linha. Antes de escrever, peça variações de hook para o dia que você escolheu.

:::bloco
prompt — hooks do dia⟦botão: Copiar⟧

```
Pegue o Dia [NÚMERO] do meu calendário.

Crie 10 hooks para esse tema. Distribua assim:
- 2 contrários ao senso comum;
- 2 começando por um erro;
- 2 com número ou consequência concreta;
- 2 em formato de bastidor;
- 2 em segunda pessoa, falando diretamente com meu cliente.

Regras:
- até 12 palavras por hook;
- sem usar "revolucionário", "segredo", "game changer" ou "transforme sua vida";
- cada hook precisa fazer sentido mesmo fora do contexto;
- não invente dados ou resultados.

No fim, indique os 3 hooks mais fortes e explique em uma linha o motivo.
```
:::fim

Escolha o que parece mais verdadeiro, não o que parece mais barulhento. Se o hook promete demais, ele ganha clique e perde confiança no slide seguinte.

## Prompt 3 — Transforme um Tema em Conteúdo Completo

Quando o tema e o hook já estão definidos, aí sim vale pedir a peça inteira.

:::bloco
prompt — post completo⟦botão: Copiar⟧

```
Use este contexto do meu negócio: [cole o contexto inicial, se necessário].

Tema: [COLE O TEMA DO DIA]
Hook aprovado: [COLE O HOOK]
Formato: [CARROSSEL / REEL / TEXTO]
Objetivo: [COLE O OBJETIVO DO DIA]

Crie o conteúdo completo.

Se for carrossel:
- 8 slides;
- slide 1 só com o hook;
- um ponto por slide;
- frases curtas, sem parágrafos longos;
- slide 8 com CTA coerente com o post.

Se for Reel:
- gancho de abertura;
- roteiro falado de até 45 segundos;
- texto na tela por cena;
- legenda curta.

Se for texto:
- abertura forte;
- desenvolvimento em blocos curtos;
- uma conclusão útil;
- CTA sem pedir venda à força.

Não invente case, número, depoimento ou resultado. Escreva no meu tom de voz.
```
:::fim

## Como Executar Sem Transformar Isso Numa Nova Tarefa Gigante

O calendário inteiro sai em uma tarde. A produção não precisa sair inteira no mesmo dia.

Use esta rotina:

- →**Hoje:** rode o contexto e o Prompt 1; adapte os 30 dias.
- →**Toda segunda:** escolha os 5 ou 7 dias da semana e rode o Prompt 2 para cada um.
- →**Na produção:** desenvolva um post por vez com o Prompt 3.
- →**No domingo:** olhe o que gerou conversa, salvamento, clique ou DM. Troque o próximo tema se precisar — não siga o calendário por teimosia.

O sistema serve para acabar com a indecisão, não para te obrigar a publicar coisa ruim só porque estava no Dia 14.


## Checklist Antes de Começar

- Dei ao Claude contexto específico sobre negócio, cliente e oferta
- Adaptei os 30 temas — não deixei os colchetes genéricos
- Escolhi hook antes de pedir o post completo
- Tenho formatos variados: Reel, carrossel e texto
- Reservei posts de oferta para quando já existir contexto e prova
- Vou medir resposta do público e ajustar o próximo bloco

Você não precisa de uma agência para decidir o que publicar este mês. Precisa de uma estrutura que faça cada post cumprir um papel — e de um Claude com contexto suficiente para trabalhar junto com você.

---

## POST 46 — Fable 5: 5 usos reais (com os prompts prontos pra copiar)

- URL: `/blog/fable-5`
- Template: padrão (hero + artigo 720px)
- Categoria: CLAUDE
- Data no card: 19 Ago 2026 | Data na página: 19 de agosto de 2026
- Tempo de leitura: 9 min (página: "9 min de leitura")
- Resumo do card: Quando vale a pena usar o Fable 5 em vez do Opus 5, e 5 usos reais com os prompts completos: virar planilha em sistema, auditar seu próprio uso do Claude, montar painel, caçar bug intermitente e escrever PRD.
- Meta description: Quando vale a pena usar o Fable 5 em vez do Opus 5, e 5 usos reais com os prompts completos: virar planilha em sistema, auditar seu próprio uso do Claude, montar painel, caçar bug intermitente e escrever PRD.
- Título da aba: Fable 5: 5 Usos Reais (com os Prompts Prontos pra Copiar) | NX Digital
- Imagem og: —
- Índice "Neste artigo" (gerado automaticamente a partir dos H2): 01Fable 5 ou Opus 5: a Regra que Eu Uso · 02Uso 1 — Vire a Planilha em Sistema · 03Uso 2 — Audite Como Você Usa o Claude · 04Uso 3 — Monte o Painel da Operação · 05Uso 4 — O Melhor Modelo pra Caçar Bug · 06Uso 5 — Entregue uma Especificação · 07O Checklist

### Corpo do post (conteúdo exato, na ordem da página)

Acabou a fase de "usa o modelo mais novo porque é novo". O Fable 5 virou padrão no plano Max (até 50% do limite semanal), no Pro só roda com créditos, e o Opus 5 chegou fazendo quase o mesmo por metade do preço. Agora é escolha, e escolha errada de modelo custa caro, em dinheiro e em tempo perdido.

## Fable 5 ou Opus 5: a Regra que Eu Uso

|  | Opus 5 (padrão) | Fable 5 (premium) |
| --- | --- | --- |
| Entrada | $5 / M tokens | $10 / M tokens |
| Saída | $25 / M tokens | $50 / M tokens |
| Contexto | 1M tokens | 1M tokens |

Os dois têm o mesmo teto de contexto. A diferença não é "quanto ele aguenta", é quanto raciocínio ele sustenta quando esse contexto está cheio de verdade.

Regra prática: se a tarefa cabe numa conversa normal e você resolveria em menos de 30 minutos (ajuste de código pontual, uma legenda, um bug óbvio), usa Opus 5. Se você está prestes a colar dezenas de arquivos ou telas de uma vez, ou vai deixar o modelo trabalhando sozinho por horas sem supervisão, é aí que o dobro do preço do Fable 5 se paga.

Os 5 usos abaixo são exatamente esses casos-limite.

## Uso 1 — Vire a Planilha em Sistema

Joga todas as planilhas e os prints do processo no Fable. Com 1M de contexto ele lê tudo de uma vez, deduz a regra real do negócio (não a regra que está escrita, a que realmente acontece na prática) e devolve o sistema inteiro, com painel.

:::bloco
prompt — planilha em sistema⟦botão: Copiar⟧

```
Leia estas planilhas e os prints do processo. Deduza
as regras reais, modele o banco e entregue o sistema
com painel.
```
:::fim

**O que colar junto:** não manda só a planilha "oficial". Manda também os prints das exceções, os ajustes manuais que todo mundo faz por fora dela, a coluna extra que alguém criou sem avisar ninguém. É nessa bagunça que mora a regra de verdade — a planilha limpa só mostra o que deveria acontecer, não o que acontece.

Depois que ele devolver a primeira versão, dois prompts de continuação que resolvem 90% dos ajustes:

:::bloco
prompt — revisão do esquema⟦botão: Copiar⟧

```
Revisa o esquema do banco que você propôs e me
explica cada tabela em uma frase. Onde você teve
que chutar uma regra por falta de informação?
```
:::fim

:::bloco
prompt — implementação incremental⟦botão: Copiar⟧

```
Agora gera as migrations e o painel inicial em
[sua stack]. Comece só pelas 3 telas mais usadas
no dia a dia, não pelo sistema inteiro.
```
:::fim

**Erro mais comum:** aceitar o esquema de banco na primeira resposta sem pedir pra ele apontar onde chutou. Ele sempre vai ter que preencher alguma lacuna quando a planilha for ambígua, e se você não perguntar onde isso aconteceu, essas suposições erradas vão virar bug depois, silenciosamente.

## Uso 2 — Audite Como Você Mesmo Usa o Claude

Aponta o Fable pro seu histórico de Claude Code. Ele abre subagentes, agrupa onde você trava toda semana e devolve skills, automações e correções prontas pro seu CLAUDE.md.

:::bloco
prompt — auditoria de uso⟦botão: Copiar⟧

```
Audite minhas sessões de Claude Code com subagentes.
Agrupe onde eu travo e proponha skills, automações e
ajustes no CLAUDE.md.
```
:::fim

Esse é o único dos 5 usos que audita você, não o seu negócio. É virar o modelo contra o seu próprio jeito de trabalhar pra achar o atrito que você nem percebe mais de tão acostumado a ele.

Prompt de continuação, depois que ele te devolver a lista de padrões:

:::bloco
prompt — skills a partir do atrito⟦botão: Copiar⟧

```
Pega os 3 pontos de atrito mais frequentes dessa
lista e escreve a skill ou instrução pra cada um,
já no formato que o CLAUDE.md espera.
```
:::fim

**Erro mais comum:** rodar isso uma vez e nunca mais voltar. O valor real está em repetir de tempos em tempos, porque o seu padrão de uso muda conforme você evolui, e o atrito de daqui a dois meses não vai ser o mesmo de hoje.

## Uso 3 — Monte o Painel da Própria Operação

O que hoje você olha em cinco abas separadas (leads, conversas, cobrança, o que precisa de decisão hoje) vira uma tela só. É o que eu uso, rodando em produção, todo santo dia.

Esse uso não tem um prompt único porque o painel de cada operação é diferente. Mas o caminho pra chegar lá é sempre o mesmo, nessa ordem:

### 1. Liste as perguntas que você se faz toda manhã

Não é "o que eu quero ver", é literalmente a pergunta que passa na sua cabeça quando abre o celular: quantos leads novos, quantas conversas esperando resposta, quanto está atrasado pra receber. Cada pergunta dessas vira uma métrica do painel.

### 2. Aponte pras fontes de dado reais

Não pra uma cópia delas. Banco de dados, API do WhatsApp, planilha de cobrança. Se o painel ler uma cópia desatualizada, ele vira mais uma tela que você não confia e para de olhar.

### 3. Peça a arquitetura antes do código

:::bloco
prompt — arquitetura do painel⟦botão: Copiar⟧

```
Antes de implementar, desenhe a arquitetura: quais
tabelas ou views eu preciso, o que precisa atualizar
em tempo real e o que pode rodar em intervalo (cron).
Não escreva código ainda.
```
:::fim

### 4. Só depois disso, peça a implementação

Começando pela tela que você mais olha, não pelo painel inteiro de uma vez.

**Erro mais comum:** pular direto pro "constrói meu painel" sem passar pelas perguntas do passo 1. Painel construído assim sempre acaba bonito e raramente usado, porque mostra o que é fácil de mostrar, não o que você realmente precisa decidir.

## Uso 4 — O Melhor Modelo pra Caçar Bug

É aqui que o Fable 5 abre vantagem de verdade: acha bug real, não frescura de linter. Pega falha intermitente (aquela que só acontece às vezes e ninguém consegue reproduzir) e segura a base de código inteira dentro do 1M de contexto pra entender a causa raiz, não só o sintoma.

:::bloco
prompt — caça a bugs⟦botão: Copiar⟧

```
Cace bugs reais nesta base. Abra revisores em paralelo,
verifique cada achado de forma adversarial e ranqueie
por severidade com plano de correção.
```
:::fim

**Por que "revisores em paralelo" e "verificação adversarial" importam:** em vez de uma passada só pela base, você pede pra ele abrir várias linhas de análise ao mesmo tempo e depois contestar os próprios achados antes de te entregar a lista final. Isso reduz muito bug fantasma, ou seja, coisa que parece bug lendo o código mas nunca aconteceria na prática.

Prompt de continuação, depois da lista de achados:

:::bloco
prompt — plano de correção⟦botão: Copiar⟧

```
Pega só os bugs de severidade alta e monta um plano
de correção com ordem de prioridade. Pra cada um,
explica como eu reproduzo o problema manualmente.
```
:::fim

**Erro mais comum:** aceitar um "achado" sem pedir a reprodução. Se ele não consegue te explicar o passo a passo de como o bug acontece de verdade, é sinal de que pode ser um falso positivo, mesmo depois da verificação adversarial.

## Uso 5 — Entregue uma Especificação e Saia do Caminho

Escreve o PRD (documento de especificação) uma vez, e deixa rodar por horas sem precisar ficar no meio corrigindo direção. Funciona melhor em tarefas grandes e bem definidas, geração de um sistema inteiro, não um ajuste pontual.

Esse uso não tem prompt fixo porque o PRD muda de projeto pra projeto. O que não muda é a estrutura que separa um PRD bom de um vago:

- →**Objetivo:** em uma frase: o que esse sistema resolve, pra quem.
- →**Escopo:** o que entra nessa versão. E, tão importante quanto, o que fica de fora, dito explicitamente.
- →**Regras de negócio reais:** não as óbvias. As exceções, os casos de borda, o que acontece quando dois eventos conflitam.
- →**Fluxos principais:** passo a passo do que o usuário faz, não só o que o sistema tem.
- →**Critérios de aceite:** como você vai saber, olhando o resultado, que ficou pronto.
- →**Fora de escopo:** de novo, agora como lista curta e explícita. Isso é o que evita que ele "invente" funcionalidade que parece útil mas não foi pedida.

Quanto mais completo esse documento antes de começar, menos você precisa intervir no meio do caminho. Um PRD fraco não trava a tarefa, mas o resultado sai genérico, porque ele preenche as lacunas com a suposição mais comum, não com a sua regra específica.


## O Checklist

- Pra planilha bagunçada, uso o prompt do Uso 1 e peço pra ele apontar onde chutou
- De tempos em tempos, rodo o Uso 2 pra achar meus próprios pontos cegos de uso
- Pro painel da operação, sigo as 4 etapas do Uso 3 antes de pedir código
- Pra bug real e intermitente, uso o Uso 4 com revisão adversarial, nunca uma passada só
- Pra tarefa grande, escrevo o PRD completo (com o que fica de fora) antes de deixar rodar sozinho

Nenhum desses usos exige o Fable 5 o tempo todo. O Opus 5 resolve boa parte do dia a dia por metade do preço. O Fable vale quando o contexto é realmente grande (base de código inteira, todas as planilhas de uma vez) ou a tarefa é longa e sem supervisão.
