# Firmware for Motorola Moto G5S Plus (sanders)

Proprietary firmware extracted from stock Oreo 8.1.0 `OPS28.65-36-14`.

- Source: <https://github.com/moto-msm8953/dump_motorola_sanders>
  at commit `16a947e43579a62174b43a349f4573d33abbf30d`
- `modem/image/`: MBA, modem, ADSP, Venus, WCNSS, A506 ZAP and
  TrustZone apps, as shipped in the stock `modem` partition.
- `wlan/`: default `WCNSS_qcom_wlan_nv.bin` plus `WCNSS_cfg.dat`
  and reference `WCNSS_qcom_cfg.ini`.
  Regional variants (`WCNSS_qcom_wlan_nv_Brazil.bin`,
  `WCNSS_qcom_wlan_nv_Argentina.bin`, `WCNSS_qcom_wlan_nv_India.bin`)
  exist upstream; the default NV is packaged.

All files are proprietary to Qualcomm/Motorola and redistributed
for use with postmarketOS on this device only.
