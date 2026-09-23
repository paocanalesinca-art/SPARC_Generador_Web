# SPARC — Generador de Campañas para Maestrías UP

## Abrir en Visual Studio Code

1. Descarga y descomprime esta carpeta.
2. Abre la carpeta `SPARC_Generador_Web` en Visual Studio Code.
3. Abre `index.html`.
4. Para probarlo localmente, abre `index.html` en el navegador o usa la extensión **Live Server**.

## Publicarlo con un enlace público usando GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo: `sparc-generador-maestrias`.
2. Sube el archivo `index.html` y el archivo `.nojekyll`.
3. En GitHub entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda.
7. GitHub te mostrará una URL pública similar a:
   `https://TU-USUARIO.github.io/sparc-generador-maestrias/`

## Publicar desde Visual Studio Code con Git

Desde la terminal de VS Code, dentro de esta carpeta:

```bash
git init
git add .
git commit -m "Publicar generador SPARC"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/sparc-generador-maestrias.git
git push -u origin main
```

Después activa GitHub Pages desde **Settings → Pages** del repositorio.

## Nota

El generador funciona del lado del navegador. No guarda automáticamente los datos ingresados en una base de datos ni los comparte entre usuarios.
