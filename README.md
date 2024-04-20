# USB Stick Reset auf Kali Linux

Dieses Repository bietet eine Anleitung zum Zurücksetzen eines USB-Sticks auf den Werkszustand unter Kali Linux. Dies ist nützlich, wenn der Stick zuvor als bootfähiges Laufwerk oder für andere spezielle Zwecke verwendet wurde.

## Voraussetzungen

Stellen Sie sicher, dass Sie `sudo`-Rechte haben, da einige Befehle administrative Privilegien erfordern.

## Anleitung

Folgen Sie diesen Schritten, um Ihren USB-Stick zurückzusetzen:

### 1. USB-Stick anschließen

Schließen Sie Ihren USB-Stick an Ihren Computer an.

### 2. Terminal öffnen

Öffnen Sie ein Terminalfenster durch Klicken auf das Terminalsymbol oder Drücken von `Ctrl + Alt + T`.

### 3. USB-Stick identifizieren

Verwenden Sie den Befehl `lsblk` oder `fdisk -l`, um Ihren USB-Stick zu identifizieren. Suchen Sie nach der entsprechenden Größe und dem Typ (normalerweise `/dev/sdb` oder `/dev/sdc`).

```bash
sudo fdisk -l
