# rpi-nix-config

# Setup
install nix

# home manager
- [reference-doc](https://nix-community.github.io/home-manager/index.xhtml#sec-install-standalone)
- nix-channel --add https://github.com/nix-community/home-manager/archive/release-23.11.tar.gz home-manager
- nix-channel --update
- nix-shell '<home-manager>' -A install


