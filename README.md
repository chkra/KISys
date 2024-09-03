# lecture template

Dieses Repository dient als template für eine Vorlesung. Es sollte mit dem entsprechenden Repository für die Modules verknüpft werden.


## Aufbau des Repositories

Das Repsitory basiert auf dem Jekyll Template [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) von Michael Rose. Alle technischen Ordner entstammen dem Minimal Mistakes Repo mit ggf. minimalen ästhetischen Anpassungen (z.B. Code Syntax Highlighting).

Folgende Ordner enthalten den Content:

* `/lectures` enthält die Einstiegsseiten und Übersichten für die theoretischen Inhalte der wöchentlichen Lektionen
* `/modules` enthält Ordner, die fachlich getrennt unterschiedliche Themen beinhalten. Eine wöchtenliche Lektion kann mehrere Module umfassen. Der Ordner kann aus einem anderen Repo der KI Werkstatt eingebunden werden.
* `/workshops` enthält praktischen Aufgaben und Materialien für die wöchentlichen Gruppenarbeiten vor Ort.

## Seiteninhalte erzeugen

Diese Seite wurde mit Jekyll erstellt. Die erzeugten Inhalte sind mit eingecheckt. Zur Vorbereitung ist auf einem System, das eine aktuelle Version von Ruby benötigt, folgendes einmalig auszuführen:

```bash
# install gem manager, may need sudo
gem install bundler

# install all requirements listed in Gemfile
bundle install
```

Zum wiederholten Bauen der Lösung folgende Befehle ausführen:

```bash
# build all pages
bundle exec jekyll build
# or build and serve all pages at a local webserver
bundle exec jekyll serve
```

Wichtige Parameter der Jekyll-Webseite wie der Autor und der Github-Pfad finden sich in der `_config.yml` und müssen angepasst werden. Zum wiederholten Bauen der Lösung folgende Befehle ausführen:

Der Output findet sich als HTML-Seite im Unterordner `/site`. 

## Bilder

Im Unterordner `/assets` findet sich eine Powerpoint-Datei mit vielen Bild-Vorlagen.

## Copyright

Alle Rechte vorbehalten | 2024 | KI Werkstatt @ HTW Berlin.

