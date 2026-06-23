## Cypress QA Automation (con enfoque en Technology with Purpose) 🧪😴

Este repositorio guarda ejercicios y ejemplos de **Cypress** para practicar y aprender lo relevante de **QA Automation**, inspirado en el enfoque de **“Technology with Purpose”** de Santex (sin aburrirnos… demasiado) 🤝⚙️😄

### Objetivo 🎯
- Aprender a automatizar pruebas **end-to-end** con Cypress 🚀
- Practicar buenas prácticas de QA Automation: mantenibilidad, claridad y cobertura 🧹🧠
- Documentar aprendizajes a medida que avanzamos 📓✨

### Estructura sugerida del repo 📁
- `cypress/`
  - `e2e/` (tests) 🧩
  - `fixtures/` (datos de prueba) 🧾
  - `support/` (comandos, helpers, configuración) 🛠️
- `tests/` (si agregás notas o utilidades fuera de Cypress) 🗂️
- `README.md` (este doc) 👋
- `docs/` (guías y apuntes) 📚
- `scripts/` (scripts opcionales) 🎛️

### Qué vas a encontrar aquí 👀
- Tests progresivos (smoke → regresión → escenarios más completos) 🥾🔥
- Recomendaciones prácticas para QA Automation (naming, asserts, estado, etc.) ✅📏
- Notas de aprendizaje en cada iteración: qué funcionó, qué no y por qué 🧠🔁

### Requisitos 🧰
- Node.js (versión compatible con tu Cypress)
- npm o yarn 😎

### Instalación 💻
```bash
npm install
```

### Ejecutar pruebas ▶️
- Modo interactivo:
```bash
npx cypress open
```

- Modo headless:
```bash
npx cypress run
```

### Metodología (enfoque “Technology with Purpose”) 🧠🎯
Al escribir o mejorar un test intentamos:
- **Propósito claro:** qué riesgo reduce y qué valida 🛡️
- **Simplicidad:** pocas capas, intención legible ✨
- **Confiabilidad:** asserts sólidos y estados bien controlados 🧷
- **Mantenibilidad:** helpers reutilizables, nombres consistentes y bajo acoplamiento 🧱

### Checklist para nuevos tests ✅😴➡️😃
- [ ] Cubre un objetivo real (riesgo/feature) y no solo “funciona” 🙃
- [ ] Usa selectors estables (preferir `data-*` cuando aplique) 🧷
- [ ] Evita `wait` arbitrarios; esperar por condiciones reales ⏳➡️✅
- [ ] Asegura con assertions claras y específicas 🎯
- [ ] Mantiene el test lo más independiente posible 🧠🧩
- [ ] Documenta en el test/README qué se aprendió 📓

### Contribuir 👨‍💻🤝
Si querés mejorar algo:
1. Creá una rama 🌿
2. Sumá o ajustá tests y notas 🧪
3. Abrí un Pull Request con una descripción breve del cambio 📨

---

Decime cómo querés que se llame el repo y cómo está tu estructura real (si ya existe), y te lo dejo perfecto para pegar y correr 😄🚀
