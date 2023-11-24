# TinyNet_xv6

Our project hereby presents a feasible xv6-based network system scheme. We implemented a virtio-net NIC in the driver layer and a full set of client and serverside sockets. We further conducted correctness and performance evaluations.

**Report can be find at [here](https://drive.google.com/file/d/1rEj21rOMV6I2iS-aYhQe3n1r7UKgqWyu/view?usp=drive_link)**

## Running

1. Download and build up `xv6` image
2. Run `make`
3. Run `make qemu`

## Testing

- run `pingpong-server` in docker to use xv6 as server
- run `pingpong-client` in docker to use xv6 as client