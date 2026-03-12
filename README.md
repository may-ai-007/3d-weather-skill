# 3D Weather Skill / SkyVibe Weather

<p align="center">
  <strong>AI 天气视觉工具</strong>
</p>

<p align="center">
  输入城市名，30 秒内生成具有城市地标/人文特色的 3D 天气海报与 Live Photo 动态效果
</p>

<p align="center">
  <img src="assets/cover.jpg" alt="3D Weather Skill Cover" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Coze-Skill-blue" />
  <img src="https://img.shields.io/badge/AI-Multimodal-black" />
  <img src="https://img.shields.io/badge/Weather-Visual%20Generation-success" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

---

## 项目简介

3D Weather Skill / SkyVibe Weather 是一个基于多模态大模型能力打造的 AI 天气视觉工具。

它不同于传统天气 App 的信息式展示，而是将“实时天气 + 城市地标/人文特色 + 3D 微缩景观 + 动态效果”组合成一套更具审美、传播性和情绪价值的天气表达方式。

用户只需要输入一个城市名，即可在 30 秒内得到：
- 一张 3D 城市天气海报
- 一段基于海报生成的 Live Photo 动态效果
- 中文化的信息展示与地点文案

---

## 获奖信息

本项目为扣子技能大赛获奖作品，获得：
- 极客赛道第一名

> 这里放获奖公告截图
>
> 建议文件路径：`assets/award.png`

<p align="center">
  <img src="assets/award.png" alt="Award" width="88%" />
</p>

---

## 为什么它不只是天气工具

传统天气产品大多强调“信息效率”，而这个项目更关注“信息如何被重新设计成有情绪、有风格、可传播的视觉内容”。

换句话说，它不只是在回答：
> 今天几度？是晴是阴？

它还在回答：
> 如果把一座城市今天的天气，变成一张具有在地特色的 3D 微缩城市海报，会是什么样？

这也是我对 AI 原生产品的一种理解：
- AI 不只是提高效率
- AI 也可以重塑表达形式
- AI 可以把常规信息重新变成内容、体验和传播素材

---

## 核心能力

- 实时天气信息获取：温度、天气状态等
- 城市特色提取：地标建筑、自然景观、人文元素
- 3D 微缩天气海报生成：统一风格、适合展示与分享
- Live Photo 动态效果生成：基于海报延展出 5 秒动态体验
- 中文化视觉输出：城市名、天气、温度等信息统一中文呈现
- 全球主要城市支持：面向全球主要城市输入场景

---

## 效果演示

### 海报示例

> 请在这里放 3 张代表性海报
>
> 建议：
> - 伊犁
> - 上海
> - 东京 / 伦敦 / 巴黎任一国际城市

<p align="center">
  <img src="assets/cases/yili-poster.jpg" width="31%" />
  <img src="assets/cases/shanghai-poster.jpg" width="31%" />
  <img src="assets/cases/lundun-poster.jpg" width="31%" />
</p>

### 动态效果

> README 中建议使用 GIF 展示，而不是直接使用 Live Photo 原始文件
>
> 建议文件路径：`assets/demo.gif`

<p align="center">
  <img src="assets/demo.gif" alt="Live Demo" width="82%" />
</p>

> 如果后续你准备了高清视频版本，可以把下方链接替换成实际地址：
>
> [观看高清视频演示](https://www.xiaohongshu.com/discovery/item/6984a059000000000a029327?app_platform=android&ignoreEngage=true&app_version=9.21.0&share_from_user_hidden=true&xsec_source=app_share&type=video&xsec_token=CBuZhis81Ew9HU4Y0z7q2aFVlxa6DD94PWck3lDSCIy1M%3D&author_share=1&xhsshare=&shareRedId=ODs5MjhHNUI2NzUyOTgwNjlHOTlFOjZO&apptime=1773324553&share_id=eed7018e2eff4fa59ac7b04874626844&share_channel=copy_link)

---

## 如何体验

### Coze 技能链接

- 在线体验：<https://www.coze.cn/?skill_share_pid=7600080213497610274>

### 输入示例

- 上海天气
- 北京天气
- 伦敦天气海报
- 东京天气图片
- 伊犁天气

### 输出逻辑

- 当用户明确表达“只要图片 / 天气海报 / 不要视频”时，输出静态海报
- 其他默认情况，输出海报 + Live Photo 动态效果

---

## 开源范围

这个仓库采用的是“展示性开源”策略。

本仓库公开：
- 项目介绍与设计思路
- 效果图与演示素材
- 用户使用说明
- 公开版 Prompt 框架
- 智能座舱方向的产品思考

本仓库不公开：
- 完整系统 Prompt
- `.skill` 导出文件
- `.coze` 配置文件
- 可直接复刻核心工作流的私有细节

详见：
- [`docs/open-source-scope.md`](docs/open-source-scope.md)
- [`docs/prompt-framework-public.md`](docs/prompt-framework-public.md)

---

## 智能座舱延展

这个项目虽然起点是一个天气技能，但我更感兴趣的是它在智能座舱中的延展潜力。

我过去长期在车联网与智能座舱领域做产品，因此我会把这个能力进一步思考为：
- 更有氛围感的天气可视化
- 更有在地感的导航目的地展示
- 更具惊喜感和传播性的车内 AI 体验
- 可与语音、地图、壁纸、HUD、后排屏联动的场景化能力

详见：
- [`docs/automotive-solution-ideas.md`](docs/automotive-solution-ideas.md)

---

## 关于我

我是一名拥有 15 年互联网产品经验的产品经理，目前正在做 AI 创业，也持续探索 AI 在工具、内容和行业场景中的产品化机会。

我长期关注的方向包括：
- AI 原生产品
- 多模态能力落地
- Web 工具开发
- 车联网与智能座舱体验
- AI 产品商业化与内容表达

这个仓库既是一个获奖项目的公开展示，也是我的一份作品集。

---

## 合作与联系

欢迎以下方向交流：
- AI 产品合作
- 招聘机会
- 顾问咨询
- 智能座舱 / 车机体验方案讨论
- 内容合作与媒体交流

联系方式：
- 邮箱 1：mayuzone.com@163.com
- 邮箱 2：mayuzone.com@gmail.com

> 后续我会建立交流群，并把群二维码更新到这里。

---

## 支持项目

如果这个项目对你有启发，欢迎：
- Star 本仓库
- 分享给更多朋友
- 关注我的内容账号
- 请我喝杯咖啡

> 赞赏入口占位说明：
>
> 你后续可以在这里放以下任一方式：
> - 微信赞赏码截图：`assets/support-wechat.png`
> - 爱发电主页链接
> - Buy Me a Coffee / 赞助链接
>
> 示例占位：
>
> `<img src="assets/support-wechat.png" width="260" />`

---

## License

本项目建议采用 MIT License，以便更开放地展示项目思路与能力表达。
