
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

`$ ./trace-gw`
- if more than one argument than prints relative path to last argument.

`$ ./rpath file.txt ../file2.txt /etc/passwd /etc/apache2`
