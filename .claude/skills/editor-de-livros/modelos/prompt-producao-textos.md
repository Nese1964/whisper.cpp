**Prompt de produção de livros**

Textos, tabelas e quadros. Padrão de produção e revisão editorial de livros técnicos e didáticos.

Arq. Flávio Nese

Versão 1, 11 de outubro de 2026 · Versão 1.1 do agente, 12 de outubro de 2026 (decisões do autor: legenda de 15 linhas; figura no ponto exato em que é citada; leitor da lâmina e das legendas definido em cada livro; texto corrido em Times New Roman 12)

*Este documento é independente de qualquer título. Vale para todos os livros técnicos e didáticos do autor e pode ser usado em qualquer sistema de inteligência artificial que leia texto. O livro em trabalho é chamado apenas de "o livro" ou "\[Nome do livro\]". As ilustrações, infográficos e figuras têm prompt próprio, no documento "Prompt de produção de imagens, ilustrações e infográficos", que acompanha este.*

**0. Campos a preencher antes de usar**

Preencha os campos abaixo e mantenha o bloco no início do prompt. Tudo o que vem depois se refere a eles. Campo não preenchido é perguntado pela IA no primeiro turno.

| **Campo**                      | **Valor para este livro**                                                                                                                           |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| Título do livro                | \[Nome do livro\]                                                                                                                                   |
| Autor e editora                | Arq. Flávio Nese. Editora \[nome da editora\]                                                                                                       |
| Assunto em uma linha           | \[por exemplo: estruturas para arquitetos e engenheiros; projetos de indústrias farmacêuticas; metodologia FEL aplicada a projetos de arquitetura\] |
| Público da lâmina              | \[por exemplo: ao arquiteto e ao engenheiro; ao projetista e ao arquiteto responsável pelo projeto; ao arquiteto e ao dono do empreendimento\]      |
| Pergunta própria da lâmina     | \[por que \[o público do livro\] precisa considerar o tema deste livro neste ponto\]                                                              |
| Normas e regulação do setor    | \[órgãos e famílias de normas que regem o tema: ABNT, Anvisa, ISO, NFPA, legislação, resoluções\]                                                   |
| Forma de comunicar             | \[tom dialógico, "você" e "nós" (padrão do autor, seção 4); nível do leitor; ajustes próprios deste livro, se houver\] |
| Limite de páginas e prazo      | \[número de páginas previsto; data de entrega à editora\]                                                                                           |
| Pendências da versão anterior  | \[listar, ou "nenhuma registrada"\]                                                                                                                 |
| Anexos previstos               | \[normas, guias e documentos de origem do tema, com autoria confirmada\]                                                                            |
| Paleta das ilustrações         | \[ver o prompt de imagens; definida no plano de revisão\]                                                                                           |
| Local de gravação das entregas | \[Google Drive pessoal do autor, pasta Agentes_Cloude/\<título\>/\<data\>\]                                                                                                        |

**1. Para que serve e como usar**

Este documento é o padrão de produção e de revisão editorial dos livros técnicos e didáticos do autor. Ele entra em ação depois que a primeira versão do livro já existe: sumário definido, todos os capítulos escritos e todas as figuras especificadas ou executadas. Se os capítulos ainda estão em arquivos separados, a primeira tarefa é a unificação (seção 3, fase 0). A partir daí, ele conduz a revisão final e a padronização do livro, com liberdade para enriquecer o material didático (figuras, tabelas, quadros, exemplos, remissões), desde que o acréscimo entre no plano de figuras, tabelas e quadros e seja aprovado pelo autor.

Lido por uma IA no início de um chat, este documento funciona como o prompt de trabalho. A seção 15 traz o modelo curto de prompt a ser colado no chat, com os campos da seção 0 preenchidos.

**Primeira pergunta da IA**

Antes de qualquer outra coisa, a IA pergunta ao autor o título do livro em trabalho, caso ele não tenha sido informado. O título orienta as pesquisas de normas, fontes e casos, define o público da lâmina e dá nome às entregas. Sem o título confirmado, nenhuma etapa começa.

**Como iniciar o trabalho num chat novo**

1.  Anexe: (a) este documento; (b) o livro, em DOCX, ou o pacote de trabalho do próprio livro, se já houver; (c) o prompt de imagens, se as figuras forem tratadas na mesma sessão.

2.  Cole o prompt da seção 15, com os campos preenchidos para o livro.

3.  Responda às decisões da seção 13 no primeiro turno, ou aceite as recomendações.

4.  Aprove o plano de revisão antes de qualquer alteração no texto.

**Trabalho em vários dias**

A revisão completa de um livro de 500 a 800 páginas consome mais de uma sessão de trabalho. O método foi desenhado para ser interrompido e retomado sem perda: a cada lote de capítulos, o pacote de trabalho e o arquivo de situação (LEIA-ME) são atualizados e gravados no local indicado pelo autor. Num chat novo, basta anexar o pacote mais recente e dizer "prossiga".

**2. Entregas**

| **Entrega**                                            | **Conteúdo**                                                                                                                                                                                                                                             |
|--------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Plano de revisão (documento de raciocínio)             | Diagnóstico com os números do livro, escopo, ordem de execução e decisões para o autor, cada uma com recomendação, mais o plano de figuras, tabelas e quadros. Entregue antes de qualquer edição.                                                        |
| Documento 1, livro revisado (DOCX e PDF)               | Ordem editorial completa: pré-textuais, partes e capítulos, referências unificadas, glossário, apêndices, anexos, índice remissivo. Sumário e listas com paginação real. Figuras ainda não produzidas como página reservada com título, legenda e fonte. |
| Documento 2, figuras e prompts (DOCX)                  | Uma entrada por desenho, no formato do prompt de imagens, com prompt de 20 linhas em português e em inglês. Quadro final com as fotografias e imagens mantidas.                                                                                          |
| Pacote de trabalho                                     | Capítulos em arquivos mestres, relatórios de revisão por capítulo, lista de pendências \[VERIFICAR\], notas de coordenação e LEIA-ME com a situação.                                                                                                     |
| Nota sobre o uso de inteligência artificial (opcional) | Uma página A4, impessoal e informativa: período de produção, onde a IA foi usada, origem das ilustrações, base nas referências, responsabilidade do autor.                                                                                               |

**3. Sequência de trabalho**

Cada fase termina com o que foi feito, quantas páginas o livro tem e o que ficou pendente. Fases que mudam o texto só começam depois da aprovação do plano.

| **Fase**                             | **O que se faz**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|--------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0\. Diagnóstico                      | Unificação dos capítulos, se chegam em arquivos separados: um só documento, numeração contínua de capítulos e seções, estilos de título, terminologia e remissões uniformizados. Em seguida, contagem de páginas, capítulos, palavras, figuras por situação (a produzir, existente, a refazer, fotografia), tabelas, quadros, fórmulas, referências e duplicatas, marcações \[VERIFICAR\], lâminas fora do padrão, títulos com dois-pontos, citações no texto, e varredura de vícios de redação. |
| 1\. Plano para aprovação             | Documento de raciocínio com escopo, ordem e decisões (seção 13), mais o plano de figuras, tabelas e quadros: leitura do livro inteiro, do início ao fim, marcando todos os pontos onde cabe uma peça (seções 9 e 10). Depois da aprovação do plano, nada entra.                                                                                                                                                                                                                                  |
| 2\. Revisão por capítulo             | Leitura crítica completa de cada capítulo, em lotes, pelo protocolo da seção 12. Cada capítulo gera uma lista de edições conferida e um relatório.                                                                                                                                                                                                                                                                                                                                               |
| 3\. Coordenação entre capítulos      | Títulos alterados, remissões, citação uniforme de normas, dados repetidos, figuras sobrepostas. Registro em notas de coordenação, lidas pelos lotes seguintes.                                                                                                                                                                                                                                                                                                                                   |
| 4\. Figuras, tabelas e quadros novos | Execução do plano aprovado na fase 1: inserção, renumeração e atualização de todas as chamadas do livro.                                                                                                                                                                                                                                                                                                                                                                                         |
| 5\. Pós-textuais                     | Referências unificadas, glossário, siglas, símbolos, apêndice de normas e índice remissivo, montados a partir do que cada revisão coletou.                                                                                                                                                                                                                                                                                                                                                       |
| 6\. Pré-textuais                     | Folha de rosto, ficha, páginas reservadas, listas, sumário com seções, Sobre o autor e Apresentação em rascunho.                                                                                                                                                                                                                                                                                                                                                                                 |
| 7\. Montagem                         | Livro em duas passadas para a paginação real; Documento 2.                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 8\. Verificação final e entrega      | Nova varredura de vícios, revisão de sequência, contagem de figuras do livro contra o Documento 2, lista de conferência final (seção 12), PDF folheado, lista de pendências do autor, gravação no local indicado.                                                                                                                                                                                                                                                                                |

**4. Diretrizes de redação**

Valem para todo texto produzido ou revisado, inclusive legendas, quadros, tabelas e prompts.

**Princípios**

1.  Português do Brasil, registro técnico maduro, como um profissional experiente que conversa com o leitor. Preciso, direto, com cara de texto escrito por uma pessoa. A voz do livro é a do tom dialógico (ver "Voz do texto", abaixo).

2.  Na revisão, preservar a voz e a estrutura do autor: corrigir o necessário e não reescrever o que já funciona. Edição mínima, no trecho exato.

3.  Cada frase traz informação. Concreto antes do genérico: dados, nomes, normas, datas, exemplos, casos.

4.  Tomar posição quando o assunto pede. Ressalvar só onde há incerteza real, dizendo qual é.

5.  Variar o tamanho das frases e dos parágrafos. Parágrafo com mais de 8 a 10 linhas é dividido onde a ideia muda.

6.  Raciocínio em prosa, com conectivos. Listas só para itens de fato enumeráveis.

7.  Começar pelo assunto. Terminar quando o argumento termina.

**Voz do texto: tom dialógico**

O livro fala com o leitor. O tom dialógico, segunda pessoa ("você") combinada com a primeira pessoa do plural ("nós"), é hoje o mais elegante, didático e acolhedor na literatura técnica. A voz impessoal (terceira pessoa sem sujeito, "verifica-se", "considera-se", voz passiva em série) é o padrão antigo da academia: afasta o leitor e deixa o texto frio e difícil de ler. Por isso:

1.  **"Você" para o leitor agir e decidir.** Instruções, verificações, decisões e consequências práticas: "Antes de definir a rota de fuga, você confere a lotação do pavimento." Sempre "você", nunca "tu"; verbo na terceira pessoa ("você verifica").

2.  **"Nós" para o raciocínio feito em conjunto e para as remissões.** "Vamos comparar as duas soluções", "Como vimos na Seção 2.3", "Agora podemos dimensionar a escada." O "nós" é o autor acompanhando o leitor, nunca o plural de modéstia vazio.

3.  **Impessoal só onde a neutralidade é exigida, e sem empilhar.** Requisitos de norma, definições, dados e resultados de ensaio podem vir em frase impessoal ou com o sujeito real ("A ABNT NBR 9077:2001 exige…", "A norma define…"). Nunca duas ou três frases seguidas em "verifica-se", "observa-se", "constata-se"; prefira o sujeito concreto.

4.  **Distribuição no capítulo.** Lâmina e aberturas de seção: "você" e "nós". Passagens práticas, exemplos e casos: "você". Normas, definições, tabelas e fórmulas: sujeito concreto ou impessoal pontual. Síntese e fecho: "nós", ligando o capítulo aos demais.

5.  **Legendas** no mesmo tom: "Observe que…", "Note como…", "Repare que…", variando a abertura de legenda para legenda.

6.  **Dialógico não é informal.** Sem gíria, sem exclamações, sem "a gente", sem intimidade forçada ("caro leitor", "querido aluno"). Diálogo também não justifica pergunta retórica respondida em seguida nem anúncio do conteúdo ("Neste capítulo vamos ver…"); a lâmina já cumpre esse papel.

7.  **Na revisão de livro existente**, texto impessoal é convertido para o tom dialógico só onde a frase ganha clareza; a conversão entra no plano de revisão e conta como edição registrada.

**A experiência do autor no livro**

O autor é arquiteto, especialista em gerenciamento de projetos, com cerca de 40 anos de prática na construção civil. Os livros dele trazem essa experiência: estudos de caso e passagens vividas em obra e na vida profissional. Essa é a marca pessoal do livro e não pode ser imitada pela IA.

1.  **Nunca inventar experiência do autor.** Nenhum relato, obra, cliente, data, número ou fala atribuído ao autor é escrito sem que ele tenha contado. A IA prepara o lugar e faz a pergunta; o autor responde; só então o relato é redigido.

2.  **Onde cabe um relato.** Ao redigir, a IA marca os pontos em que uma passagem da prática do autor reforça o texto: depois de um requisito de norma que costuma ser descumprido em obra, num erro frequente, numa decisão difícil de projeto ou de gestão, num conflito entre projeto e execução, na abertura ou no fecho de um capítulo. De um a três pontos por capítulo, sem forçar.

3.  **Marcação no texto.** Cada ponto recebe, no lugar exato, a marca `[RELATO DO AUTOR R-N.M: pergunta curta]`, por exemplo `[RELATO DO AUTOR R-3.2: você já viu uma rota de fuga obstruída por material de obra? O que aconteceu e como foi resolvido?]`. O texto em volta é escrito de modo a funcionar com ou sem o relato.

4.  **A produção não para.** As perguntas não interrompem a redação: o livro é escrito e montado inteiro, e todas as perguntas vão para o Caderno de perguntas ao autor (`modelos/caderno-perguntas-autor.md`), entregue no fim, em Word e PDF. O autor pode estar desconectado; muitas vezes ele só decide onde entra um caso depois de ver o livro montado.

5.  **Estudos de caso de terceiros.** Casos públicos (acidentes, incêndios, interdições, obras conhecidas) podem ser redigidos pela IA, só com fonte verificável (investigação, laudo, registro oficial, publicação técnica), citados pela seção 7. Caso do autor e caso de terceiros nunca se misturam.

6.  **Forma do relato.** O relato do autor vem em primeira pessoa do singular ("eu"), a única exceção ao tom dialógico, em quadro destacado "Da prática do autor" ou, quando for longo e estruturado, como "Estudo de caso N.M, Título" (situação, problema, decisão, resultado, lição). O texto em volta liga o relato ao conteúdo com "você" e "nós".

7.  **Depois das respostas.** O relato é redigido a partir das palavras do autor, com a voz dele preservada, apenas limpo dos vícios da seção 4, e volta para o autor aprovar. Pergunta sem resposta tem a marca retirada sem deixar lacuna no texto. Nomes de pessoas e empresas só com autorização do autor; na dúvida, anonimizar.

**Vocabulário a evitar (vícios de IA)**

- **Palavras-curinga:** crucial, fundamental, robusto, abrangente, essencial, significativo, inovador, transformador, revolucionário, sem precedentes.

- **Verbos de consultoria:** potencializar, alavancar, impulsionar, fomentar, endereçar (no sentido de tratar).

- **Metáforas gastas:** jornada, mergulhar, navegar, cenário, ecossistema, pilares (em sentido figurado), bússola, divisor de águas.

- **Enchimento:** "vale ressaltar", "é importante destacar", "cabe mencionar", "nesse sentido", "nesse contexto", "vale registrar", "é tema que", "merece atenção", "pede um olhar à parte".

- **Aberturas genéricas:** "No cenário atual", "Em um mundo cada vez mais...", "Este capítulo aborda...".

- **Decalques do inglês:** "desempenha um papel", "faz sentido", "no final do dia", "jogar luz sobre", "isso dito", "performar". Anglicismo só quando não houver termo consagrado em português; quando necessário, explicado na primeira ocorrência.

**Construções a evitar**

1.  Antítese mecânica: "não se trata apenas de X, mas de Y", "não é X, é Y", "mais do que X, Y". Afirmar Y diretamente.

2.  Agrupamentos automáticos de três (adjetivos, exemplos, itens).

3.  Pergunta retórica seguida da própria resposta.

4.  Frase de efeito ou "moral da história" no fim do parágrafo.

5.  Abstração como sujeito de ação humana ("a tecnologia nos convida", "os dados revelam").

6.  Introdução que anuncia o conteúdo e conclusão que o repete ("Em suma", "Em última análise"); síntese só na seção final.

7.  Teaser ("como veremos adiante"): trocar por remissão exata ("ver Seção 12.4") ou apagar com o resto da frase.

8.  Simetria forçada entre seções e itens; parágrafos todos no mesmo molde.

**Pontuação e formatação**

- Vírgula para incisos e apartes, nunca travessão.

- Negrito só para termos que o leitor precisa localizar rápido. Sem emojis.

- Títulos com maiúscula só na primeira palavra e nos nomes próprios, sem dois-pontos e sem título em duas partes.

- Números: vírgula decimal, ponto de milhar, espaço entre número e unidade ("25 MPa", "1.200 m²"). Unidades do SI, com a grafia da norma.

**Regras de execução da limpeza**

1.  A limpeza é feita por leitura, frase a frase, com cada edição registrada (local, texto antigo, texto novo, motivo).

2.  Proibidos: rodízio de sinônimos, substituição global, expressão regular sem conferência do resultado, apagar palavra sem ler o que vem depois.

3.  Ao apagar uma muleta ou um teaser, apagar também o resto da frase que dependia dele.

4.  Depois da limpeza, reler os parágrafos alterados à procura de frase quebrada.

5.  A varredura automática é só triagem: os vícios que mais pesam (trincas, fechos de efeito, moldes repetidos) só aparecem na leitura.

**Antes de entregar**

Há frases que serviriam para qualquer assunto? Aparecem palavras ou construções das listas acima? Os parágrafos seguem todos o mesmo molde? Alguma afirmação factual está sem base? Corrigir o que encontrar.

**5. Leitura crítica de cada capítulo**

O capítulo é lido inteiro, sem pular nada, e conferido nos pontos abaixo.

1.  **Correção técnica e atualidade.** Conceitos corretos, números com fonte, normas com edição, unidades do SI com vírgula decimal, ponto de milhar e espaço entre número e unidade, terminologia uniforme no livro todo.

2.  **Marcações \[VERIFICAR\].** Cada uma é pesquisada em fonte primária e resolvida, com a URL registrada no relatório; o que não se confirmar continua marcado, com redação precisa do que falta conferir.

3.  **Vícios de redação** (seção 4).

4.  **Títulos** sem dois-pontos, com a numeração mantida.

5.  **Repetições e lacunas.** Trecho que repete o capítulo-sede vira remissão; tema relevante que falta entra em parágrafo curto, sem inflar o capítulo.

6.  **Lâmina** com cerca de 2.400 caracteres (seção 6).

7.  **Fórmulas** com explicação de pelo menos dez linhas, todos os símbolos definidos e as unidades.

8.  **Citações** autor-data onde o dado, o caso ou o conceito vem de uma obra (seção 8).

9.  **Referências** no formato da ABNT e todas sustentando alguma passagem.

10. **Tabelas e quadros** com título, fonte, coerência com o texto e chamada (seção 10).

11. **Figuras**: título, chamada, posição, legenda, fonte e prompt (seção 9 e prompt de imagens).

12. **Remissões** conferidas contra o sumário atual do livro inteiro.

13. **Coleta para os pós-textuais**: termos de glossário, entradas de índice, siglas e símbolos do capítulo.

**6. Padrão do capítulo**

- **Abertura:** título do capítulo e lâmina em caixa sombreada, "Por que isto interessa a \[público do livro\]". O público é definido no plano de revisão e vale para o livro inteiro.

- **Lâmina:** cerca de 2.400 caracteres em três parágrafos: a decisão que o capítulo ajuda o leitor a tomar e por que \[o público do livro\] precisa considerar \[o tema do livro\] neste ponto; o que dá errado quando o tema é ignorado, com um problema concreto; o que o leitor sabe fazer ao terminar e quanto isso melhora o resultado, com dado quando houver. Cada lâmina com exemplo próprio, sem frase-modelo. A lâmina não repete o primeiro parágrafo do capítulo.

- **Rodapé da lâmina:** Leitura prévia (só capítulos anteriores), Continua em (só posteriores), Tempo de leitura (pela contagem de palavras). As conexões vêm de um mapa único de dependências entre capítulos.

- **Corpo:** seções numeradas (N.1, N.2...), subtítulos quando o tamanho justifica, figuras, tabelas e quadros numerados por capítulo na ordem de citação. A última seção é "N.x Síntese", que responde ao objetivo declarado na lâmina e termina com o fecho do capítulo.

- **Fecho do capítulo:** parágrafo final da Síntese que liga o capítulo aos demais, dizendo o que cada capítulo citado acrescenta ao tema, com remissão exata ("ver Capítulo 7, Seção 7.3"). Nenhum capítulo fica isolado; sem frase de suspense (seção 4).

- **Notas de rodapé**, quando usadas: duas linhas, a primeira com definição conceitual breve, a segunda com a referência bibliográfica no formato da ABNT.

**7. Normas, fatos e fontes**

1.  Toda norma técnica ou regulatória é citada com número e edição (por exemplo, "ABNT NBR 6118:2023, Emenda 1:2026"; resolução com número e data). A edição vigente é conferida no catálogo do órgão emissor ou em fonte que o reproduza; emendas só aparecem quando o conteúdo delas importa ao trecho.

2.  Normas citadas em vários capítulos recebem uma forma única de citação, definida uma vez e aplicada no livro todo.

3.  Fonte primária sempre que possível: norma, órgão oficial, publicação técnica, escritório do projeto, artigo revisado. Página genérica só como pista.

4.  Nunca inventar dado, referência, página, DOI ou norma. O que não se confirmar recebe \[VERIFICAR o que exatamente\] e vai para a lista de pendências do autor.

5.  Número alterado só com fonte. Dado de versão anterior sem fonte sai do texto.

6.  Casos reais (obras, acidentes, falhas, interdições) são conferidos nas investigações ou nos registros oficiais e citados com eles.

7.  Material antigo do autor (aulas, apostilas, textos, livros anteriores) é tratado como possivelmente desatualizado: cada norma, regulamento, dado e prática é conferido na fonte primária e registrado no Quadro de atualização (`modelos/material-de-origem.md`). Regulamentação local, como as Instruções Técnicas do Corpo de Bombeiros, é sempre a do estado definido para o livro.

**8. Citações e referências**

- **Citação no texto** pela ABNT NBR 10520:2023, sistema autor-data, sobrenome em maiúsculas e minúsculas também entre parênteses: "(Abdelrazaq, 2011)", "segundo Thomaz (2020)", "(Baker; Korista; Novak, 2007)"; até três autores todos, quatro ou mais "et al."; autor institucional como no cabeçalho da referência. Normas continuam citadas pelo número e pela edição.

- **Referências** pela ABNT NBR 6023:2018. Documento on-line com "Disponível em:" e "Acesso em:".

- **Capítulo único de Referências** no fim do livro, em ordem alfabética, sem duplicatas, com a mesma obra escrita de um só modo. As listas por capítulo saem.

- Cada referência sustenta alguma passagem; a que não sustenta nada sai ou recebe a citação no ponto certo. Conferência cruzada entre citações e lista antes da montagem final.

**9. Figuras no livro**

Esta seção trata da figura como elemento do texto: posição, legenda, fonte, numeração. A especificação visual e o prompt de geração estão no prompt de imagens, ilustrações e infográficos.

**Página da figura**

1.  Toda figura ocupa uma página A4 inteira, na posição retrato, que começa em página nova.

2.  No topo, "Figura N.M, Título".

3.  Caixa da ilustração com cerca de 16,8 cm de altura, para caber a legenda longa.

4.  Abaixo, a legenda e, em seguida, a fonte.

5.  A figura entra no ponto exato em que é citada: quebra de página, página da figura, nova quebra de página, e o texto continua no parágrafo seguinte. Figuras não são agrupadas no fim da seção; a editora decide a posição final.

**Legenda, fonte e situação**

- **Legenda:** 15 linhas (cerca de 135 a 180 palavras), a mesma no livro e no Documento 2. Diz o que o leitor deve observar e por que isso pesa na decisão que ele precisa tomar. Complementa o texto sem repeti-lo, não começa sempre do mesmo jeito e não inventa fato; em fotografia, só o que é verificável sobre a obra.

- **Fonte:** desenhos, "Elaborada pelo autor com base em Sobrenome (ano)" ou na norma; desenho conceitual, "Elaborada pelo autor.". Figura adaptada ou trazida de outra obra cita a origem na fonte, e a obra entra nas Referências. Fotografias e reproduções mantêm a fonte e a nota de licenciamento.

- **Situação:** a produzir; existente; existente, a refazer (com o motivo); fotografia. Figura ainda não produzida aparece no livro como página reservada "Ilustração a produzir", com título, legenda e fonte.

**Fotografias**

Fotografias que já estão no livro ficam como estão; o autor as complementa. Imagem de banco com marca d'água é licenciada ou substituída antes da publicação. Fotografia que não corresponde ao título tem título e legenda ajustados ao que mostra, ou é apontada para troca. Fotografia de obra real não é gerada por IA.

**Plano de figuras, tabelas e quadros**

Toda figura, tabela ou quadro novo é decidido no plano (seção 3, fase 1), a partir da leitura do livro inteiro: entra peça só onde o texto descreve uma relação espacial, um detalhe construtivo, um processo ou um conjunto de dados que a prosa não resolve e que nenhuma peça cobre. Cada entrada do plano tem justificativa e especificação completa (título, legenda, fonte, tipo, prompt). Depois da aprovação do plano, nada entra; na revisão por capítulo, aponta-se apenas peça redundante para corte ou para diferenciação de conteúdo.

**Numeração**

Numeração por capítulo, na ordem de citação; toda figura é citada antes de aparecer. Inserção ou corte gera mapa de-para, aplicado a todas as chamadas do livro, inclusive as de outros capítulos, e conferido por revisão de sequência.

**10. Tabelas e quadros**

**Quando usar cada um**

- **Tabela:** dados numéricos, comparáveis entre linhas e colunas (dimensões, cargas, custos, prazos, índices).

- **Quadro:** conteúdo textual organizado (classificações, requisitos, comparações qualitativas, listas de verificação, correspondências entre normas e etapas).

- O que cabe em uma frase não vira tabela. Tabela com uma só linha de dados ou uma só coluna volta para o texto.

**Formato**

1.  Título acima: "Tabela N.M, Título" ou "Quadro N.M, Título", numeração por capítulo, na ordem de citação, em série separada das figuras.

2.  Linha de cabeçalho em destaque (cinza-claro), com os nomes das colunas e a unidade entre parênteses quando toda a coluna a compartilha ("Vão (m)", "Custo (R\$/m²)").

3.  Fonte abaixo, no mesmo formato das figuras: "Elaborado pelo autor com base em Sobrenome (ano)", ou a norma com número e edição, ou "Elaborado pelo autor.".

4.  Números alinhados à direita, com vírgula decimal, ponto de milhar e o mesmo número de casas decimais na coluna. Texto alinhado à esquerda.

5.  Células sem dado recebem traço simples ou "n.d." (não disponível), nunca ficam vazias sem explicação; o critério é dito em nota abaixo da tabela.

6.  Notas de tabela em letra menor, abaixo da fonte, chamadas por letras (a, b, c) para não confundir com as notas do texto.

7.  Tabela ou quadro que ocupa mais de uma página repete o cabeçalho em cada página e recebe "(continua)" e "(conclusão)".

8.  Tabela e quadro ficam no corpo do texto, logo depois do parágrafo que os cita, e não em página inteira separada; a página inteira é reservada às figuras.

9.  Sem cores de marca, sem fundos coloridos além do cabeçalho, sem bordas grossas. Em livros impressos em preto e branco, a leitura não pode depender da cor.

**Conteúdo**

1.  Todo número vem do texto ou de fonte citada; o que não se confirmar recebe "\[VERIFICAR\]" na célula e vai para a lista de pendências.

2.  Os valores da tabela e os do texto são os mesmos; divergência é corrigida na fonte do erro, não escondida.

3.  Toda tabela e todo quadro são citados no texto antes de aparecer ("ver Tabela 4.2") e o texto diz o que o leitor deve observar neles, sem repetir a tabela em prosa.

4.  Quadro que compara normas ou etapas usa a mesma ordem e a mesma terminologia do texto.

5.  Siglas usadas em tabelas e quadros entram na lista de siglas e são explicadas na nota da tabela na primeira ocorrência.

**Listas de tabelas e quadros**

O livro traz lista de tabelas e lista de quadros nos pré-textuais, separadas da lista de figuras, com número, título e página real.

**11. Elementos pré-textuais e pós-textuais**

Ordem baseada na ABNT NBR 6029:2023 e na prática da editora. Elemento sem conteúdo fica como página reservada com a marca do que falta, para não alterar a paginação depois.

| **Grupo**    | **Elementos**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pré-textuais | Folha de rosto (título, autor, editora, local e ano); ficha catalográfica (página reservada, a cargo da editora, com dados sugeridos); dedicatória e agradecimentos (texto do autor); lista de figuras; lista de tabelas; lista de quadros, todas com título e página; lista de siglas e abreviaturas; lista de símbolos; sumário com partes, capítulos e seções; Sobre o autor (rascunho para revisão); prefácio (reservado para convidado); Apresentação (rascunho em voz do autor: propósito, leitor, organização, modo de usar); nota do autor e nota sobre o uso de IA, se o autor quiser. |
| Textuais     | Partes com página de abertura e lista dos capítulos; capítulos no padrão da seção 6.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Pós-textuais | Referências (capítulo único); glossário com remissão ao capítulo e à figura; apêndices (material elaborado pelo autor, entre eles o apêndice de normas técnicas citadas: número, título, edição, capítulos); anexos (material de terceiros: normas, guias e documentos de origem do tema tratado, com autoria confirmada em fonte verificável e registrada nas Referências); índice remissivo por seção (vale em qualquer paginação; a editora converte para páginas se preferir).                                                                                                              |

Sumário e listas sem caixa alta, com pontilhado até o número e recuo nas entradas longas; números de página tirados do PDF real.

**12. Protocolo operacional da IA**

Este protocolo não depende de ferramenta ou de sistema específico. Cada IA o executa com os recursos que tiver; o que importa é o registro, a conferência e a possibilidade de retomar o trabalho.

**Modelo de trabalho**

1.  Cada capítulo é mantido como arquivo mestre, em formato estruturado e legível (blocos de títulos, parágrafos, itens, fórmulas, figuras, quadros, tabelas, referências). Toda edição é feita no mestre, e o livro em Word é sempre gerado a partir dele.

2.  Livro que chega em DOCX é convertido primeiro em capítulos mestres; a conversão é conferida contra o original antes da revisão. Capítulos que chegam em arquivos separados são unificados antes da conversão (seção 3, fase 0).

3.  Cópia dos mestres antes de cada etapa que altera muitos arquivos (revisão, figuras novas), com nome que indique a etapa; nunca sobrescrever a cópia anterior.

**Revisão em lotes**

1.  Um capítulo por vez, em lotes de tamanho compatível com o limite de uso da sessão. Antes do lote completo, um piloto com dois capítulos calibra a qualidade.

2.  Para cada capítulo: leitura das diretrizes e das notas de coordenação, leitura do capítulo inteiro e registro de uma lista de edições: substituições de trecho exato, legendas, fontes, prompts, referências, inserções curtas, além de glossário, índice, siglas, símbolos, pendências, repetições e propostas de figura.

3.  A lista de edições passa pela conferência até zerar erros e avisos (legenda fora de 135 a 180 palavras (15 linhas), lâmina fora de 2.200 a 2.600 caracteres, prompt sem 12 + 8 linhas, título com dois-pontos, travessão, citação entre colchetes). Depois, prévia do capítulo revisado, varredura de vícios e releitura completa.

4.  Medir a extensão das mudanças: o texto revisado mantém cerca de 85% a 90% de semelhança com o original. Acima disso, verificar se algo deixou de ser corrigido; abaixo, verificar se a voz do autor foi preservada.

5.  A cada lote: notas de coordenação atualizadas, pacote de trabalho regerado, LEIA-ME atualizado, arquivos gravados no local indicado pelo autor.

**Cuidados práticos**

- Quando a capacidade de busca na web se esgota no meio de um lote, a conferência continua por acesso direto às páginas das fontes primárias; nada é preenchido por suposição.

- Arquivos com imagens são entregues em tamanho compatível com o meio de envio, por recompressão sem perda visível na página.

- Saídas entregues sempre pelo chat e gravadas no local indicado; entregas anteriores nunca são apagadas.

- Trabalho parcial interrompido por limite de uso é descartado e refeito a partir do último pacote gravado, nunca emendado de memória.

**Lista de conferência final**

- Toda figura, tabela e quadro citados no texto antes de aparecer, numerados sem saltos e presentes nas listas.

- Toda citação do texto está na lista de referências, e toda referência sustenta uma citação.

- Numeração contínua e sem saltos de capítulos e seções; remissões conferidas contra o sumário final.

- Sumário e listas coerentes com o conteúdo e com a paginação do PDF real.

- Lâmina, Síntese e fecho presentes em todos os capítulos.

- Contagem de figuras do livro igual à do Documento 2.

- Nenhuma marcação \[VERIFICAR\] sem registro na lista de pendências do autor.
- Nenhuma marca \[RELATO DO AUTOR\] fora do Caderno de perguntas ao autor; nenhum relato do autor sem resposta e aprovação dele.

- Varredura de vícios zerada; tabelas e quadros no formato da seção 10; paleta uniforme em todas as figuras.

**13. Decisões a confirmar com o autor no início**

| **Decisão**                           | **Recomendação padrão**                                                                                                               |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| Título do livro                       | Informado pelo autor; sem ele a IA não começa (seção 1).                                                                              |
| Título da lâmina e público principal  | Conforme o livro; definir antes da revisão.                                                                                           |
| Limite de páginas e prazo de entrega  | Informados pelo autor; o plano mostra a estimativa.                                                                                   |
| Legenda de 15 linhas também no livro  | Sim, a mesma do Documento 2.                                                                                                          |
| Paleta das ilustrações                | Definida no plano, segundo o prompt de imagens.                                                                                       |
| Índice remissivo                      | Por seção.                                                                                                                            |
| Títulos de partes inferidos           | Mantidos, salvo indicação do autor.                                                                                                   |
| Local de gravação                     | Drive pessoal do autor, Agentes_Cloude/\<título\>/\<data\>.                                                                                  |
| Fotografias de banco com marca d'água | Ficam marcadas para licenciar ou substituir.                                                                                          |
| Figuras de obras anteriores do autor  | Mantidas, sem prompt, com a origem indicada.                                                                                          |
| Nota sobre o uso de IA                | Página informativa e impessoal, se o autor quiser.                                                                                    |
| Plano de figuras, tabelas e quadros   | Fechado na fase 1, após leitura integral do livro e aprovação do autor; depois dele nada entra.                                       |
| Anexos                                | Material de terceiros indicado pelo autor (normas, guias, documentos de origem do tema), com autoria confirmada em fonte verificável. |

Se o autor responder apenas "aprovado" ou "prossiga", valem as recomendações.

**14. Lições aprendidas**

Registro acumulado dos livros já revisados com este método. Novas lições entram aqui a cada livro.

| **O que aconteceu**                                                                                 | **Regra**                                                                                   |
|-----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| O espaço reservado às figuras mudou duas vezes num mesmo livro e a paginação foi refeita três vezes | Página inteira de figura fixada antes da revisão.                                           |
| Rodízio de sinônimos e substituição global criaram tiques e frases quebradas                        | Só edição manual registrada.                                                                |
| Leitura parcial deixou passar erros de norma e de números                                           | Leitura integral e conferência na fonte desde a primeira rodada.                            |
| Versões anteriores traziam dados sem fonte ou inventados                                            | Desconfiar de todo número sem fonte; retirar o que não se confirma.                         |
| Fotografias de banco com marca d'água e fotos que não correspondiam ao título                       | Conferir cada fotografia contra o título; licenciar ou substituir.                          |
| Legendas curtas e figuras sem citação no texto                                                      | Legenda de 15 linhas e revisão de sequência.                                               |
| Citações quase ausentes e referências só no fim dos capítulos                                       | Citação autor-data e capítulo único de referências.                                         |
| A mesma norma citada de modos diferentes entre capítulos                                            | Forma única de citação definida e aplicada no livro todo.                                   |
| Títulos de capítulo com dois-pontos e anglicismos ("softwares")                                     | Títulos simples e termo em português.                                                       |
| Limites de uso interromperam lotes no meio                                                          | Lotes menores, pacote e situação salvos a cada lote; trabalho parcial descartado e refeito. |
| Prompts de figura por frase-modelo ficaram repetitivos                                              | Oito linhas de conteúdo escritas para cada figura.                                          |
| \[Nova lição\]                                                                                      | \[Regra\]                                                                                   |

**15. Modelo de prompt para colar no chat**

Copie o bloco abaixo num chat novo, preencha os campos entre colchetes (os mesmos da seção 0) e anexe este documento, o livro (ou o pacote de trabalho do livro) e o prompt de imagens, se as figuras forem tratadas na mesma sessão.

> Você vai fazer a revisão final do livro "\[Nome do livro\]" (autor: Arq. Flávio Nese, Editora \[nome da editora\]) para entrega à editora. Siga integralmente o documento anexo "Prompt de produção de livros: textos, tabelas e quadros", com o mesmo critério, o mesmo rigor e o mesmo escopo definidos nele. Adapte o público da lâmina, as normas do setor e a paleta a este livro.
>
> MODO DE TRABALHO
>
> 1\. Confirme comigo o título do livro, o público da lâmina e as decisões da seção 13 antes de qualquer outra coisa.
>
> 2\. Monte o ambiente: converta o livro em capítulos mestres (ou use o pacote de trabalho, se anexado) e confira a conversão.
>
> 3\. Faça o diagnóstico (seção 3, fase 0) e me entregue o plano de revisão em documento de raciocínio, com o plano de figuras, tabelas e quadros, as decisões da seção 13 e a sua recomendação para cada uma. Não altere o texto antes do meu aval.
>
> 4\. Depois do aval, revise capítulo a capítulo, em lotes, pelo protocolo da seção 12. Comece por um piloto de dois capítulos.
>
> 5\. A cada lote, salve o pacote de trabalho e o LEIA-ME e grave os arquivos no local indicado. O trabalho pode levar mais de uma sessão; tudo precisa poder ser retomado num chat novo com o pacote mais recente.
>
> ESPECÍFICO DESTE LIVRO
>
> \- Assunto: \[assunto em uma linha\].
>
> \- Lâmina: "Por que isto interessa a \[público do livro\]".
>
> \- Pergunta própria da lâmina: \[por que \[o público do livro\] precisa considerar o tema deste livro\].
>
> \- Normas e regulação do setor: \[órgãos e famílias de normas\], com edição vigente conferida na fonte; o que não se confirmar vai com \[VERIFICAR\] para a lista de pendências.
>
> \- Dados de mercado, estatísticas e números de produção: só com fonte e ano.
>
> \- Pendências registradas na versão anterior, a conferir se ainda existem: \[listar, ou "nenhuma registrada"\].
>
> \- Anexos: \[normas, guias e documentos de origem do tema, com autoria confirmada em fonte verificável e registrada nas Referências\].
>
> \- Paleta do Documento 2: \[conforme o prompt de imagens\].
>
> \- Foco das legendas, das tabelas e dos quadros em \[público do livro\].
>
> ENTREGAS AO FINAL
>
> 1\. Documento 1: livro revisado completo, DOCX e PDF, com pré-textuais, referências unificadas, glossário, apêndices, anexos e índice remissivo.
>
> 2\. Documento 2: figuras e prompts no formato do prompt de imagens.
>
> 3\. Pacote de trabalho atualizado, com relatórios por capítulo e a lista de pendências \[VERIFICAR\].
