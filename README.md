# sass-tutorial
Kom igång med Sass
* Syntactically awesome style sheets
* Från 2006
* Sass är ett skriptspråk som interpreteras och kompileras till Cascading Style Sheets (CSS)
* Sass-kompilator behöver instaleras
* Ett exempel är `node-sass` från NodeJs-biblioteken
* Filtyp: .sass, .scss

## Visual Studio Code
* Skapa mappen `css`
* Skapa mappen `scss` och filen `style.scss` i mappen
* Öppna Integrerade terminalfönstret i VS Code
* Slå `npm ini -y` för att skapa package.json
* Slå `npm i node-sass` för att instrallera paketet node-sass
* Redigera scripts-objektet i package.json enligt följande...

`"sass": "node-sass -w scss/ -o css/"` //watch folder, output folder

* Starta därefter scriptet med `npm run sass`
* Klart

## Testa
* Redigera filen main.scss enligt följande...

```
$primary: #428bca;

body {
    background-color: $primary;
}
```

* Spara
