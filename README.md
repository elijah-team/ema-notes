# ema-notes

## Running using Nix

To start the Emanote live server using Nix:

```sh
# If you're using VSCode, you can also: Ctrl+Shift+B
nix run
```

To update Emanote version in flake.nix:

```sh
nix flake lock --update-input emanote
```

To build the static website via Nix:

```sh
nix build -o ./result
# Then test it:
nix run nixpkgs#nodePackages.live-server -- ./result
```

## GitHub Pages

https://elijah-team.github.io/ema-notes
