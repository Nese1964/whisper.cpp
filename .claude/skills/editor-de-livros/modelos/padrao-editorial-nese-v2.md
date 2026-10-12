# Padrão de produção e revisão editorial de livros técnicos – NESE (v2)

Fonte: documento do autor, Arq. Flávio Nese, versão 2, 11 de outubro de 2026
(`Padrao_Producao_Revisao_Editorial_Livros_Tecnicos_v2.docx`). Nasceu na
revisão final do livro *Estruturas para Arquitetos e Engenheiros*. É um
documento vivo, vale para todos os livros técnicos do autor e pode receber
melhorias a cada uso. "O livro" ou "[Nome do livro]" = o livro em trabalho.

> **Ajustes do autor que prevalecem sobre este documento** estão na seção
> "Regras fixas do usuário" do `SKILL.md` (Word + PDF, A4, figura em página
> inteira no ponto de inserção, legenda de 15 linhas, pasta `agente_Claude`).

---

# Parte 1. Padrão editorial do autor

## 1. Para que serve e como usar

Padrão de produção e de revisão editorial dos livros técnicos do autor. Entra
em ação depois que a primeira versão do livro existe (sumário definido,
capítulos escritos, figuras especificadas ou executadas) e conduz a revisão
final e a padronização, com liberdade para enriquecer o material didático
(figuras novas, quadros, exemplos, remissões) desde que justificado e aprovado
pelo autor. As diretrizes de redação (seção 4), o padrão do capítulo (seção
6), normas e fontes (7), citações (8) e figuras (9) valem também para a
redação de capítulos novos.

**Primeira pergunta da IA:** o título do livro em trabalho, se não foi
informado. O título orienta pesquisas de normas, fontes e casos, define o
público da lâmina e dá nome ao kit, ao Documento 1 e ao Documento 2. Sem o
título confirmado, nenhuma etapa começa.

**Como iniciar num chat novo:** anexar (a) este documento; (b) o livro em DOCX
ou o kit de produção do livro; (c) o kit de ferramentas (seção 12); (d) o
PDF-modelo de orientação de imagens, se existir. Colar o prompt da seção 15.
Responder às decisões da seção 13 no primeiro turno ou aceitar as
recomendações. Aprovar o plano antes de qualquer alteração no texto.

**Trabalho em vários dias:** a revisão de um livro de 500 a 800 páginas leva
dois ou três dias de créditos de uso. A cada lote de capítulos, o kit, o
LEIA-ME (situação) e o documento do projeto são atualizados e gravados na
pasta do autor. Num chat novo, basta anexar o kit mais recente e dizer
"prossiga".

## 2. Entregas

| Entrega | Conteúdo |
|---|---|
| Plano de revisão (documento de raciocínio) | Diagnóstico com números do livro, escopo, ordem de execução e decisões para o autor, cada uma com recomendação. Entregue antes de qualquer edição. |
| Documento 1, livro revisado (DOCX e PDF) | Ordem editorial completa: pré-textuais, partes e capítulos, referências unificadas, glossário, apêndices, índice remissivo. Sumário e listas com paginação real. Figuras não produzidas como página reservada com título, legenda e fonte. |
| Documento 2, figuras e prompts (DOCX) | Uma entrada por desenho, no formato da Parte 2, com prompt de 20 linhas em português e em inglês. Quadro final com fotografias e imagens mantidas. |
| Kit de produção (ZIP) | Capítulos mestres (JSON), relatórios de revisão por capítulo, lista de pendências [VERIFICAR], notas de coordenação, ferramentas e LEIA-ME com a situação. |
| Nota sobre o uso de IA (opcional) | Uma página A4, impessoal e informativa: período de produção, onde a IA foi usada, origem das ilustrações, base nas referências, responsabilidade do autor. |

## 3. Sequência de trabalho

Cada fase termina com o que foi feito, quantas páginas o livro tem e o que
ficou pendente. Fases que mudam o texto só começam após aprovação do plano.

| Fase | O que se faz |
|---|---|
| 0. Diagnóstico | Contagem de páginas, capítulos, palavras, figuras por situação (a produzir, existente, a refazer, fotografia), quadros, fórmulas, referências e duplicatas, marcações [VERIFICAR], lâminas fora do padrão, títulos com dois-pontos, citações no texto, varredura automática de vícios. |
| 1. Plano para aprovação | Documento de raciocínio com escopo, ordem e decisões (seção 13). |
| 2. Revisão por capítulo | Leitura crítica completa, em lotes, pelo protocolo da seção 12. Cada capítulo gera um patch conferido e um relatório. |
| 3. Coordenação entre capítulos | Títulos alterados, remissões, citação uniforme de normas, dados repetidos, figuras sobrepostas. Registro em notas de coordenação. |
| 4. Figuras novas | Decisão sobre as propostas; inserção, renumeração e atualização de todas as chamadas. |
| 5. Pós-textuais | Referências unificadas, glossário, siglas, símbolos, apêndice de normas, índice remissivo. |
| 6. Pré-textuais | Folha de rosto, ficha, páginas reservadas, listas, sumário com seções, Sobre o autor e Apresentação em rascunho. |
| 7. Montagem | Livro em duas passadas para a paginação real; Documento 2. |
| 8. Verificação final e entrega | Nova varredura de vícios, revisão de sequência, contagem de figuras do livro contra o Documento 2, PDF folheado, lista de pendências do autor, gravação na pasta. |

## 4. Diretrizes de redação

Valem para todo texto produzido ou revisado, inclusive legendas, quadros e
prompts.

### Princípios

- Português do Brasil, registro técnico e acadêmico maduro, como um
  profissional experiente escreveria para colegas. Preciso, direto, com cara
  de texto escrito por uma pessoa.
- Na revisão, preservar a voz e a estrutura do autor: corrigir o necessário,
  não reescrever o que funciona. Edição mínima, no trecho exato.
- Cada frase traz informação. Concreto antes do genérico: dados, nomes,
  normas, datas, exemplos, casos.
- Tomar posição quando o assunto pede. Ressalvar só onde há incerteza real,
  dizendo qual é.
- Variar o tamanho de frases e parágrafos. Parágrafo com mais de 8 a 10 linhas
  é dividido onde a ideia muda.
- Raciocínio em prosa, com conectivos. Listas só para itens de fato
  enumeráveis.
- Começar pelo assunto. Terminar quando o argumento termina.

### Vocabulário a evitar

- Palavras-curinga: crucial, fundamental, robusto, abrangente, essencial,
  significativo, inovador, transformador, revolucionário, sem precedentes.
- Verbos de consultoria: potencializar, alavancar, impulsionar, fomentar,
  endereçar (no sentido de tratar).
- Metáforas gastas: jornada, mergulhar, navegar, cenário, ecossistema,
  pilares (figurado), bússola, divisor de águas.
- Enchimento: "vale ressaltar", "é importante destacar", "cabe mencionar",
  "nesse sentido", "nesse contexto", "vale registrar", "é tema que", "merece
  atenção", "pede um olhar à parte".
- Aberturas genéricas: "No cenário atual", "Em um mundo cada vez mais…",
  "Este capítulo aborda…".
- Decalques do inglês: "desempenha um papel", "faz sentido", "no final do
  dia", "jogar luz sobre", "isso dito", "performar". Anglicismo só sem termo
  consagrado em português, explicado na primeira ocorrência.

### Construções a evitar

- Antítese mecânica ("não se trata apenas de X, mas de Y", "não é X, é Y",
  "mais do que X, Y"). Afirmar Y diretamente.
- Agrupamentos automáticos de três.
- Pergunta retórica seguida da própria resposta.
- Frase de efeito ou "moral da história" no fim do parágrafo.
- Abstração como sujeito de ação humana ("a tecnologia nos convida", "os
  dados revelam").
- Introdução que anuncia e conclusão que repete ("Em suma", "Em última
  análise"); síntese só na seção final.
- Teaser ("como veremos adiante"): trocar por remissão exata ("ver Seção
  12.4") ou apagar com o resto da frase.
- Simetria forçada entre seções; parágrafos todos no mesmo molde.

### Pontuação e formatação

- Vírgula para incisos e apartes, **nunca travessão**.
- Negrito só para termos que o leitor precisa localizar rápido. Sem emojis.
- Títulos com maiúscula só na primeira palavra e nos nomes próprios, **sem
  dois-pontos** e sem título em duas partes.

### Regras de execução da limpeza

- Por leitura, frase a frase, com cada edição registrada (local, texto
  antigo, texto novo, motivo).
- Proibidos: rodízio de sinônimos, substituição global, regex sem conferência,
  apagar palavra sem ler o que vem depois.
- Ao apagar muleta ou teaser, apagar o resto da frase que dependia dele.
- Depois, reler os parágrafos alterados à procura de frase quebrada.
- Varredura automática é só triagem; trincas, fechos de efeito e moldes
  repetidos só aparecem na leitura.

### Antes de entregar

Há frases que serviriam para qualquer assunto? Aparecem palavras ou
construções das listas? Os parágrafos seguem o mesmo molde? Alguma afirmação
factual está sem base? Corrigir o que encontrar.

## 5. Leitura crítica de cada capítulo

O capítulo é lido inteiro e conferido em:

- **Correção técnica e atualidade:** conceitos corretos, números com fonte,
  normas com edição, unidades do SI com vírgula decimal, ponto de milhar e
  espaço entre número e unidade, terminologia uniforme.
- **[VERIFICAR]:** pesquisar em fonte primária e resolver, com URL no
  relatório; o que não se confirmar continua marcado, com redação precisa do
  que falta.
- Vícios de redação (seção 4).
- Títulos sem dois-pontos, numeração mantida.
- Repetições e lacunas: trecho que repete o capítulo-sede vira remissão; tema
  relevante que falta entra em parágrafo curto.
- Lâmina com cerca de 2.400 caracteres (seção 6).
- Fórmulas com explicação de pelo menos dez linhas, símbolos definidos e
  unidades.
- Citações autor-data (seção 8). Referências ABNT, todas sustentando alguma
  passagem.
- Quadros com título, fonte, coerência e chamada.
- Figuras: título, chamada, posição, legenda, fonte e prompt (seção 9 e
  Parte 2).
- Remissões conferidas contra o sumário atual.
- Coleta para pós-textuais: glossário, índice, siglas e símbolos.

## 6. Padrão do capítulo

- **Abertura:** título do capítulo e lâmina em caixa sombreada, "Por que isto
  interessa a [público do livro]". Público definido no plano, vale para o
  livro inteiro.
- **Lâmina:** cerca de 2.400 caracteres (2.200 a 2.600) em três parágrafos:
  a decisão de projeto que o capítulo ajuda a tomar; o que dá errado quando o
  tema é ignorado, com um problema concreto; o que o leitor sabe fazer ao
  terminar. Exemplo próprio em cada lâmina, sem frase-modelo; não repete o
  primeiro parágrafo do capítulo.
- **Rodapé da lâmina:** Leitura prévia (só capítulos anteriores), Continua em
  (só posteriores), Tempo de leitura (pela contagem de palavras), a partir de
  um mapa único de dependências entre capítulos.
- **Corpo:** seções N.1, N.2…, subtítulos quando o tamanho justifica, figuras
  e quadros numerados por capítulo na ordem de citação. Última seção:
  "N.x Síntese", que responde ao objetivo declarado na lâmina.
- **Quadros:** "Quadro N.M – Título", linha de cabeçalho, fonte abaixo
  ("Elaborado pelo autor com base em Sobrenome (ano)" ou a norma).

## 7. Normas, fatos e fontes

- Norma citada com número e edição (ex.: "ABNT NBR 6118:2023, Emenda
  1:2026"; resolução com número e data). Edição vigente conferida no catálogo
  do órgão emissor; emendas só quando importam ao trecho.
- Norma citada em vários capítulos tem forma única de citação no livro todo.
- Fonte primária sempre que possível. Página genérica só como pista.
- Nunca inventar dado, referência, página, DOI ou norma. O que não se
  confirmar recebe [VERIFICAR o que exatamente] e vai para a lista de
  pendências.
- Número alterado só com fonte. Dado anterior sem fonte sai do texto.
- Casos reais (obras, acidentes, falhas, interdições) conferidos em
  investigações ou registros oficiais e citados com eles.

## 8. Citações e referências

- Citação ABNT NBR 10520:2023, autor-data, sobrenome em maiúsculas e
  minúsculas também entre parênteses: "(Abdelrazaq, 2011)", "segundo Thomaz
  (2020)", "(Baker; Korista; Novak, 2007)"; até três autores todos, quatro ou
  mais "et al."; autor institucional como no cabeçalho da referência.
- Referências ABNT NBR 6023:2018; on-line com "Disponível em:" e "Acesso em:".
- Capítulo único de Referências no fim do livro, ordem alfabética, sem
  duplicatas. Listas por capítulo saem.
- Cada referência sustenta alguma passagem. Conferência cruzada automática
  citações × lista antes da montagem final.

## 9. Figuras no livro

### Página da figura

- Toda figura ocupa uma página A4 inteira, que começa em página nova.
- No topo, "Figura N.M – Título".
- Caixa da ilustração com cerca de 16,8 cm de altura, para caber a legenda
  longa.
- Abaixo, a legenda e, em seguida, a fonte.
- O texto seguinte recomeça em página nova.

### Legenda, fonte e situação

- Legenda: a mesma no livro e no Documento 2. Diz o que o leitor deve
  observar e por que isso pesa na decisão de projeto. Complementa o texto sem
  repeti-lo, não começa sempre igual, não inventa fato; em fotografia, só o
  verificável. (Tamanho: ver regra do autor no `SKILL.md`.)
- Fonte: desenhos, "Elaborada pelo autor com base em Sobrenome (ano)" ou na
  norma; desenho conceitual, "Elaborada pelo autor.". Fotografias e
  reproduções mantêm fonte e nota de licenciamento.
- Situação: a produzir; existente; existente, a refazer (com motivo);
  fotografia. Figura não produzida aparece como página reservada "Ilustração
  a produzir", com título, legenda e fonte.

### Fotografias

Fotografias do livro ficam como estão; o autor as complementa. Imagem de banco
com marca d'água é licenciada ou substituída. Fotografia que não corresponde
ao título tem título e legenda ajustados ou é apontada para troca. **Fotografia
de obra real não é gerada por IA.**

### Figuras novas e redundantes

Figura nova só onde o texto descreve relação espacial, detalhe construtivo ou
processo que a prosa não resolve e nenhuma figura cobre; no máximo duas
propostas por capítulo, cada uma justificada e especificada (título, legenda,
fonte, tipo, prompt). Figura redundante é apontada para corte ou diferenciada.

### Numeração

Por capítulo, na ordem de citação; toda figura é citada antes de aparecer.
Inserção ou corte gera mapa de-para aplicado a todas as chamadas do livro e
conferido por revisão de sequência automática.

## 10. Documento 2 e paleta

Formato detalhado na Parte 2. Paleta definida no plano: no máximo uma cor de
destaque e uma cor de função, além do grafite para linhas e textos e do
cinza-claro ou bege para superfícies e painéis.

| Tipo de livro | Paleta |
|---|---|
| Estruturas | Grafite #2B2B2B (linhas e textos), azul #1F3864 (destaque), vermelho-tijolo #B23A2E só para cargas, forças e setas de carga, cinza-claro #E6E6E6 (superfícies e cortes), branco nos preenchimentos. |
| Instalações industriais | Grafite #2B2B2B, terracota #9C4A2E como única cor de destaque, bege quente #F4F1EE nos painéis internos, branco nos preenchimentos; fundo transparente. |
| Livro em trabalho | Definida no plano. |

Ao final do Documento 2, quadro com fotografias, reproduções, capturas de tela
e figuras de obras anteriores do autor (sem prompt): figura, título,
capítulo, tipo, situação e fonte.

## 11. Elementos pré-textuais e pós-textuais

Ordem baseada na ABNT NBR 6029:2023 e na prática da editora. Elemento sem
conteúdo fica como página reservada com a marca do que falta.

- **Pré-textuais:** folha de rosto (título, autor, editora, local e ano);
  ficha catalográfica (página reservada, a cargo da editora, com dados
  sugeridos); dedicatória e agradecimentos (texto do autor); lista de figuras;
  lista de quadros; lista de siglas e abreviaturas; lista de símbolos;
  sumário com partes, capítulos e seções; Sobre o autor (rascunho); prefácio
  (reservado para convidado); Apresentação (rascunho em voz do autor:
  propósito, leitor, organização, modo de usar); nota sobre o uso de IA, se o
  autor quiser.
- **Textuais:** partes com página de abertura e lista dos capítulos;
  capítulos no padrão da seção 6.
- **Pós-textuais:** Referências (capítulo único); glossário com remissão ao
  capítulo e à figura; apêndice de normas citadas (número, título, edição,
  capítulos); índice remissivo por seção.

Sumário e listas sem caixa alta, com pontilhado até o número e recuo nas
entradas longas; números de página tirados do PDF real.

## 12. Protocolo operacional da IA

- Cada capítulo é um arquivo mestre estruturado (JSON de blocos: títulos,
  parágrafos, itens, fórmulas, figuras, quadros, referências). Toda edição é
  feita no mestre; o Word é sempre gerado a partir dele.
- Kit de ferramentas (herdado do livro de origem, adaptado a cada título):
  `rev/DIRETRIZES_REVISAO.md`, `rev/export_chapter.py`, `rev/apply_patch.py`
  (--check, --preview, --apply), `rev/scan_vicios.py`, `check_seq.py`,
  `insert_figs.py`, `prep_final.py`, `build_final.js` e `locate_pages.py`
  (Documento 1 em duas passadas), `build_doc2.js` (Documento 2),
  `light_docx.py` (recompressão de imagens).
- Livro que chega em DOCX é convertido em capítulos mestres e a conversão é
  conferida contra o original.
- **Revisão em lotes:** um revisor por capítulo, lotes de até oito ou nove
  capítulos; antes, um piloto com dois capítulos. Cada revisor lê diretrizes e
  notas de coordenação, lê o capítulo inteiro e grava um patch. O patch passa
  pela conferência automática até zerar erros (legenda fora do tamanho,
  lâmina fora de 2.200 a 2.600 caracteres, prompt sem 12 + 8 linhas, título
  com dois-pontos, travessão, citação entre colchetes). O texto revisado
  mantém cerca de 85% a 90% de semelhança com o original.
- A cada lote: notas de coordenação, kit, LEIA-ME e documento do projeto
  atualizados e gravados na pasta do autor.
- **Cuidados:** quando a busca na web se esgota, conferir por acesso direto às
  fontes primárias, nunca por suposição. Cópia dos mestres antes de cada etapa
  grande, sem sobrescrever a anterior. Arquivos até 30 MB: Word com imagens
  recomprimido (JPEG qualidade 88, até 1.800 px). Entregas anteriores nunca
  são apagadas.

## 13. Decisões a confirmar com o autor no início

| Decisão | Recomendação padrão |
|---|---|
| Título do livro | Informado pelo autor; sem ele não se começa. |
| Título da lâmina e público principal | Conforme o livro; definir antes. |
| Limite de páginas e prazo | Informados pelo autor; o plano mostra a estimativa. |
| Legenda também no livro | Sim, a mesma do Documento 2. |
| Paleta das ilustrações | Definida no plano (seção 10). |
| Índice remissivo | Por seção. |
| Títulos de partes inferidos | Mantidos, salvo indicação do autor. |
| Pasta de saída | `agente_Claude/<livro>/`, subpasta datada. |
| Fotografias com marca d'água | Marcadas para licenciar ou substituir. |
| Figuras de obras anteriores do autor | Mantidas, sem prompt, com origem indicada. |
| Nota sobre uso de IA | Página informativa e impessoal, se o autor quiser. |
| Enriquecimento didático | No máximo duas propostas por capítulo, justificadas e submetidas ao autor. |

Se o autor responder apenas "aprovado" ou "prossiga", valem as recomendações.

## 14. Lições aprendidas

| O que aconteceu | Regra |
|---|---|
| Espaço das figuras mudou duas vezes e a paginação foi refeita três vezes | Página inteira de figura fixada antes da revisão. |
| Rodízio de sinônimos e substituição global criaram tiques e frases quebradas | Só edição manual registrada. |
| Leitura parcial deixou passar erros de norma e números | Leitura integral e conferência na fonte desde a primeira rodada. |
| Dados sem fonte ou inventados em versões anteriores | Desconfiar de todo número sem fonte; retirar o que não se confirma. |
| Fotos de banco com marca d'água e fotos que não correspondiam ao título | Conferir cada foto contra o título; licenciar ou substituir. |
| Legendas curtas e figuras sem citação no texto | Legenda longa e revisão de sequência automática. |
| Citações quase ausentes e referências só no fim dos capítulos | Autor-data e capítulo único de referências. |
| Mesma norma citada de modos diferentes | Forma única de citação no livro todo. |
| Títulos com dois-pontos e anglicismos ("softwares") | Títulos simples e termo em português. |
| Limites de uso interromperam lotes | Lotes menores, kit e situação salvos a cada lote. |
| Prompts por frase-modelo ficaram repetitivos | Oito linhas de conteúdo escritas para cada figura. |

Novas lições entram aqui a cada livro.

## 15. Modelo de prompt para a revisão do livro

```
Você vai fazer a revisão final do livro "[Nome do livro]" (autor: Arq. Flávio
Nese, Editora [nome da editora]) para entrega à editora. Siga integralmente o
"Padrão de produção e revisão editorial de livros técnicos", com o mesmo
critério, rigor e escopo. Adapte nomes de arquivo, público da lâmina e paleta
a este livro.

MODO DE TRABALHO
1. Confirme comigo o título, o público da lâmina e as decisões da seção 13.
2. Monte o ambiente: converta o livro em capítulos mestres (ou use o kit do
   livro) e confira a conversão.
3. Faça o diagnóstico (fase 0) e entregue o plano de revisão, com as decisões
   da seção 13 e sua recomendação. Não altere o texto antes do meu aval.
4. Depois do aval, revise capítulo a capítulo, em lotes (seção 12), começando
   por um piloto de dois capítulos.
5. A cada lote, salve o kit, o LEIA-ME e o documento do projeto, e grave na
   minha pasta. Tudo deve poder ser retomado num chat novo.

ESPECÍFICO DESTE LIVRO
- Lâmina: "Por que isto interessa a [público do livro]".
- Normas e regulação: [órgãos e famílias de normas, ex.: ABNT, Anvisa, ISO,
  NFPA, CBPM, leis e decretos], edição vigente conferida na fonte; o que não
  se confirmar vai com [VERIFICAR].
- Dados de mercado e estatísticas: só com fonte e ano.
- Pendências da versão anterior: [listar ou "nenhuma registrada"].
- Paleta do Documento 2: [grafite #2B2B2B, destaque, função, superfícies;
  fundo transparente].
- Foco das legendas e prompts em [público do livro].

ENTREGAS
1. Documento 1: livro revisado completo, DOCX e PDF.
2. Documento 2: figuras e prompts no formato da Parte 2.
3. Kit atualizado, com relatórios por capítulo e lista de pendências.
```

---

# Parte 2. Orientação para geração das imagens

Ver `modelos/prompt-de-imagens.md` (formato completo do Documento 2, linhas
1 a 12 comuns, linhas 13 a 20 por figura e exemplo preenchido).
