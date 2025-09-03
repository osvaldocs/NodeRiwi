# nestjs-riwi

This repository is an introduction to starting the advanced programming path using NestJS.

## ✅ Task

1. Create a simple NestJS project that returns `Hello RIWI world`.
2. Use **Visual Studio Code (VS Code)** as the editor.

---

## 🚀 How to create and run the NestJS project

### 1. Prerequisites

- Make sure you have **Node.js** installed. Check with:

  ```bash
  node -v
Install the NestJS CLI globally:

bash
Copiar código
npm i -g @nestjs/cli
2. Create a new NestJS project
bash
Copiar código
nest new nestjs-riwi
Choose npm or yarn when prompted.

3. Modify the default controller
Open src/app.controller.ts and replace its content with:

typescript
Copiar código
import { Controller, Get } from '@nestjs/common';

@Controller()
export class AppController {
  @Get()
  getHello(): string {
    return 'Hello RIWI world';
  }
}
4. Run the application
bash
Copiar código
cd nestjs-riwi
npm run start
Open your browser and go to: http://localhost:3000

You should see: Hello RIWI world

🧑‍💻 Editor used
Visual Studio Code

Installed on Ubuntu.
