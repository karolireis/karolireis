# Entregas Expressas — Direção de arte para produção
**Data:** 26/08/2026
**Cliente:** Entregas Expressas (entregasexpressas.com.br)
**Origem do copy:** `clientes/entregas-expressas/copy/2026-08-26-pilar1-pilar4-copy.md` (copywriter)
**Autor:** social-media-designer
**Status:** ⚠️ **Proposta de direção visual a validar com o cliente — não existe guia de marca oficial confirmado.** Não encontrei identidade visual definida em repositório ou em conversas anteriores, e o site (entregasexpressas.com.br) não pôde ser acessado a partir deste ambiente para extrair logo/paleta real. A direção abaixo é uma proposta coerente com o segmento (tech/logística B2B com bastidor humano), não uma identidade oficial. Antes de produção final em escala, confirmar com o cliente: logotipo real, paleta oficial (se já existir) e qualquer restrição de marca.

---

## 0. Arte publicada

A arte do carrossel (Peça 1, 8 slides prontos) e um guia visual navegável das 3 peças foram publicados como Artifact:
**https://claude.ai/code/artifact/32618d27-3a30-476e-89fa-2db1c621de62**

Nota técnica: o ambiente de execução usado para esta entrega não tinha acesso a terminal/shell, então a arte foi produzida como uma página HTML autocontida publicada diretamente via Artifact (galeria com os 8 slides em tamanho real de exportação, 1080×1350, mais o sistema visual e o guia de referência dos dois reels) — não pelo editor visual "Claude Design" (que normalmente permite edição ponto-a-clique). Isso significa que o cliente pode ver, mas não editar diretamente essa versão pelo Artifact; ajustes precisam ser pedidos numa nova iteração ao designer. Os slides do carrossel estão prontos para exportação/recorte em ferramenta de design (Figma, Canva etc.) a partir das especificações abaixo.

## 1. Direção visual proposta (a validar)

**Racional:** o comprador é dono de empresa de entregas — precisa confiar que o produto é robusto o suficiente pra rodar a operação dele (tech B2B, confiável, "painel de verdade"), mas duas das três peças mostram bastidor humano (entregador na chuva, rotina de trabalho) — a direção não pode parecer fria/corporativa a ponto de destoar desse tom. A proposta busca meio-termo: base de confiança (azul-marinho + tipografia geométrica firme) com um acento de energia/movimento (laranja) que remete a delivery/urgência sem cair no clichê "app de comida vermelho-e-amarelo".

### Paleta (hex de proposta)

| Papel | Cor | Hex | Uso |
|---|---|---|---|
| Primária (confiança/marca) | Azul-marinho "Entregas Blue" | `#1B2A55` | Fundos de destaque, texto de headline em fundo claro, bloco de solução |
| Acento (energia/ação) | Laranja "Expressa" | `#FF6A3D` | CTA, destaques numéricos, ícones de alerta, elemento de contraste no hook |
| Positivo (ganhos/sucesso) | Verde-água "Ganho" | `#16C79A` | Usado só onde o assunto é dinheiro/resultado positivo (ex.: cena de conferir ganhos, bullet "sem taxa de setup") — não é cor de marca, é cor de contexto |
| Base clara (não-branco frio) | Off-white "Papel" | `#FAF7F2` | Fundo padrão dos slides de conteúdo — mais quente que branco puro |
| Texto/tinta | Grafite | `#14161F` | Texto de corpo sobre fundo claro |
| Neutro de apoio | Cinza-azulado | `#8A93A8` | Textos secundários, legendas, watermark de marca |

Regra de aplicação: **cada peça usa no máximo 2 cores de destaque por tela** (uma de fundo/estrutura + uma de acento), nunca as três cores fortes (azul, laranja, verde) juntas na mesma composição — verde fica reservado só para os momentos de "ganho/resultado".

### Tipografia (proposta)

- **Display/headline:** uma geométrica bold e firme — referência: *Sora* ou *Archivo Black* (peso 700–800). Usada em hook, CTA e números grandes. Poucas palavras por linha, muito respiro.
- **Corpo/apoio:** uma humanista neutra, alta legibilidade em tela pequena — referência: *Inter* ou *Manrope* (peso 400–600). Usada em textos de desenvolvimento e legendas.
- Tamanho mínimo recomendável no carrossel: 44px equivalente para corpo de texto em 1080px de largura (legibilidade em thumbnail de feed); headline de capa e CTA podem ir a 90–120px.

### Estilo geral

- Alto contraste tipo "capa jornalística" nos momentos de gancho e fechamento (slide 1 e 8 do carrossel; abertura e CTA dos reels).
- Clean/minimalista no desenvolvimento — um problema, um ícone de apoio, respiro generoso, sem poluição.
- Iconografia de linha (stroke, não preenchida), simples, remetendo a dispatch/rota/mensagem/cobrança — não usar ilustração cartoon fofa, o tom é prático, não infantilizado.
- Fotografia/vídeo (reels): realista, luz natural, nada de still de banco de imagem genérico "sorriso forçado corporativo" — o entregador é o protagonista humano da marca nesses dois formatos.

---

## 2. Peça 1 — Carrossel, 8 slides (feed 1080×1350)

**Grid consistente em todo o carrossel:** margem de 96px em todos os lados, logotipo/watermark discreto sempre no canto inferior direito (24px de margem interna, baixa opacidade ~60%), numeração de slide discreta no canto inferior esquerdo (ex. "1/8") em cinza-azulado.

**Curva de contraste:** máximo no slide 1 (hook) e no slide 8 (CTA); intermediário nos slides 2–4 (bloco de problema, ritmo de lista); pico de tratamento gráfico no slide 5 (dado numérico); virada de cor no slide 6 (problema → oportunidade); tom "produto" no slide 7.

| Slide | Fundo | Hierarquia (destaque → apoio) | Composição | Notas |
|---|---|---|---|---|
| **1 — Capa/hook** | Azul-marinho `#1B2A55` cheio | 1) Headline em branco/laranja, quebrada em 3 linhas curtas conforme o copy 2) tag pequena "custo invisível da operação" em laranja, acima da headline 3) watermark de marca | Headline centralizada verticalmente, tipografia display grande (90–110px), muito espaço negativo ao redor — nada mais compete com o texto | Contraste máximo: fundo escuro + texto claro + acento laranja. É o frame que precisa parar o scroll. |
| **2 — Problema 1 (rota sem dispatch)** | Off-white `#FAF7F2` | 1) Texto do problema em grafite, tipografia corpo grande (56–64px) 2) ícone de linha de "rota/pino desorganizado" em laranja, topo do slide 3) tag "01" pequena | Ícone centralizado no topo, texto abaixo alinhado à esquerda, respiro nas laterais | Primeiro slide do bloco de 3 — define o padrão que se repete |
| **3 — Problema 2 (comunicação manual)** | Off-white `#FAF7F2` (idêntico ao slide 2) | Mesma hierarquia do slide 2 | Ícone de linha "balão de mensagem + papel" no mesmo grid do slide 2 | Repetir exatamente posição/tamanho do ícone e do texto — dá ritmo de lista/checklist ao rolar |
| **4 — Problema 3 (cobrança sem controle)** | Off-white `#FAF7F2` (idêntico) | Mesma hierarquia | Ícone de linha "lupa/detetive + cifrão" no mesmo grid | Fecha o bloco de 3 problemas — consistência é o ponto, não variação |
| **5 — Dado de mercado** | Off-white `#FAF7F2` | 1) Dois números grandes em laranja e azul-marinho ("78%" e "26%"), tipografia display 130–150px 2) frase curta de contexto abaixo de cada número, tipografia corpo 3) nota de rodapé minúscula "Dados de pesquisa de mercado, 2026" em cinza-azulado, canto inferior | Dois blocos numéricos empilhados ou lado a lado (empilhado funciona melhor em 1080×1350 vertical), separados por linha fina laranja | Tratamento de dado: número é o herói da tela, texto de apoio é só legenda |
| **6 — Bridge (virada)** | **Muda para azul-marinho `#1B2A55`** — quebra intencional de fundo | 1) Texto da virada em branco, tipografia corpo grande 2) linha final em destaque laranja ("Só que isso não escala numa planilha.") | Texto centralizado, composição mais respirada que os slides 2–4 | Esta é a quebra de cor de fundo sinalizada no roteiro — marca a virada problema→oportunidade. Único slide de conteúdo com fundo escuro. |
| **7 — Solução (produto)** | Azul-marinho `#1B2A55` (continua do slide 6) | 1) Texto de apresentação do produto em branco 2) fileira de 4 ícones de linha (dispatch, rastreio, app do entregador, cobrança) em laranja, com legenda curta sob cada um 3) menção ao IAGo com ícone de "assistente/chat" separado, levemente destacado | Bloco de texto no topo, fileira de ícones no meio, menção ao IAGo como elemento final antes do slide de fechamento | Único slide com "grid de produto" (4 ícones) — reforça robustez sem virar print de tela |
| **8 — Fechamento + CTA** | Laranja `#FF6A3D` cheio (inverte para a cor de acento como protagonista) | 1) CTA em azul-marinho ou branco, tipografia display grande, botão/pill visual "Criar conta grátis" 2) 3 bullets curtos (gratuito pra sempre / sem taxa de setup / paga só pelo que usa) em corpo menor 3) "Link na bio" em destaque final | CTA centralizado, bullets em lista compacta acima, sensação de botão clicável (pill com contorno ou preenchido) mesmo sendo estático | Contraste máximo de volta — é o slide de conversão. Laranja cheio quebra o padrão azul/off-white de propósito, funciona como "última parada" visual do carrossel. |

---

## 3. Peça 2 — Reels cômico, 6 cenas (referências visuais, sem produção de vídeo)

**Papel da marca:** quase invisível. A marca não é protagonista nesta peça — é reconhecimento de canal, não venda. Logotipo pequeno e discreto (opacidade reduzida, canto inferior) **só no último frame** (cena 6), no tamanho de um watermark, nunca como elemento de composição.

**Paleta em tela:** natural/realista (chuva, rua, luz de fim de tarde/manhã nublada) — **não** forçar a paleta de marca (azul/laranja) no cenário ou figurino. A identidade aparece só nos textos on-screen (tipografia) e no watermark final.

**Tipografia on-screen (legendas):** usar a família de corpo (Inter/Manrope), peso 600–700, branca com contorno/sombra sutil para garantir legibilidade sobre qualquer fundo (chuva, rua, variação de luz) — nunca depender só da cor de marca para contraste, porque o fundo muda cena a cena.

**Figurino e cenário — diretrizes:**
- Entregador: uniforme/casaco de chuva funcional e realista (pode ter um detalhe discreto em laranja — braçadeira, capa impermeável — como nod sutil de marca sem virar propaganda), mochila de entrega (térmica, genérica, sem logo de terceiros como iFood/marketplace estampado, já que ele atua para uma empresa de courier própria, não para um marketplace específico).
- Veículo: moto ou bike, neutro, sem adesivo de marketplace de comida — reforça a correção de público (courier próprio, não entregador de app de restaurante).
- Cenário: rua urbana real, chuva, prédio residencial simples — nada de cenário "produzido"/estúdio. Tom documental-cômico, tipo flagrante do dia a dia.
- Luz: natural, cinza de dia chuvoso — contraste vem da situação (chuva, susto, sorriso), não de iluminação artificial de marca.

**Cena a cena — nota visual:**
| Cena | Referência visual | Enquadramento sugerido |
|---|---|---|
| 1 — Hook | Plano fechado, entregador olhando pro céu embaixo de toldo pequeno, chuva visível em primeiro plano | Close/médio, câmera na altura dos olhos, chuva desfocada em frente à lente pra dar sensação de "estar ali" |
| 2 — Notificação | Close no celular + expressão facial | Plano médio, celular ocupa canto do quadro, rosto no centro |
| 3 — Poças | Travelling lateral acompanhando o entregador andando | Plano aberto/médio, câmera baixa pra pegar as poças no chão |
| 4 — Interfone | Plano médio-fechado, entregador encolhido, porta fechada em foco | Estático, tensão de espera |
| 5 — Virada | Dois planos: porta abrindo (POV do entregador) + reação de sorriso | Corte rápido entre os dois |
| 6 — Fechamento | Plano aberto, ele se afasta a pé/moto, câmera segue de longe | Wide, logotipo discreto surge só no congelamento final do frame |

---

## 4. Peça 3 — Reels "um dia na vida", 5 cenas (referências visuais, sem produção de vídeo)

**Papel da marca:** também discreto ao longo do vídeo — a única aparição de marca "de verdade" é a **interface mockada do app na cena 4**. Fora isso, sem overlay de logo adicional.

**Paleta em tela:** realista nas cenas 1–3 e 5 (luz de manhã cedo na cena 1, luz de rua/trânsito nas cenas 2–3, luz dourada de fim de tarde na cena 5 — arco de luz natural acompanhando a passagem do dia). Na **cena 4**, a paleta de marca (azul-marinho + verde "ganho" + laranja de acento) aparece de forma controlada, mas só dentro da tela do celular mockado — o entregador ao redor continua em luz/cor realista.

**Mockup da interface (cena 4) — diretrizes:**
- Tela de "ganhos do dia" do app do entregador, com estética consistente com a paleta de marca proposta (fundo `#FAF7F2` ou `#1B2A55`, número de destaque em verde `#16C79A` para indicar "positivo", elementos de navegação em azul-marinho).
- **Nenhum valor numérico real ou inventado** — usar placeholder tipo "R$ •••" ou um blur/skeleton sutil sobre o número, ou ainda um número claramente fictício e genérico do tipo mockup de design system (ex. "R$ 0,00" estilizado como placeholder, nunca um valor que pareça dado real de ganho).
- Foco visual na **ação** de deslizar/atualizar a tela, não no número em si — pode usar indicador de "atualizando em tempo real" (ex. pequeno ícone de sincronização/pulso).
- Elementos de UI simples, cantos arredondados, tipografia Inter/Manrope — consistente com o restante da proposta visual, mas sóbrio (é uma tela de trabalho, não uma peça de venda).

**Figurino e cenário — diretrizes:**
- Mesma lógica da Peça 2: uniforme funcional, sem logos de marketplace de terceiros, mochila térmica neutra.
- Cenas 2–3: variedade de trajeto (rua, prédio, campainha, porteiro) pra reforçar "vários destinos, uma correria só" sem precisar mostrar logo de cliente específico.
- Cena 4: importante transmitir alívio/satisfação física (tirar capacete, sentar, respirar) antes de abrir o app — o gesto de conferir ganhos é recompensa, não trabalho.
- Cena 5: luz dourada, ele sai satisfeito — fecha o arco de luz do dia (manhã cinza → tarde dourada) como reforço narrativo sutil, sem precisar de texto extra pra isso.

**Cena a cena — nota visual:**
| Cena | Referência visual | Enquadramento sugerido |
|---|---|---|
| 1 — Hook | Despertador, mão, luz de manhã ainda fraca/azulada | Close no despertador → médio no entregador se espreguiçando |
| 2 — Setup | Vestindo jaqueta, pegando capacete, celular com notificações genéricas (ícones, sem citar marca de terceiro específica em destaque) | Plano médio, ritmo ágil de corte |
| 3 — Montagem | Cortes rápidos (trânsito, escada, campainha, aceno, porteiro) | Sequência de planos curtos, 1–2s cada, ritmo de montagem |
| 4 — Ganhos | Sentado, capacete no colo, tela do celular em foco (mockup de marca) | Close no rosto (alívio) → close na tela do celular (mockup) |
| 5 — Fechamento | Luz dourada, ele sai satisfeito, câmera acompanha | Plano médio/aberto, movimento de saída, sem CTA visual forte — o texto carrega o CTA |

---

## 5. Atualização com dados confirmados (recebidos após a primeira versão desta direção)

Chegou confirmação factual via `clientes/entregas-expressas/analise/2026-08-26-funcionalidades-confirmado.md` (conteúdo real da página entregasexpressas.com.br/funcionalidades). Isso não muda o direcionamento das 3 peças, mas ajusta dois pontos da proposta visual:

**a) Prova social real (não é mais dado a evitar).** "Mais de 50 milhões de entregas processadas para mais de 2 mil empresas" é o número oficial do site. Não uso esse número para reescrever a copy aprovada (a copy do carrossel já está fechada e não é papel do design alterar texto do copywriter), mas adiciono um **badge de credibilidade discreto** no slide 8 do carrossel — elemento visual adicional, pequeno, abaixo dos bullets e acima do CTA, sem competir com a hierarquia principal do slide. É uma opção de reforço; pode ser removido sem prejuízo se o cliente preferir o slide 8 mais limpo.

**b) Linguagem visual real do produto (dashboard operacional).** O site confirma que a interface real usa: cards de pedido com status (`Pendente` / `Coletado` / `Em rota` / `Entregue`), badge "Ao vivo", mapa com pins de entregadores em tempo real, e painel de carteira digital com saldo e extrato. Isso substitui qualquer suposição genérica de "app consumer" nas peças que tocam em produto:

- **Carrossel, slide 7 (solução):** o ícone de "Rastreio" ganha uma pequena marcação "tempo real" para ecoar a linguagem real do produto (mapa ao vivo), sem virar print de tela — o slide continua sendo ilustração de linha, não mockup de UI.
- **Peça 3, cena 4 (conferindo os ganhos) — atualização da diretriz de mockup:** o mockup deve usar o vocabulário real da interface — card de "saldo do dia" com badge **"Ao vivo"**, lista tipo extrato abaixo, sem valor numérico real ou inventado (manter placeholder). Isso é mais fiel ao produto do que um mockup genérico de carteira digital.
- **Nuance de white-label — importante para os dois Reels:** o app do entregador e o painel do cliente da Entregas Expressas são **white-label** — quem aparece de marca no app é a empresa de entregas que contratou a plataforma, não "Entregas Expressas". Ou seja, o mockup de app na cena 4 da Peça 3 **não deve estampar o logotipo "Entregas Expressas" como se fosse a marca do app do entregador** (isso não corresponde à realidade do produto). Proposta: usar uma UI neutra, sem marca de terceiro nem marca "Entregas Expressas" em destaque — só uma etiqueta discreta e genérica tipo "app do entregador" na barra superior do mockup, mais fiel ao que o entregador realmente vê no dia a dia. Se o cliente quiser reforçar reconhecimento de marca mesmo assim (é conteúdo do canal da Entregas Expressas, afinal), isso é uma decisão de negócio a validar com ele, não uma escolha unilateral de design.

## 6. Pendências para o cliente

1. Confirmar se existe manual de marca, logotipo em vetor e paleta oficial da Entregas Expressas — a proposta acima assume um território visual coerente com o segmento, mas deve ser substituída pela identidade real assim que disponível.
2. Validar se o laranja `#FF6A3D` e o azul-marinho `#1B2A55` não colidem com marca já registrada/usada pelo cliente em outros canais (app, site).
3. Confirmar disponibilidade de gravação real para os Reels (Peças 2 e 3) — as diretrizes acima assumem produção com ator/entregador real, não motion/stock.
