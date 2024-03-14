# Bhamu
**Bhamu** is an static binary installer for Linux. It is more or less the Worst Linux ~~package manager~~ in the world.

It downloads binaries from polaco1782's [repository](https://github.com/polaco1782/linux-static-binaries) holding static binaries.
## Usage:
```sh
./bhamu BINARY_NAME ARCHITECTURE
```

Where architectures given is:
- armv8-aarch64
- x86-i686
- armv7l-eabihf

### Examples:
Install the ARM64 linux binary for git. (maybe if it exists?)
```
./bhamu git armv8-aarch64
```
Install the x86 linux binary for git.
```
./bhamu git x86-i686
```

