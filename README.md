# PKGBUILD for the linux-zen-hardened Kernel #
The linux-zen-hardened kernel is a merging of the linux-zen and linux-hardened patchsets.
- The upstream zen sources are: [zen-kernel](https://github.com/zen-kernel/zen-kernel) 
- The upstream hardened sources are: [linux-hardened](https://github.com/anthraxx/linux-hardened).
- The upstream repository that the PKGBUILD pulls from is [here](https://github.com/awcurless/zen-kernel).

## Kernel Configuration ##
Before installing, double check the config file to ensure the kernel options fit 
your use case. If you need to, modify the file and update the checksum in the PKGBUILD. The `updpkgsums` tool is useful for this.
