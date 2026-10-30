---
name: Xavier Odontologia
description: Campo marinho, creme de respiro, equipe real e um único dourado claro levando ao WhatsApp.
colors:
  blue: "#1b2a5c"
  blue-deep: "#0f1836"
  navy: "#0f1836"
  lime: "#d8bd86"
  lime-hover: "#e5d2a8"
  sky: "#f3ecdf"
  paper: "#fbfaf7"
  on-blue-soft: "#ece5d6"
  white: "#ffffff"
  text: "#2a2f3d"
  muted: "#646a7a"
  line: "#e8e3d8"
  foot-text: "#d6cfbf"
  error: "#b42318"
  error-border: "#c0352b"
  error-bg: "#fdf1f0"
typography:
  display-hero:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "clamp(2.9rem, 5.3vw, 5.2rem)"
    fontWeight: 350
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "clamp(2.3rem, 4.6vw, 4rem)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  subhead:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "clamp(1.6rem, 2.6vw, 2.2rem)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "1.6rem"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  quote:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "clamp(1.2rem, 1.8vw, 1.5rem)"
    fontWeight: 400
    lineHeight: 1.42
    letterSpacing: "-0.01em"
  fact:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "1.6rem"
    fontWeight: 500
    letterSpacing: "-0.02em"
  group:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "1.35rem"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  row-title:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "1.35rem"
    fontWeight: 500
    lineHeight: 1.6
    letterSpacing: "-0.015em"
  small-display:
    fontFamily: "Funnel Display, system-ui, sans-serif"
    fontSize: "1.1rem"
    fontWeight: 500
    letterSpacing: "-0.01em"
  lead:
    fontFamily: "Funnel Sans, system-ui, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "Funnel Sans, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Funnel Sans, system-ui, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 600
  caption:
    fontFamily: "Funnel Sans, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
rounded:
  lg: "32px"
  md: "20px"
  field: "14px"
  sm: "12px"
  focus: "6px"
  row: "4px"
  pill: "999px"
  round: "50%"
spacing:
  gutter: "20px"
  container: "1240px"
  sec: "clamp(80px, 10vw, 128px)"
  sec-tight: "clamp(56px, 6.5vw, 88px)"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  "2xl": "48px"
  "3xl": "64px"
components:
  button-pill-white:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "8px 8px 8px 22px"
  button-pill-lime:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.navy}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "8px 8px 8px 22px"
  button-pill-lime-hover:
    backgroundColor: "{colors.lime-hover}"
  pill-dot:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.navy}"
    rounded: "{rounded.round}"
    size: "40px"
  button-ghost:
    textColor: "{colors.navy}"
    rounded: "{rounded.pill}"
    padding: "12px 18px"
  button-ghost-hover:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
  text-link:
    textColor: "{colors.blue}"
    typography: "{typography.label}"
    padding: "10px 4px"
  text-link-hover:
    textColor: "{colors.navy}"
  chip:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.navy}"
    rounded: "{rounded.pill}"
    padding: "9px 16px"
  chip-touch:
    height: "44px"
  chip-selected:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
  chip-compact:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.navy}"
    rounded: "{rounded.pill}"
    padding: "8px 12px"
  input:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.navy}"
    rounded: "{rounded.field}"
    padding: "15px 16px"
  input-focus:
    backgroundColor: "{colors.white}"
  contact-form:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    rounded: "{rounded.lg}"
    padding: "32px"
  send-status:
    textColor: "{colors.navy}"
  skip-link:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
    rounded: "{rounded.pill}"
    padding: "12px 18px"
  picker-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    rounded: "{rounded.lg}"
    padding: "24px"
  treatment-row:
    textColor: "{colors.navy}"
    typography: "{typography.row-title}"
    rounded: "{rounded.row}"
    padding: "24px 12px"
  treatment-row-hover:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.blue}"
  testimonial-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    typography: "{typography.quote}"
    rounded: "{rounded.md}"
    padding: "32px"
  cro-pill:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.navy}"
    rounded: "{rounded.pill}"
    padding: "8px 16px"
  step-number:
    textColor: "{colors.blue}"
    typography: "{typography.title}"
    width: "52px"
  faq-toggle:
    backgroundColor: "{colors.sky}"
    rounded: "{rounded.round}"
    size: "36px"
  faq-toggle-open:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
  whatsapp-float:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.navy}"
    rounded: "{rounded.round}"
    size: "60px"
  whatsapp-float-mobile:
    size: "56px"
  nav-bar:
    backgroundColor: "{colors.blue}"
    textColor: "{colors.white}"
    height: "84px"
  menu-button:
    textColor: "{colors.white}"
    rounded: "{rounded.round}"
    size: "44px"
  menu-panel:
    backgroundColor: "{colors.blue-deep}"
    textColor: "{colors.white}"
    padding: "12px 20px 24px"
---

# Design System: Xavier Odontologia

## Overview

**Creative North Star: "A Recepção Azul-Marinho"**

O site é a recepção da clínica estendida para o celular: um campo marinho de ponta a ponta, a equipe real sorrindo, e alguém que pergunta "o que você precisa?" antes de qualquer coisa. O marinho não é moldura nem detalhe; ele é dono de faixas inteiras (cabeçalho, abertura, fatos, "Quem cuida", contato). O papel e o creme entram como respiro entre essas faixas, e o marinho profundo segura o texto, os resultados e o rodapé. O dourado claro, eco do dourado do logotipo, aparece pouco e sempre com a mesma função: é por ali que se age (ou é ali que está o foco do teclado sobre marinho).

A densidade é baixa e a leitura é de cima para baixo, uma ideia por faixa. Títulos grandes e leves em Funnel Display, texto em Funnel Sans, fotos reais em retângulos de canto generoso. A personalidade é próxima e calorosa, nunca hospitalar (branco com dente de ícone) e nunca "luxo distante" (preto com dourado metálico): o marinho com dourado daqui se apoia no creme e no papel, não no preto. A prova é só o que existe: fotos da equipe, fachada, recepção e o CRO da Dra. Vilma. Onde a prova ainda não chegou (antes/depois, depoimentos), o espaço fica vazio e marcado, nunca preenchido com algo inventado.

Há três movimentos e nenhum outro: a entrada da abertura, uma vez só; o vídeo em loop como marca d'água atrás do título (um dente branco realista girando, em tons claros e a 20%); e o mapa do sorriso em Tratamentos (pontos dourados que pulsam e uma linha que se desenha até a etiqueta). O vídeo é um extra: sem ele, ou com menos movimento pedido, fica só o campo marinho. Com menos movimento pedido, o mapa mostra os pontos parados e a etiqueta aparece sem a linha animada. Tudo o mais está visível por padrão e responde apenas a interação (hover, foco, seleção).

**Key Characteristics:**
- Faixas de cor inteira alternando marinho / papel / creme / marinho profundo, terminando em marinho profundo.
- Um único acento dourado claro (#d8bd86) para ação; selecionado e aberto são marinho.
- Pílulas totalmente arredondadas com um "ponto" circular à direita que carrega o ícone; o ponto não gira.
- Fotos reais com canto de 32px ou 20px; nada de ilustração de estoque.
- Ornamento autoral único: o dente facetado em traço, com uma faceta dourada, no título do contato.
- Movimento só na entrada da abertura e no vídeo opcional da abertura; tudo desligado com `prefers-reduced-motion` (e o vídeo também com economia de dados).

## Colors

Uma paleta de marinho, creme e papel com um único acento dourado claro; o dourado existe para ser encontrado, não para decorar.

**Escolha confirmada pela clínica (29/10/2026):** a paleta voltou ao marinho, dourado e creme de antes do redesenho, a pedido da clínica. Os nomes dos tokens no CSS ficaram (`--blue`, `--lime`, `--sky`…); só os valores mudaram. A intenção continua a mesma: quente e próximo, não luxo distante, com creme no lugar do preto.

### Primary
- **Marinho Campo** (`blue`): a cor do mundo. Fundo do cabeçalho, da abertura, da faixa de fatos, da faixa "Quem cuida" (Dra. Vilma + clínica) e do contato; também `theme-color` do navegador. Como texto sobre papel, branco e creme, é a cor dos títulos de grupo dos tratamentos, dos nomes de tratamento no hover, do link "Agendar este", dos algarismos dos passos e do tique do status de envio (no CSS também como o apelido `--blue-ink`, mesmo valor). Texto branco sobre ele: 13,7:1; ele sobre creme: 11,7:1.
- **Marinho Profundo** (`blue-deep`): a faixa de resultados (antes/depois + depoimento, a "prova"), o painel do menu no celular e o fundo de espera das fotos sobre marinho. Marca a mudança de capítulo sem sair da família (branco sobre ele: 17,4:1).

### Secondary
- **Dourado Ação** (`lime`): o dourado claro que ecoa o dourado do logotipo, reservado para ação, para o botão do comparador e para a faceta do ornamento. É a única cor de envio: as duas pílulas "Enviar no WhatsApp" (seletor da abertura e formulário do contato) são douradas, com texto marinho profundo (9,6:1); também o ponto da pílula branca, o botão flutuante do WhatsApp, o botão arrastável do comparador, o sublinhado de 3px de "Agendar este" no hover, a faceta do dente facetado, o anel de foco padrão (sobre marinho, 7,5:1), `::selection` e o brilho rápido da frase ao vivo do seletor. Estados "selecionado" e "aberto" não são dourados: são marinho. **Dourado Claro** (`lime-hover`) só no hover da pílula dourada.

### Tertiary
- **Marinho Tinta** (`navy`, mesmo valor de `blue-deep`): texto de títulos sobre papel e creme, chips selecionados, botão "+" aberto do FAQ (com ícone branco), ponto da pílula dourada, régua de 2px sob os títulos de grupo dos tratamentos, link de pular para o conteúdo (pílula marinho profundo, texto branco), anel de foco sobre os elementos dourados (botão do comparador e WhatsApp flutuante), fundo do rodapé e texto sobre o dourado.

### Neutral
- **Papel** (`paper`): o fundo da página (`body`); por isso as faixas de tratamentos e FAQ, sem fundo próprio, são papel, não branco puro.
- **Branco** (`white`): cartões sobre marinho, papel ou marinho profundo (seletor, formulário, cartão do endereço, depoimento), a pílula "Agendar" e o texto sobre marinho.
- **Creme Respiro** (`sky`): faixa "primeira consulta" (medo de dentista); fundo dos chips, campos de formulário, selo do CRO, botão "+" fechado do FAQ e hover das linhas de tratamento.
- **Creme sobre Marinho** (`on-blue-soft`): leads, subtítulo, links do menu e texto suave sobre marinho (10,9:1 com `blue`). O fundo dos comparadores antes de a foto carregar usa o mesmo tom.
- **Texto** (`text`): cor padrão do corpo (12,8:1 com papel, 13,4:1 com branco).
- **Texto Secundário** (`muted`): leads, descrições, notas (5,4:1 com branco, 5,2:1 com papel, 4,6:1 com creme).
- **Linha** (`line`): divisores de 1px das linhas, passos, FAQ e borda dos campos.
- **Texto do Rodapé** (`foot-text`): texto corrido sobre marinho profundo (11,2:1).
- **Erro** (`error`, `error-border`, `error-bg`): só no campo nome inválido e na mensagem de erro (6,57:1).

O **dourado** é cor de interface, mas um só: o claro chapado (`lime`, com `lime-hover` no hover). O dourado metálico do logotipo fica no logotipo; nada de degradê, brilho ou segundo dourado na interface.

### Named Rules
**A Regra do Único Dourado.** O dourado claro marca ação e nada mais: botões de envio, o botão do comparador, o anel de foco e a faceta do dente. Selecionado e aberto são marinho. Se um elemento dourado não é clicável nem é foco, ele está errado. Sobre marinho ele passa como ícone, anel e até texto (7,5:1); sobre papel, branco ou creme não (1,8:1), então ali o dourado nunca é o único sinal: o anel de foco vira marinho e o sublinhado dourado vem junto com o texto escurecendo.

**A Regra do Campo Inteiro.** O marinho ocupa faixas de ponta a ponta, não blocos soltos dentro de uma página clara. Cabeçalho, abertura e fatos formam um só campo contínuo.

## Typography

**Display Font:** Funnel Display (com system-ui, sans-serif), auto-hospedada em `fonts/`, eixo de peso 300–800.
**Body Font:** Funnel Sans (com system-ui, sans-serif), auto-hospedada, 300–800.

**Character:** Uma família irmã de display e texto: o display é largo e leve nos tamanhos grandes, com tracking negativo, e o texto é limpo e próximo. Juntos soam modernos e amáveis, sem frieza técnica.

### Hierarchy
- **Display** (350, `clamp(2.9rem, 5.3vw, 5.2rem)`, 1.02; `clamp(2.5rem, 11.5vw, 2.9rem)` até 480px): só o título da abertura, em três linhas; a linha do meio em negrito 600 ("**ouvido antes**") carrega a ênfase.
- **Headline** (400, `clamp(2.3rem, 4.6vw, 4rem)`, 1.02, -0.03em): um título por faixa, `text-wrap: balance`.
- **Subhead** (400, `clamp(1.6rem, 2.6vw, 2.2rem)`, -0.02em): o segundo título dentro de uma faixa que junta dois assuntos: "Uma clínica nova e uma equipe inteira para você" (em "Quem cuida", máx. 22ch) e "O que dizem nossos pacientes" (em resultados). Sempre branco sobre marinho.
- **Title** (400, 1.6rem, -0.02em): o tamanho base de todo h3 (o clamp antigo saiu); usado tal como está em "Onde estamos" no cartão do endereço, e nos algarismos dos passos da primeira consulta (display 400, 1.6rem, entrelinha 1.1, em `blue`, sem círculo).
- **Fact** (500, 1.6rem): as três afirmações da faixa de fatos ("Sem pressa", "Equipe completa", "Estrutura nova").
- **Quote** (400, `clamp(1.2rem, 1.8vw, 1.5rem)`, 1.42, -0.01em): o depoimento em display, marinho, dentro do cartão branco.
- **Group** (400, 1.35rem, -0.02em, `blue`): títulos dos dois grupos de tratamento ("Saúde da boca, para toda a família", "Transformar o sorriso"), com régua marinho de 2px abaixo.
- **Row title** (500, 1.35rem, -0.015em, `navy`): nome de cada tratamento (h4) nas linhas.
- **Small display** (500, 1.1rem, -0.01em): o nome da Dra. Vilma no cartão da foto e os títulos do rodapé. A marca no cabeçalho usa display 1.35rem, no degrau do grupo (1rem abaixo de 520px).
- **Lead** (400, 1.15rem, máx. 56ch, `muted`; `on-blue-soft` sobre marinho): parágrafo de apoio logo após cada título. O subtítulo da abertura usa 1.18rem, máx. 44ch (1.05rem abaixo de 520px), e é uma frase curta só.
- **Body** (400, 17px, 1.6): base; respostas do FAQ até 65ch. A frase ao vivo do seletor usa 1rem (máx. 34ch) e o status de envio .95rem marinho.
- **Label** (600, 0.95rem): legendas do seletor (com a dica "· deslize" em 400 `muted` quando os chips viram faixa), chips (.9rem no celular), rótulos de campo (0.92rem), texto de botões (1rem; .92rem na pílula do cabeçalho no celular). Perguntas do FAQ em 600, 1.12rem; links do menu do celular em 1.15rem.
- **Caption** (600, 0.875–0.9rem): legendas sobre fotos e nos comparadores, os rótulos "Antes/Depois" (.875rem), a linha da cidade na marca; notas em .88–.9rem.

**Piso de texto: 14px** (.875rem). Nada de texto legível abaixo disso.

**A escala real de display**, do maior ao menor: 5.2rem (abertura) → 4rem (faixa) → 2.2rem (subhead) → 1.6rem (title, fact) → 1.5rem (quote) → 1.35rem (grupo, linha) → 1.1rem (small display). Novos tamanhos entram nesses degraus, não entre eles.

### Named Rules
**A Regra do Título Sozinho.** Cada faixa abre direto com o título; nada de rótulo, sobretítulo ou "eyebrow" em caixa-alta acima dele. A informação de apoio vem depois, no lead.

**A Regra do Display Leve.** Display sempre em 350–500; o peso 600 só para destacar uma expressão dentro do título da abertura.

## Layout

Página única, empilhada em faixas de largura total. O conteúdo vive num container de no máximo 1240px centralizado, e toda faixa de ponta a ponta tem 20px de respiro lateral. **Ritmo vertical em dois tempos:** faixas principais usam `--sec` (`clamp(80px, 10vw, 128px)`) em cima e embaixo; faixas de apoio levam a classe `tight` e usam `--sec-tight` (`clamp(56px, 6.5vw, 88px)`): resultados e dúvidas. A abertura começa colada no cabeçalho (20px no topo) e fecha com `clamp(56px, 8vw, 96px)`; a faixa de fatos não tem respiro superior e fecha com `--sec-tight`, para continuar o mesmo campo marinho.

**Escala de espaço** (`--s-*`, base 4): 8 / 12 / 16 / 24 / 32 / 48 / 64px (`xs`, `sm`, `md`, `lg`, `xl`, `2xl`, `3xl`). Usam essa escala: cabeçalho de tratamentos e grupos (48px), linhas (24px), galeria e depoimento (64px abaixo do bloco anterior na mesma faixa), seletor (`padding` e `margin-top` 24px, legenda 12px, fieldset 16px, chips 8px, frase ao vivo 16px), cabeçalho (vão 24px, menu 32px), formulário (`padding` 32px, vão 16px) e depoimento (`padding` 32px). Ainda ficam fora da escala: a faixa de fatos (28/22px), os comparadores (vão 20px, 44px acima), o contato (vão 20px, 40px acima, cartão do endereço 22px), os passos (18px) e os `padding` do celular do seletor (20/16/18px), do formulário (22/16px) e do depoimento (26px).

**Ritmo das faixas (de cima para baixo):** cabeçalho marinho (fixo, 84px) → abertura marinho → fatos marinho → primeira consulta creme → tratamentos papel → quem cuida marinho (Dra. Vilma + galeria da clínica numa só faixa) → resultados marinho profundo (antes/depois + depoimento, `tight`) → dúvidas papel (`tight`) → contato marinho → rodapé marinho. Nunca duas faixas claras (papel) seguidas sem um tom entre elas.

**Faixas que juntam dois assuntos:** "Quem cuida" e resultados abrem com o título da faixa (headline) e, 64px abaixo, um subhead para o segundo assunto. Nos resultados uma linha branca a 25% separa o comparador do depoimento.

**Grades:** abertura 1.22fr / .78fr (texto + seletor à esquerda, foto à direita); primeira consulta .9fr / 1.1fr; cabeçalho de tratamentos 1fr / 1fr (título + lead, vão 48px); tratamentos em dois grupos lado a lado (vão `48px clamp(32px, 5vw, 72px)`), cada linha em duas colunas (nome + descrição / botão); Dra. Vilma 1fr / 1fr; cabeçalho da clínica em linha (subhead à esquerda, texto à direita); galeria 1.25fr / 1fr com altura `min(70vh, 620px)`; comparadores 2×1fr (vão 24px, máx. 860px); FAQ .8fr / 1.2fr; contato 1.05fr / .95fr (formulário de quatro campos empilhados + foto da fachada); rodapé em três colunas 1.6fr / 1fr / 1fr (marca, "Navegue", "Siga a clínica"), vão 32px, duas colunas em 900px e uma em 520px. Vãos maiores das grades usam `clamp()`.

**Responsivo:** em 980px o menu vira um painel que desce sob o cabeçalho, aberto por um botão circular de 44px ao lado da pílula "Agendar"; a abertura vira uma coluna na ordem título → subtítulo → seletor → foto (a foto vem por último, 32px abaixo, com 380px de altura; 260px abaixo de 520px). Em 900px os grupos de tratamento, primeira consulta, Dra. Vilma, FAQ e contato viram uma coluna; em 820px os fatos empilham; em 760px a galeria e o cabeçalho da clínica empilham. Abaixo de 600px os comparadores ficam um embaixo do outro. Abaixo de 520px o cabeçalho cai para 72px (logo 40px, nome em 1rem, sem a linha da cidade, pílula compacta com ponto de 34px), os chips ficam compactos (`8px 12px`, .9rem, vão 6px), o botão do seletor ocupa a largura toda e o link "Agendar este" desce para baixo da descrição. Até 480px os chips de tratamento viram uma única faixa deslizante na horizontal (sem quebra, `scroll-snap` por proximidade, `scroll-padding` de 16px, sangrando 16px para fora do cartão, barra de rolagem oculta e uma máscara que esmaece as bordas: 14px à esquerda, 28px à direita), com "· deslize" na legenda; o título encolhe e o seletor sobe para 24px abaixo do subtítulo, para o botão de envio caber na primeira tela.

**Âncoras:** todo elemento com `id` tem `scroll-margin-top` de 96px (80px abaixo de 520px), para o título não ficar escondido sob o cabeçalho fixo.

**Toque:** em `(pointer: coarse), (max-width: 520px)` todo alvo de toque tem no mínimo 44px de altura: chips, pílula do cabeçalho, link da marca e links do rodapé (que perdem o vão de 8px entre si). A página usa `viewport-fit=cover` e o botão flutuante respeita as áreas seguras (`env(safe-area-inset-*)`). Filhos da grade da abertura e os `fieldset` do seletor têm `min-width: 0`, para a faixa deslizante não alargar a página.

**Hover só onde existe hover:** os efeitos de passar o mouse que mudam superfície ficam em `@media (hover: hover)`: a borda marinho do chip, o fundo creme da linha de tratamento e a cor marinho do nome, e o sublinhado dos links do menu. No toque eles não aparecem nem "grudam". Os hovers de botões e links (pílula dourada, link "Agendar este", fantasma do endereço, links do rodapé) seguem diretos.

**Movimento:** curva única `cubic-bezier(.16, 1, .3, 1)` (`--ease`). Estados: 0.2s (chips, fantasma, fundo do "+"), 0.25s (pílulas, linhas), 0.3s (sombra do cabeçalho, botão flutuante, giro do "+"). Entrada da abertura, só uma vez: linhas do título sobem 24px com desfoque de 6px em 1s, com atraso de 0 / .08s / .16s; subtítulo em .24s; seletor em .34s; foto se revela com `clip-path` em 1.2s. A frase ao vivo pisca dourado por .6s a cada escolha. O vídeo da abertura entra com `opacity` 0 → 1 em .8s (`--ease`) só depois de começar a tocar. `prefers-reduced-motion: reduce` desliga animações, transições e rolagem suave, e a classe `intro` nem é aplicada.

## Elevation & Depth

Sistema plano com uma única sombra ambiente. A profundidade vem da troca de cor entre faixas e de cartões brancos pousados sobre marinho ou sobre foto. A sombra existe só para o que flutua por cima de outra coisa: o botão flutuante do WhatsApp e, no cabeçalho, o próprio cabeçalho rolado e o painel do menu. O seletor, o formulário e o botão do comparador ficam sem sombra.

### Shadow Vocabulary
- **Flutuante** (`box-shadow: 0 18px 40px -18px rgba(15,29,69,.45)`, `--shadow`): só o botão flutuante do WhatsApp.
- **Cabeçalho rolado** (`box-shadow: 0 8px 24px -12px rgba(15,29,69,.5)`): aparece no cabeçalho fixo depois de 10px de rolagem.
- **Painel do menu** (`box-shadow: 0 18px 30px -18px rgba(15,29,69,.6)`): só no painel marinho profundo do menu do celular, que pende do cabeçalho. Pertence à família do cabeçalho, tingida de marinho como as outras.

As três sombras ainda usam o tom `rgba(15,29,69,…)`, o marinho da paleta anterior; ele fica perto o bastante do `navy` atual (#0f1836) para continuar lendo como sombra tingida de marinho.

### Named Rules
**A Regra de Uma Sombra.** Só existe uma sombra de elevação, sempre tingida de marinho, nunca preta. Cartões que ficam na própria faixa (linhas, passos, FAQ, cartão de depoimento) não têm sombra.

## Shapes

Formas cheias e macias, sem cantos vivos. Três famílias: o **retângulo generoso** (32px) para fotos grandes (abertura, primeira consulta, Dra. Vilma, fachada), seletor e formulário; o **retângulo médio** (20px) para galeria, comparadores, cartão do endereço e cartão de depoimento; e a **pílula/círculo** (999px / 50%) para todo botão, chip, selo e marcador, incluindo o botão do menu e o "+" do FAQ. Campos e a miniatura da Dra. Vilma usam 14px; o aviso de placeholder 12px; as linhas de tratamento 4px (visível só no hover). Bordas são raras: 1px `line` como divisor horizontal entre itens, 2px marinho sob os títulos de grupo dos tratamentos, 1.5px nos chips, campos e no botão fantasma do endereço (`currentColor`) e no botão do menu (branco a 60%), e o sublinhado de "Agendar este" (1.5px, 3px dourado no hover). Divisores sobre marinho são brancos: 35% nos fatos, 25% entre comparador e depoimento, 18% entre os links do menu do celular.

**O ornamento do dente facetado** é a única forma autoral: um SVG de traço branco (1.6px, juntas e pontas arredondadas, `viewBox 0 0 100 110`) com uma faceta triangular preenchida de dourado, ecoando o dente facetado do logotipo. Aparece **uma vez**, no canto superior direito do título do contato (`clamp(72px, 9vw, 128px)`), decorativo (`aria-hidden`). Não repita, não transforme em ícone de lista, não use como marca d'água.

### Named Rules
**A Regra do Canto Generoso.** Foto real sempre recortada com 32px ou 20px; nunca canto vivo, nunca círculo (exceto avatares de marca no cabeçalho/rodapé).

## Components

### Buttons
Pílulas confiantes com um "ponto" que convida ao toque.
- **Shape:** pílula completa (999px), `padding: 8px 8px 8px 22px`, gap 12px, texto 600 em 1rem; à direita um círculo de 40px com o ícone (seta ou WhatsApp, 20px).
- **Pílula branca** (cabeçalho, sobre marinho): fundo branco, texto marinho, ponto dourado.
- **Pílula dourada** (todo envio: seletor da abertura e formulário do contato): fundo dourado, texto marinho, ponto marinho com o ícone do WhatsApp em dourado; hover em `lime-hover`. No formulário, e no seletor abaixo de 520px, ocupa a largura toda, texto à esquerda e ponto à direita.
- **Hover / Active / Focus:** o ponto fica parado (não gira); a pílula dourada clareia para `lime-hover`; clique reduz para `scale(.98)`; foco com anel de 3px e afastamento de 3px, cuja cor depende da superfície (ver Foco).
- **Fantasma:** pílula transparente, borda 1.5px em `currentColor`, `padding: 12px 18px`, 600 em .95rem. Só no cartão do endereço: marinho, ícone de mapa à esquerda, vira marinho cheio com texto branco no hover.
- **Link "Agendar este"** (linhas de tratamento): o fantasma sem borda (borda transparente), `padding: 10px 4px`, texto marinho 600 em .95rem sublinhado (1.5px, afastamento .25em), com seta para cima à direita (aponta de volta para o seletor). No hover o texto fica marinho e o sublinhado vira dourado com 3px; o foco usa o anel marinho das faixas brancas.
- **Link de pular para o conteúdo:** pílula marinho com texto branco 600, `padding: 12px 18px`, escondida fora da tela até receber foco, quando aparece no canto superior esquerdo.
- **Botão do menu** (só abaixo de 980px): círculo transparente de 44px, borda 1.5px branca a 60%, ícone de três linhas em branco (22px). Alterna `aria-expanded` e o rótulo "Abrir menu" / "Fechar menu".
- **Flutuante do WhatsApp:** círculo dourado de 60px (56px no celular) no canto inferior direito, a 18px das bordas (12px no celular) ou mais, conforme a área segura do aparelho, com sombra flutuante; some só enquanto o seletor da abertura ou o formulário do contato estão na tela (entre 15% e 85% da altura da janela), onde já existe uma pílula dourada de envio à vista.

**Foco:** anel de 3px com afastamento de 3px (canto de 6px). Dourado é o padrão, para as faixas marinho e o cabeçalho. Marinho (`blue`) dentro de superfícies brancas, papel e creme: faixas `.on-white` e `.light`, seletor, formulário, cartão do endereço e depoimento (os chips também usam esse anel, com 2px de afastamento). Marinho profundo (`navy`) sobre os próprios elementos dourados: o botão do comparador e o WhatsApp flutuante. Os campos não usam anel: trocam a borda para marinho e o fundo para branco.

**A Regra do Único Envio.** Todo botão que envia a mensagem para o WhatsApp é a pílula dourada com o ícone do WhatsApp no ponto. Não existe variante marinho nem branca para envio; a pílula branca é só o atalho "Agendar" do cabeçalho.

### Chips (grupo de rádio)
- **Style:** rádios nativos invisíveis sobre rótulos em pílula, `padding: 9px 16px`, fundo creme, borda transparente de 1.5px, .95rem, vão 8px. Abaixo de 520px ficam compactos: `8px 12px`, .9rem, vão 6px; em telas de toque têm no mínimo 44px de altura. Até 480px os chips de tratamento rolam numa faixa horizontal (ver Layout).
- **State:** hover (só em aparelhos com hover) mostra a borda marinho; selecionado vira marinho com texto branco; foco do teclado com anel marinho de 3px. Dois grupos (tratamento e período) dentro de `fieldset` com `legend` em 600.

### Seletor "monte sua mensagem" (componente assinatura)
Cartão branco de 32px sobre o marinho da abertura, sem sombra, máx. 720px. Dois grupos de chips, depois uma linha divisória e a frase-resumo ao vivo ("Olá! Gostaria de agendar **implantes**, **à tarde**."), com as escolhas em marinho 600 piscando dourado a cada mudança, e a pílula dourada "Enviar no WhatsApp". Os botões "Agendar este" de cada tratamento preenchem este seletor e rolam de volta até ele. Toda escolha no seletor (ou por "Agendar este") também preenche os `select` de tratamento e período do formulário do contato, para a pessoa não escolher duas vezes. `padding` 24px (20/16/18px no celular).


**Sobre o marinho (desde 29/10/2026):** o seletor da abertura não é mais um cartão branco. É um painel com véu marinho `rgba(15,24,54,.55)` e borda branca a 18%, para o dente em vídeo aparecer por trás. Textos em branco; frase ao vivo em `on-blue-soft` com destaques em branco; divisor branco a 18%. Chips: fundo branco a 8%, borda branca a 28%, texto branco; selecionado vira pílula branca com texto marinho; hover (só com mouse) e foco em dourado. O status de envio aqui fica branco, com ícone e link dourados. Contraste com o vídeo no ponto mais claro: texto claro sobre o véu acima de 8:1. Não voltar a usar branco sólido nem tirar o véu (sem ele o texto cai abaixo de 4,5:1 sobre o dente).
### Status de envio
Logo abaixo de cada pílula de envio (seletor e formulário) há um parágrafo `role="status"`, escondido até o primeiro envio. Depois do clique ele mostra, em .95rem marinho, um tique de 20px em marinho e a frase "Mensagem pronta no WhatsApp, em outra aba. Não abriu?" com o link "Abrir o WhatsApp" em marinho 600. No seletor ocupa a linha inteira da frase ao vivo. Se o navegador bloquear a nova aba e não houver status por perto (links do cabeçalho e flutuante), o WhatsApp abre na mesma aba.

### Cards / Containers
- **Corner Style:** 32px (seletor, formulário) ou 20px (cartão do endereço, depoimento, comparadores, galeria).
- **Background:** branco sobre marinho, marinho profundo, papel ou creme; nunca cartão colorido sobre colorido.
- **Shadow Strategy:** só a sombra flutuante, e só para o cartão que pousa sobre uma foto (o da Dra. Vilma na abertura). O cartão do endereço também fica sobre a fachada, mas dentro do quadro da foto, sem sombra.
- **Border:** nenhuma.
- **Internal Padding:** 24px no seletor, 32px no formulário e no depoimento (máx. 820px de largura), 22px no cartão do endereço; 16–26px no celular.

### Linhas (rows)
A lista de tratamentos não é grade de cards: são dois grupos lado a lado ("Saúde da boca, para toda a família" e "Transformar o sorriso"), cada um aberto por um título de grupo em marinho, 1.35rem, com 12px de respiro e uma régua marinho de 2px embaixo. Sob ele, linhas separadas por 1px `line` (`padding: 24px 12px`), em duas colunas: à esquerda o nome (h4, display 500, 1.35rem, marinho) e a descrição `muted` (máx. 52ch); à direita o link sublinhado "Agendar este", centrado na altura das duas linhas. Em aparelhos com hover, a linha fica creme e o nome marinho. Abaixo de 520px o link desce para baixo da descrição. Os passos da primeira consulta seguem a mesma lógica: linhas com divisor e, numa coluna de 52px, o algarismo em display 1.6rem marinho, sem círculo nem fundo. A faixa de fatos usa três colunas com divisores brancos a 35%.

### Inputs / Fields
- **Formulário do contato:** quatro campos empilhados, um por linha (nome, melhor período, tratamento, convênio); não há campo de telefone.
- **Style:** fundo creme, borda 1.5px `line`, canto 14px, `padding: 15px 16px`, texto marinho 1rem, cursor marinho; rótulo 600 em .92rem acima; placeholder `#56607d` (5,3:1 sobre creme). O `select` usa uma seta SVG marinho embutida.
- **Focus:** borda marinho e fundo branco.
- **Error:** borda `error-border`, fundo `error-bg` e mensagem `error` em .88rem logo abaixo, ligada por `aria-describedby`.

### Navigation
Cabeçalho fixo marinho de 84px (72px no celular): logotipo em círculo branco de 46px + nome em display 1.35rem com a linha "Dentista em Caçapava · SP" em .875rem; menu com cinco links (Primeira consulta, Tratamentos, Quem cuida, Dúvidas, Contato) em creme (.98rem, vão 32px) que ficam brancos e sublinhados no hover (só em aparelhos com hover); pílula branca "Agendar" à direita; vão de 24px entre os blocos.

**Menu do celular** (abaixo de 980px): o botão circular de 44px fica ao lado da pílula "Agendar" (vão 12px; 8px no celular). Ele abre um painel marinho profundo de largura total logo abaixo do cabeçalho (`padding: 12px 20px 24px`, sombra do painel do menu), com os links empilhados em branco, 1.15rem, `padding: 14px 0`, separados por linhas brancas a 18%. Fecha ao tocar num link ou com Esc (o foco volta para o botão). Abaixo de 520px a marca perde a linha da cidade, o nome cai para 1rem e o logo para 40px; em telas de toque o link da marca e a pílula têm no mínimo 44px de altura.

**Rodapé:** marinho, três colunas: marca com uma frase, "Navegue" (seis links) e "Siga a clínica" (Instagram com ícone e um link "Endereço e horários" que leva ao contato). Títulos em small display branco, links em `foot-text` que ficam brancos e sublinhados no hover. Endereço e horário moram só no cartão "Onde estamos". A linha legal fica abaixo, com divisor branco a 14%, em .9rem.

### Selo do CRO e legendas de foto
O CRO da Dra. Vilma é uma pílula creme simples, texto marinho 600 em .95rem, `padding: 8px 16px`, sem ponto nem ícone: "Responsável técnica · CRO/SP 92590". Os itens da lista de formação dela, logo abaixo, levam um tique de 20px em branco (não dourado) e texto em `on-blue-soft`. Na abertura o mesmo fato aparece no cartão branco da Dra. Vilma sobre a foto (miniatura de 58px com canto 14px, nome em small display e a linha do CRO em .875rem `muted`). Legendas de foto são pílulas brancas no canto inferior esquerdo (galeria, .9rem) ou marinho no canto superior esquerdo (comparador, .875rem).

### Comparador antes/depois
Quadro quadrado de 20px (1/1) com barra marinho de 2px e um botão dourado de 48px com setas, sem sombra; com foco do teclado o botão ganha anel marinho de 3px. Rótulos "Antes" e "Depois" em 600, .875rem. O `input range` nativo fica invisível por cima só para o teclado (`pointer-events: none`); o arraste é feito pelo próprio quadro (`touch-action: pan-y`): com mouse, arrasta na hora; com o dedo, só começa a arrastar depois de um movimento horizontal de mais de 8px, e um gesto vertical continua rolando a página. Casos reais (`.ba.real`): as fotos de antes e depois cobrem o quadro (`object-fit: cover`, com `object-position` ajustado para alinhar o sorriso na divisão), barra branca e rótulos "Antes"/"Depois" em pílula marinho translúcida. Um comparador só entra quando há foto real e autorizada; sem foto, o caso não aparece.

### Mapa do sorriso (Tratamentos)
Ao lado do título "Do check-up ao implante" (grade 1fr / 1fr; empilha abaixo de 900px), a foto real do "depois" das lentes (`imagens/lentes-depois.png`, quadro de 32px, proporção 472/395, máx. 560px) leva três pontos: **Lentes de contato** (dentes da frente), **Clareamento** e **Ortodontia**. Cada ponto é um `button` de 44px com um círculo dourado de 18px e anel marinho de 3px; enquanto não está ativo, um anel dourado pulsa (2.4s, escala 1 → 2.6). Um ponto se ativa por clique, toque, hover ou foco (`aria-expanded`, `aria-controls`); o primeiro abre sozinho quando o mapa entra na tela. Ao ativar, uma linha dourada de 2.5px (SVG por cima da foto, sem captura de clique) se desenha em .6s com a curva `--ease` até a borda mais próxima da etiqueta, e a etiqueta entra com esmaecer e subida de 8px (.35s, atraso .25s). A **etiqueta** é um cartão branco de 20px com a sombra flutuante, título em display 1.2rem, uma frase em `muted` e o link "Agendar este", que preenche o tratamento no seletor da abertura e no formulário do contato. No computador a etiqueta fica no alto da foto (à direita ou à esquerda, oposta ao ponto); abaixo de 600px ela desce para baixo da foto, em largura inteira, e a linha a acompanha. Uma linha de ajuda com um ponto dourado ("Toque nos pontos do sorriso…") fica sob o lead. A foto é um caso real autorizado; não usar foto de banco nem ilustração aqui.

### Vídeo da abertura
Marca d'água em movimento na faixa da abertura, que não tem mais foto: o conteúdo (título, subtítulo e seletor) ocupa uma coluna de até 820px à esquerda e o vídeo preenche o resto. `video/hero.mp4` é o primeiro filho da `section.hero` (`isolation: isolate`), em `position:absolute`, `z-index:-1`, mudo, em loop, `playsinline`, `preload="none"`, `aria-hidden` e fora da ordem de foco. Tratamento: `filter: grayscale(1) brightness(.62) contrast(5)` (o fundo claro do vídeo some e só o dente e as bolhas ficam claros), `mix-blend-mode: screen` sobre o marinho e máscara radial que apaga as bordas. **Computador (>980px):** o vídeo começa em 36% da largura e ocupa 70%, então o dente fica no lado direito livre, ao lado do texto, com opacidade .34. **Tablet e celular (≤980px):** ocupa a largura inteira e 70% da altura, atrás do título, com opacidade .2; esse teto mantém o subtítulo (#ece5d6) perto de 5,9:1 e o título branco perto de 7,5:1, então não subir. O arquivo só é pedido quando a pessoa não pediu menos movimento nem economia de dados; aparece com um esmaecer de 1.2s quando começa a tocar, e se der erro a camada sai sem deixar marca.

**Escolha da clínica (29/10/2026):** a abertura não tem foto da equipe; a identidade da abertura é o título, o seletor e o dente em marca d'água. A equipe real aparece em "Quem cuida" (Dra. Vilma e galeria). Não estender o dente 3D para outros pontos da página.

### Prova (resultados)
A faixa marinho profundo junta as duas provas: dois casos reais (lentes de contato e clareamento) em comparadores quadrados lado a lado, numa grade de no máximo 860px, a nota de autorização em `on-blue-soft` .88rem e, depois de uma linha branca a 25% (64px acima, 48px abaixo), o subhead "O que dizem nossos pacientes" e o cartão de depoimento branco de 20px com a citação em display marinho. Sem nota, sem estrelas: o cartão fica com o texto entre colchetes até haver depoimento real.

### FAQ
`details` com divisor `line`; pergunta em 600, 1.12rem, marinho; à direita um círculo creme de 36px com "+", que gira 45° e fica marinho com ícone branco quando aberto. Não há hover em dourado.

## Do's and Don'ts

### Do:
- **Do** dar ao marinho faixas inteiras de ponta a ponta e alternar com papel e creme, fechando em marinho profundo.
- **Do** usar o dourado claro (#d8bd86) só para ação: pílulas de envio, ponto, botão flutuante, botão do comparador, sublinhado de hover, foco sobre marinho, e a faceta do ornamento. Selecionado e aberto ficam em marinho.
- **Do** usar a pílula dourada para todo envio ao WhatsApp, no seletor e no formulário.
- **Do** tirar o espaço novo da escala `--s-*` (8 / 12 / 16 / 24 / 32 / 48 / 64px) e o respiro das faixas de `--sec` ou `--sec-tight`.
- **Do** usar fotos reais da clínica, equipe e Dra. Vilma, recortadas com 32px ou 20px.
- **Do** abrir cada faixa direto com o título em Funnel Display leve, seguido do lead em `muted`.
- **Do** mostrar o CRO/SP 92590 da Dra. Vilma junto ao nome dela sempre que ela aparecer como responsável.
- **Do** deixar marcado e vazio (entre colchetes) o lugar de prova que ainda não existe.
- **Do** manter texto em AA: branco sobre `blue` (13,7:1), marinho profundo sobre dourado (9,6:1), `muted` sobre branco (5,4:1) e sobre creme (4,6:1, o mínimo; não use `muted` em fundo mais escuro que o creme).
- **Do** manter o movimento restrito à entrada da abertura, ao vídeo opcional da abertura e a respostas de interação, sempre com `--ease`, e desligar tudo em `prefers-reduced-motion`.
- **Do** escolher a cor do anel de foco pela superfície: dourado sobre marinho, marinho sobre branco, papel e creme, marinho profundo sobre dourado.
- **Do** pôr os hovers que mudam superfície (borda, fundo, sublinhado decorativo) dentro de `@media (hover: hover)`.
- **Do** manter a foto real por baixo de qualquer vídeo, para ela aparecer quando o vídeo não carrega.
- **Do** dar a cada envio um status visível com um link de reserva para abrir o WhatsApp.

### Don't:
- **Don't** colocar rótulos, sobretítulos ou "eyebrows" em caixa-alta acima dos títulos.
- **Don't** usar cards com ícone em quadradinho (icon tiles); tratamentos são linhas, não grade de ícones.
- **Don't** usar texto em degradê nem degradês decorativos em superfícies; não há degradê visível no site. A máscara que esmaece as bordas da faixa de chips é funcional, não decoração.
- **Don't** inventar notas, estrelas, número de pacientes, depoimentos ou métricas; só entram quando houver avaliações reais e autorizadas.
- **Don't** usar fotos de banco de imagem, ilustração genérica de dente ou fotos do Instagram com texto sobreposto.
- **Don't** repetir o ornamento do dente facetado; o SVG aparece uma vez, no contato. O dente do vídeo da abertura é realista, não facetado, e não conta como repetição.
- **Don't** usar mais de um dourado: o de interface é o claro chapado (`lime`, #d8bd86, e `lime-hover` só no hover); nada de dourado metálico, degradê ou brilho.
- **Don't** cair no branco-hospitalar com dente de ícone nem no luxo distante (preto, dourado metálico, cerimônia). Marinho e dourado são escolha confirmada da clínica (29/10/2026) e se apoiam no creme e no papel, nunca no preto.
- **Don't** usar o dourado como texto corrido nem como único sinal sobre papel, branco ou creme (1,8:1), nem um segundo acento além do dourado.
- **Don't** criar outra cor de botão de envio; a pílula marinho foi retirada.
- **Don't** criar tamanhos de display fora da escala 5.2 / 4 / 2.2 / 1.6 / 1.5 / 1.35 / 1.1rem.
- **Don't** criar novas sombras; só a flutuante tingida de marinho para o que paira sobre outra coisa (WhatsApp flutuante) e as duas do cabeçalho (rolado e painel do menu). Seletor, formulário e botão do comparador ficam sem sombra.
- **Don't** pôr texto abaixo de 14px nem alvos de toque abaixo de 44px.
- **Don't** fazer o ponto da pílula girar nem usar pontinhos dourados decorativos em selos e listas.
