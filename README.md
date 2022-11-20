# Crypto-E-Ink
Nice little crypto tracker created out of ESP8266 + Seedstudio's Triple Color E-Ink Display 2.13".  

<img src="https://github.com/toto99303/Crypto-E-Ink/blob/main/Pictures/Crypto-e-ink.png" width=30%>

I had to de-solder the STM32 chip from the e-ink board in order to use the native SPI interface of the display.  
Otherwise it's useless...  
Then just tap into the proper solder points and connect to the ESP dev board:  



I used "Lolin new NodeMCU v3" and these pins:  

BUSY -> D2  
RST -> D4  
DC -> D3  
CS -> D8  
CLK -> D5  
DIN -> D7  
GND -> GND  
3.3V -> 3.3V  




