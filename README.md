# 🎲 Bingo Virtual (1 - 100)

Aplicación web interactiva para jugar al Bingo del 1 al 100. Diseñada para funcionar sin dependencias en cualquier navegador (PC, proyector o celular).

---

## ✨ Características

- **Sorteo aleatorio:** Saca números del 1 al 100 sin repetir, con animación visual.
- **Tablero interactivo:** Marca automáticamente los números que salieron y permite marcación manual con un clic.
- **Historial de bolillas:** Muestra el último número y los 5 anteriores.
- **Carga manual:** Posibilidad de ingresar números manualmente mediante teclado.
- **Persistencia automática:** Guarda el estado en `localStorage` para no perder la partida si se recarga la página.
- **Deshacer y Reiniciar:** Botón de retroceso de última jugada y reinicio con confirmación.
- **Modo Pantalla Completa / Tablero:** Oculta controles para proyectar solo el tablero (con botón flotante y tecla `Esc` para salir).
- **Modo Oscuro / Claro:** Se adapta automáticamente a la preferencia del sistema.
- **Atajos de teclado:**
  - `Espacio` o `Enter`: Sacar siguiente número.
  - `Esc`: Salir del modo solo tablero.

---

## 🚀 Cómo correr el proyecto

### Opción 1: Abrir directamente (Sin instalar nada)
Simplemente haz doble clic sobre el archivo `index.html` o arrástralo a tu navegador web favorito (Chrome, Edge, Firefox, Safari).

### Opción 2: Con Live Server (VS Code)
1. Abre esta carpeta en Visual Studio Code.
2. Si tienes la extensión **Live Server**, haz clic derecho en `index.html` y selecciona **Open with Live Server**.

### Opción 3: Con Node.js (opcional)
Si tienes Node.js instalado, puedes ejecutar un servidor local con:
```bash
npx serve .
```

---

## 🌐 Cómo publicarlo gratis en GitHub Pages

Para tener la aplicación online y compartir el enlace con amigos o proyectarla desde cualquier dispositivo:

1. Sube los cambios a tu repositorio en GitHub:
   ```bash
   git add .
   git commit -m "feat: Bingo web app listo para correr y desplegar"
   git push -u origin main
   ```
2. En GitHub, ve a tu repositorio (`chavow5/Bingo`).
3. Entra a **Settings** (Configuración) > **Pages** (en el menú lateral izquierdo).
4. En **Build and deployment** > **Source**, elige **Deploy from a branch**.
5. Selecciona la rama **`main`** y la carpeta **`/(root)`**, luego haz clic en **Save**.
6. En 1 o 2 minutos, tu Bingo estará publicado en:
   **`https://chavow5.github.io/Bingo/`**

