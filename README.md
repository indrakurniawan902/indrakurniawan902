<p align="center"><img src="https://raw.githubusercontent.com/indrakurniawan902/flutter-ai-agent/development/assets/images/flames_logo.png" width="420" alt="On-device mobile AI agent"></p>

# Indra Kurniawan

**Mobile Engineer · Flutter & Kotlin** · Jakarta, Indonesia

I build mobile apps around what the phone has to do itself — native hardware
APIs, platform channels, USB peripherals, and an architecture that survives the
third feature. Flutter first; Kotlin when it has to reach the metal.

[Portfolio](https://indra-developer.my.id) · [Email](mailto:indrakurniawan902@gmail.com)

**Currently:** building an on-device AI agent that drives real device tools —
camera, calendar, alarms, geofences, voice — without a cloud round-trip.

## Featured work

### [flutter-ai-agent](https://github.com/indrakurniawan902/flutter-ai-agent) — Mobile AI agent with device tool calling
25 native tools behind one domain boundary: camera vision, voice in/out, fine
alarms, calendar, contacts, geofencing, file workspace, and a system overlay
bubble. The model is just one driver — the interesting engineering is the tool
registry and its security policy layer: what an LLM is allowed to touch on a
phone, and how to fail closed when it asks for more.
`Flutter` · `Cubit` · `Clean Architecture` · `flutter_secure_storage`

### [external_camera](https://github.com/indrakurniawan902/external_camera) — USB/UVC camera control from Flutter
Thin app-facing wrapper over `flutter_ffi_uvc`/`libuvc`: list attached USB (OTG)
devices, live preview, still capture, device status. The hard part was never the
preview — Android needs two different grants here (runtime `CAMERA` and a
per-device `UsbManager` grant raised by the engine), and a second requester on
the same grant double-prompts or wedges the system dialog.
`Flutter plugin` · `Platform channels` · `Android USB host`

### [my_quran](https://github.com/indrakurniawan902/my_quran) — Offline-first Quran reader with recitation audio
Full Clean Architecture reference implementation — the app whose structure got
extracted into my reusable template below, so the rules describe code that
already survived real features.
`Cubit` · `get_it` · `dio` · `hive` · `dartz Either`

## Also public

[flutter-cubit-template](https://github.com/indrakurniawan902/flutter-cubit-template) ·
[flutter-riverpod-template](https://github.com/indrakurniawan902/flutter-riverpod-template)
— Clean Architecture starting points that ship an `AGENTS.md` so AI coding agents
follow the same conventions as the humans.

[sosfomt_walkthrough_app](https://github.com/indrakurniawan902/sosfomt_walkthrough_app) ·
[hmbtn_guide_app](https://github.com/indrakurniawan902/hmbtn_guide_app)
— Flutter game companion apps with a real CI + release pipeline.

Most of my day-to-day work lives in private client repositories.

---

## Stack

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com/?user=indrakurniawan902&theme=tokyonight&hide_border=true" alt="Contribution streak" />
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=indrakurniawan902&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
</p>
