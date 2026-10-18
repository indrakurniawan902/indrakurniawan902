# Indra Kurniawan

**Mobile Engineer · Flutter & Kotlin** · Jakarta, Indonesia

I build mobile apps, mostly around what the phone has to do itself — native
hardware APIs, platform channels, USB peripherals, and an architecture that
survives the third feature. Flutter first; Kotlin when it has to reach the
metal.

[Portfolio](https://indra-developer.my.id) · [Email](mailto:indrakurniawan902@gmail.com)

---

## Stack

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)

## Featured work

### [flutter-ai-agent](https://github.com/indrakurniawan902/flutter-ai-agent) — On-device mobile AI workstation
An action-oriented mobile AI agent with 25 native device tools — camera vision,
voice I/O, fine alarms, calendar, geofencing, and an overlay bubble. The model
is just one driver; the core is a clean domain boundary where device
capabilities are exposed as structured tools with strict security policies.
Flutter + Cubit + Clean Architecture.

### [external_camera](https://github.com/indrakurniawan902/external_camera) — USB/UVC camera control from Flutter
A thin app-facing wrapper over `flutter_ffi_uvc`/`libuvc`: list attached USB
(OTG) devices, live preview, still capture, device status. The hard part was
Android's dual permission model (runtime `CAMERA` permission vs per-device
`UsbManager` grant raised by the engine) — a second requester on the same grant
double-prompts or wedges the system dialog.

### [my_quran](https://github.com/indrakurniawan902/my_quran) — Offline-first Quran & audio player
Full Clean Architecture reference implementation (Cubit only, `get_it` +
`injectable`, `dio`, `hive`, `dartz` `Either`). The architecture pattern that
survived here was later extracted into my reusable
[flutter-cubit-template](https://github.com/indrakurniawan902/flutter-cubit-template).

### [sosfomt_walkthrough_app](https://github.com/indrakurniawan902/sosfomt_walkthrough_app) — Story of Seasons walkthrough guide
Game companion app with a versioned CI/release pipeline. Documents real-world
Flutter 3.38 analyzer/generator constraint resolutions (`bloc_test` ↔ `test_api`
caps).

---

Clean Architecture starting templates:
[flutter-cubit-template](https://github.com/indrakurniawan902/flutter-cubit-template) (personal) ·
[flutter-riverpod-template](https://github.com/indrakurniawan902/flutter-riverpod-template) (client/office)
