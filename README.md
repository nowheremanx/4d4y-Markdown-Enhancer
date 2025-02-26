# 4d4y Markdown Enhancer  

## 介绍  
这是一个 **Tampermonkey** 脚本，适用于 **4d4y 论坛**，可自动将论坛帖子中的 **Markdown 语法** 转换为 **HTML**，优化阅读体验。  

## 功能  
- 自动检测并转换帖子中的 Markdown 语法，如 `# 标题`、`**加粗**`、`*斜体*`、`代码块` 等。  
- **不影响原始 HTML 格式**，不会移除图片、链接等元素。  
- **快捷键切换**（`Ctrl + M`）：
  - 默认显示转换后的 Markdown 版本。  
  - 按 `Ctrl + M` 可切换回原始文本，再次按下可恢复 Markdown 格式。  
- **切换模式时显示通知**，并会自动淡出，不影响阅读体验。  
- **不会在每次刷新页面时弹出通知**，避免干扰。  

## 安装方法  
1. **安装 Tampermonkey 插件**（如果尚未安装）：  
   - [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)  
   - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)  
   - 其他浏览器请访问 [Tampermonkey 官网](https://www.tampermonkey.net/)  

2. **安装脚本**：  
   - 打开 [Tampermonkey 控制面板](chrome-extension://dhdgffkkebhmkfjojejmpbldmpobfkfo/options.html#tab-scripts)。  
   - 点击“添加新脚本”，将脚本粘贴进去并保存。  

3. **刷新 4d4y 论坛页面，即可生效！**  

## 使用方法  
- **打开 4d4y 论坛**，帖子中的 Markdown 语法会自动转换。  
- **按 `Ctrl + M` 可切换 Markdown 显示模式**。  
- **每次切换模式时都会有通知提示**。