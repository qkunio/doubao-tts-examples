# 豆包 TTS 声音库

豆包 TTS 2.0 可用音色的试听页面，支持按性别、年龄筛选和名称搜索。

## 架构

```
doubao-tts-examples/
├── index.html          # 试听页面
└── voice-samples/      # MP3 音频文件 + summary.json
```

## 功能

- **试听**：点击声音卡片上的"播放"按钮，底部会出现播放控制栏
- **筛选性别**：男生 / 女生
- **筛选年龄**：年轻 / 成熟（根据音色名称关键词自动分类）
- **搜索**：按音色名称或 voiceType ID 实时过滤

## 音色来源

音频文件由豆包 TTS API 生成，共包含 **100 个中文音色**，覆盖 `uranus_bigtts` 和 `saturn_tob` 两个系列。