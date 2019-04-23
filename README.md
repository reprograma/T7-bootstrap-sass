# T7-bootstrap-sass
Turma 7 | Front-end | 2019 | Semana 9 | Bootstrap e Sass

O objetivo deste módulo é apresentar às alunas os frameworks css com foco em bootstrap e o uso de pré-processadores, neste módulo será usado o Sass.

***

* [Bootstrap](#bootstrap)
  * [Instalação](#instalação)
  * [Aula 1](#aula-1)

***

## Bootstrap 
## Documentação 
[Versão PT/BR](https://getbootstrap.com.br/)

### Instalação
### Instalação do Bootstrap via CDN
  
  - [O que é CDN ?](https://www.youtube.com/watch?v=02rvd_7HcFY)
  - Quais scripts usar? Onde colocar os scripts?
  
### colar no head

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```
### colar no script no final do body
```
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```

### Instalação do Bootstrap via NPM
- Verificar se tem o Nodejs instalado na máquina, caso contrário instalar. https://nodejs.org/en/
- No terminal, na pasta do projeto executar: npm init e responder as perguntas
- Instalar o bootstrap: npm install bootstrap
- Copiar os arquivos .js e .css que estão em node_modules/bootstrap/dist para sua pasta do projeto em que consta os arquivos js e css
- Chamar os arquivos do bootstrap no index.html, lembrar de chamar sempre após os arquivos do Jquery

### Instalação do Jquery
- Instalar o jquery: npm install jquery
- Copiar o arquivo jquery.slim.min.js que está em node_modules/jquery/dist para sua pasta do projeto em que consta os arquivos js
- Chamar o arquivo do jquery no index.html, lembrar de chamar sempre antes dos arquivos do Bootstrap

### Criando Arquivo Git Ignore
Na raíz do projeto criar um arquivo com o nome .gitignore
Dentro desse arquivo você vai colocar os arquivos que não serão enviados no push do git, por exemplo a pasta com as nossas bibliotecas: node_modules

## Planejamento - Bootstrap
Planejamento da aula da Reprograma da T6 sobre Bootstrap

### Aula 1 - 06/05
Nesta primeira aula irei abordar brevemente os frameworks de css usados no mercado, a importância de aprender bootstrap e os prós e contras de usá-lo. 
Slides: https://docs.google.com/presentation/d/10SqDClB9mymaVEBu9wBy9k4tdtoESua9VcK27NPgVug/edit?usp=sharing

Explicarei data-toggle, data-target e vamos trabalhar os principais componentes do bootstrap.
Para esse exercício vou usar o seguinte modelo: https://blackrockdigital.github.io/startbootstrap-modern-business/

### Aula 2 - 07/05

#### Exercício/projeto: Sessão da tarde
https://github.com/reprograma/T7-javascript-I/blob/master/aula-2/exercicio.md