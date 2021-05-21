# Node-red

Uso de low-code para programação  
Foi iniciado na IBM para ajudar na facilitação do Protocolo MQTT para IoT, sendo passada para a JavaScript Foundation.  
RED = Rapid Event Developer

* Low code

Ambiente de desenvolvimento usado para criar software por meio de interfaces gráficas de usuário, ao invés da programação codificada manualmente  
(Ex: UML)

* Flow programming

Programação baseada em fluxos, que permite o desenho da representação visual de como as mensagens devem fluir

## Onde o Node-red executa?

Ele pode ser executado de forma remota, na Raspberry Pi ou na Cloud

## Detalhes

* Comandos de input: possuem uma bola no lado esquerdo
* Comandos de output: possuem uma bola no lado direito
* Modificações são mostradas com uma bolinha azul
* Dois clicks nos nós para edição de suas especificações

Os flows do node-red são escritos e salvos no formato JSON
É possível criar uma função com JavaScript usando o flow Function

### Flows

* Flow 1 - utiliza só input e output
* Flow 2 - utiliza switch, function e um nó externo (email)
* Flow 3 - Utiliza o nó de http request com GET para uma API externa