---
title: "Ciberpiratas podem roubar senha dos Macs em 30 segundos"
date: "2016-12-16"
categories: 
  - "tecnologia"
  - "tvmedia"
tags: 
  - "apple"
  - "bugs"
  - "direct-memory-access"
  - "dma"
  - "efi"
  - "mac"
  - "macos"
  - "microsoft"
  - "seguranca"
  - "uefi"
  - "windows"
---

Os **Macs**, e o seu sistema operativo, _macOS_, são considerados mais seguros que o _Windows_ e os computadores onde o _software_ da _Microsoft_ é instalado. Uma nova dose de realidade vem, mais uma vez, ajudar a desfazer este mito.

**Ulf Frisk**, um _hacker_ e _penetration tester_ sueco, desenvolveu um método para descobrir a palavra-passe de bloqueio do _macOS_ em apenas 30 segundos. Basta apenas um pequeno equipamento que custa mais ou menos 300 dólares, chamado [_PCILeech_](https://github.com/ufrisk/pcileech).

#### Como funciona:

O método recorre a duas falhas de segurança no _FileVault2_, o sistema de encriptação de disco da _Apple_. Ambas foram descobertas por Ulf Frisk em julho deste ano.

A primeira deve-se ao facto do sistema _[EFI](https://pt.wikipedia.org/wiki/EFI)_ (_Extensible Firmware Interface_), utilizado nos _Macs,_ permitir que os dispositivos ligados por _Thunderbolt_ tenham acesso à memória, sem que exista um sistema que impeça o acesso direto à memória - ou _DMA (Direct Memory Access)_.

Segundo, a senha do _FileVault2_ é armazenada na memória do equipamento em texto simples _(plain text)_, mesmo que o computador se encontre suspenso ou bloqueado. Quando é reiniciado, a _password_ é colocada em vários locais da memória, dentro de um intervalo fixo, e assim é possível ser lida.

O vídeo em baixo mostra como tudo é feito:

<iframe src="https://www.youtube.com/embed/n_3eIFMR46Y" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

#### Como evitar esta falha:

Existem, de momento, duas formas de evitar este ataque. A primeira é a instalação das atualizações para o _macOS_. As falhas foram reportadas à _Apple_ e, no dia 13 de dezembro, foram corrigidas na versão 10.12.2 do sistema operativo.

A segunda, caso não tenham instalado as atualizações, passa por impedirem que qualquer pessoa tenha acesso físico ao vosso _Mac_. Não basta apenas bloquear a sessão ou suspender o equipamento; tem que ser desligado.
