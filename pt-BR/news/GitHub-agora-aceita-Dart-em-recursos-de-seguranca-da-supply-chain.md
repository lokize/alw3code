---
title: "GitHub agora aceita Dart na supply chain"
token: "GitHub agora aceita Dart na supply chain"
category: dart
description: "Aplicativos multi-plataforma construídos com o kit de ferramentas Flutter agora se beneficiam de alertas do Dependabot"
media: https://github.com/lokize/alw3code/blob/main/img/dart.png?raw=true
by: "Lokize"
like:
dislike:
rate: 0
---

# Introducao

O que aplicativos como Google Ads, eBay Motors e Alibaba Xianyu têm em comum? Além de milhões de usos mensais, cada um foi construído com o popular framework Flutter,  desenvolvido com a Dart, uma linguagem de programação projetada para o desenvolvimento do cliente, como para a web e aplicativos móveis.

Dado seu rápido crescimento e ampla adoção – e graças a uma colaboração com a equipe Dart no Google – os recursos de segurança da supply chain do GitHub agora suportam o ecossistema de desenvolvimento Dart. Isso torna mais fácil para pessoas desenvolvedoras e equipes de segurança visualizarem, manterem e protegerem as dependências na supply chain do software Dart.

Segundo Michael Thomson, Gerente de Produto do Grupo do Google, “o GitHub é usado diariamente por milhares de pessoas desenvolvedoras de Dart e Flutter para criar aplicativos multiplataforma. Ao colaborar com o GitHub para adicionar o Dart aos recursos de segurança da supply chain, a comunidade  do Dart têm novas maneiras de encontrar e corrigir problemas antes deles afetarem seus clientes”.

# Avisos de seguranca do GitHub

O GitHub Advisory Database é um banco de dados aberto de alta qualidade para pessoas desenvolvedoras, com avisos de segurança focados em informações de vulnerabilidade acionáveis. Mantenedores do pacote Dart agora podem usar os Avisos de Segurança do GitHub para colaborar com relatórios de vulnerabilidades e para discutir e corrigir vulnerabilidades em particular antes de anunciá-las publicamente.

Além disso, caso a pessoa usuária encontre uma vulnerabilidade do Dart com um CVE que não esteja no banco de dados consultivo do GitHub, poderá denunciá-la por meio de uma contribuição da comunidade.

O gráfico de dependência analisa os arquivos pubspec.yaml e pubspec.lock de um repositório para determinar as dependências usadas em seu projeto. Isso serve como backbone para o Dependabot, que alerta quando há uma vulnerabilidade conhecida e cria pull requests para atualizar a dependência afetada. Para visualizar as dependências detectadas de um repositório, selecione a guia Insights e, depois, escolha Gráfico de Dependência na barra à esquerda.


O gráfico de dependência é habilitado como padrão para repositórios públicos, mas deve ser habilitá-lo manualmente em repositórios privados.

Pode-se impedir que as vulnerabilidades em um código Dart sejam introduzidas com a revisão de dependência GitHub Action. Esta ação verifica pull requests para alterações nas dependências do Dart e gera um erro para vulnerabilidades conhecidas para mantê-las fora do novo código.

# Alertas e atualizacoes Dependabot

Os alertas do Dependabot notificam quando novas vulnerabilidades são descobertas em pacotes Dart que já estiverem em utilização, e essas criarão pull requests para atualizar automaticamente os pacotes com erro para uma versão sem a vulnerabilidade. Existe a opção de configurar os alertas e atualizações de segurança do Dependabot para receber apenas notificações específicas para seu repositório.

Com essas atualizações, o GitHub capacita o setor Tech a proteger a supply chain de software com soluções de ponta a ponta, renovando seu compromisso com o desenvolvedor de tornar a experiência de programação cada vez mais segura, colaborativa e positiva.
