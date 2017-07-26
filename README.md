# Deathstar

Setup & configs for my home server

### Specs

- Intel Core i3 6100
- MSI H100M PRO-D
- 16GB DDR4
- 240GB SSD for OS and Docker
- Debian 9.1

### Install

I've mostly used the [perfect media server post](https://www.linuxserver.io/2017/06/24/the-perfect-media-server-2017/) to set the server up.

Because the R8169 driver isn't open source, Debian doesn't have it built in. To install it:

- Edit the `/etc/apt/sources.list` file to add `non-free` to the main repo.
- `apt update && apt install r8168-dkms`

This will rebuild the kernel plus it will be included with any further kernel updates

### Uses

- Store my files
- Plex
- GitLab
- Sonarr
- more to come...
