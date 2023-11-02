# Funktionsweise eines FTIR-Spektrometers

## Funktionsweise ursprünglicher IR-Spektrometer

Ursprünglich wurde Licht unterschiedlicher Wellenlänge schrittweise (nm für nm) durch die Probe geschickt. Die Aufnahme eines IR-Spektrums dauerte ziemlich lange und die Probenvorbereitung war deutlich aufwendiger.

<figure><img src="../../.gitbook/assets/image (18) (1).png" alt=""><figcaption><p>Quelle: Bruker</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

## Funktionsweise neuartiger, FTIR-Spektrometer

FTIR-Spektrometer bestehen aus einer Quelle, einem Interferometer, einem Probenraum und einem Detektor. Die Quelle erzeugt die Strahlung. Diese passiert die Probe und schliesslich den Detektor.

{% embed url="http://www.ir-spektroskopie.de/spec/ftir-prinzip/index.html" %}

Bei neueren IR-Spektrometern wird ein Michelson Interferometer verwendet:

{% embed url="https://www.youtube.com/watch?v=MZw3hjRMQBw" %}

Im Zentrum des FTIR-Spektrometers steht ein Michelson-Interferometer.

Der Michelson-Interferometer

1. Teilt einen Lichtstrahl in zwei Strahlen und leitet sie zu Spiegeln
2. Führt die zwei Strahlen zusammen und leitet sie zum Detektor.

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption><p>Michelson-Interferometer</p></figcaption></figure>

Ein Spiegel ist stationär (fix) und ein zweiter Spiegel ist beweglich. Der Teiler in der Mitte lässt die Hälfte des Lichts hindurch und reflektiert die andere Hälfte. Nach Reflektion beider Strahlen an den Spiegeln werden die Strahlen kombiniert an den Detektor geleitet.

Haben die beiden Strahlen _die gleiche Distanz_ zurückgelegt, liegt eine Nullpfaddifferenz (zero path difference, ZPD) vor. Wird der bewegliche Spiegel um ein ganzzahliges Vielfaches verschoben (bspw. 2n), dann wird eine konstruktive Interferenz beim Detektor vorliegen, umgekehrt liegt bei einer Halbierung des Wegs eine destruktive Interferenz vor.

Der Spiegel bewegt sich allerdings hin und her, sodass die Intensität des Signals zwischen dem Maximum (volle konstruktive Interferenz) und dem Minimum (volle destruktive Interferenz) liegt.

Aus dem Interferenzmuster kann dann über die sogenannte Fourier-Transformation ein Spektrum erzeugt werden, das die Absorption in Abhängigkeit der Wellenlänge zeigt.

{% hint style="info" %}
Der mathematische Teil der Fourier-Transformation wird ist eher kompliziert und wird an dieser Stelle nicht behandelt. Im folgenden Video wird die Fourier-Transformation erklärt (-> Mathematik-Lehrperson für weitere Informationen fragen).
{% endhint %}

{% embed url="https://www.nanoo.tv/link/v/dggJjUNu" %}

{% embed url="https://www.youtube.com/watch?v=0e_xBwQ7znI" %}
$
{% endembed %}
