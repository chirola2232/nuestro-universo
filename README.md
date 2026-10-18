# Para Eliana ✧ Nuestro universo

Web romántica e interactiva, especialmente diseñada para abrirse en teléfonos con un código QR.

## Qué incluye
- 12 pantallas consecutivas con botón **Continuar**, **Atrás**, deslizamiento horizontal y reinicio.
- Estrellas animadas, nebulosas, meteoros suaves y un corazón de partículas alrededor de la imagen cósmica de Eliana.
- Una imagen cósmica realizada usando las fotografías de Eliana como referencia; dentro del corazón aparece ELIEL.
- Seis fotografías reales integradas como pequeños planetas/estrellas en una constelación interactiva.
- La carta personal repartida en tres pantallas legibles desde celular.
- Diseño adaptable, compatible con iPhone y Android, respetando la opción de reducir movimiento.
- Sitio 100% estático, sin contraseñas, bases de datos ni dependencias JavaScript externas. Las fuentes de Google Fonts requieren conexión; hay fuentes alternativas si no cargan.

## Ver antes de publicar
Abrí `index.html` desde una computadora o teléfono. Para evitar restricciones al abrir archivos locales, podés iniciar un servidor local con Python en la carpeta del proyecto:

```bash
python -m http.server 8000
```

Después entrá a `http://localhost:8000` desde ese equipo.

## Publicar en GitHub Pages
1. Entrá a https://github.com/new y creá un repositorio llamado `nuestro-universo`.
2. Entrá en él, elegí **Add file → Upload files** y subí el contenido del ZIP: `index.html`, `README.md` y **toda la carpeta `assets`**. No subas la carpeta contenedora `eliel-experiencia`: `index.html` debe quedar en la raíz.
3. Confirmá los cambios (**Commit changes**).
4. En **Settings → Pages**, sección **Build and deployment**, elegí `Deploy from a branch`, rama `main` y carpeta `/ (root)`, y guardá.
5. La dirección será similar a `https://TU-USUARIO.github.io/nuestro-universo/`. Puede demorar unos minutos en funcionar.
6. Abrila desde tu teléfono. Con la URL exacta se puede crear un QR imprimible para entregar de sorpresa.

## Privacidad y consentimiento
GitHub Pages publica estos materiales en Internet. **El nombre, la carta sobre el embarazo y las fotografías pueden quedar accesibles para otras personas**, incluso si el enlace se comparte solamente con Eliana. Asegurate de que ambos estén cómodos con esto antes de publicarlo. Si buscás un acceso privado de verdad, GitHub Pages público no es la opción adecuada.

## Personalización
- Texto: `index.html` (cada sección `class="scene"`).
- Imagen de galaxia central: `assets/eliana-universo.webp`.
- Fotografías: `assets/recuerdo-1.webp` a `recuerdo-6.webp`.
- Los textos no indican cuántos meses exactos habían pasado; solamente que recién comenzaban la relación.

Hecho con cariño, para ELIEL, Eliana y una historia que sigue creciendo.