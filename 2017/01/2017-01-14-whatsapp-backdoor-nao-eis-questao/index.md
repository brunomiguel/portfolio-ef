---
title: "Whatsapp: Backdoor ou não? Eis a questão"
date: "2017-01-14"
categories: 
  - "tecnologia"
  - "tvmedia"
tags: 
  - "backdoor"
  - "criptografia"
  - "open-whister-systems"
  - "opiniao-2"
  - "seguranca"
  - "signal"
  - "tobias-boelter"
  - "whatsapp"
---

Nos últimos dias têm-se escrito artigos atrás de artigos sobre um alegado _backdoor_ na aplicação de _instant messaging_ **Whatsapp**. Mas será que ele existe mesmo? Antes de confirmarmos a sua alegada existência, convém primeiro saber o que é exatamente um _backdoor_.

#### O que é um backdoor?

Um _backdoor_ é uma espécie de porta dos fundos, que pode ou não ser propositado. É um método de contornar sistemas de segurança, por forma a ganhar acesso não autorizado a recursos que de outra forma não estariam disponíveis e/ou acessíveis.

Um _backdoor_ pode estar incluído numa aplicação ou ser uma aplicação separada, como um _rootkit_. Pode mesmo ser o próprio _hardware_.

#### Afinal o que se passa com o Whatsapp?

Em abril de 2016, Tobias Boelter, um criptógrafo da Universidade de Califórnia, descobriu que o _Whatsapp_ gera uma chave criptográfica nova quando o utilizador tenta enviar uma mensagem enquanto está _offline_. Assim que há um acesso à Internet, a mensagem é enviada de forma encriptada com a nova chave, mas o utilizador não tem conhecimento disso porque a aplicação não o notifica da alteração. O destinatário recebe normalmente a mensagem, porque a aplicação confia automaticamente na nova chave sem pedir validação.

Boelter afirma que este comportamento permite que o _Facebook_, proprietário do _Whatsapp_, aceda às mensagens dos utilizadores. Este acesso também pode ser feito por piratas informáticos, governos, forças de segurança... a lista continua.

Quando reportou a falha ao _Facebook_, foi-lhe dito que este é o comportamento padrão e esperado da aplicação. Desde essa altura que a aplicação mantém este comportamento e foi por isso que Tobias Boelter decidiu tornar a sua descoberta pública.

Existe inclusive um vídeo no _Youtube_ que demonstra este alegado _backdoor_ e que podes ver abaixo.

https://youtu.be/we-pJE5JjAs

###  O que posso fazer para evitar isto?

O _Whatsapp_ tem uma opção para notificar o utilizador quando há alteração de chave criptográfica. Para isso, deves aceder a Definições > Conta > Segurança e ativar a única opção que aí se encontra.

#### Afinal é ou não um backdoor?

A resposta mais honesta que posso dar é: talvez. As aplicações do _Whatsapp_ (clientes e servidor) são proprietárias, o que significa que não temos acesso ao código-fonte e não o podemos analisar. Sabe-se, no entanto, qual o protocolo utilizado para a encriptação.

Esse protocolo, chamado _Signal_ e desenvolvido pela [_Open Whisper Systems_](https://whispersystems.org/) (que colaborou com o _Facebook_ na implementação dele na aplicação), é aberto e pode ser verificado e implementado por qualquer pessoa com conhecimento para isso. Do que se aferiu até agora, não é uma questão do protocolo.

Aliás, o _Signal_ contempla estas situações de alterações da chave criptográfica e obriga a validação presencial. Quando é com os nossos amigos que vivem próximos de nós, é fácil; quando se trata de contactos noutro país ou continente, torna-se mais complicado.

#### Devo continuar a confiar no Whatsapp?

Citando uma fala do filme _My Blueberry Nights_: «_trust everyone, but always cut the cards_». Ou melhor: confia, desconfiando.

A verdade é que não há sistema de encriptação que te valha quando não há bom-senso na utilização. Porque a maior falha de segurança de todas está [entre a cadeira e o teclado](https://espalhafactos.com/2017/01/02/efsecurity-cadeira-teclado-esta-das-chaves-da-seguranca/).
