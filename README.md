# Vertikalwindkraftanlage
 
Dieses Tool soll die Funktionsweise eines H-Darrieus-Rotors mit 3 Blättern visualisieren. Die verwendeten Werte für die Windgeschwindigkeit etc. sind dabei willkürlich gewählt und dienen nur einer qualitativen Betrachtung der auftretenden Kräfte. Inspiration für dieses Tool war das YouTube-Video von Jörn Loviscach (https://youtu.be/q9HUGboOV2s).

Obacht, folgende Dinge sollten bei der Nutzung des Tools beachtet werden:

  + Der Auftriebsbeiwert des Profils ist proportional zum Anströmwinkel. Die Werte für den Auftrieb sind deswegen nur für kleine Anströmwinkel physikalisch korrekt.
    Aus diesem Grund sollte eine Schnelllaufzahl > 3 eingestellt werden, um die Anströmwinkel klein zu halten. Das Anlaufen der Anlage aus dem Stillstand kann deswegen
    nicht dargestellt werden.
  + Es werden (bisher) keine Widerstände berücksichtigt. Die Tangentialkräfte sind also lediglich Auftriebskräfte.
  + Die Blätter sind masselos -> keine Zentrifugalkräfte. Die Radialkräfte sind also lediglich Auftriebskräfte.

Wer möchte darf das Tool gerne selber nutzen oder sogar erweitern/verbessern. Es gibt noch zahlreiche Möglichkeiten das Tool zu verbessern. Sei es die Berücksichtigung von Widerständen, eine bessere Implementierung des Auftriebs mit Stall, sodass auch große Anströmwinkel dargestellt werden können und dadurch der Anfahrvorgang betrachtet werden kann. Die Krönung wäre dann die Verknüpfung der Rotationsgeschwindigkeit mit der Windgeschwindigkeit (Windgeschwindigkeit -> Auftrieb -> antreibendes Moment -> Rotationsgeschwindigkeit). Für Hinweise auf Fehler bin ich natürlich sehr dankbar.

Viel Spaß!
