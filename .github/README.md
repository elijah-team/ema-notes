# Elijah ema-notes

A bunch of stuff to think about later (that I already thought about) 

Rendered: https://elijah-team.github.io/ema-notes/

Development
------------

## Running using Nix

To start the Emanote live server using Nix:

```sh
# If you using VSCode, you can also: Ctrl+Shift+B
nix run
```

To build the static website via Nix:

```sh
nix build -o ./result
# Then test it:
nix run nixpkgs#nodePackages.live-server -- ./result
```
