## RFID READER V2

[pt_BR]Equipamento desenvolvido para uso juntamente com Rastreadores Veiculares para idenficação do motorista atual.

[en]Equipment desinered to identify driver and send it using a Tracker


### Description
[pt_BR]Esquema elétrico, PCB e Firmware (C++/ESP8266) desenvolvido para possibilitar a identificação via RFID Mifare MFRC522 e envio de informação para rastreador veicular
  
[en]Schematic, PCB and Firmware (C++/ESP8266) Equipment use MRFC522 and to identify driver and send this information by Tracker to server.

### Features / Technology
  #### HARWARE
  * DC-DC Bulk Step Down regulated 5v out, with Trasient, Switch Polarity, Over voltage and Over current protection and work in range 8~60v .
  * RS232 interface with protection external interface to a TTL internal uC comunication.
  * SPI Internal interface to MFRC522 module with protections,Connection variations, Power Supply and Control Pins.
  * Internal Buzzer Indication.
  * External Protected Input to use by Ignition or Like OneWire Device.
  * External OutPut to relay usage, for a standalone work like a locker.
  * ISCP and DEBUG by RS232 connection.
  * Comercial Enclousure OEM prepared.
  * uC ESP8266 with Wifi and Large Memory 
  * Modular Schematic to select Components and change features
  #### PCB
  * Dual Side design, one side components for Low cost PCB and Prototype.
  * Fit Board to Comercial Enclousure to lower costs.
  * LowCost/High Performance Components selected to improve production time.
  #### FIMWARE
  * MRFC522 controller to read and write mifare cards
  * RS232 multiprotocol to use with diferent existing commercial equipment and protocols
  * Control Hardware Errors with self soft/hard reset system if necessary
  * Control internal system to standalone locker functions, white and black list of cards
  * Implement WiFi Protocol to acess socket/web to receive configurations

*Sorry for the low quality for images, it is because project need be preserved.

