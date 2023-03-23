---
title: "Nunca uses passwords de origem. Explicamos porquê"
date: "2017-02-06"
categories: 
  - "tecnologia"
  - "tvmedia"
tags: 
  - "botnet"
  - "cctv"
  - "default"
  - "dvr"
  - "efsecurity"
  - "efsecurity"
  - "insecam"
  - "mirai"
  - "palavra-apasse"
  - "password"
  - "passwords"
  - "rubricas-tecnologia"
  - "seguranca"
---

No [artigo anterior](https://espalhafactos.com/2017/01/02/efsecurity-cadeira-teclado-esta-das-chaves-da-seguranca/) da rubrica, referi no final do texto que muitas vezes o problema está entre a cadeira e o teclado. No entanto isto nem sempre se aplica. Por vezes a falha está - parcial ou totalmente - no próprio produto, e pouco ou nada pode ser feito por parte do utilizador.

Há situações em que a culpa é parcialmente do utilizador. No lado do utilizador, a culpa deve-se à utilização de dados (nomes de utilizador e palavras-passe) genéricos nos equipamentos. Do lado do fabricante, por não alertar para os riscos da utilização desses dados ou não fornecer uma forma simples e percetível de os alterar, e por não disponibilizarem atualizações para correção de falhas de segurança. Como todos bem sabemos, ninguém é obrigado a ser versado nas novas tecnologias.

Noutros casos, bem mais graves, alguns fabricantes incluem dados de acesso codificados no próprio _firmware_ e que não são documentados. Significa isto que os teus equipamentos podem ter uma forma de acesso oculta e que qualquer pessoa com conhecimentos para tal os pode explorar para efeitos maliciosos.

### O problema dos dados genéricos

Em setembro do ano passado, o _website_ do jornalista de segurança informática **Brian Krebs** sofreu um dos [maiores ataques _DDoS_](https://krebsonsecurity.com/2016/09/krebsonsecurity-hit-with-record-ddos/) até à data: sensivelmente 620Gbps de tráfego. Metade deste valor é mais do que suficiente para tornar indisponível muitos _sites_.

A origem foi uma _botnet_ chamada _Mirai_. A maioria dos equipamentos infetados e controlados por ela eram câmaras _CCTV_ expostas na _web_, mas também _routers_ e _DVRs_. Análises feitas ao ataque revelaram que estes dispositivos estavam espalhados por mais de 150 países.

**Para conseguir infetar os equipamentos, a _botnet_ recorreu à técnica de “força bruta”, isto é: utilizava uma lista de utilizadores e palavras-passe comuns para tentar o _login_**. Tendo sucesso, infetava o equipamento.

Este tipo de acesso forçado é uma das técnicas usadas habitualmente. Se pesquisares em qualquer motor de busca, vais encontrar vários dicionários (é este o nome dado às listas com dados genéricos) que podes descarregar e utilizar para diversos efeitos. Alguns incluem a adivinhação das _passwords_ das redes sem fios. Recomendo, claro, que o faças dentro dos limites da lei.

Percebes agora o risco de utilizar dados padrão para acesso aos equipamentos? Se ainda não o assimilaste, recomendo-te que visites os endereços [insecam.org](//insecam.org) e [github.com/turbo/c4](https://github.com/turbo/c4). Ambos contêm listas de câmaras de videovigilância sem _password_ ou com dados padrão, às quais qualquer pessoa pode aceder para acompanhar as imagens. É assustador o número de _CCTVs_ que estão listados nestes endereços. E sim, algumas estão em Portugal.

### Possíveis soluções

Uma possível solução passa pela utilização de palavras-passe atípicas e difíceis de adivinhar. Elas não têm que ser uma combinação sem nexo de números, letras e os designados carateres especiais (como o cardinal, asterisco, etc.) Se, por exemplo, gostares de futebol, podes usar algo como “OBenficaVaiSerCampeão. CarregaBenfica.”\[1\]. É extensa, com maiúsculas, minúsculas e os tais carateres especiais, mas em simultâneo é fácil de decorar.

Se futebol não for a tua praia, podes, por exemplo, usar o teu programa preferido como base. “StrangerThingsIsTheBestTVShowInTheWorld” é outro exemplo. O limite é a vossa imaginação.

E não te esqueças de ir verificando se o fabricante dos teus equipamentos tem atualizações para eles. Se existirem, instala-as.

\[1\] peço que não me levem a mal usar o SLB como exemplo. Podem utilizar o FCP, o SCP, o VFC ou outro clube qualquer. Eu não sofro nem gosto de _futebolices_ e espero que tu também não.
