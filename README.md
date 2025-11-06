# Mini-Proyecto2-React

Aplicación React del Servicio Nacional de Aprendizaje (SENA) con información sobre programas de formación.

## 🚀 Características

- Diseño moderno y responsivo
- Navegación intuitiva
- Formulario de contacto
- Secciones informativas sobre programas

## 🛠️ Tecnologías Utilizadas

- React 19.2.0
- CSS3 con diseño moderno
- Create React App
- GitHub Pages para despliegue

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/Wuelcom/Mini-Projecto2-React.git
```

2. Instala las dependencias:
```bash
npm install
```

3. Ejecuta en modo desarrollo:
```bash
npm start
```

## 🚀 Despliegue en GitHub Pages

### Pasos para desplegar:

1. **Crea un repositorio en GitHub** con el nombre exacto: `Mini-Projecto2-React`

2. **Configura tu usuario de Git** (si no lo has hecho):
```bash
git config user.name "Tu Nombre Completo"
git config user.email "tu-email@github.com"
```

3. **Agrega el repositorio remoto**:
```bash
git remote add origin https://github.com/TU_USUARIO/Mini-Projecto2-React.git
```

4. **Sube el código al repositorio**:
```bash
git add .
git commit -m "Primera versión del proyecto"
git push -u origin main
```

5. **Ejecuta el despliegue**:
```bash
npm run deploy
```

### 📋 Notas Importantes:

- El proyecto está configurado para desplegar automáticamente en: `https://wuelcom.github.io/Mini-Projecto2-React/`
- Si tu nombre de usuario es diferente, actualiza la URL en `package.json` y `set-public-url.js`
- El comando `npm run deploy` ejecuta automáticamente:
  - `npm run build` (construye la aplicación)
  - `gh-pages -d build` (sube la carpeta build a la rama gh-pages)

### 🔧 Configuración del Repositorio en GitHub:

Después del primer despliegue:

1. Ve a Settings → Pages en tu repositorio de GitHub
2. En "Source" selecciona "Deploy from a branch"
3. Selecciona la rama `gh-pages` y carpeta `/ (root)`
4. Guarda los cambios

## 🎨 Personalización

Los colores y estilos se pueden modificar en:
- `src/App.css` - Estilos principales
- `src/index.css` - Estilos globales

## 📄 Scripts Disponibles

- `npm start` - Ejecuta en modo desarrollo
- `npm run build` - Construye para producción
- `npm run deploy` - Despliega a GitHub Pages
- `npm test` - Ejecuta las pruebas

## 📞 Contacto

Para soporte o preguntas, puedes contactar a través del formulario en la aplicación.

---

**¡Hecho con ❤️ por el equipo SENA!**
