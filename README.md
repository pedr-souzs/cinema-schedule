# Cinema Schedule

Site estático desenvolvido com HTML e CSS para praticar navegação entre páginas, organização de arquivos e aplicação de estilos compartilhados em um projeto web.

## Sobre o projeto

O projeto apresenta uma programação de filmes organizada por estado, com uma página inicial e páginas específicas para Rio de Janeiro e São Paulo.

A navegação é realizada por meio de links entre as páginas, permitindo acessar a programação de cada estado e retornar à página inicial.

## Estrutura do projeto

O projeto é organizado da seguinte forma:

```text
cinema-schedule/
│
├── index.html
│
├── estados/
│   ├── rj.html
│   └── sp.html
│
└── css/
    └── style.css
```

## Conteúdo

A página inicial apresenta links para os estados disponíveis:

* Rio de Janeiro
* São Paulo

Cada página de estado apresenta os filmes disponíveis, seus horários e a indicação de quando entram em exibição.

## Estilização

O arquivo CSS é compartilhado entre todas as páginas e aplica as seguintes regras:

* Filmes em exibição hoje utilizam a cor `darkred`
* Filmes em exibição amanhã utilizam a cor `darkblue`
* Links não possuem sublinhado
* Links dentro de títulos de nível 2 utilizam a cor `seagreen`
* Parágrafos possuem fonte de `20px`
* Todo o site utiliza a família de fontes Arial

## Tecnologias utilizadas

* HTML5
* CSS3

## Conceitos praticados

* Estruturação de páginas HTML
* Links e navegação entre páginas
* Organização de arquivos e diretórios
* Uso de caminhos relativos
* Títulos e parágrafos em HTML
* Folha de estilos externa
* Seletores CSS
* Cores e tipografia
* Compartilhamento de estilos entre diferentes páginas

## Objetivo

Praticar os fundamentos de HTML e CSS por meio da construção de um site com múltiplas páginas, desenvolvendo conhecimentos sobre navegação, organização de arquivos e aplicação de estilos externos.
