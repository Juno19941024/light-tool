# 简易光源网页应用需求说明

## 项目目标
创建一个简单的网页应用，用作黑夜里的光源工具。

## 核心功能需求
1. 基本显示
   - 网页全屏显示光源
   - 背景颜色可调节

2. 控制功能
   - 亮度调节滑块
     * 左右滑动控制屏幕亮度
     * 从暗到亮渐变调节
   
   - 色温调节滑块
     * 左右滑动控制光线色温
     * 可在冷色调与暖色调之间切换

## 技术实现
- 使用HTML+CSS+JavaScript实现
- 通过滑块控件实现交互
- 使用RGB颜色值计算实现色温变化
- 添加平滑过渡效果

## 已实现功能
- [x] 全屏显示界面
- [x] 亮度调节滑块
- [x] 色温调节滑块
- [x] 平滑的颜色过渡效果
- [x] 移动设备适配

## 部署方案
### 方案1：GitHub Pages（推荐）
1. 创建 GitHub 账号
   - 访问 https://github.com
   - 点击右上角 "Sign up" 按钮
   - 填写：
     - 用户名（Username）
     - 电子邮箱（Email）
     - 密码（Password）
   - 验证账号并完成注册
2. 创建新的代码仓库 (Repository)
   - 仓库名称可以设置为：light-tool
   - 选择 "Public" 公开仓库
3. 上传项目文件
   - 上传 index.html 文件
4. 开启 GitHub Pages
   - 进入仓库设置 (Settings)
   - 找到 Pages 选项
   - 选择 main 分支作为源
   - 保存后等待几分钟
5. 访问地址
   - 形如：https://你的用户名.github.io/light-tool

### 方案2：Netlify（也是免费的）
1. 注册 Netlify 账号
2. 点击 "New site from Git"
3. 选择 "Deploy manually"
4. 直接拖拽文件夹到上传区域
5. 完成部署，获得网址

### 方案3：Vercel（免费）
1. 注册 Vercel 账号
2. 创建新项目
3. 导入项目文件
4. 自动部署完成
