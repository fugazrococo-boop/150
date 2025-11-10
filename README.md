# 📚 Seguimiento de Proyectos - Escuela Secundaria Técnica No. 150

Una aplicación web moderna y fácil de usar para gestionar proyectos escolares. Diseñada específicamente para la Escuela Secundaria Técnica No. 150.

## 🚀 Características

- ✅ **Interfaz moderna y responsive** - Funciona perfectamente en computadoras, tablets y móviles
- ✅ **Gestión completa de proyectos** - Crear, editar y eliminar proyectos
- ✅ **Filtros inteligentes** - Filtrar por disciplina, grado, grupo y estado
- ✅ **Estadísticas en tiempo real** - Visualiza el progreso de tus proyectos
- ✅ **Almacenamiento local** - Los datos se guardan automáticamente en tu navegador
- ✅ **Sin instalación** - Funciona directamente en el navegador
- ✅ **Sin dependencias externas** - No requiere Node.js ni servidores

## 📱 Vista previa

La aplicación incluye:
- Dashboard con estadísticas
- Formulario intuitivo para nuevos proyectos
- Tarjetas de proyecto con diseño moderno
- Sistema de filtrado avanzado
- Iconos y animaciones suaves

## 🛠️ Cómo usar la aplicación

### Opción 1: Abrir directamente (Más fácil)
1. Descarga todos los archivos del proyecto
2. Abre el archivo `index.html` en tu navegador
3. ¡Listo! La aplicación funcionará inmediatamente

### Opción 2: Publicar en la web

#### Método 1: GitHub Pages (GRATIS)
1. Crea una cuenta en [GitHub](https://github.com)
2. Crea un nuevo repositorio con tu nombre de usuario (ej: `tunombre.github.io`)
3. Sube estos archivos:
   - `index.html`
   - `index.css`
4. Tu aplicación estará disponible en: `https://tunombre.github.io`

#### Método 2: Netlify (GRATIS)
1. Ve a [Netlify](https://www.netlify.com)
2. Arrastra la carpeta del proyecto a la página
3. ¡Tu aplicación estará en línea en segundos!

#### Método 3: Vercel (GRATIS)
1. Ve a [Vercel](https://vercel.com)
2. Sube tu proyecto
3. Obtén tu URL personalizada

## 📁 Archivos necesarios

Para publicar tu aplicación, necesitas subir estos archivos:

**Obligatorios:**
- ✅ `index.html` - La aplicación principal
- ✅ `index.css` - Los estilos y diseño

**Opcionales (pero recomendados):**
- 📄 `README.md` - Este archivo de instrucciones
- 📄 `DEPLOY_GUIDE.md` - Guía detallada de publicación

## 🎯 Cómo funciona

### Gestión de Proyectos
1. **Crear proyecto**: Haz clic en "Nuevo Proyecto"
2. **Llenar formulario**: Completa todos los campos requeridos
3. **Guardar**: El proyecto se guarda automáticamente
4. **Editar**: Haz clic en "Editar" en cualquier tarjeta de proyecto
5. **Eliminar**: Usa el botón "Eliminar" con confirmación

### Filtros
- Filtra por **Disciplina** (Matemáticas, Ciencias, etc.)
- Filtra por **Grado** (1° a 6°)
- Filtra por **Grupo** (A, B, C, D)
- Filtra por **Estado** (Planificado, En Progreso, Completado, Cancelado)

### Estadísticas
- **Total de Proyectos**: Cuenta todos los proyectos
- **En Progreso**: Muestra proyectos activos
- **Completados**: Muestra proyectos finalizados

## 💾 Almacenamiento de datos

- Los datos se guardan automáticamente en tu navegador
- No se pierden al cerrar la página
- Funciona sin conexión a internet
- Cada usuario tiene sus propios datos locales

## 🌐 Compatibilidad

- ✅ Chrome (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera
- ✅ Móviles y tablets

## 🔧 Personalización

### Cambiar colores
Edita el archivo `index.css` y modifica las variables de color:
```css
:root {
    --primary-color: #3B82F6;
    --secondary-color: #10B981;
    --accent-color: #8B5CF6;
}
```

### Agregar más disciplinas
En el archivo `index.html`, busca la sección `Disciplines` y agrega:
```javascript
const Disciplines = [
    'Matemáticas', 'Ciencias', 'Lenguaje',
    'Nueva Disciplina 1', 'Nueva Disciplina 2'
];
```

### Agregar más profesores
Busca la sección `Teachers` y modifica:
```javascript
const Teachers = [
    'Profesor 1', 'Profesor 2', 'Profesor 3',
    'Nuevo Profesor'
];
```

## 🆘 Solución de problemas

### La aplicación no carga
- ✅ Verifica que ambos archivos (`index.html` y `index.css`) estén en la misma carpeta
- ✅ Asegúrate de tener conexión a internet (para los CDN)
- ✅ Prueba con otro navegador

### Los datos no se guardan
- ✅ Verifica que tu navegador permita localStorage
- ✅ No uses modo incógnito
- ✅ Reinicia el navegador

### Problemas de diseño
- ✅ Actualiza tu navegador a la última versión
- ✅ Limpia la caché del navegador
- ✅ Verifica que `index.css` se esté cargando correctamente

## 📞 Soporte

Si tienes problemas:
1. Revisa esta guía
2. Verifica los archivos necesarios
3. Prueba los métodos de solución de problemas
4. La aplicación es muy estable y debería funcionar sin problemas

## 🎉 ¡Listo para usar!

Tu aplicación de seguimiento de proyectos está completamente funcional y lista para publicar. ¡Simplemente elige tu método de publicación favorito y comparte tu URL con los usuarios!

---

**Escuela Secundaria Técnica No. 150** - Tecnología al servicio de la educación 🎓
