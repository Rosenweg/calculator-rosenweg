<p align="center"><img src="assets/logo/rosenweg-rechner-512.png" width="96" alt="Logo"></p>
<h1 align="center">Rosenweg Rechner</h1>
<p align="center">Taschenrechner für die Smartphones der Siedlung Rosenweg – auf den geteilten Telefonen und dem eigenen Handy.</p>
<p align="center"><a href="https://www.rosenweg4303.ch/apps">Herunterladen</a> · <a href="docs/anleitung.md">Anleitung</a> · <a href="docs/entwickeln.md">Für Entwickler</a></p>

## Was die App kann

- Rechnen wie gewohnt: Grundrechenarten, Prozent, Wurzel und Potenzen.
- Einstellungen gehören der angemeldeten Person und sind auf jedem geteilten Telefon wieder da.
- Hält auf dem eigenen Handy alle Rosenweg-Apps aktuell (Rosenweg Updater).
- Mit dem Rosenweg-Schlüssel signiert, ohne Spenden- und Store-Hinweise.

## Plattformen

Android.

## Entwickeln

Android-App (Kotlin) auf Basis von Fossify Calculator, gebaut gegen
[commons-rosenweg](https://github.com/Rosenweg/commons-rosenweg): `./gradlew assembleFossRelease` –
Bau, Signatur, Logo und Veröffentlichung stehen in [docs/entwickeln.md](docs/entwickeln.md).

## Herkunft und Lizenz

Basiert auf [Fossify Calculator](https://github.com/FossifyOrg/Calculator) – herzlichen Dank an das Fossify-Team und alle Mitwirkenden.
GPL-3.0, siehe [LICENSE](LICENSE).
