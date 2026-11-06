# Ramas, merge y resolucion de conflicto
![Licencia](https://img.shields.io/badge/licencia-MIT-green)
![Version](https://img.shields.io/badge/version-v1.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

Uso de ramas y merge. Proyecto que consiste en crear una pagina web de dos archivos, abrir ramas sobre estas, unirlas y provocar conflictos para aprender a resolverlo

## Tabla de contenidos
- [Instalacion](#instalacion)
- [Uso](#uso)
- [Estado de las funciones](#estado-de-las-funciones)
- [Arquitectura](#arquitectura)
- [Contribucion](#contribucion)
- [Licencia](#licencia)
## Instalacion
```bash
git clone https://github.com/4SHA001/lab02-ramas
cd lab02-ramas
```
## Uso
1. Abrir el archivo `index.html` en el navegador.
2. Usar git log --oneline --graph , para visualizar los commits y las ramas

## Estado de las funciones
| Funcion | Estado | Prioridad |
|:--------|:------:|----------:|
| Creación de la rama menu | Listo | Alta |
| Unir la rama menu a main | Listo | Media |
| Provocar y resolver el conflicto | Listo | Media |
| Implementar JS interactivo | Pendiente | Baja |
## Hoja de ruta
- [x] Creación de la rama menu
- [x] Unir la rama menu a main
- [x] Provocar y resolver el conflicto
- [ ] Implementar JS interactivo

## Arquitectura

```mermaid
graph LR
    A[Inicializar el repositorio.] --> B[Crear los dos archivos]
    B --> C[Rama menu]
    C --> D[Merge menu a main]
    D --> E[Rama color-azul]
    E --> F[Rama color-rojo]
    F --> G[Merge color-azul a main]
    G --> J[Resolución Manual #0072ce]

```

## Contribucion
lee la guia de contribucion [https://github.com/4SHA001/new/blob/main/CONTRIBUTING.md](CONTRIBUTING.md).


## Licencia
Este proyecto usa la licencia MIT. Revisa el archivo [LICENSE](LICENSE).
## Autor
Hecho por **JOUSE** - [GitHub](https://github.com/4SHA001)