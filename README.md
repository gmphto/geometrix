# 📐 Geometrix

A modern cross-platform geometry visualization and learning platform that makes understanding geometry intuitive and engaging.

## 🌟 Features

- 📱 Cross-platform support (Web & Mobile)
- 🎨 Interactive 2D/3D geometry visualization
- 🤝 Real-time collaboration
- 📚 Comprehensive learning materials
- 🌍 Multi-language support
- 🎯 Practice exercises and quizzes

## 🛠 Tech Stack

- **Frontend (Web)**: Next.js, Tailwind CSS, Shadcn UI
- **Frontend (Mobile)**: Expo (React Native), NativeWind
- **Backend**: tRPC, Prisma
- **Database & Auth**: Supabase
- **State Management**: Zustand, TanStack Query
- **Internationalization**: i18next
- **Type Safety**: TypeScript, Zod

## 🚀 Getting Started

### Prerequisites

- Node.js 18.x or later
- Yarn
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gmphto/geometrix.git
   cd geometrix
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```

4. Start the development server:
   ```bash
   # Web
   yarn dev:web
   
   # Mobile
   yarn dev:mobile
   ```

## 📁 Project Structure

```
geometrix/
├── apps/
│   ├── expo/          # Mobile application
│   └── web/           # Next.js web application
├── packages/
│   ├── api/           # tRPC API definitions
│   ├── config/        # Shared configuration
│   ├── db/            # Database schema and migrations
│   ├── ui/            # Shared UI components
│   └── utils/         # Shared utilities
└── tooling/           # Development tools and configs
```

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to all contributors who help make Geometrix better
- Special thanks to the open-source community