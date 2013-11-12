# 5. Ressourcen

Um die Reichweite seiner App zu erhöhen, ist man natürlich gut beraten, diese für einen großen Sprachraum auszulegen.    
Hierbei sind in erste Linie die Wortlaute in den Activities betroffen.  
In dieser App wird gezeigt, wie dies erledigt werden kann.

# Hilfestellung

Die String-Ressourcen findet Ihr unter  
&nbsp;&nbsp;&nbsp;&nbsp;**res/values/strings.xml**

Dies Ressource-Datei ist zugleich die Default-Ressource-Datei, falls für eine Lokale keine Ressource-Datei auffindbar sein sollte.  
Dies heißt in Klartext, daß der Taliban, dessen Stammessprache wir nicht abbilden können, die App bedauerlicherweise in English ansehen muß.

Ist jedoch für die im Android-Gerät eingestellte Sprache eine Ressource-Datei vorhanden, wird diese Verwendung finden.   

Fangen wir an.

Als erstes der der **app_name** angepaßt.  
Diese trägt nämlich zur Zeit noch den Namen des Projektes und diese in Deutsch.  
Also 'Ressourcen' in 'Resources' ändern. Danke!   

![Image](./readme-img/1-Resources-tagged.png)

Die Datei 'strings.xml' kann einmal als pure XML-Datei bearbeitet werden oder mehr oder minder komfortabler über 'Resources'. Zu finden am linken, unteren Rand des Editor-Fensters.

![Image](./readme-img/2-android-ressources-default-2.png)

Um nun eine eigene Ressource zu erstellen, bewegen wir uns zu 
&nbsp;&nbsp;&nbsp;&nbsp;**res/layout/activity_main.xml**
und klicken dort drauf.

Es erscheint das mittlerweile bekannte 'Graphical Layout'.  
Dort auf diese Art Weltkugel klicken und 'Add New Translation' auswählen.

![Image](./readme-img/3-new-translation.png)

Es erscheint der folgende Dialog:

![Image](./readme-img/4-new-ressource-select-lang.png)

In diesem Dialog ist als erstes die Auswahlbox 'Language' zu klicken und der gewünschte __Sprachraum__ zu wählen.  
Danach kann bei Bedarf noch eine Region ausgewählt werden.  
Im Beispiel-Fall __Language__ gleich 'Deutschland' würde dort 

![Image](./readme-img/5-new-ressource-finished.png)

![Image](./readme-img/6-select-new-de-ressource.png)

![Image](./readme-img/7-ressource-de.png)


# Was sollten wir jetzt beherrschen?

- String-Ressourcen für verschiedenlichste Sprach-Räume anlegen zu können
