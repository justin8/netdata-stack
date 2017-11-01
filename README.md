# Netdata stack

This is a basic docker-compose setup that will run (Netdata)[https://github.com/firehol/netdata] in a container, on port 19999. There is a default config, but it can be modified and won't be overwritten.

## Usage

To install/update the service:

1. Make a copy of `netdata.conf.example` as `netdata.conf` in this folder and customize it
2. Run `./install`
3. Access the service on port `19999`
