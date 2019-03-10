![Logo](admin/sma.png)
# ioBroker.sma-speedwire
![Number of Installations](http://iobroker.live/badges/sma-speedwire-installed.svg) ![Number of Installations](http://iobroker.live/badges/sma-speedwire-stable.svg) =================

This is a adapter for iobroker that can communicate with SMA inverters using the speedwire interface, which is IP based, so you need an IP connection to your device

## Steps 
1. To install this adapter
* got to the Adapter configuration
* select 'install from custom URL', and there select custom
* add URL 'https://github.com/AttackStrawbery/ioBroker.sma-speedwire'

2. Configure the adapter
* IP address
* User
* Password

## Requirements
* SMA Inverter with an IP connection   

## Changelog

### 0.7.0
* Rework of state creation, now dynamic
* Added values for role and unit to the states
* First version to add the translation/explanation for the collected values
* Support for the admin 3 interface

### 0.0.1
* initial release

## License
The MIT License (MIT)

Copyright (c) 2017 Thomas Hepper <thomasAThepperDOTeu>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.