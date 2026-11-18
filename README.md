# De muur

Mini-website: mijn voorlezing van "De muur" (Toon Tellegen, uit *Waar gaan we eigenlijk heen*), met de platen van Thé Tjong-Khing die op vaste momenten in beeld komen. Alleen voor persoonlijk gebruik.

- **Deel 1**: start op de vlakte. Bij "…vroeg hij toen. Hier heb je een foto" (181,4 s) komt de muur in beeld.
- **Deel 2**: gaat open op 19/11/2026 om 06:00. Start op de muur. Bij "Dan moet je kijken naar de foto" (97,3 s) komt het huis in beeld. Die plaat blijft als eindscherm staan.

## Nieuwe audio

1. Vervang `site/audio/deel-1.m4a` en/of `site/audio/deel-2.m4a`.
2. Pas in `site/index.html` bovenaan het script (`DELEN`) de `tijd` van elk moment aan, in seconden.
3. Push naar `main`. De website wordt dan vanzelf bijgewerkt.

Lokaal bekijken kan met elke simpele webserver in de map `site`. Als container: `docker build -t de-muur . && docker run -p 8080:8080 de-muur`.
