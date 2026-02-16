# 🌌 Sonnensystem

Ein interaktives 3D Sonnensystem, gebaut mit Three.js.

## Version 1.1

### Neuerungen gegenüber Version 1.0

#### 🔥 Verbesserte Sonne
- **Fire Shader** - Animierte Flammen-Textur mit Simplex-Noise
- **Mehrlagige Corona** - 4 gestaffelte Glüh-Effekte für realistische Atmosphäre
- **Sonnen-Strahlen** - Leuchtende Ray-Lines, die vom Körper ausgehen
- **Partikel-Effekte** - Pulsierende Funkenströme

### Features

#### 🎮 Interaktivität
- **3D-Navigation**: Rotieren, Zoomen und Schieben mit der Maus
- **Orbit Controls**: Intuitives Steuern der Kamera
- **Planet-Info**: Klick auf beliebigen Planeten für detaillierte Informationen

#### 🪐 Objekte
- **Sonne** mit neuem Fire-Effekt, Corona und Strahlen
- **8 Planeten** mit realistischen Farben und Größen
- **Umlaufbahnen** mit Inklation (geneigte Bahnebenen)
- **Monde** für Erde, Mars, Jupiter, Saturn, Uranus und Neptun
- **Saturn-Ringe**
- **Atmosphären** bei Erde und anderen Planeten

#### ⚙️ Steuerung
- **Geschwindigkeit**: Umschalten zwischen 0.2x, 0.5x, 1x, 2x, 5x (**Default: 0.2x**)
- **Labels**: Planeten-Namen ein-/ausblenden
- **Monde**: Anzeige der Monde umschalten
- **Bahnen**: Umlaufbahn-Linien ein-/ausblenden
- **Reset**: Kamera zurück zur Standard-Position

#### ✨ Visual Effects
- **Sternenhintergrund** mit Tausenden von Sternen
- **Beleuchtungssystem** mit mehreren Lichtquellen
- **Tiefeneffekte** durch Fog
- **Feuer-Sonne** mit animated GLSL Shader

## Technologie

- **Three.js** r134 - 3D Rendering Engine
- **Custom GLSL Shaders** - Für Fire-Effekt
- **Pure JavaScript** - Keine Frameworks
- **Responsive Design** - Funktioniert auf verschiedenen Bildschirmgrößen

## Installation

1. Repository clonen oder die HTML-Datei herunterladen
2. Die `index.html` in einem modernen Browser öffnen
3. Internetverbindung erforderlich (lädt Three.js vom CDN)

---

Viel Spaß mit der Erkundung unseres Sonnensystems! 🚀