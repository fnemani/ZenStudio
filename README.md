# Warzone GPC Script - V2.7 FAWI Edition (Aggressive Movement)

Willkommen zum Git-Repository für das ultimative Warzone-Skript, speziell kalibriert für kompetitive Rebirth Island 4er-Lobbies. Diese Version fokussiert sich auf extrem aggressives Movement, minimalen Input-Lag und einen unsichtbaren, dauerhaft aktiven Aim Assist.

## ⚠️ Wichtige In-Game-Einstellungen
Damit das Skript fehlerfrei funktioniert, **müssen** folgende Einstellungen in Call of Duty: Warzone vorgenommen werden:
*   **Tastenbelegung:** `Stick & Bewegung` (Stick & Move)
*   **Automatischer Sprint:** `Automatischer Taktiksprint` (Zwingend erforderlich für das Auto-Run-Skript und flüssige Slide-Cancels)

## 🎮 Controller Layout (PS5)
Das Skript ist nativ auf den DualSense-Controller und die oben genannte Belegung zugeschnitten:
*   **Zielen / Schießen:** L2 / R2 (Hair-Triggers integriert – reagieren bei minimaler Berührung)
*   **Sprint / Movement:** L3 (Taktiksprint triggert jetzt extrem früh bei 50% Stick-Ausschlag)
*   **Springen:** R3 (Rechter Stick Klick)
*   **Haltung:** Kreis (Sliden/Hocken)
*   **Waffenwechsel:** Dreieck (Steuert gleichzeitig das Skript-Profil)

---

## ⚡ Aggressive Movement Systems
Das Movement-Profil wurde überarbeitet, um in Close-Quarter-Gunfights ein extrem schweres Ziel zu bieten:
*   **Aggressive Slide-Cancel (Slide into 3x B-Hop):** Drückst du im Taktiksprint die `Kreis`-Taste, führt dein Charakter einen schnellen Slide aus, bricht diesen perfekt ab und hängt **automatisch 3 Bunny-Hops** hinten an.
*   **Auto_Strafe_Jump (Camera Breaker):** Wenn du in einem Gunfight zielst (L2) und schießt (R2) und dann *kurz aufhörst zu zielen* (Wechsel ins Hip-Fire), zwingt das Skript deinen Charakter in einen extrem harten, unvorhersehbaren Seitwärtssprung.
*   **Endless Bunny-Hop:** Halte `R3` gedrückt, um kontinuierlich und im perfekten In-Game-Timing zu springen.

---

## 🎯 Aiming & Combat Utility
Der Aim Assist wurde entschlackt und auf konstante Performance getrimmt:
*   **Always-On Aim Assist:** Der Aim Assist (Rotational & Strafe) ist permanent beim Zielen aktiv. Ein manuelles Ein- und Ausschalten ist nicht mehr nötig (und verhindert Fehler in der Hektik).
*   **Dynamic Anti-Recoil:** Zieht die Waffe beim Feuern sanft nach unten. Der Zug stoppt intelligent (`AR_Release = 45`), sobald du den Stick bewegst, um auf slidene Gegner zu flicken.
*   **Auto-Ping:** Markiert den Gegner automatisch, sobald du aus der Zielvorrichtung (ADS) den ersten Schuss abfeuerst.
*   **Auto-Breath:** Simuliert automatisches Luftanhalten (L3) beim Zielen (perfekt für Sniper).

---

## 📟 Smart Weapon Tracking & OLED Display
Das Skript verwaltet zwei völlig separate Anti-Recoil-Profile (MP und Sturmgewehr) und verzichtet auf störende Controller-Vibrationen. Stattdessen nutzt es das Hardware-Display deines Adapters (Cronus/Titan).

*   **OLED Live-Feedback:** Beim Drücken von `Dreieck` (Waffenwechsel im Spiel) ändert das Skript im Hintergrund den Rückstoß und zeigt auf dem kleinen Display in Echtzeit **"WAFFE: MP"** (Recoil 15) oder **"WAFFE: AR"** (Recoil 25) an.
*   **Manueller Resync:** Falls das Skript aus dem Takt gerät (z.B. durch Tod, Gulag, Plattenkauf oder das Aufheben einer Bodenwaffe), halte **L2 (Zielen) + Dreieck**. Das setzt das Skript lautlos wieder auf das MP-Profil (Primary) zurück, *ohne* dass die Waffe im Spiel gewechselt wird. Das Display springt dabei zur Bestätigung wieder auf "WAFFE: MP".