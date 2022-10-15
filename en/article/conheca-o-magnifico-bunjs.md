---
title: "Conheça o Magnífico BunJS"
token: "Conheça o Magnífico BunJS"
category: javascript
description: "Conheça mais sobre Bun: o novo runtime para Javascript"
media: https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/BunjsLogoOnLaptop-1.jpg
by: "Lokize"
like:
dislike:
rate: 0
---

# O que faz um runtime?

Runtime é o ambiente onde o javascript será executado.

Caso não tenha entendido ainda, eu te explico. O trabalho do runtime é executar o JavaScript fora do navegador, assim sendo o primeiro passo para que o JS possa ser usado como uma linguagem de backend. Primeiramente é necessário implementar o seu motor de execução o que no caso do node é usado o V8 que é o motor da Google.

Porém apenas isso não é o suficiente para que JS seja uma linguagem de backend pois por si só o JavaScript não acessa o FileSystem, não sobe servidor, resumindo ele não vai interagir com nada da sua máquina. Então entra o runtime a plataforma onde o seu código JS será executado, o mesmo pode implementar bibliotecas para aprimorar a linguagem. O runtime mais conhecido hoje em dia é o Node.js, porém nós iremos falar sobre um cara novo chamado bun.js

# Sobre o Bun

O bun.js é um novo runtime para JavaScript criado com as seguintes premissas

Start fast (it has the edge in mind). Iniciar rápido

New levels of performance (extending JavaScriptCore, the engine). Novos niveis de performance (extendo o core do Javascript)

Being a great and complete tool (bundler, transpiler, package manager). Sendo uma ferramente ótima e completa (bundler, transpilador e gerenciador de pacote)

A ideia do bun é que ele consiga substituir o seu runtime atual sem muito problemas. Até por isso ele implementa alguns módulos do NodeJS e ultiliza bibliotecas do NPM. Você pode checar quais APIs são implementadas neste link.

Além disso o bun também da suporte a arquivos TypeScript e JSX como a própria documentação diz, "isso apenas funciona".

Resumindo o bun é um runtime que ultiliza API's do NodeJs, pacotes do npm, compila códigos TypeScript e JSX e faz tudo isso de uma forma muita mais rápida que o Deno e o NodeJS.

# O que difere o Bun dos demais?

No geral o bun acaba sendo mais rápido que o seu concorrentes em lidar com requisições HTTP, realizar mais queries por segundo e resolver mais operações por segundo. Abaixo coloquei alguns prints dos gráficos que são apresentados no site do runtime.

#### Requisições HTTP

<figure><br>
  <img
    src="https://github.com/lokize/alw3code/blob/main/img/bunhttp.png?raw=true"
    alt=""
  />
  <figcaption>
    As requisições http do <a href="https://bun.sh/"><strong>Bun</strong></a>
  </figcaption>
</figure>

#### Queries

<figure><br>
  <img
    src="https://github.com/lokize/alw3code/blob/main/img/bunqueryes.png?raw=true"
    alt=""
  />
  <figcaption>
    A velocidade das queryes
  </figcaption>
</figure>

#### Operacoes por segundo

<figure><br>
  <img
    src="https://github.com/lokize/alw3code/blob/main/img/bunopseg.png?raw=true"
    alt=""
  />
  <figcaption>
    As operações por segundo do Bun
  </figcaption>
</figure>


# Extemamente veloz

O Bun foi criado usando uma linguagem de programação multi-paradigma chamada Zig, também foi criado pensando em padrões de projetos mais modernos e ultilizando o motor JavaScriptCore ao contrário do NodeJS e Deno que usam o motor V8.

# A parte a ser melhorada

E por último, mas não menos importante, os testes. De fato Bun é novo e certamente tem bugs. Sumner seu criador está ciente disso e credita a falta de testes generalizados como uma das razões pelas quais é tão problemático. Sobre isso, ele diz, “o Bun não tem cobertura de teste suficiente e é por isso que é tão problemático”. Bun tem um executor de teste JavaScript e o comando cli é bun wiptest.

No geral os Desenvolvedores junto com Sumner estão muito empolgados com Bun e, embora ainda seja novo, há grandes esperanças para ele. Sumner disse: “Eu venho da perspectiva de 'ele precisa funcionar o máximo possível com o ecossistema existente porque as pessoas não deveriam ter que reescrever seu código', mas talvez eu deva começar a pensar mais sobre o que fazer se fizermos/ que coisas novas são possíveis porque o bun APIs permite.”

