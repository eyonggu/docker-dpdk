# docker-dpdk


Build mainstream version (see [`settings.sh`](settings.sh)):

```bash
./build.sh
```

You can specify DPDK version and/or Ubuntu version to build non-mainstream image:

```bash
DPDK_VERSION=18.11.11 UBUNTU_VERSION=18.04 ./build.sh
```

---------------------------------

Change Notes
- updated default DPDK UBUNTU versions
- Updated docker image tag to my docker hub
- Added "--break-system-packages" to pip3 (see https://veronneau.org/python-311-pip-and-breaking-system-packages.html)

