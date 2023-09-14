<p align="center">
  <img width="200px" alt="Project NLW IA Mastery" title="Project NLW IA Mastery Logo" src="./.gihub/logo.svg" />
  
  <h1 align="center">Project NLW IA Mastery</h1>

  <!-- <p align="center">
    🔗 <a href="https://URLThisProject.com">https://URLThisProject.com</a> 🔗
  </p>   -->

Developed the video transcription project with AI and requests to OpenAI's AI, aiming at generating titles, descriptions, and other options.

</p>

## 🧭 Table of contents

- [🧭 Table of contents](#-table-of-contents)
- [🎥 Implementation Video](#-implementation-video)
- [👏 Learning and more Implementations](#-learning-and-more-implementations)
- [💡 Technologies Used](#-technologies-used)
  - [Back-end](#back-end)
  - [Front-end Web](#front-end-web)
- [📂 Folder Structure](#-folder-structure)
- [🚀 Running the Project](#-running-the-project)
  - [Back-end](#back-end-1)
  - [Front-end Web](#front-end-web-1)
- [🌎 License](#-license)
- [✒ Author](#-author)

## 🎥 Implementation Video

In the GitHub edit, drag the video that it already puts on github itself.

<!-- ## 🎨 Layout

Layout developed by [Name](https://www.instagram.com/urlName/)

[![Layout in Figma](https://github.com/VagnerNerves/default-readme/blob/main/assets/layout-in-figma.svg)](https://www.figma.com/files) -->

## 👏 Learning and more Implementations

- Learned to use OpenAI's API.
- Learned to convert the video to MP3 using ffmpeg.wasm through the user's web browser.

## 💡 Technologies Used

### Back-end

- [x] Node.js
- [x] [Fastify](https://fastify.dev/)
- [x] [Prisma](https://www.prisma.io/client)
- [x] [TypeScript](https://www.typescriptlang.org/)
- [x] [fastify-multipart](https://github.com/fastify/fastify-multipart)
- [x] [Zod](https://zod.dev/)
- [x] [Openai](https://platform.openai.com/docs/api-reference)

### Front-end Web

- [x] [React](https://reactjs.org/)
- [x] [Vite](https://vitejs.dev/)
- [x] [TypeScript](https://www.typescriptlang.org/)
- [x] [Tawilndcss](https://tailwindcss.com/)
- [x] [RadixUi](https://www.radix-ui.com/primitives/docs/overview/introduction)
- [x] [Shadcn/ui](https://ui.shadcn.com/docs)
- [x] [Lucide React](https://lucide.dev/guide/packages/lucide-react)
- [x] [ffmpeg.wasm](https://ffmpegwasm.netlify.app/)
- [x] [Axios](https://axios-http.com/ptbr/)

## 📂 Folder Structure

```plainText
app
.
.
├── upload-ai-api               # Project Back-end
│   ├── src                       # Source files
│         ├── lib                   # Contains the connections
│         ├── routes                # Contains the routes
│         . server.ts               # Aplication entry
│   ├── tmp                       # MP3 files saved for transcription
│   . .env                        # Environment variables
│   . routes.http                 # Executing routes whit Rest Client
.
├── upload-ai-web               # Project Back-end
│   ├── src                       # Source files
│         ├── components            # Contains all global react components
│         ├── ffmpeg                # Contains ffmpeg files
│         ├── lib                   # Contains the connections
│         . main.tsx                # Aplication entry react
│   . index.html                  # Aplication entry
│
.
└── README.md
```

## 🚀 Running the Project

Clone the project

```bash
  git clone https://github.com/VagnerNerves/nlw-ia-mastery-092023.git
```

### Back-end

Enter the project directory

```bash
  cd nlw-ia-mastery-092023/upload-ai-api
```

Install with dependencies

```bash
  npm install
```

Create the file '.env' following the example in the '.env.example' file.

To create and obtain the OpenAI key, visit https://platform.openai.com/account/api-keys."

Create DB

```bash
  npx prisma migrate dev
```

Create data in the prompt table

```bash
  npx prisma db seed
```

Start the server

```bash
  npm run dev
```

### Front-end Web

Enter the project directory

```bash
  cd nlw-ia-mastery-092023/upload-ai-web
```

Install with dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

<!-- ### Mobile

Clone the project

```bash
  git clone https://link-para-o-projeto
```

Enter the project directory

```bash
  cd my-project
```

Install with dependencies

```bash
  npm install
```

Start the server

```bash
  npx expo start
```

- IOS:

```bash
  npx pod-install && npx react-native run-ios
```

- Android:

```bash
  npx react-native run-android
``` -->

<!-- ## 📝 Routes

[![Run in Postman](https://github.com/VagnerNerves/default-readme/blob/main/assets/run-in-postman.svg)](https://app.getpostman.com/run-collection/link)
[![Run in Insomnia](https://github.com/VagnerNerves/default-readme/blob/main/assets/run-in-insomnia.svg)](https://insomnia.rest/run/?label=NAMEPROJECT&uri=LINK) -->

## 🌎 License

This project is under the MIT license. See the [LICENSE](https://github.com/VagnerNerves/nlw-ia-mastery-092023/blob/main/LICENSE) file for more details.

## ✒ Author

<p align="center">
  <img width="200px" alt="Author Vagner Nerves" title="Author Vagner Nerves" src="https://github.com/VagnerNerves/default-readme/blob/main/assets/VagnerNerves.svg" />

  <h3 align="center">Vagner Nerves</h3>
  
  <p align="center">  
    Made with love and hate 😅, get in touch!
  </p>
</p>  
  
<div align="center">

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-1f6feb?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vagnernervessantos/)](https://www.linkedin.com/in/vagnernervessantos/)
[![Gmail Badge](https://img.shields.io/badge/-vagnernervessantos@gmail.com-1f6feb?style=flat-square&logo=Gmail&logoColor=white&link=mailto:vagnernervessantos@gmail.com)](mailto:vagnernervessantos@gmail.com)
[![GitHub Badge](https://img.shields.io/badge/-GitHub-1f6feb?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/VagnerNerves)](https://github.com/VagnerNerves)

</div>
