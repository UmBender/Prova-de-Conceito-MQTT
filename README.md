# Prova de conceito
Aqui está o presento projeto implementado em python da prova de conceito
proposta no desavio seletivo.
Para implementação seguindo as demandas das requisições definidas
são criadas duas estâncias, uma que irá salvar em um arquivo o texto
que será recebido atráves dos post recebidos pelo client subscriber.
E outra estância irá o executar o festival.

O diagrama da arquitetura do projeto.
![alt text](./Diagrama.png)

O projeto utilizou paho-mqtt e asyncio para realização do projeto.

O projeto foi configurado via hardcode, pois se trata de uma prova de conceito.
A porta utilizada será a 1883, e os post serão no tópico test/status.
