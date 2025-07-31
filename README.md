# lilla
A Lilla é uma robô quadrúpede desenvolvida para andar de forma autônoma ou para ser controlada pelo celular. Para se locomover, ela possui 4 patas de 3 graus de liberdade cada (3 motores) e uma ESP32 que comanda o conjunto! Ela é a quarta integrante robótica do nosso espaço inteligente!

# Estrutura física
A estrutura física do robô é composta por quatro patas de três eixos cada (três motores). As patas são fixadas a uma estrutura de PLA para deixar o robô firme. As peças são todas projetadas em 3D e foram impressas utilizando PLA, podendo ser encontradas na pasta Pecas_3d deste projeto.

<img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/tiffany0.jpeg" height="250"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/tiffany3.jpeg" height="250"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/tiffany2.jpeg" width="350"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/tiffany1.jpeg" width="350">

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
  * 1x [LILLA_FRONT_FRAME.STL (128 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FRONT_FRAME.STL)
  * 1x [LILLA_FACE.STL (128 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_FACE.STL)
  * 1x [LILLA_BUMBUM.STL (134 mm)](https://github.com/Penguin-Lab/lilla/blob/main/Pecas_3d/LILLA_BUMBUM.STL)
* Motor
  * 12x [TIFFANY_TAMPA_MOTOR.STL (41 mm)](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_TAMPA_MOTOR.STL)

Obs: a tampa de 12 motores deverão ser trocadas pelas peças [TIFFANY_TAMPA_MOTOR.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_TAMPA_MOTOR.STL) para que seja possível fixar os rolamentos nas patas. Serão utilizados 3 rolamentos por pata:

<img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/pata0.png" height="300"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/pata1.png" height="300"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/corpo0.png" height="300"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/corpo1.png" height="300">

## Outros itens da estrutura
Alguns outros itens são necessários para finalizar a estrutura da Tiffany:
* 6x Parafusos m4 ou similar de cm: prender as peças [TIFFANY_BODY_UP.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_BODY_UP.STL) e [TIFFANY_BODY_DOWN.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_BODY_DOWN.STL)
* 24x Parafusos m4 de cm: prender as peças [TIFFANY_OMBRO_DOWN_LEFT.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_OMBRO_DOWN_LEFT.STL) e [TIFFANY_OMBRO_UP.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_OMBRO_UP.STL)
* 24x Parafusos m3 de cm: prender as peças [TIFFANY_TIBIA_LEFT.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_TIBIA_LEFT.STL) nos motores
* 6x Tiras de EVA: colocar na ponta das peças [TIFFANY_FOOT.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_FOOT.STL) para evitar que o robô deslize
* Arruelas entre as peças [TIFFANY_SPACER.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_SPACER.STL) e [TIFFANY_BODY_UP.STL](https://github.com/Penguin-Lab/tiffany/blob/main/Pecas_3d/TIFFANY_BODY_UP.STL) para ajustar a altura correta do interior do robô

## Placa de circuito impresso
No projeto, foi desenvolvida uma placa de circuito para servir como shield para a ESP32 e conexão com as duas placas PCA9685.

<img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/shield_esp_foto0.jpeg" height="500"> <img src="https://github.com/Penguin-Lab/tiffany/blob/main/images/shield_esp_projeto.png" height="500">


## Componentes eletrônicos
Os componentes eletrônicos embarcados no robô e equipamentos utilizados são:
* Controlador com Wi-fi e Bluetooth
  * 1x ESP32 (38 pinos)
* Motores
  * 18x Servo TowerPro MG995 Metálico
* 2x Placas PCA9685 para comando dos 18 motores
* Chave (switch)
* Alimentação
  * Bateria Zippy LiFe 1100mAh 2s 6,6V (ESP32)
  * Bateria TM Hobbies LiFe 2100mAh 2s 6,6v (motores)

# Software
Na pasta de códigos, há dois códigos de programação da ESP32 (38 pinos). Eles são exemplos em C++ do comando de movimentação da Tiffany:
* Dabble: a ESP32 pode se comunicar com o aplicativo Dabble no celular e receber comandos de ação;
* Espaço Inteligente (IS): a ESP32 pode se comunicar com o Espaço Inteligente e receber esses mesmos comandos.
