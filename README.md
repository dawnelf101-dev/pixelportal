<img width="2172" height="724" alt="banner" src="https://github.com/user-attachments/assets/aab6658f-3543-4e93-88ca-45d8bcacb1e9" />
# PIXELPORT - Bedrock Server Connector (PS5 / Xbox)

Verbinde deine Konsole direkt mit beliebigen externen Bedrock-Servern – ganz ohne DNS-Änderungen oder komplizierte Einstellungen auf der Konsole.

---

## ⚡ Was die App macht

1. **Server-IP + Port eintragen:** Beliebig viele Server abspeichern (auch externe IPs).
2. **Microsoft Account Login abwarten:** Warten, bis der eigene Microsoft-Account im Hauptmenü von Minecraft geladen ist.
3. **"Start" drücken:** Die App öffnet den lokalen Port `19132` auf dem Smartphone.
4. **Im Spiel finden:** Die PS5/Xbox erkennt die App automatisch im Minecraft-Menü unter **Spielen → Welten** ganz oben als ersten Eintrag.
5. **Verbinden:** Die Konsole verbindet sich mit dem Smartphone, welches ein *Transfer Packet* mit der Ziel-IP sendet.
6. **Direktverbindung:** Die Konsole baut die Verbindung **DIREKT** zum Ziel-Server auf.
7. **Fertig:** Die App kann danach geschlossen werden — die Serververbindung bleibt bestehen.

> **Vorteil:** Keine DNS-Änderung. Keine Konsoleneinstellungen. Funktioniert rein über das lokale WLAN.

---

## ⚙️ Voraussetzungen

* **Gleiches Netzwerk:** Android-Handy und PS5/Xbox müssen im selben WLAN sein.
* **Kein VPN:** Das Handy darf **keine aktive VPN-Verbindung** installiert oder aktiviert haben (da VPN den lokalen LAN-Broadcast blockieren kann).
* **Android-Version:** Android 8.0 (API Level 26) oder neuer.
* **Minecraft-Einstellung:** In den Minecraft-Einstellungen muss die Option **"Sichtbar für LAN-Spieler"** aktiviert sein (`AN`).

---

## 🔐 Berechtigungen auf deinem Android OS

Damit PIXELPORT reibungslos funktioniert, benötigt die App folgende System-Berechtigungen:

### 📌 Startbildschirm-Verknüpfungen & Widgets
* **Favoriten-Funktion:** Über das **Stern-Symbol** kannst du deine Lieblingsserver zu den Favoriten hinzufügen. Diese werden in der App immer ganz oben angeordnet.
* **Server-Widget:** Du kannst dir ein Widget auf deinen Hauptbildschirm legen. Dort werden deine Lieblingsserver mit der aktuellen Anzahl der Online-Spieler angezeigt.

### 🔔 Benachrichtigungen & Hintergrundbetrieb
* **Stabile Verbindung:** Ohne diese Berechtigung kann das Android-System die App im Hintergrund beenden.
* **Unterbrechungsfreier Transfer:** Der Hintergrunddienst garantiert, dass die LAN-Verbindung stabil bleibt, sobald du zu einer anderen App auf deinem Smartphone wechselst oder den Bildschirm sperrst, bis der Server-Transfer abgeschlossen ist.

---

## 🤖 Hinweis zur Entwicklung & Distribution

Diese App wurde mit Unterstützung von KI entwickelt. Es wurde im höchsten Maße darauf geachtet, dass die gesamte App sauber ist und keinen Schaden verursachen kann.

Die App wird von mir selbst genutzt und auf dem aktuellen Stand gehalten.

* **Keine Premium-Funktionen:** Keine versteckten Kosten wie bei allen anderen Connect-Apps.
* **Unbegrenzt:** Fügt so viele Server hinzu, wie ihr braucht!
* **Feedback willkommen:** Es werden sicherlich mit der Zeit weitere Funktionen hinzukommen. Wichtig ist euer Feedback.

> **Wichtiger Hinweis zur Veröffentlichung & Nutzung:**  
> Die App wird ausschließlich hier auf GitHub veröffentlicht – nicht im Google Play Store oder anderen App-Stores. Jegliche Weiterverbreitung oder Veröffentlichung auf anderen Plattformen ist nicht gestattet. Das hat unter anderem den Grund, dass ich keine unangebrachte Werbung in der App haben möchte. Die App soll auch für Kinder sicher nutzbar sein und kommt garantiert ohne versteckte Berechtigungen aus.

<img width="1776" height="592" alt="ppdownload" src="https://github.com/user-attachments/assets/77ca1664-557c-4a6b-8bb4-11d7a83ee2d7" />
# 📱 Pixelportal – Installationsanleitung (Android)

Da **Pixelportal** als direkte APK-Datei über GitHub bereitgestellt wird, stuft Android die Anwendung beim ersten Installieren als *"unbekannte Quelle"* ein. Das ist ein ganz normaler Schutzmechanismus des Betriebssystems für Apps, die nicht direkt aus dem Google Play Store bezogen werden.

Folge dieser Anleitung, um **Pixelportal** sicher auf deinem Android-Gerät zu installieren:

---

### 1. APK herunterladen
1. Lade die neueste Datei **`Pixelportal.apk`** aus dem [Release-Bereich](../../releases) herunter.
2. Tippe nach dem Download in der Benachrichtigungsleiste auf die Datei oder öffne sie über deinen **Dateimanager** / **Browser**.

---

### 2. Installation aus unbekannten Quellen zulassen
Beim ersten Versuch blockiert Android die Installation automatisch.

1. Tippe im eingeblendeten Fenster auf **Einstellungen**.
2. Aktiviere den Schalter **"Dieser Quelle vertrauen"** (oder *"Apps aus dieser Quelle zulassen"*).
3. Tippe oben links auf den **Zurück-Pfeil**, um zum Installationsmenü zurückzukehren.

---

### 3. Sicherheitshinweis & Bestätigung (Herstellerspezifisch)
Je nach Herstellerschnittstelle deines Smartphones (z. B. Xiaomi oder Samsung) erscheinen nun zusätzliche Bestätigungsdialoge:

* **Xiaomi / Redmi / POCO (MIUI & HyperOS):**
  1. Es erscheint eine Warnmeldung (*"Gefahr / Unbekannte Apps"*).
  2. Warte den **10-Sekunden-Timer** ab.
  3. Setze das Häkchen bei *"Ich bin mir der eventuellen Risiken bewusst..."*.
  4. Tippe auf **OK**.

* **Samsung (One UI):**
  1. Falls der *Auto Blocker* aktiv ist, fordert das System eine Bestätigung zum einmaligen Sideloading an.
  2. Bestätige die Abfrage, um fortzufahren.

---

### 4. Automatische Sicherheitsprüfung
Vor der eigentlichen Freigabe wird die Datei automatisch auf Schadcode geprüft:

1. **Google Play Protect** und der integrierte **Virenscanner deines Herstellers** scannen die APK-Datei.
2. Sobald die Überprüfung abgeschlossen ist (*"Keine Bedrohungen gefunden"*), tippe auf **Installieren**.

---

### 5. Fertigstellen
Nach erfolgreicher Installation tippe auf **Öffnen**, um **Pixelportal** zu starten.

---

> 🔒 **Sicherheitshinweis:** Bei Pixelportal handelt es sich um eine eigenständig entwickelte Anwendung. Die Warnmeldungen von Android sind Standard-Sicherheitshinweise des Betriebssystems für alle manuell installierten Anwendungen.
