---
title:  "O Sistema Informático"
author: Prof. Jocilé Serra
date: 2022-09-04 19:00:00 -0300
categories: [AULAS 2022, MONTAGEM E INSTALAÇÃO DE SISTEMAS]
tags: [manutenção, eletrônica]
---
Um Sistema Informático trata-se de um conjuntos de equipamentos mecânicos e eletrônicos adequados e capazes de processar dados afim de que estes se tornem informação, de forma automática.

## Objetivos

* Conhecer a organização interna de um Sistema Informático;
* Reconhecer os componentes internos do sistemas informáticos;
* Compreender o processo de administração de dados no sistema informático;
* Entender o funcionamento e a importância dos componentes;
* Entender o dimensionamento e a compatibilidade.

## Características

### Arquitetura de Von Neumann

![Arquitetura de Von Neumann]({{site.data.images.von-neumann.link}})
_{{site.data.images.von-neumann.caption}}_

A figura mostra como funciona o sistema onde são introduzidos os dados na Entrada, usando um ou mais dispositivos destinados a esse fim, e são trabalhados dentro de um dispositivo de processamento (UCP). Após o processamento, os dados são exibidos em dispositivos de Saída.  
Os equipamentos que são utilizados como entrada podem ser: mouse, teclado, scanner, webcam, etc. Já os de saída temos como exemplo: monitor, impressora, fone de ouvido, etc.  
Esse modelo é definido desde a arquitetura de criada por Von Neuman.  
O Sistema Informático é formado basicamente por 2 componentes: o Hardware e Software.  
Hardware é a parte física do computador, isto é, os componentes e equipamentos necessário para o funcionamento do sistema informático. Os programas que comandam o hardware, damos o nome de software.

> A Arquitetura de von Neumann (de John von Neumann, pronunciado Nóimánn) é uma arquitetura de computador que se caracteriza pela possibilidade de uma máquina digital armazenar seus programas no mesmo espaço de memória que os dados, podendo assim manipular tais programas. Esta arquitetura é um projeto modelo de um computador digital de programa armazenado que utiliza uma unidade de processamento (CPU) e uma de armazenamento ("memória") para comportar, respectivamente, instruções e dados. [^1]
{: .prompt-info }

## Principais elementos

![elementos do hardware]({{site.data.images.elementos-hardware.link}})
_{{site.data.images.elementos-hardware.caption}}_

* Hardware - dispositivos físicos de entrada, processamento, memória e Saída;
* Software - comanda o Hardware, composto de Sistema Operacional e Aplicativos.

### Entrada

Na entrada ocorre a interação com o usuário e a alimentação de dados através de:

* Teclado;
* Mouse;
* DVD-Rom;
* Rede;
* Web-Cam;
* Pen-Drive.

### Processamento

O processamento é composto de uma placa onde são montados: o processador, a memória e o barramento de alimentação e de comunicação entre todos os componentes.

#### Placa mãe

![Placa mãe]({{site.data.images.placa-mae.link}})
_{{site.data.images.placa-mae.caption}}_

É uma placa principal que interliga todos os outros componentes. A motherboard ou mainboard é uma placa de circuito impresso e pode apresentar diferentes configurações dependendo da marca e do modelo. Para se poder aproveitar todos os recursos e suas potencialidades, é essencial portar o Manual da mesma, nele obtemos, por exemplo, qual(is) processador(es) podem ser instalados, os tipos de memórias, a velocidade dos barramentos, etc.

#### CPU ou Processador

![CPU]({{site.data.images.cpu.link}})
_{{site.data.images.cpu.caption}}_

Os processadores ou CPUs (Central Processing Unit) são circuitos integrados previamente
programados para realizar todas as tarefas relativas a manipulação e processamento da
informação em um computador. Através do seu uso é possível a manipulação da máquina
com dispositivos de entradas e dados em dispositivos de saída.

#### Barramento

![Barramentos]({{site.data.images.barramentos.link}})
_{{site.data.images.barramentos.caption}}_

Os barramentos ou bus, são sistemas de condutores que possibilita a comunicação e o tráfego de dados entre os componentes do sistema informático. Esse meio permite a comunicação entre processador CPU, memória principal, Slots de Expansão, etc. Podemos ter os seguintes tipos de barramentos:

* Barramento Local: é o barramento utilizado pelo processador para se comunicar com os dispositivos capitais, como memória principal e cache.
* Barramento de Dados: Esse barramento serve para transmissão de dados em duas direções em uma comunicação bidirecional full duplex.
* Barramento de Controle: Realiza o controle da comunicação de dados. Seu tráfego é simplex.
* Barramento de Endereço: Nesse barramento são enviados sinais relativos ao endereço da memória e da mesma forma do barramento de controle, utiliza comunicação simplex.
* Barramento de Expansão: é o canal por onde dispositivos de expansão são conectados, como placa de vídeo, som, rede, etc.
* Barramento de alimentação: trilhas de alimentação elétrica entre a fonte e os componentes eletrônicos.

![Chipsets]({{site.data.images.chipsets.link}})
_{{site.data.images.chipsets.caption}}_

Temos também os microcontroladores chamados de ponte norte e ponte sul, que controlam a comunicação entre os barramentos. A ponte norte que vem  integrada nos computadores modernos controla a comunicação entre o processador e a memória principal, e a ponte sul a comunicação com os periféricos.

![Chipsets]({{site.data.images.chipsets2.link}})
_{{site.data.images.chipsets2.caption}}_

### Memória

![memórias]({{site.data.images.memorias.link}})
_{{site.data.images.chipsets2.caption}}_

![HDD e SSD]({{site.data.images.hd.link}})
_{{site.data.images.hd.caption}}_

A memória é o elemento de suporte ao processamento dotado de capacidade para armazenamento de todo tipo de informação, seja eles dados simples ou programas. Computador possui basicamente dois tipos de memória: A Principal e a Secundária.

* Principal: Também conhecida como Primária ou Central, esse tipo de memória trata os dados diretamente com o processador, tornando-se indispensável para o sistema informático. Consistem em módulos ou pentes e a esses são agregados chips ou circuitos integrados que se conectam diretamente à placa-mãe.
* Secundária: é também chamada de suporte, pois sua função é armazenar informações, que se encontram na memória principal, de forma permanente. Essa informação é guardada para uso de antes ou depois de processamento. Geralmente são armazenadas em HDD, leitores de CD/DVD.

### Saída

Na saída as informações são fornecidas ou realimentão a entrada de um novo processamento. São exemplos de saídas:

* Monitor;
* Impressora;
* Pen-drive;
* Rede;
* Som.

### Software

* Software de Sistema: Função principal é servir de interface entre o usuário e o e hardware e também os softwares aplicativos e o maior exemplo dessa classe é o Sistema Operacional.
* Software de Aplicação: desempenha tarefas de aplicações do interesse do usuário, tais como editor de textos, planilhas, banco de dados.

![Componentes do computador]({{site.data.images.componentes-pc.link}})
_{{site.data.images.componentes-pc.caption}}_

## Referências

[^1]: [Arquitetura de von Neumann - Wikipédia](https://pt.wikipedia.org/wiki/Arquitetura_de_von_Neumann)

* [Apresentação sobre Sistemas Informáticos](https://drive.google.com/file/d/1bi_GMsgJ93DbNpZjLDh_vIMtlwr_vNqK/view)
* [Apostila sobre {{ site.data.references.apostilas.redes[13].name }}]({{ site.data.references.apostilas.redes[13].link }})
* [Monte seu PC - meupc.net](https://meupc.net/)
