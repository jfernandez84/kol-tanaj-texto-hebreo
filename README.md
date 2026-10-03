# Texto hebreo del Tanaj, adaptado (CC BY-SA) · Adapted Hebrew text of the Tanakh (CC BY-SA)

**Español.** Texto hebreo con vocales y cantilación de los 39 libros del Tanaj, con la numeración de Sefaria, en el formato que usa la aplicación
*Kol Tanaj* (Torá Para Todos). Ver [`NOTICE`](NOTICE) para la procedencia, los cambios y la licencia (**CC BY-SA 4.0**).

**English.** Hebrew text with vowels and cantillation of the 39 books of the Tanakh, with Sefaria's numbering, in the format used by the
*Kol Tanakh* app (Torá Para Todos). See [`NOTICE`](NOTICE) for provenance, changes and license (**CC BY-SA 4.0**).

Un archivo por libro / One file per book (`NN.json`, orden del Tanaj / Tanakh order):

```json
{"titulo": "Genesis", "titulo_hebreo": "בראשית", "texto": [ ["verse 1 of chapter 1", "verse 2", ...], ... ]}
```

`texto[c][v]` es el versículo `v+1` del capítulo `c+1` / is verse `v+1` of chapter `c+1`. En cada versículo, el ketiv va entre paréntesis y el qeré entre corchetes /
in each verse the ketiv is in parentheses and the qere in square brackets; `{פ}` y `{ס}` marcan el fin de una sección abierta o cerrada / mark the end of an open or closed
section; un salto de línea sigue a `{פ}` / a line break follows `{פ}`.

Contacto / Contact: info@toraparatodos.com · https://toraparatodos.com
