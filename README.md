# [RK3566](https://github.com/SoCXin/RK3566)

* [Rockchips](https://www.rock-chips.com/): [Cortex-A55](https://github.com/SoCXin/Cortex)
* [L6R6](https://github.com/SoCXin/Level): 1.8 GHz

## [简介](https://github.com/SoCXin/RK3566/wiki)

[RK3566](http://www.rock-chips.com/a/cn/product/RK35xilie/2021/0113/1273.html)

### 关键特性

* Cortex-A55 Quad-Core + Mali-G52 GPU
* LPDDR4/LPDDR4X/DDR4/DDR3/DDR3L/LPDDR3 32GB
* 0.8 TOPS NPU
* PCIe 2.1 1x1 Lane
* SDIO 3.0, 10x UART, 4x SPI, 16x PWM,6x I2C, 2x SARADC
* FCCSP565L(15.5mm x 14.4mm)

### [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)


## [选型建议](https://github.com/SoCXin)

[RK3566](https://github.com/SoCXin/RK3566) 相对 [RK3568](http://www.rock-chips.com/a/cn/product/RK35xilie/2021/0113/1275.html) 不是兼容的，后者拥有更多高速接口和外设资源，特别是支持 PCIe 3.0 1×2 lane or 2x 1-lane @ 8 Gbps

RK3568 封装为 FCBGA636L(19mm x 19mm)，拥有2个Gigabit Ethernet (GMAC)，四路串行千兆媒体独立接口（QSGMII），支持3x CAN FD