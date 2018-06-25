## Crearea de linkuri

Pe acest card veți afla cum să creați o legătură care să vă ducă la o altă pagină când este făcută clic pe ea.

- Adăugați următorul cod la secțiunea de corp `index.html`:

```html
  <a href="">Faceți clic aici</a>
```

Tag-urile `<a> </a>` transformă ceea ce se află între ele într-o legătură.

- Încercați să faceți clic pe linkul dvs. pentru a vedea ce se întâmplă. Nu face nimic, nu?

Aceasta deoarece atributul `href` este gol în acest moment. Aceasta trebuie să conțină **URL -** (adresa de web) a paginii pe care doriți să creați un link.

- Accesați Wikipedia și găsiți o pagină despre ceva pe site-ul dvs. web. Voi folosi pagina despre Irlanda.

- Faceți clic pe bara de adrese și selectați tot textul din i5. Aceasta este adresa URL completă a paginii pe care vă aflați. apasă pe <kdb>Ctrl</kdb> (sau <kdb>cmd</kdb>) și <kdb>C</kdb> simultan pentru copiere.
    
    ![Adresa URL în bara de adrese](images/AddressBarURL.png)

- În trinket, faceți clic între ghilimele după `href =` și apăsați pe <kdb>Ctrl</kdb> (sau <kdb>cmd</kdb>) și <kdb>V</kdb> chei în același timp pentru a lipi în URL-ul pe care tocmai l-ați copiat. Codul dvs. ar trebui să pară așa:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">Faceți clic aici</a>
```

Tocmai ai creat primul tău link! Faceți clic pe acesta pentru a vedea dacă funcționează acum.

![Link tag](images/egLinkTagWithURL.png)

## \--- colaps \---

## titlu: Legături către alte site-uri web

Trinket are probleme cu unele adrese web. Puteți încerca să utilizați URL-uri de alte site-uri decât Wikipedia dacă doriți, dar este posibil ca acestea să nu funcționeze în trinket. Cu toate acestea, dacă ați descărcat proiectul și ați vizualizat fișierele într-un browser web, ați vedea că link-urile funcționează.

\--- / colaps \---

- Încercați să puneți o imagine între etichetele `<a> </a>` în loc de cuvintele `Faceți clic aici`, după cum urmează:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">
      <img src="tito.png" alt="Tito the dog" width="100px" />
  </a>
```

- Faceți clic pe imaginea dvs. Vezi că a fost transformată într-o legătură?

Puteți pune și un link în alte elemente ale paginii dvs. web, cum ar fi într-un paragraf sau chiar într-o listă. Iată un exemplu de propoziție cu o legătură în ea:

```html
  <p>
    <a href="https://en.wikipedia.org/wiki/Ireland">Faceți clic aici</a> pentru a citi pagina Wikipedia!
  </p>
```

\--- provocare \---

## Provocare: puneți o legătură într-o listă

- Vedeți dacă puteți crea o listă care conține o legătură într-unul din elementele listate.

\--- /provocare \---