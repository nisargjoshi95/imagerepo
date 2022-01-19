# imagerepo
Preconfigured LXC development environments

# Usage
```bash
lxc image import <path/to/image> --alias <local/name>
```
Ex.
```bash
# from repo root
lxc image import ./containers/nodejs.tar.gz --alias devenv/nodejs/container
lxc image import ./vms/nodejs.tar.gz --alias devenv/nodejs/vm
```