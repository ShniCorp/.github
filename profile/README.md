
# 🧠 ShniCorp  
_Creadores de inteligencia aplicada a bots · Discord.js · TypeScript · Node.js_

---

<div align="center">

![Banner ShniCorp](https://i.imgur.com/0q06YRC.jpeg)

**Automatizamos comunidades. Diseñamos agentes. Refinamos interacciones.**  
<sub>Un grupo de desarrolladores que encuentra belleza en la estructura.</sub>

</div>

---

## 🧩 Quiénes somos

ShniCorp es un colectivo técnico fundado por [**Shnimlz**](https://github.com/Shnimlz) que diseña y mantiene sistemas conversacionales, bots inteligentes y herramientas para Discord.  
Somos una mezcla de curiosidad técnica y obsesión por la precisión.  
Cada línea de código busca expresar intención, no solo funcionar.

> _“Un bot bien hecho no responde. Anticipa.”_

Nos especializamos en:
- Arquitecturas **asíncronas y modulares**
- Integraciones con **APIs y sistemas externos**
- **TypeScript** como núcleo de diseño de tipos
- **Discord.js** como punto de contacto con el usuario
- Infraestructura flexible y portable mediante **Docker** y **Railway**

---

## 🛠 Stack base

| Capa | Tecnologías |
|------|--------------|
| **Lenguaje** | TypeScript / JavaScript (ESNext) |
| **Runtime** | Node.js / Bun |
| **Framework Discord** | discord.js |
| **ORM / DB** | Prisma · PostgreSQL / Redis |
| **Infraestructura** | Docker · Railway · Appwrite |
| **Dev Tools** | ESLint · Prettier · Husky · pnpm |
| **Pipeline** | GitHub Actions · PM2 / Systemd Deploy |

---

## 🧱 Filosofía de desarrollo

> “El código no es arte, pero tiene estética.”

- **Pureza estructural**: sin dependencias superfluas  
- **Escalabilidad funcional**: modularización sin acoplamiento  
- **Trazabilidad**: logs con contexto, no ruido  
- **Control de flujo**: todo error tiene dueño  
- **Iteración consciente**: cada commit deja el proyecto mejor que lo encontró  

---

## 🧬 Ecosistema

### 🚀 Proyecto actual
**[Amayo](https://github.com/ShniCorp/amayo)** — bot modular orientado a comunidades y alianzas.  
Código base en TypeScript, diseñado para persistencia híbrida y eventos desacoplados.  

### 🧰 Otros proyectos internos (Proximamente)
- **core-utils**: conjunto de helpers comunes entre bots  
- **shni-logger**: sistema de log adaptado a webhooks de Discord  
- **shni-cli**: CLI interna para scaffolding y despliegues rápidos  

---

## ⚙️ Instalación y uso

```bash
git clone https://github.com/ShniCorp/amayo
cd amayo
pnpm install
cp .env.example .env
pnpm dev
````

Para build de producción:

```bash
pnpm build && pm2 start dist/main.js --name amayo
```

---

## 🧠 Principios de diseño

| Concepto                | Descripción                                                          |
| ----------------------- | -------------------------------------------------------------------- |
| **Legibilidad**         | Que cualquier miembro entienda el flujo sin comentarios innecesarios |
| **Desacoplamiento**     | Cada módulo funciona como una unidad independiente                   |
| **Tolerancia a fallos** | Los errores no detienen, se encapsulan y reportan                    |
| **Extensibilidad**      | Nuevas funciones se añaden sin romper las existentes                 |

---

## 🧍‍♂️ Equipo

| Rol                   | Miembro                               | Enfoque                                 |
| --------------------- | ------------------------------------- | --------------------------------------- |
| 🧩 Founder / Lead Dev | [Shnimlz](https://github.com/Shnimlz), [FrovaHappy](https://github.com/FrovaHappy), [Hellsa](https://github.com/Hellsa), [Zumber](https://github.com/zumberr) | Arquitectura · Bot design · Backend TS  |
| ⚙️ DevOps / Infra     | (Vacante)                            | CI/CD · Contenedores · Deploy           |
| 🎨 Visual / Docs      | [Shnimlz](https://github.com/Shnimlz)                             | Branding · Presentación · Documentación |

---

## 🌐 Enlaces

* 🏢 Organización: [github.com/ShniCorp](https://github.com/ShniCorp)
* 👤 Fundador: [github.com/Shnimlz](https://github.com/Shnimlz)
* 💬 Discord: `discord.gg/ykw9Gku5v8`
* 🌱 Wiki interna: próximamente

---

## 📈 Roadmap

* [x] Establecer base de arquitectura modular
* [x] Integrar Appwrite como persistencia
* [ ] Sistema de configuración vía panel web
* [ ] Bot SDK interno (`@shnicorp/core`)
* [ ] Integración de LLMs para respuestas dinámicas

---

## ⚖️ Licencia

**MIT License**
Usa, modifica y distribuye libremente con atribución.

---

<div align="center">

> *“No buscamos viralidad. Buscamos consistencia.”* <sub>© ShniCorp — Discord Automation & Codecraft</sub>

</div>
```

Incluye:

* Diseño visual centrado con banner y bloques minimalistas.
* Filosofía de desarrollo expresada con tono técnico.
* Tablas coherentes y branding modular.
* Enlaces y placeholders para expansión futura.

