### `dialecticdaemon`

**Telecom & mobile security · on-device privacy · OpenWrt / embedded**

I look at how mobile modems and consumer routers handle identity, and contribute changes that shrink
a device's forensic and radio-layer footprint.

#### What I work on
- 📡 **Cellular security** — LTE attach & identity procedures, IMSI/IMEI handling, IMSI-catcher awareness.
- 🛡️ **Anonymity & forensic hygiene** — reducing IMEI/IMSI/MAC leakage on-device; secure-erase on UBIFS; least-privilege ACLs; safe identity-rotation flows.
- 🧩 **OpenWrt / embedded** — packaging, modem AT/QMI orchestration, init/rpcd, firmware analysis on Qualcomm/Quectel.

#### 🔬 The lab
A small **RF-shielded test bench** — Faraday enclosure, a private **srsRAN + Open5GS** LTE core,
**bladeRF** SDR and sysmoISIM test SIMs — so modem privacy behaviour can be validated on-air
without ever touching public spectrum.

#### 🚀 Selected work
- **[srlabs/blue-merle](https://github.com/srlabs/blue-merle)** — contributor to this OpenWrt
  cellular-anonymity package; a TAC / fingerprinting-alignment proposal, with forensic-hygiene and
  rotation-robustness work in progress (hardware-validated on GL-E750 / EM060K).
- **[EFForg/rayhunter](https://github.com/EFForg/rayhunter)** — a
  [controlled false-positive analysis](https://github.com/EFForg/rayhunter/issues/543#issuecomment-5192816597)
  of the "identity-request-without-auth-accept" heuristic (inbound-roaming / NAS-timer periodicity),
  from an under-represented region.

#### 🧰 Toolbox
`OpenWrt` · `Python` · `POSIX shell` · `srsRAN` / `Open5GS` · `bladeRF` / SDR · `radare2` / `Ghidra`
