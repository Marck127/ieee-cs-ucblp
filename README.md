# IEEE CS Student Branch — UCB La Paz 🌐

Landing page oficial del capítulo IEEE Computer Society, Universidad Católica Boliviana "San Pablo" — Sede La Paz.

---

## 🚀 Cómo publicar en GitHub Pages (paso a paso)

### 1. Crear el repositorio en GitHub

1. Ve a [github.com](https://github.com) e inicia sesión
2. Haz clic en **"New repository"** (botón verde)
3. Nómbralo: `ieee-cs-ucblp` (o el nombre que prefieras)
4. Márcalo como **Public**
5. Haz clic en **"Create repository"**

---

### 2. Subir el archivo `index.html`

**Opción A — Desde el navegador (más fácil):**
1. Dentro de tu nuevo repositorio, haz clic en **"uploading an existing file"**
2. Arrastra el archivo `index.html` a la zona de carga
3. Escribe un mensaje de commit, ej: `feat: agregar landing page inicial`
4. Haz clic en **"Commit changes"**

**Opción B — Con Git (terminal):**
```bash
git clone https://github.com/TU_USUARIO/ieee-cs-ucblp.git
cd ieee-cs-ucblp
cp /ruta/al/index.html .
git add index.html
git commit -m "feat: agregar landing page inicial"
git push origin main
```

---

### 3. Activar GitHub Pages

1. En tu repositorio, ve a **Settings** (pestaña superior derecha)
2. En el menú lateral izquierdo, haz clic en **Pages**
3. En **"Source"**, selecciona:
   - Branch: `main`
   - Carpeta: `/ (root)`
4. Haz clic en **Save**
5. Espera 1-2 minutos y tu sitio estará disponible en:

```
https://TU_USUARIO.github.io/ieee-cs-ucblp/
```

---

## ✏️ Personalización recomendada

Abre `index.html` con cualquier editor de texto (VS Code recomendado) y actualiza:

| Sección | Qué cambiar |
|--------|------------|
| **Equipo** | Nombres y roles reales de la directiva |
| **Estadísticas** | Números reales del capítulo |
| **Eventos** | Fechas y eventos actuales |
| **Contacto** | Email, Instagram, LinkedIn reales |
| **Stats** | Años de trayectoria, miembros, proyectos |

---

## 📁 Estructura del proyecto

```
ieee-cs-ucblp/
└── index.html       ← Página completa (una sola archivo)
└── README.md        ← Este archivo
```

> La landing es un único archivo HTML autocontenido — sin dependencias externas ni frameworks. Solo necesitas subirlo y listo.

---

## 🛠️ Herramientas recomendadas

- [VS Code](https://code.visualstudio.com/) — editor gratuito para editar el HTML
- [GitHub Desktop](https://desktop.github.com/) — interfaz visual para Git si prefieres no usar terminal

---

*IEEE Computer Society — Student Branch · UCB La Paz · Bolivia*
