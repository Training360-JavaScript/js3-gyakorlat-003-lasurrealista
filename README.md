# Dátumok

## NAGYON FONTOS!!!
- A könnyebb tesztelhetőség érdekében az elkészített függvényeket és változókat 
exportálni kell!
- Függvények esetén egy példa:
```javascript
export default objectsMerge;
```
- Változók esetén egy példa:
```javascript
export {
  firstName,
  lastName,
  job,
};
```

## 1. Feladat
- Fájl: `solutions/app.js`
- Export: a setCookie és a cookieHandler.
- Az előző storage modulban lévő 2 file -t mozgasd át ide és exportáld ki 
a következőek szerint:
- a setCookie default export legyen
- a cookieHandler egy export objektumon belül legyen
- az app.js -ben mind a kettőt importáld be és exportáld ki egy közös 
objektumban.
