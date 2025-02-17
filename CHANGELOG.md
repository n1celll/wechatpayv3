# Changelog

## [1.2.13] - 2022-02-17

### Added

- 初始化加载证书失败时抛出异常

## [1.2.12] - 2022-01-15

### Added

- 增加hmac_sha256签名方法，用于支持调起支付分订单时签名

### Fixed

- 创建支付分订单非必须参数值的 bug

## [1.2.11] - 2021-12-15

### Fixed

- notify_url 未赋值的 bug
- 连锁品牌请求分账的 bug

## [1.2.10] - 2021-12-05

### Fixed

- 请求分账的 bug

## [1.2.9] - 2021-12-05

### Fixed

- 请求分账的 bug

## [1.2.8] - 2021-12-05

### Fixed

- 查询代金券批次详情的一个 bug

## [1.2.7] - 2021-11-23

### Fixed

- 拼写错误

## [1.2.6] - 2021-11-20

### Added

- 新增 callback 接口，解密并保留所有回调参数，替代原 decrypt_callback 接口

## [1.2.5] - 2021-11-19

### Added

- 提交投诉回复新增可选参数
- 商户开户意愿确认接口
- 商户违规通知回调接口

## [1.2.4] - 2021-11-19

### Fixed

- 请求分账接口参数传递错误的 bug

## [1.2.3] - 2021-11-05

### Added

- 访问请求支持代理

## [1.2.2] - 2021-11-05

### Fixed

- 特约商户进件缺少 Wechatpay-Serial 的 bug

## [1.2.1] - 2021-11-04

### Fixed

- 拼写错误

## [1.2.0] - 2021-11-04

### Added

- 服务商模式接口(电商收付通除外)

### Fixed

- 直连模式部分接口 bug

## [1.1.0] - 2021-10-11

### Added

- 营销工具下代金券接口
- 营销工具下商家券接口

## [1.0.22] - 2021-10-09

### Fixed

- 查询支付分订单接口 bug

## [1.0.21] - 2021-09-29

### Added

- 商户申请获取对账单

## [1.0.20] - 2021-09-27

### Fixed

- 未引入支付分接口函数

## [1.0.19] - 2021-09-19

### Added

- 经营能力下微信支付分接口

### Changed

- 提前加载平台证书

## [1.0.18] - 2021-09-18

### Added

- 营销工具下支付有礼接口

## [1.0.17] - 2021-09-18

### Changed

- 日志信息内容

## [1.0.16] - 2021-09-18

### Added

- 初始化时支持日志记录

## [1.0.15] - 2021-09-17

### Added

- 营销工具下委托营销接口
- CHANGLOG.md

### Changed

- 示例 example

## [1.0.14] - 2021-09-14

### Changed

- 微调账单和图像下载接口返回值类型，message 参数从 string 变更为 bytes

## [1.0.13] - 2021-09-14

### Fixed

- 敏感信息解密 bug

## [1.0.12] - 2021-09-14

### Added

- 风险合规下消费者投诉 2.0 接口

## [1.0.11] - 2021-09-09

### Added

- 资金应用下分账接口

## [1.0.10] - 2021-09-05

### Changed

- 增强回调消息验证接口兼容性

## [1.0.9] - 2021-08-13

### Added

- 营销工具下图片上传(营销专用)接口

## [1.0.8] - 2021-08-13

### Added

- 行业方案下微信支付分停车接口

## [1.0.7] - 2021-08-12

### Added

- 其他能力下图片及视频上传接口

## [1.0.6] - 2021-08-09

### Changed

- 增强回调消息验证接口兼容性

## [1.0.5] - 2021-07-30

### Added

- 敏感信息参数自动加密

## [1.0.4] - 2021-07-14

### Added

- 经营能力下支付即服务接口

## [1.0.3] - 2021-06-22

### Fixed

- 下载证书无需验证签名

## [1.0.2] - 2021-06-16

### Fixed

- 平台证书更新 bug

## [1.0.1] - 2021-04-20

### Changed

- 代码重构

## [1.0] - 2021-04-20

### Added

- 智慧商圈积分授权查询

## [0.54] - 2021-04-20

### Added

- 支持本地缓存平台证书，减少网络请求

## [0.54] - 2021-04-20

### Changed

- 移除无效的 import

## [0.53] - 2021-04-19

### Changed

- 移除对 pyOpenSSL 包的依赖

## [0.53] - 2021-04-19

### Changed

- 移除对 pyOpenSSL 包的依赖

## [0.52] - 2021-04-19

### Added

- 行业方案下智慧商圈积分同步接口

### Fixed

- 签名验证 bug

## [0.51] - 2021-04-16

### Added

- 调起支付时需要的签名
- 回调消息接口自动解密 resource 字段

## [0.50] - 2021-04-16

### Added

- 微信平台证书自动下载及更新，无需提前准备

### Removed

- 证书下载接口

## [0.49] - 2021-04-16

### Changed

- 未提供平台证书时跳过接口验证

## [0.48] - 2021-04-16

### Fixed

- 验证签名 bug

## [0.47] - 2021-04-15

### Changed

- 接口返回类型从 bytes 更换为 string

## [0.46] - 2021-04-15

### Added

- 验证应答签名有效性

## [0.45] - 2021-04-15

### Fixed

- POST 接口签名错误

## [0.44] - 2021-04-15

### Added

- 基础支付下合单支付接口

## [0.43] - 2021-04-14

### Changed

- sdk 结构
- pypi 发布包格式

## [0.1] - 2021-04-14

### Added

- 基础支付(JSAPI 支付、APP 支付、H5 支付、Native 支付、小程序支付)下的：
  下单、查询订单、关闭订单、退款、退款查询、交易账单、资金账单及账单下载接口
- 新增证书下载接口
