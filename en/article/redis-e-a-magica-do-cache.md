---
title: "Redis e a mágica do cache"
token: "Redis e a mágica do cache"
category: database
description: "Entenda melhor o que é e pra que serve o Redis"
media: https://github.com/lokize/alw3code/blob/main/img/redis.png?raw=true
by: "Lokize"
featured: true
---
# Entenda pra que serve o Redis

O Redis é um armazenamento de estrutura de dados de chave-valor de código aberto e na memória. O Redis oferece um conjunto de estruturas versáteis de dados na memória que permite a fácil criação de várias aplicações personalizadas. Os principais casos de uso do Redis incluem cache, gerenciamento de sessões, PUB/SUB e classificações. É o armazenamento de chave-valor mais conhecido atualmente. Ele tem a licença BSD, é escrito em código C otimizado e é compatível com várias linguagens de desenvolvimento. Redis é um acrônimo de REmote DIctionary Server (servidor de dicionário remoto).

Por conta da sua velocidade e facilidade de uso, o Redis é uma escolha em alta demanda para aplicações web e móveis, como também de jogos, tecnologia de anúncios e IoT, que exigem o melhor desempenho do mercado. A AWS oferece compatibilidade com o Redis por meio de um serviço de banco de dados gerenciado e otimizado chamado Amazon ElastiCache for Redis, além de permitir que os clientes executem o Redis autogerenciado no AWS EC2.

# Desempenho muito rápido

Todos os dados do Redis residem na memória principal do seu servidor, em contraste com a maioria dos sistemas de gerenciamento de banco de dados que armazenam dados em disco ou SSDs. Ao eliminar a necessidade de acessar discos, bancos de dados na memória, como o Redis, evitam atrasos de tempo de busca e podem acessar dados com algoritmos mais simples que usam menos instruções de CPU. Operações comuns exigem menos do que 10 milissegundos para serem executadas.

# Estruturas de dados na memória

O Redis permite que os usuários armazenem chaves que fazem o mapeamento para vários tipos de dados. O tipo de dados fundamental é uma string, que pode ser em formato de dados de texto ou binários e ter no máximo 512 MB. O Redis também é compatível com listas de strings na ordem em que foram adicionadas, conjuntos de strings não ordenadas, conjuntos classificados ordenados de acordo com uma pontuação, hashes que armazenam uma lista de campos e valores e HyperLogLogs para contar os itens exclusivos de um conjunto de dados. Praticamente qualquer tipo de dados pode ser armazenado na memória usando o Redis.

# Versatilidade e facilidade de uso

O Redis é disponibilizado com várias ferramentas que tornam o desenvolvimento e as operações mais rápidas e fáceis, inclusive o PUB/SUB para publicar mensagens nos canais que são entregues para os assinantes, o que é ótimo para sistemas de mensagens e chat, as chaves com TTL podem ter um tempo de vida útil determinado, após a qual elas se autoexcluem, o que ajuda a evitar sobrecarregar o banco de dados com itens desnecessários, os contadores atômicos garantem que condições de corrida não criem resultados incompatíveis, além da Lua, uma linguagem de script potente, porém leve.

# Replicação e persistência

O Redis emprega uma arquitetura no estilo mestre/subordinado e é compatível com a replicação assíncrona em que os dados podem ser replicados para vários servidores subordinados. Isso pode disponibilizar desempenho de leitura melhorado (à medida que as solicitações podem ser divididas entre os servidores) e recuperação quando o servidor primário passar por uma interrupção.

Para disponibilizar durabilidade, o Redis oferece compatibilidade com snapshots point-in-time (copiando o conjunto de dados do Redis no disco) e criando um Append Only File (AOF) para armazenar cada alteração de dados no disco conforme elas vão sendo gravadas. Os dois métodos permitem a restauração rápida dos dados do Redis no caso de uma interrupção.

# Compatibilidade com a sua linguagem

Mais de cem clientes de código aberto estão disponíveis para os desenvolvedores do Redis.

As linguagens compatíveis incluem Java, Python, PHP, C, C++, CSharp, JavaScript, Node.js, Ruby, R, Go e muitas outras.

