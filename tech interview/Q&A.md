# pytania
# HTML
## semantyczny HTML
Semantyczny HTML odnosi się zatem do tworzenia dokumentu HTML, w którym znaczniki poprawnie opisują znaczenie i funkcję fragmentu tekstu, który zawierają.

https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Sectioning_content

[znaczniki semantyczne](http://www.kurshtml.edu.pl/html/kod_poprawny_semantycznie,tekst.html)

article, aside, details, figcaption, figure, footer, header, main, mark, nav, section, summary, time

## data & time
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/data
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

# CSS
## float
* right/ left/ centre
* display: none vs. visibility: hidden
## Bootstrap (modal)
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

# JS
## document.cookie
## .this
## .splice .reverse i .join
## Klasy / ‘class’
http://kursjs.pl/kurs/es6/class.php
w JS tworzenie klas nie istnieje, a cały mechanizm posługuje się konstruktorami i działa na prototypach.
# New Promise
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
https://developers.google.com/web/fundamentals/primers/promises
http://www.datchley.name/es6-promises/

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
Wartość zmiennej niezdeklarowanej za pomocą var. Czy mozna sie do niej odwołać potem czy garbageCollector ją usuwa?
stosowanie określonego nazewnictwa klas zgodnie z metodyką BEM czy OOCSS
Opanowanie funkcji wyższego rzędu, IIFE, asynchroniczności, promises, closures, dziedziczenia prototypowego, event bubble, hoistingu, jak działa „this” czy „strict mode”,
