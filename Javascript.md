# Javascript bevezető (XII.A)
## A HTML DOM:
Egy szabványos objektum modell, egy programozási felület a HTML számára

![DOM model](https://www.w3schools.com/js/pic_htmltree.gif)

### Meghatározza:
- A HTML elemeket objektumként 
- A HTML elemek tulajds
- A HTML elemeket elérési módszereit
- A HTML eseményeket

## A JavaScriptről:
- A világ egyik legelterjedtebb programozási nyelve
- Inkább webprogramozási nyelv
- Könnyen megtanulható, mert hasonlít (alapja) a C nyelvekhez
- A weboldalak viselkedését meghatározó nyelv
- Verziói: ES1, ES2, ES6, ES2022

### Beépítés a weboldalban:
#### A HTML kódba:
```html
<script>...</script>
```
> ##### Head:
> Az oldal generálása előtt fut le
> ##### Body:
>Akkor generálódik, amikor sorra kerül
#### Külön állományban:
Külön **script.js** fájlban, majd HTML-be rakva:
```html
<script src="script.js"></script>
```
## HTML elemek elérése:
### Azonosító (ID) szerint:
```js
document.getElementById("azonosító");
```
### Cimkenév (name) szerint:
```js
document.getElementsByTagName("cimkenév");
```
### Osztálynév (class) szerint:
```js
document.getElementsByClassName("osztálynév");
```
### CSS választók (selector) szerint:
```js
document.querySelectorAll("selector");
```
### Objektumgyűjtemény (form) szerint:
```js
document.forms["űrlap"];
```
## Információ megjelenítése (Output):
1. HTML elembe (inner HTML)
```js
document.getElementById("tartalom").innerHTML = "Hello World!";
```
2. Kiírás paranccsal
```js
document.write("Hello World!");
```
3. Figyelmeztető ablakban
```js
window.alert("Hello World!");
```
4. Böngésző konzolba
```js
console.log("Hello World!");
```