# Publicar esta demo gratis en GitHub Pages

## 1. Crear una cuenta de GitHub
Entra en GitHub y crea una cuenta si todavía no tienes una.

## 2. Crear un repositorio
Pulsa **New repository** y usa, por ejemplo:

`olympic-fitness-concept`

Opciones recomendadas:
- Public
- No hace falta marcar "Add a README", porque este proyecto ya incluye uno.

## 3. Subir los archivos desde la web
Dentro del repositorio:

**Add file → Upload files**

Sube:
- `index.html`
- `styles.css`
- `script.js`
- `README.md`
- `DEPLOY.md`

Después pulsa **Commit changes**.

## 4. Activar GitHub Pages
Ve a:

**Settings → Pages**

En **Build and deployment**:
- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

Guarda los cambios.

La URL normalmente tendrá esta forma:

`https://TU-USUARIO.github.io/olympic-fitness-concept/`

## 5. Mantener la demo segura
Mientras sea un concepto no autorizado:
- Mantén visible el aviso "CONCEPTO NO OFICIAL".
- Mantén `<meta name="robots" content="noindex,nofollow">`.
- No uses el logo oficial ni fotografías del negocio sin permiso.
- No recojas datos personales.
- No simules reservas reales.

## 6. Si el negocio acepta la propuesta
Crea una versión de producción:
- valida todos los datos;
- utiliza recursos autorizados;
- añade textos legales;
- conecta dominio y contacto real;
- configura SEO y analítica;
- idealmente trabaja en un repositorio independiente del concepto de portfolio.

## Comandos Git opcionales

Si prefieres subirlo por terminal:

```bash
git init
git add .
git commit -m "Initial concept website"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/olympic-fitness-concept.git
git push -u origin main
```
