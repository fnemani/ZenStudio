# 🎮 Warzone GPC Script PRO | PS5 Edition

Dieses GPC-Skript ist speziell für **Call of Duty: Warzone auf der PlayStation 5 (DualSense-Controller)** optimiert. Es bietet fortschrittliche Movement-Mechaniken, dynamisches Anti-Recoil-Tracking über das Adapter-Display (Cronus Zen/Titan) und maximierten Aim Assist.

---

## ⚠️ Wichtige In-Game-Einstellungen

Damit das Skript fehlerfrei funktioniert, **müssen** folgende Einstellungen in Warzone vorgenommen werden:

*   **Tastenbelegung:** `Stick & Bewegung` (Stick & Move)
*   **Automatischer Sprint:** `Automatischer Taktiksprint` *(Zwingend erforderlich für das Auto-Run-Skript und flüssige Slide-Cancels!)*

---

## 🕹️ Controller Layout (PS5 DualSense)

Das Skript greift nativ in die "Stick & Bewegung"-Belegung ein und optimiert die Trigger-Reaktionszeiten:

| Taste | Aktion | Skript-Optimierung |
| :--- | :--- | :--- |
| **L2 / R2** | Zielen / Schießen | **Hair-Triggers** – reagieren sofort bei minimaler Berührung. |
| **L3** | Sprint / Movement | Taktiksprint triggert extrem früh (bereits bei 50% Stick-Ausschlag). |
| **R3** | Springen | Standard "Stick & Move"-Verhalten (Rechter Stick Klick). |
| **Kreis (O)** | Haltung | Steuert das erweiterte Slide-Cancel-System. |
| **Dreieck (Δ)**| Waffenwechsel | Steuert In-Game-Waffe **und** synchronisiert das Skript-Profil. |

---

## ⚡ Aggressive Movement Systems

Das Movement-Profil wurde komplett überarbeitet, um die Hitbox in Close-Quarter-Gunfights unberechenbar zu machen:

*   **Aggressive Slide-Cancel (Slide into 3x B-Hop):** 
    Wird im Taktiksprint die `Kreis`-Taste gedrückt, führt der Charakter einen schnellen Slide aus, bricht diesen serverseitig perfekt ab und hängt **automatisch 3 Bunny-Hops** an.
*   **Auto Strafe Jump (Camera Breaker):** 
    Befindest du dich im Gunfight (L2 + R2 gedrückt) und lässt die Ziel-Taste (`L2`) kurz los (Wechsel ins Bunny-Hops), führt das Skript automatisch einen unvorhersehbaren Strafe-Jump aus.

---

## 🎯 Aiming & Combat Utility

Der Aim Assist-Code wurde entschlackt und auf konstante, maximale Performance getrimmt:

*   **Always-On Aim Assist:** Der Rotational & Strafe Aim Assist ist beim Zielen permanent am Limit aktiv. Ein manuelles Ein- und Ausschalten ist jederzeit möglich (der aktuelle Status ist auf dem Display des Cronus Zen ersichtlich).
*   **Dynamic Anti-Recoil:** Maßgeschneidert für ein Loadout mit **Maschinenpistole (Primary)** und **Sturmgewehr (Secondary)**.
*   **Auto-Ping:** Markiert den Gegner automatisch, sobald der erste Schuss aus der Zielvorrichtung (ADS) abgefeuert wird.
*   **Auto-Breath:** Simuliert automatisches Luftanhalten (`L3`) beim Zielen – ideal für Sniper-Loadouts.

---

## 📟 Smart Weapon Tracking & OLED Display

Das Skript verwaltet zwei völlig separate Anti-Recoil-Profile (MP und AR). Auf störende Controller-Vibrationen als Feedback wurde bewusst verzichtet. Stattdessen wird das Hardware-OLED-Display des Adapters (Cronus Zen / Titan) genutzt.

### 🔄 Profil-Wechsel
Beim Drücken von `Dreieck` ändert das Skript im Hintergrund den Rückstoßwert und liefert Echtzeit-Feedback auf dem Display:
*   **Primary:** Anzeige `WAFFE: MP` (Recoil-Wert: 20)
*   **Secondary:** Anzeige `WAFFE: AR` (Recoil-Wert: 25)

### 🛠️ Manueller Resync (Desync Fix)
Falls das Skript durch In-Game-Ereignisse (Tod, Gulag, Plattenkauf, Aufheben einer Bodenwaffe) asynchron zur tatsächlichen Waffe wird:
*   **Aktion:** Halte `L2` (Zielen) + drücke `Dreieck`.
*   **Ergebnis:** Das Skript wird *lautlos* wieder auf das MP-Profil (Primary) zurückgesetzt, **ohne** dass die Waffe im Spiel gewechselt wird. Das Display bestätigt dies durch den Sprung auf `WAFFE: MP`.