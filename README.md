<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/logo.jpeg" width="300" alt="TempShield Logo">
</p>

# TempShield  
>  *Um protótipo para monitoriamento de refrigereção de vacinas baseado na internet das coisas*

<h3 aling="right" <a name="features"></a> 
     O que é? 
</h3>

<p>
  O protótipo de monitoramento de temperatura das vacinas utiliza sensores para acompanhar a temperatura das vacinas e é alimentado por baterias recarregáveis, o que o torna independente da eletricidade comum. Os dados   
  coletados são armazenados em uma plataforma de nuvem IoT, e um aplicativo especial pode enviar notificações aos responsáveis se a temperatura sair dos limites corretos. Isso garante que as vacinas estejam sempre na 
  temperatura certa, mesmo se houver problemas de energia.
</p>

<h3 aling="right" <a name="requisito"></a>
  🛠 Funcionamento 
</h3>

- Utiliza a placa NodeMCU ESP8266 para capturar e processar dados de temperatura. [Uma placa de desenvolvimento baseada no microcontrolador ESP8266,que possui conectividade Wi-Fi integrada.]
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/nodemcu.jpeg" width="300" alt="TempShield Logo">
</p>
  
- Garante autonomia com baterias recarregáveis do tipo "powerbank".
- Mede a temperatura das vacinas com um termopar tipo K e amplificador MAX6675. [é um excelente dispositivo capaz de fazer medições de temperaturas entre 0 a incríveis 800°C. juntamente ao Termopar Tipo K, interagindo e os valores obtidos junto a microcontroladores]
<p align="center">
  <img src="https://github.com/dayanenubia/TempShield/blob/main/assets/max6675.jpeg" width="300" alt="TempShield Logo">
</p>

- Exibe a temperatura em um visor LCD 16x2 em graus Celsius.
- Armazena dados na nuvem Thingspeak e os compartilha no Twitter, além de enviar e-mails via Gmail.
- Um aplicativo Android emite notificações com base nos dados da nuvem.
