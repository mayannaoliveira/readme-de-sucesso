## Readme de Sucesso
│   README.md
│
└───.github
    └───workflows
            blog-post-workflow.yml
            update-badges.yml
            update-readme.yml
```
No arquivo `README.md` inserir os comentários:

```html
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->
```
Após criar as pastas `.github` e `workflows` inserir dentro da `workflows` o YML `update-readme.yml` com o código abaixo:
```yml
name: Update README

on:
  schedule:
    - cron: "*/5 * * * *" # Runs every 5 minutes.

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          COMMIT_MSG: "Updated README with recent activity"
          MAX_LINES: 10
```

Atividades do GitHub:
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

Após finalizar o processo acima abra o link do repositório na guia anônima do navegador para ver o resultado.

---
### Github Readme Activity Graph
Para mais informações acesse a página [Github Readme Activity Graph](https://github.com/Ashutosh00710/github-readme-activity-graph).

[![Mayanna's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=mayannaoliveira&theme=merko)](https://github.com/Ashutosh00710/github-readme-activity-graph)

O código em Markdown:
```
[![Mayanna's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=mayannaoliveira&theme=merko)](https://github.com/Ashutosh00710/github-readme-activity-graph)
```

Utilizando os temas:
[![Github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=mayannaoliveira&theme=xcode)](https://github.com/Ashutosh00710/github-readme-activity-graph)


#### Todoist Stats

Status do Todoist no readme: [![Todoist Readme](https://github.com/mayannaoliveira/readme-de-sucesso/actions/workflows/todoist-readme.yml/badge.svg)](https://github.com/mayannaoliveira/readme-de-sucesso/actions/workflows/todoist-readme.yml)

<!-- TODO-IST:START -->
<!-- TODO-IST:END -->



