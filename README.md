
# network-scripts
Help to messure network activities

# Setup
`$ chmod +x tcp-stat`

`$ chmod +x trace-gw`

you may add these in your path variable via your **~/.bash_profile** file (you should have nmap installed in case of macOS)

## Usage of tcp-stat
- prints count of TCP connection Statistics.

`$ ./tcp-stat`

`ESTABLISHED 60`

`LISTEN      16`

`CLOSED      1`


## Usage of trace-gw
- Check if you have a gateway that could get you somewhere nice.

`$ ./trace-gw 8.8.4.4`

[info] Trying ARP entries to reach 8.8.4.4...

[success] Could reach 8.8.4.4 via xx:xx:xx:xx:xx:xx (10.0.0.11) at eth0

[success] Could reach 8.8.4.4 via xx:xx:xx:xx:xx:xx (10.0.0.20) at eth0

[info] Done!