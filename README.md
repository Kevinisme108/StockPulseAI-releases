# StockPulseAI · 股脉

> **AI 驱动的美股 + 亚洲股市投研助手**（Android）。多市场实时行情、K 线 + 技术指标、国际个股新闻、AI 结构化投资意见。全部基于免费 API。

## 📥 下载

**[⬇️ 下载最新版 APK](https://github.com/Kevinisme108/StockPulseAI-releases/releases/latest)**

下载 `stockpulseai_v*.apk` → Android 允许「未知来源」安装即可。源码仓库私有，此处仅提供 APK 公开下载。

## ✨ 功能

### 多市场行情
- 🇺🇸 美股 · 🇲🇾 马股 · 🇭🇰 港股 · 🇨🇳 A股 · 🇸🇬 新股
- 全球大市：道指 / 纳指 / 标普500 **真实指数点位**
- 亚洲大市：富时马股 / 恒生 / 上证 / 新加坡 STI + 黄金 / 白银 / 原油
- 本地货币显示：RM / HK$ / S$ / ¥

### 个股详情
- 日 / 周 / 月 K 线 + MA20/50/200、RSI(14)、MACD（本地计算，零额度消耗）
- 基本面：PE / PEG / EV-EBITDA / EPS / 营收增长 / 净利率 / ROE / 股息率 / 52 周区间
- 业绩表现（季报 / 年报）+ 盈利惊喜 + 分析师评级
- 个股新闻：国际个股经 Google News 检索，真实逐条报道

### AI 投研助手
- 市场感知分析师角色，按 技术面 / 基本面 / 消息面 / 综合评级 四维输出
- 个股引入所属大盘做**相对强弱**判断
- 大市解读纳入用户自选股持仓
- 多 AI 提供商可选：Gemini / DeepSeek / Groq

## 🔑 使用前准备（免费 key）

| 服务 | 注册地址 | 用途 | 免费额度 |
|------|---------|------|---------|
| Finnhub | finnhub.io | 美股报价/新闻/基本面 | 60 次/分钟 |
| Twelve Data | twelvedata.com | 美股历史 K 线 | 800 次/天 |
| Gemini | aistudio.google.com | AI 分析 | ~1,500 次/天 |
| DeepSeek / Groq | 可选 | AI 分析（备选） | Groq 永久免费 |

> 亚洲市场行情/K 线/新闻走 Yahoo Finance + Google News，**无需 key**。安装后到「设置」填入 key（本机加密存储）。

## 🛠 技术栈

Kotlin · Jetpack Compose · MVVM + Hilt · Room · Retrofit/Moshi · MPAndroidChart

## ⚠️ 免责声明

本 App 所有分析（含 AI 生成内容）**仅供参考，不构成投资建议**。免费行情有 15–20 分钟延迟。