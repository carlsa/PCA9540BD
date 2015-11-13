# PCA9540BD driver for Arduino #
 
This driver has been implemented for easily manage the PCA9540BD component (http://www.nxp.com/documents/data_sheet/PCA9540B.pdf).

## About the PCA9540BD ##

The PCA9540BD is a 2-channel I2C-bus multiplexer.

Let's say that you want to get data from 2 components through I2C but they both have the same I2C address. The PCA9540BD allows you to redirect the SCA and SDA pins to (SCA0, SDA0) or (SCA1, SDA1).

## How to install this library ##

As any arduino library, simply copy this folder into the library directory of Arduino.

## How to connect the component to your arduino ##

The PCA9540BD pins have a pitch of 0.05 inches making the component difficult to connect to your arduino. As far as
I know, there doesn't exist any breakout board for this component. Some easy solutions to this problem are listed below.

### Buy a DIP8 adapter ###

The most general solution, since the PCA9540BD component has 8 pins, is to buy a DIP8 adapter. You only have to solder your component to
the DIP8 adapter, some pins headers, and you are good to go. The drawback of this method is that the order of the pins is not very
convenient, and the circuit is less clear since only pin's number are indicated.

<img src="http://sebastien.drouyer.com/images_for_projects_readme/PCA9540BD/DIP8.png" />

## About the author ##

Sebastien Drouyer - [website](http://sebastien.drouyer.com) - [twitter](https://twitter.com/sdrdis)