**Prompt de produção de imagens**

Ilustrações, infográficos e diagramas técnicos para livros técnicos e didáticos.

Arq. Flávio Nese

Versão 1, 11 de outubro de 2026 · Versão 1.1 do agente, 12 de outubro de 2026 (decisões do autor: legenda de 15 linhas; figura no ponto exato em que é citada; leitor da lâmina e das legendas definido em cada livro; texto corrido em Times New Roman 12)

*Este documento é independente de qualquer título e de qualquer gerador de imagens. Vale para todos os livros técnicos e didáticos do autor. O livro em trabalho é chamado apenas de "o livro" ou "\[Nome do livro\]". O texto, as tabelas e os quadros têm prompt próprio, no documento "Prompt de produção de livros: textos, tabelas e quadros", que acompanha este.*

**0. Campos a preencher antes de usar**

Preencha os campos abaixo e mantenha o bloco no início do prompt. Os valores entram nas linhas 1 a 12 de todos os prompts de figura do livro.

| **Campo** | **Valor para este livro** |
|---|---|
| Título do livro | \[Nome do livro\] |
| Assunto em uma linha | \[por exemplo: estruturas para arquitetos e engenheiros\] |
| Público das figuras | \[por exemplo: o arquiteto; o arquiteto e o engenheiro; o arquiteto e o dono do empreendimento\] |
| Cor de destaque | \[nome e código hexadecimal; uma só\] |
| Cor de função | \[nome, código e o que ela marca: cargas, portões de decisão, fluidos, zonas; uma só, ou "nenhuma"\] |
| Cor de superfícies e painéis | \[cinza-claro \#E6E6E6 ou bege quente \#F4F1EE\] |
| Linguagem visual predominante | \[diagrama técnico vetorial em sépia; infográfico técnico ilustrado colorido; ou os dois, escolhidos por figura\] |
| Número de figuras | \[N\] |

**1. Para que serve e como usar**

Este documento define como as figuras dos livros do autor são especificadas e geradas. Ele produz o Documento 2 de cada livro, "\[Nome do livro\]: figuras e prompts", com uma entrada por desenho, e orienta a geração de cada imagem em qualquer IA que produza SVG ou PNG. As regras valem para ilustrações, infográficos, diagramas, esquemas, cortes, plantas esquemáticas e gráficos; não valem para fotografias, reproduções e capturas de tela, que não recebem prompt e vão para o quadro final (seção 8).

A IA que lê este documento tem duas tarefas possíveis: escrever os prompts das figuras a partir do texto do livro, ou gerar as imagens a partir de prompts já escritos. Nos dois casos, a primeira pergunta é o título do livro, se não tiver sido informado; a segunda, a paleta, se o bloco da seção 0 estiver em branco.

**2. Regras gerais, válidas para toda figura**

1.  **Página inteira A4 retrato.** Toda figura é concebida para ocupar uma página A4 inteira (210 x 297 mm) na posição retrato, com título no alto da página e legenda abaixo. Nenhuma figura é pensada para meia página ou para a posição paisagem.

2.  **Legibilidade acima de tudo.** Pouco texto dentro da imagem: no máximo seis a oito rótulos curtos. Texto demais sai pequeno na impressão. O que precisa de explicação longa vai para a legenda do livro, não para a imagem. Tamanho mínimo de qualquer texto na imagem: 8 pt no tamanho final de impressão.

3.  **Fidelidade ao conteúdo.** A figura mostra o que o texto do livro diz, com os termos e os números do texto. Nenhum dado, rótulo ou valor é inventado; onde falta dado, escreve-se "valor a confirmar".

4.  **SVG como entrega preferencial.** O original de toda figura é entregue em SVG, com textos e formas preservados como elementos separados e editáveis. Acompanha uma versão em PNG para visualização e para o Word do livro. Converter ou incorporar um PNG num SVG não torna os elementos editáveis; o SVG precisa nascer vetorial.

5.  **Textos em camada própria.** Quando a figura tem muitos textos ou vai passar por revisão, a composição é planejada em duas camadas desde a produção: a ilustração de base e uma camada separada de textos, legendas e setas. Isso permite corrigir uma palavra sem refazer o desenho.

6.  **Uma só linguagem visual por figura**, escolhida entre as duas da seção 3, segundo o objetivo didático. Não misturar as duas na mesma página.

7.  **Paleta do livro em todas as figuras.** Uma cor de destaque, uma cor de função (se houver), grafite para linhas e textos, cinza-claro ou bege para superfícies e painéis, branco nos preenchimentos. Fundo do arquivo transparente, com moldura cinza-claro de contorno da área da página.

8.  **Tipografia Verdana** em toda a imagem, com todos os acentos do português preservados. Todo texto dentro da imagem em português do Brasil.

9.  **Título dentro do arquivo**, fora da área do desenho, na parte superior da página, sempre com o número: "Figura N.M, Título". O título em texto que aparece acima da figura no Word do livro serve de marcador para a diagramação e sai quando a imagem definitiva entrar.

10. **Impressão em preto e branco.** A leitura da figura não pode depender da cor: a cor de destaque e a de função são apoio; a hierarquia é dada por espessura de linha, preenchimento e posição.

11. **Sem logotipos, marcas, marcas d'água, pessoas identificáveis ou fotografias**, salvo pedido expresso na entrada da figura.

12. **Convenções brasileiras de desenho técnico** para apoios, cotas, hachuras, cortes e símbolos; convenções de fluxograma (losango para decisão, retângulo para fase ou documento) nos diagramas de processo.

**3. As duas linguagens visuais**

Cada figura adota uma das duas linguagens abaixo, definida na linha 2 do prompt. A escolha segue o objetivo didático: diagramas para processos, sequências, hierarquias, relações, cortes e esquemas; infográficos ilustrados para espaços, instalações, sistemas e cenas que o leitor precisa reconhecer. A regra geral é: os desenhos mais técnicos vão em diagrama vetorial, em sépia; os infográficos de cena podem ser coloridos.

**3.1 Diagrama técnico vetorial, em sépia**

Para processos, redes, caminhos críticos, fluxogramas, organogramas, linhas do tempo, cortes esquemáticos, detalhes construtivos, esquemas estruturais e gráficos. Caixas, linhas, setas e textos editáveis; poucas cores; fundo limpo; hierarquia clara. Prioridade à leitura das etapas e das relações.

- **Traço:** linhas finas e uniformes (cerca de 0,75 pt), contornos e cortes um pouco mais fortes que eixos, cotas e setas; cantos retos ou levemente arredondados.

- **Aparência:** vetorial chapada, sem degradês, sem sombras, sem efeitos de renderização 3D, sem ícones decorativos.

- **Escala de sépia** (monocromática, de tons quentes): sépia escuro \#5C4A3A para contornos, textos e setas principais; sépia médio \#9C8468 para preenchimentos de elementos secundários, hachuras e linhas auxiliares; sépia claro \#EDE4D6 para fundos de painel, faixas de fase e superfícies; branco nos preenchimentos principais.

- **Cores da paleta do livro** entram só como acento: a cor de destaque marca o elemento que o leitor precisa ver primeiro; a cor de função marca o que ela designa (cargas, portões de decisão, fluidos, zonas). Nada mais recebe cor.

- **Composição:** margens generosas, respiro equilibrado, elementos alinhados, uma única ordem de leitura (de cima para baixo ou da esquerda para a direita), nada encostado nas bordas.

**3.2 Infográfico técnico ilustrado, colorido**

Para explicar espaços, instalações, equipamentos e sistemas por meio de cenas reconhecíveis: um pavimento hospitalar, uma área limpa farmacêutica, um canteiro, um edifício em perspectiva com a estrutura à vista. A cena principal está em perspectiva (isométrica ou cavaleira, de preferência), com elementos reconhecíveis e detalhados, volume, sombras suaves e cores organizadas por função.

- **Cena:** uma só cena principal por página, em perspectiva, com o ponto de vista declarado no prompt. Edificações, ambientes, equipamentos e vegetação entram quando pertinentes ao tema; nada entra como decoração.

- **Volume e sombra:** volume dado por faces em dois ou três tons da mesma cor e por sombras suaves, sem efeito fotográfico, sem reflexos e sem textura realista.

- **Cores por função:** cada família de elementos recebe uma cor e a mantém em todas as figuras do livro (por exemplo, estrutura em um tom, instalações em outro, circulação em outro). A paleta do livro continua valendo: o grafite nas linhas e nos textos, a cor de destaque no elemento principal, a cor de função no que ela designa; as demais cores da cena ficam dessaturadas, para não competir.

- **Anotações integradas:** setas, legendas curtas e quadros explicativos fazem parte da composição, com textos legíveis no tamanho final. O limite de seis a oito rótulos continua valendo; quando a cena pede mais, agrupam-se os secundários numa legenda interna discreta, numerada.

- **Contorno:** linha grafite fina em todos os volumes, para que a figura continue legível impressa em preto e branco.

**3.3 Como escolher**

| **O texto do livro descreve...** | **Linguagem** |
|---|---|
| Uma sequência de etapas, um fluxo de decisão, uma rede de atividades, uma hierarquia, uma linha do tempo | Diagrama técnico vetorial, sépia |
| Um corte, um detalhe construtivo, um esquema estrutural, um diagrama de esforços, um gráfico de valores | Diagrama técnico vetorial, sépia |
| Uma comparação lado a lado de alternativas esquemáticas | Diagrama técnico vetorial, sépia |
| Um ambiente, um pavimento, uma instalação, um sistema predial em funcionamento, um canteiro | Infográfico técnico ilustrado, colorido |
| Um edifício ou conjunto em perspectiva, com a relação entre partes (estrutura, espaço, forma) | Infográfico técnico ilustrado, colorido |
| Um equipamento ou sala técnica com os componentes nomeados | Infográfico técnico ilustrado, colorido |

**4. Paleta do livro**

A paleta é definida no plano de revisão, com no máximo uma cor de destaque e uma cor de função, além do grafite \#2B2B2B para linhas e textos e do cinza-claro ou bege para superfícies e painéis. Nos diagramas em sépia, a escala da seção 3.1 substitui o cinza-claro nos fundos e as cores da paleta entram só como acento. Exemplos de paletas já usadas:

| **Tipo de livro** | **Paleta** |
|---|---|
| Livro de estruturas | Grafite \#2B2B2B (linhas e textos), azul \#1F3864 (destaque), vermelho-tijolo \#B23A2E só para cargas, forças e setas de carga, cinza-claro \#E6E6E6 (superfícies e cortes), branco nos preenchimentos. |
| Livro de instalações industriais | Grafite \#2B2B2B (linhas e textos), terracota \#9C4A2E como única cor de destaque, bege quente \#F4F1EE nos painéis de fundo internos, branco nos preenchimentos. |
| Livro de gestão de projetos (metodologia por fases e portões) | Grafite \#2B2B2B (linhas e textos), azul \#1F3864 (destaque), âmbar \#C98A1B reservado a portões, decisões e marcos, cinza-claro \#E6E6E6 para fundos de fase e painéis, branco nos preenchimentos. |
| Livro em trabalho | \[Definida no plano de revisão, conforme a seção 0.\] |

**5. O Documento 2 e os campos de cada entrada**

O Documento 2 de cada livro tem o título "\[Nome do livro\]: figuras e prompts" e começa com uma linha de abertura: "\[N\] figuras. Para cada uma: número, inserção, formato, fonte, legenda e prompt de 20 linhas em português e em inglês, para conferência de alinhamento com o texto do livro e com o ponto de inserção." Seguem três notas curtas: o padrão gráfico do livro (resumo das linhas 1 a 12 com a paleta preenchida), a nota sobre o título dentro do arquivo (seção 2, item 9) e a situação das figuras existentes a redesenhar.

Cada figura começa em página nova, com os campos:

- **Título:** "Figura N.M, Título".

- **Inserção:** Capítulo N, título do capítulo. Seção N.x, título da seção.

- **Situação:** a produzir; ou existente, a redesenhar, com o arquivo de referência.

- **Linguagem visual:** diagrama técnico vetorial, sépia; ou infográfico técnico ilustrado, colorido.

- **Formato na página:** A4 PORTRAIT 210 x 297 milímetros.

- **Fonte:** elaboração do autor, com as referências de base.

- **Legenda:** 15 linhas, cerca de 135 a 180 palavras, a mesma do livro. Diz o que o leitor deve observar e por que isso pesa na decisão que ele precisa tomar.

- **Prompt em português (20 linhas)** e **Prompt in English (20 lines)**, este precedido de Placement, Page format, Source e Caption, em inglês.

**6. O prompt de 20 linhas**

As linhas 1 a 12 são o padrão comum a todas as figuras do livro e mudam só nos campos entre colchetes. As linhas 13 a 20 são escritas para cada figura. A versão em inglês é tradução fiel; os rótulos entre aspas e o título da linha 6 ficam em português.

**Linhas 1 a 12, padrão comum a todas as figuras**

> 1\. Crie a figura "Figura N.M, \[Título\]" para o capítulo N ("\[título do capítulo\]") de um livro técnico sobre \[assunto do livro\], seção "N.x \[título da seção\]".
>
> 2\. Estilo: \[diagrama técnico vetorial em sépia \| infográfico técnico-didático ilustrado em perspectiva isométrica\], em ilustração técnica editorial limpa, \[aparência vetorial chapada \| volume por faces e sombras suaves\], adequada para impressão em preto e branco e em cores em página A4.
>
> 3\. Paleta: \[para diagrama: sépia escuro \#5C4A3A para contornos e textos, sépia médio \#9C8468 para preenchimentos secundários e hachuras, sépia claro \#EDE4D6 para fundos e superfícies, branco nos preenchimentos principais; cor de destaque do livro, \#\_\_\_\_\_\_, só no elemento principal; cor de função, \#\_\_\_\_\_\_, só para \_\_\_\_\_\_\] \[para infográfico: grafite \#2B2B2B para linhas e textos, cor de destaque \#\_\_\_\_\_\_ no elemento principal, cor de função \#\_\_\_\_\_\_ para \_\_\_\_\_\_, cores dessaturadas por família de elementos, cinza-claro \#E6E6E6 ou bege \#F4F1EE nas superfícies e painéis, branco nos preenchimentos\].
>
> 4\. Tipografia: Verdana em toda a imagem, com no mínimo 8 pt no tamanho final e todos os acentos do português preservados.
>
> 5\. Todo texto dentro da imagem deve estar em português do Brasil, exatamente como indicado entre aspas nas linhas de conteúdo abaixo, com no máximo seis a oito rótulos curtos; quando as linhas de conteúdo listarem mais rótulos, agrupar os secundários em uma legenda interna discreta.
>
> 6\. Coloque o título fora da área do desenho, na parte superior da página, sempre com o número da figura: "Figura N.M, \[Título\]".
>
> 7\. Linhas: finas e uniformes (cerca de 0,75 pt), com contornos e cortes um pouco mais fortes que eixos, cotas e setas; cantos retos ou levemente arredondados; \[para diagrama: sem degradês, sem sombras, sem efeitos de renderização 3D\] \[para infográfico: sombras suaves e volume por faces, sem efeito fotográfico, sem reflexos, sem texturas realistas\]; sem ícones decorativos.
>
> 8\. Composição: margens generosas, respiro equilibrado, elementos alinhados, uma única ordem de leitura, nada encostado nas bordas.
>
> 9\. Precisão: use somente os dados e rótulos informados abaixo; onde houver "valor a confirmar", escreva exatamente isso e não invente números; \[apoios, cotas e hachuras segundo as convenções brasileiras de desenho técnico \| losangos para decisões e retângulos para fases e documentos, segundo as convenções de fluxogramas\].
>
> 10\. Saída: formato A4 PORTRAIT 210 x 297 milímetros; SVG com textos e formas editáveis, fundo transparente e moldura cinza-claro de contorno da área da página; mais uma versão em PNG com pelo menos 600 dpi.
>
> 11\. Legenda do livro, só como contexto (não desenhar): \[legenda\]. Destaque no detalhe da ilustração ou do infográfico o que interessa a \[público do livro\] e mantenha o foco na decisão que o leitor precisa tomar.
>
> 12\. Conteúdo da figura: sem logotipos, marcas, marcas d'água, pessoas identificáveis ou fotografias, salvo se pedido abaixo.

**Linhas 13 a 20, conteúdo de cada figura**

Exatamente oito linhas escritas para aquela figura, nunca por frase-modelo. Cada linha responde a uma pergunta:

| **Linha** | **O que diz** |
|---|---|
| 13 | Composição na página A4 retrato: como a página se divide (faixas, colunas, cena única, cena e detalhe) e onde fica cada parte. |
| 14 | Elementos obrigatórios: o que precisa aparecer, com os nomes do texto do livro. |
| 15 | Rótulos exatos, entre aspas, no máximo seis a oito; o que vai para a legenda interna, se houver. |
| 16 | Relações e setas: o que liga o quê, em que sentido, com que tipo de linha. |
| 17 | Escala, dimensões de referência ou valores a representar, só os que estão no texto; onde faltar, "valor a confirmar". |
| 18 | Ponto de vista (planta, corte, elevação, isométrica, cavaleira) e nível de detalhe. |
| 19 | O que recebe a cor de destaque e o que recebe a cor de função; o resto fica em sépia ou dessaturado. |
| 20 | O detalhe que o leitor precisa enxergar: o elemento que resolve a dúvida do leitor tratada no texto. |

**7. Exemplo de entrada preenchida**

Exemplo genérico, de um livro sobre estruturas, para mostrar o formato. A legenda do exemplo tem cerca de dez linhas, do padrão anterior; nas entradas novas, a legenda tem 15 linhas. Em cada livro novo, todas as entradas seguem exatamente este formato, com paleta, público e conteúdo próprios.

**Figura 1.1, A estrutura como elemento gerador de forma, espaço e expressão**

**Inserção:** Capítulo 1, A estrutura como elemento de projeto. Seção 1.1, A estrutura no projeto arquitetônico.

**Situação:** a produzir.

**Linguagem visual:** infográfico técnico ilustrado, colorido.

**Formato na página:** A4 PORTRAIT 210 x 297 milímetros.

**Fonte:** Elaborada pelo autor.

**Legenda:** Os três estágios representam o mesmo edifício de dois pavimentos, na mesma escala e do mesmo ponto de vista. Primeiro aparece só o esqueleto de pilares, vigas e lajes; depois, os ambientes que esse esqueleto deixa livres; por fim, o edifício com vedações e caixilhos, em que a estrutura ainda se lê na fachada. Observe que a posição dos pilares e a espessura das lajes, fixadas no primeiro estágio, já limitam o tamanho dos ambientes e o desenho das aberturas dos estágios seguintes. Por isso a decisão estrutural pertence ao estudo preliminar: mudar um pilar depois que a forma está fechada costuma obrigar a refazer o espaço interno e a fachada.

**Prompt em português (20 linhas)**

> 1\. Crie a figura "Figura 1.1, A estrutura como elemento gerador de forma, espaço e expressão" para o capítulo 1 ("A estrutura como elemento de projeto") de um livro técnico sobre estruturas para arquitetos e engenheiros, seção "1.1 A estrutura no projeto arquitetônico".
>
> 2\. Estilo: infográfico técnico-didático ilustrado em perspectiva isométrica, em ilustração técnica editorial limpa, volume por faces e sombras suaves, adequada para impressão em preto e branco e em cores em página A4.
>
> 3\. Paleta: grafite \#2B2B2B para linhas e textos, azul \#1F3864 como cor de destaque, vermelho-tijolo \#B23A2E reservado a cargas, forças e setas de carga, cores dessaturadas por família de elementos, cinza-claro \#E6E6E6 para superfícies e cortes, branco nos preenchimentos.
>
> 4\. Tipografia: Verdana em toda a imagem, com no mínimo 8 pt no tamanho final e todos os acentos do português preservados.
>
> 5\. Todo texto dentro da imagem deve estar em português do Brasil, exatamente como indicado entre aspas nas linhas de conteúdo abaixo, com no máximo seis a oito rótulos curtos.
>
> 6\. Coloque o título fora da área do desenho, na parte superior da página, sempre com o número da figura: "Figura 1.1, A estrutura como elemento gerador de forma, espaço e expressão".
>
> 7\. Linhas: finas e uniformes (cerca de 0,75 pt), com contornos e cortes um pouco mais fortes que eixos e cotas; cantos retos ou levemente arredondados; sombras suaves e volume por faces, sem efeito fotográfico, sem reflexos, sem texturas realistas; sem ícones decorativos.
>
> 8\. Composição: margens generosas, respiro equilibrado, elementos alinhados, uma única ordem de leitura, nada encostado nas bordas.
>
> 9\. Precisão: use somente os dados e rótulos informados abaixo; onde houver "valor a confirmar", escreva exatamente isso e não invente números; apoios, cotas e hachuras segundo as convenções brasileiras de desenho técnico.
>
> 10\. Saída: formato A4 PORTRAIT 210 x 297 milímetros; SVG com textos e formas editáveis, fundo transparente e moldura cinza-claro de contorno da área da página; mais uma versão em PNG com pelo menos 600 dpi.
>
> 11\. Legenda do livro, só como contexto (não desenhar): Os três estágios representam o mesmo edifício de dois pavimentos, na mesma escala e do mesmo ponto de vista. Primeiro aparece só o esqueleto de pilares, vigas e lajes; depois, os ambientes que esse esqueleto deixa livres; por fim, o edifício com vedações e caixilhos, em que a estrutura ainda se lê na fachada. Observe que a posição dos pilares e a espessura das lajes, fixadas no primeiro estágio, já limitam o tamanho dos ambientes e o desenho das aberturas dos estágios seguintes. Por isso a decisão estrutural pertence ao estudo preliminar: mudar um pilar depois que a forma está fechada costuma obrigar a refazer o espaço interno e a fachada. Destaque no detalhe da ilustração o que interessa ao arquiteto e mantenha o foco na decisão de projeto que ele precisa tomar.
>
> 12\. Conteúdo da figura: sem logotipos, marcas, marcas d'água, pessoas identificáveis ou fotografias, salvo se pedido abaixo.
>
> 13\. Página A4 retrato dividida em três faixas horizontais empilhadas, cada uma com o mesmo edifício esquemático de dois pavimentos em perspectiva isométrica.
>
> 14\. Faixa superior: só o esqueleto estrutural, pilares, vigas e lajes. Faixa do meio: o mesmo esqueleto em traço fino, com os ambientes internos preenchidos em azul-claro translúcido e alguns móveis em contorno. Faixa inferior: o edifício completo, com vedações, caixilhos de vidro e cobertura, deixando a malha de pilares e as bordas das lajes legíveis na fachada.
>
> 15\. Rótulos, um à esquerda de cada faixa: "Estrutura", "Espaço", "Forma"; nenhum outro texto na imagem.
>
> 16\. Setas verticais em azul \#1F3864 ligam as faixas de cima para baixo, na sequência estrutura, espaço e forma.
>
> 17\. Edifício de dois pavimentos, com quatro pilares por fachada; sem cotas, pois o texto não traz dimensões.
>
> 18\. Perspectiva isométrica, mesma escala, mesmo ponto de vista e mesma posição dos pilares nas três faixas, para que o leitor reconheça cada pilar do esqueleto no edifício pronto.
>
> 19\. Pilares e vigas realçados em azul \#1F3864 na faixa superior; vedações em cinza dessaturado na faixa inferior; nada em vermelho-tijolo, porque a figura não mostra cargas.
>
> 20\. Detalhe que o arquiteto precisa enxergar: um mesmo pilar de canto contornado em azul nas três faixas, mostrando que a decisão estrutural permanece na forma final.

**Prompt in English (20 lines)**

> Placement: Chapter 1, Structure as a design element. Section 1.1, Structure in architectural design.
>
> Page format: A4 PORTRAIT 210 x 297 millimeters.
>
> Source: Author's own work.
>
> Caption: The three stages show the same two-storey building, at the same scale and from the same viewpoint. First, only the skeleton of columns, beams and slabs appears; then, the spaces that this skeleton leaves free; finally, the building with infill walls and window frames, in which the structure can still be read on the façade. Note that the position of the columns and the thickness of the slabs, fixed in the first stage, already limit the size of the rooms and the design of the openings in the following stages. That is why the structural decision belongs to the preliminary design: moving a column once the form has been settled usually means redesigning the interior space and the façade.
>
> 1\. Create the figure "Structure as a generator of form, space and expression" for chapter 1 ("Structure as a design element") of a technical book on structures for architects and engineers, section "1.1 Structure in architectural design".
>
> 2\. Style: illustrated technical-didactic infographic in isometric perspective, as a clean editorial technical illustration, volume given by faces and soft shadows, suitable for both black-and-white and colour printing on an A4 page.
>
> 3\. Palette: graphite \#2B2B2B for lines and text, blue \#1F3864 as the accent colour, brick red \#B23A2E reserved for loads, forces and load arrows, desaturated colours by family of elements, light grey \#E6E6E6 for surfaces and cut sections, white for fills.
>
> 4\. Typography: Verdana throughout the image, minimum 8 pt at final size, with all Portuguese accents preserved.
>
> 5\. All text within the image must be in Brazilian Portuguese, exactly as indicated in quotation marks in the content lines below, with at most six to eight short labels.
>
> 6\. Place the title outside the drawing area, at the top of the page, always including the figure number, written in Portuguese exactly as: "Figura 1.1, A estrutura como elemento gerador de forma, espaço e expressão".
>
> 7\. Lines: thin and uniform (approx. 0.75 pt), with outlines and cut sections slightly heavier than axes and dimensions; corners straight or slightly rounded; soft shadows and volume by faces, no photographic effect, no reflections, no realistic textures; no decorative icons.
>
> 8\. Composition: generous margins, balanced white space, aligned elements, a single reading flow, and no elements touching the edges.
>
> 9\. Precision: use only the data and labels provided below; where "valor a confirmar" appears, write exactly that and do not invent numbers; supports, dimensions and hatching per Brazilian technical-drawing conventions.
>
> 10\. Output: A4 PORTRAIT format (210 x 297 millimeters); SVG with editable text and shapes, transparent background and a light grey border outlining the page area; plus a PNG version at 600 dpi minimum.
>
> 11\. Book caption (for context only, do not draw): \[caption in English, as above\]. Highlight in detail what matters to the architect and keep the focus on the design decision the architect must make.
>
> 12\. Figure content: no logos, brands, watermarks, identifiable people or photographs, unless requested below.
>
> 13\. A4 portrait page divided into three stacked horizontal bands, each with the same schematic two-storey building in isometric perspective.
>
> 14\. Top band: only the structural skeleton, columns, beams and slabs. Middle band: the same skeleton in fine line, with the interior rooms filled in translucent light blue and a few pieces of furniture in outline. Bottom band: the finished building, with walls, glazed frames and roof, keeping the column grid and slab edges readable on the façade.
>
> 15\. Labels, one to the left of each band: "Estrutura", "Espaço", "Forma"; no other text in the image.
>
> 16\. Vertical arrows in blue \#1F3864 link the bands from top to bottom, in the sequence structure, space and form.
>
> 17\. Two-storey building with four columns per façade; no dimensions, since the text gives none.
>
> 18\. Isometric perspective, same scale, same viewpoint and same column positions in the three bands, so the reader recognises each skeleton column in the finished building.
>
> 19\. Columns and beams highlighted in blue \#1F3864 in the top band; walls in desaturated grey in the bottom band; nothing in brick red, since the figure shows no loads.
>
> 20\. Detail the architect needs to see: the same corner column outlined in blue in all three bands, showing that the structural decision remains in the final form.

**8. Imagens sem prompt**

Fotografias, reproduções históricas, capturas de tela e figuras de obras anteriores do autor não recebem prompt. Ficam no quadro final do Documento 2, com a situação de cada uma. Fotografia de obra real não é gerada por IA; imagem de banco com marca d'água é licenciada ou substituída antes da publicação.

| **Figura** | **Título** | **Capítulo** | **Tipo** | **Situação** | **Fonte** |
|---|---|---|---|---|---|
| \[N.M\] | \[Título\] | \[N\] | \[fotografia / reprodução / captura de tela / obra anterior do autor\] | \[mantida / licenciar / substituir\] | \[Fonte e nota de licenciamento\] |

**9. Conferência antes da entrega**

Antes de entregar cada figura, a IA que a gerou, ou a que a revisa, confere os pontos abaixo contra o texto do livro e contra a entrada do Documento 2.

1.  O conteúdo corresponde ao trecho do livro em que a figura é citada e à legenda; nada foi acrescentado ou omitido.

2.  Ortografia e acentos de todos os textos da imagem; rótulos exatamente como entre aspas no prompt.

3.  Setas e relações entre elementos no sentido certo; nenhuma seta solta.

4.  Cores conforme a paleta do livro e a linguagem visual escolhida; cor de destaque só no elemento principal; cor de função só no que ela designa; a figura continua legível em preto e branco.

5.  Legibilidade no tamanho de impressão previsto: nenhum texto abaixo de 8 pt em A4; no máximo seis a oito rótulos.

6.  SVG com textos e formas editáveis, fundo transparente, moldura da página; PNG com dimensões em pixels compatíveis com A4 a 600 dpi (cerca de 4.960 x 7.016 pixels).

7.  Título no alto da imagem com o número correto da figura, igual ao do livro e ao do Documento 2.

8.  Fonte e situação da entrada atualizadas depois da geração (de "a produzir" para "existente", com o nome do arquivo).

**10. Decisões a confirmar com o autor no início**

| **Decisão** | **Recomendação padrão** |
|---|---|
| Título do livro e assunto | Informados pelo autor; sem eles a IA não começa. |
| Paleta do livro | Uma cor de destaque e uma cor de função, no máximo; grafite nas linhas e textos. |
| Linguagem visual predominante | Diagrama vetorial em sépia para os desenhos técnicos; infográfico colorido para as cenas; escolha por figura no plano. |
| Formato de entrega | SVG editável mais PNG a 600 dpi, A4 retrato. |
| Legenda de 15 linhas na entrada e no livro | Sim, a mesma. |
| Figuras existentes | Redesenhadas no padrão, com o arquivo de origem como referência. |
| Fotografias e reproduções | Mantidas, sem prompt, no quadro final; marca d'água licenciada ou substituída. |

Se o autor responder apenas "aprovado" ou "prossiga", valem as recomendações.

**11. Modelo de prompt para colar no chat**

Copie o bloco abaixo num chat novo, preencha os campos entre colchetes e anexe este documento, o texto do livro (ou os capítulos em trabalho) e, se houver, o Documento 2 já iniciado.

> Você vai \[escrever os prompts das figuras \| gerar as figuras\] do livro "\[Nome do livro\]" (autor: Arq. Flávio Nese, Editora \[nome da editora\]). Siga integralmente o documento anexo "Prompt de produção de imagens, ilustrações e infográficos".
>
> DADOS DESTE LIVRO
>
> \- Assunto: \[assunto em uma linha\].
>
> \- Público das figuras: \[público\].
>
> \- Paleta: cor de destaque \[nome, \#\_\_\_\_\_\_\]; cor de função \[nome, \#\_\_\_\_\_\_, para \_\_\_\_\_\_\]; superfícies e painéis \[cinza-claro \#E6E6E6 \| bege \#F4F1EE\]; grafite \#2B2B2B nas linhas e textos.
>
> \- Linguagem visual: diagrama técnico vetorial em sépia para \[tipos de figura\]; infográfico técnico ilustrado colorido para \[tipos de figura\].
>
> \- Número de figuras: \[N\]; figuras existentes a redesenhar: \[listar ou "nenhuma"\]; imagens sem prompt: \[listar ou "nenhuma"\].
>
> MODO DE TRABALHO
>
> 1\. Confirme comigo o título, a paleta e as decisões da seção 10 antes de qualquer outra coisa.
>
> 2\. \[Se escrever prompts:\] Leia o livro inteiro e monte o Documento 2 no formato da seção 5, uma entrada por figura, com as 20 linhas em português e em inglês. Entregue primeiro as entradas de duas figuras como piloto, para meu aval do formato e do tom.
>
> 3\. \[Se gerar figuras:\] Gere uma figura por vez, na ordem do Documento 2, em SVG editável mais PNG, A4 retrato. Entregue a primeira como piloto antes de seguir.
>
> 4\. Antes de cada entrega, aplique a conferência da seção 9 e informe o que foi conferido.
>
> 5\. Grave os arquivos no local indicado, com o nome "Figura_N-M\_\[título curto\].svg" e ".png"; nunca sobrescreva uma versão anterior.
