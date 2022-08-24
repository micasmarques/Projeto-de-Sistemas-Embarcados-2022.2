# Sistemas Embarcados - 2022.1

#### Grupo 05 - Sistemas de automação hidroponia 2

### 1 - Descrição do projeto:

##### O presente projeto consiste na criação de um dispositivo capaz de coletar dados referentes a temperatura da água e o volume do reservatório, como também o controle da bomba de água de forma remota, a fim de se poder realizar análises no sistema instalado.

### 2 - Objetivos

##### O objetivo do projeto é coletar os dados dos sensores de temperatura da água e volume do reservatório, onde serão monitorados através de uma implementação WEB com controle da bomba e envio de status por Telegram, com capacidade de exibir dados em tempo real enquanto online, realizar a leitura, o monitoramento e o controle de dados que estão sendo recebidos.
  
### 3 - Resumo das arquiteturas

  O projeto foi composto pelos seguintes itens:
  
  ##### 1.  Hardware utilizado
  ###### 1. ESP32
  ![alt text](https://github.com/micasmarques/projeto-2022-fotos/blob/main/fotos/esp32.jpg)
  ###### 2. HX711
  ![alt text](https://github.com/micasmarques/projeto-2022-fotos/blob/main/fotos/hx711.jpg)
  ###### 3. Sensor de Peso
  ![alt text](https://github.com/micasmarques/projeto-2022-fotos/blob/main/fotos/sensor-de-peso.jpg)
  ###### 4. DS18B20
  ![alt text](https://github.com/micasmarques/projeto-2022-fotos/blob/main/fotos/sensor-de-temperatura-ds18b20-prova-d-agua.jpg)
  ###### 5. Led Liga-Desliga Vermelho
  ![alt text](https://github.com/micasmarques/projeto-2022-fotos/blob/main/fotos/led.jpg)


  ##### 2.  Software
  ###### 1. ESP-IDF 

#### Diagrama de Blocos
![alt text](https://github.com/micasmarques/projeto-2022-fotos/blob/main/fotos/diagrama-blocos.png)
  
### 4 - Resumo dos Resultados

  ##### A imagem abaixo apresenta o protótipo final do projeto, onde é possível ver em verde o sensor de temperatura DS18B20, em amarelo o sensor de peso HX711, em vermelho a célula de carga e em roxo o led, que estão posicionados dentro de uma caixa para maior segurança e melhor portabilidade. Também é possível identificar o ESP32, que controla todo o protótipo, recebendo a alimentação suportável de 3.3V que vem da porta USB (5V).
  ##### Também foi produzido dois vídeos apresentando todo o funcionamento do projeto:

  * https://youtu.be/aw8LmGfO70s
  * https://youtu.be/Qtd4zbR8mlc

  ##### Tivemos problemas em relação a calibração da célula de carga, pois após testes utilizando o multímetro, concluímos que o cristal da nossa célula de carga quebrou, e não tivemos tempo hábil para realizar sua calibração, uma vez que foi necessário encomendar de João Pessoa uma nova célula. Também tivemos dificuldade em programar o projeto para enviar mensagens para o Telegram, mostrando a situação atual de todo o protótipo.

  ![alt text](https://github.com/micasmarques/projeto-2022-fotos/blob/main/fotos/projeto-final.jpg)
 

### 5 - Grupo

* Kilvia da Silva Carvalho
* Micael Marques Rodrigues Silva
* Pâmela Victoria Soares Lima

### 7 - Instituição

* Instituto Federal da Paraíba - IFPB
* Campus Campina Grande

### Docente responsável
* Alexandre Sales Vasconcelos