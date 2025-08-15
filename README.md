# Demo Projekt

Wir verwenden dieses Projekt um unsere Installation zu testen.

## Webserver starten

Wenn Ihr `VSCode` richtig aufgesetzt ist, so wie es
[hier](https://gymmu.github.io/gym-inf/praktikum/install) beschrieben ist, können Sie ein
neues Terminal öffnen, und den folgenden Befehl eingeben:

```bash
npm run dev
```

Damit wird ein Webserver gestartet, und Sie können Sich die Webseite im Browser
anschauen.

## Aufgaben

Hier finden Sie einige Aufgaben um zu prüfen ob Sie alles richtig installiert haben, und auch soweit alles richtig konfigurieren können.

### Aufgabe 00

Wir müssen zuerst `git` richtig konfigurieren. Öffnen Sie dafür ein neues Terminal mit `Shift + Ctrl + P` und suchen Sie nach dem Befehl: `Terminal: Create new Terminal`. In diesem Terminal müssen Sie dann die folgenden beiden Befehle eingeben, und jeweils mit `Enter` den Befehl abschicken:

```bash
git config --global user.name "Vorname Nachname"
```

und den zweiten Befehl:

```bash
git config --global user.email "e123456@sbl.ch"
```

Wenn Sie alles in einem Container ausführen, müssen Sie das bei jedem Projekt wieder machen. Merken Sie sich diese Befehle am besten.

### Aufgabe 01

Drücken Sie `Ctrl + P` und suchen Sie nach `index.html`.

Fügen Sie Ihren Namen im Titel ein, und ersetzen Sie dabei die `...`.

> **`Commit`**: Machen Sie eine neue Version wenn Sie mit der Aufgabe fertig sind! Wie man einen **`Commit`** vom Terminal aus macht, können Sie [hier](#commit) nachlesen

### Aufgabe 02

Fügen Sie ein `<section>`-Tag in die Webseite ein, und füllen Sie es mit einem
sehr kurzen Text.

Platzieren Sie dieses `<section>`-Tag direkt unterhalb vom `<h1>`-Tag, noch
innerhalb vom `<main>`-Tag.

> **`Commit`**: Machen Sie eine neue Version wenn Sie mit der Aufgabe fertig sind!

### Aufgabe 03

Sie sollen einen kurzen Text schreiben der Sie vorstellt. Der Text soll 2
Abschnitte haben und einen Titel. Verwenden Sie dafür die folgenden Elemente:
`<h2>, <section>, <p>`.

> **`Commit`**: Machen Sie eine neue Version wenn Sie mit der Aufgabe fertig sind!

## Commit

Wie machen Sie einen neuen **Commit**? Sie können das entweder über die `Source Control` Ansicht machen (`Shift + Ctrl + G`) oder direkt über das Terminal.

Wenn Sie das Terminal wählen, dann brauchen Sie den folgenden Befehl 

```bash
git commit -am "Änderungsnachricht"
```