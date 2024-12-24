# My Vue Tailwind Project

这是一个使用 Vue.js 和 Tailwind CSS 构建的项目。

## 项目结构

```
my-vue-tailwind-project
├── public
│   └── index.html          # 应用的主 HTML 文件，包含 Vue 应用的挂载点
├── src
│   ├── assets              # 存放项目的静态资源，如图片和字体
│   ├── components
│   │   └── iFrame.vue      # 渲染 iframe 的 Vue 组件
│   ├── views
│   │   └── index.vue       # 使用 iFrame 组件的视图组件
│   ├── App.vue             # 应用的根组件
│   ├── main.js             # 应用的入口文件
│   └── styles
│       └── tailwind.css    # Tailwind CSS 的样式文件
├── package.json            # npm 的配置文件
├── postcss.config.js       # PostCSS 的配置文件
├── tailwind.config.js      # Tailwind CSS 的配置文件
└── README.md               # 项目的文档和说明
```

## 安装依赖

在项目根目录下运行以下命令以安装依赖：

```
npm install
```

## 启动项目

使用以下命令启动开发服务器：

```
npm run serve
```

## 贡献

欢迎任何形式的贡献！请提交问题或拉取请求。

## 许可证

此项目采用 MIT 许可证。