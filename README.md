# stm32-esp8266-AccessPointMode
 Access Point Mode esp8266 with stm32
 
 In this part, the esp8266 programmed in access point mode receives the necessary message from the esp8266 in client mode and transfers it to the buffer. Once the message arrives in the buffer, the RX interrupt is triggered, and the operations inside the ISR (Interrupt Service Routine) are initiated.

In the project, two separate esp8266 devices, programmed with stm32, are used for client mode and AP mode respectively.

The main objective of the project is to trigger an alarm for the parent in a different location when a baby cries, using a sound detection module. For this purpose, communication between two microcontrollers is established using esp8266.

YOU SHOULD REFER TO THE OTHER REPOSİTORY FOR THE CLİENT MODE!!!
