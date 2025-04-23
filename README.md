<p align="left">
  <img src="./public/images/icons/icon-light.svg" alt="Lunark AI Logo" width="80" />
</p>

Documentation site for the Lunark AI platform, built with Nextra, Next.js, TypeScript, and Tailwind CSS.

## 🌟 Features

- **Modern Documentation Framework**: Built with [Nextra](https://nextra.site/), a Next.js-based documentation framework
- **Rich Content**: Markdown-based content with support for code blocks, tables, and more
- **Responsive Design**: Mobile-first approach ensuring great experience on all devices
- **Dark/Light Mode**: Seamless theme switching for better readability
- **Search Functionality**: Built-in search capabilities to find content quickly
- **Navigation System**: Intuitive sidebar and table of contents

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or later)
- Yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/lunark-ai/lunark-docs.git
   cd lunark-docs
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Run the development server:
   ```bash
   yarn dev
   ```

Your documentation site should now be running at [http://localhost:3000](http://localhost:3000).

## 📖 Project Structure

```
lunark-docs/
├── pages/                # Documentation pages in MDX format
│   ├── _meta.jsx         # Navigation structure definition
│   └── index.mdx         # Homepage
├── public/               # Static assets
│   └── images/           # Images and icons
├── components/           # React components
├── styles/               # CSS styles
├── theme.config.jsx      # Nextra theme configuration
└── next.config.mjs       # Next.js configuration
```

## 📝 Writing Documentation

Add new pages by creating MDX files in the `pages/` directory. The navigation structure is defined in `pages/_meta.jsx`.

Example page:

```mdx
# Getting Started

This is a guide to help you get started with Lunark AI.

## Installation

First, install the package...

## Configuration

Configure your environment...
```

## 🧪 Running Tests

```bash
yarn test
```

## 📱 Deployment

Build the documentation site for production:

```bash
yarn build
```

Start the production server:

```bash
yarn start
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-docs`)
3. Commit your changes (`git commit -m 'Add documentation for new feature'`)
4. Push to the branch (`git push origin feature/amazing-docs`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

Lunark AI Team - [https://lunarkai.org](https://lunarkai.org)

Project Link: [https://github.com/lunark-ai/lunark-docs](https://github.com/lunark-ai/lunark-docs) 