# SCP/A via IP2SL
This is a simple script to communicate with Ross NK video routers via their SCP/A, connected via a GlobalCache IP2SL
This is NOT for communicating directly with NK routers

## Setup
Setup is simple, create a class instance and include an ip address.

scp = ScpViaIP2SL(ip='192.168.1.1)

Then, either call get_status or switch_output

print(scp.get_status(output=1))
scp.switch_output(input=1, output=2)
