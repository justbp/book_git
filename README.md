# 书籍资料库

个人书籍阅读笔记和资料整理项目。

## 项目结构

```
book_git/
├── README.md           # 项目说明
├── books/              # 书籍资料目录
│   ├── technical/     # 技术类书籍
│   ├── literature/    # 文学类书籍
│   ├── history/       # 历史类书籍
│   └── other/         # 其他类别
└── notes/             # 读书笔记
```

## 使用说明

1. 在 `books/` 目录下按分类存放书籍相关资料
2. 在 `notes/` 目录下存放读书笔记
3. 使用 Markdown 格式编写笔记，便于阅读和版本控制

## Git 使用

### 首次推送到远程仓库

```bash
# 添加远程仓库（替换为你的仓库地址）
git remote add origin <你的仓库地址>

# 推送到远程
git push -u origin main
```

### 日常使用

```bash
# 添加更改
git add .

# 提交更改
git commit -m "描述你的更改"

# 推送到远程
git push
```

## 注意事项

- 定期提交和推送，避免资料丢失
- 使用有意义的提交信息
- 大文件建议使用 Git LFS 或外部存储

