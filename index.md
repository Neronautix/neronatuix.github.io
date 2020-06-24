# neronautix.github.io
# Node JS Hilfe

## EACESS ::80 Fehler
```sh
sudo setcap cap_net_bind_service=+ep `readlink -f \`which node\``
```
