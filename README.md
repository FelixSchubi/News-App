# News App Case Study    <img src="https://travis-ci.org/FelixSchubi/News-App.svg?branch=master" >

        //     - https://www.webcomponents.org/element/vaadin/vaadin-upload/demo/demo/index.html



    - https://www.polymer-project.org/2.0/toolbox/case-study
- Applikation ausdünnen!
- Einbauen einer Todo/Bild Funktion
- Einarbeitung in die Struktur
- "Mixin's" ? <br/>
    -> https://news-docs.polymer-project.org/docs/using.html    <br/>
    -> https://meowni.ca/posts/polymer-2-cheatsheet/    <br/><br/><br/><br/>
    
<h1> Aktueller Stand ist <b><a href="https://github.com/FelixSchubi/News-App">hier</a></b> zu finden. </h1>
 Neue Kategorie mit dem Name "observations" wurde erstellt.<br/>
 - _updateDocumentTitle() Funktion wurde bearbeitet um den richtigen document Title zu erhalten!<br/>
 - news-list-featured-item.html muss verändert werden (evtl. mit Mixin's Arbeiten?)<br/>
 - App-Route so verändern, dass "animal" bei "observations" wegfällt<br/>
<br/>

## Introduction to Structured Data
<br/>
-> https://search.google.com/structured-data/testing-tool

https://developers.google.com/search/docs/guides/intro-structured-data<br/>
 -> zum besseren Versändnis

Test zum Teilen der Website auf "Google +"
 - https://developers.google.com/+/web/share/
 
 
 # To Fix
 
 
 # Fixed
 - Der Auswahl Container (wenn man runterscrollt) lädt etwas falsches beim Klick auf "Beobachtungen"
 
 _computeURI(categoryName) {
        if (categoryName === "observations") {
          return '/' + 'observations/observations';
        }
        else {
          return '/list/' + categoryName;
        }
      }
 
 
 
 
 
 
 
 
 

<br/><br/><br/><br/><br/><br/><br/><br/><br/>
# Todo

- Notes Overlay von Weather-PWA in Polymer bauen
  - Welche Form von IndexedDB verwenden?
 
 - https://todopoly97.firebaseapp.com/  !!
 - https://codelabs.developers.google.com/codelabs/polymer-firebase-pwa/index.html?index=..%2F..%2Findex#25
  
  
 ### WebComponents
 - https://www.webcomponents.org/
    - https://www.webcomponents.org/element/google/uniflow-polymer Mit Indexeddb verwenden geht nicht!!
  
### App Storage
  -> https://www.webcomponents.org/element/PolymerElements/app-storage

