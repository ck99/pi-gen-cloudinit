# pi-gen-cloudinit

_Tool used to create cloud-init ready Raspbian images_


## Main Documentation

This is a fork of pi-gen, with custom build stages. See the pi-gen docs for almost everything.

## Customisations

The target here is to create a cloud-init ready, but minimal apart from that, Raspbian image. This is achieved 
using custom build stages to configure cloud-init: see [here](https://gist.githubusercontent.com/RichardBronosky/fa7d4db13bab3fbb8d9e0fff7ea88aa2/raw/cloud-init-setup.sh)
for details of that.