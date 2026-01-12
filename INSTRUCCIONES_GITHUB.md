# 📋 Instrucciones para Publicar en GitHub Pages

Sigue estos pasos para que tu página sea accesible online y puedas compartir el link:

## Paso 1: Crear una Cuenta en GitHub (si no tienes)
Visita: https://github.com

## Paso 2: Crear un Nuevo Repositorio
1. Click en el ícono `+` en la esquina superior derecha
2. Selecciona "New repository"
3. Nombre del repositorio: `para-ti` (o el nombre que desees)
4. Descripción: "Un mensaje romántico especial"
5. Selecciona "Public" (para que sea visible)
6. Click en "Create repository"

## Paso 3: Subir los Archivos
### Opción A - Usando Git en la Terminal

```bash
# Navega a la carpeta del proyecto
cd C:\Users\Admin\Desktop\Detalle

# Inicializar git
git init

# Agregar los archivos
git add .

# Hacer el primer commit
git commit -m "Primer commit: Página romántica"

# Conectar con GitHub (reemplaza TU_USUARIO con tu usuario)
git remote add origin https://github.com/TU_USUARIO/para-ti.git

# Cambiar rama a main
git branch -M main

# Subir los archivos
git push -u origin main
```

### Opción B - Arrastrar y Soltar (en GitHub)
1. En tu nuevo repositorio, selecciona "Add file" → "Upload files"
2. Arrastra los archivos `index.html` y `README.md`
3. Haz click en "Commit changes"

## Paso 4: Activar GitHub Pages
1. Ve a Settings (⚙️) en tu repositorio
2. Busca "Pages" en el menú izquierdo
3. En "Source", selecciona "main" o "master"
4. Click en Save
5. Espera 1-2 minutos...

## Paso 5: ¡Tu Link está Listo!
Tu página estará disponible en:
```
https://TU_USUARIO.github.io/para-ti
```

## Compartir el Link
Simplemente copia el link y envía por:
- ✅ WhatsApp
- ✅ Telegram
- ✅ Instagram
- ✅ Email
- ✅ Cualquier red social

## 💡 Consejos
- El repositorio debe ser **Public** para que GitHub Pages funcione (a menos que tengas GitHub Pro)
- Los cambios pueden tardar 1-2 minutos en reflejarse
- Puedes editar el HTML directamente en GitHub si necesitas cambios pequeños
- Personaliza el link y mensajes según lo desees

## 🆘 Problemas Comunes

### "No veo mi página después de activar Pages"
- Espera 2-3 minutos
- Presiona F5 o Ctrl+Shift+Del para limpiar caché

### "El link no funciona"
- Verifica que el repositorio sea Public
- Asegúrate de que `index.html` esté en la raíz
- Revisa la configuración de Pages

### "Cambios no se reflejan"
- GitHub puede tardar 1-5 minutos en actualizar
- Limpia el caché del navegador

---

¡Listo! Tu página romántica está en línea y lista para compartir 💕
