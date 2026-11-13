# VTX Fulmen

VTX Fulmen is a desktop API client — HTTP, GraphQL, WebSocket, SSE, gRPC, SOAP and MCP — in the spirit of
Postman and Apidog. Everything stays on your computer: no account, no cloud.

**This repository holds the release files only.** Get VTX Fulmen from
[**Releases → the latest one**](https://github.com/tanawat011/vtx-fulmen-release/releases/latest):

| Your computer | The file to download |
| --- | --- |
| Mac (Apple silicon or Intel) | `VTX-Fulmen_<version>_universal.dmg` |
| Windows 10 / 11 | `VTX-Fulmen_<version>_x64_portable.zip` — unzip it and run, nothing to install |

`SHA256SUMS.txt` lists each file's SHA-256.

From 0.56.0 the releases here are **VTX Fulmen's Free edition**: every kind of request, flows, the mock server,
Specs and the code they make, and every run's report. Capture, Load test,
Databases, Schedules and the team reports' extras are part of Fulmen Pro, which is coming — their buttons are marked
PRO. Releases up to 0.55.4 had a dmg for each kind of Mac and a Windows installer.

VTX Fulmen was called Arccc up to 0.52.0: those releases keep the `Arccc_<version>_…` file names. Installing VTX Fulmen keeps the data Arccc had. This repository used to be `arccc-releases`, then `fulmen-releases` — the old addresses still lead here.

## The first time you open it

VTX Fulmen is not signed yet, so your computer asks once.

- **macOS 15 and later:** open it, click Done, then System Settings → Privacy & Security → Open Anyway (next to "VTX Fulmen").
- **macOS 14 and earlier:** right-click VTX Fulmen in Applications → Open → Open.
- **Windows:** right-click the zip → Properties → tick Unblock → OK, before unzipping. If "Windows protected your PC" shows, click More info → Run anyway. The app keeps its data in the `data` folder next to `VTX Fulmen.exe`.

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
(เดิมชื่อ Arccc — ข้อมูลเดิมอยู่ครบ) · ดาวน์โหลดจาก [Releases](https://github.com/tanawat011/vtx-fulmen-release/releases/latest) — Mac (ทั้งชิป M และ Intel) เอา `universal.dmg`,
Windows เอา `x64_portable.zip` (แตก zip แล้วเปิดได้เลย) · ตั้งแต่ 0.56.0 เป็นรุ่น Free (ส่วน Pro มีป้าย PRO) · ยังไม่ได้ sign: ครั้งแรกต้องกดอนุญาต (ดูข้างบน) ·
เจอปัญหา: ในแอปกด ⌘K / Ctrl+K → Report a problem… แล้ว copy ข้อความส่งมา
