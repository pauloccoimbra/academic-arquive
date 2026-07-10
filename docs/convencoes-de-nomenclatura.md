# Convenções de nomenclatura

Regras simples para manter o repositório navegável no longo prazo.

## Pastas

- `kebab-case`, em português, sem acentos: `equilibrio-nash-incerteza-knightiana`
- Nome descreve o **tema**, não o status (evitar `paper-final-v2`)
- Pastas de disciplinas usam o nome curto do curso, sem o código institucional

## Arquivos dentro de uma pasta de artigo

```
artigos/<tema>/
├── README.md              # status, resumo, venue-alvo, links
├── manuscrito.pdf          # versão mais recente sempre com este nome
├── manuscrito.tex           # se aplicável
└── versoes/                 # versões antigas, se quiser manter histórico
    └── 2026-03-manuscrito.pdf
```

Não usar `v1`, `v2`, `final`, `final_final` no nome do arquivo principal — o histórico do git já versiona isso. Se quiser manter cópias de marcos importantes, use `versoes/AAAA-MM-descricao.pdf`.

## Arquivos dentro de uma pasta de disciplina

```
notas-de-aula/<disciplina>/
├── README.md
├── slides/        aula-01-titulo.pdf, aula-02-titulo.pdf, ...
├── notas/          notas de aula em prosa, por tópico
├── exercicios/      listas e gabaritos
└── avaliacoes/       provas, se for compartilhar
```

## Datas

Formato ISO: `AAAA-MM-DD` ou `AAAA-MM`, sempre que uma data aparecer em nome de arquivo.

## Commits

Mensagens curtas e descritivas, em português, no imperativo:

```
adiciona notas da aula 6 de Derivativos
atualiza manuscrito Nash-Knightian com revisão do referee
corrige gabarito da lista 3
```
