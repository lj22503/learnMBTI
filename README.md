---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 1c835e55ba3b06878e6538b2edadf703_886c1827beff11f18019525400248c00
    ReservedCode1: QZwfRsK8KU/QaDyl0D/qpu/GMcLxlRlfa+1xEX3ZN0grBD0hMwRjeGvpvm46m6JJqm6JY3BOY0w5XtDPtFzspYI04Pu1AswFWvMyJmS+P6fANbwnV23HSw3JTVR3tmIDBWwWBJBTkYLqk9KatguZTKr6NX5tI+1aExlE+rJOfhz1YWZaAlyULR4rkKA=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 1c835e55ba3b06878e6538b2edadf703_886c1827beff11f18019525400248c00
    ReservedCode2: QZwfRsK8KU/QaDyl0D/qpu/GMcLxlRlfa+1xEX3ZN0grBD0hMwRjeGvpvm46m6JJqm6JY3BOY0w5XtDPtFzspYI04Pu1AswFWvMyJmS+P6fANbwnV23HSw3JTVR3tmIDBWwWBJBTkYLqk9KatguZTKr6NX5tI+1aExlE+rJOfhz1YWZaAlyULR4rkKA=
---

# learnMBTI

> 家长视角的孩子学习人格测评：先懂孩子怎么学，再帮 TA 学得更顺。

learnMBTI 是一套面向家长的学习人格测评与学习支持方案。以 MBTI 风格交互呈现 16 型「学习人格」，用正面温暖的称号替代刻板标签，帮助家长理解孩子的学习偏好，并给出「这样帮 TA 学得更顺」的具体建议。

## 在线体验

- GitHub Pages 部署：<https://lj22503.github.io/learnMBTI/>
- 可交互 Demo v1.3（纯前端，无依赖，直接静态托管）：[index.html](./index.html)

## 产品逻辑

| 环节 | 说明 |
| --- | --- |
| 免费测评 | 35 题轻量测评，输出 16 型学习人格 |
| 学习人格档案 | 16 型 × 8 类型交叉报告：风格偏好、适配建议 |
| 7 天任务卡 | 可落地的亲子学习微行动，逐日打卡 |
| 21 天定制方案 | 付费转化路径（199 元），个性化学习支持 |

视觉规范：白底大留白、圆角胶囊、紫蓝主色（MBTI 测试页风格）；16 型称号一律正面温暖，不使用 SBTI 自嘲梗。

## 项目结构

```
learnMBTI/
├── index.html               # 可交互 Demo v1.3（GitHub Pages 首页）
├── README.md
├── AGENTS.md                # 项目规则（OPC OS 规范）
├── PROGRESS.md              # 进度：刘小排 11 步法
├── docs/
│   ├── learnMBTI-产品逻辑设计.md        # 产品逻辑设计
│   ├── learnMBTI-16型×8类型整合设计.md  # 16 型 × 8 类型交叉报告设计（v1.1 定稿）
│   ├── learnMBTI-招募话术三版.md        # 招募话术
│   ├── screenshots/                   # 演示截图
│   └── references/                    # 设计依据（学习观方法论、转化模块底稿）
└── archive/                 # 历史版本归档（v1/v1.1/v1.2、原型稿、旧设计）
```

## 本地运行

纯前端静态页面，任选一种方式：

```bash
# 方式一：直接双击打开 index.html
# 方式二：本地起静态服务
python -m http.server 8080
# 访问 http://localhost:8080
```

## 部署（GitHub Pages）

仓库根目录即为 Pages 站点，`index.html` 是首页。在仓库 Settings → Pages 中选择：

- Source: `Deploy from a branch`
- Branch: `main` / `root`

推送后自动生效。

## 进度

采用刘小排 11 步法推进，当前处于第 7 步「验证 MVP」。详见 [PROGRESS.md](./PROGRESS.md)。

## License

[MIT](./LICENSE) © lj22503
*（内容由AI生成，仅供参考）*
