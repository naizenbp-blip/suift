# Suift

Enregistreur d'ecran leger pour Windows avec replay buffer instantane
(façon Nvidia Instant Replay) et capture audio par source separee.

## Telecharger

Va dans l'onglet **[Releases](../../releases/latest)** de ce depot et
telecharge `Suift-win64.zip`. Decompresse, lance `Suift.exe`.

Windows 10/11 64 bits requis.

## Fonctionnalites

- **Buffer en boucle continue** : les dernieres secondes sont toujours
  disponibles, une touche suffit pour les sauvegarder dans un fichier.
- **Audio par source separee** : microphone, tout le systeme, ou une
  application precise isolee (WASAPI process loopback).
- **Capture legere** : DXGI Desktop Duplication + encodage materiel
  (NVENC / QuickSync / AMF) quand disponible, sans impact FPS notable.
