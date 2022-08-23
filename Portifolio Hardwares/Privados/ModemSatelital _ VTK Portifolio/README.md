## Iridium Satelite Modem

[pt_BR]Projeto para a criação de interface e protocolo para uso do módulo de comunicação satelital iridium, provendo interface RS485 para seu uso.
Projeto criar para uso juntamente com rastreador veicular VTK

[en]Project to create interface and protocol to use iridium satelite module, and provide interface RS485 to use this...
project created to work together VTK Tracker.


### Description
[pt_BR]Esquema elétrico, PCB e Firmware (C++/ARM/Arduino) desenvolvidos para inclusão no sistema de possibilidade de utilização de infraestrutura satelital fornecida pela constelação Iridium* para o envio e recebimento de dados. 
  Criado para proporcionar a possibilidade de troca de informações com o terminal em áreas cujo a cobertura 2g/Gsm é indisponível, gerando assim a possibilidade comunicação initerrupta do terminal com o servidor.

[en]Schematic, PCB and Firmware (C++/ARM/Arduino) designed for include on system the possibility to use iridium satelital constelation to send and receive data.
  Created to provide data comunication between vtk terminal and server on places without 2g/gsm coverage.

### Features / Technology
  #### HARWARE
  * DC-DC Bulk Step Down regulated 5v out, with Trasient, Switch Polarity, Over voltage and Over current protection and work in range 8~32v .
  * RS485 interface with protection external interface to a TTL internal uC comunication.
  * uC TTL Internal interface to Iridium Modem with protections, Power Supply and Control Pins.
  * Internal Buzzer Indication.
  * External Protected IO/s .
  * ISCP and DEBUG/TTL port by pins.
  * IP65 Comercial Enclousure OEM prepared.
  * uC 8Bits ARM/AVR family (ATMEGA328P-AU)
  #### PCB
  * Dual Side, Low cost PCB.
  * Fit Board to Comercial Enclousure to lower costs.
  * LowCost/High Performance Components selected to improve production time.
  #### FIRMWARE
  * Iridium module protocol implemented with IRQs and TTL send/receive data
  * RS485, internal protocol, provided to operate system of message exchange
  * Control Hardware Errors with self soft/hard reset system if necessary
  * Control memory stored mensages at confirmation of transactions, RS485->Satelite and Satelite->RS485.
  * Send Satelital Control Message to reguard data link and costs of operation.
  #### SOFTWARES
  * PROTEUS ECAD
  * VSCODE+PLATFORMIO
  * ARDUINO CORE+C++ ARM COMPILER
  * ANOTHER RELATED SOFTWARES

*Sorry for the low quality for images, it is because project need be preserved.


![Alt text](SCH%20_%20Capture.JPG?raw=true "Title")
![Alt text](PCB%20_%20BOT%20Side.JPG?raw=true "Title")
![Alt text](3D%20-%20Board%20bot%20Side.JPG?raw=true "Title")
![Alt text](IMG_0766.JPEG?raw=true "Title")
![Alt text](IMG_0765.JPEG?raw=true "Title")
