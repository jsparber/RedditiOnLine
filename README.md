# UnicoOnLine
This is a flatpak wrapper of the [RedditiOnLine](https://www.agenziaentrate.gov.it/portale/web/guest/redditi-pf-2022/software-di-compilazione-redditi-pf-2022) java applet provided by the Agenzia delle Entrate to fillout the tax form.

All files created by this app will be placed in `~/UnicoOnLine`.

## Install instructions
```
git clone https://github.com/jsparber/RedditiOnLine.git
cd RedditiOnLine
flatpak-builder --user --force-clean --install builds it.gov.agenziaentrate.RedditiOnLine.json
```
