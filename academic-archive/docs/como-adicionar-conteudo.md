# Como adicionar conteúdo novo

## Novo artigo

1. Copie `artigos/_template/` para `artigos/<novo-tema>/`
2. Preencha o `README.md` copiado (status, resumo, venue-alvo)
3. Adicione o PDF/LaTeX
4. Atualize o índice em `artigos/README.md`
5. Commit: `git add artigos/<novo-tema> && git commit -m "adiciona artigo <novo-tema>"`

## Nova disciplina / semestre

1. Copie `notas-de-aula/_template-curso/` para `notas-de-aula/<disciplina>/`
2. Preencha o `README.md` (ementa breve, carga horária, semestre)
3. Vá adicionando slides/notas/exercícios ao longo do semestre
4. Atualize o índice em `notas-de-aula/README.md`

## Novo projeto de extensão

1. Crie `extensao/<projeto>/`
2. README com objetivo, público-alvo, carga horária, edital vinculado (ex.: PROEX 07/2025)
3. Atualize `extensao/README.md`

## Fluxo git padrão

```bash
git pull origin main
# edite/adicione arquivos
git add .
git commit -m "mensagem descritiva"
git push origin main
```

## Publicando no site (hub)

O site em si vive num repositório separado (o "hub"). Quando um artigo/curso ganha uma página própria lá, adicione o link correspondente na seção relevante do hub e, se fizer sentido, um link de volta aqui a partir do README do item.
