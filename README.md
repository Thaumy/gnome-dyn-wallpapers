# GNOME dynamic wallpapers

Dynamic wallpapers for GNOME(42+)

## Available wallpapers

* mojave-dyn

## Install over Nix

1. [Enable NUR](https://github.com/nix-community/NUR#installation)

2. Edit `configuration.nix` ：

```nix
environment.systemPackages = with pkgs; [
  nur.repos.thaumy.mojave-dyn
  nur.repos.thaumy.catalina-dyn
  nur.repos.thaumy.bigsur-dyn
];
```

