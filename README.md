-----------------------------------------------------
***An English version is in preparation.***  <br>

                  And here is an english version of CoopOS with stackchange.<br>
                  Slower, but even easier to use:
                  
                  This makes tasks out of your functions:

                  void setup() {
                    Serial.begin(500000);
                    StackInit();
                    TaskInit("T1", Task1, 90, 100,   0, READY);
                    TaskInit("T2", Task2, 90, 100,   0, READY);
                    StartMultiTasking();
                  }

>>>>>>>           https://github.com/MacLeod-D/Arduino-Multitasking-CoopOS

-----------------------------------------------------



Eine englische Version ist in Vorbereitung.


***Schnelles und mächtiges kooperatives Multitasking für Arduino IDE   
              Kurs auf Deutsch mit allen Sourcen***   
              
                      **CoopOS**
                      
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

Achtung: 

https://github.com/MacLeod-D/Arduino-Multitasking-CoopOS
