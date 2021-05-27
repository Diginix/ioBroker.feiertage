![Logo](../../admin/feiertage.png)
# ioBroker.feiertage

## Beschreibung
Dieser Adapter liefert das Datum, die Dauer bis zu diesem Datum in Tagen und den Namen des nächsten deutschen Feiertages und gibt Auskunft, ob heute, morgen oder übermorgen ein Feiertag ist.

Brückentage, die jährlich fest am Freitag nach einem Feiertag stattfinden sind auswählbar.

##  Datenpunkte
![alt text](img/DatapointsScreenshot.jpg "Screenshot Datenpunkte")

## Einstellungen
Feiertage, die bei der Befüllung der Datenpunkte berücksichtigt werden sollen, können ausgewählt werden.

![alt text](img/SettingScreenshot.jpg "Screenshot Einstellungen")

## Aktivierung
Der Adapter startet jeden Tag um Mitternacht. Ein häufigeres Starten ist nicht erforderlich.

## Sonstiges
Es können natürlich weitere Instanzen des Adapters mit abweichenden Feiertagsauswahlen angelegt werden. So kann man z.B. die unterschiedlichen Anforderungen bei Feiertagsarbeitern abdecken. Eine Beispielanwendung ist der [Shuttercontrol Adapter](https://github.com/simatec/ioBroker.shuttercontrol/blob/master/docs/de/shuttercontrol.md#extra-einstellungen)
