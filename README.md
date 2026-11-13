# Spotify Web (template)

L'interfaccia web di Spotify rifatta in HTML e CSS. L'ho fatta per esercizio durante il bootcamp: c'è solo la parte grafica, niente JavaScript e niente musica che parte davvero. Non ha niente a che fare con Spotify, ne ho solo preso l'idea.

## Cosa c'è dentro

- Barra laterale con navigazione, playlist e profilo
- Intestazione con il pulsante "Effettua l'upgrade" e il menu delle sezioni
- Le sezioni "Riprodotti di recente", "Creato per te" e "Artisti più popolari", con le copertine
- Il player in basso con i controlli e il volume

## La parte che mi interessava: il mobile

Il layout si adatta alla larghezza dello schermo. Sotto i 576 px la barra laterale sparisce e al suo posto resta una striscia stretta con le sole icone, come nell'app. Le copertine passano da sei per riga a quattro e poi a due, con una griglia a 12 colonne e breakpoint a 1200, 992, 768, 600 e 480 px.

## Come aprirlo

Non serve installare niente: scarica il progetto e apri `index.html` nel browser. I font e le icone si caricano da internet (Google Fonts e Font Awesome), quindi serve la connessione.

## Cartelle

- `css/` contiene il reset, le utility, gli stili del progetto e la griglia
- `img/` contiene copertine, icone e logo

## Stack

HTML5, CSS3, Font Awesome, Google Fonts (Ubuntu).
