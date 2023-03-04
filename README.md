# ChatGPT-API Demo

A demo repo based on [OpenAI GPT-3.5 Turbo API](https://platform.openai.com/docs/guides/chat).

基于 OpenAI GPT-3.5 Turbo API 的演示存储库。

## Run Locally(本地运行）

1. Setup & Install dependencies (设置和安装依赖项)

    > First, you need [Node.js](https://nodejs.org/) installed.(首先，您需要安装 Node.js。)

    ```shell
    npm i
    ```

2. Make a copy of `.env.example`, then rename it to `.env` (创建 的副本，然后将其重命名为`.env.example` `.env`)
3. Add your [OpenAI API key](https://platform.openai.com/account/api-keys) to `.env` (将您的 OpenAI API 密钥添加到 `.env`)
    ```
    OPENAI_API_KEY=sk-xxx...
    ```
4. Run the app (运行应用)
    ```shell
    npm run dev
    ```
    
## Deploy With Vercel （使用 Vercel 进行部署）

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fddiu8081%2Fchatgpt-demo&env=OPENAI_API_KEY&envDescription=OpenAI%20API%20Key&envLink=https%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys)

注 ：部署完成之后，国内进不去，得使用魔法！

## License 

MIT

麻省理工学院

## 来源 ：

[Github](https://github.com/ddiu8081/chatgpt-demo)
