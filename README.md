# NixOS packages for Binary Ninja and SCC (shellcode compiler)
Can be installed on your system using the following commands, first if your installation is not located in /opt/binaryninja then you will have to edit the package so that it points to your binary ninja installation instead, same thing for scc.
```shell
# run to install in your nix-env.
nix-env -i -f ./binaryninja.nix
nix-env -i -f ./scc.nix
```
