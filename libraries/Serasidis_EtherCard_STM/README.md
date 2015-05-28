# EtherCard

**EtherCard** is a driver for the ENC28J60 chip, compatible with Arduino IDE 1.6.3 (or later).  
Adapted and extended from code written by Guido Socher and Pascal Stang.

License: GPL2

The documentation for this library is at http://jeelabs.net/pub/docs/ethercard/.

## Physical Installation

### PIN Connections (Using STM32F103):

    VCC -   3.3V
    GND -    GND
    SCK - Pin PA5
    SO  - Pin PA6
    SI  - Pin PA7
    CS  - Pin PA8 # Selectable with the ether.begin() function
    RST -   3.3V

## Credits

The **EtherCard** library was written by [Jean-Claude Wippler][F] and ported to **STM32F103** by [Vassilis Serasidis][V] 

## Support

That library works perfect on Arduino IDE 1.6.3 (or later) with [Arduino_STM32 project][S] installed.

The Arduino STM32 project has a forum ([STM32duino][F]) also for getting or for providing help to people that are interested in that project .

[F]: https://github.com/jcw
[S]: https://github.com/rogerclarkmelbourne/Arduino_STM32
[F]: http://www.stm32duino.com
[V]: https://github.com/Serasidis
