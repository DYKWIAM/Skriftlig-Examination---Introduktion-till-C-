# Skriftlig Examination - Introduktion till C#

**Kursnamn**: Introduktion till C#  
**Examination av**: Läranderesultat 1, 2 och 3 (Kunskaper)  
**Betyg**: Icke Godkänt (IG) eller Godkänt (G)  
**Tidsåtgång**: Ca 3-4 timmar  
**Inlämning**: Senast söndag den 9 november (23:59)  
**Format**: Kopiera den här filen och skriv svaren här inne.
---

**Elevens namn**: ![blue badge](https://img.shields.io/badge/Masoud%20Dehdar-blue)

---

## Instruktioner

- Svara på alla frågor med egna ord
- Det är inte tillåtet att använda AI i sina svar.
- Alla inlämningar kontrolleras i ett antiplagiat-verktyg. Fusk kan leda till disciplinära åtgärder och risk för avstängning.
- Förklara tydligt och koncist - inga långa utläggningar krävs
- Ge korta kodexempel endast där det efterfrågas (oftast räcker 1-3 rader)
- Försök att använda korrekt terminologi.
- Det är okej att använda kursmaterial och anteckningar

---

## Del 1: Objektorienterad programmering i C# (Läranderesultat 1)

### Fråga 1 - Grundläggande OOP

**Vad är objektorienterad programmering?** Förklara med egna ord vad OOP innebär och ge minst två fördelar med att använda OOP.

its a way to conceptualize coding !
so its about the idea rather then coding.
e.g a car is an object it can have fields, properties, name, age etc.
two good things with it: its less complex than c++ and very integrated.
---

### Fråga 2 - Klasser och Objekt

**.**
a) Förklara skillnaden mellan en klass och ett objekt, använd gärna en analogi från verkligheten för att illustrera din förklaring.

an objekt can be an instance of the class
a class is a blueprint and object its product or once its made like the car.

b) Vad innebär det om en klass benämns static? Ex: `public static class File`
that it cannot be instantiated and is like a default blueprint.
you can use it as it is.
---

### Fråga 3 - Konstruktorer

**Vad är en konstruktor och vad används den till?** Förklara vad som händer när man skapar ett nytt objekt med `new` keyword.

you create a new instance of something with new. new creates a space, gives a label and and instantiat it !
new instance of a function, object, array etc

---

### Fråga 4 - Properties och Fields

**Förklara skillnaden mellan ett field och en property i C#.** Ge exempel på när man bör använda respektive.
field is general variables like int x or string y
property has setters and getters allows read and write
int age:
property adress:
---

### Fråga 5 - Inkapsling

**Vad är inkapsling (encapsulation) och varför är det viktigt?** Förklara skillnaden mellan `private` och `public`, och när man bör använda vad.

its encapsulating something and showing the part which is public and not private.
if you want tel nr hidden you set it to private.

---

### Fråga 6 - Metoder

**Förklara följande:**

a) Vad är skillnaden mellan en metod som returnerar något (t.ex. `int`) och en `void` metod?  
  void doesn't return antything but int, string <generic types > or others before the variable names not always returns int string or generic types.
  like public string x {}

b) Vad innebär det att en metod är `static`?
a method being static means that method is bound to the class it is in.
and you can only access other static members not instance fields.
you cant use new on static beause again its bound.
---

## Del 2: Applikationstyper (Läranderesultat 2)

### Fråga 7 - Applikationstyper i .NET

**C# och .NET kan användas för att bygga olika typer av applikationer.**

a) Nämn minst tre olika typer av applikationer man kan bygga med C# och .NET (t.ex. console) 
console, desktop, cli, mobile apps, full stack app.
b) Beskriv kort vad dessa applikationstyper har för syfte.
console will print on console and runs there.
dekstop for desktop apps
full stack like a webshop with database, server, front end, razor .

---

### Fråga 8 - Konsolapplikationer

**Vi har fokuserat på konsolapplikationer (Console Application) i kursen.**

a) Vad är en konsolapplikation?  
console app will print on console and runs in console.

b) Ge ett exempel på när en konsolapplikation kan vara lämplig att använda.
calander, registry, calculator
---

## Del 3: Datatyper i C# (Läranderesultat 3)

### Fråga 9 - Primitiva Datatyper

**Beskriv följande datatyper och när man använder dem:**

a) `int` numbers
b) `double`  numbers accuracy
c) `string`  text
d) `bool`    on off switch or when something has only 2 values.

Förklara också skillnaden mellan `int` och `double`.
int is whole numbers, double is decimal accuracy
---

### Fråga 10 - Stark typning

**C# är ett starkt typat språk, medan JavaScript är löst typat.**

a) Vad innebär det att ett språk är starkt typat?  all types has to be known otherwise compiler error
b) Ge ett exempel på en fördel med stark typning som du märkt av i C#. ? int something to expect numbers.
in js you have let something can be int string etc. in c# type has to be known.

---

### Fråga 11 - Arrays och Listor

**Förklara skillnaden mellan en array och en `List<T>` i C#.**

a) När bör man använda en array? when you know the type and its consistent.
b) När bör man använda en `List<T>`?  when t can be other then primitive types
c) Skriv ett kort kodexempel (1-3 rader) som visar hur man lägger till ett element i en `List<int>`.
List<int> nr = new List<int>();
nr.add(10);
---

### Fråga 12 - Dictionary

**Vad är en `Dictionary<TKey, TValue>` och när är den användbar?**

Förklara med egna ord och ge två exempel på scenarion där Dictionary är ett bra val (inget kodexempel krävs).
when you want to add key-value pairs like name-address or atk-def;
---

### Fråga 13 - LINQ

**Vad är LINQ och vad används det till?**

Ge exempel på minst två LINQ-metoder du använt (t.ex. `Where`, `Select`, `OrderBy`, `Count`, etc.) och förklara kort vad de gör.
var nr = nr.Where(n => n > 0);
var nr = nr.Select(x => x > 0);
---

## Inlämning och Bedömning

### Format

- Ladda upp den här md filen med dina svar på It's learning senast den 9 november 2025. För de
  som hellre vill länka till sin Git får ni också göra det.

- Skriv ditt **namn** i dokumentet

### Bedömning

#### Godkänt (G)

För att få **Godkänt** krävs att du:

- Besvarar **alla 13 frågor**
- Visar förståelse för grundläggande koncept
- Ger tydliga förklaringar med egna ord
- Använder korrekt terminologi
- Ger kodexempel där det efterfrågas (behöver inte vara perfekt, men ska visa förståelse)

#### Icke Godkänt (IG)

Du får **Icke Godkänt** om:

- Flera frågor är obesvarade eller mycket ofullständiga
- Svaren visar grundläggande missförstånd av koncept
- Svaren är uppenbart kopierade från AI eller andra källor utan egen förståelse
- Svaren är så kortfattade att de inte visar förståelse

**Vid gränsfall**: Om du är nära G men några svar är otillräckliga kan du få möjlighet att komplettera specifika frågor.

---

## Tips för att lyckas

- Börja med frågorna du känner dig säkrast på
- Svara koncist - kvalitet över kvantitet
- Läs igenom dina svar innan inlämning
- Börja i tid - du har två veckor på dig
- Fråga på lektioner om något är oklart

**Kom ihåg**: Det viktiga är att du visar att du **förstår** koncepten, inte hur mycket du skriver. Tydliga, korta förklaringar är ofta bättre än långa utsvävningar.

---

## Hjälp och resurser

### Tillåtet

- Använda kursmaterial och dina egna anteckningar
- Titta på kod du själv skrivit under kursen
- Använda C# dokumentation (docs.microsoft.com)
- Fråga läraren om du inte förstår vad en fråga betyder
- Man får också använda AI för egen inlärning

### Inte tillåtet

- Kopiera svar från ChatGPT eller andra AI-verktyg
- Kopiera svar från klasskamrater eller internet
- Låta någon annan skriva dina svar

---

**Lycka till! 🚀**
#