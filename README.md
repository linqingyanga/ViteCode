# ViteCode
# 一、初始化Vite项目
> 注意：Vite 需要 Node.js 版本 14.18+，16+

## 1.1 搭建第一个 Vite 项目
```
npm create vite@latest

cd vite-project
npm install
npm run dev
```

## 1.2 构建一个 Vite + Vue 项目
```
npm create vite@latest my-vue-app --template vue

cd my-vue-app
npm install
npm run dev
```

## 1.3 构建其他项目
```
# npm 6.x
npm create vite@latest my-vue-app --template vue

# npm 7+, extra double-dash is needed:
npm create vite@latest my-vue-app -- --template vue

# yarn
yarn create vite my-vue-app --template vue

# pnpm
pnpm create vite my-vue-app --template vue
```