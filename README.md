# 2d-platformer

Ein 2D-Plattformer, entwickelt in der **Unity Game Engine** mit C#. Dieses Repository enthält den fertig exportierten Windows-Build (Unity Player) – das Unity-Projekt selbst wird lokal weiterentwickelt und gepflegt.

## Spielen

Voraussetzung: Windows 64-Bit. Keine Installation nötig.

```
game\Test Projekt.exe
```

Die Dateien in `game\` sind das kompilierte Spiel (Unity-Player mit Mono/Burst-Unterteilungen). Es genügt, die `.exe` im Ordner `game` zu starten.

## Technologien

- Unity (2D-Setup, Scene- & Sprite-Workflow)
- C# (MonoBehaviour-Skripting)
- Burst/Mono-Builds für Windows Standalone

## Struktur

```
game\                              – Windows-Build des Spiels
└── Test Projekt.exe               – Startdatei
```

> Hinweis: Das Unity-Projekt (Assets, Scenes, Skripte) ist nicht Teil dieses Repos. Sinn und Zweck des Repos ist die Bereitstellung des spielbaren Builds.

## Projektbezug

Trainee-Projekt zum Erlernen der Unity-Engine: 2D-Physik, Sprite-Layer, Input-Handling und Build-Pipeline für Windows.