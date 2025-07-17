# Gutenberg

The Gutenberg project is the new editing experience for WordPress. It aims to modernize the WordPress content creation process and provide a more flexible, intuitive user interface.

## 🚀 What is Gutenberg?

Gutenberg is more than just an editor — it's the foundation for a new publishing experience in WordPress. It introduces the concept of blocks for all types of content: paragraphs, images, galleries, videos, and more.

Blocks provide a consistent way to customize and manage content across your entire site.

## 🧰 Getting Started

To get started with development, you'll need:

- Node.js (check `.nvmrc` for the required version)
- npm (comes with Node.js)
- A local WordPress environment (e.g., [WordPress + Docker](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-env/))

### Setup

1. Clone the repo:

```bash
git clone https://github.com/WordPress/gutenberg.git
cd gutenberg
```

2. Install dependencies:

```bash
npm install
```

3. Build the project:

```bash
npm run build
```

4. Start developing:

```bash
npm run dev
```

For more setup details, see the [Development Environment](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-env/) docs.

## 📦 Folder Structure

```bash
gutenberg/
├── packages/        # Individual block editor packages
├── docs/            # Documentation
├── bin/             # CLI tools
├── lib/             # PHP files for WordPress plugin integration
├── stories/         # Storybook stories
```

## 🤝 Contributing

We welcome contributions of all types — code, documentation, design, and more. To get started:

- Check [CONTRIBUTING.md](CONTRIBUTING.md)
- Browse issues labeled [Good First Issue](https://github.com/WordPress/gutenberg/issues?q=is%3Aissue+is%3Aopen+label%3A%22Good+First+Issue%22)
- Join discussions on [Make WordPress Slack](https://make.wordpress.org/chat/)

## 📄 License

Gutenberg is licensed under the [GNU General Public License v2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) or later.

---

🌟 Happy coding! Help shape the future of WordPress.
