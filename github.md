# Github

Til at starte med fokuseres der på meget grundlæggende principper som:
* Repository
* Clone to desktop
* Commit
* Push

Med de værktøjer kan vi komme rigtig langt her i starten af uddannelsen.

# Opret en konto
For at kunne arbejde med Github, skal du oprette en konto. Den oprettes på hjemmesiden: https://github.com/join

Hvis du benytter din skole email (din-persid@rts-365.dk) så vil du kunne oprette private repositories! samt du får del af en github starter pakke, men mere om det senere.

Benyt dit rigtige navn som brugernavn, det vil have en betydning når du senere på uddannelsen skal aflevere opgaver her på github... det er ikke nemt for os lærere at gennemskue hvem der har afleveret hvad, med mindre navnet er til at gennemskue.

Har du allerede en github konto, kan du knytte din skoleemail til kontoen.


# Github Desktop
Hent og installer [Github Desktop](https://desktop.github.com/)
Det program kan benyttes til at holde styr på dine lokale repo's. Det er selvfølgelig muligt at benytte andre programmer hvis du har et favorit github program.

# git
Det er også nødvendigt at få windows til at forså hvad git er, derfor skal git installeres på maskinen. Det burde ske samtidigt med GithubDesktop, men det er ikke altid det sker, derfor er det en god ide at installere manuelt her fra:
https://git-scm.com/downloads

PC'en kræver højst sandsyntligt en genstart efter installationen.

# Credentials manager for windows
Hvis VSCode bliver ved med at spørge efter github login oplysninger, så installeres denne manager:

https://github.com/Microsoft/Git-Credential-Manager-for-Windows#download-and-install

---

## ```Opgave:``` igang med github
#### Mål: at få oprettet et repository og clone det til computeren

Nu hvor du er oprettet på Github, skal du prøve at oprette et repository.

Inde på Githubs side, https://github.com/new, skal du oprette et nyt repo med navnet **igang-med-github**

Under oprettelsen sætter du flueben i **Initialize this repository with a README** samt vælger **Node** under **Add .gitignore** 

Til sidst, klik på **Create Repository**


Når repo er oprettet, klikkes på **Clone or download** hvor der vælges **open in desktop**.
Sørg for at placere klonen et sted du let kan finde på din computer.

---

Åben Visual Studio Code, og åben den nye mappe der indeholder dit repo.

Læg mærke til at der skal ligge en fil kaldet **.gitignore** samt en fil kaldet **README.md** under filtræet i VSCode.
Mangler filerne er det en forkert mappe du har åbnet ... prøv igen.

Tilføj en ny fil, kald den **app.js**


tilføj følgende kode-linje i toppen af den nye fil:
```javascript
console.log('Hej verden!');
```

her kan man selvfølgelig lige prøve at åbne konsollen i VScode **[ctrl] + [æ]**, og skrive **node app** for at få NodeJS til at køre filen, og se at den skriver **Hej verden!** i VSCode konsollen.

---

## ```Opgave:``` Commit og Push
#### Mål: at få synkroniseret det lokale repository med det der ligger online
Hvis der er et rundt badge med et 1-tal, over ikonet til **source control** i visual studio code, så klikkes på ikonet og du kan nu skrive en besked, f.eks. **Tilføjet app.js**. Alle commit's skal have en besked der beskriver hvad der er ændret.

I listen over ændrede filer (changes) klikkes på plusset der dukker op når musen føres over en fil (der burde kun være 1 fil lige nu).

Nu burde der stå **Staged Changes** og under den **app.js**

klik på de tre **[...]** over beskedfeltet, og vælg **Commit Staged**


Gå tilbage til browseren, og opdater siden med dit repo. (der burde ikke være nogle ændringer endnu).


**Commit Staged** synkroniserer ikke med det online github repo, til det skal vi tilbage i VSCode, og vælge **Push** fra samme menu hvor **Commit Staged** lå.

Så kan du prøve at opdatere github siden igen, og se at nu ligger der en app.js på dit online repo, yay!

---
## ```Opgave:``` Markdown
#### Mål: at blive fortrolig med github markdown, der skal benyttes til dokumentation af koder og opgaver
En af de arbejdsopgaver du kommer til at bruge meget tid på, er at dokumentere og beskrive dine koder. 
Du skal i **README.md** filen lave din egen beskrivelse af hvordan du opretter et repository på din github, med den opsætning vi har været igennem her. 

Du vælger selv om du vil sidde i Visual Studio Code, eller om du gør det via browseren på github.com 

Du skal benytte **headers**, **emphasis**, **lists**, **links** samt **flavored markdown** (syntaks highlight) 
Til syntakshightlight, kan du kort beskrive, hvad console.log koden gør :+1: . 

Prøv at gør beskrivelsen kort men præcis, og spørg din sidemand om beskrivelsen giver mening.

Husk at Commit (og Push hvis du sidder i Visual Studio Code), så din readme.md bliver opdateret.

Her er en online beskrivelse af [Github Markdown](https://guides.github.com/features/mastering-markdown/)



---

[tilbage til programmer og systemer](programmer-og-systemer.md)