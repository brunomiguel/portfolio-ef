---
title: "Waterfox é um browser baseado no Firefox que aposta na performance"
date: "2017-02-15"
categories: 
  - "tecnologia"
  - "tvmedia"
tags: 
  - "browser"
  - "download"
  - "firefox"
  - "internet"
  - "linux"
  - "macos"
  - "perf"
  - "performance"
  - "software"
  - "waterfox"
  - "windows"
---

_[**Waterfox**](http://waterfoxproject.org/)_ é um _browser_ baseado no [_Firefox_](https://espalhafactos.com/2016/12/03/tornar-browser-seguro/), criado em 2011 por Alex Kontos, na altura um jovem de 16 anos, com o objetivo de melhorar a performance do navegador da _Mozilla_. Atualmente, tenta ser uma plataforma mais ética e orientada para o utilizador, sem perder o foco na fluidez.

As semelhanças entre o _Waterfox_ e o _Firefox_ são muitas, não fosse um baseado no outro. As diferenças, no entanto, são poucas, mas importantes para os propósitos do projeto.

### As diferenças

Uma dessas diferenças é a utilização do [_Ecosia_](https://www.ecosia.org) como motor de busca padrão, um projeto que tem como objetivo plantar árvores com as receitas geradas. Se preferires o [_Google_](https://google.pt), [_Sapo_](https://www.sapo.pt/pesquisa), [_Duck Duck Go_](https://duckduckgo.com/) ou outro para as pesquisas, podes fazer a alteração normalmente como farias no _Firefox_.

Também, não vem com o [_Pocket_](https://getpocket.com) e o [sistema](https://wiki.mozilla.org/Media/EME) [_DRM_](http://drm.info/index.pt.html) da _Adobe_ (este último significa que não poderão ver conteúdos no _Netflix_, por exemplo) integrados, não recolhe estatísticas de utilização e pode utilizar todos os _plugins_ de 64bit, mesmo os que a _Mozilla_ bloqueia no _Firefox_.

Estas não são as únicas diferenças. Por exemplo, o _Waterfox_ passa opções de otimização mais "agressivas" para o compilador. Para veres estas e outras, recomendo-te uma análise ao [repositório](https://github.com/MrAlex94/Waterfox/) do código-fonte da aplicação no _Github_.

### É mesmo mais rápido?

Os testes que realizei a ambos, com o mesmo perfil (extensões, cache, configurações, etc), mostram poucas diferenças. Por exemplo, o _Waterfox_ demora menos uns milésimos de segundo a abrir e utiliza ligeiramente menos os processadores.

Na utilização de memória _RAM_ a diferença é um pouco maior. O _Firefox_ utiliza quase mais 20MB, como poderás ver nas imagens que se seguem.

\[su\_custom\_gallery source="media: 246839,246840" limit="21" link="lightbox" width="1100" height="700" title="always"\]\[su\_custom\_gallery source="media: 196375,196380,196379,196378,196377,196376" link="custom" width="800" height="400" title="never"\]\[/su\_custom\_gallery\]

Estes testes foram realizados em [_Arch Linux_](https://www.archlinux.org/), com a função _time_ da _Bash_ e com o [_perf_](https://perf.wiki.kernel.org/index.php/Main_Page). Os teus resultados poderão variar porque o _hardware_, sistema operativo, compilador, bibliotecas, etc, têm sempre influência na performance.

### Download do Waterfox

A aplicação está disponível apenas para plataformas de 64bit. _Linux_, _macOS_ e _Windows_ são os sistemas operativos oficialmente suportados, com binários disponíveis para cada um deles. Se utilizares outro sistema operativo, tens que compilar o _browser_ a partir do código-fonte.

\[su\_button url="https://www.waterfoxproject.org/downloads" target="blank" style="flat" icon="icon: cloud-download" rel="nofollow"\]Download\[/su\_button\]
