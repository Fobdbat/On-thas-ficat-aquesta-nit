# On t'has ficat aquesta nit? · el joc

Joc de ritme amb la cançó de La Ludwig Band. Sis fases, una per músic, amb el relleu fet per un tobogan i el concert final.

## Què hi ha a la carpeta

| Fitxer | Què és |
|---|---|
| `index.html` | El joc sencer (gràfics, ninots, mapa de girs i temps de la lletra) |
| `canco.mp3` | La cançó (MP3 de 192 kbps, 4,8 MB) |
| `lletra.txt` | *No inclòs.* Opcional: si el poses tu, el joc el carrega sol |

## Publicar-lo a GitHub Pages

1. A github.com, **New repository**. Posa-li un nom, per exemple `On-thas-ficat-aquesta-nit`. Fes-lo **Public** i crea'l.
2. **Add file → Upload files**. Arrossega-hi `index.html` i `canco.mp3`, i després **Commit changes**.
3. **Settings → Pages**. A *Build and deployment* tria **Deploy from a branch**, branca `main` i carpeta `/ (root)`. Desa.
4. En un o dos minuts el joc ja és a `https://fobdbat.github.io/On-thas-ficat-aquesta-nit/`.

Per actualitzar-lo, torna a pujar el fitxer amb el mateix nom i GitHub el substitueix. Al mòbil, si veus la versió antiga, recarrega la pàgina.

## La lletra

Hi ha dues maneres de posar-la:

- **Per a tothom.** Afegeix un `lletra.txt` al costat de l'`index.html`. Ha de ser text pla en UTF-8, amb un vers per línia (71 versos). Les línies buides no compten. El joc el llegeix en obrir-se i la reparteix pels rètols, pels aparadors i pel subtítol de sota. Tingues en compte que tot el que pugis a un repositori públic és públic.
- **Només en un aparell.** Fes servir *Carrega la lletra* o *Enganxa la lletra* a la pantalla d'inici. Queda desada en aquell navegador.

Si un vers surt massa d'hora o massa tard, fes servir *Sincronitza la lletra*. El joc marca cada vers amb un toc, i després *Copia els temps* et dona la llista de temps.

## Sincronia del so (mòbil i Bluetooth)

Cada aparell té un retard d'àudio diferent. Els auriculars Bluetooth poden arribar a 150–250 ms. Si els girs et semblen avançats o endarrerits:

1. A la pantalla d'inici, toca **Calibra tocant**.
2. Fes servir els mateixos auriculars o el mateix altaveu amb què jugaràs.
3. Toca a cada un dels 16 cops que sentis.

El joc mesura el retard i el corregeix. Queda desat en aquell aparell. Els botons − i + l'afinen de 10 en 10 ms. Si toques el número, torna a zero.

## Comptador de visites

L'`index.html` porta la línia de GoatCounter del teu compte (`fobdbat.goatcounter.com`) just abans de `</body>`. Les visites et sortiran amb la ruta del repositori. Si no la vols, esborra aquella línia.

## Proves locals

Si obres l'`index.html` amb doble clic, el navegador no deixa carregar l'MP3. Per provar-lo a l'ordinador sense pujar-lo, obre un terminal a la carpeta i executa `python3 -m http.server`. Després ves a `http://localhost:8000`.
