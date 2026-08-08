### `dialecticdaemon`

**Telecom & mobile security · on-device privacy · OpenWrt / embedded**

Security research at **[ZERO Cybernetic Systems & Digital Solutions UG](https://zerotrust.is)** (Berlin) · ✉️ security@zerotrust.is

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
  cellular-anonymity package. Open, hardware-tested PRs: forensic-hygiene + rotation-robustness +
  switch-abort ([#89](https://github.com/srlabs/blue-merle/pull/89)), vendor-OUI MAC/BSSID mimicry
  ([#90](https://github.com/srlabs/blue-merle/pull/90)) and a flash-wear fix
  ([#91](https://github.com/srlabs/blue-merle/pull/91)); plus a TAC / fingerprinting-alignment
  proposal. Hardware-validated on GL-E750 / EM060K.

#### 🧰 Toolbox
`OpenWrt` · `Python` · `POSIX shell` · `srsRAN` / `Open5GS` · `bladeRF` / SDR · `radare2` / `Ghidra`
