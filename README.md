# lilla
A Lilla é uma robô quadrúpede desenvolvida para andar de forma autônoma ou para ser controlada pelo celular. Para se locomover, ela possui 4 patas de 3 graus de liberdade cada (3 motores) e uma ESP32 que comanda o conjunto! Ela é a quarta integrante robótica do nosso espaço inteligente!

# Estrutura física
A estrutura física do robô é composta por quatro patas de três eixos cada (três motores). As patas são fixadas a uma estrutura de PLA para deixar o robô firme. As peças são todas projetadas em 3D e foram impressas utilizando PLA, podendo ser encontradas na pasta Pecas_3d deste projeto.

<img src="https://github.com/Penguin-Lab/lilla/blob/main/images/lilla0.png" height="350"> <img src="https://github.com/Penguin-Lab/lilla/blob/main/images/lilla1.png" height="350"> <img src="https://github.com/Penguin-Lab/lilla/blob/main/images/lilla4.png" height="320"> <img src="https://github.com/Penguin-Lab/lilla/blob/main/images/lilla3.png" height="320">

## Peças 3D em STL
As peças em 3D desenvolvidas para este projeto foram baseadas no projeto do robô desenvolvido por Andres ([LINK](https://gitlab.com/anflores/pavlov_mini)). Na pasta Pecas_3d, estão listadas essas peças em STL. Para ajudar, segue abaixo uma lista de todas as peças que devem ser impressas e qual o valor da sua maior dimensão (para ajudar na escolha da impressora):
* Corpo
  * 1x [LILLA_AXILA_FRONT_LEFT.STL (81 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_AXILA_FRONT_LEFT.STL)
  * 1x [LILLA_AXILA_FRONT_RIGHT.STL (81 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_AXILA_FRONT_RIGHT.STL)
  * 1x [LILLA_AXILA_BACK_LEFT.STL (81 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_AXILA_BACK_LEFT.STL)
  * 1x [LILLA_AXILA_BACK_RIGHT.STL (81 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_AXILA_BACK_RIGHT.STL)
  * 1x [LILLA_SUPPORT_LEFT_TOP.STL (127 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_SUPPORT_LEFT_TOP.STL)
  * 1x [LILLA_SUPPORT_LEFT_TOP.STL espelhado (127 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_SUPPORT_LEFT_TOP.STL)
  * 2x [LILLA_SUPPORT_FACE_BACK_UP.STL (51 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_SUPPORT_FACE_BACK_UP.STL)
  * 2x [LILLA_SUPPORT_FACE_BACK_DOWN.STL (63 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_SUPPORT_FACE_BACK_DOWN.STL)
  * 2x [LILLA_SUPPORT_FACE_BACK_DOWN.STL (63 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_SUPPORT_FACE_BACK_DOWN.STL)
  * 2x [LILLA_SUPPORT_BOTTOM.STL (99 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_SUPPORT_BOTTOM.STL)
  * 4x [LILLA_SUPPORT_PCI.STL (9 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_SUPPORT_PCI.STL)
* Patas
  * 2x [LILLA_TIBIA_LEFT.STL (128 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_TIBIA_LEFT.STL)
  * 2x [LILLA_TIBIA_LEFT.STL espelhado (128 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_TIBIA_LEFT.STL)
  * 2x [LILLA_FEMUR_LEFT_A_1.STL (134 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FEMUR_LEFT_A_1.STL)
  * 2x [LILLA_FEMUR_LEFT_A_1.STL espelhado (134 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FEMUR_LEFT_A_1.STL)
  * 4x [LILLA_FEMUR_LEFT_A_2.STL (8 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FEMUR_LEFT_A_2.STL)
  * 2x [LILLA_FEMUR_LEFT_B.STL (134 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FEMUR_LEFT_B.STL)
  * 2x [LILLA_FEMUR_LEFT_B.STL espelhado (134 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FEMUR_LEFT_B.STL)
  * 2x [LILLA_OMBRO_LEFTFRONT_BACKRIGHT.STL (66 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_OMBRO_LEFTFRONT_BACKRIGHT.STL)
  * 2x [LILLA_OMBRO_LEFTFRONT_BACKRIGHT.STL espelhado (66 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_OMBRO_LEFTFRONT_BACKRIGHT.STL)
  * 8x [LILLA_TIBIA_TUBO.STL (20 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_TIBIA_TUBO.STL)
* Rosto e bumbum
  * 1x [LILLA_FRONT_FRAME.STL (137 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FRONT_FRAME.STL)
  * 1x [LILLA_FACE.STL (137 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FACE.STL)
  * 1x [LILLA_BUMBUM.STL (137 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_BUMBUM.STL)

Obs 1: para que as patas girem sem forçar a conexão dos eixos dos motores com as peças, são utilizados dois tipos de rolamentos para cada pata: dois rolamentos [6805-2RS 25x37x7](https://pt.aliexpress.com/item/4000347743665.html?src=google&snpsid=230868174&pdp_npi=4%40dis!BRL!42.29!42.29!!!!!%4021032fb417539812201246724d5fbe!12000025424450961!ppc!!!&snps=y&src=google&albch=shopping&acnt=768-202-3196&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=_oEDJ7Ho&gclsrc=aw.ds&&albagn=888888&&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=pt4000347743665&ds_e_product_merchant_id=5551326180&ds_e_product_country=BR&ds_e_product_language=pt&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=21532694118&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=22003973025&gbraid=0AAAAAC_WlP-osBnJpLOe33NXV9Dkw2uHs&gclid=CjwKCAjwqKzEBhANEiwAeQaPVaxBBwSfUmAnXYsZFo7xcrcdahXF7pTrYmLQCVcC5jL9HLM-KAcNBRoCUIAQAvD_BwE) e um rolamentos [606-2RS 6x17x6](https://www.oliveirarolamentos.com.br/micro-rolamento-rigido-de-esferas-606-2rs-c3-6x17x6mm.html?srsltid=AfmBOorIJu8QL9XP75JwG1OypQNvwIxncIfi8yv9wJUTfwy0kq7k5aC4).
Obs 2: para o comando da tibia, o motor deverá ter em seu eixo uma [polia dentada GT2 de 36 dentes para eixo de servo e correia de 6mm](https://a.aliexpress.com/_mPVv40N), e uma [correia de 6mm com 300mm de comprimento](https://a.aliexpress.com/_mN8S5o1).
<img src="https://github.com/Penguin-Lab/lilla/blob/main/images/poliaecorreia.png" height="300">
Obs 3: os outros motores ficam fixados nas peças por [discos metálicos pequenos padrão para eixos de servo](https://a.aliexpress.com/_mPHt3nf).
<img src="https://github.com/Penguin-Lab/lilla/blob/main/images/discoeixo.png" height="300">

<img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/pata0.png" height="300"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/pata1.png" height="300"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/corpo0.png" height="300"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/corpo1.png" height="300"> ALTERAR

## Outros itens da estrutura
Alguns outros itens são necessários para finalizar a estrutura da Lilla:
* Parafusos m3 de diversos tamanhos
* 4x Tiras de EVA: colocar na ponta das peças de tibia para evitar que o robô deslize no chão


## Placa de circuito impresso
No projeto, foi desenvolvida uma placa de circuito para servir como shield para a ESP32 e conexão com a placa PCA9685 e o módulo DFPlayer Mini MP3 Player.

<img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/shield_esp_foto0.jpeg" height="500"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/shield_esp_projeto.png" height="500"> ALTERAR


## Componentes eletrônicos
Os componentes eletrônicos embarcados no robô e equipamentos utilizados são:
* Controlador com Wi-fi e Bluetooth
  * 1x ESP32 (38 pinos)
* Motores
  * 12x Servo TowerPro MG995 Metálico
* 1x Placa PCA9685 para comando dos 12 motores
* 1x Módulo DFPlayer Mini MP3 Player com cartão micro SD contendo aúdio de latidos
* 1x Alto-falante de 3W e 4Ohm para os latidos
* Chave (switch)
* Alimentação
  * Bateria Zippy LiFe 1100mAh 2s 6,6V (ESP32)
  * Bateria TM Hobbies LiFe 2100mAh 2s 6,6v (motores)

# Software
Na pasta de códigos, há um código de programação da ESP32 (38 pinos). Ele é um exemplo em C++ do comando de movimentação da Lilla:
* Dabble: a ESP32 pode se comunicar com o aplicativo Dabble no celular e receber comandos de ação.
