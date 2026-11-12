# Guía para subirlo a GitHub (no se sube; es solo para ti)

Borra este archivo antes del primer commit, o añade `GITHUB_GUIA.md` a `.gitignore`.

## 1. Crear el repositorio vacío
1. github.com → **New repository**.
2. Nombre: `laboratorio-ia` (minúsculas, sin espacios).
3. Descripción: `Apuntes interactivos de IA para tocar: mueve los controles, rompe cosas y mira qué pasa.`
4. Público. **No** marques README, .gitignore ni licencia (ya los tienes).

## 2. Subirlo desde la carpeta
```bash
cd laboratorio-ia
git init -b main
git add .
git commit -m "Primera versión del Laboratorio de IA"
git remote add origin https://github.com/TU-USUARIO/laboratorio-ia.git
git push -u origin main
```

## 3. Activar la web (GitHub Pages)
Settings → Pages → *Source*: **Deploy from a branch** → rama `main`, carpeta `/ (root)` → Save.
En 1-2 minutos estará en `https://TU-USUARIO.github.io/laboratorio-ia/`.

## 4. Pulir la portada del repo
- **About** (engranaje arriba a la derecha): pega la descripción, la URL de la demo y marca *Use your GitHub Pages website*.
- **Topics** sugeridos: `machine-learning`, `educacion`, `interactive`, `cybersecurity`, `data-science`, `javascript`, `html`, `spanish`.
- Sustituye `TU-USUARIO` y `TU-EMAIL` en el README.
- Añade una captura de pantalla a la carpeta `img/` y enlázala bajo el título del README (la imagen es lo que más hace que alguien pinche).
- **Releases** → crea `v1.0.0` para tener algo citable.

## 5. Comprobar antes de compartir
- [ ] La demo carga y las seis pestañas funcionan en móvil.
- [ ] No hay datos personales ni rutas locales en el código.
- [ ] El enlace a la demo del README funciona.
- [ ] Probado en modo oscuro.
