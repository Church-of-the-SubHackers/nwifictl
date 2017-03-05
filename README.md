# nwifictl
A simple wifi connection tool

This tool is used for connecting to open or password-protected networks with an option to spoof your MAC address or set a custom WPA configuration file. This makes it easy to connect to an AP with custom interface settings without having to deal with the NetworkManager mess.

# Usage
    nwifictl -e <essid> -i <iface> [options]
    [options]:
	-p|-psk [PSK]		Specify the password
	-s|-spoof [ADDR]	Spoof interface MAC address
	-c|-config [CONFIG]	Specify a custom wpa_supplicant config
	-help			Prints this help text

