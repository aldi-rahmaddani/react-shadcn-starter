# 🚀 Frontend Starter Template (React + TypeScript + Vite + ShadCN-UI)

Template ini dibuat untuk mempermudah setup awal proyek frontend dengan React, TypeScript, Vite, dan ShadCN-UI.

## ✨ Fitur

- 🚀 **Vite** sebagai bundler untuk kecepatan optimal
- 💡 **TypeScript** untuk kode yang lebih aman
- 🎨 **ShadCN-UI** sebagai UI component library
- 🎯 **ESLint + Prettier** untuk memastikan kualitas dan konsistensi kode
- 🛠 **Lint-staged + Husky** untuk pre-commit hook
- 🔥 **Mudah dikustomisasi** untuk berbagai kebutuhan proyek

---

## 📦 Instalasi

Pastikan Anda sudah menginstal **pnpm** atau package manager lainnya.

```sh
pnpm install
```

Setelah itu, jalankan proyek dengan:

```sh
pnpm dev
```

## 🚀 Struktur Folder

/src
├── components/ # Komponen UI
├── pages/ # Halaman utama
├── styles/ # Styling & theme
├── lib/ # Helper & utilities
├── main.tsx # Entry point aplikasi

## 🛠 Setup ESLint & Prettier

```sh
pnpm lint      # Mengecek kode dengan ESLint
pnpm format    # Memformat kode dengan Prettier
```

Detail konfigurasi linting & formatting ada di docs/eslint-prettier.md.

## 🎨 Customisasi Tema

Untuk mengubah warna utama, edit file tailwind.config.ts.

Lebih detail ada di docs/theming.md.
