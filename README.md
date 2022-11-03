# Deprecation notice

This repository is no longer maintained.

To patch [pwclient](https://aur.archlinux.org/packages/pwclient)’s
`PKGBUILD`, you can use
[customizepkg](https://github.com/ava1ar/customizepkg) and maintain
the following file at `/etc/customizepkg.d/pwclient`:

```
# https://aur.archlinux.org/packages/pwclient#comment-878296
replace#global#python setup.py#PBR_VERSION=$pkgver python setup.py
```