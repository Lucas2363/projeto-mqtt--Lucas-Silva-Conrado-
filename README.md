# Projeto MQTT

## Objetivo

O objetivo deste projeto foi utilizar um arduino uno com um sensor magnético para monitorar se a porta de um rack de rede está **ABERTA** OU **FECHADA**; essa informação é enviada
via internet utilizando o protocolo MQTT (Message Queuing Telemetry Transport) para um servidor MQTT hospedado na Amazon Web Service (AWS) e exibir as informações do
rack em um cliente MQTT ([MQTT DASH](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=pt_BR&gl=US)) instalado em um aparelho celular. 

Segue abaixo uma represetanção do projeto:

![Alt Text](https://camo.githubusercontent.com/7beef2d4780d87a603d7de49b2da0467c8537dff96575b628a04bd4010ebb1cc/68747470733a2f2f692e696d6775722e636f6d2f4d576870586b562e706e67)

Nesse projeto foram utilizadas as seguintes bibliotecas:

* [UIPEthernet](https://github.com/UIPEthernet/UIPEthernet)
* [PubSubClient](https://github.com/knolleary/pubsubclient)

## Materiais 

* Arduino Uno
* Módulo Ethernet (ENC28J60)
* Sensor Magnético (MC-38)
* Jumpers

## Circuito

A imagem abaixo é uma representação virtual do projeto físico, onde as conexões coloridas são as conexões referentes ao Módulo Ethernet e as conexões brancas são as 
conexões do sensor magnético.

![Alt Text](https://camo.githubusercontent.com/ad1da211b35b60b23fb095a64e76dc6504d0c3229e853bd82a69a4d5d27bbb88/68747470733a2f2f692e696d6775722e636f6d2f594947477453472e706e67)

Autor: Lucas Silva Conrado

<img alt="LinkedIn" src="https://www.linkedin.com/in/lucas-silva-conrado25/"/>

