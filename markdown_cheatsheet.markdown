# Markdown sintaksa

## Headeri
----------
H1 underlined sa =====,
H2 underlined sa --------------

### Ovo je  H3

###### Ovo je H6

## Citiranje
------------
Blok citata pocinje sa > na pocetku paragrafa (ili sa > na pocetku svake linije).

> What's up with it, vanilla face? Me and my homie Azamat just parked our slab outside. We're looking for somewhere to post up our black asses for the night. So, uh, bang bang, skeet skeet, nigga. Just a couple of pimps, no hoes.

## Liste
-------

Neuredjena lista - koristi se *

* element1
* element2

Uredjena lista - bilo koji broj pracen tackom. Da pisanje godine ne bi triggerovalo uredjenu listu tacka nakon godine se eskejpuje sa \.

1. element1
1. element2
1. element3

## Code blokovi
---------------
Blok koda je svaki blok cije su linije indentovane za 4 space-a.

    Code block
    Code block line 2


Primer pytohn koda

    ```python
    print('You get syntax highlighting...')
    print('...if you include the language name')
    ```    
Primer diff-a

    ```diff
    - This line got removed
    + This line got added
    ```

Horizontal rule <hr/> moze da napravi sa 3 \*, - ili _ karaktera. Izmedju njih moze biti space.

### Italic, bold, spanovi i urlovi..
---
*Emphasize* sa '\*', a **strong** sa '\*\*'.
~~Strikethrough~~ sa dve tilde(~).

U tekstu, kod se citira sa backtickom (\`).
Npr. Please don't use `<blink>` tag.


Ovo je [primer](http://google.com/ "Google") linka.

[Ovaj link](http://google.com/) nema title.

Automatski link:
<http://google.com/>

This is [primer] [Google] reference linka.

[Google]: http://google.com/  "opcioni Title"
