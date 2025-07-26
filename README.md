# alx-project-0x03-setup

This project is part of the ALX curriculum. The goal is to build a **Next.js** application demonstrating shared layouts, routing techniques, error handling, and project structure best practices using **TypeScript** and **Tailwind CSS**.

## 🚀 Tech Stack

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Icons](https://react-icons.github.io/react-icons/)
- Google Fonts (Montserrat)

---


---

## ✅ Tasks Implemented

### 0. **Implementing a Shared Layout (DRY)**

Created reusable layout components:

- `Header.tsx`
- `Footer.tsx`
- `Layout.tsx`
- `Button.tsx`

These components are composed into a `Layout` wrapper used around page content, following the DRY principle.

### 1. **Importing Google Fonts**

Imported **Montserrat** font in `styles/global.css` using:

```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

body {
  font-family: 'Montserrat', sans-serif;
}


