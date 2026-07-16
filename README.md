# TuanZiLuLu 工作室网站 - 操作指南

## 📌 网站信息

### 🌐 三个网址（都能访问同一个网站）

| 网址名称 | 网址地址 | 说明 |
|---------|---------|------|
| **根域名** | https://tuanzilulu.xyz | ⭐ 推荐使用！短、好记、专业 |
| **www域名** | https://www.tuanzilulu.xyz | 更正式的版本 |
| **临时地址** | https://tuanzilulu-website.colinjacobsonfbp.workers.dev | 永久可用，但太长不好记 |

### 📁 其他信息

| 项目 | 内容 |
|------|------|
| 源文件位置 | `D:\Users\li\桌面\前端网页的宣传\index.html` |
| GitHub仓库 | https://github.com/stlldsa/tuanzilulu-website |

---

## 🔄 更新网站的方法

### 方法一：自己手动更新

#### 第一步：修改网站内容

1. 打开文件夹：
   ```
   D:\Users\li\桌面\前端网页的宣传
   ```

2. 右键点击 `index.html`，选择"用记事本打开"或"用 VS Code 打开"

3. 修改你想要改的内容：
   - **改文字**：找到对应的文字，直接修改
   - **改颜色**：找到颜色代码（如 `#0ea5e9`），改成你想要的颜色
   - **改视频**：找到视频链接，换成你的视频链接

4. 保存文件（按 `Ctrl + S`）

#### 第二步：推送到 GitHub

1. 打开命令提示符：
   - 按 `Win + R`
   - 输入 `cmd`
   - 按回车

2. 输入以下命令（一行一行输入）：
   ```bash
   cd "D:\Users\li\桌面\前端网页的宣传"
   git add .
   git commit -m "更新网站内容"
   git push
   ```

3. 等待 1-2 分钟

4. 打开 https://tuanzilulu.xyz 查看更新

---

### 方法二：找 AI 帮忙更新

#### 使用 Claude Code（推荐）

1. 打开 Claude Code（就是你现在用的这个工具）

2. 告诉 AI 你想要改什么，比如：
   ```
   帮我把网站上的"联系我们"改成"立即咨询"
   ```

3. AI 会自动帮你修改文件并推送

4. 等待 1-2 分钟，网站就更新了！

#### 使用其他 AI 工具

1. 打开 ChatGPT、Claude 网页版、或其他 AI 工具

2. 把 `index.html` 的内容复制给 AI

3. 告诉 AI 你想要改什么

4. AI 会给你修改后的代码

5. 把代码复制回 `index.html`，保存

6. 推送到 GitHub（方法同上）

---

## 📊 两种方法对比

| 方法 | 优点 | 缺点 | 适合场景 |
|------|------|------|---------|
| **自己手动** | 完全控制、不需要网络 | 需要懂一点代码 | 小改动（改几个字） |
| **找 AI 帮忙** | 简单快速、不需要懂代码 | 需要网络 | 大改动（改布局、加功能） |

---

## 🎯 常见修改示例

### 修改工作室名称

找到：
```html
<a href="#" class="text-2xl font-bold gradient-text">TuanZiLuLu</a>
```

改成：
```html
<a href="#" class="text-2xl font-bold gradient-text">你的工作室名称</a>
```

### 修改联系电话

找到：
```html
<div class="font-medium">hello@tuanzilulu.xyz</div>
```

改成：
```html
<div class="font-medium">你的联系电话</div>
```

### 修改服务项目

找到服务卡片部分，修改标题和描述即可。

---

## ⚠️ 注意事项

1. **修改前先备份**
   - 复制一份 `index.html` 作为备份

2. **修改后一定要推送**
   - 否则网站不会更新

3. **等待时间**
   - 推送后需要 1-2 分钟才能看到更新

4. **测试网站**
   - 修改后打开 https://tuanzilulu.xyz 检查效果

---

## 🆘 遇到问题？

### 问题1：git push 失败

**解决方法**：
```bash
# 先检查网络连接
ping github.com

# 如果网络正常，重新输入
git push
```

### 问题2：网站没有更新

**解决方法**：
- 检查是否推送成功
- 等待 2-3 分钟
- 清除浏览器缓存（按 `Ctrl + F5` 刷新）

### 问题3：网站打不开

**解决方法**：
- 检查域名是否正确：https://tuanzilulu.xyz
- 等待几分钟再试
- 检查网络连接

---

## 📞 联系方式

如果遇到问题，可以：
- 查看 GitHub 仓库：https://github.com/stlldsa/tuanzilulu-website
- 在 GitHub 上提交 Issue

---

**最后更新时间**：2024年
