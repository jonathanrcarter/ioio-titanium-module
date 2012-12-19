ioio-titanium-module
====================

google ioio titanium module


### Usage
Include by using the code

var ioio = require('com.glimworm.app.module.ioio');

then to control a digital port use

ioio.relay(1,true) - port 1 on
ioio.relay(1,false) - port 1 off

### Issues
It currently only supports ports 0,1,2,3 but I will add more later.  This is only because we ran out of time.

It does not seem to work with Bluetooth at the moment also.  We will also try to fix this
