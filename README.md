-----------------------------------------------------
This is the **fast** and **universal** CoopOS-version **without** stackchange  for ALL CPUs- but in **German**.

***An English version is available:      https://github.com/MacLeod-D/CoopOS-Lessons-English***  <br>

 Links:

With Stackframes (Arduino):
https://github.com/MacLeod-D/Arduino-Multitasking-CoopOS

With Stackframes and WebServer (ESP8266):
https://github.com/MacLeod-D/ESP8266-Multitasking-CoopOS 





**Dies ist die schnelle und universelle CoopOS-Version füe alle Prozessoren !**

**Schnelles und mächtiges kooperatives Multitasking für Arduino IDE   
              Kurs auf Deutsch mit allen Sourcen**   
              
# CoopOS
                      
Ein umfangreicher Kursus, der ganz simpel startet
                     
         ***Für Anfänger und Profis gleichermaßen geegnet***


Auf über 65 Seiten PDF und 8 Demo-Sourcen wird ***CoopOS***, ein Hilfsmittel für kooperatives Multitasking, sehr detailiert und auch für den Anfänger nachvollziehbar vorgestellt.   

Kooperatives Multitasking benötigt keinen eigenen Stack für jeden Task. Daher ist es so kompakt, dass es selbst auf einem AtTiny45 funktioniert!   

Da die Stackbereiche und damit die Prozessor-Register nicht umgeschaltet werden ist CoopOS extrem schnell.   

Troztzdem enthält es viele Optionen, die sonst nur bei RTOSs zu finden sind:   

while(1) {
    ...
}

taskSwitch   
taskDelay   
taskStop   
taskResume   
taskWaitSignal   
taskSetSignal (auch von Interrupt-Routinen)   
taskWaitResource   
taskFreeResource   

Es hat mich einfach geärgert, dass es modern zu sein scheint, RTOS für die heilige Kuh zu erklären, deren Ergebnisse mit   
kooperativem Multitasking nicht zu erreichen sind - denn das ist Unsinn!   

Gewiss wollte ich auf ein RTOS in embedded systems nicht verzichten  da, wo es vorhanden ist.   
Aber CoopOS ist selbst dann verfügbar, wenn der Platz sehr knapp ist - und bietet leicht die Möglichkeit von 10 Tasks,   
wo ein RTOS nicht existiert.   

Ein weiterer Vorteil ist die vollständige Unabhängigkeit vom Prozessortyp.   
Die Programme sind so sehr leicht zu übertragen.   

Und es kann ein RTOS sehr wohl gut ergänzen - insbesondere da, wo mehrere Prozessorkerne vorhanden sind.   

Die Kursteile 0-6 laufen auf jedem Prozessor - ohne Änderung - , für die die Arduino IDE verfügbar ist !   

Die beste Methode ist:   
PDF lesen - bei Aufforderung den entsprechend Kursteil in der Arduino IDE ausführen.   

Obwohl mit jedem Prozessor ausführbar erhält man besonders beeindruckende Ergebnisse mit einem ESP8266,   
auf den sich auch die Demo-Bilder beziehen.   

Es wird dringend empfohlen, einen Logic-Analyzer oder ein Oszilloskop zu benutzen. Einfachste Ausführungen   
reichen! Wer sich traut: in China gibt es sehr billige Clones ;)

***Installation:***   

Die PDF kann direkt gelesen werden.   
Die Demos sollten direkt in den Arduino-Sketches Ordner entpackt werden.   

---------------------------

    Achtung: 
    Hier ist die Version >>>MIT<< Stack-Change (jeder Task hat eigenen stack).
    Dadurch langsamer. aber noch einfacher benutzbar. Nur für AVR-Prozessoren (Aruino Uno, Nano, ...):

------------------------
https://github.com/MacLeod-D/Arduino-Multitasking-CoopOS




Ausführliche weitere Informationn:  **http://HelmutWeber.de**
