# Indra Kurniawan

**Mobile Engineer · Flutter & Kotlin** · Jakarta, Indonesia

I build mobile apps, mostly around what the phone has to do itself — platform
channels, device I/O, and an architecture that survives the third feature.
Flutter first; Kotlin when it has to reach the metal.

[Portfolio](https://indra-developer.my.id) · [Email](mailto:indrakurniawan902@gmail.com)

---

## Stack

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)

## Featured work

### [external_camera](https://github.com/indrakurniawan902/external_camera) — USB/UVC camera control from Flutter
A thin app-facing wrapper over `flutter_ffi_uvc`/`libuvc`: list attached USB
(OTG) devices, live preview, still capture, device status. The hard part was
never the preview — it was the permission model. Android needs two separate
grants here (a runtime `CAMERA` permission and a per-device `UsbManager` grant
raised by the engine), and a second requester on the same grant double-prompts
or wedges the system dialog. Documenting that, and keeping the API narrow enough
that an app is not coupled to the engine's whole surface, is most of the package.

### [flutter-cubit-template](https://github.com/indrakurniawan902/flutter-cubit-template) — Clean Architecture starting point (Cubit)
Cubit-only state management, `get_it` + `injectable` DI, `go_router`, `dio`,
Hive, and `dartz` `Either` for error handling. Canonized from an app that
already shipped rather than invented for a slide, and it ships an `AGENTS.md`
template so AI coding agents produce the same file layout and conventions as
the humans do.

### [flutter-riverpod-template](https://github.com/indrakurniawan902/flutter-riverpod-template) — Clean Architecture starting point (Riverpod)
The Riverpod counterpart — `freezed`, `dio`/`dio_extended`, `go_router` — plus a
`design.md` for the visual system, so a new project starts with the same
architecture *and* the same design decisions already written down.

---

Most of my day-to-day work lives in private client repositories.
