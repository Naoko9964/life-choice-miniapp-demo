# Life Choice Miniapp Demo

一个围绕「重大选择、了解自己、职业人生模拟」的小程序原型包。

## GitHub 交付

- 项目仓库：[Naoko9964 life-choice-miniapp-demo](https://github.com/Naoko9964/life-choice-miniapp-demo)。
- 完整交付包：[life-choice-miniapp-demo.zip](https://github.com/Naoko9964/life-choice-miniapp-demo/releases/download/v0.1.0-demo/life-choice-miniapp-demo.zip)。
- 版本页面：[v0.1.0-demo](https://github.com/Naoko9964/life-choice-miniapp-demo/releases/tag/v0.1.0-demo)。

完整交付包保留原目录结构，包含源代码、题库、六型人格与互动表情、架构文档、中英文设计稿和角色预览图。解压后进入 `life-choice-miniapp-demo` 目录，再按下方步骤启动本地演示。

## 交付内容

- `docs/architecture.md`：产品架构、技术架构、数据模型、上线策略。
- `data/questions.json`：65 道选择题题库与计分维度。
- `data/personas.json`：人物画像、职业推荐、人生模拟素材。
- `prototype/index.html`：可直接演示的静态交互 demo。
- `prototype/styles.css`：清爽活泼的界面样式。
- `prototype/app.js`：测评、画像、岗位推荐、模拟器交互逻辑。
- `assets/canva-demo-mockup.png`：用于 Canva 转换的高保真展示底图。
- Canva 可编辑 demo：[编辑链接](https://www.canva.com/d/ptpNbkXQjL6pCZO)，[查看链接](https://www.canva.com/d/V-Aq2po-7UlhAEH)。
- 中文 Canva demo：[编辑链接](https://www.canva.com/d/yibzjKR9FUuyipp)，[查看链接](https://www.canva.com/d/KF43aRRcrVBNIbT)。
- 六型人格解析 demo：[编辑链接](https://www.canva.com/d/7UZLjKgaRtPrcdG)，[查看链接](https://www.canva.com/d/oxp1B0ffQL87tRF)。
- English persona analysis demo：[编辑链接](https://www.canva.com/d/EgjlMAuQ--u_5py)，[查看链接](https://www.canva.com/d/eLp_1FEnfU1fb_h)。

## 快速预览

由于原型会读取 `data/` 里的 JSON，建议从仓库根目录启动本地服务：

```bash
python -m http.server 8765
```

然后访问：

```text
http://localhost:8765/prototype/index.html
```

## MVP 核心路径

1. 用户完成 65 道选择题。
2. 系统输出人物画像、优势、风险提醒。
3. 系统推荐合适行业与岗位。
4. 用户选择岗位后进入人生模拟器。
5. 模拟器描述工作环境、日常任务、人际关系、突发事件、最高频日常与意义感。

## 建议仓库名

```text
life-choice-miniapp-demo
```
