# LED PCB V1

A board to drive 12 V addressable LED strips (WS2815) with [WLED](https://kno.wled.ge).

## How it works

- Fused 12 V input
- 12 V → 5 V → 3.3 V regulation
- ESP32-S3-WROOM-1 running WLED
- 3.3 V → 5 V level shifting on the data lines (SN74AHCT125)
- Two strip outputs, USB-C

KiCad files in [`HW/wled_V1/`](HW/wled_V1/).

## References

- [WS2815B datasheet](https://www.marutsu.co.jp/contents/shop/marutsu/datasheet/WS2815B.pdf)
- [ESP32-S3-WROOM-1 datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s3-wroom-1_wroom-1u_datasheet_en.pdf)
- [Video: the bare minimum to run an ESP on a PCB](https://www.youtube.com/watch?v=tQ0dL_9M1wI&t=242s)
