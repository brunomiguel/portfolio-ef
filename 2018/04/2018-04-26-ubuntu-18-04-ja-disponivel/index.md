---
title: "Ubuntu 18.04 já disponível, confere as novidades"
date: "2018-04-26"
categories: 
  - "tecnologia"
  - "tvmedia"
---

A nova versão do _[**Ubuntu**](https://ubuntu.com)_ já está disponível para download. Esta é também a nova **LTS** (_Long Term Support_) do projeto, o que significa que terá atualizações e suporte durante 5 anos.

Se já tens uma versão anterior do _Ubuntu_ instalada, irás receber uma notificação da disponibilidade da nova versão, notificação essa que te permite iniciar o processo de atualização. Contudo, se tens outro sistema operativo instalado e queres instalar este, precisas apenas de **[descarregar](http://releases.ubuntu.com/18.04/ubuntu-18.04-desktop-amd64.iso)** o ficheiro ISO do _website_ do projeto e seguir as [**instruções de instalação**](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-windows#0).

Não te preocupes se já tiveres outro sistema operativo instalado, como por exemplo o _Windows_ 10. O instalador do _Ubuntu_ dá-te a possibilidade de manter o teu outro sistema operativo lado a lado com este. Quando ligares o computador, escolhes em qual deles queres entrar.

### Novidades

#### Arranque mais rápido

Uma das novidades mais badaladas do _Ubuntu_ 18.04 é a diminuição do tempo de arranque do sistema. Esta é uma [promessa](https://community.ubuntu.com/t/desktop-newsletter-19th-jan-2018/3524) da Canonical, a empresa que faz a gestão do projeto.

#### Opção para instalação minimalista

O instalador recebeu uma nova opção que permite ao utilizador realizar uma instalação minimalista. Isto significa que, para além do ambiente gráfico, serão instalados um _browser_ e alguns utilitários.

Aplicações como o [_LibreOffice_](https://libreoffice.org) não são instaladas, como normalmente seriam, quando esta opção é ativada pelo utilizador durante o processo de instalação do sistema operativo.

##### Lê também: [Linux com domínio total no top500 dos supercomputadores](https://espalhafactos.com/2017/11/18/linux-top500-supercomputadores/)

#### Gnome 3.28

O ambiente gráfico padrão é o [_Gnome_](https://gnome.org), na versão 3.28. A utilização deste ambiente gráfico não é novidade para quem utiliza ou utilizou o _Ubuntu_ 17.10, mas sê-lo-à para os utilizadores da anterior versão LTS (16.04).

Para facilitar a adaptação ao novo ambiente gráfico, a Canonical alterou a sessão _default_ do _Gnome_ por forma a que se assemelhe ao ambiente gráfico padrão anterior, o [_Unity_](https://pt.wikipedia.org/wiki/Unity_(interface_de_usu%C3%A1rio)). É, no entanto, possível ter uma sessão sem as alterações da Canonical ou mesmo instalar o ambiente gráfico padrão anterior_,_ que se mantém disponível nos repositórios de _software_.

#### Xorg entra em cena e sai o Wayland

O servidor gráfico padrão é novamente o _Xorg_. No _Ubuntu_ 17.10 foi escolhido o _Wayland_, mas dado o número de aplicações que não funcionavam com ele, a Canonical reverteu a mudança.

#### Instalação mais rápida

Graças à adoção do algoritmo de compressão **_zstd_**, desenvolvido pelo _Facebook_, a instalação do sistema operativo é 10% mais rápida.

### Como atualizar para a nova versão

Se és um utilizador de _Ubuntu_, podes aguardar pela notificação da nova versão, como acontece com as atualizações das aplicações, ou podes forçá-la.

Caso optes pela última, podes fazê-lo de duas formas: com uma aplicação gráfica ou com a linha de comandos. Para utilizares a aplicação gráfica, abre o programa "Atualizações" e segue os passos. Caso prefiras a linha de comandos, corre o teu emulador de terminal preferido e escreve o seguinte:

`sudo do-release-upgrade`

Independentemente da opção que escolhas, serão descarregadas e instaladas automaticamente as atualizações.
