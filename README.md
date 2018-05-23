# laravel_weapp

## 功能如下
<ul>
<li>用户认证 —— 注册、登录、退出；</li>
<li>个人页面 —— 用户个人信息，编辑资料，上传头像；</li>
<li>用户授权 —— 作者才能删除自己的内容；</li>
<li>话题 —— 列表，详情，删除；</li>
<li>话题回复 —— 列表，发布，删除；</li>
<li>消息通知 —— 轮训显示消息提示，消息列表，标记已读；</li>
<li>用户权限；</li>
<li>页面分享；</li>
</ul>

## 运行环境要求
WePY 1.7+

## 开发环境部署/安装
本项目代码使用 WePY 框架 WePY 开发

基础安装
1. 克隆源代码
克隆 larabbs-weapp 源代码到本地：

    git clone git@github.com:summerblue/larabbs-weapp.git
  
2. 安装扩展包依赖

    yarn
    yarn global add wepy-cli
    
3. 编译

    npm run build
