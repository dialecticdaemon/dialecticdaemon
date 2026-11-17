### dialecticdaemon

Mobile and router security, privacy on the device. Berlin.

I look at how LTE modems and mobile routers handle device identity, measure what actually leaks, and send fixes upstream.

**Upstream work**

- [srlabs/blue-merle](https://github.com/srlabs/blue-merle):
  [#91](https://github.com/srlabs/blue-merle/pull/91) (merged),
  [#95](https://github.com/srlabs/blue-merle/pull/95) keeps `/root/esim` on tmpfs, because the original IMEI survived swaps in the UBIFS flash,
  [#96](https://github.com/srlabs/blue-merle/pull/96) randomises the guest-network BSSIDs too,
  [#97](https://github.com/srlabs/blue-merle/pull/97) and [#99](https://github.com/srlabs/blue-merle/pull/99) make the Wi-Fi look like an ordinary phone hotspot,
  [#90](https://github.com/srlabs/blue-merle/pull/90) sets the locally administered bit,
  [#98](https://github.com/srlabs/blue-merle/issues/98) proposes the Wi-Fi country code from the mobile network.
- How recognisable these routers are in public wardriving data, from WiGLE aggregate counts:
  [#97](https://github.com/srlabs/blue-merle/pull/97) and [#90](https://github.com/srlabs/blue-merle/pull/90).

**Lab**

Shielded LTE test bench (srsRAN / Open5GS, bladeRF, sysmoISIM) and a portable Kismet sensor case.

Contact: dialecticdaemon@proton.me

PGP: `BE0F FDC1 F4EE 2604 9875  8270 5148 9C36 DC7A 7893`
