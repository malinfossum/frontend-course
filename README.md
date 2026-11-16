# Frontend Course

My work for the Vue module (Single Page Applications with Vue) of the Fagskole frontend course, which I take as part of GET Prepared at Fagskolen GET Academy. Week 1 is a set of small exercises. From week 2 I build my own project, a visual day planner, instead of the shared class app. Later drills land here when they stand on their own.

**Stack:** Vue 3 (Composition API, `<script setup>`), TypeScript, Vite, Vitest, ESLint + Oxlint.

## Setup

```bash
npm install
npm run dev
```

| Command | What it does |
| --- | --- |
| `npm run dev` | Dev server on `localhost:5173` |
| `npm test` | Runs the tests once |
| `npm run lint` | Oxlint + ESLint (fixes files in place) |
| `npm run build` | Type-check and production build |

## Week 1: exercises

| Day | Topic |
| --- | --- |
| Monday | Getting started: `ref`, template syntax, first component (`AppCounter`) |
| Tuesday | Directives and lists: `v-if`, `v-show`, `v-for` with `:key`, `v-model` and its modifiers (`TodoList`) |
| Wednesday | Components and testing: `TodoList` split into `TodoForm`, `TodoItem` and `TodoStats` with props and emits, plus component tests |
| Thursday | Slots and modals: `AppBox` with a default slot, `AppModal` on a native `<dialog>` with named slots, used for the delete confirm |
