# Hjemmeside – fra skabelon til GitHub Pages

Følg trinene nedenfor for at arbejde med din hjemmeside og til sidst publicere den med GitHub Pages.

## 1. Opret en GitHub-konto

Opret en konto på GitHub, hvis du ikke allerede har en.

## 2. Hent skabelonen

Download HTML- og CSS-skabelonen fra det sted, din underviser har angivet.

## 3. Kopiér filerne til din egen mappe

Du skal arbejde i din **egen individuelle mappe**.

Kopiér HTML-, CSS- og eventuelle andre filer fra skabelonen til din mappe.

Åbn derefter **hele mappen** i Visual Studio Code.

## 4. Installer Live Server

Åbn **Extensions** i Visual Studio Code.

Søg efter og installer:

**Live Server**

Live Server kan bruges til at åbne hjemmesiden i browseren, mens du arbejder med den.

## 5. Tilpas hjemmesiden

Tilpas hjemmesiden med dit eget indhold:

* Ret teksterne i HTML.
* Indsæt dine egne billeder.
* Tilpas farver, skrifttyper, størrelser osv. i CSS.
* Brug Live Server til at kontrollere resultatet undervejs.

## 6. Indstil dit navn og din e-mail i Git

Hvis du ikke tidligere har brugt Git på computeren, skal du fortælle Git, hvem du er.

Åbn terminalen i VS Code og skriv:

```bash
git config --global user.name "Fornavn Efternavn"
git config --global user.email "dinmail@example.com"
```

Eksempel:

```bash
git config --global user.name "Anna Jensen"
git config --global user.email "anna.jensen@gmail.com"
```

Brug dit eget navn og den e-mailadresse, du bruger til GitHub.

Du kan kontrollere oplysningerne med:

```bash
git config --global user.name
git config --global user.email
```

## 7. Commit og opret repository

Brug **Source Control** i Visual Studio Code.

1. Gem dine ændringer.
2. Lav et commit.
3. Opret/publicér projektet som et repository på GitHub.

Giv repositoriet et passende navn.

## 8. Synkronisér med GitHub

Synkronisér/push projektet til GitHub.

Gå derefter ind på GitHub og kontrollér, at dine filer ligger i repositoriet.

Du skal blandt andet kunne se din HTML-fil, CSS-fil og de billeder, du bruger på hjemmesiden.

## 9. Find GitHub Pages

Åbn dit repository på GitHub.

Gå til:

**Settings → Pages**

## 10. Publicér hjemmesiden

Under **Build and deployment**:

1. Vælg **Deploy from a branch**.
2. Vælg **main**.
3. Vælg **/(root)**.
4. Gem.

GitHub begynder nu at publicere din hjemmeside.

## 11. Åbn din hjemmeside

Vent lidt, mens GitHub Pages bygger hjemmesiden.

Gå igen til:

**Settings → Pages**

Her finder du linket til din publicerede hjemmeside.

Åbn linket og kontrollér:

* at hjemmesiden vises korrekt
* at CSS virker
* at billederne vises
* at links virker

---

## Kort huskeregel

**Egen mappe → VS Code → Live Server → tilpas → Git-navn og mail → commit → repository → synkronisér → Settings → Pages → main → /(root) → færdig hjemmeside**
