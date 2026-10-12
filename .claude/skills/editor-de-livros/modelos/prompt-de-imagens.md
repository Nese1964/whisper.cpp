# Caderno de prompts de imagens

Gere um único documento com todas as imagens sugeridas no livro, na ordem em
que aparecem. Comece pelo cabeçalho e repita o bloco de figura para cada
imagem.

## Cabeçalho do caderno

- **Livro:** <título completo>
- **Autor:** <autor>
- **Tipo de livro:** <manual técnico / didático / uso em obra / ...>
- **Público:** <público-alvo>
- **Estilo visual comum a todas as imagens:** <ex.: ilustração técnica
  vetorial, fundo branco, paleta sóbria, sem texto embutido na imagem>
- **Total de figuras:** <n>

## Bloco de cada figura

```
FIGURA <capítulo>.<número>  —  <título da figura>
Livro: <título do livro>
Capítulo / seção: <ex.: 3 — Sistemas de hidrantes / 3.2 Reserva técnica>
Página aproximada: <opcional>
Fonte: <autor do livro> (imagem criada para esta obra)

LEGENDA (15 linhas):
1. ...
2. ...
...
15. ...

PROMPT DE CONTEXTO (o que a imagem quer dizer):
- Tipo de livro e leitor: <para quem é e como o livro será usado>
- Contexto no texto: <o que o parágrafo está explicando quando a figura aparece>
- Mensagem da imagem: <o que o leitor precisa entender só de olhar>
- Elementos obrigatórios: <objetos, pessoas, EPIs, medidas, normas citadas>
- Evitar: <erros técnicos, elementos fora de norma, texto ilegível>

PROMPT PARA A IA DE IMAGEM:
<descrição direta e completa da cena, enquadramento, estilo, proporção
(ex.: 16:9 ou 4:3), iluminação, nível de detalhe técnico>
```

Regras:

- A numeração da figura é a mesma do marcador `[FIGURA X.Y]` no texto.
- A legenda tem sempre 15 linhas: descreve a imagem, explica cada elemento
  relevante, liga ao conteúdo do capítulo e, quando houver, cita a norma.
- A fonte é sempre o autor do livro, salvo imagem de terceiros indicada pelo
  usuário.
