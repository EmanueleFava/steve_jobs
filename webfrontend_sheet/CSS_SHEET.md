# CSS Cheat Sheet

## Selettori

I selettori CSS consentono di identificare gli elementi HTML a cui applicare gli stili. Alcuni esempi comuni includono:

- **Selettore di tipo**: `p` per i paragrafi, `h1` per i titoli di primo livello, ecc.
- **Selettore di classe**: `.classe` per selezionare elementi con una specifica classe.
- **Selettore di ID**: `#id` per selezionare un elemento con un ID specifico.
- **Selettore universale**: `*` per selezionare tutti gli elementi.

Esempio:
```css
p {
  color: blue;
}

.classe {
  font-size: 16px;
}

#id {
  background-color: #f0f0f0;
}
```

## Proprietà

Le proprietà CSS definiscono l'aspetto degli elementi selezionati. Alcune delle proprietà più utilizzate includono:

- **color**: definisce il colore del testo.
- **font-family**: imposta il tipo di carattere.
- **font-size**: specifica la dimensione del carattere.
- **background-color**: imposta il colore dello sfondo.
- **padding**: definisce lo spazio interno dell'elemento.
- **margin**: imposta lo spazio esterno dell'elemento.
- **border**: definisce lo stile, lo spessore e il colore del bordo.

Esempio:
```css
h1 {
  color: red;
  font-family: Arial, sans-serif;
  font-size: 24px;
  background-color: #fff;
  padding: 10px;
  margin: 0;
  border: 1px solid black;
}
```

## Box Model

Il modello box CSS è un concetto fondamentale che definisce lo spazio occupato da un elemento HTML. È composto da:

- **Content**: il contenuto dell'elemento.
- **Padding**: lo spazio tra il contenuto e il bordo.
- **Border**: il bordo dell'elemento.
- **Margin**: lo spazio esterno dell'elemento.

Esempio:
```css
.box {
  width: 200px;
  height: 100px;
  padding: 20px;
  border: 1px solid #000;
  margin: 10px;
}
```

## Layout

Il layout in CSS può essere gestito utilizzando varie tecniche, tra cui:

- **Float**: posiziona gli elementi l'uno accanto all'altro.
- **Flexbox**: offre un modo flessibile per organizzare gli elementi in un contenitore.
- **Grid**: crea layout basati su righe e colonne.

Esempio di layout Flexbox:
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

## Media Queries

Le media queries consentono di applicare stili basati sulle caratteristiche del dispositivo, come la larghezza dello schermo o l'orientamento. Alcuni esempi includono:

```css
@media screen and (min-width: 768px) {
  /* Stili per schermi con larghezza minima di 768px */
}

@media (orientation: landscape) {
  /* Stili per schermi in modalità landscape */
}
```

Esempio di media query:
```css
@media screen and (max-width: 600px) {
  body {
    font-size: 14px;
  }
}
```

## Pseudo-classi e Pseudo-elementi

Le pseudo-classi e i pseudo-elementi consentono di selezionare elementi in base allo stato o alla posizione all'interno del documento. Alcuni esempi sono:

- **:hover**: seleziona un elemento quando viene passato sopra con il mouse.
- **:nth-child()**: seleziona un elemento in base alla sua posizione all'interno del genitore.

Esempio:
```css
a:hover {
  color: red;
}

li:nth-child(even) {
  background-color: #f2f2f2;
}
```

---

Puoi salvare questo testo in un file con estensione `.md` per utilizzarlo come documento Markdown.