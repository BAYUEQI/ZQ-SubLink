# ZQ-SubLink

基于 vue-cli 与 [BAYUEQI/ZQ-SubApi](https://github.com/BAYUEQI/ZQ-SubApi) 后端实现的配置自动生成。

---

## 本地开发

1. 安装依赖

```bash
yarn install
```

2. 本地运行

```bash
yarn serve
```

3. 代码检查

```bash
yarn lint
```

## 构建产物

项目构建后的产物会输出到 `dist` 目录：

```bash
yarn build
```

## 部署到 Vercel

1. **Vercel 项目创建**  
   在 [Vercel 官网](https://vercel.com/) 新建项目，选择本仓库。

2. **设置构建命令和输出目录**  
   - 构建命令：`yarn build`
   - 输出目录：`dist`
   - 部署命令：`yarn deploy`

3. **环境变量（如有需要）**  
   可在 Vercel 项目设置中添加所需的环境变量。

4. **自动部署**  
   每次推送到主分支，Vercel 会自动构建并部署。

## 目录说明

- `src/`  源码目录
- `public/`  公共资源
- `dist/`  构建产物（自动生成）
- `vue.config.js`  构建配置

---

如需进一步自定义部署或遇到问题，可参考 [Vercel 官方文档](https://vercel.com/docs) 或在 Issues 区提问。


