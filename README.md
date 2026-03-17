# 贾维斯AI助手审核材料

此仓库包含贾维斯AI助手在QQ开放平台审核所需的材料：

## 📄 文件列表

1. **privacy-policy.html** - 隐私政策文档
2. **service-agreement.html** - 服务协议文档
3. **.nojekyll** - 禁用Jekyll处理（确保HTML正常显示）
4. **CNAME** - 自定义域名配置（可选）

## 🔗 链接格式

### GitHub Pages链接（部署后）
- **隐私政策**：https://[您的用户名].github.io/jarvis-privacy-policy/privacy-policy.html
- **服务协议**：https://[您的用户名].github.io/jarvis-privacy-policy/service-agreement.html

### 示例（假设用户名为`jarvis-ai`）
1. https://jarvis-ai.github.io/jarvis-privacy-policy/privacy-policy.html
2. https://jarvis-ai.github.io/jarvis-privacy-policy/service-agreement.html

## 🚀 部署步骤

### 方法一：GitHub网页上传（推荐新手）
1. 访问 https://github.com/new
2. 创建仓库：`jarvis-privacy-policy`
3. 权限：**Public**（必须公开）
4. 不初始化README.md
5. 上传本目录所有文件
6. 进入仓库 Settings → Pages
7. 选择 Branch: main, Folder: / (root)
8. 点击 Save

### 方法二：Git命令行
```bash
# 初始化仓库
git init
git add .
git commit -m "Add privacy policy and service agreement for Jarvis AI Assistant"

# 添加远程仓库（替换[用户名]和[Token]）
git remote add origin https://[Token]@github.com/[用户名]/jarvis-privacy-policy.git

# 推送代码
git push -u origin main
```

### 方法三：GitHub Desktop
1. 下载GitHub Desktop
2. 创建新仓库：`jarvis-privacy-policy`
3. 将本目录所有文件拖入仓库
4. 提交更改
5. 发布到GitHub

## ⏱️ 部署时间线
- **文件上传**：1-2分钟
- **GitHub Pages激活**：1-2分钟
- **首次访问**：部署后约2-3分钟
- **稳定访问**：部署后约5-10分钟

## ✅ 验证部署成功
1. ✅ 页面正常加载，无404错误
2. ✅ 内容完整显示，无乱码
3. ✅ 链接稳定，可重复访问
4. ✅ 无需登录即可访问（公开）

## 🎯 在QQ开放平台使用
1. 登录 https://q.qq.com
2. 进入应用管理
3. 找到AppID: `1903550362`（贾维斯）
4. 填写上述两个链接
5. 提交审核申请

## 🛡️ 隐私和安全说明
- 所有数据处理在用户本地设备完成
- 零数据上传到云端服务器
- 使用HTTPS加密通信
- 临时内存处理，不保存对话历史

## 📞 技术支持
如有问题，请参考：
- QQ开放平台文档：https://q.qq.com/wiki/
- GitHub Pages文档：https://docs.github.com/pages
- GitHub支持：https://support.github.com

## 📝 许可证
这些文档仅用于贾维斯AI助手在QQ开放平台的审核目的。

---
**最后更新**：2026年3月17日
**机器人名称**：贾维斯
**AppID**：1903550362