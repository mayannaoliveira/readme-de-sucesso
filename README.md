## Readme de Sucesso

Como montar apresentações no Readme do repositório do Github.
Caso queira criar um perfil para aparecer como sua pagina inicial então crie um repositório com o mesmo nome do seu usuário no Github.

Substitua as tags abaixo :
- Utilizar o nome do usuário: `<usuário>`.
- Alterar o tema `<tema>`.
- Pode utilizar as cores no padrão hex como left_color=2f80ed e right_color=2f80ed, para criar uma paleta de cores acesse o [Coolors](www.coolors.com).

#### Como funciona o Markdown com as Badges?
É nescessário entender a estrutura de um card ou badge em Markdown, geralmente vemos a estrutura `[![Nome da Badge](URL da Badge)](URL para redirecionamento)` 

#### Estrutura para construir um readme de sucesso
1. Inicie com sua apresentação, pode até ser com o exemplo inicial ao criar o  readme para seu perfil.
2. Apresente suas redes sociais e email pois, as pessoas podem querer conhecer mais seu trabalho.
3. Liste exemplo de repositórios com projetos recentes.
4. Listar ferramentas, linguagem de programação, banco de dados entre outros itens que mostre ao leitor sua experiência profissional.
5. Alguns sites como o Creddly registram badges de cursos e essas podem ser usadas no perfil.
6. Use os itens abordados nesse artigo para incrementar o que achar nescessário.

---
### Badges

- Visitas no perfil:
<!-- ![Visitas](https://visitor-badge.glitch.me/badge?page_id=mayannaoliveira&left_color=green&right_color=red) -->

```md
![Visitas](https://visitor-badge.glitch.me/badge?page_id=<usuário>&left_color=green&right_color=red)
```
---
### Inserir ícones/imagens das redes sociais
Ícones podem ser encontrados no sites [icon8](https://icons8.com/), [iconfinder](https://www.iconfinder.com/), [thenounproject](https://thenounproject.com/) e [iconmonstr](https://iconmonstr.com/).

Abaixo exemplo do icone do Github:

```html
<p align="center">
	<a href="https://github.com/"><img src="https://img.icons8.com/bubbles/50/000000/github.png" alt="GitHub"/></a>
</p>
```

<p align="center">
	<a href="https://github.com/"><img src="https://img.icons8.com/bubbles/50/000000/github.png" alt="GitHub"/></a>
	<a href="https://www.linkedin.com/"><img src="https://img.icons8.com/bubbles/50/000000/linkedin.png" alt="LinkedIn"/></a>
	<a href="https://www.facebook.com/"><img src="https://img.icons8.com/bubbles/50/000000/facebook-new.png" alt="Facebook"/></a>
	<a href="https://www.instagram.com/"><img src="https://img.icons8.com/bubbles/50/000000/instagram.png" alt="Instagram"/></a>
        <a href="https://wa.me/"><img src="https://img.icons8.com/bubbles/50/000000/whatsapp.png" alt="Whatsapp"/></a>
        <a href="https://www.reddit.com/"><img src="https://img.icons8.com/bubbles/50/000000/reddit.png" alt="Reddit"/></a>
</p>

---
### Redes Sociais em Badges

É possível gerar badges de redes sociais ou até mesmo lista com as ferramentas, linguagens de programação entre outros pelos sites [Markdown Badges](https://github.com/Ileriayo/markdown-badges), [GitHub Profile Badges](https://home.aveek.io/GitHub-Profile-Badges/), [Shields](https://shields.io/), [Repositório Shields](https://github.com/badges/shields), [Awesome Badges](https://dev.to/envoy_/150-badges-for-github-pnk) e [Simple Badges](https://badges.pages.dev/). Pode ser usado via HTML ou Markdown como no exemplo abaixo:

```html
<p align="center">
    <a href="https://bio.link/mayanna">
    <img alt="Bio link" src="https://img.shields.io/badge/Bio%20Link-000000.svg?style=for-the-badge&logo=Bio-Link&logoColor=white"/>
    </a>
</p> 
```
<p align="center">
    <a href="https://bio.link/mayanna">
    <img alt="Bio link" src="https://img.shields.io/badge/Bio%20Link-000000.svg?style=for-the-badge&logo=Bio-Link&logoColor=white"/>
    </a>
    <a href="https://www.linkedin.com/in/mayannaoliveira/">
    <img alt="Linkedin" src="https://img.shields.io/badge/LinkedIn-0A66C2.svg?style=for-the-badge&logo=LinkedIn&logoColor=white"/>
    </a>
    <a href="https://www.credly.com/users/mayannaoliveira/">
    <img alt="Credly" src="https://img.shields.io/badge/Credly-FF6B00.svg?style=for-the-badge&logo=Credly&logoColor=white"/>
    </a>
    <a href="https://dev.to/mayannaoliveira">
    <img alt="DEV" src="https://img.shields.io/badge/dev.to-0A0A0A.svg?style=for-the-badge&logo=devdotto&logoColor=white"/>
    </a>
    <a href=mailto:mayannasoliveira@gmail.com>
    <img alt="linkedin" src="https://img.shields.io/badge/Gmail-EA4335.svg?style=for-the-badge&logo=Gmail&logoColor=white"/>
    </a>
    <a href="https://github.com/mayannaoliveira">
    <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white"/>
    </a>
    <a href="https://stackoverflow.com/users/16884312/mayanna">
    <img alt="StackOverflow" src="https://img.shields.io/badge/Stack%20Overflow-F58025.svg?style=for-the-badge&logo=Stack-Overflow&logoColor=white"/>
    </a>
</p> 

---
### GitHub Stats Badges

[![GitHub forks](https://img.shields.io/github/forks/mayannaoliveira/awesome-badges.svg?style=social&label=Fork)](https://github.com/mayannaoliveira/awesome-badges)
[![GitHub stars](https://img.shields.io/github/stars/mayannaoliveira/awesome-badges.svg?style=social&label=Star)](https://github.com/mayannaoliveira/awesome-badges)
[![GitHub watchers](https://img.shields.io/github/watchers/mayannaoliveira/awesome-badges.svg?style=social&label=Watch)](https://github.com/mayannaoliveira/awesome-badges)
[![GitHub followers](https://img.shields.io/github/followers/mayannaoliveira.svg?style=social&label=Follow)](https://github.com/mayannaoliveira/awesome-badges)
[![Twitter Follow](https://img.shields.io/twitter/follow/oliveiramayanna.svg?style=social)](https://twitter.com/oliveiramayanna)

---
### GitHub Stats

```
![Mayanna GitHub stats](https://github-readme-stats.vercel.app/api?username=<usuário>&show_icons=true&theme=<tema>)
```

![Mayanna GitHub stats](https://github-readme-stats.vercel.app/api?username=mayannaoliveira&show_icons=true&theme=dark)

![Mayanna GitHub stats](https://github-readme-stats.vercel.app/api?username=mayannaoliveira&show_icons=true&theme=radical)

![Mayanna GitHub stats](https://github-readme-stats.vercel.app/api?username=mayannaoliveira&show_icons=true&theme=dracula)

![Mayanna GitHub stats](https://github-readme-stats.vercel.app/api?username=mayannaoliveira&show_icons=true&theme=merko)

![Mayanna GitHub stats](https://github-readme-stats.vercel.app/api?username=mayannaoliveira&show_icons=true&theme=gruvbox)

![Mayanna GitHub stats](https://github-readme-stats.vercel.app/api?username=mayannaoliveira&show_icons=true&theme=transparent)

Os temas (theme) podem ser: dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast e dracula.

---
### Awesome GitHub Stats
Card para exibir os dados do Github, é possível gerar via site [Awesome GitHub Stat](https://awesome-github-stats.azurewebsites.net/) ou usar a versão HTML ou Markdown.
Esse tipo de card permite alterar os seguintes itens:
- O tipo do card `cardType=level`.
- O tema `theme=ocean-dark`.
[![Awesome Stats](https://awesome-github-stats.azurewebsites.net/user-stats/mayannaoliveira?cardType=level&theme=ocean-dark&preferLogin=false)](https://git.io/awesome-stats-card)

Versão Markdown:
```
[![Awesome Stats](https://awesome-github-stats.azurewebsites.net/user-stats/mayannaoliveira?cardType=level&theme=ocean-dark&preferLogin=false)](https://git.io/awesome-stats-card)
```

<p align="center">
    <a href="https://awesome-github-stats.azurewebsites.net/index.html??cardType=github&theme=vision-friendly-dark&preferLogin=false">
    <img  alt="mayannaoliveira's GitHub Stats" src="https://awesome-github-stats.azurewebsites.net/user-stats/mayannaoliveira?cardType=github&theme=vision-friendly-dark&preferLogin=false" /></a>
</p>

Versão HTML com o alinhamento no centro:
```
<p align="center">
    <a href="https://awesome-github-stats.azurewebsites.net/index.html??cardType=github&theme=vision-friendly-dark&preferLogin=false"> 
    <img  alt="mayannaoliveira's GitHub Stats" src="https://awesome-github-stats.azurewebsites.net/user-stats/mayannaoliveira?cardType=github&theme=vision-friendly-dark&preferLogin=false" /></a>
</p>
```

---
### GitHub Profile Trophy

É bem parecido com o GitHub Stats. Pode-se usar os temas: flat, onedark, gruvbox, dracula, monokai, chalk, nord, alduin, darkhub, juicyfresh, buddhism, oldie, radical, onestar, discord, algolia, gitdimmed, tokyonight, matrix, apprentice, dark_dimmed e dark_lover. Detalhes disponíveis na página [GitHub Profile Trophy](https://github.com/mayannaoliveira/github-profile-trophy) 
[![trophy](https://github-profile-trophy.vercel.app/?username=mayannaoliveira&theme=onedark)](https://github.com/mayannaoliveira/github-profile-trophy)

Versão em Markdown: 
```
[![trophy](https://github-profile-trophy.vercel.app/?username=<usuário>&theme=<tema>)](<url-para-redirecionar>)```
```
[![trophy](https://github-profile-trophy.vercel.app/?username=mayannaoliveira&theme=nord)](https://github.com/mayannaoliveira/github-profile-trophy)

Versão em Markdown:
```
[![trophy](https://github-profile-trophy.vercel.app/?username=mayannaoliveira)](https://github.com/mayannaoliveira/github-profile-trophy)

```

[![trophy](https://github-profile-trophy.vercel.app/?username=mayannaoliveira&row=2&column=3&theme=chalk)](https://github.com/mayannaoliveira/github-profile-trophy)

Versão em Markdown:
```
[![trophy](https://github-profile-trophy.vercel.app/?username=mayannaoliveira&row=2&column=3)](https://github.com/mayannaoliveira/github-profile-trophy)
```

---
### GitHub Recent Activity
Exibe as atividades que foram executadas recentemente no GitHub. Os passos abaixo devem ser seguidos para que a ação possa acontecer no repositório. Mais informações na página [GitHub Recent Activity](https://github.com/jamesgeorge007/github-activity-readme).

Estrutura do repositório:
Criar uma pasta `.github` e dentro dela outra `workflows`, onde ficarar os arquivos YML.

```md
usuário/usuário
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

O código em Markdown:
```
[![Github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Ashutosh00710&theme=<tema>)](https://github.com/<usuário>/github-readme-activity-graph)
```

---
### Blog Post Workflow

Lista as postagens recentes do seu blog dentro do README, processo semelhante ao do GitHub Recent Activity. Os passos abaixo devem ser seguidos para que a ação possa acontecer no repositório. Mais informações na página [Blog Post Workflow](https://github.com/gautamkrishnar/blog-post-workflow). 

Estrutura do repositório:
Criar uma pasta `.github` e dentro dela outra `workflows`, onde ficarar os arquivos YML.

```
usuário/usuário
│   README.md
│
└───.github
    └───workflows
            blog-post-workflow.yml
            update-badges.yml
            update-readme.yml
```

Inserir dentro `README.md` do o código abaixo:

```html
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->
```
Após criar as pastas `.github` e `workflows` inserir dentro da `workflows` o YML `blog-post-workflow.yml` com o código abaixo:

```yml
name: Latest blog post workflow
on:
  schedule: 
    - cron: '0 * * * *'
  workflow_dispatch: 
permissions:
  contents: write

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v3
      - name: Pull in dev.to posts
        uses: gautamkrishnar/blog-post-workflow@v1
        with:
          feed_list: "https://dev.to/feed/mayannaoliveira,https://www.mayannaoliveira.com/feed/"
          max_post_count: 4
```

No trecho `feed_list: "https://dev.to/feed/mayannaoliveira,https://www.mayannaoliveira.com/feed/"` deve inserir o link e o feed do seu blog como no exemplo, já usei no Dev e no Hashnode.
Para alterar a quantidades de artigos a serem exibidos alterem a quantidade em `max_post_count: <quantidade>`.

Blog posts:
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

---
### GitHub WidgetBox
[![GitHub WidgetBox](https://github-widgetbox.vercel.app/api/skills?languages=python,ruby,java,jquery)](https://github.com/Jurredr/github-widgetbox)

```md
[![GitHub WidgetBox](https://github-widgetbox.vercel.app/api/skills?languages=python,ruby,java,jquery)](https://github.com/Jurredr/github-widgetbox)
```

---
### Stack Overflow 
[Stackoverflow card](https://github.com/nschloe/stackoverflow-card/blob/main/README.md)
Mostre sua colaboração na plataforma utilizando um dos cards do [Stack Overflow Stats](https://github.com/omidnikrah/github-readme-stackoverflow) abaixo alguns exemplos:

[![A-StackOverflow](https://github-readme-stackoverflow.vercel.app/?userID=16884312)](https://stackoverflow.com/users/16884312/mayanna)

```md
[![StackOverflow](https://github-readme-stackoverflow.vercel.app/?userID=<ID-do-usuário>)](URL-do-perfil)
```

![C-StackOverflow](https://github-readme-stackoverflow.vercel.app/?userID=16884312&layout=compact&theme=dark)

[![DStackOverflow](https://github-readme-stackoverflow.vercel.app/?userID=16884312&layout=compact)](https://stackoverflow.com/users/16884312/mayanna)

```md
[![StackOverflow](https://github-readme-stackoverflow.vercel.app/?userID=16884312&layout=compact)](https://stackoverflow.com/users/16884312/mayanna)
```

[![E-StackOverflow](https://stackoverflow-badge.onrender.com/api/StackOverflowBadge/16884312)](https://stackoverflow.com/users/16884312/mayanna)

Na opção acima alguns itens podem ser adicionados ao código seguindo o exemplo de `theme`.
- showLogo: true
- theme: [stackoverflow-dark, stackoverflow-light, dracula, ...]
- showBorder: true
- showIcons: true
- showAnimations: true

### Todoist Stats

<!-- TODO-IST:START -->
<!-- TODO-IST:END -->






.














