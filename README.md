# Nordic_Blinky - LE Test Fixture

BLE 广告信号发射源 - 基于 ZMK 固件

## 配置

- **设备名称**: Nordic_Blinky
- **功能**: BLE 广播模式 (Advertising Beacon)
- **TX 功率**: +8dBm (最大)

## 支持板卡

- nice_nano_v2
- puchi_ble_v1

## 编译

GitHub Actions 自动构建，输出:
- `nordic_blinky_nice_nano_v2.uf2`
- `nordic_blinky_puchi_ble_v1.uf2`

## 刷写

1. 双击复位键进入 bootloader
2. 拖入 .uf2 文件
