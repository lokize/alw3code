---
title: "Instalando Docker no CentOS 9 Stream"
token: "Instalando Docker no CentOS 9 Stream"
category: docker
description: "passo a passo para instalar o docker no centos stream 9"
media: "https://github.com/lokize/alw3code/blob/main/img/docker-min.jpg?raw=true"
by: "Lokize"
featured: true
---
## Afinal pra que serve o Docker?

O Docker é uma plataforma open source que facilita a criação e administração de ambientes isolados. Ele possibilita o empacotamento de uma aplicação ou ambiente dentro de um container, se tornando portátil para qualquer outro host que contenha o Docker instalado. Então, você consegue criar, implantar, copiar e migrar de um ambiente para outro com maior flexibilidade. A ideia do Docker é subir apenas uma máquina, ao invés de várias. E, nessa única máquina, você pode rodar várias aplicações sem que haja conflitos entre elas.

Vale lembrar que a tecnologia e a empresa compartilham o mesmo nome. A empresa Docker Inc. desenvolve a tecnologia com base no trabalho realizado pela comunidade do Docker. Essa comunidade trabalha gratuitamente para melhorar essas tecnologias em benefícios de todos.


<figure><br>
  <img
    src="/blog/dockercartoon.jpeg"
    alt=""
  />
  <figcaption>
    Wall-e picture by <a href="https://unsplash.com/@mariushaak"><strong>@mariushaak</strong></a> on <a href="https://unsplash.com/"><strong>Unsplash</strong></a>
  </figcaption>
</figure>

## Por onde iniciar?

O primeiro passo é instalar os pacotes necessários para o docker funcionar bem nesta distribuição linux

```sh
git  clone  https://github.com/KimangKhenng/Traffic-SImulation-and-Visualization.git
```

 ```javascript
curl https://download.docker.com/linux/centos/docker-ce.repo -o /etc/yum.repos.d/docker-ce.repo
sed -i 's/$releasever/8/g' /etc/yum.repos.d/docker-ce.repo
dnf install docker-ce -y
```

## Can AI exist entirely on its own?

The idea of autonomous robots has again reinvigorated the belief in the future of AI to replace human beings. Although autonomous robots are trained to make decisions independent of human directives, they still need human support in terms of deployment, consultation, or even manual controlling. Let’s take the curiosity rover for example, of course, it worked on behalf of human beings for exploration on Mars. It collected data, analyzed Martian terrain, and answer the ultimate question of whether there was life on the red planet. However, the robot is said to be objective in that it only serves some specific purposes to exist on its own. The microcontroller chip inside holds only certain instructions for the corresponding events that might occur and affect the robot on Mar in its lifetime. What if a giant asteroid suddenly hit Mars like it hit the earth in ancient times that might destroy the rover, how would the rover then respond? Was it programmed to respond to such events? Can it realize what’s happening and take a wise course of action? This indeed would require a General-Purpose Artificial Intelligence — or put it more accurately, an Artificial Human Being.
We can draw the conclusion that Artificial Intelligence and humans coexist in a joint effort as each entity needs the other to fulfill its respective tasks.
