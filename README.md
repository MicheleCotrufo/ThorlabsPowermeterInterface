# ThorlabsPowermeterInterface
A module to connect and collect data from a Thorlabs powermeter, based on py-visa and NI-VISA

### Installation

1. Install pyvisa (pip install pyvisa)
2. Clone the repo (or simply download the whole code) anywhere on your computer.

<!-- USAGE EXAMPLES -->
## Usage


The software automatically looks for any oscilloscope and/or powermeter connected to the computer. The devices are recognized as scopes or powermeters by looking for keywords in the string that they send after the query '*IDN?' (see code of files instruments/scope.py and instruments/powermeter.py). The dropdown lists labeled 'Device list:' in the 'Scope settings' and 'Powermeter settings' panels are populated with the corresponding devices found. Each list can be refreshed at any moment by clicking the corresponding 'Refresh' button. After a device is selected, connection can be established by clicking on 'Connect'. If connection is succesful, the corresponding 'Connect' button will turn its caption into 'Disconnect'.
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


