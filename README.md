# 📌 BackEnd Project Modulation System

```bash
📂 Backend-Project
├── 📂 node_modules/
├── 📄 .env
├── 📄 .gitignore
├── 📄 .prettierrc.json
├── 📄 .eslintrc.cjs
├── 📄 package.json
├── 📄 package-lock.json
├── 📄 tsconfig.json
├── 📄 README.md
├── 📂 src/
│ ├── 📂 app/
│ │ ├── 📂 middleware/
│ │ │ ├── 📄 auth.middleware.ts
│ │ │ ├── 📄 globalErrorHandler.ts
│ │ │ ├── 📄 notFound.ts
│ │ │ └── 📄 request.ts
│ │ ├── 📂 router/
│ │ │ ├── 📄 index.ts
│ │ │ ├── 📄 routes.ts
│ │ ├── 📂 utils/
│ │ │ ├── 📄 catchAsync.ts
│ │ │ └── 📄 sendResponse.ts
│ │ ├── 📄 app.ts
│ │ └── 📄 server.ts
│ ├── 📂 Builder/
│ │ ├── 📄 QueryBuilder.ts
│ ├── 📂 config/
│ │ └── 📄 index.ts
│ ├── 📂 Errors/
│ │ ├── 📄 ApiError.ts
│ │ ├── 📄 handleMongooseCastError.ts
│ │ ├── 📄 handleMongooseError.ts
│ │ ├── 📄 handleValidationError.ts
│ │ └── 📄 handleZodError.ts
│ ├── 📂 interface/
│ │ ├── 📄 global.interface.ts
│ │ └── 📄 index.ts
│ ├── 📂 modules/
│ │ └── 📂 Auth/
│ │ ├── 📄 auth.constant.ts
│ │ ├── 📄 auth.interface.ts
│ │ ├── 📄 auth.model.ts
│ │ ├── 📄 auth.route.ts
│ │ ├── 📄 auth.service.ts
│ │ ├── 📄 auth.util.ts
│ │ └── 📄 index.ts
│ └── 📄 index.ts
```

## 🚀 Setup and Installation

**1️⃣ Project Initialization**:

    ```bash
        npm init -y
    ```

**2️⃣ Install Required Packages**:

    ```bash
        npm i express cors dotenv mongoose
    ```

**3️⃣ Setup TypeScript**:

    ```bash
        npm install --save-dev typescript
        tsc --init
        npm i ts-node-dev --save-dev

    ```

**4️⃣ Setup ESLint and Prettier**:

    ```bash
        npm install eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev
        npx eslint --init
        npm install --save-dev prettier
        npm install --save-dev eslint-config-prettierrc

    ```

**5️⃣ Install Type Definitions**:

    ```bash
       npm i @types/cors @types/express @types/node
    ```
