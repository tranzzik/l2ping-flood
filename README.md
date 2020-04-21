# L2PING flood attack

This repo contains a simple script to run `l2ping` on a bunch of processes to try and flood a device.

# Example
To run this rudimentary l2ping flood attack on a device with MAC address FC:58:FA:83:FA:2D on 150 processes, type this command:
```
$ python l2ping-flood.py FC:58:FA:83:FA:2D -p 150
```

# Usage

To view usage, run `python l2ping-flood.py -h`:

```
usage: l2ping-flood.py [-h] [-p PROCESSES] mac

positional arguments:
  mac                   MAC address of device to smash

optional arguments:
  -h, --help            show this help message and exit
  -p PROCESSES, --processes PROCESSES
                        Number of process to run l2ping on. Default is 100
```