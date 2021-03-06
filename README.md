## 说明
* copy from： https://github.com/QxQstar/react-demo
* 作者博客：http://www.cnblogs.com/QxQstar/

## 安装
> 进入react-oa目录，然后在命令行中输入npm install
## 运行
> 在react-oa目录，npm start
## 注意
> 由于这个demo接入了数据库mongodb，所有要安装mongodb才能运行完整的功能!!!(员工管理和部门管理中用到了数据库)。安装了mongodb还需要启动
  mongodb
> 还有很多不足的地方会持续改进
## 技术栈
* React v15.6.2
* react-redux
* redux
* react-router-dom
* webpack
* nodeJs
* mongodb
* axios
## 项目架构
```
react-oa/                      # 源码目录
  ├─ config/                  # 服务配置文件
  ├─ controller              # 处理网络请求
  ├─ note                    #学习笔记
  ├─ ├─img                  #截图
  ├─ model/                   # mongoose Model
  ├─ route/                   # nodeJs 路由配置
  ├─ schema/                 # mongoose Schema
  ├─ scripts/                # 启动服务的文件
  ├─ src/                    # react代码从这里开始
  │   ├─ components/          # 全局组件
  │   ├─ css/                 # 全局css样式
  |   ├─ global/             # 全局方法
  |   ├─ pages/              # 页面
  |   |     |── att/          # 考勤分组模块
  |   |     |── attendance/   # 通讯录模块
  |   |     |── department/   # 部门管理模块
  |   |     |── holiday/      # 假期管理
  |   |     |── member/       # 员工管理
  |   ├─ router/             # router
  |   ├─ store/              # redux
  |   ├─ App.css
  |   ├─ App.js
  |   ├─ index.css
  |   ├─ index.js            # 入口

```

## 学习笔记
> 关于react的学习笔记都在note文件夹下面
## 截图
> 通讯录
![通讯录-公司职员列表截图](./note/img/addressBook.png)
> 假期管理
![假期管理-假期类型列表截图](./note/img/holiday.png)
> 考勤分组
![考勤分组-分组列表截图](./note/img/group.png)
> 选择人员
![选择人员弹窗](./note/img/addGroup.png)
> 员工管理
![员工列表](./note/img/member.png)
> 部门管理
![部门管理列表](./note/img/dept.png)
