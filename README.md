# 连连看 (Mahjong Link) 🀄

一个经典的 **连连看** 小游戏，纯 HTML + CSS + JavaScript 实现，无需任何外部依赖。

## 在线试玩 🎮

👉 [https://landeshuodmm.github.io/game/](https://landeshuodmm.github.io/game/)

或者直接下载 `index.html` 用浏览器打开即可游玩。

## 游戏规则 📋

- 8×12 网格，共 96 张牌，16 种动物 emoji 各出现 6 次
- 点击两张**相同图案**的牌，如果它们之间的路径**最多经过两次转弯**且畅通无阻，即可消除
- 所有牌消除完毕即为胜利

## 功能特性 ✨

| 功能 | 说明 |
|------|------|
| ⏱️ **计时器** | 从游戏开始累计计时（mm:ss） |
| 🏆 **得分** | 每成功消除一对 +10 分 |
| 🔄 **洗牌** | 打乱剩余牌的布局，计入洗牌次数 |
| 💡 **提示** | 自动找到一对可连接的牌并高亮闪烁（3秒冷却） |
| 🔁 **重新开始** | 重置全盘 |

## 技术栈 🛠️

- **纯 HTML + CSS + Vanilla JS** — 单文件，无外部依赖
- **CSS Grid** — 棋盘布局
- **Canvas** — 连线动画绘制
- **Web Audio API** — 音效生成（无需音频文件）
- **寻路算法** — 支持 0/1/2 次转弯 + 虚拟边界路径检测

## 项目结构 📁

```
game/
├── index.html   # 游戏主文件（内嵌所有代码）
└── README.md    # 本文件
```

## 本地运行 🚀

1. 下载 `index.html`
2. 双击文件用浏览器打开
3. 🎉 开始游戏！

---

## Run Locally 🚀

Just open `index.html` in any modern browser. Double click and play!

---

Made with ❤️ by Codex
