# NetScaler

## Simple NetScaler

This deploys a basic NetScaler with one NIC and multiple IP configurations. 

This is designed to use static IP addresses which you need to provide in the INTIP variable as an array. If the array contains one IP, then that is what is deployed.

If the array contains multiple IPs, then multiple IP configurations will be setup.

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fwvanbesien%2FAzureTemplates%2Fmaster%2FNetScaler%2Fnetscalervpx130.v1.json)
