# Pocket Kit Arduino - 8. Piscando um LED
# piscando_um_led

A constante LED_BUILTIN aponta para o pino digital 13 que por padrão vem ligada ao led físico do arduino UNO. 
Por isso com esse Sketch podemos observar o led da protoboard piscar junto com o led que vem na placa do arduino. 
Uma curiosidade: os arduinos UNOS vem de fábrica carregados com esse Sketch para você apenas energizá-los e saber que estão ok.

- Piscando um LED com Arduino
- Vídeo -> https://www.youtube.com/shorts/1oOgQ5glc-E

![image](https://github.com/jorgeluige/piscando_um_led/assets/37905961/f66d99e3-feb0-4fbb-ab03-66e2543dbfcd)







# APRENDA ARDUINO COM UM KIT QUE CABE NO SEU BOLSO!
O Pocket Kit para Arduino da RoboCore é um kit com mais de 80 componentes, perfeito para você que quer começar com um ótimo custo x benefício. Este é um kit simples, porém completo, com os principais componentes que você precisa ter para começar seu aprendizado com Arduino e fazer diversos experimentos.

Como os demais kits da RoboCore, este kit é fabricado no Brasil e possui manual online exclusivo para aprendizado! Isso mesmo, este kit também possui uma série de tutoriais exclusivos, com os quais você aprenderá conceitos, como uso de pinos digitais de entrada ou saída, uso de entradas analógicas, comunicação serial com o computador, leitura de sensores e muito mais!

![image](https://github.com/user-attachments/assets/9afec2a1-a0c4-4b33-a741-73dfc2f319fc)

- https://www.robocore.net/


´´´
void setup() {
  // Inicializar o pino digital LED_BUILTIN como uma saída.
  pinMode(LED_BUILTIN, OUTPUT);
}

// Funcao looping 
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // Liga o LED 
  delay(1000);                       // espera um segundo
  digitalWrite(LED_BUILTIN, LOW);    // Desliga o LED
  delay(1000);                       // espera um segundo
}
´´´
