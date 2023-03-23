---
title: "Avast alvo de ataque informático, Ccleaner era o objetivo"
date: "2019-10-22"
categories: 
  - "tecnologia"
  - "tvmedia"
tags: 
  - "ataque"
  - "avast"
  - "ccleaner"
  - "ciberseguranca"
  - "malware"
---

A empresa checa **_Avast_** sofreu um ataque à sua rede interna em meados de maio. De acordo com o [comunicado oficial](https://blog.avast.com/ccleaner-fights-off-cyberespionage-attempt-abiss), o alvo era o **_Ccleaner_**.

A _Avast_ foi alvo de um **ataque informático** que terá tido como objetivo a inserção de código malicioso na aplicação _Ccleaner_. O ataque, apelidado de _Abiss_, começou a 14 de maio deste ano e só foi detetado no final de setembro.

Para aceder à rede interna, o atacante comprometeu as credenciais de um funcionário para acesso por _VPN_. A conta alvo do ataque não tinha privilégios de administrador do domínio, mas isso não impediu o atacante de escalar os privilégios da conta e replicar a implementação de _Active Directory_, tendo ficado efetivamente com um "mapa" da rede da empresa.

Quando o ataque foi finalmente detetado, a 23 de setembro, a empresa decidiu manter a conta ativa para poder monitorizar o atacante. Dois dias depois, foi suspenso o lançamento de novas versões do _Ccleaner_, para que as versões da aplicação lançadas desde o início do ataque fossem auditadas.

A 15 de outubro, depois de confirmar que não tinha sido distribuído código malicioso com a aplicação, a empresa "tapou o buraco".

Para além desta, foram tomadas mais duas medidas para evitar problemas futuros. Uma delas foi o _reset_ forçado a todas as contas. A outra foi a emissão de um novo certificado digital para assinar a aplicação, com a consequente revogação do certificado anterior. A revogação tem como objetivo evitar que o certificado antigo seja usado para, por exemplo, distribuir cópias comprometidas do _Ccleaner_.

Esta não é a primeira vez que a aplicação _Ccleaner_ é alvo de um ataque, como já te tínhamos [informado](https://espalhafactos.com/2017/09/18/ccleaner-infetado-com-malware/). Já em 2017, antes da _Avast_ comprar a aplicação à _Piriform_, o programa esteve a ser distribuído durante um mês, pelos canais oficiais, com _malware_.

Se utilizas o _Ccleaner_, recomendo-te que, por descargo de consciência, coloques o teu antivírus a fazer uma análise extensiva.
