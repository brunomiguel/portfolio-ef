---
title: "Como melhorar a performance do Firefox"
date: "2017-02-15"
categories: 
  - "tecnologia"
  - "tvmedia"
tags: 
  - "browser"
  - "dicas"
  - "firefox"
  - "historico"
  - "performance"
  - "software"
  - "tutorial"
---

O **Firefox** é um excelente _browser_, mas sofre de problemas de _performance_ após algum período de utilização sem o reiniciar ou fechar. A origem está, entre outras coisas, nos valores padrão de algumas opções. Neste caso em concreto, opções relacionadas com o histórico.

Resolver isso é simples e rápido. Segue os passos abaixo e coloca as tuas dúvidas nos comentários.

### As alterações

Abre o _browser,_ escreve _about:config_ na barra de endereço e pressiona _Enter_. Clica no botão do aviso para acederes a todas as opções. Agora, necessitas de criar quatro entradas novas: para isso, basta clicares com o botão direito do rato em cima de qualquer opção, escolher “novo” e de seguida “inteiro”.

As novas opções são:

- [browser.history\_expire\_days](http://kb.mozillazine.org/Browser.history_expire_days)
- [browser.history\_expire\_days\_min](http://kb.mozillazine.org/Browser.history_expire_days_min)
- [browser.history\_expire\_sites](http://kb.mozillazine.org/Browser.history_expire_sites)
- [browser.history\_expire\_visits](http://kb.mozillazine.org/Browser.history_expire_visits)

Para cada uma destas entradas, defini os valores de 30, 30, 4000 e 2000, respetivamente. Podes, no entanto, definir qualquer outro valor. Salvaguardo que, quanto maiores os valores colocados, maior será o histórico do _Firefox_ e pior a performance.

##### Lê também: [Waterfox é um browser baseado no Firefox que aposta na performance](https://espalhafactos.com/2017/02/15/waterfox-um-browser-baseado-no-firefox-aposta-na-performance/)

### As opções

##### browser.history\_expire\_days

Esta opção define o número máximo de dias em que um _site_ se mantém no histórico de visitas do _browser_. O valor padrão é 180, o que significa que o Firefox guarda o histórico de navegação dos últimos 180 dias.

##### browser.history\_expire\_days\_min

Esta é semelhante à anterior, mas refere-se ao número de dias de histórico que o _browser_ guarda na memória quando está a ser executado. Aqui, o valor padrão é 90.

##### browser.history\_expire\_sites

O histórico do Firefox tem um limite máximo de entradas nessa lista. O valor padrão é 40,000 e elas vão sendo criadas à medida que se vai navegando. Diminuindo o valor, aumenta-se a _performance_.

##### browser.history\_expire\_visits

Esta é a versão anterior da opção supramencionada. A função é essencialmente a mesma, apesar de funcionarem de forma ligeiramente diferente: a anterior define um teto máximo e esta cria logo o número de entradas no histórico e vai-as preenchendo à medida que se visitam os _sites_.

_Artigo [publicado](http://blog.brunomiguel.net/dicas/como-melhorar-a-performance-do-firefox-parte-i) inicialmente no meu blog pessoal._
