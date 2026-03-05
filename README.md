# 🛁 バスボール魔法 · Bath Ball Magic Demo

## 📁 文件结构

```
bathball/
├── unicorn.html    ← 🦄 ユニコ 页面
├── mermaid.html    ← 🧜 マリエル 页面
├── dragon.html     ← 🐲 ドラゴン 页面
└── qr.html         ← 二维码生成页面（印刷用）
```

---

## 🚀 GitHub Pages 部署步骤（10分钟搞定）

### 第一步：创建仓库
1. 登录 [github.com](https://github.com)
2. 右上角 **+** → **New repository**
3. Repository name 填：`bathball`
4. 选 **Public**（免费必须公开）
5. 点 **Create repository**

### 第二步：上传文件
1. 在新仓库页面点 **uploading an existing file**
2. 把 `unicorn.html` `mermaid.html` `dragon.html` `qr.html` 全部拖进去
3. 点 **Commit changes**

### 第三步：开启 GitHub Pages
1. 仓库页面 → **Settings**
2. 左侧菜单 → **Pages**
3. Source 选 **Deploy from a branch**
4. Branch 选 **main** → 文件夹选 **/ (root)**
5. 点 **Save**
6. 等 1-2 分钟，你的访问地址就是：
   ```
   https://你的用户名.github.io/bathball/unicorn.html
   https://你的用户名.github.io/bathball/mermaid.html
   https://你的用户名.github.io/bathball/dragon.html
   ```

### 第四步：生成并下载二维码
1. 打开 `https://你的用户名.github.io/bathball/qr.html`
2. 三个角色的二维码自动生成 ✅
3. 点「⬇ QRをダウンロード」下载PNG
4. 印刷贴到玩具卡片/浴球包装上 ✅

---

## 🎵 配音说明（Web Speech API）

- ✅ 完全免费，零服务器费用
- ✅ iOS Safari / Android Chrome 均支持日语
- ✅ 各角色音色不同：ユニコ高音萝莉、ドラゴン低沉男声
- ⚠️ 部分Android机器日语语音包需手动安装（设置→语言→TTS）

---

## 🔧 修改台词

找到 HTML 文件中的这段代码直接改：

```javascript
const slogans = [
  '一句目の台詞...',
  '二句目の台詞...'
];
```

改完重新上传到 GitHub 即可，二维码不变。
