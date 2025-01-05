# 📝 Notion Clone - Full Stack Application

A full-featured Notion-like workspace application built following Code with Antonio's tutorial, featuring real-time collaboration, rich text editing, and file management. You can follow his tutorial ![here](https://www.youtube.com/watch?v=0OaDyjB9Ib8)

![Jotion](./public/jotion-dark.jpeg)

![Jotion](./public/jotion-light.jpeg)

## 🚀 Tech Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-FF731D?style=for-the-badge&logo=convex&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)
![Shadcn/ui](https://img.shields.io/badge/Shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Edge Store](https://img.shields.io/badge/Edge_Store-2E59C7?style=for-the-badge&logo=edgestore&logoColor=white)

## ✨ Features

- 📝 Real-time database with Convex
- 🔐 Authentication using Clerk
- 📁 File upload using EdgeStore
- 📱 Full responsiveness
- ⌨️ Rich text editor
- 🎨 Light and Dark mode
- 📊 Expandable sidebar
- 🔄 Real-time updates
- 🗂️ Infinite children documents
- ⚡ Publish to web feature
- 🔍 Search functionality
- 🎯 Sort and filter options
- ⚙️ Settings for customization
- 🖼️ Icons for each document
- 📱 Full mobile responsiveness

## 🛠️ Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/pakagronglb/notion-clone.git
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env.local
```

4. Configure your environment variables:
```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

5. Run the development server
```bash
npm run dev
```

## 🏗️ Project Structure

```bash
notion-clone/
├── app/
│ ├── (main)/
│ ├── (marketing)/
│ └── layout.tsx
├── components/
│ ├── ui/
│ └── providers/
├── convex/
│ ├── documents.ts
│ └── schema.ts
└── public/
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is [MIT](LICENSE) licensed.

## 🙏 Acknowledgments

- [Code With Antonio](https://www.youtube.com/watch?v=0OaDyjB9Ib8) for the amazing tutorial
- [Convex](https://www.convex.dev/) for the real-time backend
- [Clerk](https://clerk.dev/) for authentication
- [Shadcn/ui](https://ui.shadcn.com/) for the UI components

## 📧 Contact

Pakagrong L - [@pakagronglb](https://twitter.com/pakagronglb)

Github Repo: [https://github.com/pakagronglb/notion-clone](https://github.com/pakagronglb/notion-clone)

