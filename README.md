# Ecos da Paróquia — livro animado

As quatro edições do jornal **Ecos da Paróquia**, informativo do Programa UGA da Rádio Intervalo, em um livro animado que abre no navegador.

- Os textos são os originais dos jornais, transcritos sem alterações.
- Os desenhos e fotos foram recortados dos próprios jornais escaneados.
- Os personagens se mexem e falam: as falas aparecem em balões e, com o botão **Vozes** ligado, são lidas em voz alta pelo sintetizador do navegador (pt-BR). Cada personagem tem seu próprio tom de voz.
- **Tocar cena** faz os personagens da página falarem. Clicar em um personagem toca só as falas dele.
- **Modo filme** lê o livro inteiro sozinho, virando as páginas.
- **Ver original** mostra o jornal escaneado da edição aberta.

## Como abrir

Abra `index.html` no navegador. Se as imagens não carregarem ao abrir o arquivo direto, sirva a pasta:

```sh
python3 -m http.server
# depois acesse http://localhost:8000
```

Para publicar, basta ativar o GitHub Pages neste repositório (branch com o `index.html` na raiz).

## Estrutura

- `index.html`: o livro (HTML, CSS e JavaScript em um só arquivo)
- `assets/img/`: personagens, fotos e cabeçalhos recortados dos jornais
- `assets/scans/`: os quatro jornais originais escaneados

A foto do fim da edição 03 foi pixelada, porque tinha nudez.
