# pytania
# HTML
## semantyczny HTML
Semantyczny HTML odnosi się zatem do tworzenia dokumentu HTML, w którym znaczniki poprawnie opisują znaczenie i funkcję fragmentu tekstu, który zawierają.

https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Sectioning_content

[znaczniki semantyczne](http://www.kurshtml.edu.pl/html/kod_poprawny_semantycznie,tekst.html)

article, aside, details, figcaption, figure, footer, header, main, mark, nav, section, summary, time

## data & time
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/data
* custom data attribute
* helps extend the info that HTML element can communicate to a program or script
* i.e. 'data-something-awesome="123456789"' then target it by '_____.dataset.somethingAwesome'
* [nice explenation](https://www.youtube.com/watch?v=3r7dkLersKA)

https://developer.mozilla.org/en-US/docs/Web/API/HTMLDataElement
## optymalizacja strony html
[Porady odnośnie tworzenia szybko ładujących się stron HTML](https://developer.mozilla.org/pl/docs/Porady_odno%C5%9Bnie_tworzenia_szybko_%C5%82aduj%C4%85cych_si%C4%99_stron_HTML)
http://www.websiteoptimization.com/
* Zmniejsz rozmiar strony
* Zminimalizuj liczbę plików
* Zmniejsz liczbę wywołań domen
* Przechowuj w cache wielokrotnie wykorzystywane treści
* Optymalnie porządkuj komponenty strony
* Zmniejsz liczbę skryptów wpisanych
* Używaj nowoczesnego CSS i poprawnej składni znaczników
* Segmentuj zawartość
* Określaj rozmiary obrazków i tabel
* Mądrze dobieraj wymagania agenta użytkownika
* .gzip

## referencje do HTML

* document.querySelector
* element.querySelector
* element.querySelectorAll()
* document.querySelectorAll()
* getElementById()
* getElementsByClassName()
* getElementsByName()
* getElementsByTagName()
* getElementsByTagNameNS()
* getSelection()
---
# CSS
## float, clear 
[css tricks - float](https://css-tricks.com/all-about-floats/)
* right, left, inherit, none

* display: none vs visibility: hidden
  *display: none - removes element from page (stays in DOM)
  *visibility: hidden - removes element from view, leaves the sapce
## Bootstrap (modal)
https://v4-alpha.getbootstrap.com/layout/overview/

[modale](https://www.nafrontendzie.pl/okna-modalne-bootstrap-wtyczka-jquery)
## pseudoklasy
* A CSS pseudo-class is a keyword preceded by a colon (:) that is added on to the end of selectors to specify that you want to style the selected elements only when they are in certain state.

:active
:any
:checked
:default
:dir()
:disabled
:empty
:enabled
:first
:first-child
:first-of-type
:fullscreen
:focus
:focus-within
:hover
:indeterminate
:in-range
:invalid
:lang()
:last-child
:last-of-type
:left
:link
:not()
:nth-child()
:nth-last-child()
:nth-last-of-type()
:nth-of-type()
:only-child
:only-of-type
:optional
:out-of-range
:read-only
:read-write
:required
:right
:root
:scope
:target
:valid
:visited

## @import
* used to import style rules from other style sheets. 
* These rules must precede all other types of rules, except @charset rules; 
* as it is not a nested statement, @import cannot be used inside conditional group at-rules.

## [metodyka BEM](https://www.nafrontendzie.pl/metodyki-css-2-bem)
---
# JS
## document.cookie
## .this
[article](https://www.nafrontendzie.pl/slowo-kluczowe-this-javascript)
* referencja do obiektu, który wywołał daną funkcję lub...
* w zakresie globalnym “this” jest po prostu referencją do obiektu ‘window’
## .splice .reverse i .join
## Klasy / ‘class’
http://kursjs.pl/kurs/es6/class.php
w JS tworzenie klas nie istnieje, a cały mechanizm posługuje się konstruktorami i działa na prototypach.
## New Promise
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

https://developers.google.com/web/fundamentals/primers/promises

http://www.datchley.name/es6-promises/
# Node.js
* open-source, cross-platform JavaScript run-time environment for executing JavaScript code server-side
# Webpack
* open-source JavaScript module bundler. Webpack takes modules with dependencies and generates static assets representing those modules.
# React
Cykl życia komponentu https://codepen.io/tgoyer/details/ONNJWE

# HTTP / przeglądarka
## localStorage
Metody
* .setItem
* .deleteItem
* .removeItem

Dostęp z różnych domen - nie można z różnych aplikacji

Przechowywane dane w formacie: {key:___ value:___}

## sessionStorage

# REST API
## metody
*
## CORS - Cross-Origin Resource Sharing
https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS
[XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
[Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)


# GIT
Jakie czynności wykonuję po otrzymaniu zadania w projekcie
---

#inne tematy do przerobienia

Wartość zmiennej niezdeklarowanej za pomocą var. Czy mozna sie do niej odwołać potem czy garbageCollector ją usuwa?



Opanowanie funkcji wyższego rzędu, IIFE, asynchroniczności, promises, closures, dziedziczenia prototypowego, event bubble, hoistingu, jak działa „this” czy „strict mode”,

testy jednostkowe

SOLID
wzorce projektowe
- https://stormit.pl/pytania-rekrutacyjne-javascript/
