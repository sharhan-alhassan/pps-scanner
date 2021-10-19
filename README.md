# Portable Port Scanner (ppscanner)
Portable Port Scanner (ppscanner) is a light-weight open-source CLI utility that leverages on `nmap` to make quick and elegant scanning of host devices and their ports to better insights, troubleshooting, check vulnerabilites and meet compliance requirements of networks.

### Installation Guide 

### Global dependencis
- ppscanner leverages on `nmap` functionalities so you need it installed to be able use it.

```bash
$ sudo apt-get install nmap
```

### Project Dependencies
```bash
$ sudo pip install -i https://test.pypi.org/simple/ ppscanner

```

## Run Commands
- Example code
```bash
$ ppscan scan --host 127.0.0.1 --port 80
```

## Help commands
```bash
$ ppscan scan --help
```
