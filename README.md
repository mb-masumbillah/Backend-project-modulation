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
│    ├── 📂 app/
│    │    ├── 📂 Builder/
│    │    │    └── 📄 QueryBuilder.ts    # এখানে class দিয়ে search,filter,pagination,sort,field করা হয় 
│    │    │
│    │    ├── 📂 config/
│    │    │    └── 📄 dotenv.index.ts     # .env file এ রাখা সকল ডাটা এখানে আসবে , then সব জায়গায় যাবে 
│    │    │
│    │    ├── 📂 Errors/                  # এই Error গুলো সব globalErrorHandler file এ যাবে 
│    │    │    ├── 📄 AppError.ts
│    │    │    ├── 📄 handleMongooseCastError.ts
│    │    │    ├── 📄 handleMongooseError.ts
│    │    │    ├── 📄 handleValidationError.ts
│    │    │    └── 📄 handleZodError.ts
│    │    │
│    │    ├── 📂 interface/
│    │    │    ├── 📄 global.interface.ts
│    │    │    └── 📄 index.d.ts
│    │    │
│    │    └── 📂 modules/
│    │      └── 📂 Auth/
│    │           ├── 📄 auth.constant.ts
│    │           ├── 📄 auth.controller.ts
│    │           ├── 📄 auth.interface.ts
│    │           ├── 📄 auth.model.ts
│    │           ├── 📄 auth.route.ts
│    │           ├── 📄 auth.service.ts
│    │           └── 📄 auth.util.ts
│    │
│    ├── 📂 middleware/
│    │     ├── 📄 auth.ts
│    │     ├── 📄 globalErrorHandler.ts    # Errors ফাইল থেকে সব Error এই ফাইল এ আসবে 
│    │     ├── 📄 notFound.ts
│    │     └── 📄 validationRequest.ts
│    │
│    ├── 📂 router/
│    │     └── 📄 router.index.ts    # This file will be connect modules in all "Route"  
│    │
│    ├── 📂 utils/
│    │     ├── 📄 catchAsync.ts     # This file will be used in all "controllers"
│    │     └── 📄 sendResponse.ts   # controller থেকে সব Response এই ফাইলে পাঠাবে 
│    │
│    ├── 📄 app.ts     # main file
│    └── 📄 server.ts  # Mongooes connect
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

        npm install --save-dev @types/cors @types/express @types/node
        
    ```
