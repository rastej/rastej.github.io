---
layout: post
title: "Správa k zadaniu 3"
author: "Rastislav Urbán"
date: 2018-05-02
---
Zadanie 3: XML prezentácia

Analyzujte možnosti zápisu jednoduchej prezentácie v jazyku XML. Identifikujte základné súčasti prezentácie a navrhnite XML elementy pre ich označkovanie (metadátové, štrukturálne, inline). Dbajte na znovupoužiteľnosť a vyvarujte sa redundancií. Návrh elementov zrealizujte opísaním typu dokumentu pomocou vybraného jazyka (DTD, XSD, RELAX NG) spolu s vysvetlením účelu jednotlivých elementov. Vo vami navhrnutom jazyku vytvorte ukážkovú prezentáciu, ktorá bude demonštrovať možnosti tvorby prezentácií podľa definície typu dokumentu.
Navrhnite a vytvorte XSLT šablóny pre konverziu prezentácie z XML do XHTML+CSS a pre konverziu prezentácie z XML do PDF. Klaďte dôraz na znovupoužitie jednotlivých šablon pre viaceré výstupné formáty. Umožnite zadávanie parametrov transformácií.
Súčasťou požiadaviek na zadanie je vytvorenie správy o zadaní 3, v ktorej zdokumentujete splenie jednotlivých bodov zadania. Správa bude súčasťou vašej stránky o Webovom publikovaní na GitHube.

Prezentácia:
    »Prezentácia bola napísaná vo formáte xml
    
    »Na začiatku súboru je definované DTD, ktoré určuje štruktúru elementov
    
    »Na transformáciu som použil Saxon 9.1.0.8 a XEP, taký istý ako pri predchádzajúcom zadaní
    
    »Obsahuje slajdy o Porsche 911
    
Transformácie: 
    »XML do PDF
      Najprv som transformoval dáta na formátované objekty pomocou Saxonu a potom pomocou XEP som tieto formátované objekty transformoval na PDF
      
    »XML do XHTML
      Pomocou Saxonu, vystupom je viacej priesvitiek medzi ktorymi sa da preklikavat. 
