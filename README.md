# vue-chart-admin
vue3 + echart quick template

vue-chart-admin 是一款大屏前端项目解决方案，它基于了 [vue3](https://cn.vuejs.org/) 与 [echarts](https://echarts.apache.org/examples/zh/index.html#chart-type-line) 共同打造。大量使用了前沿的技术栈。其中就包括了 [栅格](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Grid_Layout) 为主布局方式，适合于 vue3 的数据状态管理 [pinia](https://pinia.vuejs.org/)，原子化 css 解决方案 [tailwindcss](https://www.tailwindcss.cn/)，以 hook 方式使用 echarts [@pureadmin/utils](https://www.npmjs.com/package/@pureadmin/utils)，[naive-ui](https://www.naiveui.com/zh-CN/light)。希望本项目能够帮助到你，搭建出美观大方，可用，可维护的大屏前端项目。

- [在线预览]()

## 使用前的一些了解

为了分享出这款项目的集成心得，特地准备了几篇文档，供你来了解项目的来龙去脉

- [栅格布局的巧用]()

- [以 hook 方式调用 echarts 相当不错]()

- [图表的数据响应逻辑究竟该怎么写，才是最优的]()

- [小彩蛋，v-modal-hook]()

## 开发

```bash
# 克隆项目
git clone https://github.com/HuziG/vue-chart-admin

# 进入项目目录
cd vue-chart-admin

# 安装依赖
pnpm install
```

## 发布

```bash
# 构建测试环境
pnpm run build:stage

# 构建生产环境
pnpm run build:prod
```

# 启动服务

```bash
pnpm run dev
```

