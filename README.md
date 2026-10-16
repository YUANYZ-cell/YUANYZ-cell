# Peixi YU · Selected Projects

你好，我是 Peixi YU。这是我围绕学习、桌面效率与日常生活构建的六个项目。

I build practical tools for learning, desktop workflows, and everyday life.

Python · C# / WPF · React · TypeScript · Electron · SQLite

## 作品集 / Portfolio

| 项目源码 | 解决的问题 |
| --- | --- |
| [**MathCode · 数学 × 编程**](https://github.com/YUANYZ-cell/mathcode) | 把读题、知识点回顾、C++ 编码与练习复盘放在一个离线桌面工作区。 |
| [**Report Formatter · 报告格式化器**](https://github.com/YUANYZ-cell/report-formatter) | 用可解释的规则检查并整理实验报告中的图表、公式编号与引用。 |
| [**My Vocabulary · 我的词汇本**](https://github.com/YUANYZ-cell/my-vocabulary) | 将英语词汇、固定搭配、阅读素材与生活口语统一收录并分开复习。 |
| [**Desktop Dynamic Island · 桌面灵动岛**](https://github.com/YUANYZ-cell/desktop-dynamic-island) | 用轻量胶囊与展开面板查看电脑负载，并在持续越界时提醒。 |
| [**Family Menu · 家常一桌**](https://github.com/YUANYZ-cell/family-menu) | 根据就餐人数、食材、口味与近期用餐记录生成一桌家常菜。 |
| [**Arpeggio · 吉他曲谱档案馆**](https://github.com/YUANYZ-cell/arpeggio) | 把图片或 PDF 曲谱整理成可检索、可阅读、可演奏的本地档案。 |

## 项目亮点

### [MathCode · 数学 × 编程](https://github.com/YUANYZ-cell/mathcode)

Offline learning workspace for mathematics and C++.

- 按主题组织课程与题目，阅读时保留当前题目和草稿。
- 目录恢复筛选、页码、滚动和焦点，减少学习过程中的来回寻找。
- 个人练习记录、代码目录管理与版本快照，SQLite 本地持久化。

### [Report Formatter · 报告格式化器](https://github.com/YUANYZ-cell/report-formatter)

Rule-based DOCX formatting and PDF report analysis.

- 支持 IEEE、模板匹配与自定义格式，提供中英文界面。
- 分析图题、表题、公式和文内交叉引用，保留报告正文。
- Word 可分析或格式化，PDF 提供分析报告；真实页面预览按本机转换器可用性启用。

### [My Vocabulary · 我的词汇本](https://github.com/YUANYZ-cell/my-vocabulary)

Local-first vocabulary capture and adaptive review.

- 本地粘贴识别、CSV 导入导出、标签和专业词汇分类。
- 累计错误参与自适应复习，支持单词与固定搭配组合复习。
- 搜索保留输入焦点和光标，阅读与集中复习各自有清晰入口。

### [Desktop Dynamic Island · 桌面灵动岛](https://github.com/YUANYZ-cell/desktop-dynamic-island)

Native Windows performance monitoring in a compact desktop widget.

- CPU、RAM、GPU、VRAM 与 GPU 温度，可信数据不可用时显示占位。
- 胶囊展开、拖拽定位、托盘控制、全屏和远程桌面场景抑制。
- 持续时间、恢复与冷却共同控制告警，避免重复弹出。

### [Family Menu · 家常一桌](https://github.com/YUANYZ-cell/family-menu)

Preference-aware meal planning with local browser storage.

- 加权生成整桌菜单，支持整桌重抽、单道替换、加菜和删菜。
- 管理菜品、食材、家庭成员、偏好及菜单预设。
- 数据保存在 IndexedDB，提供桌面浏览器与 Windows 独立窗口入口。

### [Arpeggio · 吉他曲谱档案馆](https://github.com/YUANYZ-cell/arpeggio)

A Windows guitar-score archive, reader and performance workspace.

- 按木吉他与电吉他归档，支持标签、收藏、哈希去重与 JSON sidecar。
- 阅读位置恢复、单页和双页阅读、全屏演奏与定时翻页。
- Electron 主进程管理文件和数据库，窄 IPC 与受限资源协议连接阅读界面。

## 如何查看

各项目仓库包含源码、安装运行说明与验证记录。Windows 桌面项目需要在 Windows 上构建；家常一桌可运行在桌面浏览器中。这里展示的是可审阅的源码快照，不是在线托管的六个应用。

个人学习数据、学校原始课件、私人曲谱和本机配置未公开。项目使用的第三方组件保留各自许可说明。
