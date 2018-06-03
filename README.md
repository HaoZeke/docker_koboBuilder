# koboBot Dockerfile [![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg?style=for-the-badge)](https://www.paypal.me/HaoZeke/)
> Copyright (C) 2017  Rohit Goswami <rohit1995@mail.ru>

Meant for compiling finicky kobo (Aura HD) systems with an archlinux box.

Works as a self contained setup for [koreader](https://github.com/koreader/koreader) and [plato](https://github.com/baskerville/plato).

## Usage

The recommended usage leverages your existing build tree so you only need this as your build environment.

```bash
docker run -it -h kobobot -v $SOURCE_LOCATION:/home/build/Github/Ereaders -v
$HOME/.ccache/:/home/build/.ccache -v $HOME/.cache/:/home/build/.cache -v $HOMEx-tools:/home/build/x-tools HaoZeke/kobobot
```
