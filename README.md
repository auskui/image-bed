# Obsidian Image Bed

这是一个用于 Obsidian 笔记的图片存储仓库，支持工作和个人使用的分类管理。

## 目录结构

```
├── work/                    # 工作相关图片
│   ├── projects/           # 项目图片
│   │   ├── project-a/      # 项目A相关图片
│   │   └── project-b/      # 项目B相关图片
│   ├── meetings/           # 会议相关图片
│   └── documents/          # 文档相关图片
├── personal/               # 个人使用图片
│   ├── notes/              # 笔记图片
│   ├── photos/             # 个人照片
│   └── resources/          # 资源文件
│       ├── templates/      # 模板图片
│       └── assets/         # 素材图片
└── archive/                # 归档图片
```

## 使用方法

### 1. 图片命名规范
- 使用英文和数字，避免中文和特殊字符
- 格式：`类别-描述-日期.jpg`
- 示例：`work-meeting-20241201.jpg`

### 2. 图片链接格式
```
https://raw.githubusercontent.com/你的用户名/obsidian-image-bed/main/work/projects/project-a/图片名.jpg
```

### 3. 在 Obsidian 中使用
1. 将图片上传到对应文件夹
2. 复制图片的 raw 链接
3. 在 Obsidian 中使用 `![描述](链接)` 格式插入

## 注意事项

- 请保持文件夹结构清晰
- 定期清理不需要的图片
- 注意图片大小，建议单张不超过 5MB
- 敏感信息请勿上传到公开仓库

## 更新日志

- 2024-12-01: 初始化仓库结构
