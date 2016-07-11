# PHP Resources for a Raspberry Pi

A list of resources for PHP programming on a Raspberry Pi

## GPIO Libraries

All of these libraries support reading and writing values to the GPIO pins.

- **[PiPHP: GPIO](https://github.com/PiPHP/GPIO)**

> Supports registering callbacks for interrupt handling.

- **[php-gpio](https://github.com/ronanguilloux/php-gpio)**

> No support for interrupt handling, but does have support for a couple of devices (MCP3002 analog-to-digital converter, DS18B20 one wire temperature sensor).

- **[phpi](https://github.com/calcinai/phpi/tree/master/src/PHPi)**

> Supports registering callbacks for interrupt handling. Uses React PHP and is event driven. Supports a range of MCP300X analog to digital converters.

## Other Libraries

- **[raspicam-php](https://github.com/cvuorinen/raspicam-php)**

> Library for controlling the Raspberry Pi camera module (raspicam). Supports still images and has a timelapse method. Uses a fluid interface.

- **[raspberry-piface-api](https://github.com/peec/raspberry-piface-api)**

> Library for controlling the PiFace module. This is a port of the [original python library](https://github.com/piface/pifacedigitalio) and requires the PHP SPI extension.



## Tutorials

- **[Powering Raspberry Pi Projects with PHP](https://www.sitepoint.com/powering-raspberry-pi-projects-with-php/)**

> SitePoint tutorial showing how to use **[PiPHP: GPIO](https://github.com/PiPHP/GPIO)** to blink an LED a few times after detecting a push button interrupt.

- **[Install PHP7 on a Raspberry Pi](https://www.stewright.me/2016/03/turn-raspberry-pi-3-php-7-powered-web-server/)**
