# GitHub Pages 部署详细步骤

## 1. 创建GitHub账号
1. 访问 [github.com](https://github.com)
2. 点击右上角"Sign up"按钮
3. 填写用户名、邮箱、密码（建议使用常用邮箱）
4. 完成邮箱验证

## 2. 创建代码仓库
```bash
# 在项目目录初始化git
cd d:\测试
git init
git add .
git commit -m "初始提交"

# 创建远程仓库（网页端操作）
1. 登录GitHub点击右上角+号 → New repository
2. 仓库名称填：light-tool
3. 选择 Public 可见性
4. 点击 Create repository

# 关联远程仓库
git remote add origin https://github.com/[你的用户名]/light-tool.git
```

## 3. 上传代码文件
```bash
# 推送本地代码（确保已添加文件）
git add index.html
git commit -m "添加网页文件"
git push -u origin main
```

## 4. 启用GitHub Pages
1. 进入仓库 Settings → Pages
2. 在 Branch 选择 main 分支
3. 点击 Save 保存设置
4. 等待2分钟后访问：https://[你的用户名].github.io/light-tool

## 5. 后续更新流程
```bash
# 修改代码后执行
git add .
git commit -m "更新说明"
git push
```

> 小贴士：部署成功后建议绑定自定义域名（需在域名服务商处配置CNAME）