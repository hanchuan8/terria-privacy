# 栖记 Terria 支持网站

这是栖记（Terria）iOS 与 HarmonyOS 应用的公开支持网站，包含隐私政策和中英文详细使用说明，不包含 Terria App 源码。

- 隐私政策：<https://hanchuan8.github.io/terria-privacy/>
- 使用说明：<https://hanchuan8.github.io/terria-privacy/guide.html>

两个页面均支持中文与 English 切换。隐私政策按平台分列 iOS 与 HarmonyOS 的实际数据处理边界；使用说明目前仍以 iOS 为准。`index.html` 是隐私政策，`guide.html` 是按功能路径编写的使用说明，公共样式位于 `styles.css`。相关文件推送到 `main` 后，GitHub Actions 会自动发布到 GitHub Pages。

## 2026-09-29 内容核对

隐私政策中英文同步补充本机二维码识别与标签分享、周报字体按需下载及缓存删除，并按 App 源码将自动更新检查描述改为成功后至少 6 小时及失败重试。仅本地内容更新；GitHub Pages 是否生效以推送后的线上页面核验为准。

## 2026-10-01 诊断信息披露更新

中英文政策按当前 App 实现更新本机诊断的 500 条普通事件、最多 5 段疑似编辑退出片段及导出的技术字段；保留不自动上传、用户主动分享的边界。自动检查更新的 6 小时间隔沿用 9 月 29 日已核对的本地政策，发布后以线上页面为准。

## 2026-10-14 RevenueCat 购买隐私披露

中英文政策补充SDK版本适用边界、购买凭据/匿名用户标识、内购验证及订阅统计用途、第三方服务器处理、保留/删除请求与私人邮件联系渠道，保持宠物档案和照片不发给RevenueCat的边界。App Store问卷对应购买历史用于App功能与分析、不关联个人身份、不用于跟踪。部署状态须以推送后Pages结果和正式网址回读确认；本地编辑不等于公开更新。

## 2026-10-20 iCloud 同步诊断与支持邮件

中英文政策区分本机操作日志和包含原始档案／照片的同步诊断包，说明主动只读下载、手动附加邮件、网易163支持邮箱、限定支持用途、人工保留与删除请求、本机文件不自动到期及不完整包边界。按当前 App 实现修正旧版“不同步照片／已移除照片开关”说明；同步不默认开启。无新增网页脚本、追踪或数据提交表单。部署需经 Pages 成功和正式网址回读确认；政策文字不代替 App Store 隐私标签核对。

## 2026-10-25 HarmonyOS 邀请测试隐私说明

同一隐私网址新增中英文 HarmonyOS 独立章节及平台跳转链接，保留 iOS 原条款并标明适用范围与各自更新日期。按 terria-hm 当前源码披露华为系统云同步（初始化/前台/资料变化可自动触发，含照片附件，受系统设置控制）、IAP Kit、系统选图/扫码、提醒与卡片、本机500条有限诊断、备份分享、字体下载及应用市场更新；未将鸿蒙描述为iCloud默认关闭或接入RevenueCat。云历史、相册副本、导出与交易记录删除分别说明。未改App源码或iOS使用说明。

核对来源：PersonalCloud.ets、OnlineServices.ets、TerriaStore.ets、HuaweiServices.ets、Diagnostics.ets、SystemSurfaces.ets、SurfaceForms.ets、AppUpdateService.ets、PosterFontProfile.ets、Index.ets与module.json5；官方华为云空间/IAP隐私声明链接列于政策内。网页披露不代表App运行中的授权时机、系统服务所有字段、双设备同步或商店审核已验收。部署和AGC填写结果见 terria-hm 的 docs/DEVELOPMENT.md 本次记录。
