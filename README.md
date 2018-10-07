# spheroid
Sphero Experiments

to get bluetooth connection
* `bluetoothctl`

get the sphero-bolt number and then 
* `connect EE:6A:9A:71:EC:38`

if the prompt changes to the alias [e.g. SB-EC38] then do:
* `pair`
* `trust`

sudo rfcomm bind EE:6A:9A:71:EC:38 1

