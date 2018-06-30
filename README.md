# USB Connection Logger
This is a program that record USB device connection entries to your device.

This can be used for investigations for logging if an external threat tried/has exfilitrated data or inputed a [malicious USB device](https://hakshop.com/products/usb-rubber-ducky-deluxe).

Example Log:
```python
2018-06-30 01:49:26: "Bus 020 Device 033: ID 154b:005b" has CONNECTED 
2018-06-30 01:49:30: "Bus 020 Device 033: ID 154b:005b" has DISCONNECTED 
2018-06-30 01:49:35: "Bus 020 Device 034: ID 1050:0116" has CONNECTED 
2018-06-30 01:49:36: "Bus 020 Device 034: ID 1050:0116" has DISCONNECTED 
2018-06-30 01:49:53: "Bus 020 Device 035: ID 05e3:0610" has CONNECTED 
2018-06-30 01:49:53: "Bus 000 Device 001: ID 05e3:0616" has CONNECTED 
2018-06-30 01:49:55: "Bus 000 Device 001: ID 05e3:0616" has DISCONNECTED 
2018-06-30 01:49:55: "Bus 000 Device 002: ID 05e3:0616" has CONNECTED 
2018-06-30 01:50:06: "Bus 020 Device 036: ID 154b:005b" has CONNECTED 
2018-06-30 01:50:12: "Bus 020 Device 037: ID 1050:0116" has CONNECTED 
2018-06-30 01:50:16: "Bus 020 Device 035: ID 05e3:0610" has DISCONNECTED 
2018-06-30 01:50:16: "Bus 020 Device 036: ID 154b:005b" has DISCONNECTED 
2018-06-30 01:50:16: "Bus 000 Device 002: ID 05e3:0616" has DISCONNECTED 
2018-06-30 01:50:17: "Bus 020 Device 037: ID 1050:0116" has DISCONNECTED 
```
