<h1>Adapt4_invest<p>
  <h3> Uma das iniciativas da <a href="http://www.adapt4.com.br"> Empresa adapT4 </a> é disponibilizar a expertise e conhecimento de operações no mercado financeiro, com objetivos claro no acumulo de patrimônio. </h3>
</h1> 

<h2> Operacional </h2>
<div> <strong>Futuros</strong> com WDO, WIN, CCM, BGI, BTC, JURO se utilizando de operações diárias e medindo risco inerente a volatilidade do dia. </div>
<div> <strong>Posições</strong> em compras médias com AÇÕES brasileiras == systema de recomendação em desenvolvimento... </div>
<div> <strong>Opçoes</strong> modelando sistema para ser adicionado as operações. </div>
</h3>

<h2> Segurança </h2>
  <ol>
    <li> Não acessamos sua conta corretora </li>
    <li> Login e senha que utilizamos é da plataforma contratada pelo cliente </li>
    <li> Utilizamos nossas estações para cada cliente </li>
    <li> Repasse do pagamento é feito do cliente para adapT4 </li>
    <li> Cliente recebe infome detalhado e seus tributos a pagar </li>   
  </ol>  
<h2>

</h2>

<h2> Fluxo de Relação </h2>

```mermaid
graph LR;
_ADAPT4_ --> bot_adapT4;
bot_adapT4 --> SERVIDOR;
SERVIDOR --> máq_usuário;
máq_usuário --> plataforma_mt5;


*CLIENTE* --> conta_corretora;
conta_corretora --> contrata_mt5;
contrata_mt5 --> login_senha_mt5;
login_senha_mt5 --> mt5_cliente;
mt5_cliente --> plataforma_mt5;

plataforma_mt5 --> conecta_mt5;
conecta_mt5 --> apuração_mes;
apuração_mes --> %_pagamento_adapT4;
apuração_mes --> pagamento_Imposto_DARF;

conta_corretora --> conta_corrente;
conta_corrente --> margem_mt5;
margem_mt5 --> conta_corrente;

```
</details>



<details>
     <summary> CORRETORAS IDEAIS </summary>
    
```
As 3 corretoras são as indicadas para contratar o serviço da plataforma MT5:

XP - Permitido operações de daytrade e position. Custo 0/mes ao contratar.
RICO - Permitido operações de daytrade e position. Custo 0/mes ao contratar.
TERRA - Permitido operações de daytrade e position. Custo R$ 50,00/mes ao contratar.

Órama - Foi comprada recentemente pelo BTG, deixou de fornecer ambas as modalidades de operação.
* As demais corretoras até o momento só permitem operações de daytrade. O que impacta nosso modelo operacional em determinados ativos e impacta tambem nos custo.

```

<details>
     <summary> xxx </summary>
    
```

```
</details>
