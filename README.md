# LUPII HOCHEIULUI — Site oficial

Hub-ul digital de susținere pentru **Asociația Sportivă Lupii Hocheiului pe Gheață**, Brașov.

🔗 **Site publicat:** https://lupiihocheiului.github.io/

## Ce face site-ul

Un singur URL (ideal pentru QR pe materiale printate, social media, afișe) prin care vizitatorii pot:

- **Doneaza** — transfer bancar direct (IBAN RON / EUR cu buton de copiere)
- **Redirecționează 3,5%** din impozitul pe venit (formularul 230)
- **Sponsorizează** — pentru companii, cu contract de sponsorizare descărcabil (DOCX / PDF)
- **Contact** — formular și date oficiale ale asociației

## Structură

Site-ul este o singură pagină statică (`index.html`) — fără framework, fără build, fără dependențe.
Hosting: **GitHub Pages**, publicat automat la fiecare push pe `main`.

```
index.html                                  # site-ul complet (single-page)
Contract_sponsorizare_Lupii_Hocheiului.docx # contract de sponsorizare (editabil)
Contract_sponsorizare_Lupii_Hocheiului.pdf  # contract de sponsorizare (printabil)
QR_Lupii_Hocheiului.png                     # cod QR static → URL-ul site-ului
QR_Lupii_Hocheiului.svg                     # versiune vectorială pentru print
```

## Publicare / actualizare

Orice modificare adusă fișierelor și urmată de un `git push` pe branch-ul `main` apare
pe site în 1–2 minute. Nu e nevoie de niciun pas suplimentar.

## Date asociației

**ASOCIAȚIA SPORTIVĂ LUPII HOCHEIULUI PE GHEAȚĂ**
CUI: 54787663 • Str. Hărmanului nr. 63, parter, birou 1, Brașov
Contact: lupiihocheiului@gmail.com
