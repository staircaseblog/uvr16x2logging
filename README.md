# uvr16x2logging

I experimented with canopen library for python from Christian Sandberg (https://github.com/christiansandberg/canopen). This library is great to use and easy to package. Kudos to Christian. I almost converted the C/Cpp in a day including basic logging for the uvr16x2.

There is some work remaining to interprete the outputs of the uvr16x2 the right way. Not all eventualities are covered. I am happy if you could give learnings back.

BTW: This code logs the UVR 1611 too. The names of the I/O are not yet in. 

(german)

Ich habe mir die python canopen von Christian Sandberg (https://github.com/christiansandberg/canopen) genauer angesehen und damit experimentiert. Sie ist sehr sauber und das Fehlerverhalten ohne unerwartete Überaschungen. Damit wird der UVR Logging Code für CAN endlich portabel und leicht transportierbar.

Python, die Pakete mit pip laden und losgehts.

Die Auswertung der Rückgaben sind noch nicht ganz vollständing. Falls Ihr hier weitere Erfahrung mit der Dekodierung der Felder sammelt wäre ein commit oder Rückmeldung top.

Unter staircaseblog.blogspot.de finden sich Infos zum Anschluss von CAN Interfaces an den Raspberry.
