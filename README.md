# Backend-MS-Base

## Prerequisites

### Install Node.js
1. Download the MSI installer from [Node.js Downloads](https://nodejs.org/en/download/).
2. Verify the installation by running the following command in the terminal:
   ```
   node -v
   ```
3. Open PowerShell as an administrator and execute:
   ```
   Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
   ```
4. Verify npm installation:
   ```
   npm -v
   ```

### Install TypeScript
Run the following commands:
```
npm install -g typescript
npm install -g ts-node
npm install -g nodemon
npm i express body-parser cookie-parser compression cors
npm i -g @types/express @types/body-parser @types/cookie-parser @types/compression @types/cors
```

### Install PostgreSQL
Run the following command:
```
npm install pg @types/pg dotenv