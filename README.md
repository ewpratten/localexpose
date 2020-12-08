# localexpose
A small shell script for exposing a remote TCP port as a local port. I built this to help me forward a printer from my home network to devices on my VPN (so I can print from school, for example)

## Usage

This tool requires `socat` to be installed. Assuming you have `socat`, just run:

```sh
bash ./localexpose [server_addr] [port]
```
