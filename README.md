# GTK3 configuration

GTK3-Einstellungen und CSS für die Desktop-Anwendungen.

**[Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/components/#gtk3)** ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- gtk-3.0
```

Paket: `arch-dotfiles-gtk-3.0`. Dateien: `~/.config/gtk-3.0/settings.ini` und `gtk.css`.
Quellen und `packaging/arch/PKGBUILD` werden hier gepflegt. Nach Push auf `main`
und erfolgreichem Registry-Build aktualisiert `sudo pacman -Syu` das Paket.
Entwicklung und Builds: [PACKAGING.md](PACKAGING.md).

### Anpassung

`settings.ini` enthält die GTK3-Einstellungen; `gtk.css` ergänzt eigene Stilregeln. Betroffene GTK3-Anwendungen nach Änderungen neu starten. GTK4 verwendet eine getrennte Konfiguration.

Eigene Änderungen in der aktivierten Benutzerkopie bleiben bei der Synchronisierung erhalten; neue abweichende Vorgaben erscheinen als `.pacnew`. Siehe [Update und Wiederherstellung](https://arch-dotfiles.readthedocs.io/en/latest/verification/).

[![Package safety](https://github.com/MichaelWeissDEV/gtk3-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/gtk3-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
