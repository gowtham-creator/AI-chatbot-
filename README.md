<div align="center">

<img alt="React Chatbotify" src="src/assets/logo.png" width="300">

### React Chatbotify

React Chatbotify: a React and TypeScript chatbot component library built with Vite, MIT licensed.

<br>

[![React](https://img.shields.io/badge/React-18.2-4C1D95?style=for-the-badge&labelColor=1E1B4B)](https://react.dev) [![TypeScript](https://img.shields.io/badge/TypeScript-5.1-5B21B6?style=for-the-badge&labelColor=1E1B4B)](https://www.typescriptlang.org) [![Vite](https://img.shields.io/badge/Vite-4.5-7C3AED?style=for-the-badge&labelColor=1E1B4B)](https://vite.dev)

![license](https://img.shields.io/badge/license-MIT-4C1D95?style=flat-square&labelColor=1E1B4B) ![language](https://img.shields.io/badge/language-TypeScript-5B21B6?style=flat-square&labelColor=1E1B4B) ![updated](https://img.shields.io/badge/updated-2026--11--04-4C1D95?style=flat-square&labelColor=1E1B4B)

</div>

---

## What this is

A React chatbot component library (React Chatbotify) in React 18 and TypeScript, built with Vite and shipped under MIT. 17 components with a test suite.

The code is laid out as:

- `src/components/` — UI components
- `src/assets/` — assets
- `src/services/` — service layer
- `src/types/` — type definitions
- `src/context/` — React context
- `test/` — tests
- `types/` — type definitions
- `docs/` — documentation

<div align="center">

|  |  |  |
|:--:|:--:|:--:|
| **17** | **3** | **2** |
| components | test files | docs |

</div>

---

## Architecture

```mermaid
flowchart TB
    U["Browser"]
    RT["App root"]
    U --> RT
    CM["Components"]
    RT --> CM
    ST["State"]
    RT --> ST
```

<sub>Derived from the directories present in this repository.</sub>

---

## Stack

| Layer | Choice |
|---|---|
| [React](https://react.dev) | v18.2 |
| [TypeScript](https://www.typescriptlang.org) | v5.1 |
| [Vite](https://vite.dev) | v4.5 |

---

## Getting started

```bash
git clone https://github.com/gowtham-creator/AI-chatbot-.git
cd AI-chatbot-
npm install
npm run start
```

### Scripts

| Command | Runs |
|---|---|
| `npm run start` | `vite serve` |
| `npm run build` | `tsc && vite build && cp ./dist/index.d.ts ./dist/index.d.cts` |
| `npm run lint` | `eslint . --ext .tsx` |
| `npm run test` | `node ./test/RunTests.js` |
| `npm run prepublishOnly` | `tsc && vite build && cp ./dist/index.d.ts ./dist/index.d.cts` |
| `npm run prepack` | `tsc && vite build && cp ./dist/index.d.ts ./dist/index.d.cts` |

---

## Project structure

| Path | Contents | Files |
|---|---|---|
| `src/components/` | UI components | 33 |
| `src/assets/` | assets | 15 |
| `src/services/` | service layer | 13 |
| `src/` | — | 5 |
| `src/types/` | type definitions | 5 |
| `src/context/` | React context | 3 |
| `test/` | tests | 3 |
| `types/` | type definitions | 2 |
| `docs/` | documentation | 1 |

<sub>88 tracked files in total.</sub>

---

<div align="center">
<sub><a href="https://github.com/gowtham-creator/AI-chatbot-">gowtham-creator/AI-chatbot-</a></sub>
</div>
