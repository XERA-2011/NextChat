# X-test

## Vercel 环境变量同步到本地

> 先得在自己的 Vercel 项目中设置好环境变量，然后才能同步到本地。


```bash

# 安装 Vercel CLI
npm install -g vercel

# 登录
vercel login

# 链接项目
vercel link

# 列出环境变量
vercel env ls

# 下载环境变量
vercel env pull .env.local

```
