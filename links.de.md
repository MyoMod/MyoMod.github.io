---
layout: page
title: Links
lang: de
#background_style: bg-info
background_image: url('assets/img/backgrounds/image-from-rawpixel-id-1199650-jpeg.jpg')
# Add a link to the the top menu
menus:
  header:
    title: Links
    weight: 2

sections:
- type: address.html
  section_id: address

  background_style: bg-dark
  title: Sie sind willkommen!
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2610.2!2d9.67!3d50.55!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x123!2sFulda!5e0!3m2!1sde!2sde!4v1583193778570!5m2!1sde!2sde
  address:
    title: Adresse
    text: >
      Blücherstr. 7,<br/>
      36037 Fulda,<br/>
      Deutschland
  phone:
    title: Telefon
    text: >
      +49 (0) 661 555-014<br/>
      +49 (0) 661 555-015
- type: paragraph.html
  section_id: help
  title: Hilfe erhalten!
  text: >+
    Hier finden Sie eine Schnellreferenz und Demonstration der Markdown-Syntax:

    * [Markdown-Syntax hier](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

    * [John Grubers ursprüngliche Spezifikation](http://daringfireball.net/projects/markdown/).

    * [Github-flavored Markdown Info-Seite](http://github.github.com/github-flavored-markdown/).

- type: paragraph.html
  section_id: more-to-come
  title: Kein HTML!
#  background_style: bg-info
#  text_style: text-left text-white
  actions:
   - title: Markdown macht Spaß!
     class: btn-info
     url: '#'
  text: >+
    ### Typografische Ersetzungen

    Aktivieren Sie die Typographer-Option, um das Ergebnis zu sehen.

    (c) (C) (r) (R) (tm) (TM) (p) (P) +-

    test.. test... test..... test?..... test!....

    !!!!!! ???? ,,  -- ---

    "Smartypants, doppelte Anführungszeichen" und 'einfache Anführungszeichen'


    ### Hervorhebung

    **Das ist fetter Text**

    __Das ist fetter Text__

    *Das ist kursiver Text*

    _Das ist kursiver Text_

    ~~Durchgestrichen~~


    ### Blockzitate

    > Blockzitate können auch verschachtelt werden...
    >> ...durch die Verwendung zusätzlicher Größer-als-Zeichen direkt nebeneinander...
    > > > ...oder mit Leerzeichen zwischen den Pfeilen.

    ### Listen

    Ungeordnet

    + Erstellen Sie eine Liste, indem Sie eine Zeile mit `+`, `-`, oder `*` beginnen
    + Unterlisten werden durch Einrücken um 2 Leerzeichen erstellt:
    - Markierungszeichen-Wechsel erzwingt neuen Listenbeginn:
      * Ac tristique libero volutpat at
      + Facilisis in pretium nisl aliquet
      - Nulla volutpat aliquam velit
    + Sehr einfach!

    Geordnet

    1. Lorem ipsum dolor sit amet
    2. Consectetur adipiscing elit
    3. Integer molestie lorem at massa

---
Hier steht etwas roher Markdown-Inhalt.
