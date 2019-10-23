## 声明：

1. 涉及到强电及RF电路，环境不同，DIY水平不一，无法保证100%成功!
2. 文件仅供个人交流学习使用，禁止商业行为！


![](https://github.com/huexpub/NRF24-RELAYS/blob/master/3relay/Top.jpg?raw=true)


# nrf24-relays
NRF24-RELAYS 支持中继的2.4G无线开关改装模块，支持LED输出，LED有渐变效果，未来会增加WS2812代码输出。支持多变效果。完美改装罗朗格等自恢复LED面板

# Testing
- 本次测试增加了IRQ队列功能，将无线接收并发由3增加最高可达20，针对中继改善效果明显，但也可能导致MCU内存泄露，导致数据丢失。目前增至5，稳定后期对应增加测试10左右!
- IRQ队列固件不与其它固件兼容，Testing测试需要使用非IRQ固件需要将PCB背面的标X线切断即可

## 小量生产请自行测试稳定后再进量产，由于RF电路敏感性，请购买元件务必上正品渠道，保证焊接工艺

## QQ讨论群

![mynrf24-front](https://github.com/huexpub/MYNRF24/blob/master/doc/Mysenso-QQ.png)
