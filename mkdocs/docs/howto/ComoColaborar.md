# Cómo contribuir a esta documentación

> La documentación principal del Libre DataCenter.

Desplegado en https://jaquerespeis.github.io/libreDataCenter/

## Contribuir

### Configurar ambiente
```
git clone git@github.com:Carbon-Offset-Open-Platform/mainPublicDoc.git
python3 -m venv venv
source venv/bin/activate
(venv) ~ pip install mkdocs-material
```

### Añadir contenido
1. Crea un archivo `.md` en la carpeta respectiva y escribe tu contenido utilizando formato Markdown. [Aprende más aquí.](https://www.markdownguide.org/).
1. Edita `mkdocs.yml` y agrega tu archivo a la sección `nav`.
1. Realiza un commit y sincroniza tu repositorio GIT.

### Probar y construir

Después de ingresar al entorno de Python, puedes ejecutar `serve` para ver los resultados localmente en tu navegador web:
```
source venv/bin/activate
(venv) ~ pip install mkdocs-material
mkdocs serve 
```

O, cuando todo esté listo, ejecuta `build` para crear el sitio web estático:
```
mkdoc build
```

