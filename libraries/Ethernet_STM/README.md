Description
---

That library is for W5100 ethernet modules/shields and has been ported to work with STM32 micro-controllers.

 =========================================================
 Ported to STM32F103 on 16 Jun 2015 by Vassilis Serasidis
 
 <---- Pinout ---->
 W5100 <--> STM32F103
 SS    <-->  PA4 <-->  BOARD_SPI1_NSS_PIN
 SCK   <-->  PA5 <-->  BOARD_SPI1_SCK_PIN
 MISO  <-->  PA6 <-->  BOARD_SPI1_MISO_PIN
 MOSI  <-->  PA7 <-->  BOARD_SPI1_MOSI_PIN
 =========================================================

http://www.serasidis.gr/images/w5100_shield.jpg
