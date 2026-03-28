# Vercel Environment Variables Setup

## 在 Vercel 后台设置以下环境变量：

### 1. TTS API Key (Token Plan - 免费额度)
- **Name**: `VITE_TTS_API_KEY`
- **Value**: `sk-cp-JoIfnsjVVh9cj3XTsh1qJp5h7-ycQ123inQ_iCH6pZQQk0XETc-EVhmnigVWvKC5ZMs93tDfvdotIs3XeQ6QjBx3D2pbLuRVHGZngtiEYItYxCJskSE-k2U`

### 2. Clone API Key (充值账户)
- **Name**: `VITE_CLONE_API_KEY`
- **Value**: `sk-api-yXFnQS0j35uT7nctbZCSzjeeDWwNzHRkY0L4W4OY4CyYHEtPhNxA65pOIl4YusQC3Kb9jJ8K5NFwKkf19e6Kalz7NlZlHey_jEHLp50GLOTKuyolL-ALLR8`

## 设置步骤：

1. 打开 Vercel 项目 Dashboard
2. 点击 Settings
3. 左侧菜单点击 Environment Variables
4. 逐个添加以上变量
5. 如果需要重新部署，点击 Deployments -> Redeploy

## 注意

环境变量名前缀必须是 `VITE_` 才能在客户端代码中访问。
