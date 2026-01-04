# Chapter 13: Final Store Build

This is the end-state solution with shared code, content, and platform heads ready for store submission.

What this step shows:

- Fully aligned Windows, Android, and iOS projects using `DungeonSlime.Common`.
- Content pipeline and package management unified across platforms.
- Release-ready structure awaiting your signing assets and store metadata.

How to use this sample:

- Open `DungeonSlime.slnx`.
- Apply your signing settings (keystore on Android, certificates/profiles on iOS).
- Build Release for the platform you are submitting, then follow the store upload flow.

Projects:

- `DungeonSlime.Common` – Shared game code.
- `DungeonSlime` – Windows head.
- `DungeonSlime.Android` – Android head.
- `DungeonSlime.iOS` – iOS head.
- `MonoGameLibrary` – Shared content pipeline artifacts.
