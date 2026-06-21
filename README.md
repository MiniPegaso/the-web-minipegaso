# Proyecto The Web

Proyecto académico para el curso de NodeJS, Universidad Galileo, 2026.

## Objetivo

Crear un sitio web informativo, visualmente atractivo y publicado en GitHub Pages, explicando algunos pilares del funcionamiento de Internet y la Web.

## Páginas del sitio

- `index.html`: explica qué es Internet, qué es la World Wide Web y el modelo cliente-servidor.
- `infraestructura.html`: explica DNS, direcciones IP y el viaje de una solicitud web.
- `protocolos.html`: explica HTTP, HTTPS y qué ocurre al escribir una dirección con `https://`.

## Requerimientos cubiertos

- 3 páginas HTML conectadas.
- Archivo CSS externo en `css/style.css`.
- Explicación de modelo cliente-servidor.
- Explicación de DNS.
- Explicación de direcciones IP.
- Explicación de protocolos HTTP y HTTPS.
- Diseño responsive usando media queries.
- Estilo visual inspirado en MiniPegaso, usando colores llamativos.

## Git Workflow utilizado

Rama principal:

```bash
git branch -M main
```

Rama para contenido:

```bash
git checkout -b feature/contenido
```

Commit de contenido:

```bash
git add .
git commit -m "Agregar contenido y estilos del proyecto The Web"
```

Luego se crea un Pull Request en GitHub desde:

```text
feature/contenido → main
```

En el Pull Request se documenta que se agregaron las páginas, los estilos y la explicación de los temas solicitados.

## Publicación en GitHub Pages

En GitHub:

```text
Settings → Pages → Deploy from branch → main → /root → Save
```

Después GitHub genera el enlace público del sitio.

## Autor

César Velasquez  
Universidad Galileo  
Ing. Alejandro Córdova  
2026
