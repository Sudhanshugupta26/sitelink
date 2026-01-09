# 🎓 Learning Hub

![Project Badge](https://img.shields.io/badge/Status-Active-success)
![Next.js](https://img.shields.io/badge/Next.js-15.0-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

A stunning, responsive directory of premium developer learning resources. The Learning Hub aggregates top-tier platforms like Roadmap.sh, W3Schools, Web.dev, and Microsoft Learn into a beautiful, unified interface with a card-based design.

![Desktop Preview](/Users/tanay/.gemini/antigravity/brain/f70546a7-b79c-4864-bf5f-75c4144c794c/standard_desktop_layout_1767978039077.png)

## ✨ Features

- **Cards Directory**: Interactive cards with branded colors and categories.
- **Glassmorphism UI**: Modern aesthetic with backdrop blurs and gradients.
- **Fully Responsive**: Optimized for 4K ultrawide, desktops, laptops, tablets, and mobile devices.
- **Mobile First**: Smooth hamburger menu overlay and touch-friendly interactions.
- **Direct Links**: Bypasses iframe restrictions by linking directly to resources in new tabs.

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: Vanilla CSS Modules & CSS Variables
- **Font**: [Inter](https://fonts.google.com/specimen/Inter) via `next/font`

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- Node.js 18.17 or later
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/learning-hub.git
   cd learning-hub
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## 🤝 How to Contribute

We welcome contributions from the community! Whether it's adding a new learning resource, fixing a bug, or improving the design.

### Contribution Process

1. **Fork the Repository**
   Click the "Fork" button at the top right of this page to create your own copy of the repository.

2. **Clone your Fork**
   ```bash
   git clone https://github.com/your-username/learning-hub.git
   ```

3. **Create a Branch**
   Create a new branch for your feature or fix.
   ```bash
   git checkout -b feature/amazing-new-resource
   ```

4. **Make Changes**
   - **Add Resources**: Update `app/page.tsx` within the `resources` array.
   - **Styles**: Edit `app/page.module.css` or `app/globals.css`.
   
   *Tip: Ensure you follow the existing design tokens and verification steps!*

5. **Commit your Changes**
   ```bash
   git commit -m "feat: added freecodecamp resource"
   ```

6. **Push to GitHub**
   ```bash
   git push origin feature/amazing-new-resource
   ```

7. **Submit a Pull Request**
   Go to the original repository and click "Compare & pull request". Describe your changes in detail.

## 📂 Project Structure

```
learning-hub/
├── app/
│   ├── layout.tsx       # Global root layout
│   ├── page.tsx         # Main page with resource data
│   ├── page.module.css  # CSS Modules for the main page
│   └── globals.css      # Global styles & variables
├── public/              # Static assets
└── ...
```

## ✨ Contributors

Thank you to everyone who helps improve the Learning Hub!

<a href="https://github.com/yourusername/learning-hub/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=yourusername/learning-hub" alt="Contributors" />
</a>

*Note: Replace `yourusername/learning-hub` in the URL above with your actual GitHub repository details to see the dynamic graph.*

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
