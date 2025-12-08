[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/bQrFkq0H)

# Jardim Inteligente

## Andamento do projeto
- **Antes da aula do dia 25/11:** Estrutura de ligações dos modulos ao protoboard e Arduino; Implementação do código de controle do visor LCD e inicio do controle da bomba de água.
- **Aula do dia 25/11:** Pesquisa e tentativa de implementar a comunicação do arduino com um módulo wifi.
- **Aula do dia 26/11:** Conseguimos implementar a comunicação do arduino com o módulo wifi e estabelecemos um código que gera um servidor web em resposta. O site ainda esta sendo implmenetado. Tudo isso acarretou na mudança o placa utilizada de um arduino UNO para um arduino Mega.
- **Semana 01/12 a 05/12:** Criação do esquemático no Fritzing; Criação do site que será usado para ver informações e controlar a aplicação;


## Contextualização

### Motivação

## Aplicações

## Lista de Materiais
| Nome               | Imagem             |
| ------------------ | ------------------ |
| Arduino Mega 2560  | <img src="https://vidadesilicio.com.br/wp-content/uploads/2021/09/1901-jpg.webp" alt="Foto arduino mega 2560" width="300px"> |
| Sensor de umidade do solo HW-080 | <img src="https://curtocircuito.com.br/media/catalog/product/cache/31a7b9a8d1a38183c94fb2deca9ba15c/_/s/_s_e_sensor_umidade_do_solo_1.jpg" alt="Foto sensor de umidade HW-080" width="300px"> |
| Visor Grove-LCD RGB Backlight | <img src="https://seeeddoc.github.io/Grove-LCD_RGB_Backlight/img/Serial_LEC_RGB_Backlight_Lcd.jpg" alt="Foto visor Grove-LCD RGB Backlight" width="300px"> |
| Modulo Wifi ESP8266 | <img src="https://images.tcdn.com.br/img/img_prod/672486/modulo_wifi_esp01_esp8266_43_1_d8e1fc79a4a87d5429704b3788615b70_20241128103856.jpg" alt="Foto Módulo Wifi ESP-01" width="300px"> |
| Adaptador ESP-01 | <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwWG1IF6Woep4x9cUgK93tCzz57YrjBdrpzw&s" alt="Foto adaptador para ESP8266" width="300px">
| Bomba de água submersível | <img src="https://http2.mlstatic.com/D_NQ_NP_764687-MLB77866730739_072024-O.webp" alt="Foto bomba de água submersível" width="300px"> |
| Fonte externa a base de pilhas | <img src="" alt="Foto fonte externa 4 pilhas" width="300px"> |
| Botões | <img src="https://guiarobotica.com/wp-content/uploads/2020/04/Push-Button-Arduino-e1586870732801.jpg.webp" alt="Foto botão" width="300px"> |
| Relé 1 canal JQC3F-05VDC-C 5V | <img src="https://images.tcdn.com.br/img/img_prod/648216/modulo_rele_arduino_1_canal_5v_10a_jqc3f_05vdc_c_152044_1_5073a7355c9187c39427fd090a2fb630.jpg" alt="Foto Relé JQC3F-05VDC-C 5V" width="300px"> |
| Jumpers macho-macho | |
| Jumpers macho-fêmea | |

## Bibliotecas usadas
- **rgb_lcd.h:** Biblioteca usada para controlar o visor Grove-LCD RBG Backlight.
- **Wire.h:** (precisa?)

## Diagrama de montagem
<img src="https://github.com/Computacao-Fisica-UFSJ/projeto-final-AlmadaLuiz14/blob/main/EsquemaFritzing/tpFinal_bb.png" alt="Imagem do diagrama de montagem">
Esse projeto foi montado usando um conjunto de componentes e conexões. Falaremos sobre cada conjunto de módulos para priorizar a organização e o entendimento.
- **Protoboard:** O protoboard aqui serve, pricipalmente como distribuidor de energia já que recebe a alimentação das portas 5V e GND do arduino e todos os outros componentes pegam energia de um de seus pontos. Além disso, há também dois botões que se comunicam com o arduino através de uma comunicação com as portas digitais 8 e 10.
- **Visor LCD:** O visor Grove-LCD RGB Backlight, além das ligações de alimentação com o protoboard, possui seus pino SDA e SCL ligados ao arduino nessas respectivas entradas (portas 20 e 21, respectivamente, do arduino Mega 2560)..
- **ESP:** O módulo wifi ESP8266 está conectado ao adaptador ESP-01 que, por sua vez, está conectado ao protoboard para energia e às portas digitais 3 e 4 do arduino (ligadas, respectivamente, ao RX e TX do ESP-01).
- **Relé e bomba d'água:** O Relé JQC3F-05VDC-C 5V possui duas partes d.d9 conexão:


## Foto do projeto

## Vídeo de funcionamento

## Problemas encontrados

## Referências usadas
