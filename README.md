# 🎨 Práctica de Selectores CSS

Plantilla para practicar los **97 ejercicios de selectores CSS** de la Clase 09 del Máster Full Stack de ConquerBlocks.

El sistema es sencillo: el HTML ya tiene todos los elementos preparados. Tú escribes el selector en el CSS y si está bien, el elemento **cambia de color en el navegador al instante** con Live Server.

---

## 🚀 Cómo empezar

### 1. Haz un Fork
Haz clic en el botón **"Fork"** arriba a la derecha en GitHub. Esto crea una copia del repositorio en tu cuenta.

### 2. Clona tu fork en local
```bash
git clone https://github.com/TU_USUARIO/css-selectores.git
cd css-selectores
```

### 3. Abre en VS Code
```bash
code .
```

### 4. Lanza Live Server
Clic derecho sobre `index.html` → **"Open with Live Server"**

### 5. A practicar
Abre `selectores.css`, busca el ejercicio que toca y escribe tu selector donde pone `TU RESPUESTA ↓`

```css
/* 1. Selecciona los div que sean hijos directos de otro div */
/* TU RESPUESTA ↓ */

div > div   ← escribe aquí tu selector

{
  background-color: #ffd700;
  outline: 2px solid orange;
}
```

✅ Si el elemento cambia de color → has acertado  
❌ Sin cambio visual → revisa el selector

---

## 📁 Estructura

```
css-selectores/
├── index.html       ← HTML con todos los elementos a seleccionar (no tocar)
├── selectores.css   ← Aquí escribes tus respuestas
└── README.md
```

---

## 📋 Progreso

- [ ] Ejercicios 1–24 (Clase 09 – Lista 1)
- [ ] Ejercicios 25–42 (Clase 09 – Lista 2)
- [ ] Ejercicios 43–63 (Lista 3)
- [ ] Ejercicios 64–82 (Lista 4)
- [ ] Ejercicios 83–97 (Lista 5)

---

## 💡 Consejos

- Haz un **commit por cada bloque** de ejercicios terminado
- Si un selector no funciona, revisa que no haya un **espacio de más** antes de la pseudo-clase (error muy común)
- Si dos ejercicios se pisan visualmente es normal, es la **cascada CSS en acción**
- Las soluciones están en la rama `soluciones` si te quedas atascado

---

Creado por [@david-rr94](https://github.com/david-rr94) – Máster Full Stack ConquerBlocks
