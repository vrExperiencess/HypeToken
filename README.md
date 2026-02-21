# HypeToken + ArenaCoins (Demo)

Plataforma web de fidelización gamificada para negocios.  
HypeToken es el ecosistema base (planes, onboarding y narrativa visual), y ArenaCoins es el primer negocio demo (Oasis Games) que adopta la mecánica para demostrar el flujo completo de puntos, niveles y recompensas.

---

## ✨ ¿Qué es HypeToken?

**HypeToken** es una plataforma digital interactiva donde la fidelización se convierte en una experiencia:
- Tokens (puntos) con identidad visual
- Retos semanales y progreso
- Recompensas y canjes
- Consulta de estado por documento **sin descargar apps**
- Universo visual futurista (neón, glow, tarjetas, “energía digital”)

**Objetivo:** reemplazar las típicas tarjetas físicas (sellos, cartones, puntos manuales) por un sistema moderno, rápido y fácil de activar para negocios pequeños y medianos.

---

## 🪙 ¿Qué es ArenaCoins?

**ArenaCoins** es el primer negocio demo (Oasis Games) construido sobre la idea de HypeToken.
Sirve como **caso de uso real** para presentar:

- Consulta de puntos por documento
- Visualización de clan/nivel con cartas
- Beneficios por nivel
- IDs demo para mostrar niveles superiores

---

## 🧭 Estructura del proyecto

Este repo contiene dos “universos” dentro de la misma app:

- **HypeToken (Landing + planes + contacto)**
  - Intro / landing
  - Página de registro/planes
  - Modal de contacto por WhatsApp para onboarding

- **ArenaCoins (Demo funcional)**
  - Home del negocio
  - Registro (ArenaCoins)
  - Consultar puntos (ArenaCoins)
  - Páginas legales

---

## 🗺️ Rutas principales

> Las rutas pueden variar según tu configuración, pero la intención es:

### HypeToken
- `/` → Landing/Intro HypeToken
- `/ht/registro` (o similar) → Registro/Planes HypeToken + contacto WhatsApp

### ArenaCoins (demo)
- `/app` → Home ArenaCoins
- `/registro` → Registro ArenaCoins
- `/consultar` → Consultar puntos ArenaCoins
- `/reglas` → Reglas del programa
- `/terminos` → Términos y condiciones

---

## 🎮 IDs demo (ArenaCoins)

Para presentar clanes superiores durante la demo, puedes usar estos documentos:

- `1000000001` — Explorador Demo  
- `1000000002` — Gladiator Demo  
- `1000000003` — Maestro VR Demo  
- `1000000004` — Leyenda Oasis Demo  

---

## 💳 Planes (HypeToken)

La página de registro de HypeToken presenta planes mensuales/anuales, pensados para ser accesibles en Colombia y comparables contra el costo de imprimir tarjetas físicas.

Además, cada plan puede incluir:
- **Límite de usuarios incluidos**
- **Costo por usuario extra** si se supera el límite

> Recomendación de métrica: “usuarios activos mensuales” (consultan o transaccionan en el mes), para que el negocio no se penalice por registros históricos.

---

## 🧩 Tech stack

- **React** + **React Router**
- **TailwindCSS**
- **Framer Motion** (animaciones)
- **Lucide React** / **React Icons** (iconos)
- Integración de servicios (fetch) para ArenaCoins

---

## Trademark / Brand & Assets Notice
The names “HypeToken”, “ArenaCoins”, and “vrExperienceStudio”, along with associated logos, images, and brand assets (including files under `public/imgs/` and `src/assets/`), are not granted for reuse under the MIT License.  
You may use the code, but you may not use the branding/assets without explicit permission.
