# Windows_WFP_IPv6_Inbound_Outbound_Traffic_Process
Windows WFP baseline: IPv6 Inbound and Outbound Traffic Process, same as Linux Netfilter hooks.

.

## Demo 1: Init, Register callout & filter, Capture IPv6 inbound packets

![https://raw.githubusercontent.com/MaoJianwei/Windows_WFP_IPv6_Inbound_Outbound_Traffic_Process/master/screenshots/init-register-callout-filter---capture-packets.png](https://raw.githubusercontent.com/MaoJianwei/Windows_WFP_IPv6_Inbound_Outbound_Traffic_Process/master/screenshots/init-register-callout-filter---capture-packets.png)

.

## Demo 2: Unregister callout & filter

![https://raw.githubusercontent.com/MaoJianwei/Windows_WFP_IPv6_Inbound_Outbound_Traffic_Process/master/screenshots/unregister.png](https://raw.githubusercontent.com/MaoJianwei/Windows_WFP_IPv6_Inbound_Outbound_Traffic_Process/master/screenshots/unregister.png)

.

## Demo 3: Capture packets at the Inbound and Outbound paths

![https://raw.githubusercontent.com/MaoJianwei/Windows_WFP_IPv6_Inbound_Outbound_Traffic_Process/master/screenshots/inbound-outbound-all-ready.png](https://raw.githubusercontent.com/MaoJianwei/Windows_WFP_IPv6_Inbound_Outbound_Traffic_Process/master/screenshots/inbound-outbound-all-ready.png)

.

## Debug via Network:

create a soft symlink:

"C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\windbg.exe" -k net:port=50520,key=HBCHM3CO4ACY.VHLDUEMESHXF.9PRHGXXO9DF.I9MYY1CRQHBB
