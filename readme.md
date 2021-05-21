# Node-red e internet das coisas

(**anotações feitas do curso de Node-red dado pela Universidade Católica de Pernambuco**)

## Introdução ao curso

### Programação Visual

Programação construida de forma visual, com ajuda gráfica para o desenvolvimento do projeto.  
Node-red utiliza a programação visual, pois ela é muito útil para Internet das Coisas (IoT)

### Objetos inteligentes e Cultura *maker*

maker - ***do it youtself***

## Internet das Coisas

Mark Weiser -> "*as tecnologias mais profundas são aquelas que desaparecem. Elas tecem-se no tecido da vida cotidiana até que sejam indistinguíveis dele.*"  
A visão do passado do futuro já previa questões do futuro, assim como a Internet das Coisas  
**Computação ubiqua**: a computação está em todos os lugares, em eletrodomésticos, em roupas, etc.  
Kevin Ashton -> primeira pessoa a falar do termo "Internet of Things"  

### 1ª Onda da IoT

Criação dos ***RFID*** (Radio Frequency Identification), métodos de identificação automáticas que podiam guardar dados e serem lidos por outros aparelhos como celulares.

### 2ª Onda da IoT

Onda atual, com objetos conectados pela internet. Possui uma tendência de crescimento alta no futuro.  
Questão: número IP não esperavam o crescimento do IoT. ( IPv4 -> IPv6 )

### Como definir IoT?

A IoT é guiada por três fatores:

* Sensores e Atuadores: sensores de diversos tipos, como elétricos, ópticos, etc  
Hoje em dia, os celulares e outros computadores possuem cada vez mais sensores para várias coisas diferentes.  
* Conectividade: comunicação entre dispositivos  
Várias tecnologias de conectividade: Wi-fi, 3g, 4g, GPS, etc.  
* Pessoas e Processos: pensar a tecnologia no contexto onde ela vai ser aplicada, focado nos problemas das pessoas

## Plataformas de IoT

### Arduino

Placa com microcontrolador, sendo um computador simples que roda um programa com vez e é utilizado para atividades repetitivas e pouco numerosas  
A programação é feita em ambiente específico no computador. Ele é conectado com um cabo e utiliza um subconjunto de **Programação C**.

### Raspberry pi

Placa com microprocessador, incluindo wi-fi, hdmi, etc. É um computador de uso geral, que permite rodar vários programas de uma vez e é usada para tarefas mais complexas.  
Possui um sistema operacional, normalmente **Linux**, permite a escrita diretamente nela, utilizando mais linguagens, como Python, JavaScript, C, C++, Java, etc, e ambientes como Scratch e Node-RED, de forma mais amigável.

## Para utilização

Antes de tudo: instalar node.js e node-red

para instalar:

```console
 npm install -g --unsafe-perm node-red
```

Para rodar:

```console
node-red
```
