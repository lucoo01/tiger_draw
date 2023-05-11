# 跳跳虎AI
> 一款利用 AI 帮你的草图快速变成作品的工具

[](c1.png)

## 安装和使用

1. 安装Node.js
1. 复制 [Replicate API token](https://replicate.com/account?utm_source=project&utm_campaign=scribblediffusion) 到环境变量文件:
   ```
   echo "REPLICATE_API_TOKEN=<your-token-here>" > .env.local
   ```
1. 安装依赖并启动:
   ```
   npm install
   npm run dev
   ```
1. 打开浏览器 [localhost:3000](http://localhost:3000) 

> 注意: 存储用到了 upload.io, 请自己到 lib/upload.js 更换密钥
