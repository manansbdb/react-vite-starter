<p align="center">
  <img src="docs/banner.svg" alt="React Vite Starter banner" width="100%" />
</p>

<h1 align="center">react-vite-starter</h1>

<p align="center">
  <strong>EN</strong> Vite + React + TypeScript folder scaffold and docs<br/>
  <strong>PT</strong> Scaffold e docs Vite + React + TypeScript
</p>

<p align="center">
  <a href="https://github.com/manansbdb/react-vite-starter/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge" alt="React" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Docs and **example files** for a Vite + React + TypeScript app layout (not a full runnable app). | Docs e **ficheiros de exemplo** para um layout Vite + React + TypeScript (não é uma app completa). |
| Use `docs/STRUCTURE.md` plus the example App/config when scaffolding with `npm create vite`. | Usa `docs/STRUCTURE.md` e os exemplos App/config ao criar com `npm create vite`. |

```mermaid
flowchart LR
  A["📘 STRUCTURE.md"] --> B["⚛️ App.example.tsx"]
  B --> C["⚙️ vite.config.example.ts"]
  C --> D["🚀 npm create vite"]
  style A fill:#0ea5e9,stroke:#0369a1,color:#fff
  style B fill:#61DAFB,stroke:#0284c7,color:#111
  style C fill:#646CFF,stroke:#4338ca,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/react-vite-starter.git
cd react-vite-starter
```

### 2) Scaffold a real Vite app / Cria a app Vite

```bash
npm create vite@latest my-app -- --template react-ts
cd my-app
```

### 3) Apply examples / Aplica exemplos

```bash
cp ../react-vite-starter/examples/App.example.tsx src/App.tsx
cp ../react-vite-starter/examples/vite.config.example.ts vite.config.ts
cp ../react-vite-starter/docs/STRUCTURE.md docs/STRUCTURE.md
npm install && npm run dev
```

### Requirements / Requisitos

- Node.js 18+
- `npm`

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/react-vite-starter.git
# read docs/STRUCTURE.md, then npm create vite@latest -- --template react-ts
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `docs/STRUCTURE.md` | Suggested folder layout |
| `examples/App.example.tsx` | Sample React component |
| `examples/vite.config.example.ts` | Sample Vite config |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
react-vite-starter/
├── docs/banner.svg
├── docs/STRUCTURE.md
├── examples/App.example.tsx
├── examples/vite.config.example.ts
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
