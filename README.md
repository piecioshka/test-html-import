# test-html-import

![](images/network-panel.png)

## Uwagi

 * Atrybut `async` dodany do `<link>` informuje, że plik nie będzie renderowany od razu, tylko po załadowaniu całej strony.<br />
 **Na potwierdzenie na obrazku widzimy `null` w panelu `Console`.**
 
 * Jeśli w ściąganym pliku (poprzez `<link rel-"import">` dodamy znacznik `<template>` to jego zawartość nie będzie renderowana.<br />
 **Na potwierdzenie na obrazku widzimy, że ściągają się obrazki z końcówką `200` i `400` w adresie, a `100` i `300` już nie.** 
 