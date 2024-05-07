# Examen UF3
- El color del backgorund i el del text no tenen contrast suficient per la perfecta visualització del contingut (2.22 punts segons sigemedia). Per aixó, he canviat el color del text per un que superi els 5 punts. Segons la pàgina web aremycolorsaccessible.com l'elecció de colors es correcta.

- He canviat l'etiqueta div que emmagatzema el contingut principal per l'etiqueta main per fer-ho més favorable per al SEO.

- He afegit el titol del document per fer-ho més favorable per al SEO.

- He afegit i modificat diferents etiquetes relatives als títols, com l'adició d'un h1 i canviat els p amb negreta que simulaven el títol de l'article per h2 per fer-ho més favorable per al SEO.

- He afegit la imatge que he trobat a unsplash d'ús gratuit, l'he reescalat i el seu pes es de 54kb per optimitzar els temps de descàrrega. També he afegit un alt amb un text descriptiu de la imatge per ajudar a l'usuari que no ho pot visualitzar correctament.

- He substituit algunes etiquetes per article, section i figure, aconseguint un html més semàntic i fent-ho més favorable per al SEO.

- He afegit un botó "skip to main content" per facilitar l'accés al contingut.

- He modularitzat el css i he afegit l'atribut lang a l'html.

- He afegit l'etiqueta aria-labelledby als enllaços per facilitar el seu reconeixement. També he afegit l'atribut role a les etiquetes que n'hi havia més d'una.

- He tret les etiquetes role ja que lighthouse deia que estaven malament implementades. Es millor no posar ARIA que posar un mal ARIA.

- He tret les tables ja que dificulten les tecnologies de lectura de pantalla i les he canviat per etiquetes semàntiques.

