# EINDOPDRACHT LEMONLIVE #
*Eindopdracht voor het vak HTML-CSS Advanced*
---

##Opgave##
De opdracht is simpel: bouw een webpagina naar keuze na in HTML en CSS. De pagina moet uiteraard voldoende uitdagend zijn qua lay-out en animaties. Het al dan niet gebruiken van een CSS-Framework is vrij te kiezen.

##Invulling##
Ik heb gekozen voor de homepage van [Lemonlive](https://lemonlive.be/) en framework [Bootstrap](https://getbootstrap.com/).

##Highlights
###Moeilijkste code ~~tot nu toe~~ in opmaak:
```
    @keyframes marker {
        from {background-position: 0;}
        to {background-position: -100%;}
    }
    .purpleMarker {
        background-image: linear-gradient(to right, transparent 50%, var(--kleur3) 50%);
        background-size: 200%;
        animation-name: marker;
        animation-duration: 2s;
        animation-delay: 2s; /*Hoe ervoor zorgen dat de animatie kort na laden pg begint, maar met een groter interval herhaalt?*/
        /* animation-iteration-count: infinite; */ 
        animation-fill-mode: forwards;
    }

```
###More to come
==Watch this space!==

##To do
-[x] Project initialiseren: aanmaak bestanden, links leggen, ...
-[x] Afbeeldignen downloaden (bedankt Dominique)
-[x] Navbar namaken
-[ ] Layout namaken
-[ ] Animaties toevoegen
-[ ] Puntjes op de i: zie comments in HTML en CSS

---

##Nog wat markdown:
1. **bold**
2. > blocquote die iets te kort is
   > maar je ziet wat de bedoeling is
3. 😄 *Raar dat deze er in zitten, maar ach.*
