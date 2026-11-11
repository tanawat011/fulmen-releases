# VTX Fulmen

VTX Fulmen is a desktop API client — HTTP, GraphQL, WebSocket, SSE, gRPC, SOAP and MCP — in the spirit of
Postman and Apidog. Everything stays on your computer: no account, no cloud.

**This repository holds the release files only.** Get VTX Fulmen from
[**Releases → the latest one**](https://github.com/tanawat011/fulmen-releases/releases/latest):

| Your computer | The file to download |
| --- | --- |
| Mac with Apple silicon (M1, M2, M3, M4) | `VTX-Fulmen_<version>_aarch64.dmg` |
| Mac with Intel | `VTX-Fulmen_<version>_x64.dmg` |
| Windows 10 / 11 | `VTX-Fulmen_<version>_x64-setup.exe` — or `VTX-Fulmen_<version>_x64_portable.zip` to run without installing |

VTX Fulmen was called Arccc up to 0.52.0: those releases keep the `Arccc_<version>_…` file names. Installing VTX Fulmen keeps the data Arccc had, and this repository used to be `arccc-releases` — the old address still leads here.

Not sure which Mac you have? Apple menu → About This Mac: "Chip Apple M…" is Apple silicon, "Processor … Intel" is Intel.

## The first time you open it

VTX Fulmen is not signed yet, so your computer asks once.

- **macOS 15 and later:** open it, click Done, then System Settings → Privacy & Security → Open Anyway (next to "VTX Fulmen").
- **macOS 14 and earlier:** right-click VTX Fulmen in Applications → Open → Open.
- **Windows:** if "Windows protected your PC" shows, click More info → Run anyway. For the portable zip: right-click it → Properties → tick Unblock → OK, before unzipping.

## New to it?

Open the sample project (on the first screen, or ⌘K / Ctrl+K → Open the sample project): a small shop API that
VTX Fulmen's own mock answers on your computer, with a list of things to try.

## Updates

VTX Fulmen asks GitHub once a day for the latest release here and tells you when a newer one is out. It never
downloads or installs anything by itself. Turn it off in Settings → About → Updates.

## Found a problem?

In VTX Fulmen: ⌘K (Ctrl+K on Windows) → Report a problem… It puts what happened together with the version, your
operating system and the last things the app did, with secret values hidden. Copy it and send it to whoever
gave you VTX Fulmen.

---

**ภาษาไทย:** VTX Fulmen เป็นโปรแกรมยิง API แบบ Postman / Apidog ข้อมูลอยู่ในเครื่องทั้งหมด ไม่มีบัญชี ไม่มี cloud ·
(เดิมชื่อ Arccc — ข้อมูลเดิมอยู่ครบ) · ดาวน์โหลดจาก [Releases](https://github.com/tanawat011/fulmen-releases/releases/latest) — Mac ชิป M เอา `aarch64.dmg`,
Mac Intel เอา `x64.dmg`, Windows เอา `setup.exe` · ยังไม่ได้ sign: ครั้งแรกต้องกดอนุญาต (ดูข้างบน) ·
เจอปัญหา: ในแอปกด ⌘K / Ctrl+K → Report a problem… แล้ว copy ข้อความส่งมา
