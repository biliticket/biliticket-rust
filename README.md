# Bili Ticket Rust

> BHYG lite pro mini advanced f**ked ? ver.

[下载地址](https://github.com/biliticket/biliticket-rust/releases)

[电报交流群](https://t.me/bilibili_ticket)

本程序仅供学习交流, 不得用于商业用途,

使用本程序进行违法操作产生的法律责任由操作者自行承担,

对本程序进行二次开发/分发时请注意遵守GPL-3.0开源协议,

本脚本仅适用于蹲回流票, 我们反对将其用于抢票,

黄牛 / 收费代抢４０００＋

## 画饼

- 流程
  - login
    - 收集cookie
    - 补全cookie
  - get
  - countdown
  - cache
  - prepare(token)
    - risk
    - generate
  - createOrder
  - orderStatus
  - finish
  - 支付
  - 提醒

- 会员购功能
  - 票种
    - 实名票
    - 非实名票
    - 邮寄票
    - 优惠票
    - 团购票
    - 选座票
  - 平台功能
    - 增减实名制
    - 增减收货地址
    - 增减非实名购买人

- 软件功能
  - 会员购库
    - 网络请求
    - 接口处理
    - 接口抽象
  - 工具库
    - 配置文件
    - 状态机
    - 异步
    - 日志
    - 验证码
    - 提醒
  - 客户端
    - CLI客户端
    - 桌面客户端
    - 安卓客户端

## 运行流程

![FSM](fsm.png)

## 开发

```bash
git clone https://github.com/biliticket/biliticket-rust.git
cd biliticket-rust
```

## 感谢

- [Amorter/biliTicker_gt](https://github.com/Amorter/biliTicker_gt)
- [Just-Prog/Bilibili_show_ticket_auto_order](https://github.com/Just-Prog/Bilibili_show_ticket_auto_order)
- [biliticket/BHYG](https://github.com/biliticket/BHYG)
- [mikumifa/biliTickerBuy](https://github.com/mikumifa/biliTickerBuy)
- [transition-ticket](https://github.com/Hobr/transition-ticket)
