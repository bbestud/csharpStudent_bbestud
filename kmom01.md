<div>
  <img align="left" height="150" src="./../../images/leaf_256x256.png" alt="dbwebb leaf">
  <img align="right" height="150" src="./../../images/bth_logotyp-tillagg_ENG_black.jpg" alt="BTH logo">
</div>
<br/><br/>
<br/><br/>
<br/><br/>

# Kmom01: Kom igång med **C#**

Det första vi skall göra är att skaffa oss en utvecklingsmiljö och kika i kurslitteraturen. C# fungerar på många miljöer och i olika varianter. Vi kommer att skapa och köra C# program i terminalen. Vi använder VS code för att uppdatera vår kod och felsöka vår kod (debugging).

Vi börjar skriva de första enkla programmen för att komma underfund med hur C# kan användas och hur programmeringsspråket fungerar i grunden. Eftersom ni nyss läst Python så jämför vi med det och tittar på hur det ser ut i C#. Vi tittar även på C# som programmeringsspråk.

<!--more-->

![Informationsflödet mellan en användare och hårdvaran](./../../images/kmom01/infoUserHW.png "Informationsflödet mellan en användare och hårdvaran.")  
Bilden visar på informationsflödet mellan en användare och hårdvaran. Användaren är den som använder, nyttjar, programmet eller applikationen som det också kallas. Hårdvaran är den fysiska datorn och kan vara en PC, Linuxdator eller en Mac. Operativsystem kan vara Windows, någon Linuxvariant som Ubuntu eller Mac. Operativsystemet tillhandahåller resurser som filer och nätverkskommunikation samt hanterar resurser som minnet.

Applikationen är i vårt fall skrivet i språket C#. Vårt C#-program kompileras för att anpassas till hårdvaran. Våra C# kodrader översätts till maskinkod som körs på hårdvaran.


## Labbmiljön  

<!-- markdownlint-disable-next-line MD036 -->
*(ca: 2-4 studietimmar)*

<!-- 
Den korta varianten är att du behöver [installera labbmiljön](./labbmiljö/Installation.md), uppdatera [dbwebb-cli](dbwebb-cli) samt klona och initiera kursrepot.

```text
# Gå till din katalog för dbwebb-kurser
dbwebb selfupdate
dbwebb clone csharp
cd csharp
dbwebb init
```
-->

Du behöver ha följande installerat:

- Operativsystem Windows/MacOs/Linux
- Texteditor Visual Studio Code (VS Code)
- Webbläsare Chrome & Firefox samt OS specifik webbläsare
- Git
- Om Windows användare: Terminal WSL2 med Ubuntu
  
Skapa en katalog som heter "csharp" att jobba i:

```shell
mkdir csharp
```

Nu när kurskatalogen är på plats så behöver du också installera dotnet, se [Installation](./labbmiljö/Installation.md).


## Föreläsningar & genomgångar

1. Föreläsning om C#, .NET och  miljön
2. Genomgång installation, första programmet/appen "Skapa terminalprogram" och debugging


## Läsanvisningar

<!-- markdownlint-disable-next-line MD036 -->
*(ca: 6-10 studietimmar)*


### Kurslitteratur

Kursens huvudbok ger förståelse och bakgrunden till att klara övningar och uppgifter och heter [**C# 9.0 in a Nutshell: The Definitive Reference**](./../README.md#kurslitteratur).

Läsanvisningar:

- kapitel 1 Introducing C# & .NET
- kapitel 2 C# Language Basics


### Kunskap

1. Läs igenom [C# - vad är det för språk?](./Kunskap/CsharpInfo.md).


### Video

Titta på följande:

1. Videoserien [Lär dig C#](https://youtu.be/_oSD0_5QPEk?si=dQqCRE1XshuXjFv_) är tätt kopplat till kursmaterialet. Kika igenom serien under kursens gång. Här kommer jag att spela in små videosnuttar som tar upp det mesta i artiklarna "Python till C#" och "Mer C#" samt debugging i VS Code.


## Övningar & Uppgifter

<!-- markdownlint-disable-next-line MD036 -->
*(ca: 4-10 studietimmar)*

### Övningar

Jobba igenom följande. När du kör med C# inline kompilator får du tänka på att de kanske inte stödjer alla exempel i artiklarna.

1. Läs och jobba igenom [Python till **C#**](./Kunskap/PythonTillCsharp.md). Testa gärna i [C# online kompilator](https://dotnetfiddle.net/) (glöm ej att välja senaste kompilatorn i menyn till vänster). Skriv din kodsnutt inuti Main()-metoden.

2. Läs och jobba igenom [Mer **C#**](./Kunskap/MerCsharp.md). Testa gärna i [C# online kompilator](https://dotnetfiddle.net/) (glöm ej att välja senaste kompilatorn i menyn till vänster). Skriv din kodsnutt inuti Main()-metoden.

3. Kom igång med din första C# app tillsammans med artikeln [SkapaApp](./Kunskap/SkapaApp.md).

4. Gör ett enkelt menyprogram tillsammans med artikeln [SkapaMenyApp](./Kunskap/SkapaMenyApp.md).


### Uppgifter

Denna uppgift skall utföras och redovisas.

1. Gör ett [menyprogram](Uppgift/Uppgift.md). Använd gärna flödesschema eller pseudokod för problemlösningen.


### Extra

Det finns inga extra uppgifter för denna veckan men det finns en bra video med Mosh [C# Tutorial For Beginners](https://www.youtube.com/watch?v=gfkTfcpWqAY&ab_channel=ProgrammingwithMosh).


## Resultat & Redovisning

<!-- markdownlint-disable-next-line MD036 -->
*(ca: 1-2 studietimmar)*

Läs [instruktionen om hur du skall redovisa](./../redovisning.md).


## Målet med kmom01

Efter att ha jobbat igenom kmom01 så bör du kunna:

- grunderna i C#
  - miljön
  - datatyper
  - metoder/funktioner
  - iterationer
  - villkor och logik
- flödesschema & pseudokod
- grunderna i dotnet
  - skapa program i C# med dotnet
  - köra program med dotnet
- debugga program i VS code
