<!-- markdownlint-disable MD030 -->

# AGICrypto - AI Crypto LangchainJS Based TaskFlow Builder

![AICrypto](https://github.com/metagineers/agicrypto/blob/main/images/agicrypto.gif?raw=true)

Drag & drop AI Crytpo TaskFlow builder using framework: 
* Building applications with LLMs through composability [LangchainJS](https://github.com/hwchase17/langchainjs)
* AI Flow Builder derived and inspired by [Flowise](https://github.com/FlowiseAI/Flowise)

## 👨‍💻 Developers

Flowise has 3 different modules in a single mono repository.

-   `server`: Node backend to serve API logics
-   `ui`: React frontend
-   `components`: Langchain components

### Prerequisite

-   Install Yarn
    ```bash
    npm i -g yarn
    ```

### Setup

1. Clone the repository

    ```bash
    git clone https://github.com/FlowiseAI/Flowise.git
    ```

2. Go into repository folder

    ```bash
    cd Flowise
    ```

3. Install all dependencies of all modules:

    ```bash
    yarn install
    ```

4. Build all the code:

    ```bash
    yarn build
    ```

5. Start the app:

    ```bash
    yarn start
    ```

    You can now access the app on [http://localhost:3000](http://localhost:3000)

6. For development build:

    ```bash
    yarn dev
    ```

    Any code changes will reload the app automatically on [http://localhost:3000](http://localhost:3000)

## 🔒 Authentication

To enable app level authentication, add `USERNAME` and `PASSWORD` to the `.env` file in `packages/server`:

```
USERNAME=user
PASSWORD=1234
```

## 🐳 Docker (Work In Progress - For Future Deployment)

The docker build flow is still in progress to refactor the one done in the orignal Flowise project.

Coming soon

## 📖 Documentation

Coming soon

## 💻 Cloud Hosted

Coming soon

## 🌐 Self Host

Coming soon

## 🙋 Support

Feel free to ask any questions, raise problems, and request new features in [discussion](https://github.com/metagineers/agicrypto/discussions)

## 🙌 Contributing

See [contributing guide](CONTRIBUTING.md). Reach out to us at [Discord](https://discord.gg/UyuVDqjkDy) if you have any questions or issues.

## 📄 License

Source code in this repository is made available under the [MIT License](LICENSE.md).
