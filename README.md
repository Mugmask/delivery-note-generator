# 📦 Generador de Remitos

Una aplicación web para generar remitos en PDF, visualizar remitos previos y rellenar campos de forma dinámica. Desarrollada con **Vite, React, ShadCN y Tailwind CSS**, con soporte para **dark mode**.

## ✨ Características

- 📄 **Generación de Remitos** en PDF.
- 🔍 **Vista previa** antes de descargar.
- 🎨 **Interfaz moderna** con ShadCN y Tailwind CSS.
- 🌗 **Modo oscuro** automático con `next-themes`.
- 🗂️ **Historial de remitos generados**.
- ⚡ **Alto rendimiento** gracias a Vite y React.

## 🚀 Tecnologías utilizadas

- **Vite** ⚡ (para un desarrollo rápido y optimizado)
- **React** ⚛️ (para la UI dinámica)
- **ShadCN** 🖌️ (para componentes modernos y estilizados)
- **Tailwind CSS** 🎨 (para diseño eficiente)
- **next-themes** 🌗 (para gestionar el modo oscuro)
- **react-router-dom** 🚏 (para navegación entre vistas)
- **pdf-lib** 📝 (para la generación de PDFs)

## 📂 Estructura del Proyecto

```bash
📦 generador-remitos
├── 📂 src
│   ├── 📂 components       # Componentes reutilizables (Sidebar, ThemeToggle, etc.)
│   ├── 📂 pages            # Páginas principales (Home, Remitos, etc.)
│   ├── 📂 hooks            # Custom Hooks
│   ├── 📂 utils            # Funciones auxiliares (generación de PDF, etc.)
│   ├── 📄 App.tsx          # Componente principal
│   ├── 📄 main.tsx         # Punto de entrada
│   └── 📄 theme-provider.tsx # Manejador de temas
└── 📄 README.md           # Documentación del proyecto
```

## 🛠 Instalación y Uso

1. **Clonar el repositorio**
   ```sh
   git clone https://github.com/tu-usuario/generador-remitos.git
   cd generador-remitos
   ```
2. **Instalar dependencias**
   ```sh
   pnpm install  # O npm install / yarn install
   ```
3. **Iniciar el proyecto**
   ```sh
   pnpm dev  # O npm run dev / yarn dev
   ```

## 🌙 Modo Oscuro

El dark mode se gestiona con `next-themes`. El `ThemeProvider` está en `main.tsx` para aplicarse globalmente.

```tsx
import { ThemeProvider } from './components/theme-provider';

ReactDOM.createRoot(document.getElementById('root')!).render(
  <React.StrictMode>
    <ThemeProvider defaultTheme="system" storageKey="vite-theme">
      <App />
    </ThemeProvider>
  </React.StrictMode>
);
```

## 🛠 Funcionalidades futuras

- 📌 Guardado de remitos en la nube.
- 📥 Importación de datos desde CSV o Excel.
- 📊 Estadísticas de remitos generados.

---

💡 **Contribuciones y feedback son bienvenidos!** 🚀

