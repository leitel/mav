**MAV**

Em resposta aos problemas de segurança, a universidade começou monitorar o acesso de alguns veículos ao campus. O presente trabalho tem como objetivo verificar horário de entrada e saída de veículos e saber quais estão circulando no campus, de maneira automatizada e rápida. O sistema foi pensado para utilização no campus do Pici - UFC, mas pode, com poucas adaptações, ser utilizado em qualquer estacionamento que tenha controle de acesso, como os de empresas.

**O sistema possui dois modos de funcionamento:**

  Para um veículo de indivíduo com vínculo ao campus: O indivíduo deve ter uma Tag RFID. Ao chegar ao campus, o leitor RFID irá identificar a Tag, a cancela abrirá, a raspberry irá salvar no servidor horário de entrada do veículo.

  Para um veículo de indivíduo sem vínculo ao campus: O indivíduo, ao parar na frente da cancela, será notado através dos sensores ultrassônicos. Uma vez que é identificado que existe um veículo na entrada, a câmera é ativada, captura uma imagem e a cancela é liberada. A imagem capturada é enviada para o servidor.
