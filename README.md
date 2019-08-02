# com.elsevier.MendeleyDesktop

For installation instructions, please visit app page on flathub at https://flathub.org/apps/details/com.elsevier.MendeleyDesktop

## Known issues:

In order to use LibreOffice plugin, please do the following steps:

* Open LibreOffice Extension Manager at Tools > Extension Manager or Ctrl + Alt + E

* Locate Mendeley Desktop extension at `/var/lib/flatpak/app/com.elsevier.MendeleyDesktop/current/active/files/extra/share/mendeleydesktop/openOfficePlugin/Mendeley-{version}.oxt` or `~/.local/share/flatpak/app/com.elsevier.MendeleyDesktop/current/active/files/extra/share/mendeleydesktop/openOfficePlugin/Mendeley-{version}.oxt`

* Install it

* **Note**: If using LibreOffice from flatpak, you have to allow it to access /tmp from host, i.e. `flatpak override --filesystem=/tmp org.libreoffice.LibreOffice`

Reference:
https://blog.kukuh.syafaat.id/2018/LibreOffice-and-Mendeley-Desktop-Flatpak/
