# 🍺 RimTavern 社区故事库
> **RimTavern Community Cards** — 玩家为 RimTavern Mod 创作的剧情组件分享库。

这里是 RimTavern 玩家们分享自己创作的地方。你可以找到别人写好的 **角色卡**、**世界书** 和 **事件卡**，下载后直接放进游戏里使用，也可以上传自己的作品帮助更多人丰富殖民地故事。

---

## 📖 这是什么？

| 组件 | 说明 |
|---|---|
| 🎭 **角色卡** | 为殖民者或 NPC 设定性格、背景、说话风格，让 AI 更精准地扮演他们 |
| 📚 **世界书** | 定义世界观关键词，比如某个派系的历史、某件遗物的来历，对话中自动激活 |
| ⚡ **事件卡** | 驱动剧情前进的触发器，NPC 会主动来找你，推动故事发展 |

把这些组合起来，你就能在 RimWorld 里体验完整的叙事线，就像在玩一个自带剧情的 RPG。

---

## 🚀 快速上手

### 下载并使用

1. 进入 [`Stories/`](Stories/) 目录，浏览感兴趣的故事
2. 打开故事文件夹，将里面的 `.json` 文件复制到：
       RimWorld/Mods/RimTavern/
   
    ├── Cards/ ← 角色卡放这里
   
    ├── WorldBooks/ ← 世界书放这里
   
    └── Events/ ← 事件卡放这里

4. 启动 RimWorld，在 Mod 设置页点击 **"重新加载内容文件"**
5. 开始游戏，享受剧情！

## 📤 分享你的创作

欢迎所有人分享自己写的剧情组件！

1. **Fork** 本仓库
2. 按模板格式在 `Stories/` 下新建你的故事文件夹
3. 提交 **Pull Request**
---

## 📂 仓库结构
RimTavern-Community-Cards/

├── Stories/ ← 所有故事按文件夹聚合

│ ├── 01_Example_Story/ ← 每个故事独立文件夹

│ │ ├── README.md ← 故事简介 + 玩法提示

│ │ ├── Cards/ ← 角色卡（可选）

│ │ ├── WorldBooks/ ← 世界书（可选）

│ │ └── Events/ ← 事件卡（可选）

│ └── ...

## 🔧 需要帮助？

- 遇到格式问题？查看 [TEMPLATE/](TEMPLATE/) 里的示例文件
- 想验证你的 JSON 是否合法？使用 [JSONLint](https://jsonlint.com/) 或 [ajv](https://ajv.js.org/)
- 有任何疑问？在 [Issues](https://github.com/WilliamLambert1205/RimTavern-Community-Cards/issues) 提问

---

## ⚠️ 免责声明

- 社区内容由玩家自发创作，不代表 RimTavern Mod 作者立场
- 使用前请自行检查内容是否适合你的游戏版本（RimWorld 1.6+）
- 请尊重原创，转载或修改他人作品时注明来源

---

## 📜 许可证

本仓库的**结构代码**（README、脚本等）采用 MIT 许可证。  
各故事文件夹内的具体内容（JSON 卡片、文本）版权归各自作者所有，使用时请遵循作者在 `README.md` 中声明的授权方式。

---

**Happy Storytelling! 🍻**
