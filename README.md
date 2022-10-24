# NorwegianPasswordSpraying
A repository containing lists and different premade combinations of weak/default passwords (in Norwegian) typically seen during external pentests and red team assessments. Contains seasons, months and holidays, additionally, modified versions of some words are included to account for different representations of the letters Æ, Ø and Å.

The unmodified lists can used with tools such as [psudohash](https://github.com/t3l3machus/psudohash), [gorilla](https://github.com/d4rckh/gorilla), [mentalist](https://github.com/sc0tfree/mentalist) to create wordlists for spraying and password cracking or with the below oneliner. Modify as needed.

```
for i in $(cat helligdager.txt); do echo ${i}1; echo ${i}123; echo ${i}2022; echo ${i}2022\!; echo ${i}22; echo ${i}22\!; echo ${i}@2022; echo ${i}@22; echo ${i}\!22; echo ${i}\!2022; done > helligdager_appended.txt
```

### Seasons/Årstider:
```
Vår
Var
Vaar
Våren
Varen
Vaaren
Sommer
Sommeren
Høst
Host
Hoest
Høsten
Hosten
Hoesten
Vinter
Vinteren
```

### Months/Måneder:
```
Januar
Februar
Mars
April
Mai
Juni
Juli
August
September
Oktober
November
Desember
```

### Holidays/Høytider/helligdager:
```
Nyttår
Nyttar
Nyttaar
Helligtrekongersdag
Valentin
Valentine
Valentines
Valentinsdag
Fastelavn
Fastelaven
Kvinnedagen
Påske
Paske
Paaske
Palmesøndag
Palmesondag
Palmesoendag
Skjærtorsdag
Skjaertorsdag
Langfredag
Påskedagen
Paskedagen
Paaskedagen
Påskeaften
Paskeaften
Paaskeaften
Maidagen
Førstemai
Forstemai
Foerstemai
Morsdag
Kristihimmelfartsdag
Syttendemai
Grunnlovsdag
Grunnlovsdagen
Pinse
Treenighetssøndag
Treenighetssondag
Treenighetssoendag
Sankthans
Sankthansaften
Olsok
Allehelgensaften
Allehelgensdag
Halloween
Høsttakkefest
Hosttakkefest
Hoesttakkefest
Thanksgiving
Thanksgivingday
Farsdag
Mannsdagen
Mannedagen
Bededag
Advent
Førjulstiden
Forjulstiden
Foerjulstiden
Lucia
Luciadagen
Lucienatt
Lussimess
Jul
Julaften
Midtvinter
Midtvinterfest
```

## Comma separated/Kommaseparert:

### Seasons/Årstider:
```
Vår,Var,Vaar,Våren,Varen,Vaaren,Sommer,Sommeren,Høst,Host,Hoest,Høsten,Hosten,Hoesten,Vinter,Vinteren
```

### Months/Måneder:
```
Januar,Februar,Mars,April,Mai,Juni,Juli,August,September,Oktober,November,Desember
```

### Holidays/Høytider/Helligdager:
```
Nyttår,Nyttar,Nyttaar,Helligtrekongersdag,Valentin,Valentine,Valentines,Valentinsdag,Fastelavn,Fastelaven,Kvinnedagen,Påske,Paske,Paaske,Palmesøndag,Palmesondag,Palmesoendag,Skjærtorsdag,Skjaertorsdag,Langfredag,Påskedagen,Paskedagen,Paaskedagen,Påskeaften,Paskeaften,Paaskeaften,Maidagen,Førstemai,Forstemai,Foerstemai,Morsdag,Kristihimmelfartsdag,Syttendemai,Grunnlovsdag,Grunnlovsdagen,Pinse,Treenighetssøndag,Treenighetssondag,Treenighetssoendag,Sankthans,Sankthansaften,Olsok,Allehelgensaften,Allehelgensdag,Halloween,Høsttakkefest,Hosttakkefest,Hoesttakkefest,Thanksgiving,Thanksgivingday,Farsdag,Mannsdagen,Mannedagen,Bededag,Advent,Førjulstiden,Forjulstiden,Foerjulstiden,Lucia,Luciadagen,Lucienatt,Lussimess,Jul,Julaften,Midtvinter,Midtvinterfest
```

## Usual password mutations/Vanlige passord mutasjoner:

### Spring/Vår:
```
Vår1
Var1
Vaar1
Våren1
Varen1
Vaaren1
Vår123
Var123
Vaar123
Våren123
Varen123
Vaaren123
Vår2022
Var2022
Vaar2022
Våren2022
Varen2022
Vaaren2022
Vår2022!
Var2022!
Vaar2022!
Våren2022!
Varen2022!
Vaaren2022!
Vår22
Var22
Vaar22
Våren22
Varen22
Vaaren22
Vår22!
Var22!
Vaar22!
Våren22!
Varen22!
Vaaren22!
Vår!22
Var!22
Vaar!22
Våren!22
Varen!22
Vaaren!22
Vår!2022
Var!2022
Vaar!2022
Våren!2022
Varen!2022
Vaaren!2022
Vår@2022
Var@2022
Vaar@2022
Våren@2022
Varen@2022
Vaaren@2022
Vår@22
Var@22
Vaar@22
Våren@22
Varen@22
Vaaren@22
```

### Summer/Sommer:
```
Sommer1
Sommeren1
Sommer123
Sommeren123
Sommer2022
Sommeren2022
Sommer2022!
Sommeren2022!
Sommer22
Sommeren22
Sommer22!
Sommeren22!
Sommer@2022
Sommeren@2022
Sommer@22
Sommeren@22
Sommer!22
Sommeren!22
Sommer!2022
Sommeren!2022
```

### Autum/Høst:
```
Høst1
Host1
Hoest1
Høsten1
Hosten1
Hoesten1
Høst123
Host123
Hoest123
Høsten123
Hosten123
Hoesten123
Høst2022
Host2022
Hoest2022
Høsten2022
Hosten2022
Hoesten2022
Høst2022!
Host2022!
Hoest2022!
Høsten2022!
Hosten2022!
Hoesten2022!
Høst22
Host22
Hoest22
Høsten22
Hosten22
Hoesten22
Høst22!
Host22!
Hoest22!
Høsten22!
Hosten22!
Hoesten22!
Høst@2022
Host@2022
Hoest@2022
Høsten@2022
Hosten@2022
Hoesten@2022
Høst@22
Host@22
Hoest@22
Høsten@22
Hosten@22
Hoesten@22
Høst!22
Host!22
Hoest!22
Høsten!22
Hosten!22
Hoesten!22
Høst!2022
Host!2022
Hoest!2022
Høsten!2022
Hosten!2022
Hoesten!2022
```

### Winter/Vinter:
```
Vinter1
Vinteren1
Vinter123
Vinteren123
Vinter2022
Vinteren2022
Vinter2022!
Vinteren2022!
Vinter22
Vinteren22
Vinter22!
Vinteren22!
Vinter@2022
Vinteren@2022
Vinter@22
Vinteren@22
Vinter!22
Vinteren!22
Vinter!2022
Vinteren!2022
```

### Months/Måneder:
```
Januar
Februar
Mars
April
Mai
Juni
Juli
August
September
Oktober
November
Desember
```

### January/Januar:
```
Januar1
Januar123
Januar2022
Januar2022!
Januar22
Januar22!
Januar@2022
Januar@22
Januar!22
Januar!2022
```

### February/Februar:
```
Februar1
Februar123
Februar2022
Februar2022!
Februar22
Februar22!
Februar@2022
Februar@22
Februar!22
Februar!2022
```

### March/Mars:
```
Mars1
Mars123
Mars2022
Mars2022!
Mars22
Mars22!
Mars@2022
Mars@22
Mars!22
Mars!2022
```

### April:
```
April1
April123
April2022
April2022!
April22
April22!
April@2022
April@22
April!22
April!2022
```

### May/Mai:
```
Mai1
Mai123
Mai2022
Mai2022!
Mai22
Mai22!
Mai@2022
Mai@22
Mai!22
Mai!2022
```

### June/Juni:
```
Juni1
Juni123
Juni2022
Juni2022!
Juni22
Juni22!
Juni@2022
Juni@22
Juni!22
Juni!2022
```

### July/Juli:
```
Juli1
Juli123
Juli2022
Juli2022!
Juli22
Juli22!
Juli@2022
Juli@22
Juli!22
Juli!2022
```

### August:
```
August1
August123
August2022
August2022!
August22
August22!
August@2022
August@22
August!22
August!2022
```

### September:
```
September1
September123
September2022
September2022!
September22
September22!
September@2022
September@22
September!22
September!2022
```

### October/Oktober:
```
Oktober1
Oktober123
Oktober2022
Oktober2022!
Oktober22
Oktober22!
Oktober@2022
Oktober@22
Oktober!22
Oktober!2022
```

### November:
```
November1
November123
November2022
November2022!
November22
November22!
November@2022
November@22
November!22
November!2022
```

### December/Desember:
```
Desember1
Desember123
Desember2022
Desember2022!
Desember22
Desember22!
Desember@2022
Desember@22
Desember!22
Desember!2022
```
