# epsolar-b-series-modbus-nodejs
A simple tool for gathering data from and inputting data into the EP Solar Charge Controller devices that use the LS-B Series ModBus Register specification (seen [here](http://www.solar-elektro.cz/data/dokumenty/1733_modbus_protocol.pdf)).

Uses [node-serialport](https://github.com/EmergingTechnologyAdvisors/node-serialport).

The serial communication parameters: 115200bps baudrate, 8 data bits, 1 stop bit and no parity,no handshaking.

Will hopefully become a npm library for easy download and use (and glory).
