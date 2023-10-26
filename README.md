<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/logo.jpeg" width="300" alt="TempShield Logo">
</p>

# TempShield  
>  *Um protótipo para monitoriamento de refrigereção de vacinas baseado na internet das coisas*

<h3 aling="right" <a name="features"></a> 
     O que é? 
</h3>

<p>
  É um protótipo de monitoramento de temperatura que utiliza sensores para acompanhar a temperatura dos refrigeradores de vacinas. Ele é alimentado por baterias recarregáveis, o que o torna independente da eletricidade comum. Os dados coletados são armazenados em uma plataforma de nuvem IoT e podem ser usados para enviar notificações aos responsáveis caso a temperatura saia dos limites corretos.
</p>
<hr>
<h3 aling="right" <a name="features"></a> 
     Motivação
</h3>

<p>
  A ideia de criar o protótipo surgiu a partir da leitura de uma notícia no G1 que relatava que mais de 6.000 vacinas contra a COVID-19 perderam sua eficácia após o roubo da fiação de uma UBS no Espírito Santo. Percebemos que se houvesse um monitoramento da temperatura do refrigerador e ele notificasse os responsáveis, seria uma forma de prevenir que esse tipo de ação ocorresse. Para saber mais acesse: https://g1.globo.com/sp/santos-regiao/mais-saude/noticia/mais-de-500-vacinas-estragam-por-falta-de-refrigeracao-apos-furto-em-guaruja-sp.ghtml.
</p>
<hr>
<h3 aling="right" <a name="requisito"></a>
  🛠 Funcionamento 
</h3>

- Utiliza a placa NodeMCU ESP8266 para capturar e processar dados de temperatura. [Uma placa de desenvolvimento baseada no microcontrolador ESP8266,que possui conectividade Wi-Fi integrada.]
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/nodemcu.jpeg" width="300" alt="TempShield Logo">
</p>
  
- Garante autonomia com baterias recarregáveis do tipo "powerbank".
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/power.jpeg" width="300" alt="TempShield Logo">
</p>

- Mede a temperatura das vacinas com um termopar tipo K e amplificador MAX6675. [é um excelente dispositivo capaz de fazer medições de temperaturas entre 0 a incríveis 800°C.]
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/max6675.jpeg" width="300" alt="TempShield Logo">
</p>

- Exibe a temperatura em um visor LCD 16x2 em graus Celsius.
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/lcd.jpeg" width="300" alt="TempShield Logo">
</p>
  
- Armazena dados na nuvem Thingspeak e os compartilha no Twitter, além de enviar e-mails via Gmail.
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/twwiter.jpeg" width="300" alt="TempShield Logo">
</p>
<br>
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/gmail..jpeg" width="300" alt="TempShield Logo">
</p>

- Um aplicativo Android emite notificações com base nos dados da nuvem.
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/app.jpeg" width="300" alt="TempShield Logo">
</p>

<hr>
<h3 aling="right" <a name="requisito"></a>
  Video
</h3>
<p>
  Assista o video para ver o funcionamento do prototipo: https://www.youtube.com/embed/r7NbZOBGJZ4?si=3Bu-wZ3MjwRPBZsM 
</p>

