# Repaso General — Taller de repaso y consolidación en C++

**Actividad 6 — Taller práctico de repaso y consolidación en C++** · Laboratorio de Programación · 5.º 3.ª A-B · E.E.S.T. N.º 1 «Eduardo Ader»

Suite unificada de tres retos de bajo nivel en C++:

| Reto | Tema | Núcleo del código |
|------|------|-------------------|
| 1 | Recursividad (suma de 1 a N) | caso base `if (n <= 0) return 0;` |
| 2 | Búsqueda secuencial en un arreglo contiguo | `break` al encontrar el valor |
| 3 | Intercambio de variables con punteros | variable `temporal` y desreferenciación `*` |

- Estudiante: **Alexis Maier**
- Integrantes del grupo: Alexis Maier (individual)

## Datos institucionales

- **Institución:** E.E.S.T. N.º 1 «Eduardo Ader» — Vicente López
- **Curso:** 5.º 3.ª A-B
- **Materia:** Laboratorio de Programación (LPR)
- **Profesor:** Prof. York
- **Actividad:** 6 — Taller práctico de repaso y consolidación de C++

## Presentación de la Actividad

Taller de consolidación de los contenidos de la materia: estructura, punteros y control de flujo, organizado en retos con su informe y autoevaluación.

## Integrantes y roles

| Integrante | Rol / tarea asignada | Aporte individual |
|---|---|---|
| Alexis Maier | Resolución de los retos, documentación, manuales y control de versiones | [repaso-general](https://github.com/alitomaier2010-netizen/repaso-general) |

## Requisitos e instalación

1. **Git** instalado para clonar el repositorio.
2. **Editor de código** (VS Code con extensiones de C/C++, o Visual Studio Community).
3. **Compilador g++** (MinGW-w64 / MSYS2) agregado al `PATH` del sistema.
4. Clonar y situarse en el directorio:

```bash
git clone https://github.com/alitomaier2010-netizen/repaso-general.git
cd repaso-general
```

## Estructura

```
repasogeneral/
├── .gitignore
├── LICENSE
├── README.md
├── capturas/
│   ├── ejecucion_repasogeneral.png
│   └── traza_memoria.png
├── docs/
│   ├── InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf
│   ├── CHANGELOG.md
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf
│       └── manual_usuario_v1.0.0.pdf
└── src/
    └── main.cpp
```

## Compilar y ejecutar (PowerShell)

```
g++ src/main.cpp -o src/repasogeneral.exe
.\src\repasogeneral.exe
```

**Espejo automático:** https://gitlab.com/Alitopro/repaso-general
