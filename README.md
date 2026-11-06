# KT An Huyệt — bản phát hành

Repo này chỉ chứa **bản phát hành** (firmware `.bin` và app Android `.apk`) cho thiết bị đo lực ấn huyệt KThinker.
Tải ở mục **Releases** → bản mới nhất.

| File | Dùng cho |
|---|---|
| `do_luc_an_huyet.ino.bin` | Firmware ESP32-C6. Thiết bị tự tải khi nhận lệnh `OTA` |
| `KT-AnHuyet.apk` | App Android. Hoặc mở trang web thiết bị → "Tải app Android" |

Cập nhật firmware: gửi lệnh `OTA` (qua trang MQTT, BLE hoặc Serial); kiểm tra phiên bản bằng `VER`.
