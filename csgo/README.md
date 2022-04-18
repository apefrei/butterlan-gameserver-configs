# CS:GO Server

## ToDos
- Discovery im LAN
- Config schreiben
- Config kopieren, mehrere Instanzen erstellen
- ESL Configs verschieben nach `serverfiles/csgo/cfg` und autoladen
- Get5 installieren

## GSM Configs
Config Location `/home/csgoserver/lgsm/config-lgsm/csgoserver/csgoserver{-XX}.cfg`

### Beispielconfig
```
gslt="2D8251470A7B560B7BE61CD9AA7A3B92"
port="27015"
sourcetvport="27020"
clientport="27005"
```

### Mehrere Instanzen erstellen mit LinuxGSM
1. `su csgoserver`
2. `./linuxgsm.sh csgoserver` (entsprechend Oft wie viele Instanzen man will)
3. Configs kopieren mit angepassten Ports nach `/home/csgoserver/lgsm/config-lgsm/csgoserver/csgoserver{-XX}.cfg`
4. Starten mit `./csgoserver{-XX} start`
