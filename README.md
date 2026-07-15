# Sitio web de Cuadre RD

Sitio estático listo para GitHub Pages de Cuadre RD, una app iOS de organización financiera personal para usuarios en la República Dominicana.

Incluye:

- `index.html` - página pública principal de la aplicación
- `privacy.html` - Política de Privacidad pública
- `terms.html` - Términos de Servicio públicos
- `styles.css` - estilos responsivos compartidos
- `script.js` - navegación móvil, estado del header y animaciones ligeras
- `assets/` - asset visual ligero

## 1. Abrir localmente

No requiere backend, framework ni build step.

Puedes abrir `index.html` directamente en el navegador o levantar un servidor estático simple:

```bash
python3 -m http.server 8000
```

Luego visita:

```text
http://localhost:8000/
```

## 2. Subir a GitHub

Sube estos archivos a la raíz del repositorio:

```text
index.html
privacy.html
terms.html
styles.css
script.js
README.md
assets/
```

Con git:

```bash
git add .
git commit -m "Update Cuadre RD website in Spanish"
git push
```

## 3. Activar GitHub Pages

1. Abre el repositorio en GitHub.
2. Ve a **Settings**.
3. Entra a **Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda los cambios.

GitHub publicará el sitio cuando termine el deployment de Pages.

## 4. URLs para Google Cloud OAuth

Usa estas URLs públicas en la configuración de OAuth de Google Cloud:

```text
Application homepage: https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/
Privacy Policy: https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/privacy.html
Terms of Service: https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/terms.html
```

Para este repositorio:

```text
Application homepage: https://janmbaez.github.io/Cuadre-RD/
Privacy Policy: https://janmbaez.github.io/Cuadre-RD/privacy.html
Terms of Service: https://janmbaez.github.io/Cuadre-RD/terms.html
```
