## NixOS Iso for T2 Macs

You can use this flake to build a NixOS iso that can be used with T2 Macs.

This repo provides two isos:
* `t2-iso-minimal`
* `t2-iso-gnome`

It is reccommended to use `t2-iso-minimal` for installing NixOS. `t2-iso-gnome` can be used to preview what the system will look after the installation.

You can build with this command:
```
nix build .#t2-iso-minimal
```

You need to have `nix` installed on a **Linux** host. If you are on macOS, you can use `podman` or `docker` with the `nixos/nix` image.