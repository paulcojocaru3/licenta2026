"O librărie .NET care sa se foloseasca de WASM si standarde noi de browser precum WebUSB, WebBluetooth si WebSerial pentru a implementa drivere de comunicare cu periferice comune precum cititoare de carduri, terminale bancare,  imprimante departamentale, imprimante fiscale, etc."

30.03.2025

 "periferice comune precum cititoare de carduri, terminale bancare,  imprimante departamentale, imprimante fiscale, etc."

 
Devices: 

-> Readers
  -> Magnetic Stripe Readers
    * HID / ASCII?
    * USB / Serial RS-232
  -> Chip Readers(Smart Cards)
    * CCID / APDU
    * USB / RS-232
  -> Barcode / QR code Readers
    * HID / ASCII
    * USB / RS-232 / BLUETOOTH
  -> NFC / RFID?
    * ISO 14443 NFC / ISO 15693 RFID
    * USB / SERIAL / BLUETOOTH SPP
  
-> POS
   (protocol)* APDU (Application Protocol Data Unit) / ISO 8583
   (interfata)* USB(HID / CCID->smart cards) / BLUETOOTH

-> Printers
  -> Fiscal printer
      -> coduri de bare
      -> chitante
  * ESC/POS
  * USB / BLUETOOTH / SERIAL RS-232
  -> Multifunctional( pot imprima si scana)
     * TWAIN / WIA
     * USB / WIFI (IPP) ?
  
-> Scanners
  -> QR
    * HID / ASCII
    *  USB / SERIAL RS-232 / BLUETOOTH
  -> Document scanner
    * TWAIN / WIA
    * USB / WIFI (HTTP / IPP)
  -> coduri de bare
    * HID
    * BLUETOOTH

  Resources: 
  -> ESC/POS -> protocol pentru folosirea POS-urilor -> https://escpos.readthedocs.io/en/latest/commands.html 
