# shut

A minimal CLI tool to list open ports and associated processes.

## Usage

By default, displays open IPv4 TCP ports, to adjust:

```shell
USAGE:
    ports [OPTIONS]

OPTIONS:
    -h, --help       Print help information
        --ipv6       display IPv6 addresses with open ports
    -m, --mine       show only ports opened by myself
        --udp        display UDP ports
    -V, --version    Print version information
```

# Alternatives

Linux:

```shell
ss -tulpn
```
