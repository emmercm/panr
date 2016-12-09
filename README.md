# panr
A tool to create a basic Bluetooth PAN network.

## Dependencies
`panr` requires some networking utilities and [Mike Kazantsev's](https://github.com/mk-fg) [bt-pan](https://github.com/mk-fg/fgtk/blob/master/bt-pan) tool.
```bash
$ sudo apt-get install bridge-utils net-tools ipcalc udhcpd bluez
$ wget https://raw.githubusercontent.com/mk-fg/fgtk/master/bt-pan && chmod +x bt-pan
```

## Execution
```bash
$ ./panr
```

# panr-acceptr
`panr-acceptr` is a basic Python 3 script that uses `pexpect` to manipulate `bluetoothctl` to accept all Bluetooth pairing and service requests.

## Dependencies
```bash
$ sudo pip3 install pexpect
```

## Execution
```bash
$ ./panr-acceptr
```
