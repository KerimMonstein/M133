# Lern-Bericht
Kerim Monstein

## Einleitung
Dieser Lernbericht umfasst das Modul 133. Darin geht es um Webentwicklung mit **JSF**.

## Was habe ich gelernt?

Ich habe gelernt, wie man in JSF Verlinkungen erstellt. 

## Beschreibung
Anders als in gewöhnlichem *html* verwendet man für Verlinkungen keine ```<a>```-Tags, sondern ```<h:commandLink>``` Tags. 
Um diese zu verwenden, muss man den Codeblock mit <h:form></h:form> Tags umgeben und die notwendige Bibliothek importieren. <br>
Anstatt ```<a href="link">Klick</a>``` schreibt man nun ```<h:commandLink action="link"/>```. Den Link, den man sonst in das *href* schreibt, fügt man bei JSF bei action ein. Damit man den Link auch anklicken kann, gibt man ihm eine Value oder man umschliesst z.B. einen  ```<h:graphicImage/>``` Tag.

```java
  <h:commandLink value="Gehe zu Seite 2" action="Seite2.xhtml"/> 
```
![link](https://user-images.githubusercontent.com/69577029/186689637-0a5baaa4-4d61-49c8-8866-b5e213c0ccfb.gif)

## Verifikation

Im Bild zeige ich, wie man mit dem Link auf eine andere Seite kommt, im Code wie man es einbindet und im Text erkläre ich wie man einen solchen Link erstellt und verwendet.

# Reflektion zum Arbeitsprozess

👍 Bisher bin ich in diesem Modul gut vorangekommen. Dank den höhenverstellbaren Tischen im Klassenzimmer, konnte ich zur Abwechslung angenehmer am Tisch sitzen. Mit den Aufträgen komme ich weitgehend ohne grössere Probleme voran.
👎 Bei der Arbeit heute hatte ich vermehrt Kopfschmerzen, was mich in meiner Konzentration gestört hat. 

**VBV**: Ich werde zukünftig darauf achten, meine Pausen weniger am Bildschirm zu verbringen, mehr Wasser zu trinken und mehr frische Luft zu atmen.
