# MiWeb – Sitio Web con MkDocs + GitHub Pages

Este repositorio contiene un sitio web estático construido con MkDocs y el tema Material.  
Se publica automáticamente en GitHub Pages y utiliza un dominio personalizado con HTTPS.

## Sitio en producción
https://www.danigarcia-sec.xyz

## Tecnologías utilizadas
- Ubuntu + entorno virtual Python
- MkDocs + Material
- Git y GitHub
- DNS personalizado + Certificado SSL automático (Let's Encrypt)

## Estructura del proyecto
MiWeb/
├── .github/workflows/ # Despliegue automatizado con GitHub Actions
│ └── deploy.yml
│
├── docs/ # Contenido del sitio en formato Markdown
│ ├── index.md
│ ├── sobre-mi.md
│ ├── contacto.md
│ └── proyectos.md
│
├── CNAME # Dominio personalizado para GitHub Pages
├── mkdocs.yml # Configuración del sitio (tema, navegación, ajustes)
├── requirements.txt # Dependencias utilizadas para reproducir el entorno
└── .gitignore # Exclusiones de control de versiones
