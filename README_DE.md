# `08` Eine echte Komponente

[//]: # (autograding setup start)
## Setup
- klone dieses Repository auf deinen Rechner
- öffne ein Terminal in VS Code
- Falls nötig, wechsle in das Projektverzeichnis
- führe `npm install` im Projektverzeichnis aus

[//]: # (Autograding setup end)

In der letzten Übung haben wir unsere erste Komponente namens **PrintHello** erstellt und wir lernen, dass wir die Komponente wie ein HTML-Tag verwenden können.
```jsx
<PrintHello />
```

Jetzt wollen wir eine weitere Komponente (Funktion) mit dem Namen **"Card "** erstellen, die das folgende HTML ausgibt:

```jsx
<div class="card m-5">
  <img class="card-img-top" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/02/Bob_Dylan_-_Azkena_Rock_Festival_2010_2.jpg/800px-Bob_Dylan_-_Azkena_Rock_Festival_2010_2.jpg" alt="Card image cap" />
  <div class="card-body">
    <h5 class="card-title">Bob Dylan</h5>
    <p class="card-text">Bob Dylan (born Robert Allen Zimmerman, May 24, 1941) is an American singer/songwriter, author, and artist who has been an influential figure in popular music and culture for more than five decades.</p>
    <a href="https://en.wikipedia.org/wiki/Bob_Dylan" class="btn btn-primary">Go to wikipedia</a>
  </div>
</div>
```

:point_up: Dieser HTML-Code basiert auf der [Bootstrap Card](https://getbootstrap.com/docs/4.0/components/card/).

# :speech_balloon: Anleitung

Schreibe deinen Code in `src/index.js`

- Erstelle eine Funktion namens Card, die den Kartencode zurückgibt und füge sie mit der ReactDOM.render-Funktion `<Card />` in die Website innerhalb von `#root` ein.

- Exportiere die Komponente als Standard-Export

Hinweis: Wenn du nicht weißt oder dich nicht daran erinnerst, wie man die Funktion `ReactDOM.render` verwendet, kannst du dir die vergangenen Übungen ansehen.
