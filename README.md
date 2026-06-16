美股AI助手（Stock）
Android 美股分析 App：自选股报价、K 线 + 技术指标、个股/大市新闻、AI 专业投资意见。全部使用免费 API。

技术栈
Kotlin + Jetpack Compose · MVVM + Hilt · Room 缓存 · Retrofit/Moshi · MPAndroidChart

功能
自选股：搜索美股添加，实时报价（涨绿跌红），下拉刷新
个股详情：日/周/月 K 线 + MA20/50/200、RSI(14)、MACD(12,26,9)（全部本地计算，零 API 消耗）+ 基本面卡片（PE/EPS/营收增长/52 周区间）+ 个股新闻
大市概览：SPY/QQQ/DIA 三大指数 + 大市新闻 + AI 今日解读
AI 诊断：按四维框架（技术面/基本面/消息面/综合评级）生成结构化意见，按需触发节省额度
使用前准备（三个免费 key）
服务	注册地址	用途	免费额度
Finnhub	https://finnhub.io	报价/新闻/基本面	60 次/分钟
Twelve Data	https://twelvedata.com	历史 K 线	800 次/天
Gemini	https://aistudio.google.com	AI 分析	~1,500 次/天
安装 App 后到「设置」页填入三个 key（本机加密存储）。


免责声明
本 App 所有分析（含 AI 生成内容）仅供参考，不构成投资建议。免费行情有 15-20 分钟延迟。
